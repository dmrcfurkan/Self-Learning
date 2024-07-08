# Reduce

It scans the created array from left to right on each element and reduces it to a single value.
It does not operate on the original array.
The callback function takes as parameters.

## Using

```javascript
array.reduce(function(accumulator, currentValue, currentIndex, arr), initialValue);
```
accumulator:
Collects the values ​​returned from the callback function.

currentValue :It is the current array value as you move from left to right.

currentIndex (optional):It is the desired index value to start from in the array.

arr (optional):It is the array to be operated on.
initialValue:It is the starting value for the accumulator.

## Example 

```javascript
const numbers=[1,2,3,4,5,6];
const reducer=(accumulator,currentValue) =>accumulator+currentValue;
console.log(numbers.reduce(reducer));
```
## Output
// 21
