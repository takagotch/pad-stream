### pad-stream
---
https://github.com/sindresorhus/pad-stream

```
npm install --save pad-stream

echo 'foo\nbar' | node pad.js

```

```js
const padStream = require('pad-stream');
process.stdin.pipe(padStream(2, '>')).pipe(process.stdout);



```

```
```


