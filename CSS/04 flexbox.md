```HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Edtech Flexbox example</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header class="header">
        <h1>Edtech Plateform</h1>
        <nav class="navbar">
            <a href="">Home</a>
            <a href="">Courses</a>
            <a href="">About</a>
            <a href="">Contact</a>
        </nav>
    </header>

    <main class="main-content">
        <section class="course">
            <h2>Course 1</h2>
            <p>Learn the basics of web dev</p>
        </section>
        <section class="course">
            <h2>Course 2</h2>
            <p>Learn the basics of Javascript</p>
        </section>
        <section class="course">
            <h2>Course 3</h2>
            <p>Introduction of python programming</p>
        </section>
    </main>

    <footer class="footer">
        <p>&copy; 2024 Edtech plateform. All rights reserved</p>
    </footer>
</body>
</html>
```



```CSS
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
  display: flex;
  flex-direction: column;
  min-height: 100vh;
}

.header {
  background-color: #4caf50;
  color: white;
  padding: 20px;
  text-align: center;
  display: flex;
  flex-direction: column;
  align-items: center;
}

.navbar {
  display: flex;
  justify-content: space-between;
  width: 100%;
  max-width: 800px;
  margin-top: 10px;
}


.navbar a {
  color: white;
  padding: 10px 20px;
  background-color: #4ca049;
  border-radius: 5px;
  text-decoration: none;
  transition: background-color 0.3s ease;
}

.navbar a:hover {
  background-color: #5cb85c;
}

.main-content {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
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
  color: #4caf50;
  margin-bottom: 10px;
}


.footer {
  background-color: #4caf50;
  color: white;
  text-align: center;
  padding: 10px;
  margin-top: auto;
  position: sticky;
  bottom: 0;
  width: 100%;
}




```
