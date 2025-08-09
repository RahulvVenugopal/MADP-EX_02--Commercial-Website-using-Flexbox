# Ex02 Commercial Website
## Date:

## AIM
To create a commercial website using CSS Flexbox.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for Homepage, Products / Services, About Us, Contact Details and User Account.

### STEP 5
Include social media links at the footer with copyright information.

### STEP 6
Define global styles for fonts, colors, and layout.

### STEP 7
Style the header, navigation bar, and sections.

### STEP 8
Use Flexbox for layout design.

### STEP 9
Add hover effects and transitions for interactivity.

### STEP 10
Add Images and Media.

### STEP 11
Use optimized images for a professional look.

### STEP 12
Open the HTML file in a browser to check layout and functionality.

### STEP 13
Fix styling issues and refine content placement.

### STEP 14
Deploy the website.

### STEP 15
Upload to GitHub Pages for free hosting.

## PROGRAM
#### index.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MyShop - Commercial Website</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <div class="logo">Clyro </div>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#products">Products</a></li>
                <li><a href="#about">About Us</a></li>
                <li><a href="#contact">Contact</a></li>
                <li><a href="#account">Account</a></li>
            </ul>
        </nav>
    </header>

    <section id="home" class="hero">
        <h1>Welcome to Clyro </h1>
        <p>Your one-stop destination for quality electronic products.</p>
        <button>Shop Now</button>
    </section>

    <section id="products">
        <h2>Our Products</h2>
        <div class="product-container">
            <div class="product-card">
                <img src="./images/headphone.jpg" alt="Wireless Headphones">
                <h3>Wireless Bluetooth Headphones</h3>
                <p>$59.99</p>
            </div>
            <div class="product-card">
                <img src="./images/watch.jpg" alt="Smartwatch">
                <h3>Smart Fitness Watch</h3>
                <p>$79.99</p>
            </div>
            <div class="product-card">
                <img src="./images/backpack.jpeg" alt="Laptop Bag">
                <h3>Leather Laptop Backpack</h3>
                <p>$45.00</p>
            </div>
            <div class="product-card">
                <img src="./images/mouse.jpg" alt="Gaming Mouse">
                <h3>Gaming Mouse</h3>
                <p>$29.99</p>
            </div>
        </div>
    </section>

    <section id="about">
        <h2>About Us</h2>
         <p>
        At Clyro, we believe technology should not only be functional but also enhance everyday life. 
        Since our founding, our mission has been to bring our customers the best in innovative gadgets 
        and high-quality accessories that make work, play, and communication effortless. 
        From wireless headphones that deliver crystal-clear sound, to smartwatches that keep you 
        connected and motivated, to precision gaming mice that take performance to the next level — 
        we curate products that combine performance, style, and reliability.
    </p>
    </section>

    <section id="contact">
        <h2>Contact Us</h2>
        <p>Email: support@clyro.com</p>
        <p>Phone: +91 9876543210</p>
    </section>

    <section id="account">
        <h2>User Account</h2>
        <p>Login or register to manage your orders and profile.</p>
        <button>Login</button>
        <button>Register</button>
    </section>

    <footer>
        <div class="social">
            <a href="#">Facebook</a> |
            <a href="#">Instagram</a> |
            <a href="#">Twitter</a>
        </div>
        <p>&copy; 2025 Cylro. All Rights Reserved.</p>
    </footer>
</body>
</html>
```
#### style.css
```
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
}

header {
    background: #333;
    color: white;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 1rem 2rem;
}

.logo {
    font-size: 1.5rem;
    font-weight: bold;
}

nav ul {
    list-style: none;
    display: flex;
    gap: 1rem;
}

nav ul li a {
    color: white;
    text-decoration: none;
    padding: 0.5rem;
}

nav ul li a:hover {
    background: lightblue;
    color: black;
    border-radius: 5px;
}

.hero {
    background: lightblue;
    color: black;
    text-align: center;
    padding: 4rem 2rem;
}

.hero button {
    background: #333;
    color: white;
    padding: 0.7rem 1.2rem;
    border: none;
    cursor: pointer;
    margin-top: 1rem;
    font-size: 1rem;
    border-radius: 5px;
}

.hero button:hover {
    background: #1e90ff;
}

#products {
    padding: 2rem;
    background: #f9f9f9;
}

.product-container {
    display: flex;
    gap: 1.5rem;
    justify-content: center;
    flex-wrap: wrap;
}

.product-card {
    background: white;
    padding: 1rem;
    text-align: center;
    flex: 1 1 250px;
    max-width: 250px;
    border: 1px solid #ccc;
    border-radius: 8px;
    transition: transform 0.3s;
}

.product-card:hover {
    transform: scale(1.05);
}

.product-card img {
    max-width: 100%;
    border-radius: 5px;
}

section {
    padding: 2rem;
    text-align: center;
}

section h2 {
    margin-bottom: 1rem;
    color: #333;
}

footer {
    background: #222;
    color: white;
    text-align: center;
    padding: 1rem;
}

footer .social a {
    color: lightblue;
    text-decoration: none;
    margin: 0 0.5rem;
}

footer .social a:hover {
    text-decoration: underline;
}
#account button {
    background: lightblue;
    color: black;
    font-weight: bold;
    padding: 0.5rem 1rem;
    margin: 0.3rem;
    border: 1px solid #ccc;
    border-radius: 5px;
    cursor: pointer;
}

#account button:hover {
    background: #1e90ff;
    color: white;
}
```


## OUTPUT
<img width="1917" height="1133" alt="image" src="https://github.com/user-attachments/assets/11648af0-8388-4509-aafd-7f6f7bc84209" />
<img width="1919" height="1091" alt="Screenshot 2025-08-10 002317" src="https://github.com/user-attachments/assets/0287f34b-4c98-4f7f-9500-478d9a9c2573" />

## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
