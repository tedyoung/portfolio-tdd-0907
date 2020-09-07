# Getting Started

Test-driving the development of a simple stock portfolio tracking system.
This system isn't meant to be a trading system, merely track the current
value of stock holdings.

## Simplifying Assumptions

* USA stock symbols for sample data
* Pricing in whole dollars (stored as an int)
* Currency is in $
* Equities
* Transactions have date without time
* Console (terminal) based interface to start with

## Features

* View total value of portfolio
    * Cost basis (purchased value)
    * Stock holdings current value

* Buy a stock, enter:
    * Symbol
    * Quantity
    * Share price
    * Date

* Sell a stock, enter:
    * Symbol
    * Quantity
    * Share price
    * Date

### Optional

* Close a position, enter:
    * Symbol
    * Price sold
    * (uses today's date)

* View transactions

* Obtain pricing data from https://iexcloud.io/docs/api/#rest-how-to
    * https://iexcloud.io/docs/api/#quote
    * Sample: https://sandbox.iexapis.com/stable/stock/AAPL/quote?token=Tpk_c8187b42b499474fafb1cb44c3175c87

## Concrete Examples

* Open a portfolio and add a purchase 200 shares of AAPL at $125 on 2020/08/28

* Sell 100 shares of AAPL at $131 on 2020/09/01

