# Ex.07 Restaurant Website
## Date:07-12-2024

## AIM:
To develop a static Restaurant website to display the food items and services provided by them.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:

index.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TALK BITES</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="logo">
            <h1>TALK BITES</h1>
            <div class="doodle">🍴</div>
        </div>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#menu">Menu</a></li>
                <li><a href="#contact">Contact Us</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section id="home">
            <h2>Welcome to TALK BITES</h2>
            <p>Your favorite spot for delicious bites and endless conversations!</p>
        </section>

        <section id="links">
            <h2>Quick Links</h2>
            <ul>
                <li><a href="menu.html">View Menu</a></li>
                <li><a href="booking.html">Book a Table</a></li>
                <li><a href="hours.html">Opening Hours</a></li>
            </ul>
        </section>
    </main>

    <footer>
        <p>WEBSITE BY NANDA KISHOR S P(24011485)</p>
    </footer>
</body>
</html>

```

styles.css
```
body, h1, h2, p, ul, li, a {
    margin: 0;
    padding: 0;
    text-decoration: none;
    list-style: none;
    font-family: 'Arial', sans-serif;
}

body {
    background: linear-gradient(to bottom right, peachpuff, lightcoral);
    color: black;
    line-height: 1.6;
    padding: 0 20px;
}

header {
    text-align: center;
    margin-top: 30px;
    padding: 20px;
}

.logo h1 {
    font-size: 3em;
    color: darkslategray;
    text-shadow: 2px 2px tomato;
}

.doodle {
    font-size: 2.5em;
    margin-top: 5px;
    color: salmon;
}

nav ul {
    display: flex;
    justify-content: center;
    gap: 20px;
    margin-top: 20px;
}

nav ul li a {
    color: white;
    font-weight: bold;
    font-size: 1.2em;
    background-color: tomato;
    padding: 10px 15px;
    border-radius: 25px;
    transition: transform 0.3s ease, background-color 0.3s ease;
}

nav ul li a:hover {
    background-color: coral;
    transform: scale(1.1);
}

main {
    text-align: center;
    margin-top: 40px;
}

main h2 {
    color: dimgray;
    font-size: 2em;
    margin-bottom: 20px;
}

main p {
    color: dimgrey;
    font-size: 1.2em;
    margin-bottom: 30px;
    background: white;
    opacity: 0.8;
    display: inline-block;
    padding: 10px 20px;
    border-radius: 10px;
}

#links ul {
    margin-top: 20px;
}

#links ul li a {
    display: inline-block;
    margin: 10px 0;
    font-size: 1.2em;
    color: white;
    background-color: tomato;
    padding: 8px 12px;
    border-radius: 8px;
    transition: background-color 0.3s ease;
}

#links ul li a:hover {
    background-color: coral;
}

footer {
    text-align: center;
    margin-top: 40px;
    padding: 10px;
    background-color: black;
    color: white;
    border-top: 4px solid tomato;
}
```

## OUTPUT:

![alt text](<Screenshot (67).png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
