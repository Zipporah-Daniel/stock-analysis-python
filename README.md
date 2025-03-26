# Stock Analysis Project using Python
# Overview
This is my first python project, where I analyzed the perfromance, risk, and trends of 6 major tech stocks. Using financial data from Yahoo Finance, I explored market trends and visualized key inights to undersand stock behaviour and make informed personal investment decisions
# Objectives
The aim of the project was to answer the following questions:
1) What was the change in price of the stocks over time?
2) What was the daily return of the stock on average?
3) What was the moving average of the various stocks?
4) What was the correlation between different stocks' daily retruns?
5) How much value do we put at risk by ivesting in a particular stock?
6) How can we attempt to predict future stock behaviour?

# Technologies used
  **Python Libraries**: Pandas, NumPy, Matplotlib, Seaborn, yfinance
  **Data Sources**: Yahoo Finance

# Key Features
## Data Collection
1) I used yfinance to download the stock data for 6 major tech stocks AAPL, GOOG, MSFT, AMZN, TSLA, and NVDA
2) I made sure the data was accurate by formatting the data indices and checking the structure of the columns

## Data Analysis
1) Change in Stock Prices: I created visualizations of the adjusted close prices over time to understand overall price trends for the stocks
2) Daily Return Analysis: I calculated the daily percentage change in prices to measure how much the stocks' values fluctuated on a day-to-day basis
3) Moving Averages: I used 10-day, 20-day, and 50-day moving averages to track trends and see how the stocks performed over different time periods
4) Correlation analysis: I explored the relationship between stock prices and their daily returns using heatmaps to spot any patterns or connections

## Risk Analysis
I estimated the potential losses from investments by calculating Value at Risk (Var) using Bootstrap method and Monte Carlo Simulation

# Visualization
I used Seaborn to create:
  1) Jointplots to see how two stocks. like TSLA and NVDA, relate to each other
  2) Heatmaps to highlight the strength of correlations between different stocks
  3) Scatterplots and Pairplots to visually explore the patterns in stock returns

## Important Concepts to Note
### Monte Carlo Simulation is used to predict possible outcomes for stock prices and assess risks
### Value at Risk (VaR) helps estimate how much money could be lost in a portfolio over a certain period of time. for example a 1% VaR means there is only a 1% chance of losing more than that amount in the given period
### Correlation Matrix shows how strongly different stocks are related to each other. The stocks have a strong positive relationship if the value is closer to +1, and if it is closer to -1, the stocks have a strong negative relationship. Looking at these relationships can help figure out ways to diversify a portfolio 

# Project Status
This project is a work in progress and is an ongoing effort as part of my journey to enhance my python skills. While it currently demonstrates key insights and and methodologies, I am still exploring ways to refine the codes and improve visualizations. Since I am learning python on my own, I see this project as a stepping stone towards tackling more comprehensive and bigger projects in the future.
