# CFA® Level II Comprehensive Study Guide

## Overview of CFA Level II

### Exam Structure
- **Total Item Sets**: 22 case-based item sets (20 scored, 2 unscored)
- **Format**: 11 item sets per session
- **Questions per Item Set**: 6 multiple-choice questions
- **Total Questions**: 132 (120 scored, 12 unscored)
- **Duration**: 4 hours 24 minutes total (2h 12min per session)
- **Computer-Based Testing**: Administered at Prometric test centers

### Level II Focus
Level II emphasizes **application and analysis**. It tests:
- **Valuation skills**: Detailed asset valuation techniques
- **Analysis**: Deep analysis of financial statements and investments
- **Case-based application**: Apply concepts to realistic scenarios
- **Integration**: Connecting concepts across topics

### Key Differences from Level I
- **Item sets vs. individual questions**: Each vignette (case) has 6 related questions
- **More depth, less breadth**: Deeper analysis of fewer concepts
- **Valuation-focused**: Heavy emphasis on security valuation
- **Integration required**: Questions may draw on multiple concepts
- **Higher difficulty**: Pass rates historically lower than Level I

---

## Topic Breakdown and Weights (2025)

| Topic | Weight | Approx. Item Sets |
|-------|--------|-------------------|
| **Ethical and Professional Standards** | 10-15% | 2-3 |
| **Quantitative Methods** | 5-10% | 1-2 |
| **Economics** | 5-10% | 1-2 |
| **Financial Statement Analysis** | 10-15% | 2-3 |
| **Corporate Issuers** | 5-10% | 1-2 |
| **Equity Investments** | 10-15% | 2-3 |
| **Fixed Income** | 10-15% | 2-3 |
| **Derivatives** | 5-10% | 1-2 |
| **Alternative Investments** | 5-10% | 1-2 |
| **Portfolio Management** | 10-15% | 2-3 |

**Note**: Weights are given in ranges. Two types dominate: 5-10% for less important topics and 10-15% for more important topics.

---

## 2025 Curriculum Changes

### Minimal Changes Overall
- Most content unchanged from 2024
- 2024 study materials can be used with minor updates

### Ethics Updates (Notable Changes)
- **Soft Dollar Standards**: New reading added
- **Research Objectivity Standards**: New reading added
- **Investment Guidelines**: Enhanced coverage

### Alternative Investments
- Revised reading with updated content
- Focus on private equity, real estate, and hedge funds

---

## Topic 1: Ethical and Professional Standards (10-15%)

### Level II Ethics Focus

**Key Differences from Level I:**
- More complex scenarios
- Integration with investment analysis
- Research objectivity and independence
- Soft dollar arrangements
- Performance presentation issues

### New Topics for 2025

#### A. Soft Dollar Standards
**Definition**: Arrangements where fund managers use client commissions to purchase research and execution services

**Key Principles:**
1. Soft dollars belong to clients, not the manager
2. Can only be used for research and execution services
3. Must provide direct benefit to clients
4. Full disclosure required
5. "Client commission" arrangements must benefit clients

**Permitted Uses:**
- Investment research
- Analytical software
- Market data
- Execution services

**Prohibited Uses:**
- Office rent
- Computer hardware
- Travel expenses
- Entertainment
- General overhead

#### B. Research Objectivity Standards
**Purpose**: Maintain independence and objectivity of investment research

**Key Requirements:**
1. **Separation of research and investment banking**
   - Information barriers ("Chinese walls")
   - Separate reporting structures

2. **Restrictions on personal trading**
   - Blackout periods
   - Pre-clearance requirements
   - Restricted lists

3. **Disclosure requirements**
   - Conflicts of interest
   - Ownership positions
   - Banking relationships

4. **Quiet periods**
   - Following IPOs
   - Before earnings announcements

5. **Fair dealing in dissemination**
   - Simultaneous release to all clients
   - No preferential treatment

### Application-Based Ethics

**Case Study Approach:**
Level II ethics heavily uses detailed case studies requiring:
- Identification of violations
- Application of multiple standards
- Prioritization of duties (client vs. employer vs. profession)
- Recommended actions and compliance procedures

**Priority of Duties Framework:**
1. **Clients** (highest priority in most cases)
2. **Employers**
3. **Profession/Markets**
4. **Self** (lowest priority)

### Common Level II Ethics Scenarios

#### Research and Recommendations
- Adequate basis for recommendations
- Distinguishing facts from opinions
- Plagiarism and attribution
- Mosaic theory application
- Material nonpublic information

