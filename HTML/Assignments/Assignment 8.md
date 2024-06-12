```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Country Selector</title>
    <style>
        #countrySelect {
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
    </style>
</head>

<body>
    <h2>Select Countries: </h2>
    <select id="countrySelect" on
        onchange="this.nextElementSibling.innerHTML += <li> + this.option[this.selectedIndex].text + </li>; this.option[this.selectedIndex].disabled = true; ">
        <option value="" disabled selected>Select a country</option>
        <option value="">India</option>
        <option value="">USA</option>
        <option value="">China</option>
        <option value="">UK</option>
        <option value="">Australia</option>
    </select>
</body>

</html>
```
