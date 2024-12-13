<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TechFix - Computer Services</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            line-height: 1.6;
        }
        header {
            background: #333;
            color: #fff;
            padding: 1rem 0;
            text-align: center;
        }
        nav {
            background: #444;
            color: #fff;
            display: flex;
            justify-content: center;
            padding: 0.5rem;
        }
        nav a {
            color: #fff;
            margin: 0 1rem;
            text-decoration: none;
        }
        nav a:hover {
            text-decoration: underline;
        }
        .hero {
            background: url('https://via.placeholder.com/1500x500') no-repeat center center/cover;
            color: #fff;
            text-align: center;
            padding: 3rem 1rem;
        }
        .hero h1 {
            font-size: 2.5rem;
        }
        .services {
            padding: 2rem;
            text-align: center;
        }
        .services h2 {
            margin-bottom: 1rem;
        }
        .services .card {
            display: inline-block;
            margin: 1rem;
            padding: 1rem;
            border: 1px solid #ddd;
            width: 300px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }
        .services .card h3 {
            margin-bottom: 0.5rem;
        }
        .contact {
            background: #f4f4f4;
            padding: 2rem;
            text-align: center;
        }
        .contact h2 {
            margin-bottom: 1rem;
        }
        .contact form input,
        .contact form textarea {
            display: block;
            margin: 0.5rem auto;
            padding: 0.5rem;
            width: 80%;
            max-width: 400px;
        }
        .contact form button {
            padding: 0.5rem 1rem;
            background: #333;
            color: #fff;
            border: none;
            cursor: pointer;
        }
        footer {
            background: #333;
            color: #fff;
            text-align: center;
            padding: 1rem 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>TechFix</h1>
        <p>Your Trusted Computer Repair & Cleaning Service</p>
    </header>
    <nav>
        <a href="#services">Services</a>
        <a href="#contact">Contact</a>
    </nav>
    <section class="hero">
        <h1>Reliable Computer Solutions</h1>
        <p>We Repair, Clean, and Optimize Your Devices</p>
    </section>
    <section id="services" class="services">
        <h2>Our Services</h2>
        <div class="card">
            <h3>PC & Laptop Repairs</h3>
            <p>Quick and reliable repair services for all brands.</p>
        </div>
        <div class="card">
            <h3>Cleaning Services</h3>
            <p>Keep your devices dust-free and running smoothly.</p>
        </div>
        <div class="card">
            <h3>Software Installation</h3>
            <p>Professional software setup and troubleshooting.</p>
        </div>
    </section>
    <section id="contact" class="contact">
        <h2>Contact Us</h2>
        <form>
            <input type="text" placeholder="Your Name" required>
            <input type="email" placeholder="Your Email" required>
            <textarea placeholder="Your Message" rows="5" required></textarea>
            <button type="submit">Send Message</button>
        </form>
    </section>
    <footer>
        <p>© 2024 TechFix. All rights reserved.</p>
    </footer>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TechFix - Computer Services</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            color: white;
            background: url('your-background-image.jpg') no-repeat center center fixed;
            background-size: cover;
        }
        header {
            text-align: center;
            padding: 20px;
            background: rgba(0, 0, 0, 0.6);
        }
        nav {
            display: flex;
            justify-content: center;
            background: rgba(0, 0, 0, 0.8);
            padding: 10px 0;
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-size: 18px;
        }
        nav a:hover {
            text-decoration: underline;
        }
        section {
            padding: 20px;
            background: rgba(0, 0, 0, 0.5);
            margin: 20px auto;
            max-width: 800px;
            border-radius: 10px;
        }
        h1 {
            font-size: 36px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to TechFix</h1>
        <p>Your one-stop solution for computer repairs, cleaning, and quotes</p>
    </header>
    <nav>
        <a href="#services">Services</a>
        <a href="#about">About Us</a>
        <a href="#contact">Contact</a>
    </nav>
    <section id="services">
        <h2>Our Services</h2>
        <ul>
            <li><strong>Repair Service:</strong> Get your laptop or desktop repaired efficiently.</li>
            <li><strong>Cleaning Service:</strong> Professional cleaning for your computer hardware.</li>
            <li><strong>Quotes:</strong> Get a free quote for any of our services.</li>
        </ul>
    </section>
</body>
</html>