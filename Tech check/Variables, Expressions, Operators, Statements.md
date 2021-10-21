# Variables
## `Var`
> Before the advent of ES6, `var` declarations ruled. There are issues associated with variables declared with `var`, though. That is why it was necessary for new ways to declare variables to emerge. First, let's get to understand `var` more before we discuss those issues.
## `Let`
> `let` is now preferred for variable declaration. It's no surprise as it comes as an improvement to `var` declarations. It also solves the problem with `var` that we just covered. Let's consider why this is so.
## `Const`
> Variables declared with the `const` maintain constant values. `const` declarations share some similarities with `let` declarations.

### `Hoisting of const`
> Just like `let`, `const` declarations are hoisted to the top but are not initialized. 
> So just in case you missed the differences, here they are:
> - `var` declarations are globally scoped or function scoped while `let` and `const` are block scoped.
> -   `var` variables can be updated and re-declared within its scope; `let` variables can be updated but not re-declared; `const` variables can neither be updated nor re-declared.
> -   They are all hoisted to the top of their scope. But while `var` variables are initialized with `undefined`, `let` and `const` variables are not initialized.
> -   While `var` and `let` can be declared without being initialized, `const` must be initialized during declaration.
# Expressions & Operators
### Primary expressions

> **Basic keywords and general expressions in JavaScript.**
> <br>[`this`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/this) The `this` keyword refers to a special property of an execution context.
> <br>[`function`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/function) The `function` keyword defines a function expression.
> <br>[`class`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/class) The `class` keyword defines a class expression.
> <br>[`function*`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/function*) The `function*` keyword defines a generator function expression.
> <br>[`yield`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/yield) Pause and resume a generator function.
> <br>[`yield*`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/yield*) Delegate to another generator function or iterable object.
> <br>[`async function`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/async_function) The `async function` defines an async function expression.
> <br>[`await`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/await) Pause and resume an async function and wait for the promise's resolution/rejection.
> <br>[`[]`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array) Array initializer/literal syntax.
> <br>[`{}`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Object_initializer) Object initializer/literal syntax.
> <br>[`/ab+c/i`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/RegExp) Regular expression literal syntax.
> <br>[`( )`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Grouping) Grouping operator.
### Left-hand-side expressions
> **Left values are the destination of an assignment.**
> <br>[Property accessors](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Property_Accessors) Member operators provide access to a property or method of an object (`object.property` and `object["property"]`).
> <br>[`new`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/new) The `new` operator creates an instance of a constructor.
> <br>[`new.target`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/new.target)In constructors, `new.target` refers to the constructor that was invoked by [`new`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/new).
> <br>[`import.meta`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/import.meta)An object exposing context-specific metadata to a JavaScript module.
> <br>[`super`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/super)The `super` keyword calls the parent constructor.
> <br>[`...obj`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Spread_syntax)Spread syntax allows an expression to be expanded in places where multiple arguments (for function calls) or multiple elements (for array literals) are expected.

### Increment and decrement
> Postfix/prefix increment and postfix/prefix decrement operators.
> <br>[`A++`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Increment)Postfix increment operator.
> <br>[`A--`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Decrement)Postfix decrement operator.
> <br>[`++A`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Increment)Prefix increment operator.
> <br>[`--A`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Decrement)Prefix decrement operator.
### Unary operators
> A unary operation is an operation with only one operand.
> <br>[`delete`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/delete) The `delete` operator deletes a property from an object.
> <br>[`void`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/void) The `void` operator discards an expression's return value.
> <br>[`typeof`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/typeof)The `typeof` operator determines the type of a given object.
> <br>[`+`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Unary_plus)The unary plus operator converts its operand to Number type.
> <br>[`-`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Unary_negation)The unary negation operator converts its operand to Number type and then negates it.
> <br>[`~`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Bitwise_NOT)Bitwise NOT operator.
> <br>[`!`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Logical_NOT)Logical NOT operator.
### Arithmetic operators
> Arithmetic operators take numerical values (either literals or variables) as their operands and return a single numerical value.
> <br>[`+`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Addition) Addition operator.
> <br>[`-`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Subtraction) Subtraction operator.
> <br>[`/`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Division) Division operator.
> <br>[`*`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Multiplication) Multiplication operator.
> <br>[`%`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Remainder) Remainder operator.
> <br>[`**`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Exponentiation) Exponentiation operator.

