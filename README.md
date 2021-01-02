# ReactNative BitcoinJS (react-native-expo-bitcoinjs-lib)

[![Build Status](https://travis-ci.org/bitcoinjs/bitcoinjs-lib.png?branch=master)](https://travis-ci.org/bitcoinjs/bitcoinjs-lib)
[![NPM](https://img.shields.io/npm/v/bitcoinjs-lib.svg)](https://www.npmjs.org/package/bitcoinjs-lib)
[![tip for next commit](https://tip4commit.com/projects/735.svg)](http://tip4commit.com/projects/735)

[![js-standard-style](https://cdn.rawgit.com/feross/standard/master/badge.svg)](https://github.com/feross/standard)


ReactNative-ready fork of the [original bitcoinjs package](https://github.com/bitcoinjs/bitcoinjs-lib).
Used by over a million wallet users and the backbone for almost all Bitcoin web wallets in production today.


## Features

- Clean: Pure JavaScript, concise code, easy to read.
- Tested: Coverage > 90%, third-party integration tests.
- Careful: Two person approval process for small, focused pull requests.
- Compatible: Works on Node.js and all modern browsers.
- Powerful: Support for advanced features, such as multi-sig, HD Wallets.
- Secure: Strong random number generation, PGP signed releases, trusted developers.
- Principled: No support for browsers with crap RNG (IE < 11)
- Standardized: Node community coding style, Browserify, Node's stdlib and Buffers.
- Fast: Optimized code, uses typed arrays instead of byte arrays for performance.
- Experiment-friendly: Bitcoin Mainnet and Testnet support.
- Altcoin-ready: Capable of working with bitcoin-derived cryptocurrencies (such as Dogecoin).

## Installation

`yarn add react-native-expo-bitcoinjs-lib`


## Setup

`yarn addreact-native-expo-bitcoinjs-lib expo-random`

## Usage

Edit index.android.js and index.ios.js

```javascript
import Bitcoin from 'react-native-expo-bitcoinjs-lib'
[...]
const keypair = Bitcoin.ECPair.makeRandom()
console.log(keypair.getAddress()) // your brand new base58-encoded Bitcoin address
```


## Examples

Run the example app or refer to the [original repository](https://github.com/bitcoinjs/bitcoinjs-lib#examples) for more available examples.


## Projects utilizing BitcoinJS [for Node.js and Browsers](https://github.com/bitcoinjs/bitcoinjs-lib)

- [BitAddress](https://www.bitaddress.org)
- [Blockchain.info](https://blockchain.info/wallet)
- [Blocktrail](https://www.blocktrail.com/)
- [Dark Wallet](https://www.darkwallet.is/)
- [DecentralBank](http://decentralbank.com/)
- [Dogechain Wallet](https://dogechain.info)
- [EI8HT Wallet](http://ei8.ht/)
- [GreenAddress](https://greenaddress.it)
- [Robocoin](https://wallet.robocoin.com)
- [Skyhook ATM](http://projectskyhook.com)

## Projects utilizing BitcoinJS [for React Native](https://github.com/nexustech-solutions/react-native-expo-bitcoinjs-lib)

- [ReactNative Bitcoin Wallet](https://github.com/nexustech-solutions/react-native-bitcoin-wallet)

## Complementing Libraries

- [BIP21](https://github.com/bitcoinjs/bip21) - A BIP21 compatible URL encoding utility library
- [BIP38](https://github.com/bitcoinjs/bip38) - Passphrase-protected private keys
- [BIP39](https://github.com/novalabio/react-native-bip39) - ReactNative-ready Mnemonic generation for deterministic keys
- [BIP32-Utils](https://github.com/novalabio/react-native-bip32-utils) - ReactNative-ready set of utilities for working with BIP32
- [BIP32-Wallet](https://github.com/bitcoinjs/bip32-wallet) - A BIP32 Wallet backed by bitcoinjs-lib, lite on features but heavily tested
- [BIP66](https://github.com/bitcoinjs/bip66) - Strict DER signature decoding
- [BIP69](https://github.com/bitcoinjs/bip69) - Lexicographical Indexing of Transaction Inputs and Outputs
- [Base58](https://github.com/cryptocoinjs/bs58) - Base58 encoding/decoding
- [Base58 Check](https://github.com/bitcoinjs/bs58check) - Base58 check encoding/decoding
- [BCoin](https://github.com/indutny/bcoin) - BIP37 / Bloom Filters / SPV client
- [insight](https://github.com/bitpay/insight) - A bitcoin blockchain API for web wallets.


## Alternatives

There are currently no alternatives for React Native.

## LICENSE [MIT](LICENSE)


## Copyright

BitcoinJS (c) 2011-2016 bitcoinjs-lib contributors

Released under MIT license
