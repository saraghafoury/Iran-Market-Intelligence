
# Iran Market Intelligence

A data-driven project focused on analyzing Iranian
financial markets, investment funds, economic indicators,
and the impact of political and economic events.

## Project Overview

Iran Market Intelligence aims to collect, process,
analyze, and visualize financial and economic data
to understand market behavior and investment fund
performance.

The project initially focuses on selected investment
funds managed or offered by Mofid Brokerage.

In later stages, the platform will incorporate:
- Stock market data
- Macroeconomic indicators
- Political and economic news
- Global commodity prices
- Event-driven market analysis

## Main Objectives

- Collect historical investment fund data.
- Analyze fund returns and performance.
- Compare investment funds by category.
- Measure volatility and investment risk.
- Study market reactions to political and economic events.
- Identify historical relationships between
  economic indicators and financial markets.
- Build interactive dashboards.

## Selected Investment Funds

| Symbol | Fund |
|---|---|
| AYAR | Ayar |
| STEEL | Steel |
| KHODRAN | Khodran |
| SIMANO | Simano |
| OCTAN | Octan |
| DARUNO | Daruno |
| MADAN | Madan |
| TAVAN | Tavan |
| ORDINARY | To be verified |
| AVAND | To be verified |

Note: Official symbols, fund types, and share classes
must be verified before data collection.

## Data Sources

- TSETMC
- Fipiran
- Mofid Investment Funds
- Codal
- Central Bank of Iran
- Statistical Center of Iran
- Reuters
- World Bank
- FRED

## Technology Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- SQL
- Power BI
- Jupyter Notebook

## Project Structure

```text
config/       Fund metadata and settings
data/         Raw and processed datasets
notebooks/    Exploratory analysis
src/          Reusable Python modules
sql/          Database schemas and queries
tests/        Unit tests
dashboards/   Power BI dashboards
reports/      Analytical reports
```

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/USERNAME/Iran-Market-Intelligence.git

cd Iran-Market-Intelligence
```

### 2. Create a virtual environment

```bash
python -m venv .venv
```

Activate it:

Windows:

```bash
.venv\Scripts\activate
```

Linux / macOS:

```bash
source .venv/bin/activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Configure environment variables

Copy `.env.example` to `.env`
and configure the required settings.

### 5. Start exploring

```bash
jupyter lab
```

## Project Roadmap

- [x] Initial repository structure
- [ ] Fund metadata collection
- [ ] Historical fund data collection
- [ ] Data quality validation
- [ ] Exploratory data analysis
- [ ] Fund performance analysis
- [ ] Risk analysis
- [ ] Economic data integration
- [ ] Political and economic event dataset
- [ ] Event study analysis
- [ ] SQL database integration
- [ ] Power BI dashboard

## Disclaimer

This project is for educational and analytical purposes
only. It does not provide financial or investment advice.

Historical performance does not guarantee future results.

## Author

Sara Ghafouri

Data Analyst | Financial Data Analysis
