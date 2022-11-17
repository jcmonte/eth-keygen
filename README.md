# eth-keygen: Ethereum Private Key Generator

A one line JS script that prints out a new private key generated from [ethers.js](https://github.com/ethers-io/ethers.js/). 

```javascript
console.log(require("ethers").ethers.Wallet.createRandom().privateKey);
```

> ⚠️ This repo merely exists to serve as an example of how to generate your own private key. It is not recommended, however, this is a fully functional package and you are welcome to clone it and use at your own risk.

## Requirements

- [Node.js >= 16](https://nodejs.org/en/)

## Setup
Install packages (ethers.js)
```
npm install
```

Link the executable
```
npm link
```

## Example
```bash
> eth-keygen
0xaed12345...
```
