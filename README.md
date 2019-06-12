# AbbcJs (abbcjs-lib)

A javascript ABBC library for node.js and browsers. 

IT IS A FORK OF bitcoinjs-lib (https://github.com/bitcoinjs/bitcoinjs-lib)

Released under the terms of the [MIT LICENSE](LICENSE).

## Installation
``` bash
npm install abbc-lib
```

Typically we support the [Node Maintenance LTS version](https://github.com/nodejs/Release).
If in doubt, see the [.travis.yml](.travis.yml) for what versions are used by our continuous integration tests.

**WARNING**: We presently don't provide any tooling to verify that the release on `npm` matches GitHub.  As such, you should verify anything downloaded by `npm` against your own verified copy.

## Contributing
See [CONTRIBUTING.md](CONTRIBUTING.md).

### Running the test suite

``` bash
npm test
npm run-script coverage
```

## Complementing Libraries
- [BIP21](https://github.com/bitcoinjs/bip21) - A BIP21 compatible URL encoding library
- [BIP38](https://github.com/bitcoinjs/bip38) - Passphrase-protected private keys
- [BIP39](https://github.com/bitcoinjs/bip39) - Mnemonic generation for deterministic keys
- [BIP32-Utils](https://github.com/bitcoinjs/bip32-utils) - A set of utilities for working with BIP32
- [BIP66](https://github.com/bitcoinjs/bip66) - Strict DER signature decoding
- [BIP68](https://github.com/bitcoinjs/bip68) - Relative lock-time encoding library
- [BIP69](https://github.com/bitcoinjs/bip69) - Lexicographical Indexing of Transaction Inputs and Outputs
- [Base58](https://github.com/cryptocoinjs/bs58) - Base58 encoding/decoding
- [Base58 Check](https://github.com/bitcoinjs/bs58check) - Base58 check encoding/decoding
- [Bech32](https://github.com/bitcoinjs/bech32) - A BIP173 compliant Bech32 encoding library
- [coinselect](https://github.com/bitcoinjs/coinselect) - A fee-optimizing, transaction input selection module for bitcoinjs-lib.
- [merkle-lib](https://github.com/bitcoinjs/merkle-lib) - A performance conscious library for merkle root and tree calculations.
- [minimaldata](https://github.com/bitcoinjs/minimaldata) - A module to check bitcoin policy: SCRIPT_VERIFY_MINIMALDATA

## LICENSE [MIT](LICENSE)
