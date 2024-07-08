# Some

The Javascript `some()` method determines whether at least one array member satisfies the test defined by the given function. Returns true if it finds an element in the array where the specified function returns true; otherwise it returns false. It does not make any changes to the array.

## Using

```javascript
array.some(function (value, index, array) )
```
value: This parameter is mandatory and holds the value of the array elements.

index: This parameter is optional and holds the index number of the array elements.

array: This parameter is optional and holds the array itself.

## Example

```javascript
const ages=[3,10,18,20];
console.log(ages.some(checkAdult));
function checkAdult(age) {
  return age > 18;
}
```

## Output

// true