### Relational operators
> A comparison operator compares its operands and returns a boolean value based on whether the comparison is true.
> <br>[`in`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/in) The `in` operator determines whether an object has a given property.
> <br>[`instanceof`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/instanceof) The `instanceof` operator determines whether an object is an instance of another object.
> <br>[`<`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Less_than) Less than operator.
> <br>[`>`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Greater_than) Greater than operator.
> <br>[`<=`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Less_than_or_equal) Less than or equal operator.
> <br>[`>=`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Greater_than_or_equal) Greater than or equal operator.
### Equality operators
> The result of evaluating an equality operator is always of type boolean based on whether the comparison is true.
> <br>[`==`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Equality) Equality operator.
> <br>[`!=`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Inequality) Inequality operator.
> <br>[`===`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Strict_equality) Strict equality operator.
> <br>[`!==`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Strict_inequality) Strict inequality operator.
### Bitwise shift operators
> Operations to shift all bits of the operand.
> <br>[`<<`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Left_shift) Bitwise left shift operator.
>  <br>[`>>`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Right_shift) Bitwise right shift operator.
>   <br>[`>>>`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Unsigned_right_shift) Bitwise unsigned right shift operator.
### Binary bitwise operators
> Bitwise operators treat their operands as a set of 32 bits (zeros and ones) and return standard JavaScript numerical values.
> <br>[`&`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Bitwise_AND) Bitwise AND.
> <br>[`|`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Bitwise_OR) Bitwise OR.
> <br>[`^`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Bitwise_XOR) Bitwise XOR

### Binary logical operators
> Logical operators are typically used with boolean (logical) values, and when they are, they return a boolean value. 
> <br>[`&&`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Logical_AND) Logical AND.
> <br>[`||`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Logical_OR) Logical OR.
> <br>[`??`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Nullish_coalescing_operator) Nullish Coalescing Operator.
### Conditional (ternary) operator
> [`(condition ? ifTrue : ifFalse)`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Conditional_Operator) The conditional operator returns one of two values based on the logical value of the condition.
### Optional Chaining operator
> [`?.`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Optional_chaining) The optional chaining operator returns `undefined` instead of causing an error if a reference is `nullish` or `undefined`
### Assignment operators
> An assignment operator assigns a value to its left operand based on the value of its right operand.
> <br>[`=`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Assignment) Assignment operator.
> <br>[`*=`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Multiplication_assignment) Multiplication assignment.
> <br>[`**=`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Exponentiation_assignment) Exponentiation assignment.
> <br>[`/=`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Division_assignment) Division assignment.
> <br>[`%=`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Remainder_assignment) Remainder assignment.
> <br>[`+=`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Addition_assignment) Addition assignment.
> <br>[`-=`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Subtraction_assignment) Subtraction assignment
> <br>[`<<=`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Left_shift_assignment) Left shift assignment.
> <br>[`>>=`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Right_shift_assignment) Right shift assignment.
> <br>[`>>>=`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Unsigned_right_shift_assignment) Unsigned right shift assignment.
> <br>[`&=`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Bitwise_AND_assignment) Bitwise AND assignment.
> <br>[`^=`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Bitwise_XOR_assignment) Bitwise XOR assignment.
> <br>[`|=`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Bitwise_OR_assignment) Bitwise OR assignment.
> <br>[`&&=`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Logical_AND_assignment) Logical AND assignment.
> <br>[`||=`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Logical_OR_assignment) Logical OR assignment.
> <br>[`??=`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Logical_nullish_assignment) Logical nullish assignment.
> <br>[`[a, b] = [1, 2]`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Destructuring_assignment) `{a, b} = {a:1, b:2}`Destructuring assignment allows you to assign the properties of an array or object to variables using syntax that looks similar to array or object literals.

### Comma operator
> [`,`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Comma_Operator) The comma operator allows multiple expressions to be evaluated in a single statement and returns the result of the last expression.
# Comparison operators
> A comparison operator compares its operands and returns a logical value based on whether the comparison is true. The operands can be numerical, string, logical, or object values. Strings are compared based on standard lexicographical ordering, using Unicode values. In most cases, if the two operands are not of the same type, JavaScript attempts to convert them to an appropriate type for the comparison. This behavior generally results in comparing the operands numerically. The sole exceptions to type conversion within comparisons involve the `===` and `!==` operators, which perform strict equality and inequality comparisons. These operators do not attempt to convert the operands to compatible types before checking equality. The following table describes the comparison operators in terms of this sample code:
<table class="standard-table">
  <caption>Comparison operators</caption>
  <thead>
    <tr>
      <th scope="col">Operator</th>
      <th scope="col">Description</th>
      <th scope="col">Examples returning true</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        Equal
        (<code>==</code>)
      </td>
      <td>Returns <code>true</code> if the operands are equal.</td>
      <td><code>3 == var1</code>
        <p><code>"3" == var1</code></p><code>3 == '3'</code>
      </td>
    </tr>
    <tr>
      <td>
        Not equal
        (<code>!=</code>)
      </td>
      <td>Returns <code>true</code> if the operands are not equal.</td>
      <td><code>var1 != 4var2 != "3"</code></td>
    </tr>
    <tr>
      <td>
        Strict equal
        (<code>===</code>)
      </td>
      <td>
        Returns <code>true</code> if the operands are equal and of the same
        type. See also <code>Object.is</code> and
        sameness in JS.
      </td>
      <td><code>3 === var1</code></td>
    </tr>
    <tr>
      <td>
        Strict not equal
        (<code>!==</code>)
      </td>
      <td>
        Returns <code>true</code> if the operands are of the same type but not
        equal, or are of different type.
      </td>
      <td><code>var1 !== "3"3 !== '3'</code></td>
    </tr>
    <tr>
      <td>
        Greater than
        (<code>&gt;</code>)
      </td>
      <td>
        Returns <code>true</code> if the left operand is greater than the right
        operand.
      </td>
      <td><code>var2 &gt; var1"12" &gt; 2</code></td>
    </tr>
    <tr>
      <td>
        Greater than or equal
        (<code>&gt;=</code>)
      </td>
      <td>
        Returns <code>true</code> if the left operand is greater than or equal
        to the right operand.
      </td>
      <td><code>var2 &gt;= var1var1 &gt;= 3</code></td>
    </tr>
    <tr>
      <td>
        Less than
        (<code>&lt;</code>)
      </td>
      <td>
        Returns <code>true</code> if the left operand is less than the right
        operand.
      </td>
      <td><code>var1 &lt; var2"2" &lt; 12</code></td>
    </tr>
    <tr>
      <td>
        Less than or equal
        (<code>&lt;=</code>)
      </td>
      <td>
        Returns <code>true</code> if the left operand is less than or equal to
        the right operand.
      </td>
      <td><code>var1 &lt;= var2var2 &lt;= 5</code></td>
    </tr>
  </tbody>
