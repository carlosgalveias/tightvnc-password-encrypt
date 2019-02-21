# tightvnc-password-encrypt
Transforms a plain password in text into a hex encrypted string compatible with TightVNC

## Installation

npm install tightvnc-password-encrypt

## usage

```
const te = require('tightvnc-password-encrypt');
let encryptedPassword = te.encrypt('plainPasswordText');
```

return a object like this: 
{ buffer: <Buffer ce 5a 67 a6 74 89 fc f8>,  string: 'ce5a67a67489fcf8' }
