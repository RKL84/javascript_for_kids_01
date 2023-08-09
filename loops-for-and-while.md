## Loops (For and While)

#### What are loops used for in programming?
Loops help you repeat tasks without writing the same code over and over again. They're great for automating repetitive actions.

#### How does a `for` loop work?
A `for` loop has an initialization, a condition, and an update. It repeats as long as the condition is true. Here's the structure:
```javascript
for (initialization; condition; update) {
    // Code to repeat
}
```

Using for loops to repeat tasks
You can use for loops to count numbers, iterate over arrays, and perform actions a specific number of times.

Can you provide an example of using a for loop?
Certainly! Here's an example that counts from 1 to 5:


```javascript
for (let i = 1; i <= 5; i++) {
    console.log("Count: " + i);
}
```

How does a while loop work?
A while loop repeats as long as a condition is true. It doesn't require an initialization or an update. Here's the structure:

```javascript
while (condition) {
    // Code to repeat
}
```

Can you create a countdown timer using a while loop?
Certainly! Here's an example:

```javascript
let count = 10;
while (count >= 0) {
    console.log(count);
    count--;
}
```

#### Q & A:
Q: What's the benefit of using loops?

A: Loops help you automate repetitive tasks, saving time and reducing the need for redundant code.

Q: What's the difference between for and while loops?

A: for loops have an initialization, condition, and update. while loops rely on a condition.

Q: How can you use a loop in a real-world scenario?

A: A loop could be used to repeat a game level until the player succeeds or to process items in a shopping cart.

**Challenges:**

1. Write a program that calculates the factorial of a number using a for loop.
2. Create a guessing game where the user has to guess a secret number using a while loop.