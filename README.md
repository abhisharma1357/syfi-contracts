# Soft YFI
 
[![Build Status](https://travis-ci.com/Soft Yearn Finance (SYFI)/uFragments.svg?token=xxNsLhLrTiyG3pc78i5v&branch=master)](https://travis-ci.com/Soft Yearn Finance (SYFI)/uFragments)&nbsp;&nbsp;[![Coverage Status](https://coveralls.io/repos/github/frgprotocol/uFragments/badge.svg?branch=master&t=GiWi8p)](https://coveralls.io/github/frgprotocol/uFragments?branch=master)
 
Soft Yearn Finance (SYFI) (code name uFragments) is a decentralized elastic supply protocol. It maintains a stable unit price by adjusting supply directly to and from wallet holders. You can read the [whitepaper](https://www.Soft Yearn Finance (SYFI).org/paper/) for the motivation and a complete description of the protocol.
 
This repository is a collection of [smart contracts](http://Soft Yearn Finance (SYFI).org/docs) that implement the Soft Yearn Finance (SYFI) protocol on the Ethereum blockchain.
 W
 
## Table of Contents
 
- [Install](#install)
- [Testing](#testing)
- [Testnets](#testnets)
- [Contribute](#contribute)
- [License](#license)
 
 
## Install
 
```bash
# Install project dependencies
npm install
 
# Install ethereum local blockchain(s) and associated dependencies
npx setup-local-chains
```
 
## Testing
 
``` bash
# You can use the following command to start a local blockchain instance
npx start-chain [ganacheUnitTest|gethUnitTest]
 
# Run all unit tests
npm test
 
# Run unit tests in isolation
npx truffle --network ganacheUnitTest test test/unit/uFragments.js
```
 
## Contribute
 
To report bugs within this package, create an issue in this repository.
For security issues, please contact dev-support@Soft Yearn Finance (SYFI).org.
When submitting code ensure that it is free of lint errors and has 100% test coverage.
 
``` bash
# Lint code
npm run lint
 
# View code coverage
npm run coverage
```
 

