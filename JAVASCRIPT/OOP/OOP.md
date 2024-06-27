# OOP(Object Oriented Programming)
In Object-Oriented Programming (OOP), the concept of abstraction involves hiding implementation details and exposing only the essential features of an object to users. Embedding abstraction in a JavaScript program like this can enhance code readability and prevent redundancy.

## 1. Classes and Objects

Class: Classes are the cornerstone of object-oriented programming. They allow programs to be divided into pieces, reducing complexity. Methods and properties created are contained within a class and can be reused multiple times. Both functions and data are tightly coupled within a class simultaneously. A class should contain a set of members for the objects created within itself. These members include fields, methods, constructors, properties, events, delegates, etc.

### Constructors
In JavaScript, functions created to define the class structure are referred to as constructors. In Object Oriented Programming (OOP) terminology, constructors are called when an object is instantiated using the new keyword.

```javascript
class Animal {
    //  (constructor) 
    constructor(name) {
        this.name = name;
    }
    
    // Define method
    speak() {
        console.log(this.name + ' makes a noise.');
    }
}

// create new object
let dog = new Animal('Dog');

// call method
dog.speak(); //  Dog makes a noise.
```

## 2. Inheritance

Inheritance is an OOP feature that allows one object to inherit the properties of another. A class written can be inherited by another class. When this happens, all the properties of the base class are transferred to the new class.

### Super
A subclass can create an object of its superclass using the super() method and assign values to its variables.

```javascript
// Inheritance
class Dog extends Animal {
    constructor(name) {
        super(name); // Calling superclass constructor method
    }

    // new method
    speak() {
        console.log(this.name + ' barks.');
    }
}

let dog = new Dog('Bulldog');
dog.speak(); // Bulldog barks.
```

## 3.Encapsulation
It is the principle that variables or attributes belonging to a class can only be modified and accessed by methods belonging to that class. This principle helps prevent inconsistencies in objects.

```javascript
// Encapsulation example
class Counter {
    #count = 0; // Private private

    increment() {
        this.#count++;
    }

    getCount() {
        return this.#count;
    }
}

let counter = new Counter();
counter.increment();
console.log(counter.getCount()); // 1
```