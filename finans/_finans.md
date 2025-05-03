# Finance for Science and Technology Students

## **Finance for Science and Technology Students - Chapter 1: Introduction**

**Lecturers: Felipe Van de Sande Araujo, Anne Neumann, Carlos Miguel Dos Santos Oliveira**  
**Date: January 8, 2025**  

---

### **1. Course Overview**

- Introduces **finance** as a scientific discipline and a practical tool for financial decision- making.  
- Assumes **no prior knowledge** of finance but builds on students' **quantitative skills**.  
- Covers:  
  - **Time value of money**  
  - **Accounting concepts**  
  - **Microeconomics** (basic elements)  

---

### **2. Course Orientation**

- **Conceptual rather than technical**:
  - How should investment decisions be made?
  - What determines the cost of capital?
  - What is market efficiency?
  - How are options priced?
- Some **technical aspects** included for deeper understanding.  

---

### **3. Finance as a Science**

- Studies **how people allocate scarce resources** under **uncertainty**.  
- A social science, but closely related to natural sciences due to its **quantitative approach**.  
- Uses:  
  - **Mathematical models**  
  - **Empirical testing**  
  - **Application to real- world problems**  

#### **Key Approaches in Finance**

1. **Managerial Finance**  
   - Solves **practical** financial decision- making problems.  
   - "Approximate answer to a precise problem."  
2. **Financial Economics (Theory of Finance)**  
   - Develops **general knowledge** and principles.  
   - "Precise answer to an approximate problem."  

---

### **4. Nobel Prizes in Finance**

- Several economists awarded for their **pioneering work**:  
  - **Harry Markowitz, Merton Miller, William Sharpe (1990)** – Portfolio theory.  
  - **John Nash (1994)** – Game theory.  
  - **Robert Merton, Myron Scholes (1997)** – Derivative pricing models.  

---

### **5. Key Tools in Finance**

- **Theoretical models** → Predict market behaviors.  
- **Empirical testing** → Compare theory to real- life data.  
- **Practical application** → Use theories in investment, risk management, etc.  

Example:  

- **Option Pricing**  
  - Develop a **mathematical model** (Black- Scholes).  
  - Test it against **market data**.  
  - Use it in **trading and risk management**.  

---

### **6. Finance vs. Natural Sciences**

- Natural sciences:
  - **Precise predictions** from controlled experiments.
- Finance:
  - **Human behavior** → Noisy real- world data.
  - **Market efficiency** makes predictions difficult.

**Example Comparisons**:  

1. **NASA’s Wilkinson Microwave Anisotropy Probe**  
   - Cosmic background radiation **measured with extreme precision**.  
2. **Risk- Return Relationship in Stock Markets**  
   - Financial models (e.g., Capital Asset Pricing Model) show **high variability**.  

---

### **7. Market Efficiency**

- Efficient Market Hypothesis (EMH):  
  - **Stock prices reflect all available information**.  
  - Future price changes **unpredictable**.  
  - **Accurate predictions self- destruct** (new info immediately priced in).  

Samuelson's summary:  
> “Properly anticipated prices fluctuate randomly.”  

---

### **Finance for Science and Technology Students - Chapter 2: Time Value of Money**

**Lecturers: Felipe Van de Sande Araujo, Anne Neumann, Carlos Miguel Dos Santos Oliveira**  
**Date: January 8, 2025**  

---

### **1. Time Value of Money**

- **Money now is worth more than money later**.  
- Expressed in the **risk- free interest rate**.  
- Reasons:  
  1. **Time preference (human impatience)** – Preference for immediate consumption.  
  2. **Investment opportunities** – Sacrificing consumption today allows for higher future returns.  

**Implication:**  

- Cash flows at different times **cannot be directly compared**.  
- Need **compounding** (moving forward) or **discounting** (moving backward).  

---

### **2. Compounding & Discounting**

- **Compounding**: Earning interest on interest.  
  - Example: €100 at 10% yearly interest:  
    - Year 1: €110  
    - Year 2: €121  
    - Year 3: €133.10  

  **Formula**:  
 $FV_T = PV (1 + r)^T$
  - **FV**: Future Value
  - **PV**: Present Value  
  - **r**: Interest rate  
  - **T**: Number of periods  

- **Discounting**: Moving money back in time.  
 $PV = \frac{FV_T}{(1 + r)^T}$

---

### **3. Compounding Frequency**

- Interest can be compounded **more frequently** than annually:  
  - **Semi- annual** (twice per year)  
  - **Quarterly** (four times per year)  
  - **Continuous**  