#### Performance Presentation
- Compliant vs. non-compliant presentations
- GIPS® compliance claims
- Simulated vs. actual performance
- Cherry-picking accounts
- Survivorship bias

#### Client Relations
- Fair dealing among clients
- Suitability analysis
- Disclosure of conflicts
- Referral fee arrangements
- Confidentiality issues

### Study Tips for Level II Ethics
1. **Read the vignettes carefully** - Details matter
2. **Identify all violations** - Usually multiple issues per case
3. **Apply recommended procedures** - Not just identify violations
4. **Practice with item sets** - Get comfortable with format
5. **Review throughout preparation** - Not just at the end

---

## Topic 2: Quantitative Methods (5-10%)

### Level II Quantitative Focus

Level II quantitative methods emphasizes **advanced regression analysis** and **time series analysis** for forecasting and modeling.

### Key Topics

#### A. Multiple Regression Analysis

**Multiple Regression Equation:**
Yi = b0 + b1X1i + b2X2i + ... + bkXki + εi

**Interpretation:**
- **b0**: Intercept
- **bj**: Change in Y for one-unit change in Xj, holding other variables constant
- **Partial slope coefficients**: Control for other variables

**Assumptions:**
1. **Linearity**: Relationship is linear
2. **Homoskedasticity**: Constant variance of errors
3. **Independence**: Errors are independent
4. **Normality**: Errors are normally distributed
5. **No multicollinearity**: Independent variables not highly correlated

**Adjusted R²:**
Adjusted R² = 1 - [(n-1)/(n-k-1)] × (1-R²)

- Preferred over R² for multiple regression
- Penalizes addition of variables
- Better for model comparison

**F-Statistic:**
- Tests if all slope coefficients = 0
- Tests overall significance of regression
- If F > critical value, reject H₀ (at least one b ≠ 0)

#### B. Violations of Regression Assumptions

**1. Heteroskedasticity**
- **Definition**: Non-constant variance of errors
- **Detection**: Plot residuals, Breusch-Pagan test
- **Effect**: Standard errors unreliable, t-tests invalid
- **Solution**: Robust standard errors (White-corrected)

**2. Serial Correlation (Autocorrelation)**
- **Definition**: Errors correlated across observations
- **Detection**: Durbin-Watson statistic
  - DW ≈ 2: No serial correlation
  - DW < 2: Positive serial correlation
  - DW > 2: Negative serial correlation
- **Effect**: Standard errors unreliable
- **Solution**: Hansen method, adjust standard errors

**3. Multicollinearity**
- **Definition**: Independent variables highly correlated
- **Detection**: High R² but few significant t-stats, high correlation among independent variables
- **Effect**: Unreliable coefficient estimates, inflated standard errors
- **Solution**: Remove redundant variables, increase sample size

#### C. Qualitative Dependent Variables

**Logit/Probit Models:**
- Used when dependent variable is binary (0 or 1)
- Examples: Default/no default, buy/don't buy
- Cannot use OLS regression
- Predicted values are probabilities

#### D. Time Series Analysis

**Components of Time Series:**
1. **Trend**: Long-term movement
2. **Seasonality**: Regular pattern within year
3. **Cyclical**: Fluctuations around trend
4. **Irregular**: Random variations

**Autoregressive (AR) Models:**
xt = b0 + b1xt-1 + εt  (AR(1) model)

- Current value depends on past values
- **Order**: Number of lagged values (AR(1), AR(2), etc.)

**Moving Average (MA) Models:**
xt = μ + εt + θ1εt-1

- Current value depends on past error terms

**Random Walk:**
xt = xt-1 + εt

- Special case of AR(1) with b1 = 1
- Non-stationary
- Best forecast is last observed value

**Stationarity:**
- **Stationary**: Mean, variance constant over time; covariance depends only on lag
- **Unit root**: Non-stationary series (b1 = 1 in AR model)
- **Testing**: Dickey-Fuller test
- **Solution for non-stationarity**: First differencing

**Covariance Stationary Requirements:**
1. Constant expected value
2. Constant variance
3. Covariance depends only on time lag

**Mean Reversion:**
- Series tends to return to long-run mean
- Occurs when |b1| < 1 in AR(1) model

**ARCH (Autoregressive Conditional Heteroskedasticity):**
- Variance of errors changes over time
- Used for modeling volatility
- Common in financial time series

#### E. Machine Learning (Introduction)

**Types of Machine Learning:**
1. **Supervised Learning**: Trained with labeled data
   - Regression, classification

2. **Unsupervised Learning**: Find patterns in unlabeled data
   - Clustering, dimensionality reduction

3. **Deep Learning**: Neural networks with multiple layers

