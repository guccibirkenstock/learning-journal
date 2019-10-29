# Algorithmic thinking techniques
1. Giving info to the PC
2. Give a name to a piece of info (naming/DECLARING a variable)
3. Change the value of a variable 
4. Changing a variable based on itself ( n=1 .... n=n+1)
5. Printing values to the screen
6. Get values from the user
7. Comparing values '=== -> equals, !== -> does not equal'  
when comparing to comparisons...
false || false  = false  
false || true   = true  
true || false   = true  
true || true    = true  
  
replacing the || with &&, evaluates if BOTH expressions are true, as long as all expressions being compared are 'true', the return will be true, if any expressions values are false, the && answer will be false.  
false && false = false  
false && true = false  
true && false = false   
true && true = true  

>
'cat' === 'cat' || 'banana' === 'pizza'  
true  
'cat' === 'cat' && 'banana' === 'pizza'   
false   
>  
  
8. Make decisions based on compared values (true/false)
>
if (condition) {     -->
'code'
} else if (another condition) {
'code'
} else {
'code'
}
>
- only one part of code will run, BASED off of the conddition.  Which ever condition evaluates as true, that is the code that will run
