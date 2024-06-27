# SELECTORS
It allows us to select any element or multiple elements in an HTML page and change their properties. For example, it is necessary to use selectors to select an element and change the background color.

## Selective Methods
### Example
Here is the method to select all `<p>` elements

```css
p {
  text-align: center;
  color: red;
}
```
### Id Selector
Here is the method how to select element by id name.
putting (#) before inside the element

```css
#box {
  text-align: center;
  color: red;
}
```

### Class Selector
Here is the method how to select element by class name.
putting (*) before inside the element
```css
.element {
  text-align: center;
  color: red;
}
```
## Universal selector
The (*) element is used to select all HTML elements.
```css
* {
  text-align: center;
  color: blue;
}
```