<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Software Company</title>
    <style>
        :root {
            --primary-color: #4CAF50; /* Theme primary color */
            --secondary-color: #f0f0f0;
            --text-color: #333;
        }

        body {
            margin: 0;
            font-family: Arial, sans-serif;
            color: var(--text-color);
            background-color: var(--secondary-color);
        }

        header {
            background-color: var(--primary-color);
            padding: 1rem;
            text-align: center;
            color: white;
        }

        nav {
            display: flex;
            justify-content: center;
            gap: 2rem;
            padding: 1rem;
            background-color: #333;
        }

        nav a {
            color: white;
            text-decoration: none;
            font-weight: bold;
        }

        nav a:hover {
            text-decoration: underline;
        }

        .hero {
            text-align: center;
            padding: 2rem;
            background-color: var(--primary-color);
            color: white;
        }

        .hero h1 {
            margin: 0;
            font-size: 3rem;
        }

        .section {
            padding: 2rem;
            text-align: center;
        }

        .section h2 {
            color: var(--primary-color);
        }

        .services {
            display: flex;
            justify-content: center;
            gap: 2rem;
            flex-wrap: wrap;
        }

        .service {
            background: white;
            padding: 1rem;
            border: 1px solid #ddd;
            border-radius: 5px;
            width: 300px;
        }

        footer {
            background-color: var(--primary-color);
            color: white;
            text-align: center;
            padding: 1rem;
        }

        .contact-form {
            max-width: 400px;
            margin: 0 auto;
            text-align: left;
        }

        .contact-form label {
            display: block;
            margin-bottom: 0.5rem;
            font-weight: bold;
        }

        .contact-form input, .contact-form textarea {
            width: 100%;
            padding: 0.5rem;
            margin-bottom: 1rem;
            border: 1px solid #ddd;
            border-radius: 5px;
        }

        .contact-form button {
            background-color: var(--primary-color);
            color: white;
            border: none;
            padding: 0.5rem 1rem;
            cursor: pointer;
            border-radius: 5px;
        }

        .contact-form button:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to Razyan Solution</h1>
        <p>Innovating the future with cutting-edge technology</p>
    </header>

    <nav>
        <a href="#about">About</a>
        <a href="#services">Services</a>
        <a href="#contact">Contact</a>
    </nav>

    <section class="hero">
        <h1>Your Trusted Software Partner</h1>
        <p>Delivering quality and innovation in every line of code.</p>
    </section>

    <section id="about" class="section">
        <h2>About Us</h2>
        <p>We are a team of passionate developers, designers, and problem-solvers dedicated to building software solutions that drive success.</p>
    </section>

    <section id="services" class="section">
        <h2>Our Services</h2>
        <div class="services">
            <div class="service">
                <h3>Web Development</h3>
                <p>Create responsive, modern websites that drive engagement and conversions.</p>
            </div>
            <div class="service">
                <h3>Mobile Apps</h3>
                <p>Build intuitive and robust mobile applications for iOS and Android.</p>
            </div>
            <div class="service">
                <h3>Cloud Solutions</h3>
                <p>Leverage the power of cloud computing to scale your business.</p>
            </div>
        </div>
    </section>

    <section id="contact" class="section">
        <h2>Contact Us</h2>
        <form class="contact-form">
            <label for="name">Name</label>
            <input type="text" id="name" name="name" required>

            <label for="email">Email</label>
            <input type="email" id="email" name="email" required>

            <label for="message">Message</label>
            <textarea id="message" name="message" rows="5" required></textarea>

            <button type="submit">Send</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2024 Razyan Solution contact-9675883000 . All Rights Reserved.</p>
    </footer>
</body>
</html>
