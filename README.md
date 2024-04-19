//Question1
console.log("            question1");
let greeting: string = "Hello, World!";
console.log(greeting);

//Question2
console.log("            question2");
let num1: number = 10;
let num2: number = 20;

let sum = num1 + num2;
let difference = num1 - num2;
let product = num1 * num2;
let quotient = num1 / num2;

console.log("Sum:", sum);
console.log("Difference:", difference);
console.log("Product:", product);
console.log("Quotient:", quotient);

//Question3
console.log("            question3");
let a = 1;
let b = 2;

a = a + b;
b = a - b;
a = a - b;

console.log("a:", a);
console.log("b:", b);

//Question4
console.log("            question4");
let message: string = "This is a string";

// message = 10; // Tit is causing a compile time error in typescript

//Question5
console.log("            question5");
let no1 = 10;
let no2 = 3;

let remainder = no1 % no2;

console.log("Remainder:", remainder);

//Question6
console.log("            question6");
let counter = 0;

counter++; // Increment using pre-increment
console.log("counter (pre-increment):", counter);

counter = counter + 1; // Increment using expression
console.log("counter (expression):", counter);

//Question7
console.log("            question7");
let A = true;
let B = false;
let c = true;

let and = A && B; // AND (false)
let or = A || B; // OR (true)
let not = !c; // NOT (false)

console.log("AND:", and);
console.log("OR:", or);
console.log("NOT:", not);

//Question8
console.log("            question8");
let no = 10;

no += 5; // num becomes 15
no -= 3; // num becomes 12
no *= 2; // num becomes 24
no /= 4; // num becomes 6

console.log("num:", no);

//Question9
console.log("            question9");
let num = 15;

let isEven = num % 2 === 0;

console.log(num + " is " + (isEven ? "even" : "odd"));

//Question10
console.log("            question10");
let aage = 20;

let canVote = aage >= 18;

console.log((canVote ? "Eligible" : "Ineligible") + " to vote");

//Question11
console.log("            question11");
let score = 85;

let grade: string;

if (score >= 90) {
  grade = "A";
} else if (score >= 80) {
  grade = "B";
} else if (score >= 70) {
  grade = "C";
} else if (score >= 60) {
  grade = "D";
} else {
  grade = "F";
}

console.log("Grade:", grade);

//Question12
console.log("            question12");
let X = 5;
let Y = 10;
let z = 12;

let max = Math.max(X, Y, z);

console.log("Maximum:", max);

//Question13
console.log("            question13");
let year = 2024;

let isLeapYear = (year % 4 === 0 && year % 100 !== 0) || year % 400 === 0;

console.log(year + " is " + (isLeapYear ? "a leap year" : "not a leap year"));

//Question14
console.log("            question14");
let fahrenheit = 77;

let celsius = (fahrenheit - 32) * (5 / 9);

console.log(fahrenheit + "°F is equal to", celsius.toFixed(2) + "°C");

//Question15
console.log("            question15");
let nuumber: number = -5; // Replace with the number you want to check

if (nuumber > 0) {
  console.log("The number is positive.");
} else if (nuumber < 0) {
  console.log("The number is negative.");
} else {
  console.log("The number is zero.");
}

//Question16
console.log("            question16");
let number: number = 5; // Replace with the number you want the table for

console.log("Multiplication table of", number + ":");

for (let i = 1; i <= 10; i++) {
  let product = number * i;
  console.log(number + " x", i + " = ", product);
}
