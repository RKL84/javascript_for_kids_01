## Objects

#### What are objects used for in programming?
Objects are like containers that can hold different types of data related to a single thing. They're used to represent more complex structures.

#### How can you create an object in JavaScript?
You create an object using curly braces `{}`. For example:
```javascript
let person = {
    name: "Alice",
    age: 8
};
```


How do you access properties of an object?
You use dot notation to access properties of an object. For example:

```javascript
let personName = person.name;
```

Can you add or update properties in an object?
Yes! You can add new properties to an object or update existing ones using assignment. For example:

```javascript
person.gender = "female";
```

What's the purpose of objects with functions (methods)?
Objects can also contain functions, which are called methods. Methods help you bundle related actions together.

Can you provide an example of using an object?
Certainly! Here's an example of an object representing a book:

```javascript
let book = {
    title: "Harry Potter",
    author: "J.K. Rowling",
    pages: 332,
    isOpen: false,
    open: function() {
        this.isOpen = true;
    },
    close: function() {
        this.isOpen = false;
    }
};
```

#### Q & A:
Q: How do objects help in representing real-world things?

A: Objects allow you to store properties and behaviors of a single entity, making your code more organized.

Q: What's the difference between an object and an array?

A: An array is a list of values, while an object contains key-value pairs that represent properties.

Q: How do you access a method of an object?

A: You use dot notation to access methods of an object, just like accessing properties.

**Challenges:**

1. Create an object representing your favorite animal with properties like name, type, and age.
2. Write a program that uses an object method to turn on and off a lamp.