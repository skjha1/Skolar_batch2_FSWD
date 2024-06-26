```javascript
function exampleVar () {
    if (true) {
        var x = 10;
    }
    console.log(x); // Output: 10
}

exampleVar();
console.log(x); // throw ReferenceError: x is not defined


var globalVar = "I'm global"

function displayGlobalvar() {
    console.log(globalVar); // accessible here
}
displayGlobalvar();
console.log(globalVar); // accessible here too 


function exampleLet () {
    if (true) {
        let x = 10;
        console.log(x); // 10
    }
    console.log(x);   // ReferenceError: x is not defined
}
exampleLet();



function exampleConst() {
    //const PI = 3.14;
    PI = 3.14159; 
    console.log(PI); // TypeError: Assignment to constant variable.
}
exampleConst();


const myCostant = 10;
console.log(myCostant);

const myCostant = 10;
myCostant = 20;
console.log(myCostant);

const myArray = [1 , 2, 3];
console.log(myArray);

myArray.push(4);
console.log(myArray);

const myObject = {name: 'Nethaji', age: 20}
console.log(myObject)

myObject.age = 26
console.log(myObject)

myObject.city = "Andhra"
console.log(myObject)


const myObject = {name: 'Harpreet'}



function examplevar() {
    for (var i = 0; i < 3; i++) {
        var message = "Hello";  
    }
    console.log(message); // Hello 
    console.log(i);     // 3 

}

examplevar();
console.log(message); // ReferenceError: message is not defined
console.log(i);         //  ReferenceError: i is not defined


function examplevLet() {
    for (let i = 0; i < 3; i++) {
        let message = "Hello";  
    }
    console.log(message);  // ReferenceError: message is not defined
    console.log(i);         //  ReferenceError: i is not defined

}
examplevLet();


function exampleConst() {
    const PI = 3.14;
    //PI =  3.14159;  // This will throw an error: Assignment to constant variable
    console.log(PI); // Output : 3.14

    const person = {
        name: "john",
        age: 30
    };

    person.age = 31;   // This is allowed because the object's reference remains constant 
    console.log(person.age); // Output : 31

}
exampleConst();

```
