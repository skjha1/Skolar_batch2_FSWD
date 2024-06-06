```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Simple HTML Example</title>
    <style>
        body {
            font-family: Arial, Helvetica, sans-serif;
            background-color: #f9f9f9;
            margin: 20px;
        }
        ol {
            padding: 20px;
        }

        ol li {
            margin: 10px 0;
            padding: 10px;
            background-color: #fff;
            border: 1px solid #ddd;
            border-radius: 5px;
        }

        ol ol {
            padding: 20px;
        }

        table {
            width: 100%;
            border-spacing: 10px;
            border: 1px solid #ddd;
            margin: 20px 0;
        }
        table, th, td {
            border: 1px solid #ddd;
        }
        th, td {
            padding: 12px;
            text-align: left;
            border: 1px solid #ddd;
        }
        th {
            background-color: #f2f2f2;
        }
        tr:nth-child(even) {
            background-color: #f9f9f9;
        }
        tr:hover {
            background-color: #f1f1f1;
        }
        thead {
            background-color: #007bff;
            color: white;
        }

        form {
            width: 300px;
            margin: 0 auto;
        }
        label {
            display: block;
            margin-bottom: 5px;
        }
        input[type="text"] {
            width: 100%;
            padding: 8px;
            margin-bottom: 10px;
            border: 1px solid #ccc;
            border-radius: 5px;

        }
        input[type="submit"] {
            width: 100%;
            padding: 10px 20px;
            margin-bottom: 10px;
            border: none;
            border-radius: 4px;
            background-color: #4caf50;
            color: white;
        }
    </style>
</head>
<body>
    <h1>This is a Heading level 1</h1>
    <h2>This is a Heading level 2</h2>
    <h3>This is a Heading level 3</h3>
    <h4>This is a Heading level 4</h4>
    <h5>This is a Heading level 5</h5>
    <h6>This is a Heading level 6</h6>

    <p>This is a paragraph of text, Here's a <a href="https://www.example.com">link</a> to an example website</p>

    <ul>
        <li>Unordered List 1</li>
        <li>Unordered List 2</li>
        <li>Unordered List 3</li>
    </ul>

    <ol>
        <li>Ordered List 1</li>
        <li>Ordered List 2</li>
        <li>Ordered List 3</li>
    </ol>

    <h1>Ordered List with Letters</h1>

    <ol type="a">
        <li>First Item
            <ol type="a">
                <li>Subitem 1</li>
                <li>Subitem 2</li>
            </ol>
        </li>
        <li>Second Item
            <ol type="a">
                <li>Subitem 1</li>
                <li>Subitem 2</li>
            </ol>
        </li>
        <li>Third Item</li>
    </ol>

    <img src="https://via.placeholder.com/150" alt="Placeholder Image">


    <h1>Advance HTML tables</h1>

    <table>
        <caption>Students Information</caption>
        <thead>
            <tr>
                <th>Name</th>
                <th>Age</th>
                <th>City</th>
                <th>Course</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>shreyansh saxena</td>
                <td>20</td>
                <td>Shivpuri</td>
                <td>Btech CS</td>
            </tr>
            <tr>
                <td>Nithin Kotala</td>
                <td>19</td>
                <td>Chennai</td>
                <td>Mtech CS</td>
            </tr>
            <tr>
                <td>Arpit Kumar</td>
                <td>20</td>
                <td>Lucknow</td>
                <td>BCA</td>
            </tr>
        </tbody>
        <tfoot>
            <tr>
                <td colspan="4">Total Students: 3</td>
            </tr>
        </tfoot>
    </table>

    <form>
        <label for="fname">First Name</label><br>
        <input type="text" id="fname" name="fname"><br>
        <label for="lname">Last Name</label><br>
        <input type="text" id="lname" name="lname"><br>
        <input type="submit" value="Submit">
    </form>
    
</body>
</html>
```
