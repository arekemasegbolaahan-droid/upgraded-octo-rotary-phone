<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Abu Umar Consultz</title>
<link rel="stylesheet" href="style.css">
</head>

<body>

<header>
    <h1>Abu Umar Consultz</h1>
    <nav>
        <a href="#">Home</a>
        <a href="#about">About</a>
        <a href="#services">Services</a>
        <a href="#projects">Projects</a>
        <a href="#contact">Contact</a>
    </nav>
</header>

<section class="hero">
    <h2>Building Your Dream Projects</h2>
    <p>Professional Construction & Design Services</p>
    <a href="#contact" class="btn">Request a Quote</a>
</section>

<section id="about">
    <h2>About Us</h2>
    <p>
        Abu Umar Consultz is a professional construction and design company based in Ibadan, Nigeria.
        We specialize in building design, supervision, and project execution.
    </p>
</section>

<section id="services">
    <h2>Our Services</h2>
    <div class="grid">
        <div>Building Design</div>
        <div>Construction</div>
        <div>Project Supervision</div>
        <div>Cost Estimation (BOQ)</div>
    </div>
</section>

<section id="projects">
    <h2>Our Projects</h2>
    <div class="gallery">
        <img src="images/project1.jpg">
        <img src="images/project2.jpg">
        <img src="images/project3.jpg">
    </div>
</section>

<section id="contact">
    <h2>Contact Us</h2>

    <form>
        <input type="text" placeholder="Your Name" required>
        <input type="email" placeholder="Your Email" required>
        <textarea placeholder="Your Message"></textarea>
        <button type="submit">Send Message</button>
    </form>

    <p>📞 08168070582</p>
    <p>📍 Ibadan, Nigeria</p>

    <a href="https://wa.me/2348168070582" class="whatsapp">Chat on WhatsApp</a>

</section>

<footer>
    <p>© 2026 Abu Umar Consultz. All rights reserved.</p>
</footer>

</body>
</html>


body {
    font-family: Arial, sans-serif;
    margin: 0;
    background: #f5f7fa;
}

header {
    background: #0a3d91;
    color: white;
    padding: 15px;
    text-align: center;
}

nav a {
    color: white;
    margin: 10px;
    text-decoration: none;
    font-weight: bold;
}

.hero {
    background: linear-gradient(rgba(0,0,255,0.6), rgba(0,0,0,0.6)), url('images/bg.jpg');
    color: white;
    text-align: center;
    padding: 100px 20px;
}

.btn {
    background: white;
    color: #0a3d91;
    padding: 10px 20px;
    text-decoration: none;
    border-radius: 5px;
}

section {
    padding: 50px 20px;
    text-align: center;
}

.grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
    gap: 15px;
}

.grid div {
    background: #0a3d91;
    color: white;
    padding: 20px;
    border-radius: 5px;
}

.gallery img {
    width: 30%;
    margin: 10px;
    border-radius: 5px;
}

form input, form textarea {
    width: 80%;
    padding: 10px;
    margin: 10px;
}

button {
    padding: 10px 20px;
    background: #0a3d91;
    color: white;
    border: none;
}

.whatsapp {
    display: inline-block;
    margin-top: 15px;
    color: white;
    background: green;
    padding: 10px 15px;
    text-decoration: none;
}

footer {
    background: #0a3d91;
    color: white;
    padding: 10px;
}
