# JS DOM

Created: Mar 30, 2021 2:00 PM

Add JS to HTML File

```html
<script src="index.js" charset="utf-8"></script>
```

Preferred Location:

==> Is at the bottom of the body tag

```html
<body>
    <h1>Hello</h1>

    <script src="index.js" charset="utf-8"></script> <!-- add JS file -->
</body>
```

## Document Object Model (DOM)

Dominating the DOM to add functionality to HTML elements

[Document Object Model (DOM)](https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model)

```jsx
document.firstElementChild.lastElementChild;
```

```jsx
document.firstElementChild.children[1].children[1];
```

![JS%20DOM%20b1c6367ba8ae4fc79f48a93095a028e6/Title_0_(2).png](JS%20DOM%20b1c6367ba8ae4fc79f48a93095a028e6/Title_0_(2).png)

```jsx
var heading = decoument.firstElementChiled.lastElementChild.firstElementChild;
// heading // call
heading.innerHTML = "Good Bye"; // change heading text from "Hello" to "God Bye"
heading.style.color = "red"; // change color from black to read
```

## Properties & Methods

![JS%20DOM%20b1c6367ba8ae4fc79f48a93095a028e6/2._Introduction_to_the_Document_Object_Model_(DOM).mp4_20210403_175100.547.jpg](JS%20DOM%20b1c6367ba8ae4fc79f48a93095a028e6/2._Introduction_to_the_Document_Object_Model_(DOM).mp4_20210403_175100.547.jpg)

![JS%20DOM%20b1c6367ba8ae4fc79f48a93095a028e6/2._Introduction_to_the_Document_Object_Model_(DOM).mp4_20210403_175214.538.jpg](JS%20DOM%20b1c6367ba8ae4fc79f48a93095a028e6/2._Introduction_to_the_Document_Object_Model_(DOM).mp4_20210403_175214.538.jpg)

![JS%20DOM%20b1c6367ba8ae4fc79f48a93095a028e6/2._Introduction_to_the_Document_Object_Model_(DOM).mp4_20210403_175221.321.jpg](JS%20DOM%20b1c6367ba8ae4fc79f48a93095a028e6/2._Introduction_to_the_Document_Object_Model_(DOM).mp4_20210403_175221.321.jpg)

![JS%20DOM%20b1c6367ba8ae4fc79f48a93095a028e6/2._Introduction_to_the_Document_Object_Model_(DOM).mp4_20210403_175511.794.jpg](JS%20DOM%20b1c6367ba8ae4fc79f48a93095a028e6/2._Introduction_to_the_Document_Object_Model_(DOM).mp4_20210403_175511.794.jpg)

Car start moving

![JS%20DOM%20b1c6367ba8ae4fc79f48a93095a028e6/2._Introduction_to_the_Document_Object_Model_(DOM).mp4_20210403_175556.650.jpg](JS%20DOM%20b1c6367ba8ae4fc79f48a93095a028e6/2._Introduction_to_the_Document_Object_Model_(DOM).mp4_20210403_175556.650.jpg)

