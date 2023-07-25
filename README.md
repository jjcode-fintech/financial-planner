# financial-planner

# Overview
This project is broken out in two parts. The analysis stimulates a personal finance planner for a crypto and stock portfolio .

1. Using the Alternative Free Crypto API to retrieve Bitcoin and Ethereum prices.  The analysis will allow users to visualize their savings composed by investments in shares and cryptocurrencies to assess if they have enough money as an emergency fund. It collescts Crypto BTC, ETH prices using the requests Library. Parsin the API JSON response to select only both crypto prices and store their respective prices in a variable.

2. Using the Alpaca Markets API to to pull historical stocks and bonds information. A retirement planning analysis was done with the Alpaca API historical closing prices for a retirement portfolio composed of stocks(SPY) and bonds(AGG) was reterived. Then running the Monte Carlo simulations to project the portfolio performance at 30 years. Using the Monte Carlo data we can calculate the expected portfolio returns given a specific initial investment amount.


