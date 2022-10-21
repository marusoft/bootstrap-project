# Bootstrap

  [Bootstrap](https://getbootstrap.com/) is a powerful, feature-packed frontend toolkit.

## Getting Started with Bootstrap

  The most easiest way to use Bootstrap is through [CDN Links](https://getbootstrap.com/docs/5.2/getting-started/introduction/#cdn-links)
  The primary CDN Links are:
  _CSS_   ``` https://cdn.jsdelivr.net/npm/bootstrap@5.2.2/dist/css/bootstrap.min.css ```
  _JS_    ``` https://cdn.jsdelivr.net/npm/bootstrap@5.2.2/dist/js/bootstrap.bundle.min.js ```
Copy and paste the CSS link to Head tag in index.html and the JS link inside body tag

### Illustration

### Container

#### Navigation bar

To create a navbar, we can make use of the available example and customise to our use
[https://getbootstrap.com/docs/5.2/components/navbar/](https://getbootstrap.com/docs/5.2/components/navbar/)

```html
 <nav class="navbar navbar-dark bg-dark">
    <!-- Navbar content -->
 </nav> 

<nav class="navbar navbar-dark bg-primary">
  <!-- Navbar content -->
</nav> 

<nav class="navbar" style="background-color: #e3f2fd;">
  <!-- Navbar content -->
</nav> 
```

## Width

```html
w = width
w-100 = width of 100%
Example: <section class="w-100"></section>
```

## Margin

```html
m = margin
mt = margin-top 
mr = margin-right
ml = margin-left
mb = margin-bottom
mx = margin left and right
my = margin top and bottom
Example: <section class="m-1"></section>
```

## Padding

```html
p = padding
pt = padding-top
pr = padding-right
pl = padding-left
pb = padding-bottom
px = padding left and right
py = padding top and bottom
Example: <section class="p-2"></section>
```

## Background Color

```html
bg = background-color
bg-light = light color
bg-dark = dark color
Example: <section class="bg-light"></section>
```

## Text Color

```html
text-light = light color text
text-dark = dark color text
Example: <section class="text-light"></section>
```

### Text Positioning

```html
text-center = place element/text at the center
Example: <section class="text-center"></section>
```

### Text-color

```html
<h1 class="text-primary">Become a Web Developer</h1>
<h2 class="text-warning">Become a Web Developer</h2>
```

### Image

```html
 <img class="img-fluid w-50" src="./img/sample.jpeg" alt="">
 illustration: The img-fluid class will make an image to stay in its container and w-50 will give 50% width
```

### Bootstrap Flexbox

```html
<div class="d-flex">
  <div>
    <h1>Become a Web Developer</h1>
  </div>
  <img src="/exampl.png" alt="">
</div>
illustration: The two direct child div and img elements will be placed side by side with the parent container class = d-flex
```

### Display property

```html
display block: d-block
display none: d-none
display block small screen devices = d-sm-block
display none small screen devices = d-none-sm
```

### Bootstrap Icons

```html
 <link
  rel="stylesheet"
  href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.3.0/font/bootstrap-icons.css"
/>
example: <i class="bi bi-laptop"></i>
```

### Breakpoints

| Breakpoint         | Class infix        | Dimensions  |
| -------------      |:------------------:| -----------:|
| Extra small        |  None              |   <576px    |
| Small              | sm                 |   ≥576px    |
| Medium             | md                 |   ≥768px    |
| Large              | lg                 |   ≥992px    |
| Extra large        | xl                 |  ≥1200px    |
| Extra extra large  | xxl                |  ≥1400px    |
  