**Future Value with multiple compounding periods**:
$FV_T = PV \left(1 + \frac{r}{n}\right)^{Tn}$
where **n** is the number of compounding periods per year.

**Continuous Compounding**:  
$FV_T = PVe^{rT}$
where **e ≈ 2.718** (Euler’s number).  

---

### **4. Logarithmic Returns**

- **Continuously compounded returns**:  
 $\ln\left(\frac{S_T}{S_0}\right) = rT$
  where$S_n$is daily stock price on day **n**
- **Advantages**:  
  - **Additive over time**: Weekly return = sum of daily returns.
    - $\ln\left(\frac{S_1}{S_0}\times \frac{S_2}{S_1} \right) = \ln\left( \frac{S_1}{S_0}\right) + \ln\left(\frac{S_2}{S_1} \right) = \ln e^{r_1} + \ln e^{r_2} = r_1 + r_2$
  - **Not additive across investments** (log transformation is non- linear).  

---

### **5. Annuities and Perpetuities**

- **Annuity**: Series of payments for **finite** years.  
  - Example: Retirement pension.  
  - **Formula for present value**:  
   $
    PV = A \times \left(\frac{1 - (1 + r)^{- n}}{r}\right)
   $
- **Perpetuity**: Infinite payments ($n\rightarrow \infty$).  
  - Example: University endowments.  
  - **Formula**:  
   $
    PV = \frac{A}{r}
   $
- **Growing perpetuity (Gordon Growth Model)**:  
 $
  PV = \frac{A}{r - g}
 $
  where **g** is growth rate

---

### **6. Risk and Valuation**

- **Value** = **Discounted sum of future cash flows**:  
 $
  Value = \sum \frac{Exp[\text{Cash Flow}_t]}{(1 + \text{discount rate}_t)^t}
 $
- **Three Approaches to Handle Risk**:  
  1. **Risk- adjusted discount rate**  
  2. **Certainty equivalent cash flows**  
  3. **Risk- neutral probabilities** (used in option pricing).  

---

### **7. Course Benefits**

- **Financial literacy**:  
  - Understand Nobel- winning finance concepts.  
  - Evaluate investments & financial products.  
- **Practical skills**:  
  - Assess risk.  
  - Understand investment decisions.  
  - Be informed in financial markets.  

**Key Questions Answered**:

- Should pension funds use active investment strategies?  
- Why are options riskier than stocks?  
- How can financial engineering create new products?  

---

### **Finance for Science and Technology Students - Chapter 2: Fundamental Concepts and Techniques**  

**Lecturer: Anne Neumann**  
**Date: January 16, 2025**  

### **Lecture Plan**

1. Investment analysis  
2. The accounting representation of the firm  
3. Discounting in investment analysis  
4. Where does "risk aversion" come from?  
5. The notion of utility  
6. A simple model of financial markets  
7. Fisher’s analyses  
8. Some practical aspects of financial markets and trading  

---

### **Recap from Lecture 1**

- **Time value of money**:  
  - €1 today is worth more than €1 tomorrow.  
  - A safe €1 is worth more than a risky €1.  
- **Future value & Present value**  
- **Risk- free rate**  
- **Discounting & Compounding**  
- **Annuities and Perpetuities**  

---

### **The Accounting Representation of the Firm**

- **Accounting values in finance:**  
  - **Market values** used when possible.  
  - **Book values** used when necessary.  
- **Book values** reflect recorded transactions, while **market values** fluctuate.  
- **Financial statements**:  
  - **Income Statement** (Revenue, Expenses, Profit)  
  - **Balance Sheet** (Assets, Liabilities, Equity)  

---

### **Discounting in Investment Analysis**

- **Key financial decision- making tool**  
- **Project evaluation example (ZX Co.)**:  
  - Investment of €195M  
  - Sales revenue: €250M, €500M, €250M over 3 years  
  - Operating costs and depreciation considered  
- **Net Present Value (NPV)**  
  - NPV > 0 → Accept the project  
  - Uses discount rate (Cost of Capital)  
  - NPV accounts for time and risk, unlike book return  

---

### **Financial Representation of Investment**

- **Three adjustments to accounting view**:  
  1. Replace depreciation with **cash outflows**.  
  2. Include **changes in net working capital**.  
  3. Remove **sunk costs** (e.g., prior test expenses).  
- **Decision rule:**  
  - Accept project if **NPV > 0**.  

---

### **Other Investment Criteria (Less Reliable than NPV)**

