# JavaScript Quiz

## Multiple Choice Questions (MCQs)

1. What will the following code output: `console.log(typeof null);`
    A. "null"
    B. "NaN"
    C. "undefined"
    D. **"object"**

2. What will the following code output: `console.log(0.1 + 0.2 === 0.3);`
    A. true
    B. **false**
    C. NaN
    D. Error

3. Which method is used to remove the last element from an array and returns that element?
    A. push()
    B. shift()
    C. **pop()**
    D. unshift()

4. How to create a date object for the current date and time in JavaScript?
    A. **new Date()**
    B. Date.now()
    C. Date()
    D. Date.get()

5. What is the output of `"10" + 2` in JavaScript?
    A. 12
    B. **"102"**
    C. "12"
    D. Error

## Code Writing Questions

1. Write a JavaScript function to clone an array.

**let x = [1, 2, 3, 4];
console.log("Original array:")
console.log(x)
let y = [...x];
console.log("Clone of the array:")
console.log(y)**

2. Write a JavaScript function that takes a string and returns it in reverse order.
**function reverseString(str) {
    return str;
}
reverseString("hello");**
3. Write a JavaScript function to get the value of π (pi) up to n number of decimal places.
**function getPi(decimalPlaces) {
  if (decimalPlaces < 0 || decimalPlaces > 15) {
    throw new Error('Decimal places must be between 0 and 15.');
  }
  return Number(Math.PI.toFixed(decimalPlaces));
}
console.log(getPi(5)); 
console.log(getPi(10));
console.log(getPi(15));**

4. Write a JavaScript function to merge two objects.
**const obj1 = { a: 1, b: 2, c: 3 };
const obj2 = { d: 4, e: 5, f: 6 };
const obj3 = {...obj1, ...obj2}; 

let user = { name: 'Rihaj Bou Hamdan', age: 23 };
const changes = { name: 'Rihaj Bou Hamdan' };
user = { ...user, ...changes };**

5. Write a JavaScript function to create a deep copy of an object.
**function deepCopy(obj) {
  return JSON.parse(JSON.stringify(obj));
}
const originalObj = {
  a: 1,
  b: {
    c: 2,
    d: [3, 4, 5],
  },
};

const deepCopiedObj = deepCopy(originalObj);
console.log(deepCopiedObj);**

