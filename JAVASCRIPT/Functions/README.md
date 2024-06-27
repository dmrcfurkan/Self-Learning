# Functions
Functions are code blocks designed to execute one or more tasks efficiently. By encapsulating specific instructions, functions enable us to avoid redundant coding, ensuring that operations are performed whenever required with minimal effort.

## How To Define a Funciton
In JavaScript, you need to use the function keyword prefix to define a function. This informs JavaScript that you are defining a function block.fterward, you write the name of the function and inside parentheses, you list the parameter names.

```javascript
    function functionName(param1, param2 /*
    Parameter definition is not mandatory.*/)
{
    //Do something
}
```

## Return
The `return` statement can be used anywhere within a function. When the code reaches a return statement, the function stops executing, and the value is sent back to the place where the function was called. A function can have multiple return statements. It's important to note that return does not necessarily have to return a value.

```javascript
function sum(num1,num2){
    return (num1+num2);
}
let result=sum(4,5);
console.log(result); //9
```


