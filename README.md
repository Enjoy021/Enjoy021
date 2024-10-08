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
    <header class="intro">
        <img src="profile-image.jpg" alt="Vincent Ho" class="profile-img">
        <h1>Hi, I'm Vincent Ho</h1>
        <p>A passionate Sports Management | Digital Marketing | Streaming Operator</p>
        <ul class="social-links">
            <li><a href="https://www.linkedin.com/in/vincent-ho-00788b176" target="_blank">LinkedIn</a></li>
            <li><a href="https://www.instagram.com/wuipok/" target="_blank">Instagram</a></li>
            <li><a href="https://www.instagram.com/hkeapl/" target="_blank">EAPL Instagram</a></li>
            <li><a href="https://eapl-league.com/" target="_blank">EAPL Website</a></li>
            <li><a href="https://drive.google.com/drive/folders/1YfrQPQ3bY9lHuuEHsg3QmLS0bmDoiMoV?usp=sharing" target="_blank">My Portfolio</a></li>
        </ul>
    </header>

    <!-- About Section -->
    <section id="about" class="fade-in">
        <h2>About Me</h2>
        <p>I'm a dedicated sports management professional with experience in digital marketing, streaming, and game day operations.</p>
    </section>

    <!-- Projects Section -->
    <section id="projects" class="fade-in">
        <h2>Projects</h2>
        <div class="project">
            <h3>East Asia Pro-Am League</h3>
            <p>Founder of an e-sports league with a 200% reach increase across multiple social platforms.</p>
            <a href="https://eapl-league.com/" target="_blank" class="btn">View Project</a>
        </div>
        <div class="project">
            <h3>Streaming Assistant - NBL</h3>
            <p>Implemented LiveU streaming and managed live scores for NBL games.</p>
            <a href="https://github.com/project-link" target="_blank" class="btn">View Project</a>
        </div>
    </section>

    <!-- GitHub Stats Section -->
    <section id="stats" class="fade-in">
        <h2>GitHub Stats</h2>
        <img src="https://github-readme-stats.vercel.app/api?username=Enjoy021&show_icons=true&theme=dark" alt="Vincent's GitHub Stats">
    </section>

    <!-- Footer -->
    <footer>
        <p>© 2024 Vincent Ho</p>
    </footer>

    <script>
        // Simple fade-in effect for elements
        window.addEventListener('load', function() {
            const elements = document.querySelectorAll('.fade-in');
            elements.forEach(el => el.classList.add('visible'));
        });
    </script>
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
    overflow-x: hidden;
}

header {
    margin-bottom: 40px;
    opacity: 0;
    animation: fadeIn 1s forwards;
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
    padding: 10px 20px;
    border-radius: 5px;
    background-color: #ff5722;
    transition: background-color 0.3s ease;
}

.social-links li a:hover {
    background-color: #e64a19;
}

section {
    margin: 40px 0;
    opacity: 0;
    transform: translateY(20px);
    transition: opacity 1s ease, transform 1s ease;
}

section.visible {
    opacity: 1;
    transform: translateY(0);
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

.project a.btn {
    display: inline-block;
    margin-top: 10px;
    padding: 10px 20px;
    background-color: #ff5722;
    color: #fff;
    border-radius: 5px;
    text-decoration: none;
    transition: background-color 0.3s ease;
}

.project a.btn:hover {
    background-color: #e64a19;
}

#stats img {
    margin: 20px auto;
}

footer {
    margin-top: 40px;
    font-size: 0.8em;
    color: #ccc;
}

/* Keyframes for fade-in */
@keyframes fadeIn {
    from {
        opacity: 0;
    }
    to {
        opacity: 1;
    }
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