- **Book Rate of Return** → Affected by depreciation, not a true measure.  
- **Payback Period** → Ignores time value of money.  
- **Internal Rate of Return (IRR)**  
  - Discount rate where NPV = 0.  
  - Decision rule: Accept if **IRR > Cost of Capital**.  
  - Works only for "normal" cash flows.  

---

### **Economic Depreciation & Risk Aversion**

- **Economic depreciation**: Change in project value over time.  
- **Risk aversion**:  
  - People prefer certainty over risk.  
  - **Utility function** explains decision- making.  
  - **Concave utility functions** → Diminishing marginal utility.  
- **Indifference Curves**  
  - Represent combinations of choices with the same utility.  

---

### **Fisher's Investment Analysis**

- **Financial markets allow better decision- making**.  
- **Without financial markets**:  
  - Investment decisions depend on personal preferences.  
- **With financial markets**:  
  - **Investment and consumption decisions are separate.**  
  - **Optimal investment plan**: Select all projects where **NPV ≥ 0**.  
  - Fisher separation: Managers do not need to know individual preferences.  

---

### **Financial Markets in Practice**

#### **Four Main Functions**

1. **Facilitating flow of funds** (from surplus units to deficit units).  
2. **Price determination** (time value of money, market price of risk).  
3. **Providing liquidity and marketability** (ease of asset exchange).  
4. **Settlement and clearing** (secure transactions).  

#### **Types of Finance**

- **Direct Finance** → Issuer sells directly to buyers.  
- **Indirect Finance** → Financial intermediaries (e.g., banks).  
- **Stock Market Transactions** → Trading through brokers and clearing houses.  

---

### **Financial Intermediaries**

- **Transform flow of funds** (matching lenders with borrowers).  
- **Reduce transaction costs** (banks, investment services).  
- **Provide investment services**:  
  - **Brokers** → Facilitate transactions.  
  - **Investment banks** → Issue securities, corporate deals.  
  - **Mutual funds** → Diversified investments.  

---

### **Trading on the Exchange**

#### **Steps to Invest in the Stock Market**

1. **Open a brokerage account.**  
2. **Choose position**:  
   - **Long** (buy and hold).  
   - **Short** (sell borrowed shares, buy later).  
3. **Place an order**:  
   - **Limit order** (price control, not always executed).  
   - **Market order** (executed at best available price).  
   - **Stop- loss order** (sell automatically at a set price).  
4. **Order Execution**  
   - Broker checks account.  
   - Order sent to market.  
   - If matched, executed by clearing house.  

---

### **Key Takeaways**

- **Investment analysis** relies on NPV for decision- making.  
- **Financial markets** enable efficient allocation of resources.  
- **Risk aversion** impacts decision- making.  
- **Financial intermediaries** improve market efficiency.  
- **Stock trading** involves brokers, clearing houses, and order types.  

---

## Finance for Science and Technology Students - Chapter 3.1: Modern Portfolio Theory

### Recap from Lecture 2

- Two basic rules:
  - €1 today is worth more than €1 tomorrow.
  - A safe €1 is worth more than a risky €1.
- Time value of money, risk- free rate, discounting, and compounding.
- Introduction to accounting: Income statement & Balance sheet.
- Investment analysis and decision criteria.
- Utility and risk aversion: Combining risky choices reduces risk.
- **Further reading:**
  - Fisher’s optimal investment analysis.
  - Financial system functions, intermediaries, and trading.

### Plan for this Lecture

- Risk and return.
- Measuring risk.
- Portfolio risk: Mean & variance.
- Portfolio selection and pricing.
- Markowitz efficient portfolios.
- Capital Market Line.

### Risk and Return

- Investment choices involve uncertainty.
- Risk means future outcomes deviate from expected values.
- **Ways to express risk:**
  - Security prices in financial markets.
  - Returns, calculated as:
   $
    r_{it} = \frac{P_{i,t+1} - P_{i,t} + \text{Div}_{t+1}}{P_{it}}
   $
  - Distributional properties of returns.

### Measuring Risk

- **Standard deviation and variance:** Common measures of dispersion.
  - Historical vs. forward- looking variance.
  - Disadvantages: Treats up/down deviations equally, ignores skewness/kurtosis.
