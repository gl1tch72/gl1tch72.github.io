<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <link rel="stylesheet" href="styles.css">
    <script>
        function toggleDetails() {
            const details = document.getElementById('details');
            const button = document.getElementById('toggleButton');
            if (details.style.display === 'none') {
                details.style.display = 'block';
                button.textContent = 'Hide Details';
            } else {
                details.style.display = 'none';
                button.textContent = 'Show Details';
            }
        }
    </script>
</head>
<body>
    <header>
        <h1>Welcome to My Portfolio</h1>
        <nav>
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>
    <section id="about">
        <h2>About Me</h2>
        <button id="toggleButton" onclick="toggleDetails()">Show Details</button>
        <div id="details" style="display: none;">
            <p>Introduce yourself and highlight your skills and experience here.</p>
        </div>
    </section>
    <section id="projects">
        <h2>Projects</h2>
        <div class="project">
            <h3>Project Title</h3>
            <p>Project description goes here. Talk about what you did, technologies used, and any other relevant details.</p>
        </div>
    </section>
    <section id="contact">
        <h2>Contact</h2>
        <p>Feel free to reach out to me via email at <a href="mailto:youremail@example.com">youremail@example.com</a>.</p>
    </section>
    <footer>
        <p>&copy; 2024 Your Name. All rights reserved.</p>
    </footer>
</body>
</html>
