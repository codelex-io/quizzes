# JavaScript

---
Which of these are JavaScript types?

1. ✔ object
1. ✔ symbol
1. enum
1. array

---
```javascript
function foo(a) {
  console.log( a + b );
  let b = a;
}
foo(2);
```

What is the output?

1. 4  
1. ✔ NaN  
1. 2  
1. Error

---
How would you execute (call) this function?

```javascript
(function foo(){
  console.log( "Hello!" );
})();
```

1. This type of function expression syntax is not valid in JavaScript  
1. By calling it with `foo()`;  
1. ✔ No need to call it, it is immediately invoked by () at the end of the expression  
1. By calling it with `foo.call();`

---
Which of these data types are not available in JavaScript?

1. String
1. Boolean
1. Number
1. ✔ Int

---
```javascript
var a = [1,2,3];
var b = [1,2,3]; 
var c = "1,2,3";

a == c; 
b == c; 
a == b;
```

1. NaN 
1. false, true, true 
1. ✔ true, true, false 
1. Undefined

---
What is the difference between `==` and `===`?

1. `==` sets values `===` only compares values
1. `===` sets values `==` compares values
1. ✔ `==` only compares values `===` compare values and type both
1. `===` only compares values `==` compare values and type both

---
What is the value of `b`?

```javascript
var a = "42";
var b = a * 1;
```

1. ✔ 42
1. NaN
1. "42"
1. error will be thrown

---
What will be the output for both comparisons?

```javascript
var a = 41;
var b = "42";
var c = "43";

console.log(a < b);
console.log(b < c);
```

1. ✔ `true`, `true`
1. `true`, `false`
1. `false`, `true`
1. `false`, `false`

---
```javascript
var arr = ["hello world", 42, true];
console.log(arr.length);
```

What will be the output of this code?

1. `["hello world", 42, true]`
1. undefined
1. ✔ 3
1. error will be thrown

---
Triple equality `===` is used when:

1. types are equal
1. ✔ both values and types are equal
1. when types should not be equal
1. values  are equal

---
Which expression is true?

1. `typeof {a:"Meow", b:666, "cat"} == 'object'` 
1. ✔ `typeof ["Meow", 666, "cat"] == 'object'` 
1. `typeof {"cat"} == 'object'` 
1. all statements are true

---
Which of the following statement are not true about javascript closures?

1. gives access to an outers f(x) scope from an inner f(x)
1. ✔ outer f(x) cannot access global variables
1. inner f2(x) will have access to outers f1(x) variables even after outer f1(x) has returned something
1. inner f(x) cannot access global variables

---
```javascript
function foo() {
  const a = 4;
  console.log(this.a);
}
var a = {
  a: 2
};
var b = {
  a: a,
  foo: foo,
  b: 'hello'
}
foo.call(b);
```

What is the output?

1. ✔ `{a:2}`
1. `hello`
1. `2`
1. `4`

---
Which of the following statements are false?

1. A block (identified by a pair of curly braces) does not define a new scope for `let` and `const`, but it does for `var`
2. A variable defined as `const` or `let` is also visible outside that block where it resides
3. A variable defined as `var` inside a function is visible in every part of program
1. ✔ All of the above

---
```javascript
a = 2
var a
console.log(a)
```

What's the expected output?

1. unidentified
1. null
1. ✔ 2
1. syntax error

---
What will be in the second output?

```javascript
var a = 2;
(function IIFE(def) {
    def(window);
})(function def(global) {
    var a = 3;
    console.log(a);
    console.log(global.a);
});
```

1. ✔ 2
1. 1
1. 3
1. Null

---
```javascript
{
  let a = 123;
};

console.log(a);
```

What is the output?

1. ✔ ReferenceError: a is not defined.
1. undefined
1. 123
1. null

---
Lexical scope: what is the output?

```javascript
function foo(a) {

	var b = a * 2;

	function bar(c) {
		console.log(a, b, c);
	}

	bar(b * 3);
}

foo(2); 
```

What is the output?

1. ✔ 2 4 12
1. Undefined
1. 2 4 6
1. 2 8 16

---
```javascript
a = "42";
b = 42;
c = a == b
console.log(c)
```

What will be printed out in console?

1. Undefined
1. NaN
1. false
1. ✔ true

---
When should you use `const` instead of `let` or `var`?

1. only on global scope!
1. ✔ when value shouldn’t change
1. only in For Loops
1. when the value is going to change

---
What is the result of the below code when the functions get called in the order as mentioned?

```javascript
var a = 5;
function first() {
    a = 6;
}

function second() {
    alert(a);
}
```

1. undefined
1. null
1. 5
1. ✔ 6

---
Which two mechanisms in JavaScript can "cheat" lexical scope?

1. ✔ eval(..) and with 
1. setTimeout(..) and with 
1. eval(..) and setTimeout(..) 
1. all answers are correct

---
```javascript
var strObject = new String("I am a string");
typeof strObject;
```

What is the expected output for typeof?

1. ✔ "object"
1. "instance"
1. "function"
1. "string"

---
What does the following code print to the console?

```javascript
var object = {
  foo: function() { return (this === object); }
}
console.log(object.foo());
```

1. ✔ true
1. false
1. undefined
1. ReferenceError: this is not defined

---
```javascript
class MyClass {
    constructor() {
        this.useless = "UMP"
    }
}
```

If you have this class what will happen if we execute this code?:

```javascript
MyClass.useless = "P90"
```

1. "UMP" string changes to "P90"
1. syntax error
1. creates a new variable in the object's instance
1. ✔ creates a new static variable in MyClass

---
What will be in the output and what kind of function method is this?

```javascript
var globalObject = this; 
var foo = (() => this); 
console.log(foo() === globalObject);
```

1. false, Simple call
1. true, The Bind Method
1. ✔ true, The Arrow Function
1. false, As an object method

---
What is `this`, in method?

1. this refers to the owner constructor
1. ✔ this refers to the owner object
1. this refers to the owner properties
1. this refers to the owner prototypes

---
```javascript
function foo(num) {
	console.log("foo: " + num);
	this.count++;
}

foo.count = 0;

var i;

for (i=0; i<10; i++) {
	if (i > 5) {
		foo(i);
	}
}

console.log(foo.count);
```

What is the output?

1. 9
1. Undefined
1. 4
1. ✔ 0

---
```javascript
var myObject = {};

Object.defineProperty(myObject, "a", {
	value: 2,
	writable: false,
	configurable: true,
	enumerable: true
});
```

How would you change newly created field value to 3?

1. `myObject.a = 3;`
1. `myObject.value = 3;`
1. ✔ it's not possible
1. `a.value = 3;`

---
What will be the output of this code?

```javascript
var myArray = ["foo", 42, "bar"];
myArray.baz = "baz";
console.log(myArray.length);
console.log(myArray.baz);
```

1. ✔ 
```
    3
    "baz"
 ```
1.
```
    4
    "baz"
```
1.
```
    3
    undefined
``` 
1.
```
    3
    error 
```

---
Which of these are the primary object types in JavaScript?
 
1. null, undefined, object
1. function
1. string, number, boolean
1. ✔ a and c

---
What will be the output?

```javascript
var obj = {x: 10, y: 20};
var obj2 = {x: 20};
var obj3 = Object.create(obj2)
console.log(obj3.y)
```

1. 20
1. ✔ undefined
1. Error
1. null

---
What is a constructor?

1. ✔ a special method of the class used to construct instances of classes
1. another name for programmer
1. ✔ a method of the class which initializes any information (state) the instance will need
1. a function that is called when a class property is read from or written to