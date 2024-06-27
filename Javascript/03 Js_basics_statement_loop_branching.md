```javascript
let result = 5 + 3; // relult will be 8
console.log(result)

let result1 = 7 - 3; // result will be 4 
console.log(result1)

let result2 = 7 * 3; // result will be 21
console.log(result2)

let result3 = 7 / 3; // result will be 2.3333333333333335
console.log(result3)

let result4 = 7 % 3; // result will be 1
console.log(result4)


let x = 10;
console.log(x)  // result will be 10


let y = 5;
y += 3; // y = y + 3
console.log(y)  // result will be 8


let z = 7;
z -= 4; // z = z - 4
console.log(z) // result will be 3


// Comparision operators are used to compare values and return the boolean result (trur/false)


// Equals (==) - check if the two values are equal, regardless of their data types(Implicit type coercion)

console.log(5 == '5'); // true (because the values are equal after type coercion)


// String Equals (===) - check if two values are equal and have the same data type. (no coercion)

console.log(5 === '5'); // false (because of different data types)

// Not Equals (!=) check if the two values are not equal, regardless of their data types(Implicit type coercion)

console.log(5 != '5'); // false (because the values are equal after type coercion)

// String Not Equals (!==) check if the two values are not equal or not of the same data type.

console.log(5 !== '5'); // true (because of different data types)


// Logical operators

// Logical AND 
// t t t
// t f f
// f t f
// f f f
console.log(true && true) // True
console.log(true && false) // false


// Logical OR 

console.log(true || true) // True
console.log(true || false) // True
console.log(false || false) // false

// Logical NOT 

console.log(!true) // False
console.log(!false) // True


Control flow in programming refers to the order in which the instructions or statements of a program are executed.

Conditional statement 

Conditional statement  allow a program to make a decisions and execute diff blocks of code based on whether certain conditions are true or false.


1. If statemens 

let x = 10;
if (x > 0){
    console.log('X is posetive');  // X is posetive
}

else statement


let x = -1;
if (x > 0){
    console.log('X is posetive');
} else {
    console.log('X is negetive'); // X is negetive
}

let x = 0;
if (x > 0) {
    console.log('X is posetive');
} else if (x === 0) {
    console.log('X is Zero'); // X is Zero
} else {
    console.log('X is negetive');
}

Loops 

Loops are used to excute a block of code repeatedly unitl a specified condition is true.

const numbers = [1, 2, 3, 4, 5]
for (let i = 0; i <= numbers.length; i++){
    console.log(numbers[i]); // output: 1 2 3 4 5
}

while loop: excute a block of code repeatedly unitl a specified condition is true.

let i = 0;
while (i < 5) {
    console.log(i); // 0 1 2 3 4 
    i++;
}

do while loop: Guatantees that the block of code executed at least once before the condition is checked.

let j = 0;
do {
    console.log(j); // 0 1 2 3 4 
    j++
} while (j < 5);


Branching 

let fruit = 'Apple'

switch (fruit) {
    case "Banana":
        console.log("Banana is yellow");
        break;
    case "Apple":
        console.log("Apple is red"); // output: Apple is red
        break;
    case "Orange":
        console.log("Orange is orange");
        break;
    default:
        console.log("Unknown fruit!");
}


// Calculating avg grade 

let grades = [85, 90, 78, 92, 88];
let sum = 0;


// Using for loop to cal the sum of grades

for ( let i = 0; i < grades.length; i++ ){
    sum += grades[i];
}

let averageGrade = sum / grades.length; // Division operator to find the average
console.log("Average Grade:", averageGrade); // Average Grade: 86.6

// Grade classification 

let grade = 86;

if (grade > 90) {
    console.log("Grade: A");
} else if (grade >= 80){
    console.log("Grade: B"); // Output: Grade: B
} else if (grade >= 70){
    console.log("Grade: C");
} else if (grade >= 60){
    console.log("Grade: D");
} else {
    console.log("Grade: F");
}
 


let totalClasses = 40;
let attendedClasses = 30;
let percentageAttended = (attendedClasses / totalClasses) * 100;


while (percentageAttended < 75 ){
    console.log("Attendance below required percentage. Attend more classes.");
    attendedClasses++;
    percentageAttended = (attendedClasses / totalClasses) * 100;
}

console.log("Attendance required met: ", percentageAttended + "%");


let grade = 85;
let attendance = 60;

if (grade >= 60 && attendance >= 75){
    console.log("Student is promoted")
} else {
    console.log("Student is nots promoted")
}

let studentScore = {
    "Swati": 85,
    "Sathiya": 92,
    "Nikhil": 88,
    "Akash": 90
};

let topScorer = "";
let highestScore = 0;

// Using a for loop find the student with the highest score.
for (let student in studentScore) {
    if (studentScore[student] > highestScore){
        highestScore = studentScore[student];
        topScorer = student;
    }
}

console.log("Top scorer:", topScorer, "with a score of", highestScore);






```
