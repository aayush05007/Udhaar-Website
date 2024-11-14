# Udhaar-Website
credit management 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Udhaar Management Company</title>
    <link rel="stylesheet" href="css/styles.css">
</head>
<body>
    <!-- Header and Navigation -->
    <header>
        <nav>
            <a href="#" class="logo">Udhaar</a>
            <ul>
                <li><a href="#about">About Us</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#how-it-works">How It Works</a></li>
                <li><a href="#pricing">Pricing</a></li>
                <li><a href="#blog">Blog</a></li>
                <li><a href="#contact">Contact Us</a></li>
            </ul>
            <button class="cta-button">Get Started</button>
        </nav>
    </header>

   <!-- Main Banner -->
<section class="banner">
    <h1>Effortless Credit Management for Modern Businesses</h1>
    <p>Track, manage, and recover credits with ease.</p>
    <button class="cta-button">Get Started</button>
</section>

<!-- About Us Section -->
<section id="about" class="about">
    <h2>About Us</h2>
    <p>Our mission is to provide reliable credit management solutions to empower businesses and streamline finances.</p>
</section>

<!-- Services Section -->
<section id="services" class="services">
    <h2>Our Services</h2>
    <ul>
        <li>Udhaar Management</li>
        <li>Credit Recovery</li>
        <li>Reports & Analytics</li>
        <li>Custom Integrations</li>
    </ul>
</section>

<!-- How It Works Section -->
<section id="how-it-works" class="how-it-works">
    <h2>How It Works</h2>
    <div class="steps">
        <div class="step"><h3>1. Sign Up</h3><p>Register your business to get started.</p></div>
        <div class="step"><h3>2. Record Transactions</h3><p>Track udhaar records effortlessly.</p></div>
        <div class="step"><h3>3. Set Reminders</h3><p>Never miss repayments with automatic reminders.</p></div>
        <div class="step"><h3>4. Access Reports</h3><p>Get insights and analytics anytime.</p></div>
    </div>
</section>

<!-- Pricing Section -->
<section id="pricing" class="pricing">
    <h2>Pricing</h2>
    <p>Choose a plan that suits your needs.</p>
    <!-- Sample pricing tiers -->
    <div class="pricing-tiers">
        <div class="tier">Basic Plan</div>
        <div class="tier">Premium Plan</div>
    </div>
</section>

<!-- Blog Section -->
<section id="blog" class="blog">
    <h2>Blog & Resources</h2>
    <p>Learn more about credit management and financial insights.</p>
</section>

<!-- Contact Section -->
<section id="contact" class="contact">
    <h2>Contact Us</h2>
    <form>
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" required>
        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required>
        <label for="message">Message:</label>
        <textarea id="message" name="message" required></textarea>
        <button type="submit">Send</button>
    </form>
</section>

<script src="js/script.js"></script> 
/* Reset and Basic Styling */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    color: #333;
    background-color: #f7f9fc;
}

/* Header and Navigation */
header {
    background-color: #0073e6;
    padding: 1rem;
}

header nav {
    display: flex;
    align-items: center;
    justify-content: space-between;
}

header nav .logo {
    color: #fff;
    font-size: 1.5rem;
    font-weight: bold;
}

header nav ul {
    list-style: none;
    display: flex;
}

header nav ul li {
    margin-left: 1.5rem;
}

header nav ul li a, .cta-button {
    color: #fff;
    text-decoration: none;
    padding: 0.5rem 1rem;
}

.cta-button {
    background-color: #0091ff;
    border: none;
    cursor: pointer;
}

.banner {
    background: linear-gradient(to right, #0073e6, #0091ff);
    color: #fff;
    text-align: center;
    padding: 3rem 1rem;
}

section {
    padding: 2rem;
    text-align: center;
}

.about, .services, .how-it-works, .pricing, .blog, .contact {
    margin-top: 2rem;
    padding: 1rem;
    border-top: 1px solid #ddd;
}

/* Contact Form */
form {
    display: flex;
    flex-direction: column;
    max-width: 400px;
    margin: 0 auto;
}

form label, form input, form textarea {
    margin-top: 1rem;
}

button[type="submit"] {
    margin-top: 1rem;
    padding: 0.5rem;
    background-color: #0073e6;
    color: #fff;
    border: none;
    cursor: pointer;
}
