# Payshares Wallet
[![Build Status](https://travis-ci.org/Payshares/payshares-wallet.svg?branch=master)](https://travis-ci.org/Payshares/payshares-wallet)

```
[![Coverage Status](https://coveralls.io/repos/payshares/payshares-wallet/badge.png)](https://coveralls.io/r/payshares/payshares-wallet)
[![Code Climate](https://codeclimate.com/github/payshares/payshares-wallet/badges/gpa.svg)](https://codeclimate.com/github/payshares/payshares-wallet)
```

Note: coverage by coveralls.io and codeclimate.com is under review

Stores encrypted data. The wallet server can't decrypt the data. Used by https://github.com/payshares/payshares-client to save the user's secret keys. 



## Getting Started

1. Get yourself a db: `gulp db:setup`
1. Get yourself a running server: `stex www --watch`
1. Start making requests against port 3000 (by default)

## Connect directly to mysql

`stex db-console`