- Methods and Functions

    [](https://www.codecademy.com/articles/fwd-js-methods-functions#:~:text=A%20method,%20like%20a%20function,while%20a%20function%20is%20not)

    ****Methods and Functions
    Use this article as a reference sheet for JavaScript methods and functions.**

    Use this article as a reference sheet for JavaScript methods and functions.

    - Function — a set of instructions that perform a task.
    - Method — a set of instructions that are associated with an object.

    ### **Functions**

    Functions are like recipes. They can execute a set of instructions on data or variables and return the result. The beauty of functions is that they are recyclable. That is, the function can be used repeatedly without having to write the same code again.

    ```
    // Define a function that prints a string
    function welcomeMessage() {
      console.log('Welcome to JavaScript');
    }
    // Call the function
    welcomeMessage();
    ```

    In the example above, the `welcomeMessage` function is used to display `Welcome to JavaScript` in the console. Let’s walk through this code step-by-step:

    - The `function` keyword indicates the start of a function.
    - The word that follows (`welcomeMessage`) is the *function’s name*.
    - The empty parentheses after `welcomeMessage` indicate that there are no *parameters*, or inputs, for the function.
    - The code between the opening (`{`) and closing (`}`) curly braces is a set of instructions. This code will only execute when the function is *called*.
    - To call a method, you need the function’s name, a pair of parentheses, and a semicolon. In this example, the function is called with `welcomeMessage();`.

    Let’s also consider a function that receives inputs and returns outputs:

    ```
    function concatName(firstName, middleName, lastName) {
      return firstName + ' ' + middleName + ' ' + lastName;
    }
    ```

    Let’s walk through this example step-by-step:

    1. The `concatName` function is created with three *parameters* (inputs): `firstName`, `middleName`, and `lastName`. Think of these as variables that have not been set yet.
    2. Inside of the function, the `return` keyword will *return* the concatenation of `firstName`, `middleName`, and `lastName`, with spaces in between each. The `return` keyword terminates the function it is within and returns a value — any code inside the function that comes after the `return` keyword will not be evaluated (nor executed, itself).
    3. You can save the returned string to a variable or log it to the console when you call the function. In the example above, the `concatName` function is called with the following arguments: `'George'`, `'Washington'`, and `'Carver'`. These values are saved into the variables `firstName`, `middleName`, and `lastName` inside of the function. The function returns a concatenation of these three strings — the `concatGWC` variable stores the returned concatenated string.

        ```
        var concatGWC = concatName('George', 'Washington', 'Carver');
        ```

    In this reference sheet we have used the words *parameters* and *arguments* to reference similar, but distinctly different elements of a function and function call. What’s the difference between these words?

    - Parameters are fields that serve as variable names inside of a function. In the example above, `firstName`, `middleName`, and `lastName` are parameters.
    - Arguments are the values passed to the function when it is called. In the example above, `'George'`, `'Washington'`, and `'Carver'` are arguments.

    ### **Methods**

    A method, like a function, is a set of instructions that perform a task. The difference is that a method is associated with an object, while a function is not. Let’s explore some of JavaScript’s built-in methods.

    ```
    var str = 'CodeCADEMY';
    var str1 = str.toLowerCase();
    var str2 = str.toUpperCase();
    ```

    The variable `str` in the example above stores the string ‘CodeCADEMY’. The `.toLowerCase()` and `.toUpperCase()` methods in the example above are called on `str`. Let’s talk through each line:

    - On the second line, the `.toLowerCase()` method is called on the `str` variable, which returns the lowercase string `'codecademy'`.
    - On the third line, the `.toUpperCase()` method is called on the `str` variable, which returns the uppercase string `'CODECADEMY'`. Notice, periods are used to call a method on an object, as in `str.toLowerCase();`.

```jsx
document.getElementsByTagName("li"); 
// get list of elements that has the tag "li" 
// ? "li" for lis
document.getElementsByTagName("li").length; // ==> 3 
// the output is array you can't set a property for it
document.getElementsByTagName("li")[2].style.color="purple";
// spasific element selected from the aray 
```

```jsx
document.getElementsByClassName("btn");
// aray outbut
document.getElementsById("title");
// one element output -- ID is uniqe for every element  
// to change
document.getElementsById("title").innerHTML = "Good Bye";
```

```jsx
document.querySelector("h1");
document.querySelector("#title");
document.querySelector(".btn");
document.querySelector("li a");
document.querySelector("a");
document.querySelector("li.item");
// the same selector as CSS
```

When using `querySelector` for more than one object, you will only get the first object for getting all

objects we use `querySelectorAll`

```jsx
document.querySelectorAll("#list .item");
// to select speacific item 
document.querySelectorAll("#list .item")[2];
document.querySelectorAll("#list .item")[2].style.color = "blue";
```

## HTML DOM Style Object

[HTML DOM Style object](https://www.w3schools.com/jsref/dom_obj_style.asp)

```jsx
document.querySelector("button").style.backgroundColor = "yellow";
```

add / remove class using JS

```jsx
document.querySelector("button").classList.add("invisible"); // add
document.querySelector("button").classList.remove("invisible"); // remove 
document.querySelector("button").classList.toggle("invisible"); // reverse the current case
```

We don't use JS to change the style of elements, so it's preferred to add/remove class instead and keep all the style on the style sheet.

HTML ==⇒ content

CSS ==⇒ style

JS ==⇒ behavior

## Example:

```jsx
<p id="demo">   This element has extra spacing     and contains <span>a span element</span>.</p>

<script>
function getInnerText() {
  alert(document.getElementById("demo").innerText)
}

function getHTML() {
  alert(document.getElementById("demo").innerHTML)
}

function getTextContent() {
  alert(document.getElementById("demo").textContent)
}
</script>
```

### Get the content of the <p> element above with the specified properties:

- **innerText** returns: "This element has extra spacing and contains a span element."
- **innerHTML** returns: "   This element has extra spacing     and contains <span>a span element</span>."
- **textContent** returns: "   This element has extra spacing    and contains a span element."
- The **innerText** property returns just the text, without spacing and inner element tags.
- The **innerHTML** property returns the text, including all spacing and inner element tags.
- The **textContent** property returns the text with spacing, but without inner element tags.

## Change Attribute:

```jsx
document.querySelector("a").getAttribute("href");
// www.google.com
// to change it
document.querySelector("a").setAttribute("href", "https://www.bing.com")
```