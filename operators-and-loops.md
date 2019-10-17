# operators and loops

### comparison operators, evaluating condition
```
== is equal to
!= is not equal to
=== strictly equal to
!== strictly not equal to
> greater than
< less than
>= greater than or equal to
<= less than or equal to 
```
- you can evaluate a situation by comparing one value in the script to what you might expect it to be.  The result will be a 
bollean: True or False
- comparison operators usually return single values of true or false
- every value can be treated as a true or false even if it is not a *boolean* true or false value

### logical operators
```
&& (logical and) tests more than one condition
((2 < 5) && (3 >= 2)) ---> RETURNS TRUE
```
if both exressions evaluate to true then the expression returns true.  If just one of these returns false, then the 
expression will return false
```
|| (logical or) tests at least one condition
((2 < 5) || (2<1)) ---> RETURNS TRUE
```
if either expression evaluates to true, then the expression returns true.  If both return false then the expression will 
return false.
```
! (logical not) takes a single Boolean value and inverts it
!(2 < 1) ---> RETURNS TRUE
```
this reverses the state of an expression.  if the expression was false (without the '!' in front of it) it would return as true.
if the statement before '!' was true, it would return false after the logical not operator
- Logical opertors compare the results of more than one comparison operator

### loops
- **for loop**- use if you need to run a code a *specific number of times*.  the condition in a for loop is usually a 
counter that tells the loop how many times to run
- **while loop**- use if you do not know how many times the code should run. the condition can be something other than a counter,
and the code will continue to loop for as long as the condition is *true*
- ** do while loop**- very similar to the *while loop* but will run the statements inside the curly braces *at least once* even 
if the condition evaluates to false

### loop counters
- a *for loop* uses a counter as a condition.  the counter instructs the code to run a specified number of times
- a condition is made up of 3 statements
1. initialization - creating a variable.  The variable is only created, and the value is only set the first time the loop is run.
if there are changes to the variable value, those changes will take effect the next time the loop is run until the loop is no
longer running, and then the value resets for the next time the loop begins.
1. condition
1. update

```
for (var i=0; i<10; i++) {
document.write(i)
```
the first time the loop is run, the variable i (the counter) is assigned to a value of 0.  Every time the loop is run, the condition
is checked (is the variable i<10?). Then the code inside the loop (the statements inside the curly braces) is run.  When the statements
have finished, the variable i is incremented by 1. When the condition is no longer true, the loop ends.
