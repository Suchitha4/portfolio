# portfolio.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

    <!-- Header Section (Introduction) -->
    <header class="intro">
        <img src="profile.jpg" alt="Profile Picture" class="profile-img">
        <h1>Hi, I'm John Doe</h1>
        <p>Web Developer | Designer | Problem Solver</p>
    </header>

    <!-- About Me Section -->
    <section class="about">
        <h2>About Me</h2>
        <p>I am a passionate web developer with a love for creating beautiful and functional websites. With a background in design and programming, I aim to build intuitive and responsive web experiences.</p>
    </section>

    <!-- Skills Section -->
    <section class="skills">
        <h2>Skills</h2>
        <ul>
            <li>HTML5</li>
            <li>CSS3</li>
            <li>JavaScript</li>
            <li>React</li>
            <li>Node.js</li>
            <li>Git & GitHub</li>
        </ul>
    </section>

    <!-- Projects Section -->
    <section class="projects">
        <h2>Projects</h2>
        <div class="project-card">
            <h3>Project 1: Portfolio Website</h3>
            <p>A responsive portfolio website to showcase my skills and projects.</p>
        </div>
        <div class="project-card">
            <h3>Project 2: Task Manager App</h3>
            <p>A simple app to manage tasks with real-time updates and a clean UI.</p>
        </div>
    </section>

    <!-- Contact Section -->
    <section class="contact">
        <h2>Contact Me</h2>
        <p>If you'd like to get in touch, feel free to email me at <a href="mailto:johndoe@example.com">johndoe@example.com</a></p>
    </section>

    <!-- Footer Section -->
    <footer>
        <p>&copy; 2024 John Doe. All Rights Reserved.</p>
    </footer>

</body>
</html>


# portfolio.css
/* General Reset */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

/* Body Styling */
body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f4;
    color: #333;
    line-height: 1.6;
}

/* Header Styling */
header {
    background-color: #333;
    color: white;
    padding: 15px 0;
}

header nav ul {
    list-style: none;
    text-align: center;
}

header nav ul li {
    display: inline;
    margin: 0 20px;
}

header nav ul li a {
    color: white;
    text-decoration: none;
    font-weight: bold;
}

/* Hero Section */
.hero {
    background-color: #5c6bc0;
    color: white;
    padding: 80px 0;
    text-align: center;
}

.hero h1 {
    font-size: 2.5rem;
}

.hero p {
    font-size: 1.2rem;
    margin: 20px 0;
}

.hero button {
    background-color: #ff4081;
    color: white;
    padding: 10px 20px;
    border: none;
    font-size: 1rem;
    cursor: pointer;
    transition: background-color 0.3s ease;
}

.hero button:hover {
    background-color: #f50057;
}

/* Features Section */
.features {
    display: flex;
    justify-content: space-around;
    margin: 50px 0;
    padding: 0 20px;
}

.feature-box {
    background-color: white;
    border: 1px solid #ddd;
    padding: 20px;
    width: 30%;
    text-align: center;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    margin: 10px 0;
}

.feature-box h2 {
    color: #5c6bc0;
}

.feature-box p {
    color: #666;
}

/* Footer Styling */
footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 15px 0;
}

footer p {
    font-size: 0.9rem;
}

/* Responsive Styles for Mobile Devices */
@media (max-width: 768px) {
    .features {
        flex-direction: column;
        align-items: center;
    }

    .feature-box {
        width: 80%;
        margin-bottom: 20px;
    }

    .hero h1 {
        font-size: 2rem;
    }

    .hero p {
        font-size: 1rem;
    }

    .hero button {
        font-size: 0.9rem;
    }
}
