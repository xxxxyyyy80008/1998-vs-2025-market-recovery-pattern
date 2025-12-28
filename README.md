
# S&P 500 Recovery Pattern Analysis: 1998-99 vs 2025-26


[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)
[![Status](https://img.shields.io/badge/Status-Active-success.svg)]()



##  OVERVIEW

### Objective
Comprehensive comparison of market recovery patterns between the **1998 Crisis** and **2025 Market Drop**, analyzing whether historical patterns can predict future recovery trajectories through detailed technical and statistical analysis.

### Comparison Periods
- **Historical Benchmark**: 1998-1999 Crisis Recovery (24 months)
- **Current Analysis**: 2025-2026 Market Drop Recovery (actual data + projections)

### Key Crisis Dates
- **1998 Crisis Trough**: October 8, 1998
- **2025 Crisis Trough**: April 8, 2025
- **Analysis Window**: 24 months (504 trading days) post-crisis
- **Pre-Crisis Context**: 57 trading days included for trend analysis

---

##  ANALYTICAL FRAMEWORK

### Data Processing Methodology

#### 1. **Date Alignment Strategy**
- Both periods aligned to start at the same calendar date
- Crisis points synchronized for direct visual comparison
- 1998 timeline used as reference baseline
- 2025 dates shifted to overlay on 1998 timeline

#### 2. **Data Padding & Projection**
When 2025 data is incomplete:
- Historical pattern extrapolation using 1998 recovery trajectory
- Scaling factor applied to match current 2025 price levels
- Clear distinction between actual and projected data
- Projected period shaded/marked in visualizations

#### 3. **Normalization Methods**
- **Percentage Change**: All prices normalized to crisis point (0% reference)
- **Index-based**: First trading day = 100
- **Calendar Alignment**: Date offsets calculated for temporal comparison

---

##  VISUALIZATION SUITE (11 Components)

### **Core Price Comparisons**

#### **Visualization 1: Absolute Price Comparison**
- Side-by-side subplots showing actual prices
- Separate timelines for each crisis period
- Crisis point markers clearly indicated
- Projected period shading (if applicable)
![](images/visualization_1_price_comparison.png)

**Key Elements**:
- Date format: YYYY-MM with 3-month intervals
- Crisis point marked with vertical dashed line
- Actual vs projected data distinguished by opacity/shading

#### **Visualization 2: Normalized Overlay Comparison**
- Single chart with both series overlaid
- Crisis points aligned to 0% baseline
- Percentage returns from crisis point
- Secondary x-axis showing 2025 equivalent dates
![](images/images/visualization_2_normalized.png)

**Features**:
- 1998 series: Blue line, circular markers
- 2025 actual: Orange line, square markers
- 2025 projected: Dashed orange line (if applicable)
- Milestone markers every 6 months
- Positive/negative territory shading

#### **Visualization 3: Dual Y-Axis Timeline Comparison**
- Single chart with independent Y-axes for each period
- Left axis: 1998 prices ($)
- Right axis: 2025 prices ($)
- Direct visual comparison of recovery magnitude
![](images/images/visualization_3_dual_timeline.png)

**Annotations Include**:
- Starting prices and returns for both periods
- Current position marker (2025)
- Performance comparison box
- Month interval markers (6M, 12M, 18M, 24M)

### **Statistical Analysis**

#### **Visualization 4: Statistical Summary with Volatility Bands**
- Dual Y-axis statistical overlay
- 20-day moving average for both periods
- ±2σ (standard deviation) volatility bands
- Bollinger Band-style analysis
![](images/images/visualization_4_statistical.png)

**Statistical Metrics Displayed**:
- Average price comparison
- Annualized volatility (%)
- Maximum drawdown from peak (%)
- Current sigma distance from mean
- Band width as percentage of price

**Key Insights Box**:
- Volatility comparison (more/less/similar)
- Price position vs moving average
- Sigma status (high volatility/stabilizing/normal)
- Data coverage percentage

#### **Visualization 5: Daily Returns Distribution**
- Histogram comparison (1998 vs 2025)
- Mean return marked with vertical line
- Zero-line reference
- Frequency distribution of daily percentage changes
![](images/visualization_5_daily_returns.png)

**Metrics**:
- Mean daily return
- Standard deviation
- Distribution shape comparison
- Outlier identification

#### **Visualization 6: Cumulative Returns**
- Progressive return tracking from crisis point
- Compounded daily returns
- Zero-line baseline reference
- Time-series comparison
![](images/visualization_6_cumulative_return.png)

**Shows**:
- Total cumulative gain/loss over time
- Relative performance trajectory
- Recovery acceleration patterns

### **Technical Analysis**

#### **Visualization 7: Moving Average Analysis**
- 20-day and 50-day moving averages
- Price crossover identification
- Trend signals (bullish/bearish)
- Support/resistance level visualization
![](images/visualization_7_moving_averages.png)

**Technical Signals**:
- 20-MA above 50-MA: Bullish trend
- 20-MA below 50-MA: Bearish trend
- Price above/below MA: Momentum indication
- Moving average convergence/divergence

**Summary Statistics**:
- Final MA values and deviations
- Trend status assessment
- Days until MA calculations become meaningful

#### **Visualization 8: Rolling Volatility (20-Day Window)**
- Annualized volatility over time
- Volatility spikes identification
- Market stabilization tracking
- 20% high volatility reference line
![](images/visualization_8_rolling_volatility.png)

**Insights**:
- Volatility clustering periods
- Market calm vs turbulent phases
- Recovery stability assessment

#### **Visualization 9: Risk-Reward Analysis**
Two-part visualization:

**Part A - Scenario Analysis**:
- Bear Case: -10% return (10% probability)
- Base Case: +5% return (20% probability)
- Bull Case: +30% return (50% probability)
- Best Case: +45% return (20% probability)

**Part B - Investment Strategy Scatter**:
- X-axis: Maximum Drawdown Risk (%)
- Y-axis: Expected Return (%)
- Strategies plotted:
  - Conservative DCA
  - Moderate DCA
  - Aggressive Entry
  - Leveraged 1.5x
- Optimal zone highlighted (8-18% risk, 15-35% return)
![](images/visualization_9_risk_analysis.png)

#### **Visualization 10: Price Projection Chart**
- Complete 1998 recovery on left Y-axis
- 2025 actual + projected on right Y-axis
- Projection methodology clearly indicated
- Milestone markers (6M, 12M, 18M, 24M)
![](images/visualization_10_projections.png)

**Projection Method**:
1. Use 1998 pattern as template
2. Scale to match 2025 current price level
3. Apply growth rates from historical pattern
4. Mark transition from actual to projected data

**Key Information Boxes**:
- Current status (price, return, days elapsed)
- Projected end state (price, return, expected gain)
- Days/months remaining
- 1998 benchmark comparison
- Projection methodology note

### **Comprehensive Summary**

#### **Visualization 11: Multi-Panel Analysis Dashboard**
9-panel grid layout providing holistic view:

**Top Row (Metrics)**:
1. **1998 Crisis Metrics**: Crisis/recovery prices, total return, duration, volatility, max drawdown
2. **2025 Crisis Metrics**: Current prices, return to date, duration, volatility, max drawdown
3. **Performance Comparison**: Verdict (outperforming/tracking/underperforming), progress percentage

**Middle Row (Returns)**:
4. **Normalized Returns**: Percentage change from crisis point, aligned timelines
5. **Cumulative Returns**: Compounded gains over time with area fill
6. **30-Day Rolling Volatility**: Annualized volatility comparison with 20% reference line

**Bottom Row (Risk Analysis)**:
7. **Drawdown from Peak**: Maximum loss from running high, -10%/-20% reference lines
8. **Recovery Speed Table**: 
   - Milestone achievements (+5%, +10%, +15%, +20%)
   - Days to reach each milestone
   - 1998 vs 2025 comparison
   - Overall pace assessment

![](images/images/images/visualization_11_summary.png)

---

## 📊 KEY METRICS CALCULATED

### Price Performance
- **Starting Price**: Crisis point price ($)
- **Ending/Current Price**: Final or most recent price ($)
- **Minimum Price**: Lowest point during period ($)
- **Maximum Price**: Highest point during period ($)
- **Total Return**: Percentage gain/loss from crisis point (%)
- **Max Drawdown**: Largest peak-to-trough decline (%)
- **Max Gain**: Largest gain from starting point (%)
- **Average Price**: Mean price over entire period ($)

### Risk Metrics
- **Annualized Volatility**: Standard deviation of daily returns × √252 (%)
- **Daily Return Mean**: Average daily percentage change (%)
- **Daily Return Std Dev**: Standard deviation of daily returns (%)
- **Sharpe-style Ratios**: Risk-adjusted return calculations
- **Sigma Distance**: Current deviation from moving average (σ)

### Technical Indicators
- **20-Day Moving Average**: Short-term trend indicator
- **50-Day Moving Average**: Medium-term trend indicator
- **Bollinger Bands**: ±2σ volatility bands around 20-day MA
- **Band Width**: Volatility band range as % of price
- **Price vs MA**: Position above/below moving averages

### Recovery Metrics
- **Days to Milestones**: Time to reach +5%, +10%, +15%, +20% recovery
- **Cumulative Returns**: Compounded daily returns over time
- **Recovery Speed**: Comparative pace of recovery (1998 vs 2025)
- **Progress Percentage**: % of expected recovery period completed

---

## 🎯 INTERPRETATION GUIDELINES

### Performance Assessment

#### **Outperforming Scenario** (2025 > 1998)
- 2025 return exceeds equivalent 1998 return at same timepoint
- Faster milestone achievement
- Lower volatility with similar returns
- Higher cumulative gains
- **Verdict**: ✓ OUTPERFORMING

#### **Tracking Similar Scenario** (Within ±2%)
- Returns within 2 percentage points of 1998
- Similar volatility levels
- Comparable recovery speed
- **Verdict**: ≈ TRACKING SIMILAR

#### **Underperforming Scenario** (2025 < 1998)
- 2025 return lags equivalent 1998 return
- Slower milestone achievement
- Higher volatility with lower returns
- Lower cumulative gains
- **Verdict**: ⚠ UNDERPERFORMING

### Volatility Interpretation

#### **High Volatility** (Sigma > 1.5 or Ann. Vol > 25%)
- Market still in turbulent phase
- Higher risk environment
- Potential for sharp moves in either direction
- **Status**: ⚠ High volatility

#### **Normal Range** (0.5 < Sigma < 1.5 or 15% < Vol < 25%)
- Market showing typical crisis recovery volatility
- Moderate risk environment
- **Status**: ≈ Normal range

#### **Stabilizing** (Sigma < 0.5 or Vol < 15%)
- Market calming down
- Lower risk environment
- Recovery gaining confidence
- **Status**: ✓ Stabilizing

### Technical Signal Interpretation

#### **Bullish Signals**
- Price above both 20-day and 50-day MA
- 20-day MA crosses above 50-day MA (Golden Cross)
- Price breaking above upper Bollinger Band
- Decreasing volatility with rising prices
- **Trend**: Bullish ✓

#### **Bearish Signals**
- Price below both moving averages
- 20-day MA crosses below 50-day MA (Death Cross)
- Price breaking below lower Bollinger Band
- Increasing volatility with falling prices
- **Trend**: Bearish ⚠

#### **Neutral/Consolidation**
- Price oscillating around moving averages
- MAs moving sideways
- Price within Bollinger Bands
- Moderate, stable volatility
- **Trend**: Consolidating ≈

---

## ⚠️ IMPORTANT NOTES & LIMITATIONS

### Data Considerations

#### **Historical Data Accuracy**
- Data sourced from Yahoo Finance (^GSPC)
- Adjusted for splits and dividends
- Pre-market and after-hours data excluded
- Timezone normalized to UTC

#### **Projection Limitations**
- **Assumption**: 2025 follows 1998 pattern
- **Reality**: Each crisis is unique with different:
  - Economic fundamentals
  - Market structure
  - Policy responses
  - Global conditions
- **Use Case**: Scenario analysis, not prediction
- **Disclaimer**: Past performance ≠ future results

### Analytical Constraints

#### **Data Availability**
- 2025 analysis depends on available historical data at time of execution
- Insufficient data (< 20 days) limits moving average calculations
- Volatility metrics require minimum window size
- Statistical significance improves with longer timeframes

#### **Alignment Methodology**
- Calendar date alignment may not capture seasonal effects
- Trading day counts may vary due to holidays
- Different market microstructure (1998 vs 2025)
- Technology and trading algorithm differences

#### **Projection Method**
- Simple pattern replication, not econometric modeling
- No consideration of fundamental differences
- Scaling assumes linear relationship
- No regime change modeling

### Usage Recommendations

#### **For Investment Decisions**
- ⚠️ Use as one input among many
- Combine with fundamental analysis
- Consider current economic conditions
- Consult financial advisor
- Understand your risk tolerance

#### **For Research & Analysis**
- ✓ Pattern recognition and comparison
- ✓ Historical context understanding
- ✓ Risk-reward scenario modeling
- ✓ Volatility regime analysis
- ✓ Educational purposes

#### **Not Suitable For**
- ❌ Sole basis for investment decisions
- ❌ Short-term trading signals
- ❌ Guaranteed outcome predictions
- ❌ Risk-free investment strategies

---

## 📝 SUMMARY OUTPUT STRUCTURE

### Terminal Output Includes:

1. **Data Availability Summary**
   - Period covered for each crisis
   - Number of actual trading days
   - Number of projected days (if applicable)

2. **Statistical Comparison Table**
   - All key metrics side-by-side
   - 1998 vs 2025 comparison
   - Percentage differences

3. **Key Insights**
   - Performance relative to historical benchmark
   - Volatility comparison
   - Recovery speed assessment
   - Current trend status

4. **Milestone Projection Table**
   - Expected dates to reach recovery milestones
   - Comparison with 1998 achievement dates
   - Projected vs actual (when available)

5. **Date Alignment Information**
   - Original date ranges
   - Aligned date ranges
   - Offset calculations
   - Explanation of methodology

---

## 🔧 CONFIGURATION PARAMETERS

### Fixed Parameters
- **Random Seed**: 3407 (for reproducibility)
- **Trading Days/Month**: 21
- **Analysis Months**: 24
- **Prior Days Context**: 57
- **Moving Average Windows**: 20-day, 50-day
- **Volatility Window**: 20-day rolling
- **Annualization Factor**: √252 (trading days/year)
- **Bollinger Bands**: ±2σ

### Styling Configuration
- **Plot Style**: ggplot base with whitegrid
- **Figure Size**: (15, 7.7) inches standard
- **Font Size**: 11pt base
- **Colors**: 
  - 1998: Blue (#1f77b4)
  - 2025: Orange (#ff7f0e)
  - Bullish: Green
  - Bearish: Red
  - Projected: Gray transparency

---

This analytical framework provides a comprehensive methodology for comparing crisis recovery patterns, combining visual analysis, statistical metrics, and technical indicators to assess market behavior under stress conditions. The dual-timeline comparison with careful date alignment allows for meaningful pattern recognition while maintaining awareness of the inherent limitations in historical pattern analysis.



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


## 📜 License

This project is licensed under the MIT License - see the LICENSE file for details.

**Citation**

```bibtex
@misc{sp500recovery2025,
  author = {Your Name},
  title = {S&P 500 Recovery Pattern Analysis: 1998-99 vs 2025-26},
  year = {2025},
  publisher = {GitHub},
  url = {https://github.com/yourusername/sp500-recovery-pattern-analysis}
}
```