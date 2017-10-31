# javascript-functions.
difference between function statement and function expression in javascript.
Function statement:The function statement declares a function which will be executed when invoked. functions are objects with both, properties and methods.
Example: https://gist.github.com/nitinmanocha16/5572f3b091b9d18b672393196f079cb5
Function expression: A function expression can be stored in a variable. After a function expression has been stored in a variable, the variable can be used as a function itself. Functions stored in variables do not need function names. They are always called using the variable name.
Example:
https://gist.github.com/nitinmanocha16/8deab164c8c9b3f7de439f9975ae6a73
Difference:
In the function statement, it doesn't matter whether we have written “console” before or after the function declaration because it sets priority for the execution. the declaration of the function will be set on the top of execution context and the console part will be executed after the declaration part which means it won’t show any error in case of function statement.
A Function expression load only when the interpreter reaches the definition of the function. It is required to declare the function initially.
Examples: https://gist.github.com/nitinmanocha16/e447de8df05db7e3f64ed04893e0b752
