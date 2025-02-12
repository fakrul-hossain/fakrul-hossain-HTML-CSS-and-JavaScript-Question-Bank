
# Backpack of HTML, CSS, and JS Questions
Here is the complete HTML, CSS, and JavaScript Question Bank:
---

## **Part 1: HTML (20 Questions)**

### **1. Semantic Tags (4 Questions)**

1. **What are semantic tags in HTML?**  
   Semantic tags are HTML elements that clearly describe their meaning to both the browser and the developer. Examples include `<header>`, `<footer>`, `<article>`, and `<section>`.
   **Example:**  
   ```
   <header>This is a header</header>
   <main>This is the main content</main>
   <footer>This is a footer</footer>
   ```

2. **Why are semantic tags important?**  
   Semantic tags improve accessibility, SEO, and make the code easier to read and maintain by providing meaning to the structure of the webpage.

   **Example:**  
   ```html
   <article>
       <h1>Article Title</h1>
       <p>This is an article about semantic tags.</p>
   </article>
   ```

3. **What is the difference between `<div>` and `<section>`?**  
   `<div>` is a non-semantic container, while `<section>` is a semantic tag used to define a thematic grouping of content.

   **Example:**  
   ```html
   <div>This is a non-semantic container</div>
   <section>This is a thematic grouping of content</section>
   ```

4. **Name three semantic tags and their purposes.**  
   `<header>`: Represents the introductory content or navigation links.  
   `<main>`: Represents the main content of the document.  
   `<footer>`: Represents the footer of a section or page, typically containing authorship or copyright information.

   **Example:**  
   ```html
   <header>Header Content</header>
   <main>Main Content</main>
   <footer>Footer Content</footer>
   ```

---

### **2. Attributes (4 Questions)**

5. **What is the purpose of the `alt` attribute in the `<img>` tag?**  
   The `alt` attribute provides alternative text for an image if it cannot be displayed, improving accessibility and SEO.

   **Example:**  
   ```html
   <img src="image.jpg" alt="A description of the image">
   ```

6. **What is the difference between `id` and `class` attributes?**  
   `id` is unique and can be used to identify a single element, while `class` can be applied to multiple elements to group them for styling or scripting.

   **Example:**  
   ```html
   <div id="uniqueElement">Unique Element</div>
   <div class="commonClass">Common Element 1</div>
   <div class="commonClass">Common Element 2</div>
   ```

7. **What does the `href` attribute do in the `<a>` tag?**  
   The `href` attribute specifies the URL of the page the link goes to.

   **Example:**  
   ```html
   <a href="https://example.com">Visit Example</a>
   ```

8. **What is the purpose of the `target` attribute in the `<a>` tag?**  
   The `target` attribute specifies where to open the linked document, e.g., `_blank` opens the link in a new tab.

   **Example:**  
   ```html
   <a href="https://example.com" target="_blank">Open in New Tab</a>
   ```

---

### **3. HTML Elements (4 Questions)**

9. **What is the difference between `<ul>` and `<ol>`?**  
   `<ul>` is used for unordered lists (bulleted), while `<ol>` is used for ordered lists (numbered).

   **Example:**  
   ```html
   <ul>
       <li>Item 1</li>
       <li>Item 2</li>
   </ul>
   <ol>
       <li>First Item</li>
       <li>Second Item</li>
   </ol>
   ```

10. **What is the purpose of the `<br>` tag?**  
    The `<br>` tag inserts a line break in the text.

    **Example:**  
    ```html
    <p>This is the first line.<br>This is the second line.</p>
    ```

11. **What is the difference between `<b>` and `<strong>` tags?**  
    `<b>` is used to make text bold without implying importance, while `<strong>` indicates that the text is of strong importance.

    **Example:**  
    ```html
    <b>This text is bold.</b>
    <strong>This text is important.</strong>
    ```

12. **What does the `<iframe>` tag do?**  
    The `<iframe>` tag embeds another HTML page within the current page.

    **Example:**  
    ```html
    <iframe src="https://example.com" width="300" height="200"></iframe>
    ```

---

### **4. Forms and Inputs (4 Questions)**

13. **What is the purpose of the `<form>` tag?**  
    The `<form>` tag is used to create an HTML form for user input.

    **Example:**  
    ```html
    <form action="/submit" method="post">
        <input type="text" name="username">
        <input type="submit" value="Submit">
    </form>
    ```

