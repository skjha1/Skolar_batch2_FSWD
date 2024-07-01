```javascript
class Animal {
    constructor(name) {
        this.name = name;
    }

    sound() {
        console.log("Animal makes a sound");
    }
}


// Creating an instance of the Animal class
let dog = new Animal("Dog");
dog.sound(); // Optput: Animal makes a sound



// Class Inheritance 
class Dog extends Animal {
    constructor(name, breed) {
        super(name);
        this.breed = breed;
    }

    bark() {
        console.log("woof! woof!");
    }
}


// Creting an instance of the dog class
let bulldog = new Dog("Bulldog", "Bulldog");
bulldog.sound(); // Output: Animal makes a sound
bulldog.bark(); // Output: woof! woof!
```
