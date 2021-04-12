# Objects and Arrays

1. Assignments with Dots

```
let person = {};
person.name = "Jane Doe";

let who = person.name;

let person = {
    "name" : "Jane Doe"
};

```

Anything that ever uses a dot in JavaScript is an object. 

Primitive value is a string, number, boolean etc. where a non-primitive value is an object or a promise

Primitive values get passed by value (gets it's own spot in memory every single time)
Non-primitive values get passed by reference, can create problems