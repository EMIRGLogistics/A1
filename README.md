<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Your AI Consultancy | AI Strategy & Automation</title>
<meta name="description" content="AI Strategy, Automation, and Custom AI Solutions for Businesses. Transform your company with intelligent systems.">

<link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">

<style>
:root {
    --primary: #6C63FF;
    --dark: #0f172a;
    --light: #f8fafc;
    --gray: #94a3b8;
}

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Inter', sans-serif;
}

body {
    background: var(--dark);
    color: white;
    line-height: 1.6;
}

.container {
    width: 90%;
    max-width: 1200px;
    margin: auto;
}

header {
    padding: 20px 0;
    position: fixed;
    width: 100%;
    top: 0;
    background: rgba(15, 23, 42, 0.95);
    backdrop-filter: blur(8px);
    z-index: 1000;
}

nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

nav h1 {
    font-size: 1.5rem;
    font-weight: 700;
}

nav ul {
    display: flex;
    list-style: none;
}

nav ul li {
    margin-left: 25px;
}

nav a {
    color: white;
    text-decoration: none;
    font-weight: 500;
}

nav a:hover {
    color: var(--primary);
}

.hero {
    height: 100vh;
    display: flex;
    align-items: center;
    text-align: center;
    padding-top: 80px;
}

.hero h2 {
    font-size: 2.8rem;
    margin-bottom: 20px;
}

.hero p {
    color: var(--gray);
    max-width: 600px;
    margin: auto;
    margin-bottom: 30px;
}

.btn {
    padding: 14px 28px;
    background: var(--primary);
    border: none;
    color: white;
    font-weight: 600;
    border-radius: 6px;
    cursor: pointer;
    text-decoration: none;
    transition: 0.3s ease;
}

.btn:hover {
    opacity: 0.85;
}

section {
    padding: 100px 0;
}

.section-title {
    text-align: center;
    margin-bottom: 60px;
}

.services {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
    gap: 30px;
}

.card {
    background: #1e293b;
    padding: 30px;
    border-radius: 10px;
    transition: 0.3s ease;
}

.card:hover {
    transform: translateY(-5px);
}

.card h3 {
    margin-bottom: 15px;
}

.card p {
    color: var(--gray);
}

.about p {
    max-width: 700px;
    margin: auto;
    color: var(--gray);
    text-align: center;
}

.contact form {
    max-width: 600px;
    margin: auto;
    display: flex;
    flex-direction: column;
}

.contact input, .contact textarea {
    padding: 15px;
    margin-bottom: 15px;
    border-radius: 6px;
    border: none;
    background: #1e293b;
    color: white;
}

.contact button {
    border: none;
}

footer {
    background: #020617;
    text-align: center;
    padding: 30px 0;
    color: var(--gray);
}

@media (max-width: 768px) {
    .hero h2 {
        font-size: 2rem;
    }
}
</style>
</head>

<body>

<header>
<div class="container">
<nav>
<h1>YourAI</h1>
<ul>
<li><a href="#services">Services</a></li>
<li><a href="#about">About</a></li>
<li><a href="#contact">Contact</a></li>
</ul>
</nav>
</div>
</header>

<section class="hero">
<div class="container">
<h2>Transform Your Business With Artificial Intelligence</h2>
<p>We help companies implement AI strategy, automation, and custom machine learning solutions that drive growth and efficiency.</p>
<a href="#contact" class="btn">Book a Free Consultation</a>
</div>
</section>

<section id="services">
<div class="container">
<div class="section-title">
<h2>Our Services</h2>
</div>
<div class="services">
<div class="card">
<h3>AI Strategy Consulting</h3>
<p>Identify high-impact AI opportunities and build a roadmap tailored to your business goals.</p>
</div>
<div class="card">
<h3>Process Automation</h3>
<p>Streamline operations with intelligent automation systems that reduce costs and save time.</p>
</div>
<div class="card">
<h3>Custom AI Solutions</h3>
<p>Deploy machine learning models and AI tools built specifically for your workflows.</p>
</div>
</div>
</div>
</section>

<section id="about" class="about">
<div class="container">
<div class="section-title">
<h2>About Us</h2>
</div>
<p>We are a forward-thinking AI consultancy focused on delivering measurable business outcomes. Our team combines deep technical expertise with strategic insight to help organizations unlock the full power of artificial intelligence.</p>
</div>
</section>

<section id="contact" class="contact">
<div class="container">
<div class="section-title">
<h2>Contact Us</h2>
</div>
<form>
<input type="text" placeholder="Your Name" required>
<input type="email" placeholder="Your Email" required>
<textarea rows="5" placeholder="How can we help?" required></textarea>
<button class="btn">Send Message</button>
</form>
</div>
</section>

<footer>
<p>© 2026 YourAI Consultancy. All rights reserved.</p>
</footer>

</body>
</html>