</table>

# Statements & declarations
`JavaScript applications consist of statements with an appropriate syntax. A single statement may span multiple lines. Multiple statements may occur on a single line if each statement is separated by a semicolon. This isn't a keyword, but a group of keywords.`

## Statements and declarations by category
### Control flow
> <br>[Block](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/block) A block statement is used to group zero or more statements. The block is delimited by a pair of curly brackets.
> <br>[`break`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/break) Terminates the current loop, switch, or label statement and transfers program control to the statement following the terminated statement.
> <br>[`continue`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/continue) Terminates execution of the statements in the current iteration of the current or labeled loop, and continues execution of the loop with the next iteration.
> <br>[Empty](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/Empty) An empty statement is used to provide no statement, although the JavaScript syntax would expect one.
> <br>[`if...else`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/if...else) Executes a statement if a specified condition is true. If the condition is false, another statement can be executed.
> <br>[`switch`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/switch) Evaluates an expression, matching the expression's value to a case clause, and executes statements associated with that case.
> <br>[`throw`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/throw) Throws a user-defined exception.
> <br>[`try...catch`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/try...catch) Marks a block of statements to try, and specifies a response, should an exception be thrown.

### Declarations
> [`var`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/var) Declares a variable, optionally initializing it to a value.
> <br>[`let`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/let) Declares a block scope local variable, optionally initializing it to a value.
> <br>[`const`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/const) Declares a read-only named constant.
### Functions and classes
> [`function`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/function) Declares a function with the specified parameters.
> <br>[`function*`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/function*) Generator Functions enable writing iterators more easily.
> <br> [`async function`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/async_function) Declares an async function with the specified parameters.
> <br>[`return`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/return) Specifies the value to be returned by a function.
> <br>[`class`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/class) Declares a class.

### Iterations
> [`do...while`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/do...while) Creates a loop that executes a specified statement until the test condition evaluates to false. The condition is evaluated after executing the statement, resulting in the specified statement executing at least once.
> <br>[`for`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/for) Creates a loop that consists of three optional expressions, enclosed in parentheses and separated by semicolons, followed by a statement executed in the loop.
> <br>[`for...in`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/for...in) Iterates over the enumerable properties of an object, in arbitrary order. For each distinct property, statements can be executed.
> <br>[`for...of`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/for...of) Iterates over iterable objects (including [arrays](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array), array-like objects, [iterators and generators](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Iterators_and_Generators)), invoking a custom iteration hook with statements to be executed for the value of each distinct property.
> <br>[`for await...of`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/for-await...of) Iterates over async iterable objects, array-like objects, [iterators and generators](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Iterators_and_Generators), invoking a custom iteration hook with statements to be executed for the value of each distinct property.
> <br>[`while`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/while) Creates a loop that executes a specified statement as long as the test condition evaluates to true. The condition is evaluated before executing the statement.
### Others
> [`debugger`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/debugger) Invokes any available debugging functionality. If no debugging functionality is available, this statement has no effect. 
> <br>[`export`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/export) Used to export functions to make them available for imports in external modules, and other scripts. 
> <br>[`import`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/import) Used to import functions exported from an external module, another script.
> <br>[`import.meta`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/import.meta) Exposes context-specific metadata to a JavaScript module.
> <br>[`label`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/label) Provides a statement with an identifier that you can refer to using a `break` or `continue` statement.
> <br>[`with`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/with) Extends the scope chain for a statement.