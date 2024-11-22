<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Page Title</title>
    <link rel="stylesheet" href="styles.css">
    <link rel="icon" href="path-to-your-icon/icon.png" type="image/png">
    <style>
        button {
            display: flex;
            align-items: center;
            justify-content: center;
            border-radius: 15px;
            padding: 15px 30px;
            border: 2px solid black;
            background-color: white;
            color: black;
            cursor: pointer;
            transition: background-color 0.3s, color 0.3s;
            font-size: 1.2em;
        }

        button:hover {
            background-color: black;
            color: white;
        }

        img.icon {
            width: 30px;
            height: 30px;
            margin-right: 15px;
        }
    </style>
</head>
<body>
    <header>
        <nav></nav>
    </header>
    <section id="about">
        <h2>About Me</h2>
        <button id="openUrlButton" onclick="window.open('https://google.com', '_blank')">
            <img src="https://images-ext-1.discordapp.net/external/HdzG-ZWFfGWNBJZsI2yHgi6bUWOAn7Vd7ZT-eW6p3Ds/%3Fsize%3D4096/https/cdn.discordapp.com/icons/935613791058657370/a_17dc9fc956e57cf16f7f7c32b02db4d3.gif?width=655&height=655" alt="Icon" class="icon">
            Supervisor at New York City Roleplay
        </button>
    </section>
    <footer>
        <p>&copy; 2024 Your Name. All rights reserved.</p>
    </footer>
</body>
</html>
