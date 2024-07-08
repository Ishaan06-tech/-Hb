<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>John Doe's Personal Webpage</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 1rem 0;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #444;
        }
        nav a {
            color: #fff;
            padding: 1rem;
            text-decoration: none;
            text-transform: uppercase;
        }
        nav a:hover {
            background-color: #555;
        }
        .container {
            max-width: 1200px;
            margin: 2rem auto;
            padding: 1rem;
        }
        h1, h2 {
            text-align: center;
        }
        .about, .portfolio, .blog, .contact {
            margin-bottom: 2rem;
        }
        .portfolio img {
            max-width: 100%;
            height: auto;
        }
        .contact form {
            display: flex;
            flex-direction: column;
            align-items: center;
        }
        .contact form input, .contact form textarea {
            width: 100%;
            max-width: 500px;
            margin-bottom: 1rem;
            padding: 0.5rem;
            border: 1px solid #ccc;
            border-radius: 4px;
        }
        .contact form button {
            padding: 0.5rem 1rem;
            border: none;
            background-color: #333;
            color: #fff;
            cursor: pointer;
        }
    </style>
</head>
<body>
    <header>
        <h1>John Doe</h1>
        <p>Software Engineer | Tech Innovators Inc.</p>
    </header>
    <nav>
        <a href="#about">About Me</a>
        <a href="#portfolio">Portfolio</a>
        <a href="#blog">Blog</a>
        <a href="#contact">Contact</a>
    </nav>
    <div class="container">
        <section id="about" class="about">
            <h2>About Me</h2>
            <p>John Doe is a software engineer with 10 years of experience in web development. He loves coding, hiking, and photography. He is currently working at Tech Innovators Inc.</p>
        </section>
        <section id="portfolio" class="portfolio">
            <h2>Portfolio</h2>
            <p>Here are some of my recent projects:</p>
            <img src="project1.jpg" alt="Project 1">
            <img src="project2.jpg" alt="Project 2">
            <img src="project3.jpg" alt="Project 3">
        </section>
        <section id="blog" class="blog">
            <h2>Blog</h2>
            <p>Coming soon...</p>
        </section>
        <section id="contact" class="contact">
            <h2>Contact</h2>
            <form>
                <input type="text" name="name" placeholder="Your Name" required>
                <input type="email" name="email" placeholder="Your Email" required>
                <textarea name="message" rows="5" placeholder="Your Message" required></textarea>
                <button type="submit">Send</button>
            </form>
        </section>
    </div>
</body>
</html>
