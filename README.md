<div align="center">

# Akshay Bande

### AI Engineer · Quantitative Research · Algorithmic Trading · C++20 Systems

<a href="https://git.io/typing-svg">
  <img
    src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=21&duration=2800&pause=900&color=58A6FF&center=true&vCenter=true&width=900&lines=Financial+Machine+Learning+%7C+Quantitative+Research;Market+Microstructure+%7C+Algorithmic+Trading;C%2B%2B20+%7C+Low-Latency+Trading+Systems;Financial+Time+Series+%7C+Regime+Modeling;Build.+Measure.+Research.+Iterate."
    alt="Typing SVG"
  />
</a>

<br>

[![GitHub](https://img.shields.io/badge/GitHub-theakshaybande-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/theakshaybande)
![Python](https://img.shields.io/badge/Python-Quant_Research-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B20-Low_Latency-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Markets](https://img.shields.io/badge/Focus-Financial_Markets-0A7B83?style=for-the-badge)

</div>

---

## Profile

AI and quantitative-finance engineer with **6+ years of software and financial-systems experience** and an **MSc in Artificial Intelligence from Maastricht University**.

My work sits at the intersection of:

**Machine Learning · Quantitative Research · Financial Time Series · Market Microstructure · Algorithmic Trading · High-Performance C++**

I build research and engineering artifacts around real financial problems, from regime-conditioned time-series analysis and systematic trading research to limit-order books, matching engines, market-data infrastructure, reinforcement learning, and performance-oriented C++ systems.

---

## At a Glance

| | Focus |
|---|---|
| **Quant Research** | Financial time series · Regime detection · Backtesting · Statistical modeling · Risk analysis |
| **Financial ML** | PyTorch · scikit-learn · XGBoost · Clustering · Reinforcement learning |
| **Market Microstructure** | Limit order books · Matching engines · Order flow · Liquidity · Market making |
| **Low-Latency Engineering** | C++20 · Atomics · Concurrency · Memory pools · Cache-aware design · Branch prediction |
| **Production Systems** | 6+ years across financial platforms, enterprise systems, databases, and transaction processing |
| **Research Domain** | Crypto · FX · Equity indices · Volatility · Investment research |

---

# Experience

### Catella Investment Management
**Data Science Intern · Investment Research**  
*Netherlands · 2025*

- Conducted data-science and investment-research work within an asset-management environment.
- Developed a European **climate-risk clustering pipeline** combining hazard, exposure, and vulnerability indicators across **1,304 regions**.
- Produced **8- and 10-cluster regional typologies**, reaching **0.2112 ARI** and **0.3187 NMI**, with SHAP-based interpretation and interactive analysis.
- Applied unsupervised learning to investment, ESG, regional, and client data.

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

- Designed and deployed financial calculation and transaction-processing engines supporting government taxation systems handling **millions of transactions**.
- Worked across taxation platforms spanning **Bahrain, Saudi Arabia, Qatar, and Fiji**.
- Received **Best Performer** recognition for pioneering work on the Bahrain Integrated Tax System.

---

# MSc Research

## Multivariate Motif Discovery in Financial Time Series

**Maastricht University · MSc Artificial Intelligence · 2024 - 2026**

> **Regime-Agnostic and Regime-Conditioned Methods Under Nonstationarity**

[![Repository](https://img.shields.io/badge/Research-View_Thesis_Repository-238636?style=for-the-badge&logo=github)](https://github.com/theakshaybande/Final_master_thesis)

Research into recurrent structures in nonstationary financial markets using regime-aware and regime-agnostic motif discovery.

### Methods

- **Matrix Profile / STUMPY** for fixed-length motif discovery
- **LoCoMotif** for variable-length motif discovery
- **Gaussian Hidden Markov Models** for latent-state detection
- **Volatility quantile regimes** for observable market-state conditioning
- Multivariate feature representations
- Statistical evaluation under financial nonstationarity

### Research Universe

`BTC` · `ETH` · `S&P 500` · `NASDAQ 100` · `DAX` · `EUR/USD` · `GBP/USD` · `VIX`

### Scale

Research pipeline operated across datasets containing **73M+ regime-labelled observations**, multiple asset classes, multiple sampling frequencies, and both observable and latent market-state representations.

---

# Quant & HFT Engineering

<table>
<tr>
<td width="50%" valign="top">

### 🔬 [Regime-Conditioned Motif Discovery](https://github.com/theakshaybande/Final_master_thesis)

**Python · STUMPY · LoCoMotif · HMM · Time Series**

MSc research benchmarking regime-agnostic and regime-conditioned motif discovery under financial nonstationarity.

**Focus**

`Motifs` `Regimes` `HMM` `Matrix Profile` `Crypto` `FX` `Indices`

</td>

<td width="50%" valign="top">

### 📈 [ML for Market Making](https://github.com/theakshaybande/ML-MarketMaking-XGBoost)

**Python · XGBoost · Random Forest · Neural Networks**

Short-horizon EUR/USD signal-research pipeline with feature engineering, PCA, ML model comparison and backtesting.

**Reported test result**

`9.4% return` · `6% market exposure`

</td>
</tr>

<tr>
<td width="50%" valign="top">

### ⚡ [Lock-Free-Oriented Limit Order Book](https://github.com/theakshaybande/lockfree-limit-order-book)

**C++20 · LOB · Memory Pools · Cache-Aware Design**

Deterministic price-time-priority order book with direct order-ID indexing, fixed-capacity memory pools and no per-order heap allocation on critical paths.

**Focus**

`Latency` `Memory` `Cache` `Order Matching`

</td>

<td width="50%" valign="top">

### ⚙️ [Branchless Matching Engine](https://github.com/theakshaybande/branchless-matching-engine)

**C++20 · Matching Engine · Microbenchmarking**

Research implementation comparing conventional branching with branchless-style matching over deterministic synthetic order flow.

Includes a **1,000,000 order-pair benchmark** and explicit analysis of branch-prediction effects.

</td>
</tr>

<tr>
<td width="50%" valign="top">

### 📡 [C++20 Market Data Pipeline](https://github.com/theakshaybande/cpp20-market-data-pipeline)

**C++20 · Atomics · string_view · from_chars · CMake**

Low-overhead market-data parsing and processing scaffold focused on tokenization, normalization, aggregation and concurrency-oriented systems design.

**Focus**

`Market Data` `Parsing` `Atomics` `Low Allocation`

</td>

<td width="50%" valign="top">

### 🌐 [Market Chaos Lab](https://github.com/theakshaybande/market-chaos-lab)

**C++20 · Agent-Based Markets · LOB · Microstructure**

Order-driven market simulator where momentum, mean-reversion, and random trader archetypes interact through shared liquidity.

Market behavior emerges through an explicit limit-order-book matching process.

</td>
</tr>

<tr>
<td width="50%" valign="top">

### 🤖 [HFT Reinforcement Learning Trader](https://github.com/theakshaybande/hft-rl-trader)

**Python · PyTorch · Gymnasium · DQN**

Experimental reinforcement-learning environment for inventory management and quote placement within a stylized limit-order-book market.

**Model includes**

`Inventory Risk` `Spread` `Fees` `PnL` `Reward Design`

</td>

<td width="50%" valign="top">

### 📊 Systematic Trading Research

**Python · Backtesting · Execution · Transaction Costs**

Research infrastructure around signal validation, execution assumptions, transaction costs, market regimes and systematic strategy development.

**Focus**

`Signals` `Backtesting` `Slippage` `Risk` `Execution`

</td>
</tr>
</table>

---

# Technical Stack

### Languages

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B17%2F20-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-121011?style=flat-square&logo=gnubash&logoColor=white)

### Machine Learning & Research

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-ML-blue?style=flat-square)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![STUMPY](https://img.shields.io/badge/STUMPY-Matrix_Profile-6f42c1?style=flat-square)

### Systems & Infrastructure

![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![CMake](https://img.shields.io/badge/CMake-064F8C?style=flat-square&logo=cmake&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

---

## Core Competencies

```text
QUANTITATIVE RESEARCH
├── Financial Time Series
├── Statistical Modeling
├── Regime Detection
├── Backtesting
├── Transaction Costs
└── Risk Analysis

MARKET MICROSTRUCTURE
├── Limit Order Books
├── Matching Engines
├── Market Data
├── Order Flow
├── Liquidity
├── Execution
└── Market Making

LOW-LATENCY C++
├── C++17 / C++20
├── STL
├── Atomics
├── Concurrency
├── Memory Management
├── Lock-Free Concepts
├── Cache-Aware Design
└── Branch Prediction

FINANCIAL ML
├── Supervised Learning
├── Unsupervised Learning
├── Deep Learning
├── Reinforcement Learning
├── Regime Modeling
└── Multivariate Time Series
```

---

# Selected Academic Research

| Project | Research Area |
|---|---|
| [**Quantum Trend**](https://github.com/theakshaybande/Quantum_trend) | Quantitative academic research |
| [**Crypto Time-Series Motifs**](https://github.com/theakshaybande/crypto-time-series-motifs) | Financial data ingestion and motif research |
| [**Climate Modeling**](https://github.com/theakshaybande/climate-modeling) | Unsupervised learning and regional modeling |

---

# Current Research & Engineering Focus

```mermaid
flowchart LR

    A[Financial Markets]

    A --> B[Quantitative Research]
    A --> C[Market Microstructure]
    A --> D[Financial ML]
    A --> E[Trading Systems]

    B --> B1[Time Series]
    B --> B2[Regime Detection]
    B --> B3[Backtesting]

    C --> C1[LOB]
    C --> C2[Order Flow]
    C --> C3[Market Making]

    D --> D1[Supervised ML]
    D --> D2[RL]
    D --> D3[Clustering]

    E --> E1[C++20]
    E --> E2[Low Latency]
    E --> E3[Market Data]
```

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

</div>

<br>

<div align="center">

<img
  width="95%"
  src="https://github-readme-activity-graph.vercel.app/graph?username=theakshaybande&theme=github-compact&hide_border=true&area=true"
  alt="GitHub Contribution Activity"
/>

</div>

---

# What I Am Building Toward

I am interested in engineering and research problems where **machine intelligence, quantitative methods, high-performance computing, and real financial markets intersect**.

<div align="center">

### Quantitative Research · Quant Development · Algorithmic Trading
### Financial ML · Market Microstructure · Low-Latency Trading Systems

<br>

> **Build. Measure. Research. Iterate.**

<br>

[![GitHub](https://img.shields.io/badge/Explore_My_Work-GitHub-181717?style=for-the-badge&logo=github)](https://github.com/theakshaybande)

</div>
