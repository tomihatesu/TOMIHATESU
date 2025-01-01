<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>My Portfolio</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <nav>
            <h1>My Portfolio</h1>
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#work">Work</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="about">
        <h2>About Me</h2>
        <p>Hello! I'm [Your Name], a passionate individual with a knack for creativity. Explore my portfolio to see my work and achievements.</p>
    </section>

    <section id="work">
        <h2>My Work</h2>
        <div class="portfolio-gallery">
            <div class="item">
                <img src="image1.jpg" alt="Work 1">
                <p>Work 1 Description</p>
            </div>
            <div class="item">
                <img src="image2.jpg" alt="Work 2">
                <p>Work 2 Description</p>
            </div>
            <div class="item">
                <img src="image3.jpg" alt="Work 3">
                <p>Work 3 Description</p>
            </div>
        </div>
    </section>

    <section id="contact">
        <h2>Contact Me</h2>
        <form action="#">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>

            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>

            <label for="message">Message:</label>
            <textarea id="message" name="message" rows="5" required></textarea>

            <button type="submit">Send</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2025 Your Name. All Rights Reserved.</p>
    </footer>
</body>
</html>
