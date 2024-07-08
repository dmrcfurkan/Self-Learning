# Fill


`Array.fill()` method is used to fill the array with a specific static value. The value can be used to fill the entire array, or it can be used to fill a portion of the array.

## Using 

```javascript
array.fill(value, start, end)
```

## Example

```javascript
    const fruits = ["Banana", "Orange", "Apple", "Mango"];
    fruits.fill("Kiwi", 2, 4);
```
### Output
(4) ["Banana", "Orange", "Kiwi", "Kiwi"]