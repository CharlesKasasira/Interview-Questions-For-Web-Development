# HTML Interview Questions.

### 1. Describe HTML? 


HTML is an acronym for HyperText Markup Language, used for structuring contents on a web page. HyperText: HyperText simply means "Text within Text." A text that has a link within it, is a hypertext. HyperText is a way to link 2 or more HTML documents.
Markup language: A markup language is a computer language that is used to apply layout and formatting conventions to a text document. The contents of each webpage are defined by HTML tags, which hold the HTML elements.
<br />
<br />

### 2. Write the basic structure of the HTML template? 


```html
<!DOCTYPE html>
<html>
	<head>
		<title></title>
	</head>
	<body>

	</body>
</html>
```
<br />
<br />

### 3. Name some new features which were not present in HTML but are added to HTML5? 


HTML5 is the 5th version of HTML. With invent of features in HTML5, it’s not only possible to create better websites, but we can also create dynamic websites.
Some of the new features of HTML5 are tags and attributes.  With these new tags, there is no longer a need to identify most of the elements with a <div> tag. 
The tags are =>

- `<header>` and `<footer>`
- `<nav>`
- `<video>` and `<audio>` 
- `<svg>` and `<progress>`
- `<figure>` and `<figcaption>`
- `<main>` `<section>`, `<aside>`, `<article>`, `<summary>`.

The attributes =>

- `placeholder attribute`: The placeholder attribute specifies a short hint that describes the expected value of an input field/text area. The short hint is displayed in the field before the user enters a value.
- `Email attribute`
<br />
<br />

### 4. What is an Anchor tag and how can you open an URL into a web tab when clicked?


The anchor tag `(<a>)` is used to create a hyperlink on the webpage. This hyperlink is used to link the webpage to other webpages. It’s either used to provide an absolute reference or a relative reference as its “href” value.  

To open a URL into a web tab, add the target="_blank" attribute to the anchor tags.
<br />
<br />

### 5. Define Semantic elements in HTML? 


Semantic elements are elements with meaningful names.
A semantic element clearly describes its meaning to both the browser and the developer.(https://cutt.ly/cECob72)
Examples of Semantic tags
`<header>`
`<nav>`
`<article>`
`<section>`
`<footer>`
<br />
<br />

### 6. Define attributes in HTML tag?


HTML attributes are name/value pairs e.g name="value", specified in the start tag that provide additional information about HTML elements.
<br />
<br />

### 7. What are inline elements and block-level elements in HTML? 


inline elements are elements that don't use up all the width, they only take as much width as necessary.

block-level elements are elements that cover up all width from the left to the right. They take up the full width available.
<br />
<br />

### 8. How can we create a hyperlink in HTML? 


A hyperlink is created using the anchor tag (<a>your link</a>) which has an href attribute that takes in a URL for its value.
<br />
<br />

### 9. Why Meta tags are used in HTML? 


Meta tags describe the HTML document. metadata is the data (information) about data. They can specify the character set used, the viewport settings, sometimes the keywords and the author of the document.
<br />
<br />


### 10. Explain list elements in HTML? 

Lists are used to group items together so they associate with each other.
1. ordered list element - in a particular order.
2. unordered list element - in no particular order.
<br />
<br />

### 11. Define iframe in HTML?

An HTML iframe is used to display a web page within a web page.
```html
<iframe src="url" title="description"></iframe>
```
<iframe src="url" title="description"></iframe>

https://cutt.ly/9Rt9eQp
<br />
<br />


### 12. What is the SVG element?

The SVG(Scalar Vector Graphics ) element is used to draw vector graphics on the web using XML.

https://developer.mozilla.org/en-US/docs/Web/SVG/Element/svg
<br />
<br />

### 13. Explain about canvas? 

canvas is an HTML tag that lets you draw on the browser. The canvas is like a container that lets you draw graphics using javascript.
<br />
<br />

### 14. What is Quirks mode in HTML5?

Quirks mode aka compatibility mode means your page is running without a correct DOCTYPE declared, the document type is defined at the very top of a page and it denotes how the browser should read the HTML.
The purpose of Quirks Mode is to make old pages to display as their author in­tend­ed.