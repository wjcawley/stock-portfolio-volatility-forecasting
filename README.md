# Stock Portfolio Volatility Forecasting

In this project, the Commercial Banking Corporation (the "Bank") seeks to better understand and forecast the behavior of stock price fluctuations in order to make more informed investment and risk management decisions. The Bank aims to identify which securities are most suitable for volatility modeling using ARCH/GARCH methodologies.

To address this challenge, our team developed multiple models including: GARCH(1,1)-Normal, GARCH(1,1)-t, GJR-GARCH(1,1,1)-Normal, and GJR-GARCH(1,1,1)-t. We opted to use the GJR-GARCH model due to limitations in the arch Python package. GJR-GARCH(1,1,1)-t yielded the lowest BIC, and was utilized in the rest of our analysis. We performed sensitivity and persistence analyses, and produced 30-day volatility forecasts for each of the top five stocks, which includes: Travelers, Goldman Sachs, Boeing, Microsoft, and Honeywell. We also provided recommendations for portfolios depending on the current risk appetite of the Bank.

## Tools Used:
- Python
- numpy
- pandas
- yfinance
- matplotlib
- arch
