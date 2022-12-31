### FINANCIAL PLANNING USING APIs, JUPYTER NOTEBOOK, PYTHON, PANDAS AND  MCTForecastTool toolkit
___

# Focusing on APIs as part of the technical solution to create two financial analysis tools.

___

The first is a finacial planner that will allow users to visalize their savings composed by investments in shares and cryptocurrencies to assess if they have enough funds for emergency.

* I assume an average income of $12000 for the user.
* The user has savings comprised of both cryptocurrency, stocks and bonds. 
* I assume crypto assets as 1.2 BTH and 5.3 ETH
* Stocks and bonds are assumed at 50 SPY (stocks) and 200 AGG (bonds)


# I use crypto API to fetch JSON response and get the canadian price for BTH and ETH.
* I compute my users portfolio value for cryptocurrency and print results.

# I use Alpaca API to get the SPY (stocks) and AGG (bonds)
* The information is used to create a DataFrame

# I compute the savings health of my user and print the result.
* Printing how much they have in crypro as well as stocks and bonds
* I display the results on a Pie Chart
* I use conditional satements to validate current savings

## Retirement planning

## Using Alpaca API to fetch historical data closing prices for the retirement portfolio I use the MCTForecastTool toolkit to create a Monte Carlo simulation to project the portfolio performance at 30 years, 5 years and 10 years.

* I assume a weightes of 60% for SPY and 40% for AGG.
* I configure and execute Monte-Carlo simulation of 100 runs for 30 years ploting the simulation results, probability distribution and confidence level. 




