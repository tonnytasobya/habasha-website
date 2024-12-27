# habasha-websitedocument.addEventListener("DOMContentLoaded", () => {
    const themeSelect = document.getElementById("theme-select");
    themeSelect.addEventListener("change", (event) => {
        document.body.className = event.target.value;
    });[
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Habasaha Goods Platform</title>
    <link rel="stylesheet" href="styles.css">
    <script defer src="scripts.js"></script>
</head>
<body>
    <header>
        <div class="container">
            <h1>Welcome to Habasaha Goods Platform</h1>
            <p>Your one-stop solution for buying and selling goods with ease.</p>
        </div>
        <div class="theme-toggle">
            <label for="theme-select">Choose Theme:</label>
            <select id="theme-select">
                <option value="default">Default</option>
                <option value="light">Light</option>
                <option value="dark">Dark</option>
                <option value="custom">Custom</option>
            </select>
        </div>
    </header>

    <nav>
        <ul>
            <li><a href="#features">Features</a></li>
            <li><a href="#categories">Categories</a></li>
            <li><a href="#demo">Demo</a></li>
            <li><a href="#contact">Contact Us</a></li>
        </ul>
    </nav>

    <main>
        <section id="features" class="section">
            <h2>Key Features</h2>
            <ul>
                <li>Easy-to-use interface</li>
                <li>Quick registration process</li>
                <li>Secure transactions</li>
                <li>Mobile-friendly design</li>
            </ul>
        </section>

        <section id="categories" class="section">
            <h2>Explore Categories</h2>
            <div class="categories">
                <div class="category">Grains</div>
                <div class="category">Fruits</div>
                <div class="category">Vegetables</div>
                <div class="category">Dairy Products</div>
            </div>
        </section>

        <section id="demo" class="section">
            <h2>Experience the Platform</h2>
            <p>Click the link below to access our demo platform:</p>
            <a href="https://www.habasaha-demo.com" target="_blank" class="button">Visit Demo</a>
        </section>
    </main>

    <footer>
        <div id="contact" class="container">
            <h2>Contact Us</h2>
            <p>Email: support@habasaha.com</p>
            <p>Phone: +256705663790</p>
        </div>
        <p>&copy; 2024 Habasaha Goods Platform. All Rights Reserved.</p>
    </footer>
</body>
</html>
Uploading habasaha_goods_platform_custom.html…]()

});[Uploading 
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Arial, sans-serif;
}

body {
    line-height: 1.6;
    background-color: #f4f4f9;
    color: #333;
}

header {
    background: #007bff;
    color: #fff;
    padding: 20px 10px;
    text-align: center;
}

header h1 {
    font-size: 2.5em;
    margin-bottom: 10px;
}

header p {
    font-size: 1.2em;
}

.theme-toggle {
    margin: 10px 0;
}

nav {
    background: #333;
    color: #fff;
    padding: 10px;
    text-align: center;
}

nav ul {
    list-style: none;
    display: flex;
    justify-content: center;
}

nav ul li {
    margin: 0 15px;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
    font-size: 1.1em;
}

nav ul li a:hover {
    color: #007bff;
}

.section {
    padding: 20px;
    text-align: center;
}

.categories {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    gap: 15px;
    margin-top: 15px;
}

.category {
    background: #007bff;
    color: #fff;
    padding: 15px;
    border-radius: 5px;
    width: 120px;
    text-align: center;
}

.category:hover {
    background: #0056b3;
}

.button {
    display: inline-block;
    background: #007bff;
    color: #fff;
    padding: 10px 20px;
    text-decoration: none;
    border-radius: 5px;
    margin-top: 10px;
}

.button:hover {
    background: #0056b3;
}

footer {
    background: #333;
    color: #fff;
    text-align: center;
    padding: 10px 0;
    margin-top: 20px;
}

/* Light Theme */
body.light {
    background-color: #ffffff;
    color: #000000;
}

header.light {
    background-color: #f4f4f4;
    color: #000000;
}

nav.light {
    background-color: #dddddd;
    color: #000000;
}

.category.light {
    background: #dddddd;
    color: #000000;
}

.category.light:hover {
    background: #bbbbbb;
}

/* Dark Theme */
body.dark {
    background-color: #1e1e1e;
    color: #ffffff;
}

header.dark {
    background-color: #333333;
    color: #ffffff;
}

nav.dark {
    background-color: #444444;
    color: #ffffff;
}

.category.dark {
    background: #444444;
    color: #ffffff;
}

.category.dark:hover {
    background: #555555;
}
styles.css…]()
