## Prologue

This is an introductory session on HTML (HyperText Markup Language). HTML is the standard markup language used to create and structure content on the web. It provides the basic building blocks for web pages, allowing you to organize text, images, links, and other elements so they can be displayed in web browsers.

HTML documents are made up of elements, each defined by tags. These elements tell the browser how to display the content and how different parts of the page relate to each other.

## Basic Structure of HTML

```html
<!DOCTYPE html>
<html>
  <head>
    <title>Title</title>
  </head>
  <body>
    <h1>Heading</h1>
    <p>Paragraph</p>
    <footer>Footer</footer>
  </body>
</html>
```

Let's break down the code above:

### `<!DOCTYPE html>`

The `<!DOCTYPE html>` declaration tells the browser that the document is an HTML5 file. This ensures the browser uses the correct rendering mode.

### `<html></html>`

The `<html>` tag wraps all the content of your HTML document. It is the root element of the page.

### `<head></head>`

The `<head>` section contains meta-information about the document, such as its title, character encoding, styles, and links to scripts or external resources. Content in the `<head>` is not displayed directly on the page.

### `<body></body>`

The `<body>` section contains the main content of the web page, such as text, images, links, and other elements visible to users.

### `<footer></footer>`

The `<footer>` section typically contains information about the author, copyright details, or links to related documents. It appears at the bottom of the page and should be placed inside the `<body>` tag.

---

**Note:** In standard HTML, the `<footer>` tag must be placed inside the `<body>` tag, not outside. The correct structure is:

```html
<body>
  <!-- Main content -->
  <footer>Footer</footer>
</body>
```

---

### Additional Tips

- HTML is not case-sensitive, but it is best practice to use lowercase for tags.
- Indentation and proper formatting improve readability.
- Modern HTML5 introduces semantic elements like `<header>`, `<nav>`, `<main>`, `<section>`, and `<footer>` to better describe the structure of web pages.
- Always close your tags and nest them properly to avoid rendering issues.

With this foundation, you can start building more complex web pages by combining different HTML elements.

please install `Live Server Ritwick Dey` extension
