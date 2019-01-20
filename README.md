# Quiz-4-7-corrections

## Quiz 4 Corrections/Explanations

### Question 11


Code 01. 

```
function askedAndAnswered (x, y, z) {

 var x = prompt("What is your  first name.");
 var z = prompt("How old are you?");
 var y = parseInt(z) + 1;
 
 alert("Hello, " + x + ". When do you turn " + y + "?");
 
}
  ```       
  
  Code 02.
  
  ```
  function classTrip() { 
   let y = prompt("Enter number of students that will be attending the trip.");
   let z = prompt("Enter number of chaperones, including teachers,that will be attending the trip.");
   let busMax = prompt("Not including the bus driver, enter the maximum capacity of each bus.");
   
   let x = (y +z)/busMax;
   x = Math.round(x);
   
   console.log(x + "busses are required to accomodate " + y + "students and " + z + "chaperones.")
}
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

### Question 7
I got this question partially wrong because I did not select all the answers that applied. 
```
if (a < b)
{
    // do something
}
```
The above is also a valid syntax for an if statement in JavaScript, making it a correct answer.

### Question 8
I got this question incorrect because I selected the switch statement instead of the else-if statements. The else-if statement was the most efficient and simple way to achieve the goal, not the the switch statement.

### Question 12
 I got this question worng because I selected:
 ```
 while (x > 100) {
   x++;
}
```


 The correct answer would be:
 ```
 while (x > 100) {
   x--;
}
```
 because this shows a valid loop that will run at least once and will terminate.

### Question 13
I got this question wrong because Anything written in the form a while (or do...while) loop can be achieved with an equivalent for loop and vice-a-versa. So the answer is true, not false. 

### Question 14
I got this question wrong. I thought that difference between  a while loop and do...while loop was that A while loop is designed to iterate an undetermined number of times, whereas a do...while loop is designed to iterate a set and specific number of times. However, the primary difference is actually that A while loop check its condition before running the loop body, whereas a do...while loop checks its condition after running the loop body.

### Question 15
I got this question wrong because I forgot how loops were executed. The correct answer would have been in the order of: setup, expression, loop body, update, and return to step 2. This is the order of how the components are executed.


## Quiz 6 Corrections/Explanations

### Question 5
I got this question partially incorrect because I only selected 1 of the 3 answers. 
When considering the following function:

```
function doSomeStuff(a, b, c) {
   console.log("I need to do " + a + ", " + b + ", and " + c + "... So busy!");
}

doSomeStuff("homework", "chores", "more homework");
doSomeStuff("chores", "homework");
doSomeStuff("homework", "homework", "more homework", "oh, and chores, too");
```

I was supposed to select ALL of the statements that will be logged to the console. However, I only picked the one that corressponded to:

```
doSomeStuff("homework", "chores", "more homework");
```

The answers that corresponded to 

```
doSomeStuff("chores", "homework");
```

and
```
doSomeStuff("homework", "homework", "more homework", "oh, and chores, too");
```
 should have been selected too.
```
I need to do homework, homework, and more homework... So busy!
```
and 
```  
I need to do chores, homework, and undefined... So busy!
```
are also the correct answers because they would've been logged to the console too, based on the function.

### Question 6
I got this question paertially wrong. For this question, I was to consider a given function and select what could be determined based on the info provided. I did not select the choice which stated "The function is not designed to accept any parameters." This is also a correct answer as there was nothing between the parenthesis which determines what the parameters are. 

### Question 7
I got this question wrong because even though I selected the right answer of "prompt", I also selected an additional incorrect answer of "console.log". Prompt is the correct answer because it is designed to return a value. However, "console.log" is not one of the built-in functions that are designed to return a value.

### Question 8
I got this question wrong. I was supposed to select an answer that would modify the given function so that it accepts as parameters the values being divided. The correct answer is 
```
function divide(a, b) {
   return a / b;
}
```
This is the correct revision that will make the function accept as parameters the values being divided. The answer I selected just named variables and prompted the user to enter any two two numbers, in which a divided by b was returned.

### Question 9
I got this question wrong because there were two correct answers, but I picked one correct and one incorrect answer.
The correct answers were :

```
let difference = subtract(x, y);
console.log(difference);
```
and
```
console.log(subtract(x, y));
```
because they are both ways to print the result of calling subtract to the console. The parameters also have to be stated to do this. 

My incorrect answer was:
```
console.log(subtract);
```
This does not print the result of calling subtract to the console and the parameters are not defined.

### Question 10
I got this question partially wrong because I selected "Math.random" to be one of the built-in functions that accept parameters. However, only prompt, alert, and console.log accept parameters.

### Question 14
I got this question wrong because I answered that "2" will be printed to the console. However, the correct answer is that a ReferenceError will occur on line 10. A ReferenceError occurs when a reference to a variable or object is made in code that doesn't exist or is outside the scope of the executing code.

### Question 15
I got this question partially wrong because I said the following code snippet would only print "undefined" to the console. However, 4 would also be printed to the console because it meets the parameters.

## Quiz 7 Corrections/Explanations

### Question 9
I got this question incorrect because I answered with false instead of true. The correct asnwer is true the code segment was asking to return numbers greater than 100 and less than 999. The values that were returned did meet these parameters. I must've looked over this question hastily and put in the obviously incorrect answer.
