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
> [`this`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/this) <br>The `this` keyword refers to a special property of an execution context.
> [`function`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/function) <br>The `function` keyword defines a function expression.
> [`class`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/class) <br>The `class` keyword defines a class expression.
> [`function*`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/function*) <br>The `function*` keyword defines a generator function expression.
> [`yield`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/yield) <br>Pause and resume a generator function.
> [`yield*`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/yield*) <br>Delegate to another generator function or iterable object.
> [`async function`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/async_function) <br>The `async function` defines an async function expression.
> [`await`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/await) <br>Pause and resume an async function and wait for the promise's resolution/rejection.
> [`[]`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array) <br>Array initializer/literal syntax.
> [`{}`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Object_initializer) <br>Object initializer/literal syntax.
> [`/ab+c/i`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/RegExp) <br>Regular expression literal syntax.
> [`( )`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Grouping) <br>Grouping operator.
### Left-hand-side expressions
> **Left values are the destination of an assignment.**
> [Property accessors](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Property_Accessors) <br>Member operators provide access to a property or method of an object (`object.property` and `object["property"]`).
> [`new`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/new) <br>The `new` operator creates an instance of a constructor.
> [`new.target`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/new.target)<br>In constructors, `new.target` refers to the constructor that was invoked by [`new`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/new).
> [`import.meta`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/import.meta)<br>An object exposing context-specific metadata to a JavaScript module.
> [`super`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/super)<br>The `super` keyword calls the parent constructor.
> [`...obj`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Spread_syntax)<br>Spread syntax allows an expression to be expanded in places where multiple arguments (for function calls) or multiple elements (for array literals) are expected.

### Increment and decrement
> Postfix/prefix increment and postfix/prefix decrement operators.
> [`A++`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Increment)<br>Postfix increment operator.
> [`A--`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Decrement)<br>Postfix decrement operator.
> [`++A`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Increment)<br>Prefix increment operator.
> [`--A`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Decrement)<br>Prefix decrement operator.
### Unary operators
> A unary operation is an operation with only one operand.
> [`delete`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/delete) <br>The `delete` operator deletes a property from an object.
> [`void`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/void) <br>The `void` operator discards an expression's return value.
> [`typeof`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/typeof)<br>The `typeof` operator determines the type of a given object.
> [`+`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Unary_plus)<br>The unary plus operator converts its operand to Number type.
> [`-`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Unary_negation)<br>The unary negation operator converts its operand to Number type and then negates it.
> [`~`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Bitwise_NOT)<br>Bitwise NOT operator.
> [`!`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Logical_NOT)<br>Logical NOT operator.
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
      <td><code>var1 != 4<br>var2 != "3"</code></td>
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
      <td><code>var1 !== "3"<br>3 !== '3'</code></td>
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
      <td><code>var2 &gt; var1<br>"12" &gt; 2</code></td>
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
      <td><code>var2 &gt;= var1<br>var1 &gt;= 3</code></td>
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
      <td><code>var1 &lt; var2<br>"2" &lt; 12</code></td>
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
      <td><code>var1 &lt;= var2<br>var2 &lt;= 5</code></td>
    </tr>
  </tbody>
</table>