# CSS - 2 - updated

CSS Part 2 Notes

---

The HTML Content Division element **(<[div](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/div)>)** is the generic container for flow content. It has no effect on the content or layout until styled in some way using **[CSS](https://developer.mozilla.org/en-US/docs/Glossary/CSS)** (e.g. styling is directly applied to it, or some kind of layout model like [Flexbox](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout) is applied to its parent element).

HTML

```html
<div class="warning">
    <img src="/media/examples/leopard.jpg"
         alt="An intimidating leopard.">
    <p>Beware of the leopard</p>
</div>
```

CSS

```css
.warning {
    border: 10px ridge #f00;
    background-color: #ff0;
    padding: .5rem;
    display: flex;
    flex-direction: column;
}

.warning img {
    width: 100%;
}

.warning p {
    font: small-caps bold 1.2rem sans-serif;
    text-align: center;
}
```

Result

![CSS%20-%202%20e3eb73122a4d4129857970128dc1e197/Screenshot_2021-01-26_130114.png](CSS%20-%202%20e3eb73122a4d4129857970128dc1e197/Screenshot_2021-01-26_130114.png)

---

The **HTML <span>** element is a generic inline container for phrasing content, which does not inherently represent anything. It can be used to group elements for styling purposes (using the class or id attributes), or because they share attribute values, such as lang. It should be used only when no other semantic element is appropriate. <span> is very much like a <div> element, but <div> is a block-level element whereas a <span> is an inline element.

```html
<p>Add the <span class="ingredient">basil</span>, 
<span class="ingredient">pine nuts</span> 
and 
<span class="ingredient">garlic</span> to a blender and blend into a paste.</p>
```

```css
span.ingredient {
    color: #f00;
}
```

> Add the basil, pine nuts and garlic to a blender and blend into a paste.

---

## CSS display Property

[CSS display property](https://www.w3schools.com/cssref/pr_class_display.asp)

```css
p.ex1 {display: none;}
p.ex2 {display: inline;}
p.ex3 {display: block;}
p.ex4 {display: inline-block;}
```

[Property Values](https://www.notion.so/952080341f5849a8a3f7908b3502d97d)

[Is element block level or inline level?](https://stackoverflow.com/questions/2402761/is-img-element-block-level-or-inline-level)

## CSS Layout - The position Property

[CSS Layout - The position Property](https://www.w3schools.com/css/css_positioning.asp)

```css
div.static {
  position: static;
  border: 3px solid #73AD21;
}
```

The `position` property specifies the type of positioning method used for an element.

There are five different position values:

[position property](https://www.notion.so/a172c635002c44cc8ad06c5e9cbc95cb)

`text-align: center;` will center all elements inside the body except elements with specified width

we can center fixed width element by using `auto` value

```css
body{
    background-color: #111111;
    margin: 0;
    text-align: center;
}

h1{
    width: 10%;
    margin: 0 auto 0 auto;
}
```

change font :

[CSS Web Safe Fonts](https://www.w3schools.com/cssref/css_websafe_fonts.asp)

add font to website to load with the site cash

```html
<link href="https://fonts.googleapis.com/css2?family=Merriweather:wght@300&family=Montserrat:wght@500&family=Sacramento&display=swap" rel="stylesheet">
```

[Google Fonts](https://fonts.google.com/specimen/Merriweather?preview.text_type=custom&selection.family=Merriweather:wght@300%7CMontserrat:wght@500%7CSacramento&query=Merriweather&sidebar.open=true)

Select the font and backup font on CSS

```css
font-family: 'Merriweather', serif;
```

---

## Icons and Gif site

[Flaticon, the largest database of free vector icons](https://www.flaticon.com)

[GIPHY | Search All the GIFs & Make Your Own Animated GIF](https://giphy.com)

---

Font Size

```css
h1{
	font-size: 100px; /* fixed size */
	font-size: 562.2%; /* dinamic - 100% == 16px so if i want 90px = 90/16 = 56% */
	font-size: 562.2em; /* 1em = 16px = 100% */
	font-size: 562.2rem; /* r - is for the root, the main perpous is to ignor paranet settings - the value is not = value + parrent value */
}
```

font weight

```css
h1{
	font-weight: normal;
}
```

[font-weight](https://developer.mozilla.org/en-US/docs/Web/CSS/font-weight)

Line height

```css
line-height: 1; /* normal, 2 - double the distance */
```

float

```css
.chili-img{
    width: 25%;
    float: left;
    margin-right: 30px;
}
```

![CSS%20-%202%20e3eb73122a4d4129857970128dc1e197/Screenshot_2021-02-11_170822.png](CSS%20-%202%20e3eb73122a4d4129857970128dc1e197/Screenshot_2021-02-11_170822.png)

clear:

```css
.description-srp{
    clear: left;
}
```

![CSS%20-%202%20e3eb73122a4d4129857970128dc1e197/Untitled.png](CSS%20-%202%20e3eb73122a4d4129857970128dc1e197/Untitled.png)

## CSS Button Generator

[CSS Button Generator](https://css3buttongenerator.com)

## z-index

[z-index](https://developer.mozilla.org/en-US/docs/Web/CSS/z-index)

[CSS%20-%202%20e3eb73122a4d4129857970128dc1e197/Stacking_Order_Flowchart_v2.1.pdf](CSS%20-%202%20e3eb73122a4d4129857970128dc1e197/Stacking_Order_Flowchart_v2.1.pdf)

```css
/*title image*/

.title-image{
    width: 60%;
    transform: rotate(25deg);
    position: absolute;
    right: 15%;
}

/*Feature section */

#features{
    background-color: white;
    padding: 7% 15% !important;
    position: relative;
}
```

## Media query

**Media queries** are useful when you want to modify your site or app depending on a device's general type (such as print vs. screen) or specific characteristics and parameters (such as screen resolution or browser viewport width).

> @media <type> <feature>

[Using media queries](https://developer.mozilla.org/en-US/docs/Web/CSS/Media_Queries/Using_media_queries)

```css
/* media condition */

@media (max-width: 1028px) {
    #title{
        text-align: center;
    }

    .title-image{
        position: static;
        transform: rotate(0);
    }
}
```

---

## Combining Selectors  - 7.10

Multiple Selectors

```css
h1, h2, h3, h4, h5, h6{
    font-family: 'Montserrat', 'sans-serif';
    font-weight: 800;
}
```

Hierarchical Selectors

```css
#title .container-fluid{
	padding-top: 3%;
	text-align: left;
}
```

> selector1 selector2 {}

first selector from the parent 

the second selector from the chelid

![CSS%20-%202%20e3eb73122a4d4129857970128dc1e197/Screenshot_2021-02-25_222222.png](CSS%20-%202%20e3eb73122a4d4129857970128dc1e197/Screenshot_2021-02-25_222222.png)

---

### when there is no `space` it reading from `left` to `right`

the browser read the selectors from `right` to `left`

the two class have to be applied to the same element

```html
<h1 class="con btn">Hellow World</h1>
```


```css
.con.btn{
	color: red;
}
```

```css
h1.con.btn{
	color: red;
}
```

![CSS%20-%202%20e3eb73122a4d4129857970128dc1e197/Screenshot_2021-02-25_222648.png](CSS%20-%202%20e3eb73122a4d4129857970128dc1e197/Screenshot_2021-02-25_222648.png)

### the `div` in this example have a child of `.container-fluid` not `#title`

---

## Selector priority

- **Inline style**
- **#ID**
- **.Class**
- **HTML element**