**Overfitting:**
- Model fits training data too well
- Poor out-of-sample performance
- **Prevention**: Cross-validation, regularization

**Cross-Validation:**
- Split data into training and validation sets
- Test model on validation set
- K-fold cross-validation

### Study Tips
1. **Understand violations and their effects** - Critical for Level II
2. **Practice interpreting regression output** - Know what each statistic means
3. **Know when to use each model** - AR vs. MA vs. random walk
4. **Understand stationarity** - Key concept for time series
5. **Don't memorize formulas blindly** - Understand what they represent

---

## Topic 3: Economics (5-10%)

### Level II Economics Focus

Level II economics emphasizes **currency relationships**, **economic growth**, and **economic analysis for valuation**.

### Key Topics

#### A. Currency Exchange Rates

**Exchange Rate Quotations:**
- **Direct quote (price quote)**: Domestic currency per foreign currency
- **Indirect quote (volume quote)**: Foreign currency per domestic currency
- **Cross rate**: Exchange rate between two currencies derived from their rates with a third currency

**Bid-Ask Spreads:**
- **Bid**: Price dealer will pay (buy at)
- **Ask (Offer)**: Price dealer will sell at
- **Spread**: Ask - Bid
- Wider spreads indicate less liquidity

**Forward Exchange Rates:**
- Exchange rate for future delivery
- **Forward premium**: Forward rate > spot rate
- **Forward discount**: Forward rate < spot rate

**Forward Rate Calculation:**
Forward rate = Spot rate × (1 + idomestic) / (1 + iforeign)

#### B. Exchange Rate Determination

**Purchasing Power Parity (PPP):**
- **Absolute PPP**: Exchange rates equalize prices across countries
- **Relative PPP**: Exchange rate changes offset inflation differentials

**Relative PPP Formula:**
% Change in S(d/f) ≈ Inflationdomestic - Inflationforeign

**Interest Rate Parity (IRP):**
- **Covered IRP**: Forward rates prevent arbitrage
- **Uncovered IRP**: Expected currency appreciation offsets interest differential

**Covered IRP Formula:**
Forward rate / Spot rate = (1 + idomestic) / (1 + iforeign)

**International Fisher Relation:**
Nominal interest rate ≈ Real interest rate + Expected inflation

- Interest rate differentials reflect inflation expectations
- Nominal rate difference = Expected inflation difference

#### C. Balance of Payments

**Current Account:**
- Merchandise trade (exports - imports)
- Services trade
- Income receipts/payments
- Unilateral transfers

**Capital Account:**
- Capital transfers
- Acquisition/disposal of non-financial assets

**Financial Account:**
- Direct investment
- Portfolio investment
- Other investment
- Reserve assets

**BOP Identity:**
Current Account + Capital Account + Financial Account = 0

**Current Account Influences:**
- **Deficit**: Imports > Exports
  - Can indicate strong domestic growth
  - May pressure currency depreciation
- **Surplus**: Exports > Imports
  - Can indicate weak domestic demand
  - May support currency appreciation

#### D. Monetary and Fiscal Policy

**Monetary Policy Effects on Currencies:**
- **Expansionary** (lower rates): Currency depreciation pressure
- **Contractionary** (higher rates): Currency appreciation pressure
- **Transmission mechanisms**: Interest rates, exchange rates, asset prices

**Fiscal Policy Effects:**
- **Expansionary fiscal** (↑G or ↓T):
  - Short run: Higher growth, potential currency appreciation
  - Long run: Larger deficits, potential currency depreciation
- **Contractionary fiscal** (↓G or ↑T):
  - Slower growth, reduced government borrowing

**Policy Mix Analysis:**
- **Tight monetary + Easy fiscal**: Crowding out, higher interest rates
- **Easy monetary + Tight fiscal**: Lower interest rates, slower growth
- **Both tight**: Significant slowdown
- **Both easy**: Stimulus, potential inflation

#### E. Economic Growth

**Production Function:**
Y = A × F(K, L)

Where:
- Y = Output
- A = Total factor productivity (technology)
- K = Capital
- L = Labor

**Growth Accounting Equation:**
Growth rate of Y = Growth rate of A + αK(Growth of K) + αL(Growth of L)

**Sources of Growth:**
1. **Labor input**: Population growth, labor force participation
2. **Human capital**: Education, skills, health
3. **Physical capital**: Investment in machinery, infrastructure
4. **Technology**: Innovation, efficiency improvements
5. **Natural resources**: Land, minerals

**Convergence Hypothesis:**
- **Absolute convergence**: Poor countries grow faster than rich countries
- **Conditional convergence**: Countries converge to own steady state
- **Club convergence**: Groups of countries with similar characteristics converge

