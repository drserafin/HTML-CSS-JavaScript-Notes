## Basic HTML Structure

HTML (Hypertext Markup Language) is the standard markup language for creating web pages.
HTML Structure

```html
<!DOCTYPE html>
<html>
<head>
	<title>Page Title</title>
</head>
<body>
	<!-- Page content goes here -->
	<h1>Heading</h1>
	<p>Paragraph</p>
</body>
</html>
```

## Element Explanations:

`<!DOCTYPE html>`: Declares the document type and version of HTML.

`<html>`: The root element of the HTML document.

`<head>`: Contains metadata about the document, such as the title, charset, and links to external stylesheets or scripts.

`<title>`: Sets the title of the page, which appears in the browser's title bar and search engine results.

`<body>`: Contains the content of the HTML document.

`<h1>`: A heading element, with `<h2>`, `<h3>`, etc. for subheadings.

`<p>`: A paragraph element.

## What does `meta` mean ? 

In HTML, `meta` refers to information about the webpage that isn't display directly on the page itself. It is used in the `<head>` section to provide detailes like the page's character encoding,author,descriptions and keywords. This information helps browsers and serach engine understand and process the webpage better. 

In simple terms: `meta` tags give extra detailes abotu the page that help with how it's displayed and found. 

```html
<!DOCTYPE html>
<html>
<head>
    <title>Example Page</title>
    <meta charset="UTF-8"> <!-- Specifies the character encoding for the document -->
    <meta name="description" content="This is an example webpage using meta tags."> <!-- Provides a description of the page for search engines -->
    <meta name="keywords" content="HTML, meta tags, example"> <!-- Lists keywords related to the page content -->
    <meta name="author" content="Kevin Serafin"> <!-- Specifies the author of the page -->
</head>
<body>
    <h1>Welcome to the Example Page</h1>
    <p>This page demonstrates the use of meta tags in HTML.</p>
</body>
</html>
```

`name` is a attribute of the `meta` elemnt.