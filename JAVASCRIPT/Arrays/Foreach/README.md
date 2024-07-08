# FOREACH

In JavaScript, forEach is an array method that allows us to create and execute a loop.

## Using Foreach

```javascript
arr.forEach(function(value, index, array)) {
  // Using index and array is optional
}
```

## Example
```javascript
const fruits=['apple','lemon','banana','strawberry','melon',];
fruits.forEach((value , index , array) => {
  console.log('value: ', value );
  console.log('The index taken by the value parameter :', index );
  console.log('array:' , array );
});

```