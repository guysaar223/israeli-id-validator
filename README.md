[![Build Status](https://travis-ci.com/atlanteh/israeli-id-validator.svg?branch=master)](https://travis-ci.com/atlanteh/israeli-id-validator)

# israeli-id-validator
A simple Israeli ID validator

## INSTALLATION
`npm i israeli-id-validator`

## USAGE
```javascript
import isIsraeliIdValid from 'israeli-id-validator';

console.log(isIsraeliIdValid(123456782)) // true
console.log(isIsraeliIdValid(123456785)) // false
console.log(isIsraeliIdValid(1234567856)) // false
console.log(isIsraeliIdValid(12345678)) // false
console.log(isIsraeliIdValid("123456782")) // true
console.log(isIsraeliIdValid("123456785")) // false
console.log(isIsraeliIdValid("023456783")) // true
console.log(isIsraeliIdValid("23456783")) // true 
```
