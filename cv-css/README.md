# CSS

# Code Notes

---

CSS - Cascading Style Sheets

change background

```html
<body style="background-color: cadetblue;">

<!-- Another way -->

<head>
  <meta charset="utf-8" />
  <title>Omar's Resume</title>
  <style>
    body {
      background-color: #EAF6F6;
    }
  </style>
</head>
```

Horizontal Line Style

```css
hr{
      background-color: white;

      /* border-style: dotted none none; */

      /* Another way */

      border-style: none;
      border-top-style: dotted;
      
      height: 0;
      width: 30%;
    }
```

The `border-style` property may be specified using one, two, three, or four values.

- When **one** value is specified, it applies the same style to **all four sides**.
- When **two** values are specified, the first style applies to the **top and bottom**, the second to the **left and right**.
- When **three** values are specified, the first style applies to the **top**, the second to the **left and right**, the third to the **bottom**.
- When **four** values are specified, the styles apply to the **top**, **right**, **bottom**, and **left** in that order (clockwise).

Each value is a keyword chosen from the list below.

```css
hr{
      border-style: none;
      border-top-style: dotted;
      border-color: gray;
      border-width: 5px;
      height: 0;
      width: 30%;
    }
```

But CSS code on separate file and link it

```html
<head>
  <meta charset="utf-8" />
  <title>Omar's Resume</title>
	<!-- * * Link Line * * -->
  <link rel="stylesheet" href="CSS/styles.css">
</head>
```

For "cellspacing", you can apply the border-spacing CSS property to your table. E.g. for 10px of "cellspacing":

```css
table { 
    border-spacing: 10px;
    border-collapse: separate;
}
```

# Text Color

The `color` property is used to set the color of the text. The color is specified by:

- a color name - like "red"
- a HEX value - like "#ff0000"
- an RGB value - like "rgb(255,0,0)"

Look at [CSS Color Values](https://www.w3schools.com/cssref/css_colors_legal.asp) for a complete list of possible color values.

The default text color for a page is defined in the body selector.

```css
body {
  color: blue;
}

h1 {
  color: green;
}
```

CSS syntax explain

![CSS%20eb173105ba7a4a6b97d447b7c5c58029/vlcsnap-2021-01-25-11h54m52s773.png](CSS%20eb173105ba7a4a6b97d447b7c5c58029/vlcsnap-2021-01-25-11h54m52s773.png)

---

> The CSS class selector matches elements based on the contents of their class attribute.

## CSS

```css
.red {
  color: #f33;
}

.yellow-bg {
  background: #ffa;
}

.fancy {
  font-weight: bold;
  text-shadow: 4px 4px 3px #77f;
}
```

## HTML

```html
<p class="red">This paragraph has red text.</p>
<p class="red yellow-bg">This paragraph has red text and a yellow background.</p>
<p class="red fancy">This paragraph has red text and "fancy" styling.</p>
<p>This is just a regular paragraph.</p>
```

## Result

![CSS%20eb173105ba7a4a6b97d447b7c5c58029/Screenshot_2021-01-25_132706.png](CSS%20eb173105ba7a4a6b97d447b7c5c58029/Screenshot_2021-01-25_132706.png)

> The CSS ID selector matches an element based on the value of the element’s id attribute. In order for the element to be selected, its id attribute must match exactly the value given in the selector.

### CSS

```css
#identified {
  background-color: skyblue;
}
```

### HTML

```html
<div id="identified">This div has a special ID on it!</div>
<div>This is just a regular div.</div>
```

### Result

![CSS%20eb173105ba7a4a6b97d447b7c5c58029/Screenshot_2021-01-25_134847.png](CSS%20eb173105ba7a4a6b97d447b7c5c58029/Screenshot_2021-01-25_134847.png)

---

# Note ID VS Class

## ID’s are unique

- Each element can have only one ID
- Each page can have only one element with that ID

## Classes are not unique

- You can use the same class on multiple elements.
- You can use multiple classes on the same element.

---

A CSS **[pseudo-class](https://developer.mozilla.org/en-US/docs/Web/CSS/Pseudo-classes)** is a keyword added to a selector that specifies a special state of the selected element(s). For example, :hover can be used to change a button's color when the user's pointer hovers over it.

```css
/* Any button over which the user's pointer is hovering */
button:hover {
  color: blue;
}
```

# Resources

---

[CSS: Cascading Style Sheets](https://developer.mozilla.org/en-US/docs/Web/CSS)

## CSS reference =⇒ What

[CSS reference](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference)