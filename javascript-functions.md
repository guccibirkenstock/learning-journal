# functions in javascript
- JavaScript allows you to make websites more interactive by accessing and modifying the content and markup used while
its being viewed in the browswer
- js can help you create forms, slideshows, fliter data, or even reload specific parts of a page 
- a *script* is a series of instructions that a computer can follow to achieve a goal
- to write a script, you need to state a goal, list every task that needs to be completed in order to meet that goal, and then
code each each step it takes to complete those tasks.  Each goal may and will require multiple tasks to be completed, and each
task might have multiple steps that need to be taken to complete the task.
- functions help us avoid repetition
(ideally keep in mind which steps go first second third etc. when writing up your goal and tasks)
- an *expression* evaluates into (results in) a single value. broadly speaking, there are two types of expressions
1. expressions that just assign a value to a variable `ex: var color = 'beige';`
1. expressions that use two or more values to return a single value `ex: var area = 3 * 2;`
- expressions rely on *operators* which allow programmers to create a single value from one or more values ex `color = 'beige';`(assignment operator, assign a value to a variable)(the value of color is now beige) `area = 3 * 2;`(arithmetic operator, perform basic math)(the value of area is now 6) `greeting = 'hi' + 'Molly';`(string operator, combine two strings)(the value of greeting is now Hi Molly) `buy = 3 > 5;`(comparison operator, compare two values and return true or false)(the value of buy is false) `buy = (5 > 3) && (2 < 4);`(logical operators, combine expressions and return true or false)(the value of buy is now true)
```
addition       (+)   -  adds one value to another
subtraction    (-)   -  subtracts one value from another
division       (/)   -  divides to values
miltiplication (*)   -  miltiplies two values
incriment      (++)  -  adds one to the current number (i=10; i++; result would be 11)
decrement      (--)  -  subtracts one from the current number (i=10; i--; result would be 9)
modulus        (%)   -  divides two values and returns the remainder (10 % 3 result would be 1)
```
to declare a function (lets say we want to call the function askName)
```
function askName(){
  var username = prompt('what is your name?');
  return '<h3>' + 'hello, ' + username + '.' + '</h3>;
}
```
this way is easier.
   *** declaring a function just creates it, we have to use a function call to make that funciton do something.  
you can also set the function equal to a variable
```
var getName = function (){
  var username = prompt('whats your name?');
  return '<h3>' = 'hello, ' + username + '</h3>';
}
```
