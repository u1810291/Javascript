# Array
The JavaScript **`Array`** class is a global object that is used in the construction of arrays; which are high-level, list-like objects.

## Description
> Arrays are list-like objects whose prototype has methods to perform traversal and mutation operations. Neither the length of a JavaScript array nor the types of its elements are fixed. Since an array's length can change at any time, and data can be stored at non-contiguous locations in the array, JavaScript arrays are not guaranteed to be dense; this depends on how the programmer chooses to use them. In general, these are convenient characteristics; but if these features are not desirable for your particular use, you might consider using typed arrays.
---
> Arrays cannot use strings as element indexes (as in an [associative array](https://en.wikipedia.org/wiki/Associative_array)) but must use integers. Setting or accessing via non-integers using [bracket notation](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Working_with_Objects#objects_and_properties) (or [dot notation](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Property_Accessors)) will not set or retrieve an element from the array list itself, but will set or access a variable associated with that array's [object property collection](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Data_structures#properties). The array's object properties and list of array elements are separate, and the array's [traversal and mutation operations](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Indexed_collections#array_methods) cannot be applied to these named properties.

## Constructor
> [`Array()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/Array) Creates a new `Array` object.
## Static properties
> [`get Array[@@species]`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/@@species) The constructor function is used to create derived objects.
## Static methods
> [`Array.from()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/from) Creates a new `Array` instance from an array-like or iterable object.
> <br>[`Array.isArray()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/isArray) Returns `true` if the argument is an array, or `false` otherwise.
>  <br>[`Array.of()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/of) Creates a new `Array` instance with a variable number of arguments, regardless of number or type of the arguments.
## Instance properties
> [`Array.prototype.length`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/length) Reflects the number of elements in an array.
>  <br>[`Array.prototype[@@unscopables]`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/@@unscopables) A symbol containing property names to exclude from a [`with`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/with) binding scope.
## Instance methods
> [`Array.prototype.at()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/at) Returns the array item at the given index. Accepts negative integers, which count back from the last item.
> <br>[`Array.prototype.concat()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/concat) Returns a new array that is this array joined with other array(s) and/or value(s).
> <br>[`Array.prototype.copyWithin()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/copyWithin) Copies a sequence of array elements within the array.
> <br>[`Array.prototype.entries()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/entries) Returns a new _array iterator_ object that contains the key/value pairs for each index in the array.
> <br>[`Array.prototype.every()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/every)Returns `true` if every element in this array satisfies the testing function.
>  <br>[`Array.prototype.fill()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/fill) Fills all the elements of an array from a start index to an end index with a static value.
> <br>[`Array.prototype.filter()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/filter) Returns a new array containing all elements of the calling array for which the provided filtering function returns `true`.
> <br>[`Array.prototype.find()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/find) Returns the found `element` in the array, if some element in the array satisfies the testing function, or `undefined` if not found.
> <br>[`Array.prototype.findIndex()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/findIndex) Returns the found index in the array, if an element in the array satisfies the testing function, or `-1` if not found.
> <br>[`Array.prototype.flat()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/flat) Returns a new array with all sub-array elements concatenated into it recursively up to the specified depth.
> <br>[`Array.prototype.flatMap()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/flatMap) Returns a new array formed by applying a given callback function to each element of the array, and then flattening the result by one level.
> <br>[`Array.prototype.forEach()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/forEach) Calls a function for each element in the array.
> <br>[`Array.prototype.includes()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/includes) Determines whether the array contains a value, returning `true` or `false` as appropriate.
> <br>[`Array.prototype.indexOf()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/indexOf) Returns the first (least) index of an element within the array equal to an element, or `-1` if none is found.
> <br>[`Array.prototype.join()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/join) Joins all elements of an array into a string.
> <br>[`Array.prototype.keys()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/keys) Returns a new _array iterator_ that contains the keys for each index in the array.
> <br>[`Array.prototype.lastIndexOf()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/lastIndexOf) Returns the last (greatest) index of an element within the array equal to an element, or `-1` if none is found.
> <br>[`Array.prototype.map()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/map) Returns a new array containing the results of calling a function on every element in this array.
> <br>[`Array.prototype.pop()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/pop) Removes the last element from an array and returns that element.
> <br>[`Array.prototype.push()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/push) Adds one or more elements to the end of an array, and returns the new `length` of the array.
> <br>[`Array.prototype.reduce()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/Reduce) Apply a function against an accumulator and each value of the array (from left-to-right) as to reduce it to a single value.
> <br>[`Array.prototype.reduceRight()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/reduceRight) Apply a function against an accumulator and each value of the array (from right-to-left) as to reduce it to a single value.
> <br>[`Array.prototype.reverse()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/reverse) Reverses the order of the elements of an array _in place_. (First becomes the last, last becomes first.)
> <br>[`Array.prototype.shift()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/shift) Removes the first element from an array and returns that element. 
> <br>[`Array.prototype.slice()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/slice) Extracts a section of the calling array and returns a new array.
> <br>[`Array.prototype.some()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/some) Returns `true` if at least one element in this array satisfies the provided testing function.
> <br>[`Array.prototype.sort()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/sort) Sorts the elements of an array in place and returns the array.
> <br>[`Array.prototype.splice()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/splice) Adds and/or removes elements from an array.
> <br>[`Array.prototype.toLocaleString()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/toLocaleString) Returns a localized string representing the array and its elements. Overrides the [`Object.prototype.toLocaleString()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/toLocaleString) method.
> <br>[`Array.prototype.toString()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/toString) Returns a string representing the array and its elements. Overrides the [`Object.prototype.toString()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/toString) method.
> <br>[`Array.prototype.unshift()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/unshift) Adds one or more elements to the front of an array, and returns the new `length` of the array.
> <br>[`Array.prototype.values()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/values) Returns a new _array iterator_ object that contains the values for each index in the array. 
> <br>[`Array.prototype[@@iterator]()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/@@iterator) Returns a new _array iterator_ object that contains the values for each index in the array.


# Object
The **`Object`** class represents one of [JavaScript's data types](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Data_structures). It is used to store various keyed collections and more complex entities. Objects can be created using the [`Object()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/Object) constructor or the [object initializer / literal syntax](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Object_initializer).

## Description

> Nearly all objects in JavaScript are instances of [`Object`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object); a typical object inherits properties (including methods) from `Object.prototype`, although these properties may be shadowed (a.k.a. overridden). However, an `Object` may be deliberately created for which this is not true (e.g. by [`Object.create(null)`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/create)), or it may be altered so that this is no longer true (e.g. with [`Object.setPrototypeOf`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/setPrototypeOf)).

> Changes to the `Object` prototype object are seen by **all** objects through prototype chaining, unless the properties and methods subject to those changes are overridden further along the prototype chain. This provides a very powerful although potentially dangerous mechanism to override or extend object behavior.

> The `Object` constructor creates an object wrapper for the given value.

> -   If the value is [`null`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/null) or [`undefined`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined), it will create and return an empty object.
> -   Otherwise, it will return an object of a Type that corresponds to the given value.
> -   If the value is an object already, it will return the value.

> When called in a non-constructor context, `Object` behaves identically to `new Object()`.

### Deleting a property from an object

> There isn't any method in an Object itself to delete its own properties (such as [`Map.prototype.delete()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Map/delete)). To do so, one must use the [delete operator](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/delete).

## Constructor

> [`Object()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/Object) Creates a new `Object` object. It is a wrapper for the given value.

## Static methods

> [`Object.assign()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/assign) Copies the values of all enumerable own properties from one or more source objects to a target object.
> <br>[`Object.create()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/create) Creates a new object with the specified prototype object and properties.
> <br>[`Object.defineProperty()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/defineProperty) Adds the named property described by a given descriptor to an object. 
> <br>[`Object.defineProperties()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/defineProperties) Adds the named properties described by the given descriptors to an object.
> <br>[`Object.entries()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/entries) Returns an array containing all of the `[key, value]` pairs of a given object's **own** enumerable string properties.
> <br>[`Object.freeze()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/freeze) Freezes an object. Other code cannot delete or change its properties.
> <br>[`Object.fromEntries()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/fromEntries) Returns a new object from an iterable of `[key, value]` pairs. (This is the reverse of [`Object.entries`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/entries)).
> <br>[`Object.getOwnPropertyDescriptor()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/getOwnPropertyDescriptor) Returns a property descriptor for a named property on an object.
> <br>[`Object.getOwnPropertyDescriptors()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/getOwnPropertyDescriptors) Returns an object containing all own property descriptors for an object.
> <br>[`Object.getOwnPropertyNames()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/getOwnPropertyNames) Returns an array containing the names of all of the given object's **own** enumerable and non-enumerable properties.
> <br>[`Object.getOwnPropertySymbols()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/getOwnPropertySymbols) Returns an array of all symbol properties found directly upon a given object.
> <br>[`Object.getPrototypeOf()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/getPrototypeOf) Returns the prototype (internal `[[Prototype]]` property) of the specified object.
> <br>[`Object.is()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/is) Compares if two values are the same value. Equates all `NaN` values (which differs from both Abstract Equality Comparison and Strict Equality Comparison).
> <br>[`Object.isExtensible()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/isExtensible) Determines if extending of an object is allowed.
> <br>[`Object.isFrozen()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/isFrozen) Determines if an object was frozen.
> <br>[`Object.isSealed()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/isSealed) Determines if an object is sealed.
> <br>[`Object.keys()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/keys) Returns an array containing the names of all of the given object's **own** enumerable string properties.
> <br>[`Object.preventExtensions()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/preventExtensions) Prevents any extensions of an object.
> <br>[`Object.seal()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/seal) Prevents other code from deleting properties of an object.
> <br>[`Object.setPrototypeOf()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/setPrototypeOf) Sets the object's prototype (its internal `[[Prototype]]` property).
> <br>[`Object.values()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/values) Returns an array containing the values that correspond to all of a given object's **own** enumerable string properties.

## Instance properties
> [`Object.prototype.constructor`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/constructor) Specifies the function that creates an object's prototype.
> <br>[`Object.prototype.__proto__`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/proto) Points to the object which was used as prototype when the object was instantiated.

## Instance methods

> [`Object.prototype.__defineGetter__()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/__defineGetter__) Associates a function with a property that, when accessed, executes that function and returns its return value.
> <br>[`Object.prototype.__defineSetter__()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/__defineSetter__) Associates a function with a property that, when set, executes that function which modifies the property.
> <br>[`Object.prototype.__lookupGetter__()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/__lookupGetter__) Returns the function associated with the specified property by the [`__defineGetter__()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/__defineGetter__) method.
> <br>[`Object.prototype.__lookupSetter__()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/__lookupSetter__) Returns the function associated with the specified property by the [`__defineSetter__()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/__defineSetter__) method.
> <br>[`Object.prototype.hasOwnProperty()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/hasOwnProperty) Returns a boolean indicating whether an object contains the specified property as a direct property of that object and not inherited through the prototype chain.
> <br>[`Object.prototype.isPrototypeOf()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/isPrototypeOf) Returns a boolean indicating whether the object this method is called upon is in the prototype chain of the specified object.
> <br>[`Object.prototype.propertyIsEnumerable()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/propertyIsEnumerable) Returns a boolean indicating if the internal [ECMAScript [[Enumerable]] attribute](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Data_structures#properties) is set.
> <br>[`Object.prototype.toLocaleString()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/toLocaleString) Calls [`toString()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/toString).
> <br>[`Object.prototype.toString()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/toString) Returns a string representation of the object.
> <br>[`Object.prototype.valueOf()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/valueOf) Returns the primitive value of the specified object.