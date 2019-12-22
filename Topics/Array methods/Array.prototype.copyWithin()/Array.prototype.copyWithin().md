```javascript

// shallow copies part of an array
// to another location
// in the same array
// and returns it without
// modifying its length
const array1 = [0,1,2,3,4,5,6];
// target index 0
// copy values from index 3 to 5
const array2 = array1.copyWithin(0,3,5)
// [3, 4, 2, 3, 4, 5, 6]


```

