# Bootstrap

---

[Bootstrap](https://getbootstrap.com/)

Examples

[Examples](https://getbootstrap.com/docs/4.0/examples/)

## Design helper sites

[Awwwards - Website Design Inspiration](https://www.awwwards.com/websites/com/)

[UI-Patterns.com](http://ui-patterns.com/)

[Dribbble - Discover the World's Top Designers & Creative Professionals](https://dribbble.com/)

[Sneakpeekit Sketch Sheets](https://sneakpeekit.com)

[Balsamiq. Rapid, Effective and Fun Wireframing Software | Balsamiq](https://balsamiq.com)

---

## Start using bootstrap:

---

Include bootstrap on your site

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.6.0/dist/css/bootstrap.min.css" integrity="sha384-B0vP5xmATw1+K9KRQjQERJvTumQW0nPEzvF6L/Z6nronJ3oUOFUFpCjEUQouq2+l" crossorigin="anonymous">
```

Add JavaScript and jQuery to the site in order to function

```html
<script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
<script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js" integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN" crossorigin="anonymous"></script>
<script src="https://cdn.jsdelivr.net/npm/bootstrap@4.6.0/dist/js/bootstrap.min.js" integrity="sha384-+YQ4JLhjyBLPDQt//I+STsc9iw4uQqACwlvpslubQzn4u2UU2UFM80nGisd026JF" crossorigin="anonymous"></script>
```

navigation bar using bootstrap

```html
<nav class="navbar bg-dark navbar-expand-lg navbar-dark">
    <a class="navbar-brand" href="">Tindog</a>
     <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>
  <div class="collapse navbar-collapse" id="navbarSupportedContent">
    <ul class="navbar-nav ml-auto">
        <li class="nav-item">
            <a class="nav-link" href="">Contact</a>
        </li>
        <li class="nav-item">
            <a class="nav-link" href="">Pricing</a>
        </li>
        <li class="nav-item">
            <a class="nav-link" href="">Download</a>
        </li>
    </ul>
 </div>
</nav>
```

[Embedded Codeply](https://www.codeply.com/p/GVJU3ipWxP)

Source

[Navbar](https://getbootstrap.com/docs/4.5/components/navbar/)

colors

[Buttons](https://getbootstrap.com/docs/4.5/components/buttons/)

# Grid system

[Grid system](https://getbootstrap.com/docs/4.5/layout/grid/)

sperate screen to fixed equaled columns

```html
<div class="row">
    <div class="col" style="background-color:red; border: 1px solid;">
      col      
    </div>
    <div class="col" style="background-color:red; border: 1px solid;">
      col      
    </div>
    <div class="col" style="background-color:red; border: 1px solid;">
      col      
    </div>
</div>
```

sperate screen to fixed unequaled columns

### the entire width is **`12`**

```html
<div class="row">
    <div class="col-6" style="background-color: green; border: 1px solid;">
        col
    </div>
    <div class="col-3" style="background-color: green; border: 1px solid;">
        col
    </div>
    <div class="col-2" style="background-color: green; border: 1px solid;">
        col
    </div>
    <div class="col-1" style="background-color: green; border: 1px solid;">
        col
    </div>
</div>
```

sperate row to dynamic columns

md: referee to minim screen size the column will be fixed - "large and medium screens"

it will take a 100% in smaller screen

```html
<div class="row">
    <div class="col-md-6" style="background-color: brown; border: 1px solid;">
        col
    </div>
    <div class="col-md-6" style="background-color: brown; border: 1px solid;">
        col
    </div>
</div>
```

custom for all screens size

```html
<div class="row">
    <div class="col-lg-3 col-md-4 col-sm-6" style="background-color: yellow; border: 1px solid;">
        col
    </div>
    <div class="col-lg-3 col-md-4 col-sm-6" style="background-color: yellow; border: 1px solid;">
        col
    </div>
    <div class="col-lg-3 col-md-4 col-sm-6" style="background-color: yellow; border: 1px solid;">
        col
    </div>
    <div class="col-lg-3 col-md-4 col-sm-6" style="background-color: yellow; border: 1px solid;">
        col
    </div>
</div>
```

# Containers

[Containers](https://getbootstrap.com/docs/5.0/layout/containers/)

```html
<div class="container" style="background-color: red;">
<!-- Has pading -->
    Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.
</div>

<div class="container-fluid" style="background-color: yellow;">
<!-- Dosen't Have pading -->
    Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.
</div>
```

# Buttons

[Buttons](https://getbootstrap.com/docs/4.6/components/buttons/)

for icons

[Font Awesome](https://fontawesome.com)

```html
<!-- fontawesome -->
<script src="https://kit.fontawesome.com/92cb0d8b0f.js" crossorigin="anonymous"></script>
```

for forcing custom layout on Bootstrap we use `!important`

```css
.container-fluid {
    padding: 0!important;
}
```

Buttons code

```html
<div class="col-lg-6">
	<h1>Meet new and interesting dogs nearby.</h1>
	<button type="button" class="btn btn-dark btn-lg"> <i class="fab fa-apple"></i> Download</button>
	<button type="button" class="btn btn-outline-light btn-lg"> <i class="fab fa-google-play"></i> Download</button>
</div>
```