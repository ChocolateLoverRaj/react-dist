The main difference between React files and other files is JSX.

```jsx
const element = <div />

export default element
```
should be compiled into 
```js
const element = React.createElement('div')

export default element
```