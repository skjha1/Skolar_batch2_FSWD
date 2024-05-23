
---

# Simple HTML Example
A simple HTML example to demonstrate various basic HTML elements. Below is the full HTML code along with a detailed explanation of each part.

## HTML Code

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Simple Html example</title>
</head>
<body>

    <h1>This is a heading Level 1</h1>
    <h2>This is a heading Level 2</h2>
    <h3>This is a heading Level 3</h3>
    <h4>This is a heading Level 4</h4>
    <h5>This is a heading Level 5</h5>
    <h6>This is a heading Level 6</h6>

    <p>This is a paragraph of text. Here's a <a href="https://www.google.com">link</a> to an example website</p>

    <ul>
        <li>unordered list item 1</li>
        <li>unordered list item 2</li>
        <li>unordered list item 3</li>
        <li>unordered list item 4</li>
    </ul>

    <ol>
        <li>Ordered list item 1</li>
        <li>Ordered list item 2</li>
        <li>Ordered list item 3</li>
        <li>Ordered list item 4</li>
    </ol>

    <img src="https://via.placeholder.com/150" alt="Placeholder Image">

    <table border="1">
        <tr>
            <th>Header 1</th>
            <th>Header 2</th>
        </tr>
        <tr>
            <td>Row 1, Cell 1</td>
            <td>Row 1, Cell 2</td>
        </tr>
        <tr>
            <td>Row 2, Cell 1</td>
            <td>Row 2, Cell 2</td>
        </tr>
    </table>

    <form action="/submit-form" method="post">
        <label for="fname">First Name: </label><br>
        <input type="text" id="fname" name="fname" placeholder="Enter your first name"><br>
        <label for="lname">Last Name: </label><br>
        <input type="text" id="lname" name="lname" placeholder="Enter your last name"><br><br>
        <input type="submit" value="Submit">
    </form>

</body>
</html>
```

## Explanation

### Document Structure
- `<!DOCTYPE html>`: Defines the document type and version of HTML (HTML5 in this case).
- `<html lang="en">`: The root element of an HTML document with the language attribute set to English.
- `<head>`: Contains meta-information about the document.
    - `<meta charset="UTF-8">`: Sets the character encoding to UTF-8.
    - `<meta name="viewport" content="width=device-width, initial-scale=1.0">`: Ensures the web page is responsive by setting the viewport to match the device's width.
    - `<title>Simple Html example</title>`: Sets the title of the web page that appears in the browser tab.

### Body Content
- `<body>`: Contains the content of the HTML document.
    - `<h1> - <h6>`: Define HTML headings, where `<h1>` is the highest level (largest) and `<h6>` is the lowest level (smallest).
    - `<p>`: Defines a paragraph of text. Includes an inline `<a>` element to create a hyperlink to [Google](https://www.google.com).
    - `<ul>`: Defines an unordered (bulleted) list.
        - `<li>`: Defines a list item within an unordered list.
    - `<ol>`: Defines an ordered (numbered) list.
        - `<li>`: Defines a list item within an ordered list.
    - `<img src="https://via.placeholder.com/150" alt="Placeholder Image">`: Embeds an image with a source URL and alternative text.
    - `<table border="1">`: Creates a table with a border.
        - `<tr>`: Defines a table row.
        - `<th>`: Defines a header cell in a table.
        - `<td>`: Defines a standard cell in a table.
    - `<form action="/submit-form" method="post">`: Creates a form that submits data to the server using the POST method.
        - `<label for="fname">First Name: </label>`: Creates a label for the first name input field.
        - `<input type="text" id="fname" name="fname" placeholder="Enter your first name">`: Defines a text input field for the first name.
        - `<label for="lname">Last Name: </label>`: Creates a label for the last name input field.
        - `<input type="text" id="lname" name="lname" placeholder="Enter your last name">`: Defines a text input field for the last name.
        - `<input type="submit" value="Submit">`: Defines a submit button for the form.

This example demonstrates the basic structure and elements of an HTML document, including headings, paragraphs, links, lists, images, tables, and forms. Each element is used to structure and present content on a web page.