**Sustainable Growth Rate:**
Growth rate a country can maintain without causing:
- Excessive inflation
- Balance of payments crises
- Debt sustainability issues

#### F. Economics of Regulation

**Regulatory Tools:**
1. **Statutes**: Laws passed by legislature
2. **Administrative regulations**: Rules by regulatory agencies
3. **Judicial law**: Court interpretations

**Types of Regulators:**
- **Government agencies**: SEC, FCA, banking regulators
- **Self-regulating organizations**: FINRA, exchanges
- **Independent regulators**: Central banks

**Regulatory Costs and Benefits:**
- **Costs**: Compliance costs, reduced innovation, regulatory capture
- **Benefits**: Consumer protection, market stability, systemic risk reduction

**Regulatory Arbitrage:**
- Exploiting differences in regulations across jurisdictions
- Can lead to race to the bottom

### Study Tips
1. **Master currency relationships** - PPP, IRP are frequently tested
2. **Understand policy impacts** - How monetary/fiscal policy affects currencies
3. **Connect to valuation** - Economics supports equity and fixed income analysis
4. **Know the formulas** - PPP, IRP, growth accounting
5. **Practice calculations** - Forward rates, cross rates, BOP

---

## Topic 4: Financial Statement Analysis (10-15%)

### Level II FSA Focus

Level II FSA emphasizes:
- **Quality of financial reporting**
- **Integration with valuation**
- **Intercorporate investments**
- **Employee compensation**
- **Multinational operations**

### Key Topics

#### A. Financial Reporting Quality

**Quality Spectrum:**
1. **GAAP compliance**
2. **High quality (decision-useful, sustainable earnings)**
3. **Low quality (biased, aggressive)**
4. **Earnings management**
5. **Fraudulent reporting**

**Earnings Quality:**
- **High quality**: Sustainable, adequate returns, conservative accounting
- **Low quality**: One-time items, aggressive policies, poor cash realization

**Earnings Management:**
- **Accruals management**: Manipulating estimates and judgments
- **Real activities manipulation**: Timing real transactions to affect earnings
- **Classification shifting**: Moving items between line items

**Red Flags:**
- Divergence between earnings and cash flows
- Frequent changes in accounting policies
- Aggressive revenue recognition
- Capitalizing items competitors expense
- Unusual related-party transactions
- Weak internal controls

**Beneish M-Score:**
Model to detect earnings manipulation using 8 financial ratios

#### B. Integration of FSA Techniques

**Comprehensive Analysis:**
1. Review accounting policies
2. Analyze common-size statements
3. Calculate and interpret ratios
4. Evaluate earnings quality
5. Make adjustments for comparability
6. Project future performance

**Adjustments for Analysis:**
- Adjusting for different depreciation methods
- Inventory method adjustments (FIFO to LIFO)
- Operating vs. finance lease adjustments
- Pension adjustments
- Off-balance-sheet items

#### C. Employee Compensation

**Stock-Based Compensation:**
- **Stock options**: Right to buy shares at specified price
- **Restricted stock**: Shares that vest over time
- **Stock appreciation rights (SARs)**: Cash payment based on stock appreciation

**Accounting for Stock Options:**
- Fair value at grant date
- Expense over vesting period
- Reduces net income but no cash outflow

**Stock Option Valuation:**
- Black-Scholes-Merton model
- Factors: Stock price, exercise price, time to expiration, volatility, risk-free rate, dividends

**Impact on Financial Statements:**
- Income statement: Compensation expense
- Balance sheet: Increase in equity (APIC)
- Cash flow: Tax benefit in CFO
- Diluted EPS: Treasury stock method

**Pensions:**
- **Defined contribution**: Company contributes fixed amount
- **Defined benefit**: Company promises specific retirement benefit

**Pension Accounting (Defined Benefit):**
- **Pension obligation (PBO)**: PV of future benefits earned
- **Plan assets**: Investments funding the pension
- **Funded status**: Plan assets - PBO
  - Overfunded: Asset on balance sheet
  - Underfunded: Liability on balance sheet

**Components of Pension Expense:**
1. Service cost (current year benefit earned)
2. Interest cost (unwinding discount on PBO)
3. Expected return on plan assets (negative expense)
4. Amortization of prior service cost
5. Amortization of actuarial gains/losses

**Pension Cash Flow:**
- Contributions are actual cash outflow
- Pension expense ≠ cash paid

#### D. Multinational Operations

