## Scope, hoisting and compartmentalization

### Answer the following:
In you own words, explain the concepts of scope, hoisting, compartmentalization.

* Scope is the accessibility of variables and functions to other parts of code at runtime.
* Hoisting is the moving of all variable and function delcarations, not their values, to the top of their scope.
* Compartmentalization keeps code contained so that it does not affect other parts of the project or pollute the global scope.

### Provide examples for all three, below:

#### Scope: 
All Javascript variables defined outside of a function are part of the global scope. Variables defined within a function have a local scope and are only available inside the function.

#### Hoisting:
Function hoisting allows a function to be called at the top of the code, even though the function is defined at the botttom of the code. This is because at runtime the function delcarations are hoisted to the top of the program so that they become immediately available to any code in the program.

#### Compartmentalization:
An Immediately-Invoked Function Expressions (IIFE) is a good example of compartmentalization. Any variable declared inside of an IIFE is safe from being unintentionally accessed elsewhere in your code.
