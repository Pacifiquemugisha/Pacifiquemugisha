
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mugisha Pacifique | Portfolio</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="#about">About Me</a></li>
                <li><a href="#skills">Skills</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="about" class="dark-bg">
        <h1>Mugisha Pacifique</h1>
        <p>Statistician | Data Analyst | Policy Support</p>
        <img src="profile.jpg" alt="Profile photo">
        <p>Hello! I'm Mugisha Pacifique, a passionate statistician with a knack for data analysis and policy support. I love traveling, singing, and playing the piano in my spare time. Welcome to my portfolio!</p>
    </section>

    <section id="skills" class="light-bg">
        <h2>Skills</h2>
        <ul>
            <li>Data Analysis in R</li>
            <li>Microsoft Office Suite</li>
            <li>Leadership</li>
            <li>Community Engagement</li>
            <li>Fluency in English, French, and Kiswahili</li>
        </ul>
    </section>

    <section id="projects" class="dark-bg">
        <h2>Projects</h2>
        <div class="project">
            <h3>Project Name 1</h3>
            <p>Brief description of the project.</p>
        </div>
        <div class="project">
            <h3>Project Name 2</h3>
            <p>Brief description of the project.</p>
        </div>
        <!-- Add more projects as needed -->
    </section>

    <section id="contact" class="light-bg">
        <h2>Contact Me</h2>
        <p>Email: <a href="mailto:your.email@example.com">your.email@example.com</a></p>
        <p>LinkedIn: <a href="https://www.linkedin.com/in/yourprofile">LinkedIn Profile</a></p>
        <p>GitHub: <a href="https://github.com/yourusername">GitHub Profile</a></p>
    </section>

    /* styles.css */

    body {
        font-family: Arial, sans-serif;
        margin: 0;
        padding: 0;
        background-color: #121212;
        color: #ffffff;
    }
    
    header {
        background-color: #1a1a1a;
        padding: 20px;
        text-align: center;
    }
    
    header nav ul {
        list-style: none;
        margin: 0;
        padding: 0;
    }
    
    header nav ul li {
        display: inline;
        margin: 0 15px;
    }
    
    header nav ul li a {
        text-decoration: none;
        color: #ffffff;
    }
    
    section {
        padding: 50px 20px;
    }
    
    .dark-bg {
        background-color: #1a1a1a;
    }
    
    .light-bg {
        background-color: #2c2c2c;
    }
    
    h1, h2 {
        text-align: center;
    }
    
    img {
        display: block;
        margin: 20px auto;
        border-radius: 50%;
        width: 150px;
        height: 150px;
    }
    
    .project {
        margin-bottom: 20px;
    }
    
    footer {
        background-color: #1a1a1a;
        padding: 10px;
        text-align: center;
    }
    




    <footer>
        <p>&copy; 2024 Mugisha Pacifique</p>
    </footer>
</body>
</html>