**Foreign Currency Concepts:**
- **Functional currency**: Primary currency of operations
- **Presentation currency**: Currency of financial statements
- **Local currency**: Currency of country where subsidiary operates

**Translation vs. Remeasurement:**

**Translation (Functional = Local currency):**
- Use **current rate method**
- Assets and liabilities at current rate
- Equity at historical rates
- Income statement at average rate
- Translation gain/loss goes to **Other Comprehensive Income (OCI)**
- No impact on net income

**Remeasurement (Functional = Parent currency):**
- Use **temporal method**
- Monetary assets/liabilities at current rate
- Non-monetary items at historical rates
- Translation gain/loss goes to **Income Statement**
- Impacts net income

**Hyperinflationary Economies:**
- Use temporal method
- Remeasure to parent currency

**Effects of Exchange Rate Changes:**
- **Appreciating local currency**: Translation gain (pure translation)
- **Depreciating local currency**: Translation loss (pure translation)
- Exposure depends on net asset vs. net liability position

#### E. Intercorporate Investments

**Classification by Ownership:**

1. **<20% ownership: Financial Assets**
   - **Fair value through P&L (FVPL)**: Changes go to income statement
   - **Fair value through OCI (FVOCI)**: Changes go to OCI (debt securities)
   - **Amortized cost**: Debt securities held to maturity

2. **20-50% ownership: Equity Method (Significant Influence)**
   - **Initial**: Investment at cost
   - **Each period**: Investment increases by share of earnings, decreases by dividends received
   - Investment account = Cost + Share of earnings - Dividends received
   - Income statement shows "Income from investment" (proportionate share)

3. **>50% ownership: Consolidation (Control)**
   - **Acquisition method**
   - Combine 100% of subsidiary's assets/liabilities
   - Create non-controlling interest (minority interest) for portion not owned
   - Eliminate intercompany transactions

**Equity Method Details:**
- Proportionate share of investee's net income recognized
- Dividends received reduce investment account
- Amortization of excess purchase price over book value
- Share of investee's OCI flows through to investor's OCI

**Goodwill in Acquisitions:**
Goodwill = Purchase Price - Fair Value of Net Identifiable Assets

- Not amortized
- Tested annually for impairment
- Impairment loss reduces goodwill and net income

**Fair Value vs. Equity Method:**
| Aspect | Fair Value | Equity Method |
|--------|------------|---------------|
| Balance Sheet | Fair value | Cost + earnings - dividends |
| Income Statement | Unrealized gains/losses (FVPL) | Share of investee income |
| Dividends | Dividend income | Reduce investment account |

#### F. Business Combinations

**Acquisition Method:**
1. Identify acquirer
2. Determine acquisition date
3. Measure fair value of consideration transferred
4. Recognize and measure identifiable assets, liabilities, and non-controlling interest
5. Recognize goodwill or bargain purchase gain

**Non-Controlling Interest (NCI):**
- Equity claim of minority shareholders in consolidated subsidiary
- Reported in equity section
- Share of subsidiary's net income reported separately

**Partial vs. Full Goodwill Method:**
- **Partial**: Goodwill only for parent's share
- **Full (IFRS option)**: Goodwill includes NCI portion

#### G. Variable Interest Entities (VIEs)

**Special Purpose Entities (SPEs):**
- Created for specific purpose
- Off-balance-sheet financing vehicle

**Primary Beneficiary:**
- Must consolidate VIE
- Determined by: Power to direct activities + obligation/right to significant economics

### Study Tips
1. **Master intercorporate investments** - Heavily tested
2. **Understand equity method mechanics** - Income and balance sheet effects
3. **Know translation vs. remeasurement** - Different methods and impacts
4. **Pension accounting is complex** - Focus on funded status and components
5. **Practice analytical adjustments** - Compare across different accounting methods

---

## Topic 5: Corporate Issuers (5-10%)

### Level II Corporate Issuers Focus

Level II dives deeper into:
- **Capital structure decisions**
- **Dividend policy**
- **Corporate governance and ESG**
- **Mergers and acquisitions**
- **Working capital management**

### Key Topics

#### A. Capital Structure

**Optimal Capital Structure:**
- Minimizes WACC
- Maximizes firm value
- Balances tax benefits and financial distress costs

**Modigliani-Miller (M&M) Propositions:**

**Proposition I (No Taxes):**
- Capital structure irrelevant
- VL = VU (Value of levered firm = Value of unlevered firm)

**Proposition II (No Taxes):**
- re = r0 + (r0 - rd) × (D/E)
- As leverage increases, cost of equity increases

**Proposition I (With Taxes):**
- VL = VU + (T × D)
- Tax shield adds value
- Optimal structure = 100% debt (unrealistic)

