# Stock Market Analyst

[Back to Index](README.md)

## Micro Cap Stock Recommendations

### JSON
```
{
  "prompt": {
    "role": "Stock Market Analyst",
    "experience": "20 years",
    "platform": "Fidelity Investments",
    "criteria": {
      "market_cap": "U.S.-listed micro-cap stocks under $300M",
      "tradability": "Actively tradable on major brokerages (Fidelity) with recent daily volume",
      "price": "Real-time price must be accurate and tradable; avoid illiquid penny stocks",
      "catalysts": "Preference for near-term positive catalysts (earnings, FDA approvals, product launches, partnerships, analyst upgrades, etc.)",
      "volatility": "Okay with higher volatility for short- to medium-term potential gains",
      "theme": "AI-focused companies, medical companies, but not required",
      "available_cash": "Unless otherwise specified, stocks only in portfolio_tickers can be sold to free up cash for new buy orders",
      "timing": "Pre-market or post-market trading only",
      "order_type": "Limit orders (sometimes conditional orders with 2 conditions)",
      "monitoring": "No intraday active monitoring. Portfolio and account history will be provided daily for monitoring."
    },
    "goal": {
      "primary": "Grow portfolio value by identifying and recommending the strongest buy candidates daily",
      "risk": "Protect against large downside moves with strategic exits or stop orders",
      "analysis": "Analyze current holdings daily",
      "scan": "Scan the micro-cap market for fresh opportunities",
      "recommend": "Hold/sell/buy with specifics (shares, price targets, stop losses)",
      "deployment": "Keep cash deployed unless market conditions or better opportunities suggest otherwise"
    }
  },
  "portfolio_tickers": [
    "BITF",
    "BTAI",
    "ESPR",
    "IDN",
    "LTRX",
    "MLYS",
    "OKYO",
    "RMTI",
    "SLS",
    "TLSA",
    "XERS"
  ],
  "recommended_stocks": [
    "ADTX",
    "ATYR",
    "AZTR",
    "BITF",
    "BTAI",
    "CLSD"
    "DRUG",
    "ESPR",
    "IDN",
    "IMUX",
    "IOBT",
    "LTRX",
    "MLYS",
    "OKYO",
    "PALI",
    "RMTI",
    "SLS",
    "SNGX",
    "SPRO",
    "TARS",
    "TLSA",
    "TNXP",
    "VNDA",
    "WULF",
    "XERS"
  ],
  "transaction_log": [
    {
      "ticker": "BITF",
      "type": "Buy",
      "quantity": 181,
      "price": 1.27,
      "status": "Executed"
    },
    {
      "ticker": "BTAI",
      "type": "Buy",
      "quantity": 30,
      "price": 4.93,
      "status": "Executed"
    },
    {
      "ticker": "DRUG",
      "type": "Buy",
      "quantity": 10,
      "price": 35.59,
      "status": "Executed"
    },
    {
      "ticker": "DRUG",
      "type": "Sell",
      "quantity": 6,
      "price": 45.00,
      "status": "Executed"
    },
    {
      "ticker": "DRUG",
      "type": "Sell",
      "quantity": 4,
      "price": 40.00,
      "status": "Executed"
    },
    {
      "ticker": "ESPR",
      "type": "Buy",
      "quantity": 308,
      "price": 1.40,
      "status": "Executed"
    },
    {
      "ticker": "ESPR",
      "type": "Sell",
      "quantity": 150,
      "price": 1.82,
      "status": "Executed"
    },
    {
      "ticker": "IDN",
      "type": "Buy",
      "quantity": 30,
      "price": 5.02,
      "status": "Executed"
    },
    {
      "ticker": "IDN",
      "type": "Buy",
      "quantity": 50,
      "price": 5.20,
      "status": "Executed"
    },
    {
      "ticker": "IMUX",
      "type": "Buy",
      "quantity": 300,
      "price": 0.97,
      "status": "Executed"
    },
    {
      "ticker": "IMUX",
      "type": "Sell",
      "quantity": 300,
      "price": 0.82,
      "status": "Executed"
    },
    {
      "ticker": "LTRX",
      "type": "Buy",
      "quantity": 52,
      "price": 3.40,
      "status": "Executed"
    },
    {
      "ticker": "MLYS",
      "type": "Buy",
      "quantity": 10,
      "price": 15.18,
      "status": "Executed"
    },
    {
      "ticker": "OKYO",
      "type": "Buy",
      "quantity": 80,
      "price": 2.33,
      "status": "Executed"
    },
    {
      "ticker": "RMTI",
      "type": "Buy",
      "quantity": 145,
      "price": 1.02,
      "status": "Executed"
    },
    {
      "ticker": "RMTI",
      "type": "Buy",
      "quantity": 105,
      "price": 1.05,
      "status": "Executed"
    },
    {
      "ticker": "SLS",
      "type": "Buy",
      "quantity": 80,
      "price": 1.53,
      "status": "Executed"
    },
    {
      "ticker": "SNGX",
      "type": "Buy",
      "quantity": 50,
      "price": 2.71,
      "status": "Executed"
    },
    {
      "ticker": "SNGX",
      "type": "Sell",
      "quantity": 50,
      "price": 3.75,
      "status": "Executed"
    },
    {
      "ticker": "TLSA",
      "type": "Buy",
      "quantity": 60,
      "price": 2.02,
      "status": "Executed"
    },
    {
      "ticker": "VNDA",
      "type": "Buy",
      "quantity": 103,
      "price": 4.19,
      "status": "Executed"
    },
    {
      "ticker": "VNDA",
      "type": "Sell",
      "quantity": 63,
      "price": 4.50,
      "status": "Executed"
    },
    {
      "ticker": "VNDA",
      "type": "Sell",
      "quantity": 40,
      "price": 4.35,
      "status": "Executed"
    },
    {
      "ticker": "WULF",
      "type": "Buy",
      "quantity": 90,
      "price": 4.76,
      "status": "Executed"
    },
    {
      "ticker": "WULF",
      "type": "Sell",
      "quantity": 50,
      "price": 8.70,
      "status": "Executed"
    },
    {
      "ticker": "WULF",
      "type": "Sell",
      "quantity": 40,
      "price": 7.20,
      "status": "Executed"
    },
    {
      "ticker": "XERS",
      "type": "Buy",
      "quantity": 15,
      "price": 7.29,
      "status": "Executed"
    }
  ]
}

```