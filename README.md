# stocks-dash

A free, lightweight, and beautiful static dashboard for stock quotes using the [IEX API](https://iextrading.com/developer/). Stocks can be grouped into user-defined portfolios. Quotes update every 5 seconds. No API key required.

Based on the project <a href="https://github.com/toddwschneider/stocks">@toddwschneider/stocks</a>.

## Screenshot

[![sample stocks-dash]()]

## Customize

Edit the `PORTFOLIOS` variable within `index.html`. For example:

```js
const PORTFOLIOS = [{'name': 'Portfolio', 'symbols': ['AAPL', 'BAC', 'BRK.B', 'SPY', 'F',]}];
```

Note you can provide multiple portfolios:

```
const PORTFOLIOS = [{'name': 'Banks', 'symbols': ['MS', 'BAC', 'WFS']}, {'name': 'Tech', 'symbols': ['AAPL', 'GOOG', 'AMZN', 'NVDA']}];
```

## IEX API

You do not need to sign up for anything or get an API key to use the [IEX API](https://iextrading.com/developer/docs/), but usage is subject to their [terms of service](https://iextrading.com/api-terms/).

## Browser compatibility

The page uses the [Fetch API](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API), which means it does not work with Internet Explorer.
