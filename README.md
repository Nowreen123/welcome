# welcome
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Simple Website</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
        }
        header {
            background-color: #4CAF50;
            color: white;
            text-align: center;
            padding: 1em 0;
        }
        nav {
            margin: 0;
            padding: 0;
            overflow: hidden;
            background-color: #333;
        }
        nav a {
            float: left;
            display: block;
            color: white;
            text-align: center;
            padding: 14px 16px;
            text-decoration: none;
        }
        nav a:hover {
            background-color: #ddd;
            color: black;
        }
        main {
            padding: 1em;
        }
        footer {
            text-align: center;
            padding: 1em;
            background-color: #333;
            color: white;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>

<header>
    <h1>Welcome to My Website</h1>
</header>

<nav>
    <a href="#home">Home</a>
    <a href="#about">About</a>
    <a href="#contact">Contact</a>
</nav>

<main>
    <section id="home">
        <h2>Home</h2>
        <p>This is the home section of the website.</p>
    </section>

    <section id="about">
        <h2>About</h2>
        <p>This is the about section of the website.</p>
    </section>

    <section id="contact">
        <h2>Contact</h2>
        <p>This is the contact section of the website.</p>
    </section>
</main>

<footer>
    <p>&copy; 2024 My Simple Website</p>
</footer>

</body>
</html>
