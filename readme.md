# How to Write an HTML Boilerplate
![html](https://github.com/EdwardKim030391/intro-to-markdown-lab/blob/main/images.jpeg)

HTML document starts with a boilerplate. This serves as the foundation for your web pages, ensuring that they are structured correctly and compatible with browsers. Here's a quick guide to writing an HTML boilerplate from scratch.

## 1. What is an HTML Boilerplate?
HTML boilerplate is the basic structure of an HTML document. It includes essential tags and metadata to define the document's type, character encoding, and content layout.

## 2. The Basic Structure
Here's basic structure of an HTML document:

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Your Page Title</title>
</head>
<body>
  
</body>
</html>
```

### Key Elements of the Boilerplate:
1. **!DOCTYPE html**: Declares the document type as HTML5.
2. **html lang="en"**: Starts the HTML document and specifies the language.
3. **head**: Contains metadata like the character set, viewport settings, and title.
4. **meta charset="UTF-8"**: Sets the character encoding to UTF-8.
5. **meta name="viewport" content="width=device-width, initial-scale=1.0"**: Ensures proper scaling on mobile devices.
6. **titleYour Page Title</title>**: Defines the title of the webpage (shown on the browser tab).
7. **body**: Contains the visible content of the webpage.

## 3. Adding Comments
Comments help organize your code and are not visible to users. Add them using:

```html
<!-- This is a comment -->
```

## 4. Example
Here's an example of a complete HTML boilerplate with content:

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Welcome Page</title>
</head>
<body>
  <h1>Welcome to My Website</h1>
  <p>This is a simple HTML boilerplate example.</p>
</body>
</html>
```

## 5. Additional Resources
For more details on HTML boilerplates, visit the [MDN HTML Basics.](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/HTML_basics)
