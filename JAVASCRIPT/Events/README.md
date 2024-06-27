# Events
Events in JavaScript facilitate interaction between JavaScript code and HTML elements. They are embedded within HTML tags and can be triggered by various occurrences, such as when a window is opened, a button is clicked, or the window is resized. These examples can be expanded upon to include a wide range of events.

## Event Types
1. `Mouse Events`
1. `Keyboard Events`
1. `Form Events`


## 1. Mouse Events
### - Click
Triggered when the mouse button is clicked.

```javascript
element.addEventListener("click", myFunction);

function myFunction() {
  alert ("Hello World!");
}
```
### -  Mouseover

Occurs when the mouse pointer hovers over an element.

```javascript
element.addEventListener("mouseover", myFunction);

function myFunction() {
  alert ("This is a mouseover effect.");
}
```
### - Mouseout
Occurs when the mouse pointer leaves an element.
```javascript
element.addEventListener("mouseout", myFunction);

function myFunction() {
  alert ("This is a mouseout effect.");
}
```
### - Mousemove

It fires continuously as long as the mouse pointer moves over an element.

```javascript
element.addEventListener("mousemove", myFunction);

function myFunction() {
  alert ("This is a mousmove effect.");
}
```

### - Mousedown
Triggered when the mouse button is held down on an element.
```javascript
element.addEventListener("mousedown", myFunction);

function myFunction() {
  alert ("This is a mousdown effect.");
}
```

### - Mouseup

Occurs when the mouse button is released after pressing on an element.
```javascript
element.addEventListener("mouseup", myFunction);

function myFunction() {
  alert ("This is a mousup effect.");
}
```

## 2. Keyboard Events
### - Keydown
Triggered when a key is pressed.

```javascript
element.addEventListener("keydown",function(events){
if(events.key=='q'){
    console.log("You pressed q");
}
});
```

### - Keyup
Triggered when a key is pressed.

```javascript
document.getElementById("Idname").addEventListener("keyup", myFunction);

function myFunction() {
  let x = document.getElementById("Idname");
  x.value = x.value.toUpperCase();
}
```

### - Keypress
Triggered when a character key is pressed (an obsolete event, no longer recommended and it is recommended to use keydown and keyup instead).

## 3. Form Events

### - Submit
Triggered when the form is submitted, usually by clicking a submit button or pressing Enter.

### - Reset
Triggered when the form is reset, typically by clicking a reset button.

### - Change
Fired when the value of a form element changes (e.g., an `<input>` or `<select>` element).

### - Focus
Triggered when a form element gains focus, such as when a user clicks on an input field or navigates to it using the keyboard.

### - Blur
Fired when a form element loses focus, such as when a user clicks away from an input field or navigates away using the keyboard.

### - Input
Continuously triggered when the value of a form element changes, such as when a user types into an input field or deletes content.