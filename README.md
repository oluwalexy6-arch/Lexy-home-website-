<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Lexy Home of Interior Design</title>
<style>
    /* Reset and base styles */
    * { margin:0; padding:0; box-sizing:border-box; font-family: 'Arial', sans-serif; }
    body { background-color: #000; color: #fff; line-height:1.6; }
    a { color: #d4af37; text-decoration:none; }
    a:hover { text-decoration: underline; }
    header { background-color: #111; padding: 20px 50px; display:flex; justify-content:space-between; align-items:center; }
    header h1 { color: #d4af37; }
    nav a { margin-left:20px; font-weight:bold; }
    section { padding: 60px 50px; }
    .hero { text-align:center; padding: 100px 20px; background: linear-gradient(rgba(0,0,0,0.6), rgba(0,0,0,0.6)), url('https://via.placeholder.com/1500x800') center/cover no-repeat; }
    .hero h2 { font-size: 3em; color: #d4af37; margin-bottom:20px; }
    .hero p { font-size:1.2em; color:#fff; margin-bottom:40px; }
    .btn { background-color:#d4af37; color:#000; padding:15px 30px; font-weight:bold; border:none; cursor:pointer; transition: 0.3s; }
    .btn:hover { background-color:#b5942f; }
    .about, .services, .portfolio, .contact { max-width:1200px; margin:0 auto; }
    .portfolio-grid { display:grid; grid-template-columns: repeat(auto-fit, minmax(300px,1fr)); gap:20px; }
    .portfolio-item { position:relative; overflow:hidden; border-radius:10px; }
    .portfolio-item img { width:100%; height:auto; display:block; transition: 0.3s; }
    .portfolio-item:hover img { transform: scale(1.1); }
    .portfolio-item div { position:absolute; bottom:0; background:rgba(0,0,0,0.7); width:100%; text-align:center; padding:10px; }
    form { display:flex; flex-direction:column; gap:15px; max-width:500px; margin:auto; }
    input, textarea { padding:10px; border-radius:5px; border:none; }
    button { cursor:pointer; }
    footer { text-align:center; padding:20px; background-color:#111; color:#d4af37; }
</style>
</head>
<body>

<header>
    <h1>Lexy Home</h1>
    <nav>
        <a href="#about">About</a>
        <a href="#portfolio">Portfolio</a>
        <a href="#services">Services</a>
        <a href="#contact">Contact</a>
    </nav>
</header>

<section class="hero">
    <h2>Elegant Interior Designs</h2>
    <p>Transforming spaces into luxury experiences. Discover the art of home design with Lexy Home.</p>
    <button class="btn" onclick="document.getElementById('contact').scrollIntoView({behavior:'smooth'})">Book a Consultation</button>
</section>

<section class="about" id="about">
    <h2>About Us</h2>
    <p>Founded by <strong>Olawale Isiaka Taiwo</strong>, CEO of Lexy Home of Interior Design, we specialize in bespoke interior design solutions that elevate your living spaces. Our mission is to blend functionality with elegance, delivering exceptional designs for every client.</p>
</section>

<section class="services" id="services">
    <h2>Our Services</h2>
    <ul>
        <li>Residential Interior Design</li>
        <li>Commercial Interior Design</li>
        <li>Space Planning & Consultation</li>
        <li>Custom Furniture Design</li>
        <li>Color & Material Selection</li>
    </ul>
</section>

<section class="portfolio" id="portfolio">
    <h2>Our Portfolio</h2>
    <div class="portfolio-grid">
        <div class="portfolio-item">
            <img src="https://via.placeholder.com/400x300" alt="Project 1">
            <div>Luxury Living Room</div>
        </div>
        <div class="portfolio-item">
            <img src="https://via.placeholder.com/400x300" alt="Project 2">
            <div>Modern Bedroom</div>
        </div>
        <div class="portfolio-item">
            <img src="https://via.placeholder.com/400x300" alt="Project 3">
            <div>Elegant Kitchen</div>
        </div>
        <div class="portfolio-item">
            <img src="https://via.placeholder.com/400x300" alt="Project 4">
            <div>Office Space Design</div>
        </div>
    </div>
</section>

<section class="contact" id="contact">
    <h2>Contact Us</h2>
    <form>
        <input type="text" placeholder="Your Name" required>
        <input type="email" placeholder="Your Email" required>
        <textarea placeholder="Your Message" rows="5" required></textarea>
        <button class="btn" type="submit">Send Message</button>
    </form>
    <p style="text-align:center; margin-top:20px;">Scan QR code to visit our portfolio: <strong>[QR Code Placeholder]</strong></p>
</section>

<footer>
    &copy; 2025 Lexy Home of Interior Design. All Rights Reserved.
</footer>

</body>
</html>
