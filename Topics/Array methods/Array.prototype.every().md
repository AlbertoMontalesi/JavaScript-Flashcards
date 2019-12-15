```javascript
// tests whether ALL elements in the array pass a test
// returns a boolean

const array = [1,2,3];
array.every((item) => item > 1);
// false, not all values are more than 1
array.every((item) => item > 0);
// true
```