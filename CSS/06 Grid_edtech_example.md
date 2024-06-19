### HTML
```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Edtech grid layout example</title>
    <link rel="stylesheet" href="styles.css">
</head>

<body>
    <header class="header">Edtech Plateform</header>
    <nav class="navbar">
        <a href="#">Home</a>
        <a href="#">Course</a>
        <a href="#">About</a>
        <a href="#">Contact</a>
    </nav>
    <main class="main-content">
        <section class="course">
            <h2>Course 1</h2>
            <p>Learn about basics of web development</p>
        </section>
        <section class="course">
            <h2>Course 2</h2>
            <p>Learn about basics of Java development</p>
        </section>
        <section class="course">
            <h2>Course 3</h2>
            <p>Learn about basics of Javascript development</p>
        </section>
    </main>
        

    <aside class="sidebar">
        <h3>Upcoming Events</h2>
        <p>Webinar on Python - 30 June</p>
        <p>Webinar on CSS grid - 30 Aug</p>
    </aside>

        <footer class="footer">
            &copy; 2024 Edtech plateform. All rights reserved.
        </footer>

    
</body>

</html>

```
### CSS


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
    display: grid;
    grid-template-rows: auto 1fr auto;
    grid-template-columns: 1fr 3fr;
    grid-template-areas: 
    "header header"
    "nav main"
    "nav sidebar"
    "footer footer"
    ;
    height: 100vh;
    gap: 20px;
}

.header {
    grid-area: header;
    background-color: #4caf50;
    color: white;
    padding: 20px;
    text-align: center;
}

.navbar {
    grid-area: nav;
    background-color: #f4f4f4;
    padding: 20px;
    display: flex;
    flex-direction: column;
}

.navbar a {
    color: #333;
    text-decoration: none;
    padding: 10px 0;
    margin-bottom: 10px;
    background-color: #ddd;
    border-radius: 5px;
    text-align: center;
}

.navbar a:hover {
    background-color: #ccc;
}

.main-content {
    grid-area: main;
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
    gap: 20px;
    padding: 20px;
}

.course {
    background-color: white;
    border: 1px solid #ccc;
    padding: 20px;
    border-radius: 5px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

.course h2 {
    color: #4caf50;
    margin-bottom: 10px;
}

.sidebar {
    grid-area: sidebar;
    background-color: #fff;
    padding: 20px;
    border: 1px solid #ccc;
    border-radius: 5px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);

}

.sidebar h3 {
    margin-bottom: 10px;
    color: #4caf50;
}

.footer {
    grid-area: footer;
    background-color: #4caf50;
    color: white;
    text-align: center;
    padding: 10px;
}




```
