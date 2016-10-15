#Exercises


1: From your understanding of expressions and statements, write the difference between them.

A statement in JavaScript is made of keywords, comments, literals (literal values like numbers), operators and expressions. 

```
var a = 16;
var b = 5;
var sum = a+b;
```
This example above has three statements.

An expression, more specificially is a combination of literals, variables and operators (+-*/%) that results in a value.

```
var a = 16;
var b = 5;
var sum = a+b;
console.log(sum);//returns 21
```

This example above has four statements, and one expression which is the `var sum = a+b;` as it will return a value: 21. 

---

2: Identify the keywords, comments, literals, variables, operators, and expressions in the following program. How many statements are there?

```
var sum = 32 + 23 + 26;
/*
The formula for calculating average is:
average = sum_of_all_items/total_number_of_items
*/
var avg = sum / 3;
console.log(avg); //prints the average
```

**Keywords:**
 - var
 - console
 - log
 
**Comments:**
*
The formula for calculating average is:
average = sum_of_all_items/total_number_of_items
*/

//prints the average

**Literals:**
32, 23, 26, 3.

**Variables:**

- sum
- avg

**Operators:**

+, /.

**Expressions:**
var sum = 32 + 23 + 26;
var avg = sum / 3;

---

#Exercises

1: Without running the following program can you guess the output?

```
var a;
console.log(a);
```
//undefined
Run the program to validate your answer.
Confirmed.

2: Divide 100 with 0 and print the result to the console. What is the data type of the output?

```
answer = 100/0;
console.log(answer);
```
//Infinity.
The data type is a number. 


3: Create an array with 3 items: "banana", "apple", "orange". Print all these items using index only.

```
var items = ["banana", "apple", "orange"];
console.log(items);
```

4: Print the last element of an array. Make sure you test your program with arrays of different sizes.

```

```








































