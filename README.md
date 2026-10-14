# AKSHITKESARWANIJSFILE
// 1. Arithmetic Operations on Two Numbers
console.log("1. Arithmetic Operations");
let a = 10, b = 5;
console.log("Addition =", a + b);
console.log("Subtraction =", a - b);
console.log("Multiplication =", a * b);
console.log("Division =", a / b);
console.log("Modulus =", a % b);

// 2. Comparison Operators
console.log("\n2. Comparison Operators");
console.log("a == b:", a == b);
console.log("a != b:", a != b);
console.log("a > b:", a > b);
console.log("a < b:", a < b);
console.log("a >= b:", a >= b);
console.log("a <= b:", a <= b);

// 3. Logical Operators
console.log("\n3. Logical Operators");
let x = 10, y = 20;
console.log("AND:", x > 5 && y > 10);
console.log("OR:", x < 5 || y > 10);
console.log("NOT:", !(x > 5));

// 4. Check Positive Number
console.log("\n4. Positive Number");
let num = 10;
if (num > 0)
    console.log("Positive Number");
else
    console.log("Not a Positive Number");

// 5. Check Even or Odd
console.log("\n5. Even or Odd");
num = 7;
if (num % 2 == 0)
    console.log("Even Number");
else
    console.log("Odd Number");

// 6. Voting Eligibility
console.log("\n6. Voting Eligibility");
let age = 18;
if (age >= 18)
    console.log("Eligible for Voting");
else
    console.log("Not Eligible for Voting");

// 7. Positive, Negative or Zero
console.log("\n7. Positive, Negative or Zero");
num = -5;
if (num > 0)
    console.log("Positive");
else if (num < 0)
    console.log("Negative");
else
    console.log("Zero");

// 8. Calculate Grade Using Else-If
console.log("\n8. Calculate Grade");
let marks = 85;
if (marks >= 90)
    console.log("Grade A+");
else if (marks >= 80)
    console.log("Grade A");
else if (marks >= 70)
    console.log("Grade B");
else if (marks >= 60)
    console.log("Grade C");
else if (marks >= 40)
    console.log("Grade D");
else
    console.log("Fail");

// 9. Largest of Two Numbers
console.log("\n9. Largest of Two Numbers");
a = 10;
b = 20;
if (a > b)
    console.log(a, "is Largest");
else if (b > a)
    console.log(b, "is Largest");
else
    console.log("Both Numbers are Equal");

// 10. Check Leap Year
console.log("\n10. Leap Year");
let year = 2024;
if ((year % 4 == 0 && year % 100 != 0) || year % 400 == 0)
    console.log(year, "is a Leap Year");
else
    console.log(year, "is Not a Leap Year");

// 11. Print Numbers from 1 to 10
console.log("\n11. Numbers from 1 to 10");
for (let i = 1; i <= 10; i++) {
    console.log(i);
}

// 12. Multiplication Table
console.log("\n12. Multiplication Table");
num = 5;
for (let i = 1; i <= 10; i++) {
    console.log(num + " x " + i + " = " + (num * i));
}

// 13. Sum of First N Natural Numbers
console.log("\n13. Sum of First N Natural Numbers");
let n = 10;
let sum = 0;
for (let i = 1; i <= n; i++) {
    sum += i;
}
console.log("Sum =", sum);

// 14. Even Numbers Between 1 and 50
console.log("\n14. Even Numbers Between 1 and 50");
for (let i = 2; i <= 50; i += 2) {
    console.log(i);
}

// 15. Count Numbers Divisible by 3 Between 1 and 100
console.log("\n15. Count Numbers Divisible by 3");
let count = 0;
for (let i = 1; i <= 100; i++) {
    if (i % 3 == 0) {
        count++;
    }
}
console.log("Count =", count);

// 16. Largest of Three Numbers
console.log("\n16. Largest of Three Numbers");
a = 10;
b = 25;
let c = 15;
if (a >= b && a >= c)
    console.log(a, "is Largest");
else if (b >= a && b >= c)
    console.log(b, "is Largest");
else
    console.log(c, "is Largest");

// 17. Divisible by Both 3 and 5
console.log("\n17. Divisible by Both 3 and 5");
num = 15;
if (num % 3 == 0 && num % 5 == 0)
    console.log(num, "is divisible by both 3 and 5");
else
    console.log(num, "is not divisible by both 3 and 5");

// 18. Factorial of a Number
console.log("\n18. Factorial of a Number");
num = 5;
let factorial = 1;
for (let i = 1; i <= num; i++) {
    factorial *= i;
}
console.log("Factorial =", factorial);

// 19. Print Numbers from 50 to 1
console.log("\n19. Numbers from 50 to 1");
for (let i = 50; i >= 1; i--) {
    console.log(i);
}

// 20. Sum of Odd Numbers Between 1 and 100
console.log("\n20. Sum of Odd Numbers Between 1 and 100");
sum = 0;
for (let i = 1; i <= 100; i += 2) {
    sum += i;
}
console.log("Sum of Odd Numbers =", sum);