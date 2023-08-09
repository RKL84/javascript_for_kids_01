## Event Handling (Click)

#### What are events in JavaScript?
Events are things that happen on a web page, such as a button being clicked, the mouse moving, or a key being pressed.

#### How can you respond to a button click event?
You can add an event listener to a button element. When the button is clicked, the code inside the event listener is executed.

#### Adding event listeners to elements
To add an event listener, you use the `addEventListener` method. Here's an example that changes text when a button is clicked:
```javascript
let button = document.getElementById("myButton");
button.addEventListener("click", function() {
    button.textContent = "Clicked!";
});
```


What's an example of using event handling for a click?
Here's an example that changes the color of a box when it's clicked:

```html
<!DOCTYPE html>
<html>
<head>
    <style>
        .box {
            width: 100px;
            height: 100px;
            background-color: red;
        }
    </style>
</head>
<body>

<div class="box" id="myBox"></div>

<script>
    let box = document.getElementById("myBox");
    box.addEventListener("click", function() {
        box.style.backgroundColor = "blue";
    });
</script>

</body>
</html>
```

#### Q & A:
Q: How do events make websites interactive?

A: Events allow users to interact with web pages, triggering actions like button clicks and form submissions.

Q: How do you respond to a button click event?

A: You add an event listener to the button and define the code to execute when the event occurs.

Q: Can events be used to control animations on a website?

A: Yes, events can trigger animations, like changing colors or moving elements, to make a website more engaging.

**Challenges:**

1. Create a program that changes the text of a paragraph when a button is clicked.
2. Build a simple drawing app that changes the color of a canvas when clicked.
