```javascript
let car = {
    brand: "Toyota",
    model: "Camry",
    year: 2020,
    // Method definition
    displyInfo: function() {
        return `${this.brand} ${this.model} (${this.year})`
    }
};

console.log(car.brand); // Output: Toyota
console.log(car.year); // Output: 2020

console.log(car.displyInfo()); // Output: Toyota Camry (2020)


console.log(car); // Output: 

console.log(car.brand); // Output: Toyota
car.brand = "Honda"; 
console.log(car.brand); // Output: Honda


let mySet = new Set();
mySet.add(1);
mySet.add(2);
mySet.add(2);
console.log(mySet); //  Output: Set(2) { 1, 2 }


let myMap = new Map();
myMap.set("name", "Nikhil");
myMap.set("age", 21);
console.log(myMap.get("name")); // Output: Nikhil





```
