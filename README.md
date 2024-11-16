# Mayank
/my-website
    /index.html
    /about.html
    /contact.html
    /styles.css
    /scripts.js
    /images/
        logo.png
        background.jpg
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Website</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Welcome to My Website</h1>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section>
            <h2>Introduction</h2>
            <p>This is a basic example of a simple website. Feel free to explore!</p>
        </section>
    </main>

    <footer>
        <p>&copy; 2024 My Website</p>
    </footer>

    <script src="scripts.js"></script>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f4;
    margin: 0;
    padding: 0;
}

header {
    background-color: #333;
    color: white;
    padding: 20px;
    text-align: center;
}

header nav ul {
    list-style-type: none;
    padding: 0;
}

header nav ul li {
    display: inline;
    margin-right: 10px;
}

header nav ul li a {
    color: white;
    text-decoration: none;
}

footer {
    text-align: center;
    padding: 10px;
    background-color: #333;
    color: white;
    position: fixed;
    width: 100%;
    bottom: 0;
}
document.addEventListener("DOMContentLoaded", function() {
    const button = document.createElement("button");
    button.textContent = "Click me!";
    document.body.appendChild(button);

    button.addEventListener("click", function() {
        alert("Hello, welcome to my website!");
    });
});
