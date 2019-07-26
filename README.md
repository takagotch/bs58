### bs58
---
https://github.com/cryptocoinjs/bs58

```js
const bs58 = require('bs58')

const bytes = Buffer.from('xxx', 'hex')
const address = bs58.encode(bytes)
console.log(address)

const bs58 = require('bs58')

const address = 'xxx'
const bytes = bs58.decode(address)
console.log(bytes.toString('hex'))


```

```sh
npm i --save bs58
npm install -g browserify
browserify node_modules/bs58/index.js -o bs58.bundle.js --standalone bs58
```

```
```