- **Portfolio risk calculation:**
  - Portfolio risk is often lower than individual asset risks.
  - **Expected return of a portfolio**:
   $
    E [r_p] = \sum_{i=1}^{I} x_i E[r_i]
   $
  - **Portfolio variance:**
   $
    \sigma^2_p = \sum_{i=1}^{I} x_i^2 \sigma^2_i + 2 \sum_{i \neq j} x_i x_j \sigma_{ij}
   $
  - **Diversification effect:** Covariances influence portfolio risk.

### Covariance and Correlation

- **Covariance formula:**
 $
  \sigma_{ij} = \sum_{n=1}^{N} \pi_n (r_{ni} - E[r_i]) (r_{nj} - E[r_j])
 $
- **Correlation coefficient:**
 $
  \rho_{ij} = \frac{\sigma_{ij}}{\sigma_i \sigma_j}
 $
- Lower correlation leads to higher diversification benefits.

### Efficient Portfolios

- **Markowitz Model (1952):** Investors should optimize for risk- adjusted returns.
- **Capital Market Line (CML):** The optimal risk- return trade- off when risk- free assets exist.
- **Market Portfolio:** All investors hold a combination of the risk- free asset and the market portfolio.

---

## Finance for Science and Technology Students - Chapter 3.2: Capital Asset Pricing Model

### Recap: Capital Market Line (CML)

- James Tobin (1958): Optimal portfolios consist of:
  1. A unique risky asset combination.
  2. Allocation between the risky portfolio and a risk- free asset.
- **Key insight:** Risk- free lending/borrowing changes the efficient frontier.

### Market Equilibrium

- **Efficient portfolio M:** Investors hold a mix of M and risk- free assets.
- **Market portfolio:** All risky assets held in market value proportions.

### Capital Asset Pricing Model (CAPM)

- **CAPM equation:**
 $
  E [r_i] = r_f + \beta_i (E [r_m] - r_f)
 $
- **Beta ($\beta$) interpretation:**
  - **Systematic risk:** Risk that cannot be diversified away.
  - **Measured as:** Sensitivity of stock returns to market returns.
  - **Security Market Line (SML):** Relation between expected return and beta.

### Empirical Tests of CAPM

- **Regression approach:**
  - **First pass:** Estimate individual stock betas.
  - **Second pass:** Test whether expected returns align with CAPM predictions.
- **Findings:**
  - CAPM predicts linear relation between return and beta.
  - Empirical data shows some deviations (e.g., low- beta stocks have higher returns than predicted).

### Alternative Models: Arbitrage Pricing Theory (APT)

- **APT vs. CAPM:**
  - **APT:** Multiple risk factors influence returns.
  - **CAPM:** Market risk is the only relevant factor.
- **APT formula:**
 $
  E [r_i] = r_f + \sum_{k} \lambda_k b_{ik}
 $
- **Empirical applications:** APT often explains asset prices better than CAPM.

---

## Finance for Science and Technology Students - Chapter 4: Market Efficiency

### Efficient Market Hypothesis (EMH)

- **Definition (Fama, 1970):** Market prices fully reflect available information.
- **Forms of Efficiency:**
  1. **Weak- form:** Prices reflect all past market data (no predictable patterns).
  2. **Semi- strong:** Prices reflect all publicly available information (no advantage in fundamental analysis).
  3. **Strong- form:** Prices reflect all information, including private (no insider trading advantage).

### Implications of EMH

- **No free lunch:** Excess returns cannot be systematically earned.
- **Autocorrelation test:** No correlation between past and future returns.
- **Investment funds:** No fund should consistently outperform after adjusting for risk.
- **Price adjustments:** Prices should react instantly and unbiasedly to new information.

### Behavioral Challenges to EMH

- **Cognitive biases affecting investors:**
  - Overconfidence: Investors trade too much.
  - Familiarity bias: Preference for known stocks.
  - Herding behavior: Following market trends blindly.
- **Empirical findings:**
  - Momentum effect: Stocks that performed well continue performing well.
  - Value effect: Stocks with high book- to- market ratios tend to outperform.

### Testing Market Efficiency

- **Empirical evidence:**
  - Short- term price movements are random (supports weak- form EMH).
  - Some anomalies persist (challenges semi- strong form).
  - Insiders often outperform (challenges strong- form efficiency).
- **Market anomalies:**
  - January effect: Stocks tend to rise in January.
  - Small firm effect: Small- cap stocks tend to outperform.

### Conclusion

- Market efficiency is largely supported, but some persistent anomalies exist.
- Behavioral finance challenges pure EMH assumptions.
- Investors should focus on diversified portfolios and long- term strategies.

## Finance for Science and Technology Students - Chapter 5: Capital Structure

