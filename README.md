lamassu-coinbase
================

[![Build Status](https://travis-ci.org/lamassu/lamassu-coinbase.svg)](https://travis-ci.org/lamassu/lamassu-coinbase)

Lamassu Coinbase ticker and trader


### Testing

1. Open [`mockConfig.template.json`](https://github.com/lamassu/lamassu-coinbase/blob/master/test/mockConfig.template.json) file, and input your Coinbase [credentials](https://www.coinbase.net/account/security/api/) there,
2. Make sure to check there:
  - [x] Account balance,
  - [x] Buy limit order,
  - [x] Sell limit order.
2. Rename `mockConfig.template.json` to `mockConfig.json`,
3. Type this into your terminal:

```bash
npm update # in case you cloned via git
npm test
```

> NOTE: Two last tests depend on your account having $5 of available balance (both in USD and BTC).
