# Filter

The `filter()` method operates on each element of the array given as a parameter and returns a new array with all the values that return true. This allows you to perform various filtering operations. It does a very necessary job, and its usage is just as simple. By the way, the `filter()` method returns a `boolean` value.

## Using

```javascript
array.filter((element) => {
  //  (condition)
});
```

## Example

```javascript
const numbers = [1, 2, 3, 4, 5, 6];
numbers.filter((element) => {
  return number % 2 == 0;
});
```
## Output

[2,4,6];