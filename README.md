# crypto-aes192
Simple encrypt and decrypt tool for generate hash string

## Installation
npm i

## Usage
const password = 'abcde12345';
const cryptoAes192 = require('crypto-aes192')(password);

let test = "marshall"
let e = midlandCrypto.encrypt(test);
let d = midlandCrypto.decrypt(e);
console.log(test, e, d);