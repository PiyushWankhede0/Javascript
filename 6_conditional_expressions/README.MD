1. Alert box : An alert box is one type of popup boxes in JavaScript which is often used to make sure that information have come through the user. So, the user will have to click “OK” to proceed when an alert box pops up on the window. 

Syntax :
window.alert("message");
Another syntax to use alert box is :
alert("message");

2. Prompt box : It is also one of the type of popup boxes in JavaScript which is often to take input a value before entering a page from the user. To proceed after entering an input value in the prompt, the user will have to click either “OK” or “Cancel”. 

Syntax :
window.prompt("some message");
Another syntax to use alert box is :
prompt("some message");


 if to specify a block of code to be executed, if a specified condition is true
 else to specify a block of code to be executed, if the same condition is false
 else if to specify a new condition to test, if the first condition is false
 switch to specify many alternative blocks of code to be executed


1) The if Statement
Use the if statement to specify a block of JavaScript code to be executed if a condition is true.

Syntax
if (condition) {
  //  block of code to be executed if the condition is true
}

2) The else Statement
Use the else statement to specify a block of code to be executed if the condition is false.

if (condition) {
  //  block of code to be executed if the condition is true
} else {
  //  block of code to be executed if the condition is false
}

3) The else if Statement
Use the else if statement to specify a new condition if the first condition is false.

Syntax
if (condition1) {
  //  block of code to be executed if condition1 is true
} else if (condition2) {
  //  block of code to be executed if the condition1 is false and condition2 is true
} else {
  //  block of code to be executed if the condition1 is false and condition2 is false
}



   Usage of JavaScript switch statement
JavaScript switch statement is used with a break or default keyword (optional and both can be used together also).

1) break: This keyword is used to break out of the switch block. This stops the execution inside the code block.
2) default: This keyword is used to specify a piece of code if no case matches the given condition. There can be only one default keyword in a switch statement.

Syntax
switch (expression) {
    case value1:
        statement1;
        break;
    case value2:
        statement2;
        break;
    .
    .
    case valueN:
        statementN;
        break;
    default:
        statementDefault;
}