# Variables in JavaScript

## const
- Cannot be changed
- Block scoped

## let
- Can be updated
- Block scoped

## var
- Function scoped
- Can be redeclared

## Hoisting
- var → undefined
- let/const → error (TDZ)

## Example
```javascript
const accountId = 144553
let accountEmail = "sangee@gmail.com"
var accountPassword = "12345"
