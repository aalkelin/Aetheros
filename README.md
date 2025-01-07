<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Aetheros</title>
    <style>
        /* General Reset */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Noto Sans', sans-serif;
            color: #333;
            background-color: #FAF3E0;
            line-height: 1.6;
        }

        header {
            background-color: #F8F5F0;
            padding: 20px 40px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            border-bottom: 1px solid #DDD;
        }

        header nav a {
            text-decoration: none;
            color: #555;
            margin: 0 15px;
            font-size: 1rem;
        }

        header nav a:hover {
            color: #000;
        }

        .hero {
            text-align: center;
            padding: 100px 20px;
            background: linear-gradient(135deg, #EFE9E5, #DAD5D1);
        }

        .hero h1 {
            font-size: 2.5rem;
            font-weight: 700;
            color: #333;
        }

        .hero p {
            font-size: 1.2rem;
            color: #666;
            margin: 20px 0;
        }

        .hero button {
            background-color: #8C7B75;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }

        .hero button:hover {
            background-color: #6F5D54;
        }

        section {
            padding: 60px 20px;
            text-align: center;
        }

        section h2 {
            font-size: 2rem;
            color: #444;
            margin-bottom: 20px;
        }

        .services, .social-media {
            display: flex;
            justify-content: center;
            gap: 30px;
            flex-wrap: wrap;
        }

        .service-item {
            width: 300px;
            padding: 20px;
            background: #FFFFFF;
            border: 1px solid #DDD;
            border-radius: 10px;
            text-align: center;
        }

        .social-media a {
            display: inline-block;
            margin: 0 15px;
            text-decoration: none;
        }

        .social-media img {
            width: 50px;
            height: 50px;
            filter: grayscale(100%);
            transition: filter 0.3s;
        }

        .social-media img:hover {
            filter: grayscale(0%);
        }

        footer {
            background-color: #F8F5F0;
            text-align: center;
            padding: 20px;
            border-top: 1px solid #DDD;
        }

        footer p {
            font-size: 0.9rem;
            color: #777;
        }
    </style>
</head>
<body>
    <header>
        <div class="logo">Aetheros</div>
        <nav>
            <a href="#about">About</a>
            <a href="#services">Services</a>
            <a href="#social-media">Social Media</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <div class="hero">
        <h1>Cultivating Growth, One Insight at a Time</h1>
        <p>Discover how Aetheros blends timeless wisdom with modern insight to foster growth and transformation.</p>
        <button>Learn More</button>
    </div>

    <section id="about">
        <h2>About Aetheros</h2>
        <p>Rooted in Insight, Growing with Purpose. Aetheros combines neuroscience, psychological insights, and strategic thinking to empower meaningful change.</p>
    </section>

    <section id="services">
        <h2>Our Services</h2>
        <div class="services">
            <div class="service-item">
                <h3>Advisory</h3>
                <p>Personalised strategies to cultivate growth and achieve your goals.</p>
            </div>
            <div class="service-item">
                <h3>Lectures</h3>
                <p>Engaging talks on setting boundaries, managing stress, and achieving balance.</p>
            </div>
            <div class="service-item">
                <h3>Content Strategy</h3>
                <p>Expert guidance to refine your digital presence and connect with your audience.</p>
            </div>
        </div>
    </section>

    <section id="social-media">
        <h2>Follow Us on Social Media</h2>
        <div class="social-media">
            <a href="https://www.instagram.com/aetheros.partners/" target="_blank">
                <img src="instagram-logo.png" alt="Instagram Logo">
            </a>
            <a href="https://www.linkedin.com/company/aetheros-partners/" target="_blank">
                <img src="linkedin-logo.png" alt="LinkedIn Logo">
            </a>
        </div>
    </section>

    <section id="contact">
        <h2>Get in Touch</h2>
        <form>
            <input type="text" placeholder="Name" required><br>
            <input type="email" placeholder="Email" required><br>
            <textarea placeholder="Message" required></textarea><br>
            <button type="submit">Submit</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2025 Aetheros. All rights reserved.</p>
    </footer>
</body>
</html>
