<div align="center">

# Akshay Bande

### AI Engineer · Quantitative Research · Algorithmic Trading · C++20 Systems

<a href="https://git.io/typing-svg">
  <img
    src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=21&duration=2800&pause=900&color=58A6FF&center=true&vCenter=true&width=900&lines=Financial+Machine+Learning+%7C+Quantitative+Research;Market+Microstructure+%7C+Algorithmic+Trading;C%2B%2B20+%7C+Low-Latency+Systems;Financial+Time+Series+%7C+Regime+Modeling;Build.+Measure.+Research.+Iterate."
    alt="Typing SVG"
  />
</a>

<br>

[![GitHub](https://img.shields.io/badge/GitHub-theakshaybande-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/theakshaybande)
[![Website](https://img.shields.io/badge/Website-Beast's_Almanack-0A7B83?style=for-the-badge&logo=googlechrome&logoColor=white)](https://beastsalmanack.com)
![Python](https://img.shields.io/badge/Python-Quant_Research-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B20-Low_Latency-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)

</div>

---

## Profile

AI and quantitative-finance engineer with **6+ years of software and financial-systems experience** and an **MSc in Artificial Intelligence from Maastricht University**.

My work sits at the intersection of **quantitative research, financial machine learning, market microstructure, systematic trading, and performance-oriented C++ engineering**.

I build research and engineering systems around real financial problems: financial time-series analysis, regime modeling, backtesting, execution assumptions, limit-order books, matching engines, market-data infrastructure, and low-latency design.

---

# Featured Quant & HFT Engineering

<table>
<tr>
<td width="50%" valign="top">

### 🔬 [Regime-Conditioned Motif Discovery](https://github.com/theakshaybande/Final_master_thesis)

**Python · STUMPY · LoCoMotif · HMM · Financial Time Series**

MSc research benchmarking regime-agnostic and regime-conditioned motif discovery under financial nonstationarity.

**Scale**

`73M+ regime-labelled observations`

**Universe**

`Crypto` `FX` `Equity Indices` `Volatility`

</td>

<td width="50%" valign="top">

### 📈 [ML FX Signal Research](https://github.com/theakshaybande/ML-MarketMaking-XGBoost)

**Python · XGBoost · Random Forest · Neural Networks · Backtesting**

Built a short-horizon EUR/USD signal-research pipeline with technical feature engineering, PCA, model comparison, signal generation, and backtesting.

**Reported test result**

`9.4% return` · `6% market exposure`

</td>
</tr>

<tr>
<td width="50%" valign="top">

### ⚡ [Low-Latency Limit Order Book](https://github.com/theakshaybande/lockfree-limit-order-book)

**C++20 · Limit Order Book · Memory Pool · Cache-Aware Design**

Implemented a deterministic price-time-priority order book with direct order-ID indexing, fixed-capacity memory pools, cache-line-aligned order storage, and no per-order heap allocation on the add/cancel/match path.

The current implementation is intentionally single-threaded and deterministic, providing a baseline for future lock-free event-ingress and multi-threaded extensions.

</td>

<td width="50%" valign="top">

### ⚙️ [Branchless Matching Engine](https://github.com/theakshaybande/branchless-matching-engine)

**C++20 · Matching Engine · Branch Prediction · Microbenchmarking**

Compared conventional branching with branchless-style matching over **1,000,000 deterministic synthetic order pairs**.

**Measured result**

`Branching: 18.08 ns/match`  
`Branchless: 20.06 ns/match`

The experiment reinforced an important systems principle: branchless code is not automatically faster, and performance must be validated against the actual workload and CPU behavior.

</td>
</tr>

<tr>
<td width="50%" valign="top">

### 🌐 [Market Chaos Lab](https://github.com/theakshaybande/market-chaos-lab)

**C++20 · Agent-Based Markets · Limit Order Book · Microstructure**

Built an order-driven market simulator where momentum, mean-reversion, and random trader archetypes interact through shared liquidity.

The simulation models price-time priority, resting liquidity, spread dynamics, execution, and emergent market behavior across **10,000 simulation steps**.

</td>

<td width="50%" valign="top">

### 🤖 [HFT Reinforcement Learning Trader](https://github.com/theakshaybande/hft-rl-trader)

**Python · PyTorch · Gymnasium · DQN · Limit Order Book**

Experimental reinforcement-learning environment for inventory management and quote-placement decisions in a stylized LOB market.

**State / reward design includes**

`Inventory` `Spread` `Fees` `PnL` `Risk`

</td>
</tr>

<tr>
<td width="50%" valign="top">

### 📡 [C++20 Market Data Pipeline](https://github.com/theakshaybande/cpp20-market-data-pipeline)

**C++20 · string_view · from_chars · Atomics · CMake**

Low-overhead market-data parsing and processing scaffold focused on tokenization, normalization, aggregation, compile-time constraints, and concurrency-oriented systems design.

**Engineering direction**

`SIMD Parsing` `Batch Ingestion` `Allocator Control` `Feed Handling`

</td>

<td width="50%" valign="top">

### 🧠 [Climate-Risk Clustering for Europe](https://github.com/theakshaybande/climate-clustering_for_europe)

**Python · Unsupervised Learning · SHAP · Clustering**

Developed a European climate-risk clustering pipeline combining hazard, exposure, and vulnerability indicators across **1,304 regions**.

Produced **8- and 10-cluster regional typologies**, achieving **0.2112 ARI** and **0.3187 NMI**, with SHAP-based interpretation.

</td>
</tr>
</table>

---

# MSc Research

## Multivariate Motif Discovery in Financial Time Series

**Maastricht University · MSc Artificial Intelligence · 2024 - 2026**

> **Regime-Agnostic and Regime-Conditioned Methods Under Nonstationarity**

[![Repository](https://img.shields.io/badge/Research-View_Thesis_Repository-238636?style=for-the-badge&logo=github)](https://github.com/theakshaybande/Final_master_thesis)

Research focused on discovering recurrent structures in nonstationary financial markets while explicitly accounting for changing market regimes.

### Methods

- **Matrix Profile / STUMPY** for fixed-length motif discovery
- **LoCoMotif** for variable-length motif discovery
- **Gaussian Hidden Markov Models** for latent regime detection
- **Volatility quantile regimes** for observable market-state conditioning
- Multivariate financial representations
- Statistical evaluation across changing volatility and latent-state conditions

### Research Universe

`BTC` · `ETH` · `S&P 500` · `NASDAQ 100` · `DAX` · `EUR/USD` · `GBP/USD` · `VIX`

### Research Scale

- **73M+ regime-labelled observations**
- Multiple asset classes
- Multiple sampling frequencies
- Observable and latent market-state representations
- Regime-agnostic and regime-conditioned motif discovery

---

# Professional Experience

### Catella Investment Management
**Data Science Intern · Investment Research**  
*Netherlands · 2025*

- Conducted data-science and investment-research work in an asset-management environment.
- Developed a European climate-risk clustering pipeline combining hazard, exposure, and vulnerability indicators across **1,304 regions**.
- Produced **8- and 10-cluster regional typologies**, reaching **0.2112 ARI** and **0.3187 NMI**.
- Used **SHAP** and interactive analysis to explain cluster drivers and regional structure.
- Applied unsupervised learning to ESG, investment, regional, and client data.

<br>

### Volkswagen Group Technology Solutions
**Senior Developer · Enterprise Systems**  
*Pune, India · Mar 2023 - Jul 2024*

- Developed high-throughput **SAP HANA** systems supporting global vehicle operations.
- Optimized query latency, throughput, and production reliability across performance-sensitive database logic and enterprise pipelines.
- Engineered production systems where correctness, observability, scalability, and operational reliability were critical.

<br>

### Accenture & Invenio LSI
**Developer · Financial Systems**  
*India / Bahrain · Oct 2018 - Mar 2023*

- Designed and deployed financial calculation and transaction-processing engines supporting government taxation platforms handling **millions of transactions**.
- Worked across systems spanning **Bahrain, Saudi Arabia, Qatar, and Fiji**.
- Received **Best Performer** recognition for pioneering work on the Bahrain Integrated Tax System.

---

# Technical Stack

### Quantitative Research

`Financial Time Series` · `Backtesting` · `Statistical Modeling` · `Regime Detection` · `Risk Analysis` · `Transaction Costs` · `Execution Assumptions`

### Market Microstructure

`Limit Order Books` · `Matching Engines` · `Order Flow` · `Liquidity` · `Market Data` · `Market Making` · `Execution`

### Machine Learning

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-ML-blue?style=flat-square)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)

`Supervised Learning` · `Unsupervised Learning` · `Deep Learning` · `Reinforcement Learning` · `Clustering` · `Time-Series ML`

### C++ / Systems

![C++](https://img.shields.io/badge/C%2B%2B17%2F20-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![CMake](https://img.shields.io/badge/CMake-064F8C?style=flat-square&logo=cmake&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

`STL` · `Atomics` · `Concurrency` · `Memory Management` · `Memory Pools` · `Cache-Aware Design` · `Branch Prediction` · `Lock-Free Concepts`

### Data & Research Tooling

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white)

`STUMPY` · `Matrix Profile` · `LoCoMotif` · `Hidden Markov Models` · `Arrow/Parquet` · `SAP HANA`

---

# Selected Academic & Research Work

| Project | Area |
|---|---|
| [**Quantum Trend**](https://github.com/theakshaybande/Quantum_trend) | Quantitative academic research |
| [**Crypto Time-Series Motifs**](https://github.com/theakshaybande/crypto-time-series-motifs) | Financial-data ingestion and motif research |
| [**Matrix Profile Simulation Lab**](https://github.com/theakshaybande/matrix-profile-sim-lab) | Time-series similarity and matrix-profile experimentation |
| [**Climate-Risk Clustering for Europe**](https://github.com/theakshaybande/climate-clustering_for_europe) | Unsupervised learning and explainable regional clustering |

---

# Engineering Principles

I care about systems that are **measurable, reproducible, and technically defensible**.

- Benchmark before claiming an optimization
- Separate research results from production assumptions
- Model transaction costs and execution explicitly
- Prefer deterministic, testable systems before adding concurrency
- Measure latency distributions, not just average latency
- Keep financial ML grounded in realistic validation and market structure
- Treat low-latency engineering as a data-layout, allocation, concurrency, and measurement problem

---

# Engineering Activity

<div align="center">

<img
  width="95%"
  src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=theakshaybande&theme=github_dark"
  alt="Akshay Bande GitHub Profile"
/>

<br>

<img
  width="46%"
  src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=theakshaybande&theme=github_dark"
  alt="GitHub Stats"
/>

<img
  width="46%"
  src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=theakshaybande&theme=github_dark"
  alt="Repositories by Language"
/>

<br><br>

<img
  width="95%"
  src="https://github-readme-activity-graph.vercel.app/graph?username=theakshaybande&theme=github-compact&hide_border=true&area=true"
  alt="GitHub Contribution Activity"
/>

</div>

---

# What I Am Building Toward

I am focused on engineering and research roles where **machine intelligence, quantitative methods, market structure, and high-performance systems meet real financial markets**.

<div align="center">

### Quantitative Research · Quant Development · Algorithmic Trading
### Financial ML · Market Microstructure · Low-Latency Trading Systems

<br>

[![GitHub](https://img.shields.io/badge/Explore_My_Work-GitHub-181717?style=for-the-badge&logo=github)](https://github.com/theakshaybande)
[![Website](https://img.shields.io/badge/Read_My_Work-Beast's_Almanack-0A7B83?style=for-the-badge&logo=googlechrome&logoColor=white)](https://beastsalmanack.com)

<br><br>

> **Build. Measure. Research. Iterate.**

</div>
