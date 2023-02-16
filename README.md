# intro-to-html-css-js

# HTML
HTML (Hypertext Markup Language) is the standard language used to create and design websites. It provides a way to structure content and add text, images, videos, links, and other multimedia elements to web pages, and is a crucial foundation for web development.

## Getting Started
In order to write HTML code, you will need a text editor and a web browser. You can use any text editor you are comfortable with, such as Notepad, TextEdit, or Sublime Text. For testing your HTML pages, you can use any web browser, such as Chrome, Firefox, or Safari.

## Creating a HTML Page
To create an HTML page, you need to follow a few basic steps:

1. Create a new folder.
2. Open that folder in your text editor and create a new file with an `.html` extension (e.g., `index.html`).
3. Add the basic structure of an HTML page, which includes the `<!DOCTYPE html>` declaration and the `<html>`, `<head>`, and `<body>` tags.
4. Add the content to your page using tags such as `<h1>` for headings, `<p>` for paragraphs, `<img>` for images, and `<a>` for links.
5. Save your file and open it in a web browser to view the page.

## Using Tags
Tags in HTML are used to mark up different types of content on a web page, such as headings, paragraphs, lists, images, links, and so on. Tags are enclosed in angle brackets (`<` and `>`). Here are some common HTML tags you might need for your project:

### Header
`<h1>Anya Forger</h1>`
`<h3>Welcome to Anya's page!!</h3>`

A header tag is used to define a heading or a section title in a page. It is represented by `<h1>`, `<h2>`, up to `<h6>` tags, with `<h1>` being the largest and most important heading and `<h6>` being the smallest.

### Paragraph
`<p>I'm Anya! I'm 6, and this is where you can read everything about me. 𓁹‿𓁹</p>`

Simply put, a paragraph tag define a block of text or a paragraph. It is represented by the `<p>` tag.

### Image
`<img src="https://static.tvtropes.org/pmwiki/pub/images/anya_happy.png" alt="anya_happy", height="200px"/>`

An image tag is used to define an image. The `src` attribute specifies URL of the image file. The `alt` attribute provides a descriptive text of the image. 

The `<img>` tag can also include other attributes, such as width and height, to specify the size of the image.

- Note that the `<img>` tag is a self-closing tag, which means that you don't need to add another closing tag like `</img>`!

### Link
`<a href="https://www.youtube.com/watch?v=zAO_Rqkm1CA">Self-Defense</a>`

A link tag defines a hyperlink and is represented by `<a>`. The `href` attribute provides the URL of the target page. When the user clicks on the link, their browser will navigate to that page.

### List
A list tag is a tag used to create lists of items. There are two main types of lists in HTML: ordered lists (`<ol>`) and unordered (`<ul>`) lists. Every item in the list is represented by the `<li>` tag.

#### unordered list
```
<ul>
    <li>Telepathy</li>
    <li>Self-Defense</li>
    <li>Tennis</li>
</ul>
```
#### ordered list
```
<ol>
    <li>Peanuts</li>
    <li>Bondman</li>
    <li>Odekeke (family outing)</li>
</ol>
```

### Button
`<button type="button">Click to pat my dog Bond</button>`

A button tag is used to create buttons on a web page. It is represented by the `<button>` tag.
- For now, nothing will happen when the user clicks the button. To make the button interactive, we need to use more than just HTML. One way to achieve this is by executing a JavaScript function when the button is clicked using the 'onClick' attribute. We will cover this in more detail in the JavaScript section of this workshop.