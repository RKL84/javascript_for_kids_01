## Callbacks and Asynchronous Programming

#### What's the purpose of callbacks in JavaScript?
Callbacks are functions passed as arguments to other functions. They're used to handle asynchronous actions and events.

#### How do you use `setTimeout` for delayed actions?
You can use `setTimeout` to delay an action by a specified amount of time. For example:
```javascript
setTimeout(function() {
    console.log("Delayed message!");
}, 3000); // Delayed by 3 seconds
```

Handling asynchronous actions with callbacks
Callbacks are often used to handle events that might take time, like data fetching or animations.

How can you provide a callback function to another function?
You pass the callback function as an argument to the function that's going to call it. For example:

```javascript

function fetchData(callback) {
    // Simulate fetching data
    let data = "Server data";
    callback(data);
}

fetchData(function(data) {
    console.log("Received:", data);
});
```

What's the benefit of asynchronous programming?
Asynchronous programming allows your program to continue running while waiting for tasks like data fetching to complete.

#### Q & A:
Q: What's the role of callbacks in asynchronous programming?

A: Callbacks are used to handle tasks that might take time, allowing the program to continue running without waiting.

Q: How does setTimeout help in asynchronous programming?

A: setTimeout is used to delay a task, making it useful for creating timed events and animations.

Q: Can you provide an example of a real-world situation that uses callbacks?

A: Callbacks are commonly used in handling user interactions, like button clicks, to trigger actions.

**Challenges:**

1. Write a program that uses a callback to simulate an online order process.
2. Create a simple animation using setTimeout to move an element across the screen.