<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        /* Add styles for the button */
        button {
            display: flex;
            align-items: center;
            border-radius: 15px; /* Smooth edges */
            padding: 10px 20px;
            border: none;
            background-color: #007bff;
            color: white;
            cursor: pointer;
            transition: background-color 0.3s;
        }

        button:hover {
            background-color: #0056b3;
        }

        img.icon {
            width: 20px; /* Adjust the size of the icon */
            height: 20px; 
            margin-right: 10px; /* Space between icon and text */
        }
    </style>
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
        <button id="openUrlButton" onclick="window.open('https://google.com', '_blank')">
            <img src="https://images-ext-1.discordapp.net/external/HdzG-ZWFfGWNBJZsI2yHgi6bUWOAn7Vd7ZT-eW6p3Ds/%3Fsize%3D4096/https/cdn.discordapp.com/icons/935613791058657370/a_17dc9fc956e57cf16f7f7c32b02db4d3.gif?width=655&height=655" alt="Icon" class="icon">
            High Ranking Staff member at NYCRP
        </button>
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
