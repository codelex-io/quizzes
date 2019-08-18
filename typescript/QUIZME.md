# TypeScript

---
```typescript
function buildName(firstName: string, lastName?: string) {
    if (lastName)
        return firstName + " " + lastName;
    else
        return firstName;
}
```

Which is the correct function call?

1. ✔ `let result1 = buildName("Bob");`  
1. `let result2 = buildName("Bob", "Adams", "Sr.");`  
1. ✔ `const result3 = buildName("Bob", "Adams");`  
1. ✔ `var result4 = buildName("Bob");`

---
```typescript
function buildName(firstName = "Will", lastName: string) {
    return firstName + " " + lastName;
}
```

Which function call would not result in error?

1. `let result1 = buildName("Bob");`
1. `let result2 = buildName("Bob", "Adams", "Sr.");`
1. ✔ `let result3 = buildName("Bob", "Adams");`
1. ✔ `let result4 = buildName(undefined, "Adams");`

---
Why is it important to assign data types to variables?

1. The code executes faster, but is a little more complex
1. ✔ So you dont make a mistake by accidentally adding a different data type to a variable
1. So the code looks more complex and you'll have bragging rights
1. So you make less syntax errors

---
Static typing is feature in: 

1. Javascript
1. ✔ Typescript
1. None
1. Both

---
What will be the output?

```typescript
enum Color {Red = 7, Green = 75 , Blue}
let colorName: Color = Color.Blue;

console.log(colorName);
```

What is the output?

1. undefined
1. 2
1. 9
1. ✔ 76

---
```markdown
`...` allows us to define a set of named constants. Using `...` can make it easier to document intent, or create a set of distinct cases. TypeScript provides both numeric and string-based `...`.
```

Choose the right missing words for empty space `...`!

1. ✔ Enums
1. Classes
1. Modules
1. Decorators

---
When it is applicable to use data type 'any'?

1. 'any' is not useful because you can only assign undefined or null to it
1. ✔ The any type is handy if you know some part of the type, but perhaps not all of it
1. You can use type 'any' whenever you like, it is very useful
1. ✔ When we need to describe the type of variables that we do not know when we are writing an application

---
What is the correct way of assigning integer type in TypeScript?

1. `let frenchFries: num = 30`
1. ✔ `let frenchFries: number = 30`
1. `let frenchFries: int = 30`
1. `let frenchFries: integer = 30`

---
Which of the scopes are available in TypeScript?

1. global scope
1. block scope
1. class scope
1. ✔ all of them

---
```typescript
class Animal {
    private name: string;
    constructor(theName: string) { this.name = theName; }
}

new Animal("Cat").name;
```

Why will this code throw an error? 

1. The private element means we simply cannot access it
1. ✔ We can’t access a private element outside it’s containing class 
1. "Cat" is not defined
1. We cannot use "private" inside a class

---
How would this expression be written using typescript?

```javascript
let a = [[1,2],[3,4]];
``` 

1. `let a: Array[] = [[1,2],[3,4]];` 
1. `let a: number[] = [[1,2],[3,4]];`  
1. ✔ `let a: number[][] = [[1,2],[3,4]];` 
1. `let a: Array[][] = [[1,2],[3,4]];`