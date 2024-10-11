<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Rain's Creative Space</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Welcome to Rain's Creative Space</h1>
        <nav>
            <ul>
                <li><a href="#about">About Me</a></li>
                <li><a href="#interests">Interests</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#blog">Blog</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="about">
        <h2>About Me</h2>
        <p>Hello! I’m Rain, a 20-year-old with a passion for creativity and exploration. My journey has been unique, shaped by my interests in art, music, and the beauty of everyday life.</p>
    </section>

    <section id="interests">
        <h2>My Interests</h2>
        <ul>
            <li>Folk Music</li>
            <li>Art and Design</li>
            <li>Writing and Storytelling</li>
            <li>Nature and Outdoor Activities</li>
            <li>Exploring New Ideas</li>
        </ul>
    </section>

    <section id="projects">
        <h2>My Projects</h2>
        <p>Here are some of the projects I’ve worked on:</p>
        <ul>
            <li><strong>Art Portfolio:</strong> A collection of my artworks showcasing my creative journey.</li>
            <li><strong>Personal Blog:</strong> A blog where I share my thoughts on various topics, from art techniques to personal experiences.</li>
            <li><strong>Music Exploration:</strong> An ongoing project to discover and review folk music from different cultures.</li>
        </ul>
    </section>

    <section id="blog">
        <h2>Blog</h2>
        <p>Check out my latest posts:</p>
        <ul>
            <li><a href="#">The Healing Power of Music</a></li>
            <li><a href="#">Art: A Journey of Self-Discovery</a></li>
            <li><a href="#">My Adventures in Nature</a></li>
        </ul>
    </section>

    <section id="contact">
        <h2>Contact Me</h2>
        <p>If you'd like to get in touch, feel free to fill out the form below:</p>
        <form action="#">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>
            
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            
            <label for="message">Message:</label>
            <textarea id="message" name="message" required></textarea>
            
            <button type="submit">Send Message</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2024 Rain. All rights reserved.</p>
    </footer>
</body>
</html>body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    margin: 0;
    padding: 0;
    background-color: #f0f8ff;
    color: #333;
}

header {
    background: #4682b4;
    color: #ffffff;
    padding: 10px 20px;
    text-align: center;
}

header h1 {
    margin: 0;
}

nav ul {
    list-style: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin-right: 20px;
}

nav ul li a {
    color: #ffffff;
    text-decoration: none;
}

section {
    padding: 20px;
    margin: 10px 0;
    background: #ffffff;
    border: 1px solid #dddddd;
}

footer {
    text-align: center;
    padding: 10px 0;
    background: #4682b4;
    color: #ffffff;
    position: relative;
    bottom: 0;
    width: 100%;
}

form {
    display: flex;
    flex-direction: column;
}

form label {
    margin: 5px 0 2px;
}

form input, form textarea {
    padding: 8px;
    margin-bottom: 10px;
    border: 1px solid #ccc;
    border-radius: 4px;
}

form button {
    padding: 10px;
    background-color: #4682b4;
    color: white;
    border: none;
    border-radius: 4px;
    cursor: pointer;
}

form button:hover {
    background-color: #357ab7;
}
