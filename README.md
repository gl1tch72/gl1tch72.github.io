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
            justify-content: center;
            border-radius: 15px; /* Smooth edges */
            padding: 15px 30px; /* Increase padding */
            border: none;
            background-color: #007bff;
            color: white;
            cursor: pointer;
            transition: background-color 0.3s;
            font-size: 1.2em; /* Increase font size */
        }

        button:hover {
            background-color: #0056b3;
        }

        img.icon {
            width: 30px; /* Increase size of the icon */
            height: 30px; 
            margin-right: 15px; /* Increase space between icon and text */
        }
    </style>
</head>
<body>
    <header>
        <h1>My Portfolio</h1>
        <nav>
            <ul>
                <li><a href="#about">About</a></li>
            </ul>
        </nav>
    </header>
    <section id="about">
        <h2>About Me</h2>
        <button id="openUrlButton" onclick="window.open('https://google.com', '_blank')">
            <img src="https://images-ext-1.discordapp.net/external/HdzG-ZWFfGWNBJZsI2yHgi6bUWOAn7Vd7ZT-eW6p3Ds/%3Fsize%3D4096/https/cdn.discordapp.com/icons/935613791058657370/a_17dc9fc956e57cf16f7f7c32b02db4d3.gif?width=655&height=655" alt="Icon" class="icon">
            Go to Google
        </button>
    </section>
    <footer>
        <p>&copy; 2024 Your Name. All rights reserved.</p>
    </footer>
</body>
</html>
