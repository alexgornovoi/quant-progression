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
- **Bryant & O’Hallaron** → *Computer Systems: A Programmer’s Perspective*  
- **Williams** → *C++ Concurrency in Action*  
- **Stevens** → *UNIX Network Programming: The Sockets Networking API*  
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
- Apply Bayesian inference to decision-making and estimation.  

**Industry Tools**
- Python (`numpy`, `matplotlib`, `scipy.stats`, `seaborn`)  

**Project 1: Bayesian Simulator**  
- [ ] Create a Python notebook that models coin flips and dice rolls.  
- [ ] Implement Bayesian updating and visualize belief convergence.  

---

### Module 2: Classical Probability and Statistical Inference (DeGroot)
**Learning Outcomes**
- Master random variables, expectation, and variance.  
- Learn estimation, confidence intervals, and hypothesis testing.  
- Build the statistical foundation for stochastic modeling.  

**Industry Tools**
- Python (`numpy`, `pandas`, `scipy`, `statsmodels`)  

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
- C++17+  
- Libraries: `Eigen` (linear algebra), `fmt` (output formatting)  

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
- C++17+ (`Eigen`, `Catch2` or `doctest` for testing)  

**Project 4: C++ Quant Library Skeleton**  
- [ ] Create a modular library with components for math, utils, and pricing.  
- [ ] Add basic testing and benchmarks.  

---

### Module 5: Computer Systems and Performance Engineering (Bryant & O’Hallaron)
**Learning Outcomes**
- Understand how C++ and Python code interact with CPU, memory, and cache.  
- Analyze performance bottlenecks related to memory locality and I/O.  
- Apply profiling and optimization strategies for numerical workloads.  

**Industry Tools**
- Profilers: `perf`, `valgrind`, `gprof` (C++), `cProfile` (Python)  

**Project 5: Monte Carlo Benchmark Study**  
- [ ] Benchmark Monte Carlo simulations in Python vs C++.  
- [ ] Measure and analyze cache effects and vectorization improvements.  

---

### Module 6: Concurrency and Parallelism for Quant Systems (Williams)
**Learning Outcomes**
- Understand threads, futures, locks, and atomics in modern C++.  
- Learn to design safe, parallel numerical algorithms.  
- Apply concurrency to Monte Carlo, backtesting, and simulation workloads.  

**Industry Tools**
- C++: `<thread>`, `<future>`, `<mutex>`, OpenMP  
- Python: `multiprocessing`, `concurrent.futures`, `numba`, `joblib`  

**Project 6: Parallel Simulation Engine**  
- [ ] Parallelize Monte Carlo simulations using threads or OpenMP.  
- [ ] Compare runtime scaling with 1, 2, 4, and 8 threads.  
- [ ] Profile performance and identify synchronization overhead.  

---

### Module 7: Networking and Communication Systems (Stevens)
**Learning Outcomes**
- Understand how data moves between processes and across networks.  
- Learn TCP/UDP sockets, asynchronous I/O, and serialization.  
- Build reliable data feeds for market simulation or analytics.  

**Industry Tools**
- C++: POSIX sockets, `boost::asio`  
- Python: `socket`, `asyncio`, `websockets`  
- Serialization: `json`, `msgpack`, `protobuf`  

**Project 7: Real-Time Market Feed Simulation**  
- [ ] Stream mock tick data between a producer and consumer process.  
- [ ] Measure latency and throughput.  
- [ ] Extend to handle order and trade messages.  

---

### Module 8: Stochastic Calculus and Derivative Pricing (Shreve II)
**Learning Outcomes**
- Understand Brownian motion, Ito’s Lemma, and stochastic differential equations.  
- Derive and implement the Black–Scholes model.  
- Simulate pricing using Monte Carlo methods.  

**Industry Tools**
- Python (`numpy`, `scipy`, `matplotlib`, optional `numba` for performance)  
- Optional C++ implementation using `Eigen`  

**Project 8: Option Pricing Engine**  
- [ ] Implement analytical Black–Scholes and Monte Carlo pricers.  
- [ ] Visualize pricing results and Greeks with `matplotlib`.  

---

### Module 9: Financial Instruments and Market Context (Hull)
**Learning Outcomes**
- Understand derivatives, swaps, futures, and hedging.  
- Apply arbitrage and replication principles to practical markets.  
- Connect mathematical models to market conventions.  

**Industry Tools**
- Python (`pandas`, `numpy`, `matplotlib`, `yfinance`)  

**Project 9: Derivatives Dashboard**  
- [ ] Build a small Python or Streamlit app that prices options, forwards, and futures.  
- [ ] Visualize payoff and P/L diagrams.  

---

### Module 10: Fixed Income, Portfolio Theory, and Risk (Tuckman & Serrat)
**Learning Outcomes**
- Learn yield curve construction, duration, convexity, and DV01.  
- Build and optimize fixed-income portfolios.  
- Understand VaR, CVaR, and risk-adjusted performance metrics.  

**Industry Tools**
- Python (`pandas`, `numpy`, `cvxpy`, `scipy.optimize`, `matplotlib`)  

**Project 10: Bond & Portfolio Analyzer**  
- [ ] Bootstrap yield curves from sample data.  
- [ ] Optimize portfolio weights for risk/return or duration targets.  
- [ ] Visualize efficient frontiers and sensitivity metrics.  

---

### Module 11: Market Microstructure and Execution (Harris)
**Learning Outcomes**
- Learn order types, liquidity, and market impact.  
- Model execution algorithms (TWAP, VWAP).  
- Understand the dynamics of limit order books.  

**Industry Tools**
- Python (`pandas`, `numpy`, `plotly`, optional `simpy` for event simulation)  

**Project 11: Order Book Simulator**  
- [ ] Build a simplified order book model in Python.  
- [ ] Simulate algorithmic executions and analyze cost efficiency.  

---

### Module 12: Data Infrastructure and Systems Design (Kleppmann)
**Learning Outcomes**
- Understand data pipelines, storage, and streaming in quant systems.  
- Design robust and efficient architectures for research and backtesting.  
- Implement scalable data ingestion and querying.  

**Industry Tools**
- Python (`pandas`, `sqlalchemy`, `duckdb`, `pyarrow`)  
- Databases: DuckDB, PostgreSQL, or SQLite  

**Project 12: Market Data Pipeline**  
- [ ] Build a Python ETL pipeline to ingest and store market data.  
- [ ] Query and aggregate data for analytics using SQL or DuckDB.  

---

### Module 13: Quant Capstone Integration
**Learning Outcomes**
- Integrate financial models, risk analytics, and infrastructure into one system.  
- Build a cohesive quant research environment with efficient data access.  
- Document and benchmark system performance.  

**Industry Tools**
- Python + C++ integration (`pybind11` or `ctypes`)  
- Libraries: `numpy`, `pandas`, `matplotlib`, `Eigen`  

**Final Project: Quant Research Platform**  
- [ ] Combine previous modules into a unified pricing, risk, and analytics system.  
- [ ] Implement modular components for pricing, portfolio, and data management.  
- [ ] Produce documentation, performance plots, and usage examples.  
