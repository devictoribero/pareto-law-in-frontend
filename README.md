# 👨‍💻 pareto-law-in-frontend
Pareto's law applied in Frontend development. **Learn the 20% that gives you the 80% that's the rule.**

## 📝 HTML
The `html` is the language to create content in web development.

### Content hierarchy
An **important thing to know when building web applications or websites is to create a content hierarchy**. To do so, I recommend to:
* Create websites without styles so we can see if the content makes sense on it's own
* Place the most relevant content as before as possible

#### Tips
* At least one `<h1>` should be present.
* At least one `<main>` should be present.
* Usually a `<footer>` should be present.
* If there is a block with many `<a>`, a `<nav>` should be present.
* If there is a `date` somewhere, a `<time>` should be present.
* If there is content that makes sense on its own, an `<article>` should be present.

### Semantic HTML
To be able to do *semantic markup* you don't need to know all the `html` tags. If you're going to create something and you don't know if there is a tag that fits that need, [you can check here the existent tags](https://www.w3schools.com/tags/).
![
](https://almosthumor.files.wordpress.com/2011/09/html5demo1.jpg)

The most relevant `non-semantic` html tags are:
* `<span>`
* `<div>`

The most relevant `semantic` html tags are:
* `<nav>`
	* `<a>`
* `<header>`
	* `<h1>, <h2>, ...`
* `<aside>`
* `<main>`
* `<section>`
	* `<ul>`, `<ol>`
		* `<li>`
	* `<form>`
		* `<input>`
		* `<select>`
	* `<article>`
		* `<time>`
	* `<figure>`
		* `<figcaption>`
		* `<img>`
	* `<table>`
		* `<thead>`
			* `<th>`
		* `<tbody>`
			* `<td>`
		* `<tr>`
* `<footer>`

*PS: The indentation is an example to know where we can use those tags.*
