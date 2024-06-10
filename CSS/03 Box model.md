```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSS Grid example</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header class="header">
        <h1>Edtech Plateform</h1>
    </header>

    <main>
        <section class="cousre-list">
            <div class="course">
                <h2>Course 1</h2>
                <p>Learn the basics of web development</p>
            </div>
            <div class="course">
                <h2>Course 2</h2>
                <p>Learn the Advanced CSS techniques</p>
            </div>
            <div class="course">
                <h2>Course 3</h2>
                <p>Introduction to python progremming</p>
            </div>
        </section>
    </main>

    <footer class="footer">
        <p>&copy; 2024 Edtech plateform. All rights reserved</p>
    </footer>
</body>
</html>


```



```css
* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
}

body {
    font-family: Arial, Helvetica, sans-serif;
    background-color: #f5f5f5;
    color: #333;
    line-height: 1.6;
}

.header {
    background-color: #4caf50;
    color: white;
    padding: 20px;
    text-align: center;
    margin-bottom: 20px;
}

.cousre-list {
    display: flex;
    justify-content: space-around;
    flex-wrap: wrap;
    padding: 20px;
}


.course {
    background-color: white;
    border: 1px solid #ccc;
    padding: 20px;
    margin: 10px;
    width: 300px;
    border-radius: 5px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

.course h2 {
    margin-bottom: 10px;
    color: #4caf50;
}

.footer {
    background-color: #4caf50;
    color: white;
    text-align: center;
    padding: 10px;
    margin-top: 20px;
}```
