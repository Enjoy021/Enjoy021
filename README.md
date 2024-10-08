<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Vincent Ho's Portfolio</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <!-- Profile Section -->
    <header>
        <img src="profile-image.jpg" alt="Vincent Ho" class="profile-img">
        <h1>Hi, I'm Vincent Ho</h1>
        <p>A passionate Sports Management | Digital Marketing | Streaming Operator</p>
        <ul class="social-links">
            <li><a href="https://twitter.com">Twitter</a></li>
            <li><a href="https://linkedin.com">LinkedIn</a></li>
            <li><a href="https://github.com">GitHub</a></li>
        </ul>
    </header>
    
    <!-- About Section -->
    <section id="about">
        <h2>About Me</h2>
        <p>I'm a dedicated sports management professional with experience in digital marketing, streaming, and game day operations.</p>
    </section>

    <!-- Projects Section -->
    <section id="projects">
        <h2>Projects</h2>
        <div class="project">
            <h3>East Asia Pro-Am League</h3>
            <p>Founder of an e-sports league with a 200% reach increase across multiple social platforms.</p>
            <a href="https://github.com/project-link">View Project</a>
        </div>
        <div class="project">
            <h3>Streaming Assistant - NBL</h3>
            <p>Implemented LiveU streaming and managed live scores for NBL games.</p>
            <a href="https://github.com/project-link">View Project</a>
        </div>
    </section>

    <!-- GitHub Stats Section -->
    <section id="stats">
        <h2>GitHub Stats</h2>
        <img src="https://github-readme-stats.vercel.app/api?username=yourusername&show_icons=true" alt="GitHub Stats">
    </section>

    <!-- Footer -->
    <footer>
        <p>© 2024 Vincent Ho</p>
    </footer>
</body>
</html>
/* Basic Reset */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Arial', sans-serif;
    background-color: #1a1a1a;
    color: #f1f1f1;
    text-align: center;
    padding: 20px;
}

header {
    margin-bottom: 40px;
}

.profile-img {
    width: 150px;
    height: 150px;
    border-radius: 50%;
    border: 3px solid #fff;
}

h1 {
    font-size: 2.5em;
    margin: 10px 0;
    color: #ff5722;
}

p {
    font-size: 1.2em;
    margin-bottom: 20px;
}

.social-links {
    list-style: none;
    display: flex;
    justify-content: center;
    gap: 10px;
}

.social-links li a {
    color: #f1f1f1;
    text-decoration: none;
    font-size: 1.2em;
}

section {
    margin: 40px 0;
}

h2 {
    font-size: 2em;
    color: #ff5722;
}

.project {
    background-color: #2c2c2c;
    padding: 20px;
    margin: 20px 0;
    border-radius: 10px;
}

.project h3 {
    font-size: 1.5em;
    color: #fff;
}

.project p {
    font-size: 1em;
    color: #ccc;
}

.project a {
    text-decoration: none;
    color: #ff5722;
}

#stats img {
    margin: 20px auto;
}

footer {
    margin-top: 40px;
    font-size: 0.8em;
    color: #ccc;
}

/* Mobile Responsiveness */
@media only screen and (max-width: 600px) {
    body {
        padding: 10px;
    }

    h1 {
        font-size: 2em;
    }

    h2 {
        font-size: 1.5em;
    }
}
<img src="https://github-readme-stats.vercel.app/api?username=Enjoy021&show_icons=true&theme=dark" alt="Vincent's GitHub Stats">
git add .
git commit -m "Updated portfolio with new design and stats"
git push origin main
