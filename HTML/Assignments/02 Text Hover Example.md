```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Text Hover Example </title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

    <nav class="navbar">
        <ul class="nav-list">
            <li class="nav-item"><a href="#">Home</a></li>
            <li class="nav-item"><a href="#">About</a></li>
        </ul>
    </nav>
    <div class="text-container">
        <p class="hover-text">Nikhil Jain whats to hover over this text to see the effect!</p>
        <p class="hover-text special">Harpreet whats to hover over nth child this text to see the effect!</p>
        <p class="hover-text">Nikhil Jain whats to hover over this text to see the effect!</p>

    </div>
    
</body>
</html>

```


```css
body {
    margin: 0;
    font-family: Arial, Helvetica, sans-serif;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    background-color: #f0f0f0;
}


.text-container {
    text-align: center;
}

.hover-text {
    font-size: 2em;
    color: #333;
    transition: color 0.3s ease, text-shadow 0.3 ease, transform 0.3s ease;
}


.hover-text:hover {
    color: #ff6347;
    text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.2);
    transform: scale(1.1);
}


.hover-text:nth-child(2):hover {
    color: #4682b4;
    text-decoration: underline;
    transform: rotate(-5deg);
}


.nav-list:hover {
    color: #ff6347;

}

```
