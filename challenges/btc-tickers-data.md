# Context

Justin is our CEO here at Evil Corp.
He keeps hearing about how bitcoins and cryptocurrencies are the next big thing, but does not understand their financial value yet.
We need an real-time stats app with some graphs to make him see how crazy things are at the moment with BTC and all.

# Goal

We want you to fetch tickers from bitcoin exchange btc-e.nz, save to database the last order price.

_HINT: target the `last` field in the response from btc-e api_

- Tickers must be updated every minute
- You must display this data in line chart on the page in realtime (without page reload)
- Also Justin needs to be able to choose between 3 types of tickers: btc\usd, btc\eur, btc\rur

# Constraints

## Tooling

- To perform asynchronous tasks you must use **Sidekiq**
- To draw line chart you must use **d3.js**
- To update line chart data you must use **ActionCable**
- To fetch data from bitcoin exchange you can use **any http gem of your choice**

- To get tickers you need to perform GET requests to:
  - https://btc-e.nz/api/3/ticker/btc_usd
  - https://btc-e.nz/api/3/ticker/btc_eur
  - https://btc-e.nz/api/3/ticker/btc_rur

- Your code must be available on **GitHub**
- The application must be deployed on **Heroku**

## Timeline

We planned for a meeting with Justin in 1 week. Good luck!
