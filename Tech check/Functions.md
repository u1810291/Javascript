# Functions

> Generally speaking, a function is a "subprogram" that can be _called_ by code external (or internal in the case of recursion) to the function. Like the program itself, a function is composed of a sequence of statements called the _function body_. Values can be _passed_ to a function, and the function will _return_ a value.
>
> In JavaScript, functions are first-class objects, because they can have properties and methods just like any other object. What distinguishes them from other objects is that functions can be called. In brief, they are [`Function`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Function) objects.
>
> For more examples and explanations, see also the [JavaScript guide about functions](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Functions).

## Description

> Every function in JavaScript is a `Function` object. See [`Function`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Function) for information on properties and methods of `Function` objects.
>
> To return a value other than the default, a function must have a [`return`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/return) statement that specifies the value to return. A function without a return statement will return a default value. In the case of a [constructor](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/constructor) called with the [`new`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/new) keyword, the default value is the value of its `this` parameter. For all other functions, the default return value is [`undefined`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined).
>
> The parameters of a function call are the function's _arguments_. Arguments are passed to functions _by value_. If the function changes the value of an argument, this change is not reflected globally or in the calling function. However, object references are values, too, and they are special: if the function changes the referred object's properties, that change is visible outside the function, as shown in the following example:
## Constructor vs. declaration vs. expression

> Compare the following:
>
> A function defined with the `Function` _constructor_ assigned to the variable `multiply`:
>
>```
>var multiply = new Function('x', 'y', 'return x * y');
>```
---
> A _function declaration_ of a function named `multiply`:
> ```
> function multiply(x, y) {
> return x * y;
> } // there is no semicolon here
> ```
---
> A _function expression_ of an anonymous function assigned to the variable `multiply`:
> ```
> var multiply = function(x, y) {
> return x * y;
> };
> ```
---
>A _function expression_ of a function named `func_name` assigned to the variable `multiply`:
>```
>var multiply = function func_name(x, y) {
>return x * y;
>};
>```