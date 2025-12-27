

#  Methodology

## Analysis Framework

### 1. Data Collection
- Source: Yahoo Finance API (yfinance)
- Ticker: ^GSPC (S&P 500 Index)
- Frequency: Daily closing prices
- Adjustment: None (using actual closing prices)

### 2. Date Alignment
- Crisis start dates aligned by calendar
- 1998 reference: October 8, 1998
- 2025 comparison: [Crisis date]
- Timeline: 24-month recovery window

### 3. Normalization
- Rebasing both periods to 100 at crisis start
- Formula: `normalized = (price / crisis_price) * 100`
- Enables direct percentage comparison

### 4. Statistical Calculations
- Moving Averages: Simple moving average (SMA)
- Volatility: Annualized standard deviation
- Drawdown: Peak-to-trough percentage decline
- Returns: Both daily and cumulative

### 5. Visualization Standards
- Color coding: Blue (1998), Orange (2025)
- Date alignment: Common calendar reference
- Dual axes: Separate scales where appropriate
- Annotations: Crisis points, milestones, projections

## Limitations

1. **Historical Pattern Assumption**
   - Assumes similar recovery mechanics
   - Market structure has evolved since 1998
   - Different macro environments

2. **Data Constraints**
   - 2025 data incomplete (ongoing)
   - Projections based on single historical analog
   - No fundamental analysis included

3. **Scope Limitations**
   - Focuses only on S&P 500 index
   - Does not account for individual stock variance
   - Excludes international markets

## Further Reading

- [Original 1998 LTCM Crisis Analysis]
- [Market Recovery Pattern Research]
- [Statistical Finance Methods]
```*
