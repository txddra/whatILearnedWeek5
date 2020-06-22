# whatILearnedWeek5
This week has been filled with a various amount of projects and new techniques.
 ### we learned a bit about 
 - **if /else statements**
 - **return**
 - **switch statements**
---

 ## [Conditional Statements](https://www.guru99.com/how-to-use-conditional-statements-in-javascript.html)

 ![](https://www.guru99.com/images/JavaScript/javascript5_1.png)

 
  **If statement**
  - Use `if` to specify a block of code to be executed, if a specified condition is true


_Syntax:_

`if (condition){
lines of code to be executed if condition is true
}`


 - the if statement executes a statement if a specified condition is truthy. If the condition is falsy, another statement can be executed.


*i.e.*

`
function testNum(a) {
  let result;
  if (a > 0) {
    result = 'positive';
  } else {
    result = 'NOT positive';
  }
  return result;
}
`

**If...Else Statement**


_Syntax:_

`if (condition){
lines of code to be executed if the condition is true
}else{
lines of code to be executed if the condition is false
}`



**If…Else If…Else statement**
- You can use `If….Else If….Else` statement if you want to check more than two conditions.

_Syntax_:

`
if (condition1)

{

lines of code to be executed if condition1 is true

}

else if(condition2)

{

lines of code to be executed if condition2 is true

}

else

{

lines of code to be executed if condition1 is false and condition2 is false

}
`

## The ["switch"](https://javascript.info/switch) statement

A switch statement can replace multiple if checks.

It gives a more descriptive way to compare a value with multiple variants.
The syntax

The switch has one or more case blocks and an optional default.

It looks like this:

`
switch(x) {
  case 'value1':  // if (x === 'value1')
    ...
    [break]

  case 'value2':  // if (x === 'value2')
    ...
    [break]

  default:
    ...
    [break]
}
`