### 1. Dimensions of Securities

- **Riskiness**
  - Profit- dependent: Low priority, no upper limit.
  - Predetermined: High priority, fixed maximum.
  - Default risk: Possibility of not recovering investment.

- **Maturity**
  - Short- term, long- term, or permanent.

- **Property Rights**
  - **Equity:** Ownership + control.
  - **Liabilities:** Creditor status, priority claims.

- **Other classifications**
  - Deposited vs. promised.
  - Primary vs. secondary markets.
  - Secured vs. unsecured.
  - Derivatives: Options, futures, swaps.

### 2. Capital Structure Analysis

- **Definition**: Combination of debt and equity used to finance operations.
- **Relevance**:
  - Influences cost of capital and capital budgeting.
  - Affects firm's financial flexibility and valuation.

#### Modigliani- Miller Theorem (1958)

- **Proposition 1:** Capital structure is irrelevant in perfect capital markets.
  - Arbitrage ensures firm value remains the same regardless of leverage.
- **Proposition 2:** Cost of equity increases with leverage.
  - Equity holders require higher returns due to increased risk.
  
- **Market Imperfections that Affect Capital Structure**:
  - Taxes (interest is deductible).
  - Bankruptcy costs.
  - Agency costs (conflict between managers and shareholders).
  - Information asymmetry.

### 3. Trade- Off Theory vs. Pecking Order Theory

- **Trade- Off Theory**
  - Firms balance tax benefits of debt against bankruptcy costs.
  - Optimal debt ratio exists.

- **Pecking Order Theory**
  - Firms prefer internal financing > debt > external equity.
  - New equity issuance signals negative information.

### 4. Weighted Average Cost of Capital (WACC)
  
$
WACC = \frac{E}{V} r_e + \frac{D}{V} r_d (1 - \tau)
$

- $E$= Equity Value,$D$= Debt Value,$V$= Total Value.
- $r_e$= Cost of Equity,$r_d$= Cost of Debt,$\tau$= Tax Rate.
- **WACC decreases with debt up to an optimal point**, after which bankruptcy costs rise.

---

## Chapter 6 - Valuing Levered Projects

### 1. Levering and Unlevering

- **Unlevered Equity**: No debt, all cash flows go to shareholders.
- **Levered Equity**: Firm issues debt, reducing equity requirements.

### 2. Project Valuation with Debt

- **Net Present Value (NPV)**:

$
NPV = \sum \frac{Cash \ Flow_t}{(1+r)^t} - Initial \ Investment
$

- **Adjusting Discount Rates for Debt**:
  - Higher debt → Lower WACC due to tax shields.
  - Riskier projects → Higher cost of equity.

#### **Example: NPV with Different Debt Ratios**

- 100% equity: Discount cash flows at cost of equity.
- 50% debt: Discount at WACC, including tax shield.

### 3. Adjusted Present Value (APV)
  
$
APV = NPV_{unlevered} + PV(Tax\ Shields)
$

- Used when debt levels change over time.
- Separates tax benefits of debt from core project value.

### 4. Miles- Ezzell Adjustment for WACC

$
WACC = r_a - \frac{D}{V} r_d \tau \left(\frac{1+r_a}{1+r_d} \right)
$

- Adjusts for firms that rebalance debt periodically.

### 5. Valuing Projects with Different Debt Ratios

- **Stepwise WACC Adjustment**:
  1. Unlever cost of capital from similar firms.
  2. Adjust for firm- specific debt level.
  3. Compute project WACC.

- **Debt Rebalancing Methods**:
  - Continuous: MM formulas apply.
  - Periodic: Miles- Ezzell adjustment needed.

---

These notes provide a structured summary of the key topics from Chapters 5 and 6.

## Chapter 7 - Options as Securities

### 1. Option Characteristics

- **Definition**: Financial contracts giving the holder the *right*, but not the *obligation*, to buy or sell an asset at a pre- determined price on or before a specific date.
  
- **Key Types**:
  - **Call Option**: Right to **buy** an asset.
  - **Put Option**: Right to **sell** an asset.
  
- **Exercise Style**:
  - **European Option**: Can be exercised **only at maturity**.
  - **American Option**: Can be exercised **any time** before or on maturity.

### 2. Key Terminology

- **Strike Price (Exercise Price)**: The fixed price at which the holder can buy/sell the underlying asset.
- **Option Premium**: The price paid to acquire the option.
- **Moneyness**:
  - **In the Money (ITM)**: Option has intrinsic value (e.g., call: spot > strike).
  - **At the Money (ATM)**: Spot price = Strike price.
  - **Out of the Money (OTM)**: Option has no intrinsic value (e.g., call: spot < strike).

