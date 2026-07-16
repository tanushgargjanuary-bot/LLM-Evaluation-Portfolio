# Evaluation of Prompt 1

Prompt ID: P01

Prompt: Can you teach me algorithmic trading from scratch? I don't want to just copy existing algorithms—I want to eventually design, test, and build my own trading strategies from first principles. What would a realistic learning roadmap look like, what prerequisites do I need, how long might it take, and what are the biggest challenges I should expect? 
Keep your response concise while remaining complete. Avoid unnecessary repetition or excessive detail.

---

# ChatGPT Response

## Goal

Design, test, and improve original algorithmic trading strategies based on first principles—not just implement existing ones.

---

# Prerequisites

You do **not** need a finance degree.

You **do** need:

|Skill|Why|
|---|---|
|Python|Data processing, backtesting, automation|
|Statistics & Probability|Determine whether an edge is real or random|
|Linear Algebra (basic)|Useful for ML and optimization|
|Calculus (basic)|Helpful but not critical|
|SQL|Store and query historical market data|
|Git|Version control for research|
|Excel|Quick exploration and validation|

---

# Roadmap

### Phase 1 — Markets (2–3 weeks)

Learn:

- Market structure
    
- Exchanges
    
- Order book
    
- Bid/ask spread
    
- Slippage
    
- Liquidity
    
- Different asset classes
    
- Types of orders
    

Goal:

Understand **how markets actually function**.

---

### Phase 2 — Trading Theory (3–4 weeks)

Learn:

- Returns
    
- Volatility
    
- Drawdown
    
- Risk-adjusted return
    
- Position sizing
    
- Diversification
    
- Compounding
    
- Kelly Criterion
    
- Transaction costs
    

Goal:

Understand that **risk management is often more important than prediction**.

---

### Phase 3 — Statistics (1–2 months)

Master:

- Probability
    
- Distributions
    
- Hypothesis testing
    
- Correlation
    
- Regression
    
- Bayesian thinking
    
- Time series basics
    
- Stationarity
    
- Autocorrelation
    

Goal:

Separate genuine signal from noise.

---

### Phase 4 — Python for Quant Research (1 month)

Learn:

- NumPy
    
- Pandas
    
- Matplotlib
    
- SciPy
    

Then:

- Load data
    
- Clean data
    
- Engineer features
    
- Visualize results
    

---

### Phase 5 — Backtesting (1 month)

Learn:

- Event-driven backtesting
    
- Vectorized backtesting
    
- Look-ahead bias
    
- Survivorship bias
    
- Data leakage
    
- Walk-forward testing
    

Goal:

Avoid fooling yourself with unrealistic performance.

---

### Phase 6 — Strategy Design (2–3 months)

Study ideas behind:

- Momentum
    
- Mean reversion
    
- Trend following
    
- Breakouts
    
- Market making
    
- Statistical arbitrage
    
- Pairs trading
    
- Volatility trading
    

Do **not** memorize strategies.

Instead ask:

> Why should this produce an edge?

---

### Phase 7 — First-Principles Research (ongoing)

For every strategy:

1. What market inefficiency might exist?
    
2. Why hasn't it disappeared?
    
3. Who is on the other side?
    
4. What assumptions are required?
    
5. When will it fail?
    

This is where original ideas emerge.

---

### Phase 8 — Portfolio & Risk (1 month)

Learn:

- Position sizing
    
- Exposure
    
- Correlation
    
- Portfolio optimization
    
- Risk budgeting
    
- Maximum drawdown control
    

---

### Phase 9 — Machine Learning (optional)

Only after classical methods.

Learn:

- Feature engineering
    
- Cross-validation
    
- Tree models
    
- XGBoost
    
- Neural networks (only if justified)
    

ML rarely creates an edge by itself.

---

### Phase 10 — Live Trading Systems (1 month)

Build:

- Broker API integration
    
- Paper trading
    
- Logging
    
- Monitoring
    
- Error handling
    
- Execution engine
    
- Risk controls
    

---

# Biggest Challenges

- **Finding a real edge:** Most obvious ideas are already exploited.
    
- **Overfitting:** Strategies that look great historically often fail live.
    
- **Data quality:** Missing, biased, or incorrect data can invalidate results.
    
- **Execution costs:** Fees, slippage, and latency can erase profits.
    
- **Changing markets:** An edge can decay or disappear.
    
- **Psychology:** Sticking to a statistically sound strategy through drawdowns is difficult.
    
- **Research discipline:** Generating and rejecting hypotheses is slow and often unrewarding.
    

---

# Approximate Timeline

|Pace|Time|
|---|---|
|Casual (5–8 hrs/week)|18–30 months|
|Consistent (10–15 hrs/week)|9–15 months|
|Intensive (25–40 hrs/week)|6–9 months|

Becoming consistently profitable may take longer than becoming technically competent.

---

