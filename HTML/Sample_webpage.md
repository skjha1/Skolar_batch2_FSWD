```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Attractive webpage</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Welcome to Our website</h1>
        <p>Your one-stop destination for amazing content</p>
    </header>

    <section class="main-content"> 
        <h2>Abous us</h2>
        <p>This is website where you will be getting technical blogs and other technical content on daily basis</p>

        <div class="image-container">
            <img src="https://images.unsplash.com/photo-1575936123452-b67c3203c357?q=80&w=1000&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8Mnx8aW1hZ2V8ZW58MHx8MHx8fDA%3D" alt="Image on the left side" class="image-left">
            <img src="https://buffer.com/library/content/images/size/w1200/2023/10/free-images.jpg" alt="Image in the center" class="image-center">
            <img src="https://images.pexels.com/photos/674010/pexels-photo-674010.jpeg?cs=srgb&dl=pexels-anjana-c-169994-674010.jpg&fm=jpg" alt="Image on the right side" class="image-right">
        </div>

    </section>
    <footer>
        <p>&copy; 2024 our website. All rights reserved.</p>
    </footer>
    
</body>
</html>
```


```css
body {
    font-family: Arial, Helvetica, sans-serif;
    margin: 0; /* Removing the default margin*/
    padding: 0; /* Removing the default padding*/
}
/*
header {
    background-color: #333; 
    color: #fff; 
    padding: 20px; 
    text-align: center;
}
*/
.main-content {
    padding: 20px ;

}

header, footer {
    text-align: center;
    padding: 10px;
    background-color: #f4f4f4;
}
/* 
footer {
    background-color: #333;
    color: #fff;
    padding: 10px;
    text-align: center;

} */

.image-container {
    display: flex;
    justify-content: space-between;
    align-items: center;
    flex-wrap: wrap;
}

.image-container {
    max-width: 30%;
    height: auto;
    margin: 10px;
}

.image-left {
    align-self: flex-start;
    width: 200px;
    height: 100px;
    display: inline-block;
}

.image-center {
    align-self: center;
    width: 500px;
    height: 1000px;
    display: inline-block;
}

.image-right {
    align-self: flex-end;
    width: 200px;
    height: 100px;
    display: inline-block;
}


```
