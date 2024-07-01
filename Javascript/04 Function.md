```Javascript 
function add(a, b){
    return a + b;
}


function findMax(a, b){
    return a > b ? a : b;
}


function isEven(num){
    return num % 2 === 0;
}


let num1 = 10;
let num2 = 20;

let sum = add(num1, num2);
console.log(`Sum of ${num1} and ${num2} is: ${sum}`);
console.log('Sum of ' + num1 + ' and ' + num2 + ' is: ' + sum);


let max = add(num1, num2);
console.log(`Maxmimum of ${num1} and ${num2} is: ${max}`);


let checkNum = 15;
console.log(`${checkNum} is even? ${isEven(checkNum)}`);
```