**Proposition II (With Taxes):**
- re = r0 + (r0 - rd) × (1 - T) × (D/E)

**Static Trade-Off Theory:**
- Balance tax benefits vs. costs of financial distress
- Optimal D/E ratio exists
- **Benefits of debt**: Tax shield, discipline on management
- **Costs of debt**: Financial distress, bankruptcy, agency costs

**Pecking Order Theory:**
1. Internal financing (retained earnings) - preferred
2. Debt financing
3. Equity financing - least preferred

**Reasoning**: Information asymmetry, signaling

**Agency Costs:**
- **Debt agency costs**: Shareholders expropriate bondholder wealth
- **Equity agency costs**: Manager-shareholder conflicts

**Practical Factors:**
- Industry norms
- Company size and growth stage
- Tax regime
- Flexibility and reserve borrowing capacity
- Lender and rating agency attitudes

#### B. Dividend Policy

**Dividend Forms:**
- **Regular cash dividend**: Periodic payment
- **Extra/special dividend**: One-time payment
- **Liquidating dividend**: Return of capital
- **Stock dividend**: Additional shares
- **Stock split**: Increase shares outstanding

**Dividend Theories:**

**Dividend Irrelevance (M&M):**
- With perfect markets, dividend policy irrelevant
- Investors can create "homemade dividends"

**Bird-in-the-Hand:**
- Dividends preferred to uncertain capital gains
- Higher dividends increase value

**Tax Preference:**
- If dividends taxed higher than capital gains, low dividends preferred

**Signaling:**
- Dividends convey management's confidence
- Dividend increases = positive signal
- Dividend cuts = negative signal

**Agency Costs:**
- Dividends reduce free cash flow
- Reduces overinvestment by managers
- Forces firms into capital markets (monitoring)

**Clientele Effect:**
- Different investors prefer different dividend policies
- High tax bracket → low dividend stocks
- Tax-exempt/low bracket → high dividend stocks

**Factors Affecting Dividend Policy:**
- Investment opportunities
- Expected volatility of future earnings
- Financial flexibility
- Tax considerations
- Flotation costs
- Contractual and legal restrictions

**Stable Dividend Policy:**
- Predictable, gradually increasing dividends
- Smoothing: Dividends less volatile than earnings

**Target Payout Ratio:**
Expected dividend = Previous dividend + [(Target payout × Current earnings - Previous dividend) × Adjustment factor]

**Share Repurchases:**
- Alternative to dividends
- Flexible
- Tax advantaged (in some jurisdictions)
- Signals undervaluation
- Can improve financial ratios (EPS, ROE)

**Dividend vs. Repurchase:**
| Aspect | Dividends | Repurchases |
|--------|-----------|-------------|
| Tax treatment | Ordinary income | Capital gains (if sell) |
| Commitment | Implicit commitment | More flexible |
| Signaling | Strong signal | Signals undervaluation |
| Distribution | All shareholders | Selling shareholders |

#### C. Corporate Governance and ESG

**Corporate Governance Framework:**
- Shareholder rights
- Board responsibilities
- Manager incentives and oversight
- Stakeholder interests

**Board of Directors:**
- Duty of care
- Duty of loyalty
- Independent directors
- Committees: Audit, compensation, nominating

**Stakeholder Management:**
- Shareholders
- Employees
- Customers
- Suppliers
- Communities
- Environment

**ESG Factors:**

**Environmental:**
- Climate change and carbon emissions
- Resource depletion
- Waste and pollution
- Opportunities in clean tech

**Social:**
- Human capital management
- Product safety
- Data security and privacy
- Stakeholder opposition
- Community relations

**Governance:**
- Board independence and effectiveness
- Executive compensation
- Ownership structure
- Accounting and transparency

**ESG Integration:**
- Risk management
- Valuation impact
- Investment analysis
- Engagement and stewardship

#### D. Mergers and Acquisitions

**Types of Mergers:**
- **Horizontal**: Same industry
- **Vertical**: Along value chain
- **Conglomerate**: Unrelated businesses

**Motivations:**
- Synergies (revenue and cost)
- Growth
- Market power
- Diversification
- Managerial motives
- Tax benefits
- Unlocking hidden value

**Merger Analysis:**

**Pre-Merger Values:**
- Value of Acquirer (A)
- Value of Target (T)

**Post-Merger Value:**
- Value(A+T) = Value(A) + Value(T) + Synergies

**Premium:**
- Offer price - Pre-merger target price

**Gain to Target:**
- Gain(T) = Premium paid