### 3. Option Payoffs

- **Call Option Payoff**:

$
\text{Payoff (Call)} = \max(S_T - X, 0)
$

- **Put Option Payoff**:

$
\text{Payoff (Put)} = \max(X - S_T, 0)
$

Where:

- $S_T$= Underlying asset price at maturity.
- $X$= Strike price.

### 4. Option Strategies

1. **Simple Positions**:
    - **Long Call**: Right to buy; profit if the price rises.
    - **Short Call**: Obligation to sell; profit if price remains below the strike.
    - **Long Put**: Right to sell; profit if the price drops.
    - **Short Put**: Obligation to buy; profit if price remains above the strike.

2. **Combined Positions**:
    - **Straddle**: Buy a call and put with the same strike—profits from **volatility**.
    - **Bull Spread**: Long a lower strike call, short a higher strike call—profits from **moderate price increases**.
    - **Bear Spread**: Long a higher strike put, short a lower strike put—profits from **moderate price declines**.

### 5. Put- Call Parity (European Options)

$
C - P = S - PV(X)
$

Where:

- $C$= European call price.
- $P$= European put price.
- $S$= Current stock price.
- $PV(X)$= Present value of the strike price.

### 6. Arbitrage Bounds on Option Prices

1. **Upper Bound**:
   - **Call Option**:$C \leq S$
   - **Put Option**:$P \leq X$

2. **Lower Bound** (European Options, no dividends):
   - **Call**:$C \geq \max(0, S - PV(X))$
   - **Put**:$P \geq \max(0, PV(X) - S)$

---

## Chapter 7 - Foundations in State- Preference Theory

### 1. General Valuation Formula

$
\text{Value} = \sum_t \frac{\mathbb{E}[\text{Cash Flows}_t]}{(1 + r_t)^t}
$

Where:

- $r_t$= Discount rate.
- $\mathbb{E}$= Expectation under appropriate probability.

### 2. State- Preference Theory

- **States of the World**: Future economic scenarios with distinct payoffs.
- **State Prices**: The present value of receiving$1 in a specific state.
- **Arrow- Debreu Securities**: Pay$1 in a specific state and$0 otherwise.

### 3. Risk- Free and State Securities

- A **risk- free security** pays **1** in every state.
  
- For **state securities**:

$
\Psi \mathbf{x} = \mathbf{I}
$

Where:

- $\Psi$= Payoff matrix.
- $\mathbf{x}$ = Portfolio weights.
- $\mathbf{I}$ = Identity matrix.

- **Risk- Free Rate**:

$
r_f = \frac{1}{\sum \mathbf{v} \times \mathbf{x}}
$

Where:

- $\mathbf{v}$= Price vector of existing securities.

### 4. Market Completeness and Arbitrage

- **Complete Market**: Every possible payoff pattern can be replicated.
- **Arbitrage- Free Market**: No strategy provides:
    1. Positive profit now with zero risk.
    2. Zero cost with non- negative future payoffs.

### 5. Arbitrage Theorem

For no- arbitrage:

$
\mathbf{v} = \Psi \mathbf{\psi}
$

Where:

- $\mathbf{v}$ = Price vector.
- $\Psi$= Payoff matrix.
- $\mathbf{\psi}$= State price vector.

### 6. Risk- Neutral Valuation

- **Definition**: Prices are calculated under a **risk- neutral measure**, where all assets earn the **risk- free rate**.

$
S_0 = \frac{\mathbb{E}_\mathbb{Q}[S_T]}{(1 + r_f)^T}
$

Where:

- $\mathbb{Q}$= Risk- neutral probabilities.

### 7. Martingale Property

Under risk- neutral probabilities:

$
S_t = \frac{\mathbb{E}_\mathbb{Q}[S_{t+1}]}{(1 + r_f)}
$

- **Interpretation**: Expected future discounted prices equal today’s price.

### 8. Pricing Kernel

- The pricing kernel $m$ adjusts real probabilities to risk- neutral probabilities:

$
\psi_i = p_i m_i
$

Where:

- $\psi_i$= State price.
- $p_i$= Real probability.
- $m_i$= Marginal utility in state $i$.

### 9. No- Arbitrage Conditions

The following are equivalent:

1. Positive **state prices** exist.
2. An **equivalent martingale measure** exists.
3. A **positive pricing kernel** exists.