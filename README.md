<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Monee - Empowering Entrepreneurs</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="container">
            <h1>Monee</h1>
            <nav>
                <ul>
                    <li><a href="#about">About</a></li>
                    <li><a href="#services">Services</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section id="hero">
        <div class="container">
            <h2>Empowering Entrepreneurs with AI & UBI</h2>
            <p>Join Monee and start your journey towards financial freedom today.</p>
            <a href="#services" class="btn">Learn More</a>
        </div>
    </section>

    <section id="about">
        <div class="container">
            <h2>About Us</h2>
            <p>Monee is dedicated to reducing income inequality by providing AI-driven support and a Universal Basic Income system to aspiring entrepreneurs. Our platform is designed to help you find your niche, develop your business, and achieve financial stability.</p>
        </div>
    </section>

    <section id="services">
        <div class="container">
            <h2>Our Services</h2>
            <div class="service">
                <h3>AI-Driven Business Matching</h3>
                <p>Get personalized recommendations based on your interests and skills.</p>
            </div>
            <div class="service">
                <h3>Tiered Action Plans</h3>
                <p>Access business mentorship tailored to your experience level.</p>
            </div>
            <div class="service">
                <h3>UBI Support System</h3>
                <p>Receive financial support to kickstart your entrepreneurial journey.</p>
            </div>
        </div>
    </section>

    <section id="contact">
        <div class="container">
            <h2>Contact Us</h2>
            <form id="contactForm">
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required>
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>
                <label for="message">Message:</label>
                <textarea id="message" name="message" required></textarea>
                <button type="submit" class="btn">Submit</button>
            </form>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2024 Monee. All rights reserved.</p>
        </div>
    </footer>

    <script src="script.js"></script>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

header {
    background: #333;
    color: white;
    padding: 10px 0;
}

header .container {
    display: flex;
    justify-content: space-between;
    align-items: center;
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 20px;
}

header h1 {
    margin: 0;
}

header nav ul {
    list-style: none;
    margin: 0;
    padding: 0;
    display: flex;
}

header nav ul li {
    margin-left: 20px;
}

header nav ul li a {
    color: white;
    text-decoration: none;
}

#hero {
    background: #f4f4f4;
    text-align: center;
    padding: 100px 20px;
}

#hero h2 {
    margin: 0 0 20px;
}

#hero p {
    margin: 0 0 20px;
}

#hero .btn {
    background: #333;
    color: white;
    padding: 10px 20px;
    text-decoration: none;
}

#about, #services, #contact {
    padding: 60px 20px;
    background: white;
}

#about h2, #services h2, #contact h2 {
    text-align: center;
    margin-bottom: 40px;
}

#services .service {
    background: #f4f4f4;
    padding: 20px;
    margin-bottom: 20px;
}

#contact form {
    max-width: 600px;
    margin: 0 auto;
}

#contact label {
    display: block;
    margin-bottom: 10px;
}

#contact input, #contact textarea {
    width: 100%;
    padding: 10px;
    margin-bottom: 20px;
}

#contact .btn {
    background: #333;
    color: white;
    padding: 10px 20px;
    border: none;
    cursor: pointer;
}

footer {
    background: #333;
    color: white;
    text-align: center;
    padding: 20px 0;
}
document.getElementById('contactForm').addEventListener('submit', function(e) {
    e.preventDefault();
    alert('Thank you for contacting us. We will get back to you shortly.');
});
