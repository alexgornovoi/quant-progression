# Quant Progression

This project serves as a way for me to track my progression on studying topics for quantitative finance, programming, and system design.  
Feel free to follow this study plan if you find it interesting.

The notes for this project are intended to be opened in [Obsidian](https://obsidian.md/).  
Some advanced LaTeX will not be supported by GitHub’s markdown viewer.

---

## Books
- **Kurt** → *Bayesian Statistics the Fun Way*  
- **DeGroot** → *Probability and Statistics*  
- **Meyers** → *Effective Modern C++*  
- **Iglberger** → *C++ Software Design*  
- **Shreve II** → *Stochastic Calculus for Finance II: Continuous-Time Models*  
- **Hull** → *Options, Futures, and Other Derivatives*  
- **Tuckman & Serrat** → *Fixed Income Securities: Tools for Today’s Markets*  
- **Harris** → *Trading and Exchanges: Market Microstructure for Practitioners*  
- **Kleppmann** → *Designing Data-Intensive Applications*  

---

## Progression

### Module 1: Bayesian Thinking and Probability Foundations (Kurt)
**Learning Outcomes**
- Understand priors, posteriors, and Bayesian updating.  
- Build intuition for probabilistic reasoning under uncertainty.  
- Apply Bayesian inference to simple estimation and decision-making problems.  

**Industry Tools**
- **Python** — standard for statistical modeling and research.  
- **Libraries:** `numpy`, `matplotlib`, `scipy.stats`, `seaborn`  

**Project 1: Bayesian Simulator**  
- [ ] Create a Python notebook that models coin flips and dice rolls.  
- [ ] Implement Bayesian updating and visualize belief convergence.  

---

### Module 2: Classical Probability and Statistical Inference (DeGroot)
**Learning Outcomes**
- Master random variables, expectation, and variance.  
- Learn estimation, confidence intervals, and hypothesis testing.  
- Build the statistical foundation for applied stochastic processes.  

**Industry Tools**
- **Python**  
- **Libraries:** `numpy`, `pandas`, `scipy`, `statsmodels`  

**Project 2: Statistical Toolkit**  
- [ ] Simulate LLN and CLT using `numpy` random draws.  
- [ ] Implement hypothesis testing functions with `scipy.stats`.  
- [ ] Compare analytical vs Monte Carlo estimates.  

---

### Module 3: Introduction to Programming and Numerical Methods (Meyers)
**Learning Outcomes**
- Learn modern C++17 syntax and idioms.  
- Understand RAII, smart pointers, and value semantics.  
- Translate statistical and numerical routines into high-performance C++.  

**Industry Tools**
- **C++17+** — core language for production quant systems.  
- **Libraries:** `Eigen` (linear algebra), `fmt` (string formatting).  

**Project 3: Numerical Foundations in C++**  
- [ ] Implement basic numerical and statistical routines in C++.  
- [ ] Compare performance against Python equivalents.  

---

### Module 4: Software Design and Modular Programming (Iglberger)
**Learning Outcomes**
- Design scalable, testable C++ libraries using SOLID principles.  
- Implement compile-time polymorphism and templates.  
- Build modular codebases for quant applications.  

**Industry Tools**
- **C++17+**  
- **Libraries:** `Eigen`, `Catch2` or `doctest` for testing.  

**Project 4: C++ Quant Library Skeleton**  
- [ ] Create a modular library with components for math, utils, and pricing.  
- [ ] Add basic testing and benchmarks.  

---

### Module 5: Stochastic Calculus and Derivative Pricing (Shreve II)
**Learning Outcomes**
- Understand Brownian motion, Ito’s Lemma, and stochastic integrals.  
- Derive and implement the Black–Scholes model.  
- Simulate pricing using Monte Carlo methods.  

**Industry Tools**
- **Python** (research prototyping) and/or **C++** (production implementation).  
- **Libraries:** `numpy`, `scipy`, `matplotlib`, optional `numba` for speed.  

**Project 5: Option Pricing Engine**  
- [ ] Implement analytical Black–Scholes and Monte Carlo pricers.  
- [ ] Visualize pricing results and Greeks with `matplotlib`.  

---

### Module 6: Financial Instruments and Market Context (Hull)
**Learning Outcomes**
- Understand derivatives, swaps, futures, and hedging.  
- Apply arbitrage and replication principles to practical markets.  
- Connect mathematical models to market conventions.  

**Industry Tools**
- **Python**  
- **Libraries:** `pandas`, `numpy`, `matplotlib`, `yfinance` (market data).  

**Project 6: Derivatives Dashboard**  
- [ ] Build a small Python or Streamlit app that prices options, forwards, and futures.  
- [ ] Visualize payoff and P/L diagrams.  

---

### Module 7: Fixed Income, Portfolio Theory, and Risk (Tuckman & Serrat)
**Learning Outcomes**
- Learn yield curve construction, duration, convexity, and DV01.  
- Build and optimize fixed-income portfolios.  
- Understand VaR, CVaR, and risk-adjusted performance metrics.  

**Industry Tools**
- **Python**  
- **Libraries:** `pandas`, `numpy`, `cvxpy`, `scipy.optimize`, `matplotlib`.  

**Project 7: Bond & Portfolio Analyzer**  
- [ ] Bootstrap yield curves from sample data.  
- [ ] Optimize portfolio weights for risk/return or duration targets.  
- [ ] Visualize efficient frontiers and sensitivity metrics.  

---

### Module 8: Market Microstructure and Execution (Harris)
**Learning Outcomes**
- Learn order types, liquidity, and market impact.  
- Model execution algorithms (TWAP, VWAP).  
- Understand the dynamics of limit order books.  

**Industry Tools**
- **Python**  
- **Libraries:** `pandas`, `numpy`, `plotly`, `simpy` (for event simulation).  

**Project 8: Order Book Simulator**  
- [ ] Build a simplified order book model in Python.  
- [ ] Simulate algorithmic executions and analyze cost efficiency.  

---

### Module 9: Data Infrastructure and Systems Design (Kleppmann)
**Learning Outcomes**
- Understand data pipelines, storage, and streaming in quant systems.  
- Design robust and efficient architectures for research and backtesting.  
- Implement scalable data ingestion and querying.  

**Industry Tools**
- **Python**  
- **Databases:** `DuckDB`, `PostgreSQL`, `SQLite`  
- **Libraries:** `pandas`, `sqlalchemy`, `pyarrow`  

**Project 9: Market Data Pipeline**  
- [ ] Build a Python ETL pipeline to ingest and store market data.  
- [ ] Query and aggregate data for analytics using SQL or DuckDB.  

---

### Module 10: Quant Capstone Integration
**Learning Outcomes**
- Integrate finance models, risk analytics, and infrastructure into one system.  
- Build a cohesive quant research environment with efficient data access.  
- Document and benchmark system performance.  

**Industry Tools**
- **Python + C++** integration (`pybind11` or `ctypes`).  
- **Libraries:** `numpy`, `pandas`, `matplotlib`, `Eigen`.  

**Final Project: Quant Research Platform**  
- [ ] Combine previous modules into a unified pricing, risk, and analytics system.  
- [ ] Implement modular components for pricing, portfolio, and data management.  
- [ ] Produce documentation, performance plots, and usage examples.  