# Recommended Learning Order

1. Python
    
2. Statistics & Probability
    
3. Market structure
    
4. Trading fundamentals
    
5. Pandas & NumPy
    
6. Time-series analysis
    
7. Backtesting
    
8. Strategy research
    
9. Portfolio & risk management
    
10. Paper trading
    
11. Live trading
    
12. Machine learning (if needed)
    

The highest leverage skill is **research methodology**: forming hypotheses about market behavior, testing them rigorously with realistic assumptions, and discarding ideas that fail. That process—not any specific indicator or algorithm—is what enables original strategy development.

## Scores

| Criterion | Score (1-5) | Notes |
|-----------|------------:|-------|
| Instruction Following | | |
| Accuracy | | |
| Reasoning | | |
| Completeness | | |
| Readability | | |
| Tone | | |
| Hallucination Risk | | |
| Overall Helpfulness | | |

### Overall Comments

Strengths

-

Weaknesses

-

---

# DeepSeek Response

This is a realistic, "understanding-first" roadmap for building your own algorithmic trading strategies from first principles.

### 🧭 Learning Roadmap: From Zero to Your Own Strategy

The journey breaks into four interconnected phases:

**1. Foundation: Markets & Programming**
- **Market Mechanics:** Understand what you're trading (stocks, futures), order types (market, limit), market structure (exchanges, market makers), and trading sessions.
- **Programming (Python):** Master Python fundamentals and key libraries: `pandas` (data manipulation), `NumPy` (numerical computing), and `matplotlib` (visualization).

**2. Core Theory & Tools**
- **Math/Stats:** Solidify probability, statistics, linear algebra, and **time series analysis** (autocorrelation, stationarity) as your non-negotiable bedrock.
- **Quant Concepts:** Learn **market microstructure** (how the order book works), what an **alpha factor** is, and the basic framework of **backtesting**.

**3. Build & Iterate: Your First Strategy**
- **Strategy Development:** Start with a **rule-based system** (e.g., moving average crossover) to learn the workflow, then gradually explore **statistical arbitrage** or **momentum**.
- **Backtesting & Optimization:** Build a simple **event-driven backtesting engine**. Crucially, incorporate transaction costs, slippage, and market impact. Fight the urge to over-optimize (overfitting).

**4. Advanced & Live Deployment**
- **Execution & Risk:** Learn how to connect to a broker's API (e.g., Alpaca, Interactive Brokers) and build a **risk management module** (position sizing, stop-losses, drawdown limits).
- **Continuous Learning:** Validate your strategy via **paper trading** (simulated live markets) before risking real capital. Explore ML/AI only after mastering the basics.

---

### 📚 Prerequisites

- **Hard Skills:** Intermediate Python, college-level math (calculus/linear algebra), basic statistics, and a working knowledge of how financial exchanges operate.
- **Soft Skills:** Extreme intellectual honesty (to avoid fooling yourself with backtests), patience, and a skeptical mindset.

---

### ⏳ Time Expectation (From Scratch)

| Pace | Duration |
| :--- | :--- |
| **Full-time (intense)** | ~6 months (e.g., 40+ hrs/week) |
| **Part-time (evenings/weekends)** | 1.5 – 2 years |
| **If you already code/trade** | ~3–4 months to a working prototype |

---

### 🚧 The 5 Biggest Challenges (And How to Prepare)

1.  **Overfitting** – Your strategy works brilliantly on historical data but fails live.  
    *→ Fix: Always use out-of-sample (unseen) data for final validation. Keep your strategy as simple as possible.*

2.  **Backtest vs. Reality** – Backtests ignore slippage, latency, and liquidity.  
    *→ Fix: Build conservative cost models into every backtest. Always paper-trade first.*

3.  **Non-Stationarity** – Market regimes change (bull, bear, high volatility). A winning strategy decays.  
    *→ Fix: Design strategies that adapt, or have a "regime filter" to turn off trading in unfavorable conditions.*

4.  **Execution & Tech Risk** – Your code has a bug, or the network lags during a critical moment.  
    *→ Fix: Start with a robust risk manager that limits max loss per day. Begin trading with tiny sizes.*

5.  **Psychological Discipline** – It's easy to override or "tweak" a losing algorithm emotionally.  
    *→ Fix: Treat the *process* as the product. Stick to your predefined risk rules regardless of P&L.*

---

### 💎 First-Principles Mindset

- **Start with a hypothesis about market behavior** (e.g., "reversals happen after extreme volume"), not with a piece of code.
- **Decompose every strategy** into: *Signal* (when to act) → *Sizing* (how much) → *Execution* (how to place orders).
- **Treat every loss as data**, not failure – it tells you where your market assumption is wrong.

**Suggested starting point:** Read *Algorithmic Trading* by Ernie Chan (pragmatic, code-heavy) and *Advances in Financial Machine Learning* by Marcos Lopez de Prado (for rigorous backtesting). Start coding your first simple backtest within week one – theory alone is useless.