14. **What is the difference between `GET` and `POST` methods in forms?**  
    `GET` appends form data to the URL, while `POST` sends data in the request body, making it more secure for sensitive information.

    **Example:**  
    ```html
    <form action="/submit" method="get">
        <input type="text" name="search">
        <input type="submit" value="Search">
    </form>
    ```

15. **What is the purpose of the `<label>` tag?**  
    The `<label>` tag defines a label for an `<input>` element, improving accessibility.

    **Example:**  
    ```html
    <label for="username">Username:</label>
    <input type="text" id="username" name="username">
    ```

16. **What does the `required` attribute do in an input field?**  
    The `required` attribute ensures that the input field must be filled out before submitting the form.

    **Example:**  
    ```html
    <input type="text" name="username" required>
    ```

---

### **5. Media (4 Questions)**

17. **What is the purpose of the `<audio>` tag?**  
    The `<audio>` tag is used to embed sound content in a document.

    **Example:**  
    ```html
    <audio controls>
        <source src="audio.mp3" type="audio/mpeg">
        Your browser does not support the audio element.
    </audio>
    ```

18. **What is the difference between `<img>` and `<picture>` tags?**  
    `<img>` is used to embed a single image, while `<picture>` allows for multiple sources of images to be displayed based on device conditions.

    **Example:**  
    ```html
    <picture>
        <source srcset="image-large.jpg" media="(min-width: 800px)">
        <img src="image-small.jpg" alt="Example Image">
    </picture>
    ```

19. **What does the `controls` attribute do in the `<video>` tag?**  
    The `controls` attribute adds play, pause, and volume controls to the video.

    **Example:**  
    ```html
    <video controls>
        <source src="video.mp4" type="video/mp4">
        Your browser does not support the video element.
    </video>
    ```

20. **How do you embed a YouTube video in HTML?**  
    Use an `<iframe>` with the YouTube video URL as the `src` attribute.

    **Example:**  
    ```html
    <iframe width="560" height="315" src="https://www.youtube.com/embed/dQw4w9WgXcQ" frameborder="0" allowfullscreen></iframe>
    ```

---

## **Part 2: CSS (15 Questions)**

### **1. Selectors (3 Questions)**

21. **What is the difference between `#id` and `.class` selectors?**  
    `#id` selects an element by its unique `id`, while `.class` selects all elements with the specified class.

    **Example:**  
    ```css
    #uniqueElement { color: red; }
    .commonClass { color: blue; }
    ```

22. **What is the purpose of the `*` selector in CSS?**  
    The `*` selector selects all elements in the document.

    **Example:**  
    ```css
    * { margin: 0; padding: 0; }
    ```

23. **What is the difference between `div p` and `div > p` selectors?**  
    `div p` selects all `<p>` elements inside a `<div>`, while `div > p` selects only direct child `<p>` elements of a `<div>`.

    **Example:**  
    ```css
    div p { color: green; }
    div > p { color: purple; }
    ```

---

### **2. Box Model (3 Questions)**

24. **What are the components of the CSS box model?**  
    The box model consists of content, padding, border, and margin.

    **Example:**  
    ```css
    div {
        width: 200px;
        padding: 10px;
        border: 5px solid black;
        margin: 20px;
    }
    ```

25. **What is the difference between `margin` and `padding`?**  
    `margin` is the space outside the border, while `padding` is the space inside the border, around the content.

    **Example:**  
    ```css
    div {
        margin: 10px;
        padding: 15px;
    }
    ```

26. **How do you center a `div` horizontally using CSS?**  
    Use `margin: 0 auto;` and set a fixed width for the `div`.

    **Example:**  
    ```css
    div {
        width: 50%;
        margin: 0 auto;
    }
    ```

---

### **3. Positioning and Layout (3 Questions)**

27. **What is the difference between `position: absolute` and `position: relative`?**  
    `position: relative` positions an element relative to its normal position, while `position: absolute` positions it relative to the nearest positioned ancestor.

    **Example:**  
    ```css
    .relative { position: relative; top: 10px; }
    .absolute { position: absolute; top: 20px; left: 30px; }
    ```

28. **What does `z-index` do in CSS?**  
    `z-index` controls the stacking order of elements, with higher values appearing in front of lower values.

    **Example:**  
    ```css
    .box1 { z-index: 1; }
    .box2 { z-index: 2; }
    ```

