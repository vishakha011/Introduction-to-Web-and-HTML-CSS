
## Introduction to Web
The simplified view of how the web works is of what happens when we visit a certain webpage in a web browser on our computer or phone. The entire working can be divided into Client-Server Model.

Clients are typically our Computers, Phones and web browsers such as Firefox, Chrome and Servers are computers that store webpages, sites, or apps. So, whenever we open a website, we make a request to the SERVER from the CLIENT and the server in response send us the requested page or data.
Based on the CLIENT-SERVER model, web development has two parts: Front-End and Back-end.

The frontend of a website is what you see and interact with on your browser. Also referred to as “client-side”, it includes everything the user experiences directly: from text and colors to buttons, images, and navigation menus.
Whatever we see and interact with on our browser including texts, colors, buttons, images is included into Front-End development which is also referred to as "Client-side".
The languages used for Front-end Development are:
1. Html
2. CSS
3. JavaScript

The backend also known as the server-side is the portion of the website we don’t see and is responsible for storing and organizing data, and ensuring everything on the client-side actually works.
The languages used for Back-end Development are:

1. PHP
2. Java
3. Ruby
4. Python, etc.

Most of the websites are run by only three languages (HTML, CSS & JavaScript) and your browser also understands only these languages only. It is important to note that the browsers understand only these three languages so whatever you see on a page or you interact with it is HTML, CSS, and JS only. It can be said that these three are building blocks of any website. Mostly all the websites rely on these three languages.
So, Let's discuss the difference Between HTML, CSS, JavaScript.

### HTML:- 
HTML is the fundamental coding language that creates and organizes web content so it can be displayed by a browser. 
### CSS:-
CSS is a language that accompanies HTML, and defines the style of a website’s content, such as layout, colors, fonts, etc.
### JavaScript:-
JavaScript is a programming language used for more interactive elements like drop down menus, modal windows, and contact forms.

## Introduction to HTML:
HTML refers to HyperText Markup Language. HTML is considered as the basic building block of the Web. 
Links are an important aspects of the Web and "Hypertext" refers to links that connect web pages to one another, either within a single website or between websites.
HTML is considered as a markup language and not as a programming language because HTML is only use to wrap the content such as texts, images, paraghraph so that the browser can understant the type of contents that we are sending. This wraping of the content is known as markup
## Elements, Tags, and Attributes:

**Elements** contains opening tags, content, closing tags; for example,  
`<h1>Hello World!</h1>`

**Tag** marks the beginning and ending of an element. It consists of a less-than sign followed by an element’s name, and then ends with a greater-than sign; for example, `<p></p>`.

**Attributes** provide some extra information about the element, which actually doesn’t appear as content in a webpage. An attribute defines a property for an element, consists of an attribute/value pair, and appears within the element’s start tag; for example, 
`<a href="example.com">Example</a>`
## Standard HTML Document Structure:
Html documents are saved with .html file extensions. To create an html file open any editor and create a fiel with .html extension and type the code given below.
```
<!DOCTYPE html>
<html lang="en">
  	<head>
   		<meta charset="utf-8">
    	<title>Hello World</title>
  	</head>
  	<body>
 	</body>
</html>
```
The above code is the standard HTML document structure, which is required everytime we create a new html document.

`<!DOCTYPE html>`  - Document type declaration used to inform the browser the version of HTML being used.

`<html>` - root element of an HTML page.

`<head>` - stores extra information for a page which is not visible on the page.

`<body>` - contains the visible content of the page.

## Self Closing Elements
There are few tags that don’t require closing tags and they can end within a starting/opening tag only and the get their content from the attribute within a single tag.For example,
`<br>`, `<hr>`, `<iframe>`, `<img>`, `<link>`, `<input>`, `<meta>`, etc

## Nesting and Indentation
To make the code human readable indentation and nesting is importqant. In Html, improper indentation and spacing will not impact the functionality of the web page but will cause difficulty to understand. Hence, indentation plays a vital role for programmers to make their code more organized and readable.

## Introduction to CSS.
The presentation of any webpage depends completely on Cascading Style Sheets(CSS). CSS improves the accessibility, provide more flexibility and control. To style elements they are first targeted and then the required styles are applied with the help of selectors, properties and values in CSS.

**Selector** - A selector is an HTML tag at which a style will be applied. This could be any tag like `<h1>` or `<table>` etc.

**Properties** - a property determines the styles that will be applied to that element; for example, *color*, *border*, etc.

**Values** - Values are assigned to properties. For example, color property can have value either *red* or *#F1F1F1* etc.

## Types of Selectors(Type, Class, ID)

**Type Selector** - Type selectors target an element with the element name or element type. For example, 
h1, p, div, etc
```
h1 {

	font-size: 24px;
}
```

**Class** - Class Selector allows us to target an element with the class attribute defines inside the tag. For example, 
```
<div class = "square">...</div>

.square {

	height: 152px;
	width: 150px;
}
```
**ID Selector** - ID selectors are unique selectors that cannot be reused anywhere inside the code.
For example,
```
<div id="box"></div>

  #box {

    background-color: green;
  }
```
## Referencing CSS
CSS can be attached as a separate document or can be embedded in the HTML document itself. There are three methods of including CSS in HTML file:

**Inline Styling:** The required styles are written inside the tag. For example,  
```<h1 style="color:blue">Document</div>```

**Internal Styling:**  In internal styling, a style tag is define in the head element. 

**External Styling:** In external styling, a separate stylesheet is created to write the CSS and then connected to the HTML with the link tag. The external file is saved with .css extension. 

