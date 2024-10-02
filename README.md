# Creating-a-Mutual-Fund-Plan-with-Python

This project focuses on developing a mutual fund plan using Python by analyzing historical stock data. By selecting stocks with high returns and low volatility, the plan aims to provide a balance between risk and reward.

## Project Overview

In this project, I:
- Collected and cleaned historical stock data of Nifty 50 companies.
- Calculated key metrics such as **Return on Investment (ROI)** and **volatility** for each stock.
- Selected a set of stocks based on these metrics to create a balanced mutual fund plan.
- Projected the future value of investments using the selected stocks.

## Steps:

1. **Data Collection**: 
   - Downloaded historical stock prices of major Nifty 50 companies.
   
2. **Data Preprocessing**: 
   - Converted dates into a proper datetime format and normalized the data for analysis.

3. **Stock Selection**: 
   - Evaluated each stock's performance based on ROI and volatility to find the most promising ones.

4. **Mutual Fund Plan Creation**:
   - Constructed a portfolio with a mix of high-ROI and low-volatility stocks.

5. **Future Value Calculation**: 
   - Calculated the projected future value of monthly investments based on stock performance.

## Dependencies

- Python 3.x
- Pandas
- Plotly
- Numpy
