## DOM Manipulation

#### What is the DOM (Document Object Model)?
The DOM is like a tree that represents the structure of a web page. Each element is a node in the tree, and you can interact with them using JavaScript.

#### How can you select and manipulate HTML elements using JavaScript?
JavaScript can be used to select elements by their IDs, classes, or other attributes. Once selected, you can change their properties, styles, and content.

#### Selecting and manipulating HTML elements
You can select elements using methods like `getElementById`, `getElementsByClassName`, or `querySelector`. Here's an example that changes the text of a paragraph:
```javascript
let paragraph = document.getElementById("myParagraph");
paragraph.textContent = "New text!";
```

How can you update the style of an HTML element?
You can update the style of an element using its style property. For example:

```javascript
let heading = document.querySelector("h1");
heading.style.color = "blue";
```

Can you provide an example of updating an image source using JavaScript?
Certainly! Here's an example that changes the image source when a button is clicked:

```html
<!DOCTYPE html>
<html>
<head>
</head>
<body>

<img src="default.jpg" id="myImage">
<button id="changeButton">Change Image</button>

<script>
    let image = document.getElementById("myImage");
    let button = document.getElementById("changeButton");

    button.addEventListener("click", function() {
        image.src = "newimage.jpg";
    });
</script>

</body>
</html>
```

#### Q & A:
Q: How does the DOM structure relate to a web page?

A: The DOM represents the hierarchical structure of elements on a web page, allowing you to access and modify them with code.

Q: What's the purpose of selecting and manipulating DOM elements?

A: Selecting and manipulating elements with JavaScript lets you create dynamic and interactive web pages.

Q: Can you use JavaScript to change the content of a paragraph?

A: Yes, you can change the content using the textContent property or even the innerHTML property.

**Challenges:**

1. Build a program that changes the background color of a webpage using a button.
2. Create a simple to-do list where items are added when a button is clicked.