**Gain to Acquirer:**
- Gain(A) = Synergies - Premium

**Stock vs. Cash Offers:**
- **Cash**: Target receives fixed payment
- **Stock**: Target shares in upside/downside

**Valuation Methods:**
- DCF analysis
- Comparable company analysis
- Comparable transaction analysis
- LBO analysis

**Post-Merger Integration:**
- Cultural integration
- Systems integration
- Retaining key employees
- Realizing synergies

**Divestitures:**
- **Equity carve-out**: IPO of subsidiary
- **Spin-off**: Pro-rata distribution to shareholders
- **Split-off**: Exchange offer for parent shares
- **Liquidation**: Sale of assets

### Study Tips
1. **Understand M&M propositions** - Foundation for capital structure
2. **Know dividend theories** - Irrelevance, signaling, clientele
3. **ESG is growing** - Increasingly important in CFA curriculum
4. **M&A valuation** - Practice calculating synergies and gains
5. **Connect to other topics**: Corporate Issuers uses Corporate Finance, Equity Valuation

---

## Topic 6: Equity Investments (10-15%)

### Level II Equity Focus

Level II equity emphasizes **detailed valuation models** and **industry/company analysis**. This is one of the most heavily tested topics.

### Key Topics

#### A. Industry and Company Analysis

**Porter's Five Forces (Detailed Analysis):**
1. **Threat of New Entrants**: Barriers to entry
2. **Threat of Substitutes**: Alternative products
3. **Bargaining Power of Buyers**: Customer concentration
4. **Bargaining Power of Suppliers**: Supplier concentration
5. **Rivalry Among Existing Competitors**: Industry competition

**Industry Life Cycle Valuation Implications:**
- **Embryonic**: High risk, no earnings, valuation difficult
- **Growth**: Rapid growth, high P/E, high uncertainty
- **Shakeout**: Slowing growth, competition intensifies
- **Mature**: Stable, moderate P/E, dividends
- **Decline**: Declining sales, low P/E, value traps

**Competitive Advantage:**
- Cost leadership
- Product differentiation
- Focus strategy
- **Economic moat**: Sustainable competitive advantage

#### B. Equity Valuation Models

**Dividend Discount Models (DDM):**

**1. Gordon Growth Model:**
V0 = D1 / (r - g)

**Assumptions:**
- Constant dividend growth
- r > g
- Stable growth forever

**2. Two-Stage DDM:**
- High growth phase → Stable growth phase
- V0 = PV(High growth dividends) + PV(Terminal value)

**3. H-Model (Half-life):**
V0 = [D0 × (1 + gL) + D0 × H × (gS - gL)] / (r - gL)

- Assumes linear decline from high growth (gS) to low growth (gL)
- H = half-life of high growth period

**4. Three-Stage DDM:**
- High growth → Transition → Stable growth
- Most flexible

**Sustainable Growth Rate:**
g = Retention rate (b) × ROE

Or: g = (1 - Payout ratio) × ROE

**Free Cash Flow to Equity (FCFE) Models:**

**FCFE Calculation:**
FCFE = NI + NCC - FCInv - WCInv + Net Borrowing

Or:
FCFE = CFO - FCInv + Net Borrowing

Where:
- NI = Net income
- NCC = Non-cash charges
- FCInv = Fixed capital investment
- WCInv = Working capital investment

**Single-Stage FCFE Model:**
V0 = FCFE1 / (r - g)

**Multi-Stage FCFE Model:**
- Different growth rates over time
- More flexible than DDM (can value non-dividend-paying stocks)

**Free Cash Flow to the Firm (FCFF) Models:**

**FCFF Calculation:**
FCFF = NI + NCC + Int(1-T) - FCInv - WCInv

Or:
FCFF = CFO + Int(1-T) - FCInv

Or:
FCFF = EBIT(1-T) + NCC - FCInv - WCInv

**Firm Value:**
Firm Value = PV(FCFF)

**Equity Value:**
Equity Value = Firm Value - Market Value of Debt + Cash

**Advantages of FCFF:**
- Capital structure neutral
- Avoids dividend policy complications
- Focuses on cash generation

**Residual Income Model:**

**Residual Income:**
RI = NI - (r × Beginning Book Value of Equity)

Or:
RI = (ROE - r) × Beginning Book Value

**Single-Stage RI Model:**
V0 = B0 + [RI1 / (r - g)]

Where B0 = Current book value

**Advantages of RI:**
- Can value companies with negative earnings
- Focuses on value creation (economic profit)
- Less sensitive to terminal value

**Private Company Valuation:**
- Less marketable (discount)
- Lack of liquidity
- Control premiums
- Methods: DCF, comparables, asset-based

