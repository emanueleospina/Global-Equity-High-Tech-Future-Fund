# 🌐 Global Equity High Tech Fund
### Invesco · UCITS ETF · Launched December 2023
 
> A quantitatively-driven, UCITS-compliant ETF investing in 33 global equity positions across three high-conviction technology subsectors. Designed, screened, and stress-tested as part of an academic collaboration with Invesco, and selected for potential future client offerings.
 
---
 
## 📋 Table of Contents
 
- [Fund Overview](#fund-overview)
- [Portfolio Composition](#portfolio-composition)
- [Investment Process](#investment-process)
- [Risk Analysis](#risk-analysis)
- [Performance & Backtesting](#performance--backtesting)
- [ESG Framework](#esg-framework)
- [Fund Metrics](#fund-metrics)
- [Attribution Analysis](#attribution-analysis)
- [Repository Structure](#repository-structure)
- [Disclaimer](#disclaimer)
---
 
## Fund Overview
 
| Field | Detail |
|---|---|
| **Fund Name** | Global Equity High Tech Fund |
| **Legal Status** | UCITS |
| **Base Currency** | USD |
| **Launch Date** | December 23, 2023 |
| **Equity Allocation** | 93.98% |
| **Liquidity** | 6.02% |
| **Total Holdings** | 33 positions |
| **Management Fee (R)** | 2.00% |
| **Management Fee (I)** | 1.25% |
| **Subscription Fee (max)** | 5.00% |
| **Minimum Investment** | $2,000 USD |
| **Current Expenses** | 1.69% |
 
The fund aims to generate income and long-term capital growth by investing in global equities. The asset allocation approach is based on a series of quantitative drivers focused on risk reduction while seeking significant returns over the long term. Target companies exhibit sustainable value and competitive advantages, often centered around emerging technologies, but with financially robust fundamentals within each subsector.
 
---
 
## Portfolio Composition
 
### Sector Allocation
 
| Subsector | Weight | Positions | Total Market Cap |
|---|---|---|---|
| Semiconductors | 48.24% | 16 | $3,017B USD |
| Aerospace & Defence | 25.14% | 11 | $341B USD |
| Quantum Computing | 20.33% | 6 | $4,810B USD |
| Liquidity (Cash) | 6.02% | — | — |
 
### Geographic Allocation
 
| Region | Weight | Key Holdings |
|---|---|---|
| 🇺🇸 United States | 43.78% | NVIDIA, Microsoft, AMD, Broadcom, Boeing, LAM Research |
| 🇪🇺 Europe | 23.66% | Airbus, Thales, STMicroelectronics, Infineon, SAAB, Rolls-Royce |
| 🌏 Rest of World | 14.74% | Hanwha Aerospace, SK Hynix, Toshiba, Tokyo Electron, Elbit Systems |
| 🇹🇼 Taiwan | 11.80% | TSMC, MediaTek, Novatek, Phison, Fitipower, Elite Semiconductor |
 
### Top 10 Holdings
 
| Rank | Company | Weight |
|---|---|---|
| 1 | Cash | 6.02% |
| 2 | Broadcom Inc. | 5.00% |
| 3 | Intel Corp | 5.00% |
| 4 | Microsoft Corp | 4.87% |
| 5 | NXP Semiconductors NV | 4.61% |
| 6 | LAM Research Corp | 4.30% |
| 7 | Applied Materials Inc. | 4.15% |
| 8 | Thales SA | 4.11% |
| 9 | NVIDIA Corp | 3.84% |
| 10 | Toshiba Corp | 3.46% |
 
---
 
## Investment Process
 
The portfolio was built through a rigorous multi-stage quantitative screening process, progressively filtering a universe of **195 initial candidates** down to **33 final positions** + **44 stock reserve** (factoring approach).
 
```
INITIAL UNIVERSE (195 stocks)
         │
         ▼
   ┌─────────────┐
   │  USD DRIVER │  Market Cap > $200M USD
   └─────────────┘
         │  Quantum Computing: 17 → retained
         │  Semiconductors:   144 → retained
         │  Aerospace:         34 → retained
         ▼
   ┌─────────────┐
   │  ESG DRIVER │  ESG Score > 2.20 (scale 0–7)
   └─────────────┘
         │  QC:  17 → 14
         │  Semi: 80 retained
         │  A&D:  17 retained
         ▼
   ┌─────────────┐
   │  R&D DRIVER │  R&D % of Total Expenses > 20%
   └─────────────┘
         │  QC:   8 retained
         │  Semi: 75 retained
         │  A&D:  13 retained
         ▼
   ┌──────────────┐
   │  DATA DRIVER │  Sufficient Bloomberg data availability
   └──────────────┘
         │
         ▼
  FINAL PICK-UP: 33 positions
  STOCK RESERVE: 44 positions (factoring approach)
```
 
### Driver Specifications
 
**1. USD Driver** — Minimum market capitalisation threshold of $200M USD, ensuring sufficient liquidity and institutional-grade investability across all three subsectors.
 
**2. ESG Driver** — Proprietary ESG scoring on a 0–7 scale, sourced from Bloomberg. Covers three pillars: Environmental (energy management, water management, ecological impact, sustainable products, GHG emissions, climate exposure, waste management), Social (occupational health & safety, data security, product quality, operational risk, ethics & compliance, labour practices, community relations), and Governance (board composition, executive compensation, shareholder rights, audit).
 
**3. R&D Driver** — R&D investment as a percentage of total company expenses, minimum 20%. This ensures the portfolio is composed of companies genuinely investing in technological advancement rather than mature businesses extracting rents. Sector averages:
- Semiconductors: avg 69.18% (range: 53.83%–85.33%)
- Aerospace & Defence: avg 40.05% (range: 20.25%–66.47%)
- Quantum Computing: avg 38.44% (range: 20.51%–54.31%)
**4. Data Driver** — Bloomberg data completeness check. Companies with insufficient historical data for robust risk modelling were excluded to maintain backtesting integrity.
 
---
 
## Risk Analysis
 
*Role: Risk Analyst — responsible for sector correlation analysis, VaR modelling, scenario stress testing, and risk indicator assignment.*
 
### Value at Risk (VaR) — Bloomberg PORT (as of Dec 1, 2023)
 
| Metric | Portfolio | Benchmark | Δ vs Benchmark |
|---|---|---|---|
| **VaR (MC, 1-day, 90%)** | 3.44 | 3.61 | **-0.17 ✅** |
| **CVaR (MC, 1-day, 90%)** | 5.24 | — | — |
 
The portfolio VaR is **lower than the benchmark** despite targeting high-growth technology sectors, demonstrating that the multi-driver screening process effectively filters for quality and stability.
 
### VaR by Sector
 
| Sector | VaR (MC) | CVaR (MC) | Portfolio Weight |
|---|---|---|---|
| Information Technology | 2.41 | 3.75 | 57.81% |
| Industrials (A&D) | 1.11 | 1.66 | 35.20% |
| Communication Services | 0.14 | 0.22 | 2.77% |
 
### Risk Indicators by Subsector
 
| Subsector | Risk Level (1–7) | Rationale |
|---|---|---|
| Semiconductors | **5** | High beta, cyclical demand, concentration risk |
| Aerospace & Defence | **5** | Geopolitical exposure, long development cycles |
| Quantum Computing | **6** | Early-stage technology, higher speculative premium |
 
### Scenario Stress Testing
 
Historical scenario analysis run through Bloomberg PORT across 12 market stress events:
 
| Scenario | Portfolio P&L ($) | Portfolio P&L (%) |
|---|---|---|
| Equity Markets Rebound 2009 | +77.03 | +33.99% |
| Equities Up 10% | +30.26 | +13.35% |
| EUR Up 10% vs USD | +25.11 | +11.08% |
| Greece Financial Crisis 2015 | -15.27 | -6.74% |
| Libya Oil Shock 2011 | -7.22 | -3.18% |
| Debt Ceiling Crisis 2011 | -41.33 | -18.24% |
| Oil Prices Drop 2010 | -30.61 | -13.51% |
| Equities Down 10% | -30.26 | -13.35% |
| Japan Earthquake 2011 | -10.64 | -4.69% |
| Russian Financial Crisis 2008 | -112.84 | -49.79% |
| Lehman Default 2008 | -47.17 | -20.81% |
| EUR Down 10% vs USD | -25.11 | -11.08% |
 
> The portfolio shows symmetrical equity sensitivity (+13.35% / -13.35% on ±10% equity moves) and meaningful EUR/USD currency exposure given European holdings (~23.66% of the portfolio).
 
---
 
## Performance & Backtesting
 
### Synthetic Benchmark Construction
 
The benchmark is a composite of three MSCI AC World indices, weighted to reflect the portfolio's sector allocation:
 
| Index | Weight |
|---|---|
| MSCI AC World Semiconductors & Semiconductor Equipment USD | 50% |
| MSCI AC World Aerospace & Defense USD | 36% |
| MSCI AC World Technology Hardware USD | 14% |
 
### Annual Performance vs. Benchmark
 
| Year | Fund | Benchmark | Outperformance |
|---|---|---|---|
| 2019 | +35.92% | +40.38% | -4.46% |
| 2020 | +19.14% | +16.93% | **+2.21%** |
| 2021 | +37.38% | +25.62% | **+11.76%** |
| 2022 | -19.87% | -21.80% | **+1.93%** |
| YTD (2023) | +43.41% | +36.15% | **+7.26%** |
| **5Y Total** | **+157.00%** | **+121.41%** | **+35.59%** |
 
### Forward-Looking Projections (Next 5Y, On Average)
 
| Metric | Estimate |
|---|---|
| Standard Deviation | 13% |
| Volatility | 33% |
| Expected Performance over Benchmark | 22% |
 
> *Past performance is not a guarantee of future results.*
 
---
 
## ESG Framework
 
ESG scoring was a key differentiator in portfolio construction. Every company in the final portfolio was scored across 12 sub-dimensions in three pillars using Bloomberg ESG data.
 
### Semiconductors — ESG Summary
 
| Company | ESG Score | Environmental | Social | Governance |
|---|---|---|---|---|
| NVIDIA Corp | **6.59** | High | High | High |
| Applied Materials | 6.53 | High | High | High |
| Advanced Micro Devices | 6.24 | High | High | High |
| STMicroelectronics | 6.09 | High | High | High |
| Tokyo Electron | 6.06 | High | High | High |
| Intel Corp | 5.99 | Medium | Medium | High |
| Novatek Microelectronics | 5.98 | Medium | High | High |
| LAM Research | 5.59 | Medium | Medium | High |
| NXP Semiconductors | 5.64 | Medium | High | High |
| MediaTek | 4.95 | Medium | Medium | Medium |
| Taiwan Semiconductor | 4.77 | Medium | Medium | Medium |
| Broadcom Inc. | 4.75 | Medium | Medium | High |
| SK Hynix | 4.68 | Medium | Medium | Medium |
| Phison Electronics | 5.17 | Medium | Medium | Medium |
| Fitipower Integrated Tech | 4.57 | Low | Medium | Medium |
| Elite Semiconductor | 4.57 | Low | Medium | Medium |
 
*Sector avg: 5.50 · Min threshold applied: 2.20 (scale 0–10 Bloomberg)*
 
### Aerospace & Defence — ESG Summary
 
| Company | ESG Score | Highlight |
|---|---|---|
| Bombardier Inc-B | **6.09** | Best in sector |
| Thales SA | 5.50 | Strong governance |
| Airbus SE | 5.49 | Strong environmental |
| Aerospace Industrial Develop | 5.83 | Strong social |
| Boeing Co | 4.51 | Medium overall |
| Aerovironment Inc | 4.71 | Medium overall |
| Hanwha Aerospace | 4.21 | Weak environmental |
| SAAB AB-B | 3.51 | Below sector avg |
| Aselsan Elektronik | 3.27 | Below sector avg |
| Rolls-Royce Holdings | 4.29 | Medium overall |
| Elbit Systems | 3.24 | Minimum threshold |
 
*Sector avg: 4.60 · Range: 3.24–6.09*
 
### Quantum Computing — ESG Summary
 
| Company | ESG Score |
|---|---|
| Toshiba Corp | **6.67** |
| INTL Business Machines | 5.71 |
| Microsoft Corp | 5.67 |
| Infineon Technologies | 4.62 |
| RTX Corp | 4.51 |
| Alphabet Inc-CL A | 4.30 |
 
*Sector avg: 5.24 · Range: 4.30–6.67*
 
---
 
## Fund Metrics
 
| Metric | Value |
|---|---|
| P/E Ratio | 27.73 |
| P/B Ratio | 4.76 |
| Return on Equity (ROE) | 13.06% |
| Dividend Yield | 1.51% |
| Portfolio Risk | 20.05 |
| Volatility | 36.95 |
| Alpha (over benchmark) | +0.33 |
| Sharpe Ratio | 1.18% |
| Beta (over benchmark) | +0.87 |
 
### Reference Stock Metrics
 
**NVIDIA (Semiconductors reference)**
 
| Metric | Value |
|---|---|
| EBITDA | $22.16B USD |
| Beta | 1.76 over benchmark |
| ESG Score | 6.59 |
| Sharpe Ratio | 1.02 |
| Alpha | 0.37 over benchmark |
| ROE | 17.93 |
| P/E | 62.01 |
| R&D Investment | 76.06% |
 
**Airbus SE (Aerospace & Defence reference)**
 
| Metric | Value |
|---|---|
| EBITDA | $6.95B USD |
| Beta | 0.96 over benchmark |
| ESG Score | 5.49 |
| Sharpe Ratio | 0.19 |
| Alpha | 0.35 over benchmark |
| ROE | 37.89 |
| P/E | 26.34 |
| R&D Investment | 51.43% |
 
**Microsoft (Quantum Computing reference)**
 
| Metric | Value |
|---|---|
| EBITDA | $108.5B USD |
| Beta | 1.18 over benchmark |
| ESG Score | 5.67 |
| Sharpe Ratio | 0.93 |
| Alpha | 0.10 over benchmark |
| ROE | 38.82 |
| P/E | 35.82 |
| R&D Investment | 47.19% |
 
---
 
## Attribution Analysis
 
5-year total return attribution (Bloomberg PORT, Dec 2023):
 
| Metric | Value |
|---|---|
| **Fund Total Return** | +156.97% |
| **Benchmark Total Return** | +121.41% |
| **Total Active Return** | **+35.56%** |
| Allocation Effect | +53.63% |
| Selection Effect | -161.75% |
| Currency Effect | -9.52% |
 
### Top Performing Holdings (5Y Total Return)
 
| Company | 5Y Return | Contribution |
|---|---|---|
| NVIDIA Corp | **+1,312%** | +16.23% |
| Fitipower Integrated Tech | +577% | +5.57% |
| Advanced Micro Devices | +558% | +5.34% |
| LAM Research Corp | +468% | +13.90% |
| Tokyo Electron Ltd | +391% | +5.99% |
| Applied Materials Inc | +390% | +14.21% |
| MediaTek Inc | +436% | +3.15% |
| Microsoft Corp | +288% | +11.80% |
| Carrier Global Corp | +230% | +4.71% |
| Hanwha Aerospace | +274% | +5.23% |
 
### Underperforming Holdings (5Y)
 
| Company | 5Y Return | Contribution |
|---|---|---|
| Boeing Co/The | -25.37% | -1.82% |
| Kyndryl Holdings | -29.87% | +0.26% |
| Bombardier Inc-B | -2.72% | +0.38% |
| Rolls-Royce Holdings | -2.31% | -2.15% |
 
---
 
## Repository Structure
 
```
global-equity-high-tech-fund/
│
├── README.md                          ← You are here
│
├── docs/
│   ├── GEHT_Fund_Prospectus.pdf       ← Full fund prospectus (17 pages)
│   └── Prospectus_Summary.pdf         ← 2-page investor factsheet
│
└── data/
    ├── InvescoMasterFile.xlsx          ← Bloomberg PORT export: holdings, VaR,
    │                                      attribution, scenario analysis
    └── INVESCO_FUTURES_TECH_FUND.xlsx  ← Supplementary data
```
 
---
 
## Fund Management Board
 
| Name | Role |
|---|---|
| Álvaro Ventura Martínez | Chief Executive Officer |
| Carlos Daniel Pérez | Chief Financial Officer |
| Emanuele Ospina Castellanos | Risk Analyst |
| Manuel Inglés Guirao | Sector Manager |
| Agnes Kadama | Sector Manager |
| Vicente Sanz Puertas | Sector Manager |
 
---
 
## Tools & Data Sources
 
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Bloomberg](https://img.shields.io/badge/Bloomberg_Terminal-000000?style=flat&logo=bloomberg&logoColor=white)
![Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=flat&logo=microsoft-excel&logoColor=white)
 
- **Bloomberg Terminal** — Portfolio risk (PORT), VaR modelling, ESG scoring, R&D data, scenario stress testing, attribution analysis
- **Python** — Quantitative screening, ESG driver computation, backtesting framework
- **Quant Finance** — Factor construction, synthetic benchmark design, alpha/beta decomposition
---
 
## Disclaimer
 
This repository is for educational and portfolio demonstration purposes only. The Global Equity High Tech Fund was designed as part of an academic project in collaboration with Invesco. Past performance does not guarantee future results. This does not constitute investment advice. All Bloomberg data is used under licence and remains the property of Bloomberg Finance L.P.
 
*Not a Deposit · Not FDIC Insured · Not Guaranteed by the Bank · May Lose Value · Not Insured by any Federal Government Agency.*
 
