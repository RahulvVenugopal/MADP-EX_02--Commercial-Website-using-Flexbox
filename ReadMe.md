# Ex02 Commercial Website
## Date:11/08/2025

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
    <title>My Portfolio</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <header>
        <nav>
            <div class="logo">Portfolio</span></div>
            <ul class="nav-links">
                <li><a href="#intro">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

   
    <section id="intro" class="hero">
        <h1>Hi, I'm <span>Rahul</span></h1>
        <p>I am a passionate Web Developer eager to create impactful and beautiful designs.</p>
        <a href="#projects" class="btn">View Projects</a>
    </section>

    <section id="about" class="about">
        <h2>About Me</h2>
        <p>
            Hi! I'm a web developer with skills in <span>HTML</span>, <span>CSS</span>, and <span>JavaScript</span>. 
            I love creating interactive and user-friendly websites.Making code that’s easy to use and nice to see.


        </p>
    </section>

    <section id="projects" class="projects">
        <h2>Projects</h2>
        <div class="project-container">
            <div class="project-box">
                <h3>Movie app</h3>
                <p>A website about movie updates implemented using html and css.</p>
                <a href="#" class="btn">View Project</a>
            </div>
            <div class="project-box">
                
                <h3>Grocery app</h3>
                <p>A website for a simple grocery shop to calculate price</p>
                <a href="#" class="btn">View Project</a>
            </div>
            
        </div>
    </section>

    <section id="contact" class="contact">
        <h2>Contact Me</h2>
        <p><i class="fas fa-envelope"></i> Email: rahul@example.com</p>
        <p><i class="fas fa-phone-alt"></i> Phone: +123 456 789</p>
        <p><i class="fab fa-linkedin"></i> <a href="#">LinkedIn</a></p>
        <p><i class="fab fa-github"></i> <a href="#">GitHub</a></p>
    </section>
<footer>
        <p>&copy; Rahul V 212223040163</p>
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
<img width="1897" height="1035" alt="Screenshot 2025-08-10 233319" src="https://github.com/user-attachments/assets/43df6300-94b1-429f-97dc-b9b6b12bd9fc" />


## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