29. **How do you create a sticky header in CSS?**  
    Use `position: sticky; top: 0;` on the header element.

    **Example:**  
    ```css
    header {
        position: sticky;
        top: 0;
        background-color: white;
    }
    ```

---

### **4. Responsive Design (3 Questions)**

30. **What is a media query in CSS?**  
    A media query applies styles based on the device's characteristics, such as screen width.

    **Example:**  
    ```css
    @media (max-width: 600px) {
        body { background-color: lightblue; }
    }
    ```

31. **What is the purpose of the `viewport` meta tag?**  
    The `viewport` meta tag controls the layout on mobile browsers, ensuring proper scaling.

    **Example:**  
    ```html
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    ```

32. **How do you make images responsive in CSS?**  
    Use `max-width: 100%; height: auto;` on the image.

    **Example:**  
    ```css
    img {
        max-width: 100%;
        height: auto;
    }
    ```

---

### **5. Styling (3 Questions)**

33. **What is the difference between `em` and `rem` units?**  
    `em` is relative to the font size of the parent element, while `rem` is relative to the root element's font size.

    **Example:**  
    ```css
    .emExample { font-size: 2em; }
    .remExample { font-size: 2rem; }
    ```

34. **How do you apply a gradient background in CSS?**  
    Use `background: linear-gradient(direction, color1, color2);`.

    **Example:**  
    ```css
    div {
        background: linear-gradient(to right, red, yellow);
    }
    ```

35. **What is the purpose of the `box-shadow` property?**  
    The `box-shadow` property adds shadow effects around an element's frame.

    **Example:**  
    ```css
    div {
        box-shadow: 5px 5px 10px rgba(0, 0, 0, 0.5);
    }
    ```

---

## **Part 3: JavaScript (25 Questions)**

### **1. DOM Manipulation (5 Questions)**

36. **What is the DOM?**  
    The DOM (Document Object Model) is a programming interface for HTML and XML documents, representing the structure of a document as a tree of objects.

    **Example:**  
    ```javascript
    document.getElementById("demo").innerHTML = "Hello, World!";
    ```

37. **How do you select an element by its ID in JavaScript?**  
    Use `document.getElementById('id')`.

    **Example:**  
    ```javascript
    let element = document.getElementById("myElement");
    ```

38. **What is the difference between `innerHTML` and `textContent`?**  
    `innerHTML` returns the HTML content of an element, while `textContent` returns only the text content.

    **Example:**  
    ```javascript
    document.getElementById("demo").innerHTML = "<b>Hello</b>";
    document.getElementById("demo").textContent = "<b>Hello</b>";
    ```

39. **How do you add a class to an element using JavaScript?**  
    Use `element.classList.add('className')`.

    **Example:**  
    ```javascript
    document.getElementById("myElement").classList.add("newClass");
    ```

40. **What is event delegation?**  
    Event delegation is a technique where a single event listener is added to a parent element to handle events for its child elements.

    **Example:**  
    ```javascript
    document.getElementById("parent").addEventListener("click", function(event) {
        if (event.target.tagName === "LI") {
            console.log("List item clicked!");
        }
    });
    ```

---

### **2. Control Flow (5 Questions)**

41. **What is the difference between `==` and `===` in JavaScript?**  
    `==` checks for equality with type coercion, while `===` checks for strict equality without type coercion.

    **Example:**  
    ```javascript
    console.log(5 == "5");  // true
    console.log(5 === "5"); // false
    ```

42. **What is a ternary operator?**  
    The ternary operator is a shorthand for an `if-else` statement, written as `condition ? expr1 : expr2`.

    **Example:**  
    ```javascript
    let result = (age >= 18) ? "Adult" : "Minor";
    ```

43. **What is the purpose of the `switch` statement?**  
    The `switch` statement is used to perform different actions based on different conditions.

    **Example:**  
    ```javascript
    switch (day) {
        case "Monday":
            console.log("Start of the week");
            break;
        case "Friday":
            console.log("End of the week");
            break;
        default:
            console.log("Midweek");
    }
    ```

44. **What is the difference between `let` and `var`?**  
    `let` is block-scoped, while `var` is function-scoped.

    **Example:**  
    ```javascript
    if (true) {
        let x = 10;
        var y = 20;
    }
    console.log(y); // 20
    console.log(x); // Error: x is not defined
    ```

45. **What is a `for...of` loop?**  
    The `for...of` loop iterates over iterable objects like arrays, strings, etc.

    **Example:**  
    ```javascript
    for (let value of [1, 2, 3]) {
        console.log(value);
    }
    ```

