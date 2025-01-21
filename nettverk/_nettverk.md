# Applied networks

## Internet architecture

- Network of networks
- Access network $\rightarrow$ regional network $\rightarrow$ core network $\rightarrow$ regional $\dots$
- People connect their home network to the internet through ISP networks
- ISP networks connected through IXP (Internet exchange point)
- Also possible to have peering links, that connect ISP networks without going through IXP
- Tiers of ISP
  - As many tiers as we want
  - Providers send from tier $N$ to customer at tier $N+1$
  - Can also connect to Content Delivery Service (CDS)
  - Look through more
- Routers interconnect various network technologies
- Network structure in 2d
  - Access networks/points
    - Connects users
  - Network edge
    - Application on end systems/hosts
  - Network core
    - Network of networks
  - Routers
    - Interconnect routers
    - Forward packets
  - Packets
    - Chunks of data
- Internet protocol layer
  - App (message)
  - Transport (segment)
  - Network (packet/datagram)
  - Link (frame)
  - Physical (bit)
- Network neutrality
  - Principle contributing to everyone's ability to use the Internet with equal conditions
  - Implemented in common European ruleset
- Internet in 3D (protocol layer)
  - Network edge devices read all layers
  - Switches read physical and link layer
  - Routes read physical, link and network layer
- Service models
  - Service model of a layer is services it offers to the above layers
- Performance parameters
  - Quantifiable Quality of Service (QQoS)
  - Throughput
    - Experienced speed
    - Rate at which bits are transferred between sender and receiver
    - Capacity
      - Maximum possible throughput
  - Delay
    - Measured by looking at Round trip time (RTT)
    - 4 sources
    - Nodal processing
    - Queuing
    - Transmission (packet length / link bandwidth)
    - Propagation (length of physical link / propagation speed)
  - Packet loss
    - Packet arrives to full queue
    - Retransmission
  - What does it tell us?
    - Download throughput
    - Upload throughput
    - Round-trip time
- Internet approach bottom up
  - Transmission of bits
  - Bits are *framed* and transmitted over link which is point-to-point or broadcast, using MAC addr
  - Frame transports *IP datagram* one hop towards its destination
  - IP datagram contains IP addresses of sender and receiver
  - Routers forward IP datagrams hop by hop using forwarding tables built by routing protocols
  - Provided IP service is connectionless, best-effort service
  - End-end transport layer adds error and flow control and congestion control
  - Domain Name System translates between names and IP addresses
  - Distributed applications run only in end systems and exchange data accross network

## IP addressing

- IP addresses
  - Consists of 2 parts
  - Network part
  - Interface part
  - Size of parts can vary
  - Interface
    - Connection between host/router and physical link
    - Routers typically multiple interfaces
    - Hosts typically one active interface
  - Link-local address
    - Interface chooses own IP address
    - Used when not DHCP in router
- Subnetting
  - IP addess: subnet part + host part
  - Subnets
    - Can physically reach each other without intervening router
    - Device interfaces with same subnet part of IP address
    - Subnet mask (/n) define use of address space
    - To determine subnets, detach each interface with its host or router, and count islands
  - One IP address for broadcast (host = 1s), and one for network address (host = 0s)
  - IP address divided in 3:
    - Address from ISP
    - Subnet
    - Interface
    - (address + subnet = network part)
- IPv6
  - 128 bits
  - 8 groups of 4 hex ciphers
  - $\text{x:x:x:x:x:x:x:x}$ (x is 2 bytes)
  - /32 subnet is smallest IPv6 assignment an end user might receive with current policy
  - E.g. end user will be assigned $2^{32} \approx 4\cdot 10^9$ IPv6 addresses
  - End user assigned smalles IPv6 assignment gets a single IPv4 address
  - Notation
    - Leading 0 suppression
      - If first hex in a cipher is 0, it can be removed (at least 1 cipher in total)
      - 00FF can be rewritten as FF
    - Zero compression
      - Contiguous series of cipher blocks set to 0 can be replaced with ::
      - Can only be applied once per IP address to avoid ambiguity
      - E.g. FE80:0:0:0:2AA:FF:FE9A:4CA2 can be compressed to  FE80::2AA:FF:FE9A:4CA2
  - Network interface card MAC address
    - Interface MAC address embedded in IPv6 address
      - ![alt text](image.png)
    - Bad because MAC address should be kept private

## Internet end-end

- Instance: browser loading page from google.com

1. Laptop connecting to net work gets IP address, address of first hop router, address of DNS server using DHCP
   - Dynamic Host Configuration Protocol (DHCP)
     - Client broadcasts DHCP messages on local subnet using IP
     - Dyncamically gets IP address of client, first-hop router, DNS etc.
     - DHCP relays forwards message to DHCP server
2. Before sending HTTP request, IP address of google.com is resolved using DNS
   - Address Reslution Protocol (ARP) finds mapping between IP and MAC addr within LAN
   - ARP request broadcasted
   - Nodes create their ARP tables without intervention from net administrator
   - [IP addr, MAC addr, TTL]
3. To get MAC address of first-hop router, laptop uses ARP
4. Laptop sends DNS query using UDP
   - Domain Name System (DNS) translates between names and IP addresses
5. Routers forward IP packets
6. DNS server replies with IP address of google.com
7. To download page from google.com, TCP is used to set up connection
   - Transmission Control Protocol (TCP) delivers reliable byte stream
   - Point-to-point full duplex
     - One sender, one receiver
   - Connection-oriented
     - Handshake initialization
   - Error control
     - Bit error, segment error
   - Flow control
     - Sender will not overwhelm receiver
   - Congestion control
     - Sender adjusts transmission depending on network load
   - Port numbers used for demultiplexing to relevant application processes
8. Laptop can then send HTTP request
9. Server returns default page at google.com using HTTP response

- Instanse: email sent from one email client to another