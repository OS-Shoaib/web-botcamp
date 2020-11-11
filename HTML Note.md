# HTML

# Code - Notes

---

```html
<h1>This is the first level of heading tag</h1>
<br> breaker
<!-- Comment -->
```

```html
<p> paragraph container </p>
<em> italic with bold </em> <!-- used for itelic -->
<i> only italic </i>  
<b> bold </b>
<strong> bold stronger text </strong> <!-- used for bold -->
```

HTML5 main structure code

```html
<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8">
        <title></title>
    </head>
    <body>

    </body>
</html>
```

Meta -MDN- example

> meta element give extra data to your HTML site,
it has a lot off intrabodies.

```html
<meta name="description" content="The MDN Web Docs site provides information about Open Web technologies including HTML, CSS, and APIs for both Web sites and progressive web apps. It also has some developer-oriented documentation for Mozilla products, such as Firefox Developer Tools.">
<!--Giving Site Description-->
```

Polit List

```html
<ul>
	<li>First Item</li>
	<li>Second Item</li>
	<li>Thered Item</li>
</ul>

<!-- one inside another -->
<ul>
	<li>First Item</li>
		<ul>
			<li>inside element</li>
		</ul>
	<li>Second Item</li>
	<li>Thered Item</li>
</ul>
```

Ordered List

```html
<ol>
	<li>First Item</li>
	<li>Second Item</li>
	<li>Thered Item</li>
</ol>

<!-- <ol type="i"> -->
```

Image tag

> Self closing tag
img : HTML tag
src: the file location
alt: phaser show up when image can't load

```html
<img src="me.jpg" alt="self image for me"/>
```

Hyperlink

> A basic link is created by wrapping the text or other content, see Block level links, inside an <a> element and using the **href** attribute, also known as a Hypertext Reference, or target, that contains the web address.

```html
<a href="https://www.mozilla.org/en-US/">the Mozilla homepage</a>

<!-- Force the browser to download a URL -->

<a download href="url"> Text </a>
```

Tables

[: The Table element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/table)

```html
<table>
  <thead>
    <tr>
      <th>Dates</th>
      <th>Work</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>2010</td>
      <td>Work as Electrical Tecnation</td>
    </tr>
    <tr>
      <td>2011 - 2013</td>
      <td>Eork as Tender Engineer</td>
    </tr>
  </tbody>
</table>
```

Form

[](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/form)

[: The Input (Form Input) element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input)

> We use the <form> tag to define what should  go into the form and this by itself doesn't actually do any thing so in order  for it to do any thing we will need to import an HTML elements and that's the <label> and the <input>

```html
<form action="mailto:ramomora22@gmail.com" method="post" enctype="text/plain">
        <label for="name">Your Name: </label>
        <br>
        <input type="text" id="name">
        <br>
        <label for="email">Enter your email:</label>
        <br>
        <input type="email" id="email" pattern=".+@*.com" size="30" required>
        <br>
        <label for="message">Your Message: </label>
        <br>
        <textarea rows="15" cols="60" id="message"></textarea>
        <br>
        <input type="checkbox" id="subscribe" name="subscribe">
        <label for="subscribe">Subscribe to our mail list</label>
        <br>
        <input type="submit">
    </form>
```

# Resources

---

Documentation

[MDN Web Docs](https://developer.mozilla.org/en-US/)

 

Unicode Explain:

[The Absolute Minimum Every Software Developer Absolutely, Positively Must Know About Unicode and Character Sets (No Excuses!)](https://www.joelonsoftware.com/2003/10/08/the-absolute-minimum-every-software-developer-absolutely-positively-must-know-about-unicode-and-character-sets-no-excuses/)

Unicode Characters

[Unicode Character Table](https://unicode-table.com/en/)

A beautiful example of an online CV

[Pascal van Gemert](http://www.pascalvangemert.nl/#/profile)

Final Resume Page