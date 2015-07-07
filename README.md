Buncore
=======

A pure and powerful JavaScript Bunnycoin library.

## Principles

BUN is FUN... Bunnycoin is Love

## Get Started

```
npm install buncore
```

Using it in Node.js:

```javascript
var buncore = require('buncore');

assert(buncore.Address.isValid('BdsqKtHTXyrnPKYACMM4pk1K8MycJRCMSz'));
var simpleTx = new buncore.Transaction();
var simpleTx.from(unspent).to(address, amount);
simpleTx.sign(privateKey);
```

## Building the Browser Bundle

To build buncore full bundle for the browser:

```sh
gulp browser
```

This will generate files named `buncore.js` and `buncore.min.js`.

## Tests

Run all the tests:

```sh
gulp test
```

You can also run just the NodeJS tests with `gulp test:node`, just the browser tests with `gulp test:browser`
or create a test coverage report (you can open `coverage/lcov-report/index.html` to visualize it) with `gulp coverage`.

## License

Code released under [the MIT license](https://github.com/bitpay/bitcore/blob/master/LICENSE).

Copyright 2013-2015 BitPay, Inc. Bitcore is a trademark maintained by BitPay, Inc.