#### C. Price Multiples

**Price-to-Earnings (P/E) Ratio:**

**Trailing P/E:**
P0 / E0

**Forward P/E (Leading):**
P0 / E1

**Justified P/E (from Gordon Growth Model):**
P0 / E1 = (1 - b) / (r - g) = Payout ratio / (r - g)

**Factors Affecting P/E:**
- Growth (↑g → ↑P/E)
- Risk (↑r → ↓P/E)
- Payout ratio (↑payout → ↑P/E, assuming constant g)

**PEG Ratio:**
PEG = P/E / g

- Lower PEG may indicate undervaluation
- Typically g expressed as percentage

**Price-to-Book (P/B) Ratio:**
P/B = Market Value of Equity / Book Value of Equity

**Justified P/B:**
P0 / B0 = (ROE - g) / (r - g)

**Use Cases:**
- Financial institutions
- Distressed companies
- Asset-heavy industries

**Price-to-Sales (P/S) Ratio:**
P/S = Market Value / Total Revenue

**Advantages:**
- Always positive (unlike earnings)
- Less subject to manipulation
- Useful for early-stage companies

**Price-to-Cash Flow:**
P/CF = Price / Cash Flow per Share

**Cash flow measures:**
- CFO
- Free cash flow
- EBITDA (proxy)

**Enterprise Value Multiples:**

**EV/EBITDA:**
EV = Market Value of Equity + Market Value of Debt - Cash

**Advantages:**
- Compares firms with different capital structures
- EBITDA available to all capital providers
- Less affected by depreciation differences

**Comparable Analysis:**
1. Identify comparable companies
2. Calculate multiples
3. Determine appropriate benchmark (mean, median, harmonic mean)
4. Apply to target company
5. Adjust for differences

**Comparables Selection:**
- Same industry
- Similar size
- Similar growth
- Similar profitability
- Similar risk

#### D. Asset-Based Valuation

Used when:
- Company being liquidated
- Financial companies (NAV)
- Natural resource companies

**Net Asset Value:**
NAV = Fair Value of Assets - Fair Value of Liabilities

### Study Tips
1. **Master DCF models** - FCFE, FCFF, DDM, RI
2. **Practice valuations** - Many calculation-heavy item sets
3. **Understand justified multiples** - Link to fundamentals
4. **Know when to use each model** - Match method to situation
5. **Integration**: Uses FSA (financial statements), Corporate Finance (WACC)

---

## Level II Study Strategy

### Recommended Study Timeline (4-6 Months)

**Month 1-2: Core Valuation Topics**
- Equity Investments
- Financial Statement Analysis
- Ethics (start early, review throughout)

**Month 3: Fixed Income and Quantitative**
- Fixed Income
- Quantitative Methods

**Month 4: Supporting Topics**
- Economics
- Corporate Issuers
- Portfolio Management

**Month 5: Final Topics**
- Derivatives
- Alternative Investments
- Final Ethics review

**Month 6: Review and Practice**
- Mock exams (at least 3-4)
- Review weak areas
- Item set practice

### Study Approach

**Item Set Practice is Critical:**
- Level II is entirely item sets
- Practice reading vignettes efficiently
- Learn to identify relevant information
- Practice managing time per item set

**Time Management:**
- 132 minutes per session / 11 item sets = 12 minutes per item set
- 2 minutes per question
- Must be efficient

**Vignette Reading:**
- Skim vignette first
- Read questions
- Return to vignette for relevant information
- Don't read every word initially

**Common Mistakes:**
1. Reading vignette too carefully initially
2. Spending too long on one item set
3. Not practicing enough item sets
4. Neglecting formulas and calculations
5. Weak on integration across topics

### Pass Rates and Difficulty

- Level II historically has lower pass rates than Level I
- More depth, integration required
- Valuation-heavy
- Case-based format requires different skills
- Time management crucial

---

## Conclusion

CFA Level II is known as the most challenging of the three levels. Success requires:

- **Deep understanding**: Application and analysis, not just knowledge
- **Extensive practice**: Hundreds of item sets
- **Integration**: Connect concepts across topics
- **Time management**: Discipline in pacing
- **Valuation mastery**: DCF, multiples, residual income models

The knowledge gained at Level II directly applies to security analysis and portfolio management roles. It represents the core technical skills of investment professionals.

**Good luck with your CFA Level II preparation!**

---

*Note: This study guide focuses on the most important Level II concepts. Refer to official CFA curriculum and practice problems for complete coverage. The detailed topic guides in this series provide additional depth.*
