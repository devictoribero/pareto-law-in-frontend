# 👨‍💻 Pareto law in frontend
Pareto's law applied in Frontend development. **Learn the 20% that gives you the 80% that's the rule.**

# 📝 HTML
The `html` is the language to create content in web development.

## Content hierarchy
An **important thing to know when building web applications or websites is to create a content hierarchy**. To do so, I recommend to:
* Create websites without styles so we can see if the content makes sense on it's own
* Place the most relevant content as before as possible

### Tips
* At least one `<h1>` should be present.
* At least one `<main>` should be present.
* Usually a `<footer>` should be present.
* If there is a block with many `<a>`, a `<nav>` should be present.
* If there is a `date` somewhere, a `<time>` should be present.
* If there is content that makes sense on its own, an `<article>` should be present.

## Semantic HTML
`<html>` is a mix of `tags` and `text content`. Long time ago the tags used to be `non-semantic` what derived everyone to use the `<div>` for everything.

Semantic markup is built by `tags` that add meaning to the web *(for example, the `<main>` tag says to the crawler: Here you have the main content of a document)*. To be able to do *semantic markup* you don't need to know all the `html` tags. If you're going to create something and you don't know if there is a tag that fits that need, [you can check here the existent tags](https://www.w3schools.com/tags/).

### Benefits
* Better maintanibility (Gives context and it's easier to read)
* Better SEO (Semntic html makes easier the robots to read and understand the page)
* Massive accessibility improvement

![
](https://almosthumor.files.wordpress.com/2011/09/html5demo1.jpg)

### ⚠️ The most relevant `non-semantic` html tags are:
#### 👉 The element `<span>`
* The <span> tag is used to group inline-elements in a document.
* The <span> tag provides no visual change by itself.
* The <span> tag provides a way to add a hook to a part of a text or a part of a document.
	
#### 👉 The element `<div>`
* The <div> tag defines a division or a section in an HTML document.
* The <div> element is often used as a container for other HTML elements to style them with CSS or to perform certain tasks with JavaScript.

### ⚠️ The most relevant `semantic` html tags are:
#### 👉The element `<a>`
* Defines a hyperlink, which is used to link from one page to another.
	
#### 👉The element `<article>`
* Specifies independent, self-contained content.
* Should make sense on its own and it should be possible to distribute it independently from the rest of the site.
* Potential sources for the <article> element:
	* Forum post
	* Blog post
	* News story
	* Comment
	
#### 👉The element `<aside>`
* Defines some content aside from the content it is placed in.
* The aside content should be related to the surrounding content.
	
#### 👉The element `<figcaption>`
* Defines a caption for a <figure> element.
* Can be placed as the first or last child of the <figure> element.
	

#### 👉The element `<figure>`
* Specifies self-contained content, like illustrations, diagrams, photos, code listings, etc.
* While the content of the <figure> element is related to the main flow, its position is independent of the main flow, and if removed it should not affect the flow of the document.
	
#### 👉The element `<footer>`
* Defines a footer for a document or section.
* Should contain information about its containing element.
* You can have several `<footer>` elements in one document.
* A `<footer>`element typically contains:
	* authorship information
	* copyright information
	* contact information
	* sitemap
	* back to top links
	* related documents
	
#### 👉The element `<form>`
* Used to create an HTML form for user input.
* Can contain one or more of the following form elements: `<input>`, `<textarea>`, `<button>`, `<select>`, `<option>`, `<fieldset>`, `<label>`

#### 👉The element `<h1>` to `<h6>`
* Used to define HTML headings.

#### 👉The element `<header>`
* Represents a container for introductory content or a set of navigational links.
* You can have several <header> elements in one document.
* A <header> element typically contains:
	* one or more heading elements (`<h1>` - `<h6>`)
	* logo or icon
	* authorship information
	
#### 👉The element `<img>`
* Defines an image in an HTML page.
* Has two required attributes:
	* `src`: Specifies the URL of an image.
	* `alt`: Specifies an alternate text for an image
* Has optional attributes:
	* `srcset`: Specifies the URL of the image to use in different situations
	
#### 👉The element `<input>`
* Specifies an input field where the user can enter data.
* Used within a `<form>` element to declare input controls that allow users to input data.
* The attribute type` which express the type of data will be introduced, can have many values:
	* `checkbox`
	* `date`
	* `email`
	* `file`
	* `hidden`
	* `number`
	* `password`
	* `radio`
	* `search`
	* `tel`
	* `text`
	* `url`

PS: I recommend to (check the `<input>`specifications)[https://www.w3schools.com/tags/tag_input.asp]
	
#### 👉The element `<label>`
* Does not render as anything special for the user. However, it provides a usability improvement for mouse users, because if the user clicks on the text within the <label> element, it toggles the control.
* The `for` attribute of the `<label>` tag should be equal to the id attribute of the related element to bind them together.

*Tip: A label can be bound to an element either by using the for` attribute, or by placing the element inside the `<label>` element.*
	

#### 👉The element `<main>`
* Specifies the main content of a document
* The content inside the `<main>` element should be unique to the document
	
*Note: There must not be more than one `<main>` element in a document. The `<main>` element must NOT be a descendant of an `<article>`, `<aside>`, `<footer>`, `<header>` or `<nav>` element.*

#### 👉The element `<nav>`
* Defines a set of navigation links.
* Notice that NOT all links of a document should be inside a <nav> element. The <nav> element is intended only for major block of navigation links.
	
#### 👉The element `<section>`
* Defines sections in a document, such as chapters, headers, footers, or any other sections of the document.

#### 👉The element `<select>`
* Used to create a drop-down list.

#### 👉The element `<ul>`
* Defines an unordered (bulleted) list.

#### 👉The element `<ol>`
* Defines an ordered list. An ordered list can be numerical or alphabetical.

#### 👉The element `<li>`
* Defines a list item.

#### 👉The element `<table>`
* Defines an HTML table.

#### 👉The element `<time>`
* Defines a human-readable date/time.
