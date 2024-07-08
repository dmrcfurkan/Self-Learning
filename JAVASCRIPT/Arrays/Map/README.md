# MAP

`Map()` method is used to ensure that all elements in the array survive an operation. Each element is processed individually, values ​​can be changed, and how it will be viewed backwards can be determined. And as a result, a series of processes going through the process returns.

## Using

```javascript
array.map(function(currentValue, index, arr), thisValue);
```

## Example

```javascript
const numbers=[1,2,3,4,5];
const newNumbers=numbers.map(value =>{
    return value*5;
})
console.log(newNumbers);

```
## Output
// 5,10,15,20,25