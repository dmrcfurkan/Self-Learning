# Concat

It is used to combine two or more arrays. This method does not modify the existing array. Returns a new concatenated array.

## Using
```javascript

array.concat(array2, array3, ..., arrayX);

```

## Example

```javascript
const languages = ["turkish","english"];
const fruits = ["banana","strawberry","pear","quince"];
const animals = ["horse","bear","bee","lion"];

const newArray = languages.concat(fruits, animals);

alert( newArray );
```