It's a marathon, not a sprint. Good luck – the intellectual payoff is immense.

## Scores

| Criterion | Score (1-5) | Notes |
|-----------|------------:|-------|
| Instruction Following | | |
| Accuracy | | |
| Reasoning | | |
| Completeness | | |
| Readability | | |
| Tone | | |
| Hallucination Risk | | |
| Overall Helpfulness | | |

### Overall Comments

Strengths

-

Weaknesses

-

---

# Claude Response

# Algorithmic Trading Roadmap: From First Principles

## Prerequisites (build these first if missing)

- **Programming**: Python (pandas, numpy) is the practical minimum. You'll live in it.
- **Statistics/probability**: distributions, hypothesis testing, regression, time series (stationarity, autocorrelation)
- **Basic finance**: how markets/exchanges work, order types, market microstructure basics, what moves prices
- **Linear algebra & calculus**: enough for optimization and some ML (not research-level, just working fluency)

If you're weak in one, expect to interleave learning it with the roadmap below rather than front-loading everything.

## Roadmap (rough timeline assumes ~10-15 hrs/week; adjust for your background)

**Phase 1 — Foundations (2-4 months)** Learn Python for data analysis, get comfortable with pandas time-series handling. Study market mechanics: how orders execute, bid-ask spread, liquidity, slippage. Read historical price data, compute returns, volatility, basic statistics on real data.

**Phase 2 — Strategy building blocks (3-5 months)** Study classic strategy families (mean reversion, momentum, pairs trading/statistical arbitrage) not to copy them but to understand _why_ they work and what market inefficiency each exploits. This is where "first principles" thinking starts: for any strategy, ask what economic or behavioral rationale explains the edge, and when it should stop working.

**Phase 3 — Backtesting rigor (2-3 months, ongoing forever)** This is the make-or-break phase most people skip. Learn:

- Survivorship bias, look-ahead bias, overfitting
- Walk-forward analysis, out-of-sample testing
- Transaction costs, slippage modeling — a "profitable" backtest without realistic costs is fiction
- Statistical significance of results (with enough parameters you can overfit noise into a great-looking equity curve)

**Phase 4 — Risk management & portfolio construction (2-3 months)** Position sizing (Kelly criterion and its dangers), drawdown control, correlation between strategies, portfolio-level risk vs single-strategy risk. Most retail algo traders blow up here, not on strategy design.

**Phase 5 — Build your own strategy from first principles (ongoing)** Now start from a market hypothesis (not a known strategy) — e.g., "liquidity providers demand compensation around earnings announcements" — and build a testable model around it. Iterate: hypothesis → data → test → critique your own overfitting → refine.

**Phase 6 — Execution & infrastructure (2-4 months, can run parallel)** Paper trading, then live execution with tiny size. Learn about order execution algorithms, API integration with a broker, latency considerations (irrelevant unless you're doing HFT, but execution quality still matters).

**Total to first live, honestly-tested strategy**: realistically 12-18 months of consistent work if starting with decent programming/math skills; longer if building those from zero.

## Biggest challenges

1. **Overfitting is the default failure mode.** With enough tweaking, any dataset yields a great backtest. Distinguishing real edge from curve-fitted noise is the core skill, not writing code.
2. **Survivorship and look-ahead bias** silently inflate backtests — easy to introduce, hard to notice.
3. **Transaction costs and slippage** turn many "profitable" strategies negative in reality.
4. **Regime change**: strategies that worked on historical data can stop working because the market structure or participant behavior shifted.
5. **Emotional discipline in execution** — even a good systematic strategy gets undermined by manual overrides during drawdowns.
6. **Data quality/cost**: good historical data (especially tick-level or fundamental) isn't free, and dirty data wrecks backtests silently.

## A note on realism

Building genuinely novel, profitable strategies from scratch is hard even for well-resourced quant funds — most retail algo traders lose money, largely due to underestimating overfitting and costs rather than lacking strategy ideas. That's not a reason not to learn this — the process itself teaches excellent quantitative thinking — but calibrate expectations: the first year is about _not fooling yourself_, more than about finding alpha.

Want me to go deeper on any phase — e.g., a reading list, or a first hands-on project to start with?

## Scores

| Criterion | Score (1-5) | Notes |
|-----------|------------:|-------|
| Instruction Following | | |
| Accuracy | | |
| Reasoning | | |
| Completeness | | |
| Readability | | |
| Tone | | |
| Hallucination Risk | | |
| Overall Helpfulness | | |

### Overall Comments

Strengths

-

Weaknesses

-

---

# Comparative Analysis

## Ranking

1.

2.

3.

---

## Best Response

Explain why.

---

## Major Differences

-

-

-

---

## Interesting Observations

-

-

-

---

## Lessons Learned

-

-

-
