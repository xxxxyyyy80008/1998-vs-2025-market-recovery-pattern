
# 📊 S&P 500 Recovery Pattern Analysis: 1998-99 vs 2025-26
### Comparing the 1998 Crisis with the 2025 Market Drop

![Repository Banner](assets/images/repo_banner.png)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=flat&logo=jupyter&logoColor=white)](https://jupyter.org/)
[![Made with Love](https://img.shields.io/badge/Made%20with-❤-red.svg)](https://github.com/yourusername/sp500-recovery-pattern-analysis)

---

## 🎯 Project Overview

This repository contains a comprehensive analysis comparing the S&P 500 recovery patterns between:
- **1998-1999 LTCM Crisis Recovery** (24-month reference period)
- **2025-2026 Market Drop Recovery** (current/projected period)

The analysis uses date-aligned visualizations, statistical analysis, and historical pattern recognition to:
- ✅ Identify recovery trajectory similarities and differences
- ✅ Project potential 2026 market movements
- ✅ Provide data-driven trading recommendations
- ✅ Assess volatility and risk metrics

---

## 📊 Key Features

1. Comprehensive Visualizations
   - Price comparison charts with dual timelines
   - Normalized performance analysis
   - Statistical analysis with volatility bands
   - Moving average convergence/divergence
   - Daily and cumulative returns tracking

2. Statistical Analysis
   - 20-day moving averages
   - ±2σ volatility bands
   - Annualized volatility comparison
   - Maximum drawdown analysis
   - Recovery trajectory modeling
   
3. Trading Strategies
   - Quarter-by-quarter 2026 outlook
   - Sector rotation recommendations
   - Risk management framework
   - Position sizing guidelines
   - Entry/exit strategies

---


## 🚀 Quick Start

### **Option 1: View Online**
- 📓 [View Jupyter Notebook](notebooks/sp500_recovery_analysis.ipynb) (GitHub renders notebooks)
- 📑 [Read Executive Summary](docs/executive_summary.md)
- 💰 [Trading Recommendations](docs/trading_recommendations_2026.md)

### **Option 2: Run Locally**

#### Prerequisites
```bash
# Requires Python 3.8+
python --version

# Clone the repository
git clone https://github.com/yourusername/sp500-recovery-pattern-analysis.git
cd sp500-recovery-pattern-analysis
```

#### Install Dependencies
```bash
# Create virtual environment (recommended)
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install required packages
pip install -r notebooks/requirements.txt

```

#### Run the Analysis
```bash
# Launch Jupyter Notebook
jupyter notebook notebooks/sp500_recovery_analysis.ipynb

# Or use Jupyter Lab
jupyter lab notebooks/sp500_recovery_analysis.ipynb
```


## 📊 Visualizations

The analysis includes 8 comprehensive visualizations:

|--|--|--|

#VisualizationDescription1Price ComparisonSide-by-side actual price charts with calendar dates2Normalized ComparisonOverlay with normalized indices (base 100)3Dual TimelineSingle chart with dual Y-axes for both periods4Statistical Analysis20-day MA with ±2σ volatility bands5Daily ReturnsDay-over-day percentage changes6Cumulative ReturnsRunning total return progression7Moving AveragesMultiple timeframe MA analysis8Executive DashboardComprehensive multi-panel overview



## 📚 Documentation

#### Core Documents
- 📖 Executive Summary - High-level project overview
- 📈 Trading Recommendations 2026 - Detailed trading strategies
- 🔬 Methodology - Technical approach and rationale
- 📊 Visualization Guide - Explanation of each chart

#### Key Features
- ✅ Date-aligned comparison (not just overlays)
- ✅ Dual Y-axis for accurate price scaling
- ✅ Real-time outperforming/underperforming indicators
- ✅ Statistical rigor (volatility, drawdowns, moving averages)
- ✅ Projection capability for incomplete 2025 data
- ✅ Quarter-by-quarter 2026 outlook

## 🛠️ Technical Stack
- Language: Python 3.8+
- Core Libraries:

  - pandas - Data manipulation
  - numpy - Numerical computing
  - matplotlib - Visualization
  - yfinance - Market data retrieval


- Environment: Jupyter Notebook
- Data Source: Yahoo Finance (S&P 500: ^GSPC)
