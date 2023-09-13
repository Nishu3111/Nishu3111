
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>Your Name - Portfolio</title>
</head>
<body>
    <header>
        <h1>Your Name</h1>
        <p>Web Developer</p>
    </header>
    
    <nav>
        <ul>
            <li><a href="#about">About</a></li>
            <li><a href="#projects">Projects</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
    
    <section id="about">
        <h2>About Me</h2>
        <p>Write a brief introduction about yourself here.</p>
    </section>
    
    <section id="projects">
        <h2>Projects</h2>
        <div class="project">
            <h3>Project 1</h3>
            <p>Description of Project 1.</p>
        </div>
        <div class="project">
            <h3>Project 2</h3>
            <p>Description of Project 2.</p>
        </div>
        <!-- Add more project items as needed -->
    </section>
    
    <section id="contact">
        <h2>Contact Me</h2>
        <p>You can reach me at: your.email@example.com</p>
    </section>
    
    <footer>
        <p>&copy; 2023 Your Name</p>
    </footer>
</body>
</html>




/* Reset some default styles */
body, h1, h2, h3, p {
    margin: 0;
    padding: 0;
}

body {
    font-family: Arial, sans-serif;
    background-color: #f0f0f0;
}

header {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 20px;
}

nav ul {
    list-style: none;
    display: flex;
    justify-content: center;
    background-color: #444;
}

nav li {
    margin: 0 20px;
}

nav a {
    text-decoration: none;
    color: #fff;
}

section {
    padding: 40px;
}

.project {
    margin-bottom: 20px;
    background-color: #fff;
    padding: 20px;
    border-radius: 5px;
}

footer {
    text-align: center;
    background-color: #333;
    color: #fff;
    padding: 10px 0;
}

