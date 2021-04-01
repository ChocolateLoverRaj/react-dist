This might sound obvious, but if a file can be used in the browser (like if it doesn't have jsx), the compiled file should stay the same.

```js
const n = 3

export default n
```
should be compiled into
```js
const n = 3

export default n
```