---

### **3. ES6 Features (8 Questions)**

46. **What is the difference between `let` and `const`?**  
    `let` allows reassignment, while `const` does not.

    **Example:**  
    ```javascript
    let x = 10;
    x = 20; // Valid
    const y = 30;
    y = 40; // Error
    ```

47. **What are arrow functions?**  
    Arrow functions are a shorter syntax for writing functions and do not have their own `this` context.

    **Example:**  
    ```javascript
    const add = (a, b) => a + b;
    ```

48. **What is template literals in ES6?**  
    Template literals allow embedding expressions in strings using backticks (`) and `${}`.

    **Example:**  
    ```javascript
    let name = "John";
    console.log(`Hello, ${name}!`);
    ```

49. **What is destructuring in JavaScript?**  
    Destructuring allows extracting values from arrays or objects into distinct variables.

    **Example:**  
    ```javascript
    const [a, b] = [1, 2];
    const { name, age } = { name: "John", age: 30 };
    ```

50. **What is the spread operator?**  
    The spread operator (`...`) expands an iterable into individual elements.

    **Example:**  
    ```javascript
    const arr1 = [1, 2, 3];
    const arr2 = [...arr1, 4, 5];
    ```

51. **What is a default parameter in a function?**  
    Default parameters allow setting default values for function parameters if no value is provided.

    **Example:**  
    ```javascript
    function greet(name = "Guest") {
        console.log(`Hello, ${name}!`);
    }
    ```

52. **What is a Promise in JavaScript?**  
    A Promise represents a value that may be available now, in the future, or never, and is used for asynchronous operations.

    **Example:**  
    ```javascript
    const promise = new Promise((resolve, reject) => {
        setTimeout(() => resolve("Success!"), 1000);
    });
    promise.then(result => console.log(result));
    ```

53. **What are modules in ES6?**  
    Modules allow splitting code into separate files and exporting/importing functionality using `export` and `import`.

    **Example:**  
    ```javascript
    // math.js
    export const add = (a, b) => a + b;

    // main.js
    import { add } from './math.js';
    console.log(add(2, 3));
    ```

---

### **4. APIs (7 Questions)**

54. **What is an API?**  
    An API (Application Programming Interface) is a set of rules and protocols for building and interacting with software applications.

    **Example:**  
    ```javascript
    fetch('https://api.example.com/data')
        .then(response => response.json())
        .then(data => console.log(data));
    ```

55. **What is the Fetch API?**  
    The Fetch API provides a modern way to make network requests and handle responses.

    **Example:**  
    ```javascript
    fetch('https://jsonplaceholder.typicode.com/posts')
        .then(response => response.json())
        .then(data => console.log(data));
    ```

56. **What is the difference between `GET` and `POST` requests?**  
    `GET` retrieves data from a server, while `POST` sends data to a server to create or update a resource.

    **Example:**  
    ```javascript
    fetch('https://api.example.com/data', {
        method: 'POST',
        body: JSON.stringify({ key: 'value' })
    });
    ```

57. **What is JSON?**  
    JSON (JavaScript Object Notation) is a lightweight data interchange format used to transmit data between a server and a web application.

    **Example:**  
    ```javascript
    const jsonData = '{"name": "John", "age": 30}';
    const obj = JSON.parse(jsonData);
    console.log(obj.name); // John
    ```

58. **How do you handle errors in Fetch API?**  
    Use `.catch()` or check the `response.ok` property to handle errors.

    **Example:**  
    ```javascript
    fetch('https://api.example.com/data')
        .then(response => {
            if (!response.ok) throw new Error('Network response was not ok');
            return response.json();
        })
        .catch(error => console.error('Error:', error));
    ```

59. **What is CORS?**  
    CORS (Cross-Origin Resource Sharing) is a security feature that allows or restricts web pages from making requests to a different domain.

    **Example:**  
    ```javascript
    fetch('https://api.example.com/data', {
        method: 'GET',
        mode: 'cors'
    });
    ```

60. **What is the purpose of `localStorage`?**  
    `localStorage` allows storing data in the browser with no expiration time, persisting even after the browser is closed.

    **Example:**  
    ```javascript
    localStorage.setItem('name', 'John');
    console.log(localStorage.getItem('name')); // John
    ```

---
**Create by [Fakrul-Hossain](https://github.com/fakrul-hossain).



