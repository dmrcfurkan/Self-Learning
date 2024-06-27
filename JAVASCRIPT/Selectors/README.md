# JavaScript Selectors
JavaScript selectors are methods or syntax used to select and interact with HTML elements in the Document Object Model (DOM). They allow developers to dynamically access and manipulate elements on a webpage. Common selectors include:

1. `getElementById`
1. `getElementsByClassName`
1. `getElementsByTagName`
1. `querySelector`
1. `querySelectorAll`

## 1. getElementById

```javascript
const element=document.getElementById("IdName");
element.style.color="blue"
```

## 2. getElementsByClassName

```javascript
const element=document.getElementByClassName("className");
element.style.color="blue"
```

## 3. getElementsByTagName

```javascript
const element=document.getElementsByTagName("div")
```

## 4. querySelector

```javascript
const selectElement=document.querySelector(".element")
```

## 5. querySelectorAll

```javascript
const elements=document.querySelectorAll(".element");

/* when querySelectorAll is used, it returns all selected elements in a NodeList collection. NodeList is an object similar to an array, and you can iterate over it using a loop to access each element. For example, you can process each item using a forEach loop or a traditional for loop. This allows you to perform multiple operations related to the selected elements.*/
```