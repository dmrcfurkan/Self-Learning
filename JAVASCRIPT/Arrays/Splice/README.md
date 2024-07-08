# Splice

The splice() method allows adding and deleting an element or elements to the array. Returns the value deleted from the array with splice(). The method changes the structure of the array.

## Using

```javascript
array.splice(index, count, item1, ....., itemX)
```

## Example
```javascript
const fruits = ["Banana", "Orange", "Apple", "Mango"];

// At position 2, add "Lemon" and "Kiwi"
fruits.splice(2, 0, "Lemon", "Kiwi");
console.log(fruits);
```

## Output
// Banana,Orange,Lemon,Kiwi,Apple,Mango
