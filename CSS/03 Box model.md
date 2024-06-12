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


Assignment
```HTML
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

    <nav class="navbar">
        <a href="">Home</a>
        <a href="">Courses</a>
        <a href="">About</a>
        <a href="">Contact</a>
    </nav>

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

    <aside class="sidebar">
        <h3>Upcoming Events</h3>
        <p>Webinar on CSS GRID - 12 June </p>
        <p>Full stack web dev course from june to aug </p>
    </aside>

    <footer class="footer">
        <p>&copy; 2024 Edtech plateform. All rights reserved</p>
    </footer>
</body>
</html>


```


```CSS
/* Universal selector for box-sizing */
* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
  }
  
  /* Body styling */
  body {
    font-family: 'Open Sans', sans-serif;
    background-color: #f5f7fa;
    color: #333;
    line-height: 1.6;
    display: grid;
    grid-template-rows: auto 1fr auto;
    grid-template-columns: 1fr 3fr;
    grid-template-areas:
      "header header"
      "nav main"
      "nav sidebar"
      "footer footer";
    height: 100vh;
    gap: 20px;
    padding: 20px;
  }
  
  /* Header styling */
  .header {
    grid-area: header;
    background-color: #4CAF50;
    color: white;
    padding: 20px;
    text-align: center;
    font-size: 1.8em;
    border-radius: 10px;
  }
  
  /* Navigation bar styling */
  .navbar {
    grid-area: nav;
    background-color: #fff;
    padding: 20px;
    display: flex;
    flex-direction: column;
    gap: 15px;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
  }
  
  .navbar a {
    color: #333;
    text-decoration: none;
    padding: 10px 20px;
    background-color: #e7e9eb;
    border-radius: 5px;
    transition: background-color 0.3s;
  }
  
  .navbar a:hover {
    background-color: #4CAF50;
    color: white;
  }
  
  /* Main content styling */
  .main-content {
    grid-area: main;
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
    gap: 20px;
    padding: 20px;
  }
  
  /* Individual course styling */
  .course {
    background-color: white;
    border: 1px solid #ddd;
    padding: 20px;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    transition: transform 0.3s;
  }
  
  .course:hover {
    transform: translateY(-5px);
  }
  
  .course h2 {
    color: #4CAF50;
    margin-bottom: 10px;
  }
  
  /* Sidebar styling */
  .sidebar {
    grid-area: sidebar;
    background-color: #fff;
    padding: 20px;
    border: 1px solid #ddd;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
  }
  
  .sidebar h3 {
    margin-bottom: 10px;
    color: #4CAF50;
  }
  
  /* Footer styling */
  .footer {
    grid-area: footer;
    background-color: #4CAF50;
    color: white;
    text-align: center;
    padding: 10px;
    border-radius: 10px;
  }
  

```    
