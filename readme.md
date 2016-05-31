# HTML/CSS Review

This is a review of your working knowledge of HTML and CSS. Note that this review is designed to help you recall and familiarize yourself with technical concepts.

## Getting Started

* Fork and clone this repository
* Answer the following questions by...
  * Opening this file in Sublime
  * Answering the questions via Markdown. Feel free to refer to this [Markdown Cheat Sheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
* Commit your changes
* Make a pull request for submission

---

## HTML

1.) Create a valid, empty HTML page with the necessary tags.

```html
<!-- 
<!DOCTYPE html>
<html>
<head>
  <title></title>
</head>
<body>

</body>
</html>
 -->
```

2.) What are the differences between these tags?

```html
<!-- Tag 1 -->
<img src="images/me.jpg" alt="My profile image">

<!-- Tag 2 -->
<div></div>
```

```
One is an image (an element), and the other is a "div," which can be used to contain/divide things such as elements.
```

---

## CSS

1.) Compare and contrast the following ways to add CSS to HTML elements.

```html
<!-- Inline CSS -->
<div style="background-color: red;"></div>

<!-- Internal style sheet -->
<style type="text/css">
  div {
    background-color: red;
  }
</style>

<!-- External style sheet (not shown) -->
<link rel="stylesheet" type="text/css" href="css/style.css">
```

```
The first two methods choose to declare style information within the html document which is not as efficient as the third method of using an external style sheet which pulls style information from a separate css file.
```

2.) Below are some different CSS selectors. Use CSS comments to describe what each selector will do.

```css
/* comment like this */
div {
  border-radius: 50%;
}
/*
This assigns the div (or anything in the div) a border with a radius of 50%
*/

.header p {
  font-size: 18px;
}
/*
This assigns a font size of 18 pixels to the text in the paragraph in the header.
*/

.footer {
  position: absolute;
  bottom: 0;
}
/*
This assigns any elements in the footer an absolute position (defined by the page) and not other page elements.
*/


.splash-image {
  background-image: url("../images/ocean.jpg");
  background-size: cover;
  width: 100%;
}
/*
This defines a css class of "splash-image" assigns it a background image, size, and width of 100% of the page. 

.ninja:hover {
  display: none;
  color: black;
}
```

