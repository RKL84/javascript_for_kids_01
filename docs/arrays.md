## Arrays

#### What are arrays used for in programming?
Arrays are used to store a collection of values. They're like lists that keep things organized.

#### How can you create an array in JavaScript?
You create an array using square brackets `[]`. For example:
```javascript
let fruits = ["apple", "banana", "orange"];
```

How do you access elements in an array?
You access elements using their index. Arrays are zero-indexed, so the first element is at index 0. For example:

```javascript
let firstFruit = fruits[0];
```

Can you add or remove elements from an array?
Yes! You can add elements to the end of an array using the push method, and you can remove elements using the pop method.

What's the length property of an array?
The length property tells you how many elements are in an array. For example:

```javascript
let numFruits = fruits.length;
```

Can you provide an example of using an array?
Certainly! Here's an example that prints all the fruits in the array:

```javascript
for (let i = 0; i < fruits.length; i++) {
    console.log(fruits[i]);
}
```

#### Q & A:
Q: How are arrays useful in programming?

A: Arrays help you manage lists of data, such as names, numbers, or objects.

Q: What's the difference between an array and a variable?

A: A variable holds a single value, while an array holds multiple values.

Q: How do you add elements to an array?

A: You can use the push method to add elements to the end of an array.

**Challenges:**

1. Create an array of your favorite colors and print them one by one.
2. Write a program that finds the largest number in an array of numbers.