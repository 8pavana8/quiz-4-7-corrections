# quiz-4-7-corrections

## Quiz 4 Corrections/Explanations

### Question 11


Code 01. 
```
function askedAndAnswered () {
 let name;
 let age;
  
  let name = prompt ("Enter your first name");
  let age = (Number(prompt) ("Enter your age");
  let x = 
  document.getElementByID("asked-and-answered").innerHTML = "Hello," + name + "." + "When do you turn
  ```       
        
## Quiz 5 Correction/Explanations

### Question 1
I got this answer partially incorrect. While I did select all of the relational operators which included "<, >, <=, >=, ==, !=, ===, !==",  I also selected an additional choice that was not a relational operator. The additional one I selected was "=". I got this question partially wrong as "=" is not a relational operator. (Relational operators allow you to compare equality.)

### Question 2
My answer was incorrect. This question asked me to select 2 expressions that would satisfy the statements provided.

These were the statements provided:
```
let x = 43;
let y = "43";

if ( /* missing condition */ ) {
    console.log("x and y have equivalent values and data types.");
}

if ( /* missing condition */ ) {
    console.log("x and y have different values or different data types.");
}
```
the correct answer is

```
x === y
x !== y
```
This is the correct answer because === is equal to and compares both value and data type; and !== is not equal to and compares both value and data type. The first statment is asking for a condition that would make x and y have equivalent values and data types and the second statement asks for a condtion that would make x and y have different values or different data types. Therefore, the conditions above are the right answers that will satisfy the requirements.

### Question 4
For this question I had to consider a code segment and select what would be logged to the console based on it. 
The following is the code segment I had to consider:
```
let a = "hello";
console.log(!a);
console.log(!!a);
```

The correct answer is false, true. This is because The first ! operator converts 'a' to true and inverts it to false. The second ! operator inverts it again back to true.I had selected that false, false would be logged to the console but that was incorrect.

### Question 6
I got this question partially wrong because I did not select all the answers that applied. The ternary operator of:
```
let status = (studentGrade < 88) ? "ND" : "HR";
```
also effectively replaces the if-else statement provided. 

