## Dashboard Layout
### HTML
```html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dashboard Layout</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="grid-container">
        <div class="header">Header</div>
        <div class="sidebar">Sidebar</div>
        <div class="main">Main Content</div>
        <div class="widget">Widget 1</div>
        <div class="widget">Widget 2</div>
        <div class="footer">Footer</div>
    </div>
</body>
</html>
```
### CSS
```css
body {
    margin: 0;
    font-family: Arial, Helvetica, sans-serif;
}

.grid-container {
    display: grid;
    grid-template-areas: 
        'header header header'
        'sidebar main main'
        'sidebar widget1 widget2'
        'footer footer footer';
        grid-gap: 10px;
        padding: 10px;
}

.grid-container > div {
    padding: 20px;
    border: 1px solid #ddd;
    text-align: center;

}

.header {
    grid-area: header;
    background-color: #6fa3ef;
}

.sidebar {
    grid-area: sidebar;
    background-color: #ffdb4d;
}

.main {
    grid-area: main;
    background-color: #ff704d;
}

.widget:nth-child(n) {
    grid-area: widget1;
    background-color: #82e0aa;
}


.widget:nth-child(5) {
    grid-area: widget2;
    background-color: #f9ef9f;
}

.footer {
    grid-area: footer;
    background-color: #bfc9ca;
}


@media (max-width: 768px) {
    .grid-container {
        grid-template-areas: 
        'header'
        'sidebar'
        'main'
        'widget1'
        'widget2'
        'footer';
    }
}


```


## Photo Gallery 

### HTML
```html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Photo Gallery</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="gallery">
        <div class="item">1</div>
        <div class="item">2</div>
        <div class="item">3</div>
        <div class="item">4</div>
        <div class="item">5</div>
        <div class="item">6</div>
        <div class="item">7</div>
        <div class="item">8</div>
        <div class="item">9</div>
        <div class="item">10</div>
    </div>
    
</body>
</html>
```
### CSS
```body {
    margin: 0;
    font-family: Arial, Helvetica, sans-serif;
}

.gallery {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(150px, 1fr));
    grid-gap: 10px;
    padding: 10px;
}

.item {
    background-color: #d4e6f1;
    padding: 20px;
    border: 1px solid #b0c4de;
    text-align: center;
    font-size: 24px;
    color: #333;
}

@media (max-width: 600px) {
    .gallery {
        grid-template-columns: repeat(auto-fill, minmax(100px, 1fr)) ;
    }
    .item {
        font-size: 18px;
    }
}


```
