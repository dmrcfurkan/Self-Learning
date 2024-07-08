# Slice

The slice method allows you to return a new array containing copies of elements cut from the original array. Note that the method does not modify the original array, but returns a new element-decreased shallow copy containing copies of elements truncated from the original array. Copies object references to a new array, with the original and new array referencing the same object. If the object is changed by reference, the changes will be visible in both the original and its copy.

## Using

```javascript
array.slice(start, end);
```
start: Optional. An integer specifying where to start the selection (the first element of the index is 0). Use negative numbers to select from the end of an array. If omitted, it behaves as "0". If the array is quintupled from the end, the first element is "-1".

end: Optional. An integer (not included) indicating where the selection ends. If omitted, all elements from the starting position to the end of the array are selected. Use negative numbers to select from the end of an array.

## Example

```javascript
const fruits = ["Banana", "Orange", "Lemon", "Apple", "Mango"];
const citrus = fruits.slice(1, 3);
console.log(citrus);
```
## Output

// Orange,Lemon