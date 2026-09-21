# Dangote Cement Investment Analysis

## Overview

This repository contains a quantitative and fundamental investment analysis of Dangote Cement Plc (`DANGCEM`), completed as **Letter D** of the A–Z Equity Research Series.

The project examines the company’s historical market performance, 2026 year-to-date results, financial performance, risk profile, technical structure and possible future price outcomes. Dangote Cement is compared with the NGX All-Share Index and selected cement-industry peers, particularly Lafarge Africa and BUA Cement.

The analysis is designed to answer a central investment question:

> Does Dangote Cement’s financial strength, market position and growth outlook adequately compensate investors for the risk of holding the stock?

## Analysis period

- **Historical period:** January 2020 to December 2025
- **2026 YTD period:** January 2026 to September 18, 2026
- **Technical analysis:** Most recent 252 trading days as of September 18, 2026
- **Monte Carlo forecast:** 10,000 simulations over 252 trading days

## Areas covered

The project includes:

- Historical and 2026 YTD price performance
- Comparison with the NGX All-Share Index
- Peer comparison with Lafarge Africa and BUA Cement
- Annualized return and volatility
- Sharpe ratio
- Beta and CAPM-required return
- Maximum drawdown
- Value at Risk and Conditional Value at Risk
- Revenue, profitability, cash flow and debt analysis
- Moving-average and price-structure analysis
- Monte Carlo simulation

## Key findings

### Historical performance

Dangote Cement generated an annualized return of approximately **29.4%** during the historical period, with annualized volatility of **34.1%** and a maximum drawdown of approximately **49.5%**. Its beta of **1.37** indicates that the stock was more responsive to broader market movements than the NGX All-Share Index.

The company’s historical return fell below its CAPM-required return of approximately **34.5%**, while its Sharpe ratio of **0.37** showed a relatively modest excess return for each unit of total risk taken. Lafarge Africa delivered a higher historical annualized return and a stronger Sharpe ratio over the same period.

### 2026 YTD performance

Dangote Cement returned approximately **72.4%** as of September 18, 2026. Its annualized volatility stood at **35.6%**, while its Sharpe ratio improved to **1.88**. The stock recorded a maximum drawdown of approximately **24.5%** during the period.

Despite this strong performance, Lafarge Africa remained the standout cement stock, returning approximately **156%**. The NGX All-Share Index also produced stronger risk-adjusted performance, with lower volatility, a smaller drawdown and a higher Sharpe ratio.

### VaR and CVaR

Dangote Cement recorded a one-day 95% Historical VaR of approximately **0.74%**. This means daily losses exceeded 0.74% on about 5% of trading days within the 2026 YTD sample.

Its 95% CVaR of approximately **4.76%** shows that when losses moved beyond the VaR threshold, the average loss was considerably larger. For a hypothetical ₦1 million investment, this represents a VaR threshold of approximately **₦7,400** and an average extreme-day loss of approximately **₦47,600**.

### Financial performance

In H1 2026, revenue increased by approximately **21.4%**, from ₦2.07 trillion to ₦2.51 trillion. Operating profit rose from ₦811.0 billion to approximately ₦1.06 trillion, lifting the operating margin from **39.1% to 42.1%**.

Operating cash flow increased to approximately ₦1.06 trillion. However, capital expenditure more than doubled to ₦354.2 billion, leaving free cash flow broadly unchanged at approximately ₦702.0 billion. Total borrowings declined by approximately 46%, from ₦1.08 trillion at the end of 2025 to ₦581.0 billion in June 2026.

### Technical structure

The latest price of **₦1,050** was slightly below the 100-day moving average of **₦1,061.83** but above the 50-day moving average of **₦1,036.14**. With the 50-day moving average below the 100-day moving average, medium-term momentum slightly favoured sellers, although the price structure remained tight.

A recovery above the 100-day moving average would improve bullish momentum, while a break below the 50-day moving average could expose the stock to a deeper decline towards the support region around ₦900.

### Monte Carlo simulation

The simulation produced the following results:

- **Current price:** ₦1,050.00
- **5th-percentile final price:** ₦813.23
- **95th-percentile final price:** ₦2,516.81
- **Probability of finishing above the current price:** 81.12%
- **Probability of finishing below the current price:** 18.88%

The wide distribution indicates substantial uncertainty, with meaningful downside risk and considerable upside potential. These simulated outcomes represent possible price paths based on the assumptions used and should not be interpreted as forecasts.

## Tools and libraries

The analysis was completed in Python using:

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `mplfinance`

## Data sources

- Investo.ng API for Nigerian equity-market data
- Investing.com data for the NGX All-Share Index
- Dangote Cement annual and interim financial statements
- Dangote Cement investor-relations materials

## Investment conclusion

Dangote Cement remains a fundamentally strong business with a dominant position in Nigeria, growing Pan-African operations and significant production capacity. Its H1 2026 results showed that revenue growth was supported by higher volumes, stronger operating profitability and improved cash generation, while the reduction in borrowings strengthened its financial position. The increase in capital expenditure could support higher volumes and revenue over the long term, although the company must generate sufficient returns to justify the capital committed.

From an investment perspective, the outlook remains balanced. The stock’s 72.4% return in 2026 represents a significant improvement, but Lafarge Africa delivered stronger returns, while the NGX All-Share Index provided better risk-adjusted performance. Dangote Cement’s improving fundamentals and expansion plans support a constructive long-term outlook, but its elevated volatility, historical drawdowns and uncertain technical momentum suggest a more cautious near-term position.

## Disclaimer

This project is for educational and research purposes only. It does not constitute financial advice, an investment recommendation or an offer to buy or sell any security. Historical performance and simulated outcomes do not guarantee future results. Investors should conduct independent research and consider their objectives, risk tolerance and financial circumstances before making investment decisions.

## Author

**Olalekan Akinola**  
Financial Market Analyst and Investment Researcher

- [LinkedIn](https://www.linkedin.com/in/olalekan-akinola)
- [Lemm Financials](https://olalekanakinola.substack.com/)
- [GitHub](https://github.com/OlalekanAkinola)
