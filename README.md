<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Coffee Haven | Artisanal Coffee & Cozy Atmosphere</title>
<link rel="stylesheet" href="styles.css">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
</head>

<body>
<a href="#main-content" class="sr-only">Skip to main content</a>
<header>
<div class="container header-container">
<div class="logo">
<i class="fas fa-coffee"></i>
Coffee <span>Haven</span></div>
<button class="mobile-menu-btn" aria-label="Toggle navigation menu">
<i class="fas fa-bars"></i>
</button>

<ul class="nav-menu">
<li><a href="#home">Home</a></li>
<li><a href="#about">About</a></li>
<li><a href="#menu">Menu</a></li>
<li><a href="#gallery">Gallery</a></li>
<li><a href="#testimonials">Testimonials</a></li>
<li><a href="#contact">Contact</a></li>
</ul></div>
</header>

<section class="hero" id="home">
<div class="container">
<div class="hero-content">
<h1>Artisanal Coffee & Cozy Atmosphere</h1>
<p>Experience the blend of coffee beans skilled baristas and a welcoming environment, at Coffee Haven. We roast our beans every day to guarantee the freshest cup.</p>
<div class="hero-btns">
<a href="#menu" class="btn">View Our Menu</a>
<a href="#contact" class="btn btn-secondary">Visit Us Today</a></div>
</div></div>
</section>

<section class="section" id="about">
<div class="container">
<h2 class="section-title">Our Story</h2>
<div class="about-content">
<div class="about-text">
<p>Founded in 2010 Coffee Haven began as a neighborhood café, driven by a mission: to deliver exceptional coffee in a warm and welcoming atmosphere. Our founders, two coffee enthusiasts committed to quality traveled around the world to source the beans and perfect traditional brewing techniques.</p>
<p>Today we continue that tradition by roasting our beans here and training our baristas to craft each cup with consistency. To us coffee is not merely a beverage—it embodies a moment of comfort, connection and inspiration.</p>
<p>At Coffee Haven we commit to accountability by supporting agricultural practices and giving back to our local community.</p></div>
<div class="about-image">
<img src="https://images.unsplash.com/photo-1554118811-1e0d58224f24?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80" alt="Coffee Haven interior with cozy seating">
</div></div>
<div class="features">
<div class="feature">
<i class="fas fa-seedling"></i>
<h3>Ethically Sourced</h3>
<p>We partner with eco-farms dedicated to trade and environmental stewardship.</p>
</div>
<div class="feature">
<i class="fas fa-fire"></i>
<h3>Freshly Roasted</h3>
<p>We roast our beans daily in batches to ensure the flavor and freshness.</p>
</div>
<div class="feature">
<i class="fas fa-users"></i>
<h3>Community Focused</h3>
<p>We host community. Support local initiatives to strengthen neighborhood connections.</p>
</div>
<div class="feature">
<i class="fas fa-award"></i>
<h3>Award Winning</h3>
<p>Recognized for excellence in coffee quality and customer service by industry experts.</p>
</div></div>
</div>
</section>

<section class="section menu" id="menu">
<div class="container">
<h2 class="section-title">Our Menu</h2>
<div class="menu-tabs">
<button class="tab-btn active" data-category="all">All Items</button>
<button class="tab-btn" data-category="coffee">Coffee</button>
<button class="tab-btn" data-category="tea">Tea</button>
<button class="tab-btn" data-category="food">Food</button>
<button class="tab-btn" data-category="desserts">Desserts</button></div>
<div class="menu-grid" id="menu-items">
    
<div class="menu-item" data-category="coffee">
<img src="https://images.unsplash.com/photo-1511537190424-bbbab87ac5eb?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80" alt="Rich espresso in a small cup">
<div class="menu-item-content">
<h3>Espresso <span class="price">$3.50</span></h3>
<p>Our signature rich and bold espresso, made from single-origin beans.</p></div>
</div>
<div class="menu-item" data-category="coffee">
<img src="https://images.unsplash.com/photo-1561047029-3000c68339ca?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80" alt="Cappuccino with latte art">
<div class="menu-item-content">
<h3>Cappuccino <span class="price">$4.50</span></h3>
<p>Perfectly balanced espresso with steamed milk and a thick layer of foam.</p></div></div>
<div class="menu-item" data-category="coffee">
<img src="https://images.unsplash.com/photo-1572442388796-11668a67e53d?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80" alt="Cold brew coffee in a glass">
<div class="menu-item-content">
<h3>Cold Brew <span class="price">$4.75</span></h3>
<p>Smooth, refreshing cold brew coffee steeped for 18 hours.</p>
</div></div>
<div class="menu-item" data-category="coffee">
<img src="https://images.unsplash.com/photo-1514432324607-a09d9b4aefdd?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80" alt="Latte with beautiful art">
<div class="menu-item-content">
<h3>Vanilla Latte <span class="price">$5.25</span></h3>
<p>Espresso with steamed milk and a touch of vanilla syrup.</p>
</div></div>

<div class="menu-item" data-category="tea">
<img src="https://images.unsplash.com/photo-1556679343-c7306c1976bc?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80" alt="Earl Grey tea in a teacup">
<div class="menu-item-content">
<h3>Earl Grey <span class="price">$3.75</span></h3>
<p>Classic black tea infused with bergamot oil for a fragrant cup.</p>
</div></div>
<div class="menu-item" data-category="tea">
<img src="https://images.unsplash.com/photo-1544787219-7f47ccb76574?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80" alt="Green tea in a glass cup">
<div class="menu-item-content">
<h3>Jasmine Green <span class="price">$3.50</span></h3>
<p>Delicate green tea scented with jasmine flowers for a floral aroma.</p>
</div></div>
<div class="menu-item" data-category="tea">
<img src="https://images.unsplash.com/photo-1571934811356-5cc061b6821f?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80" alt="Chamomile tea">
<div class="menu-item-content">
<h3>Chamomile <span class="price">$3.25</span></h3>
<p>Soothing herbal tea perfect for relaxation and winding down.</p>
</div></div>

<div class="menu-item" data-category="food">
<img src="https://images.unsplash.com/photo-1541519227354-08fa5d50c44d?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80" alt="Avocado toast with toppings">
<div class="menu-item-content">
<h3>Avocado Toast <span class="price">$8.50</span></h3>
<p>Smashed avocado on artisan bread with cherry tomatoes and microgreens.</p>
</div></div>
<div class="menu-item" data-category="food">
<img src="https://images.unsplash.com/photo-1568901346375-23c9450c58cd?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80" alt="Freshly baked croissant">
<div class="menu-item-content">
<h3>Butter Croissant <span class="price">$3.25</span></h3>
<p>Freshly baked, flaky croissant made with European butter.</p>
</div></div>
<div class="menu-item" data-category="food">
<img src="download.jpg" alt="Breakfast sandwich">
<div class="menu-item-content">
<h3>Breakfast Sandwich <span class="price">$7.50</span></h3>
<p>Egg, cheese, and your choice of bacon or sausage on a croissant.</p></div></div>

<div class="menu-item" data-category="desserts">
<img src="https://images.unsplash.com/photo-1578985545062-69928b1d9587?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80" alt="Chocolate cake slice">
<div class="menu-item-content">
<h3>Chocolate Cake <span class="price">$5.50</span></h3>
<p>Rich, moist chocolate cake with ganache frosting.</p>
</div>
</div>
<div class="menu-item" data-category="desserts">
<img src="https://images.unsplash.com/photo-1563729784474-d77dbb933a9e?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80" alt="Blueberry muffin on a plate">
<div class="menu-item-content">
<h3>Blueberry Muffin <span class="price">$3.75</span></h3>
<p>Fresh blueberry-filled homemade muffin.</p></div></div>
<div class="menu-item" data-category="desserts">
<img src="https://images.unsplash.com/photo-1483695028939-5bb13f8648b0?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80" alt="Chocolate chip cookie">
<div class="menu-item-content">
<h3>Chocolate Chip Cookie <span class="price">$2.50</span></h3>
<p>Warm, chewy cookie with melty chocolate chips.</p></div></div>
</div></div>
</section>

<section class="section" id="gallery">
<div class="container">
<h2 class="section-title">Our Space</h2>
<div class="gallery-grid">
<div class="gallery-item">
<img src="https://images.unsplash.com/photo-1554118811-1e0d58224f24?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80" alt="Coffee shop interior with cozy seating">
<div class="gallery-overlay">
<i class="fas fa-search-plus"></i>
</div></div>
<div class="gallery-item">
<img src="https://images.unsplash.com/photo-1442512595331-e89e73853f31?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80" alt="Barista making coffee">
<div class="gallery-overlay">
<i class="fas fa-search-plus"></i></div></div>
<div class="gallery-item">
<img src="https://images.unsplash.com/photo-1501339847302-ac426a4a7cbb?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80" alt="Close-up of coffee beans">
<div class="gallery-overlay">
<i class="fas fa-search-plus"></i></div></div>
<div class="gallery-item">
<img src="https://images.unsplash.com/photo-1495474472287-4d71bcdd2085?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80" alt="Latte art on a cappuccino">
<div class="gallery-overlay">
<i class="fas fa-search-plus"></i>
</div></div>
<div class="gallery-item">
<img src="https://images.unsplash.com/photo-1447933601403-0c6688de566e?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80" alt="Coffee on a wooden table">
<div class="gallery-overlay">
<i class="fas fa-search-plus"></i></div></div>
<div class="gallery-item">
<img src="https://images.unsplash.com/photo-1463797221720-6b07e6426c24?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80" alt="Coffee shop exterior">
<div class="gallery-overlay">
<i class="fas fa-search-plus"></i></div></div>
</div></div>
</section>

<section class="section testimonials" id="testimonials">
<div class="container">
<h2 class="section-title">Customer Testimonials</h2>
<div class="testimonials-container">
<div class="testimonial">
<img src="sj.jpg" alt="Sarah Johnson">
<p text">"The best coffee, in town! I come every day before work begins. The atmosphere is very welcoming. The baristas remember my name and usual order."</p>
<p class="testimonial-author">- Sarah Johnson</p></div>
</div></div>
</section>

<section class="section contact" id="contact">
<div class="container">
<h2 class="section-title">Get In Touch</h2>
<div class="contact-container">
<div class="contact-info">
<div class="contact-details">
<div class="contact-detail">
<i class="fas fa-map-marker-alt"></i>
<p>16 KG 599 Street, Kigali. </p></div>
<div class="contact-detail">
<i class="fas fa-phone"></i>
<p>+250 788 123 456</p></div>
<div class="contact-detail">
<i class="fas fa-envelope"></i>
<p>hello@coffeehaven.com</p></div>
<div class="contact-detail">
<i class="fas fa-clock"></i>
<p>Monday - Friday: 7am - 8pm<br>Saturday - Sunday: 8am - 6pm</p></div></div>
<div class="map">
<img src="https://images.unsplash.com/photo-1554118811-1e0d58224f24?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80" alt="Coffee Haven location">
</div></div>
<div class="contact-form">
<form id="contactForm">
<div class="form-group">
<label for="name">Name</label>
<input type="text" id="name" class="form-control" required></div>
<div class="form-group">
<label for="email">Email</label>
<input type="email" id="email" class="form-control" required></div>
<div class="form-group">
<label for="subject">Subject</label>
<input type="text" id="subject" class="form-control" required></div>
<div class="form-group">
<label for="message">Message</label>
<textarea id="message" class="form-control" required></textarea></div>
<button type="submit" class="btn" id="submitBtn">
<span class="loading" id="formLoading"></span>
Send Message
</button>
</form>
</div>
</div>
</div>
</section>

<footer>
<div class="container">
<div class="footer-content">
<div class="footer-column">
<h3>Coffee Haven</h3>
<p>Your neighborhood destination for exceptional coffee, delicious food, and warm conversation.</p>
<div class="social-links">
<a href="#" aria-label="Facebook"><i class="fab fa-facebook-f"></i></a>
<a href="#" aria-label="Instagram"><i class="fab fa-instagram"></i></a>
<a href="#" aria-label="Twitter"><i class="fab fa-twitter"></i></a></div></div>
<div class="footer-column">
<h3>Quick Links</h3>
<ul class="footer-links">
<li><a href="#home">Home</a></li>
<li><a href="#about">About Us</a></li>
<li><a href="#menu">Menu</a></li>
<li><a href="#gallery">Gallery</a></li>
<li><a href="#contact">Contact</a></li></ul></div>
<div class="footer-column">
<h3>Hours</h3>
<ul class="footer-links">
<li>Monday - Friday: 7am - 8pm</li>
<li>Saturday - Sunday: 8am - 6pm</li>
</ul></div>
<div class="footer-column">
<h3>Newsletter</h3>
<p>Subscribe to our newsletter for updates and special offers.</p>
<form id="newsletterForm">
<div class="form-group">
<input type="email" class="form-control" placeholder="Enter your email" required></div>
<button type="submit" class="btn">Subscribe</button>
</form></div></div>
<div class="copyright">
<p>&copy; 2023 Coffee Haven. All rights reserved.</p></div></div>
</footer>
<div class="modal" id="galleryModal">
<div class="modal-content">
<span class="close-modal">&times;</span>
<img id="modalImage" src="" alt="">
</div></div>
<script src="script.js"></script>
</body></html>

:root {
    --primary-brown: #8B4513;
    --secondary-brown: #A0522D;
    --light-brown: #D2B48C;
    --cream: #F5F5DC;
    --dark-text: #3E2723;
    --light-text: #FFF8E1;
    --accent-green: #2E7D32;
    --shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    --transition: all 0.3s ease;
    --border-radius: 8px;
}
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    line-height: 1.6;
    color: var(--dark-text);
    background-color: var(--cream);
    overflow-x: hidden;
}
h1, h2, h3, h4 {
    font-weight: 600;
    line-height: 1.2;
    margin-bottom: 1rem;
}
p {
    margin-bottom: 1rem;
}
a {
    text-decoration: none;
    color: inherit;
}
img {
    max-width: 100%;
    height: auto;
    display: block;
}
.container {
    width: 90%;
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 15px;
}
.btn {
    display: inline-block;
    background-color: var(--primary-brown);
    color: var(--light-text);
    padding: 12px 24px;
    border: none;
    border-radius: var(--border-radius);
    cursor: pointer;
    font-weight: 600;
    transition: var(--transition);
    text-align: center;
}
.btn:hover {
    background-color: var(--secondary-brown);
    transform: translateY(-2px);
    box-shadow: 0 6px 12px rgba(0, 0, 0, 0.15);
}
.section {
    padding: 80px 0;
}
.section-title {
    text-align: center;
    margin-bottom: 50px;
    position: relative;
}
.section-title::after {
    content: '';
    position: absolute;
    bottom: -10px;
    left: 50%;
    transform: translateX(-50%);
    width: 80px;
    height: 3px;
    background-color: var(--primary-brown);
}
header {
    background-color: var(--primary-brown);
    color: var(--light-text);
    padding: 20px 0;
    position: sticky;
    top: 0;
    z-index: 1000;
    box-shadow: var(--shadow);
}
.header-container {
    display: flex;
    justify-content: space-between;
    align-items: center;
}
.logo {
    font-size: 1.8rem;
    font-weight: 700;
    display: flex;
    align-items: center;
}
.logo i {
    margin-right: 10px;
    color: var(--light-brown);
}
.logo span {
    color: var(--light-brown);
}
.nav-menu {
    display: flex;
    list-style: none;
}
.nav-menu li {
    margin-left: 30px;
}
.nav-menu a {
    font-weight: 500;
    transition: var(--transition);
    position: relative;
}
.nav-menu a::after {
    content: '';
    position: absolute;
    bottom: -5px;
    left: 0;
    width: 0;
    height: 2px;
    background-color: var(--light-brown);
    transition: var(--transition);
}
.nav-menu a:hover::after {
    width: 100%;
}
.nav-menu a:hover {
    color: var(--light-brown);
}
.mobile-menu-btn {
    display: none;
    background: none;
    border: none;
    color: var(--light-text);
    font-size: 1.5rem;
    cursor: pointer;
}
.hero {
    background: linear-gradient(rgba(0, 0, 0, 0.6), rgba(0, 0, 0, 0.6)), 
                url('https://images.unsplash.com/photo-1495474472287-4d71bcdd2085?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80');
    background-size: cover;
    background-position: center;
    background-attachment: fixed;
    color: var(--light-text);
    text-align: center;
    padding: 150px 0;
    position: relative;
}
.hero-content {
    max-width: 800px;
    margin: 0 auto;
    animation: fadeIn 1s ease-out;
}
.hero h1 {
    font-size: 3.5rem;
    margin-bottom: 20px;
    text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
}
.hero p {
    font-size: 1.2rem;
    margin-bottom: 30px;
    text-shadow: 1px 1px 2px rgba(0, 0, 0, 0.5);
}
.hero-btns {
    display: flex;
    justify-content: center;
    gap: 20px;
    flex-wrap: wrap;
}
.btn-secondary {
    background-color: transparent;
    border: 2px solid var(--light-text);
}
.btn-secondary:hover {
    background-color: var(--light-text);
    color: var(--primary-brown);
}
.about-content {
    display: flex;
    align-items: center;
    gap: 50px;
}
.about-text {
    flex: 1;
}
.about-image {
    flex: 1;
    border-radius: var(--border-radius);
    overflow: hidden;
    box-shadow: var(--shadow);
    transition: var(--transition);
}
.about-image:hover {
    transform: scale(1.02);
}
.features {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 30px;
    margin-top: 50px;
}
.feature {
    text-align: center;
    padding: 30px 20px;
    background-color: white;
    border-radius: var(--border-radius);
    box-shadow: var(--shadow);
    transition: var(--transition);
}
.feature:hover {
    transform: translateY(-10px);
}
.feature i {
    font-size: 2.5rem;
    color: var(--primary-brown);
    margin-bottom: 15px;
}
.menu {
    background-color: var(--light-text);
}
.menu-tabs {
    display: flex;
    justify-content: center;
    margin-bottom: 40px;
    flex-wrap: wrap;
    gap: 10px;
}
.tab-btn {
    background: none;
    border: none;
    padding: 10px 20px;
    font-size: 1rem;
    cursor: pointer;
    border-radius: 30px;
    transition: var(--transition);
    font-weight: 500;
    border: 2px solid var(--primary-brown);
}
.tab-btn.active {
    background-color: var(--primary-brown);
    color: var(--light-text);
}
.tab-btn:not(.active) {
    background-color: transparent;
    color: var(--primary-brown);
}
.tab-btn:not(.active):hover {
    background-color: var(--light-brown);
    color: var(--dark-text);
}
.menu-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
    gap: 30px;
}
.menu-item {
    background-color: white;
    border-radius: var(--border-radius);
    overflow: hidden;
    box-shadow: var(--shadow);
    transition: var(--transition);
    opacity: 1;
    transform: scale(1);
}
.menu-item.hidden {
    display: none;
}
.menu-item.fade-out {
    opacity: 0;
    transform: scale(0.9);
}
.menu-item:hover {
    transform: translateY(-5px);
    box-shadow: 0 10px 20px rgba(0, 0, 0, 0.15);
}
.menu-item img {
    width: 100%;
    height: 200px;
    object-fit: cover;
    transition: var(--transition);
}
.menu-item:hover img {
    transform: scale(1.05);
}
.menu-item-content {
    padding: 20px;
}
.menu-item h3 {
    display: flex;
    justify-content: space-between;
    align-items: center;
}
.price {
    color: var(--primary-brown);
    font-weight: 700;
}
.gallery-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
    gap: 15px;
}
.gallery-item {
    border-radius: var(--border-radius);
    overflow: hidden;
    height: 250px;
    position: relative;
    cursor: pointer;
}
.gallery-item img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    transition: var(--transition);
}
.gallery-item:hover img {
    transform: scale(1.05);
}
.gallery-overlay {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: rgba(0, 0, 0, 0.5);
    display: flex;
    justify-content: center;
    align-items: center;
    opacity: 0;
    transition: var(--transition);
}
.gallery-item:hover .gallery-overlay {
    opacity: 1;
}
.gallery-overlay i {
    color: white;
    font-size: 2rem;
}
.testimonials {
    background-color: var(--light-text);
}

.testimonials-container {
    max-width: 800px;
    margin: 0 auto;
    position: relative;
}
.testimonial {
    background-color: white;
    padding: 30px;
    border-radius: var(--border-radius);
    box-shadow: var(--shadow);
    text-align: center;
    margin: 0 20px;
}
.testimonial img {
    width: 80px;
    height: 80px;
    border-radius: 50%;
    object-fit: cover;
    margin: 0 auto 15px;
    border: 3px solid var(--light-brown);
}
.testimonial-text {
    font-style: italic;
    margin-bottom: 15px;
}
.testimonial-author {
    font-weight: 600;
    color: var(--primary-brown);
}
.contact-container {
    display: flex;
    gap: 50px;
}
.contact-info {
    flex: 1;
}
.contact-details {
    margin-bottom: 30px;
}
.contact-detail {
    display: flex;
    align-items: center;
    margin-bottom: 15px;
}
.contact-detail i {
    margin-right: 10px;
    color: var(--primary-brown);
    width: 20px;
    text-align: center;
}
.contact-form {
    flex: 1;
}
.form-group {
    margin-bottom: 20px;
}
.form-group label {
    display: block;
    margin-bottom: 8px;
    font-weight: 500;
}
.form-control {
    width: 100%;
    padding: 12px;
    border: 1px solid #ddd;
    border-radius: var(--border-radius);
    font-family: inherit;
    transition: var(--transition);
}
.form-control:focus {
    border-color: var(--primary-brown);
    outline: none;
    box-shadow: 0 0 0 2px rgba(139, 69, 19, 0.2);
}
textarea.form-control {
    min-height: 150px;
    resize: vertical;
}
.map {
    border-radius: var(--border-radius);
    overflow: hidden;
    box-shadow: var(--shadow);
}
footer {
    background-color: var(--primary-brown);
    color: var(--light-text);
    padding: 50px 0 20px;
}
.footer-content {
    display: flex;
    justify-content: space-between;
    margin-bottom: 40px;
    flex-wrap: wrap;
    gap: 30px;
}
.footer-column {
    flex: 1;
    min-width: 200px;
}
.footer-column h3 {
    margin-bottom: 20px;
    position: relative;
    padding-bottom: 10px;
}
.footer-column h3::after {
    content: '';
    position: absolute;
    bottom: 0;
    left: 0;
    width: 40px;
    height: 2px;
    background-color: var(--light-brown);
}
.footer-links {
    list-style: none;
}
.footer-links li {
    margin-bottom: 10px;
}
.footer-links a {
    transition: var(--transition);
}
.footer-links a:hover {
    color: var(--light-brown);
    padding-left: 5px;
}
.social-links {
    display: flex;
    gap: 15px;
    margin-top: 20px;
}
.social-links a {
    display: inline-flex;
    align-items: center;
    justify-content: center;
    width: 40px;
    height: 40px;
    background-color: rgba(255, 255, 255, 0.1);
    border-radius: 50%;
    transition: var(--transition);
}
.social-links a:hover {
    background-color: var(--light-brown);
    color: var(--primary-brown);
    transform: translateY(-3px);
}
.copyright {
    text-align: center;
    padding-top: 20px;
    border-top: 1px solid rgba(255, 255, 255, 0.1);
}
.modal {
    display: none;
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background-color: rgba(0, 0, 0, 0.9);
    z-index: 1100;
    justify-content: center;
    align-items: center;
    opacity: 0;
    transition: opacity 0.3s ease;
}
.modal.active {
    display: flex;
    opacity: 1;
}
.modal-content {
    max-width: 90%;
    max-height: 90%;
    position: relative;
    animation: zoomIn 0.3s ease;
}
.modal img {
    width: 100%;
    height: auto;
    border-radius: var(--border-radius);
}
.close-modal {
position: absolute;
top: -40px;
right: 0;
color: white;
font-size: 2rem;
cursor: pointer;
transition: var(--transition);
}
.close-modal:hover {
color: var(--light-brown);
}
@keyframes fadeIn {
from { opacity: 0; transform: translateY(20px); }
to { opacity: 1; transform: translateY(0); }
}
@keyframes zoomIn {
from { transform: scale(0.8); opacity: 0; }
to { transform: scale(1); opacity: 1; }
}
@keyframes fadeInUp {
from { opacity: 0; transform: translateY(20px); }
to { opacity: 1; transform: translateY(0); }
}
.loading {
display: inline-block;
width: 20px;
height: 20px;
border: 3px solid rgba(255,255,255,.3);
border-radius: 50%;
border-top-color: #fff;
animation: spin 1s ease-in-out infinite;
margin-right: 10px;
}
@keyframes spin {
to { transform: rotate(360deg); }
}
@media (max-width: 992px) {
.about-content,
.contact-container {
flex-direction: column;
    }
.hero h1 {
font-size: 2.5rem;
    }
.footer-content {
flex-direction: column;
    }
}
@media (max-width: 768px) {
.nav-menu {
display: none;
position: absolute;
top: 100%;
left: 0;
width: 100%;
background-color: var(--primary-brown);
flex-direction: column;
padding: 20px 0;
box-shadow: var(--shadow);
text-align: center;
    }
.nav-menu.active {
display: flex;
    }
.nav-menu li {
margin: 10px 0;
}
.mobile-menu-btn {
display: block;
    }
.hero {
padding: 100px 0;
    }
.hero h1 {
font-size: 2rem;
    }
.section {
padding: 60px 0;
    }
.hero-btns {
flex-direction: column;
align-items: center;
    }
.btn {
width: 100%;
max-width: 250px;
    }
}
@media (max-width: 576px) {
    .hero h1 {
        font-size: 1.8rem;
    }
.menu-grid {
grid-template-columns: 1fr;
    }
.gallery-grid {
grid-template-columns: repeat(auto-fill, minmax(150px, 1fr));
    }
.menu-tabs {
flex-direction: column;
align-items: center;
    }
.tab-btn {
width: 100%;
max-width: 200px;
    }
}
.sr-only {
position: absolute;
width: 1px;
height: 1px;
padding: 0;
margin: -1px;
overflow: hidden;
clip: rect(0, 0, 0, 0);
white-space: nowrap;
border: 0;
}
button:focus,
a:focus,
input:focus,
textarea:focus {
outline: 2px solid var(--light-brown);
outline-offset: 2px;
}

const mobileMenuBtn = document.querySelector('.mobile-menu-btn');
const navMenu = document.querySelector('.nav-menu');

mobileMenuBtn.addEventListener('click', () => {
    navMenu.classList.toggle('active');
});

document.querySelectorAll('.nav-menu a').forEach(link => {
    link.addEventListener('click', () => {
        navMenu.classList.remove('active');
    });
});

const tabBtns = document.querySelectorAll('.tab-btn');
const menuItems = document.querySelectorAll('.menu-item');

tabBtns.forEach(btn => {
    btn.addEventListener('click', () => {

        tabBtns.forEach(b => b.classList.remove('active'));
        
        btn.classList.add('active');
        
        const category = btn.getAttribute('data-category');
        
        menuItems.forEach(item => {
            const itemCategory = item.getAttribute('data-category');
            
            if (category === 'all' || category === itemCategory) {
                
                item.classList.remove('hidden');
                item.style.animation = 'fadeInUp 0.5s ease forwards';
            } else {
                
                item.style.animation = 'none';
                item.offsetHeight;
                item.classList.add('hidden');
            }
        });
    });
});

const galleryItems = document.querySelectorAll('.gallery-item');
const modal = document.getElementById('galleryModal');
const modalImage = document.getElementById('modalImage');
const closeModal = document.querySelector('.close-modal');

galleryItems.forEach(item => {
    item.addEventListener('click', () => {
        const imgSrc = item.querySelector('img').src;
        modalImage.src = imgSrc;
        modal.classList.add('active');
        document.body.style.overflow = 'hidden';
    });
});

closeModal.addEventListener('click', () => {
    modal.classList.remove('active');
    document.body.style.overflow = 'auto';
});

modal.addEventListener('click', (e) => {
    if (e.target === modal) {
        modal.classList.remove('active');
        document.body.style.overflow = 'auto';
    }
});

const contactForm = document.getElementById('contactForm');
const submitBtn = document.getElementById('submitBtn');
const formLoading = document.getElementById('formLoading');

contactForm.addEventListener('submit', (e) => {
    e.preventDefault();
    
    submitBtn.disabled = true;
    formLoading.style.display = 'inline-block';
    
    const name = document.getElementById('name').value;
    const email = document.getElementById('email').value;
    const subject = document.getElementById('subject').value;
    const message = document.getElementById('message').value;
    
    setTimeout(() => {
        alert(`Thank you, ${name}! Your message has been sent. We'll get back to you soon.`);
        
        contactForm.reset();
        
        submitBtn.disabled = false;
        formLoading.style.display = 'none';
    }, 1500);
});

const newsletterForm = document.getElementById('newsletterForm');

newsletterForm.addEventListener('submit', (e) => {
    e.preventDefault();
    const email = newsletterForm.querySelector('input[type="email"]').value;
    alert(`Thank you for subscribing with ${email}! You'll receive our updates soon.`);
    newsletterForm.reset();
});

document.querySelectorAll('a[href^="#"]').forEach(anchor => {
    anchor.addEventListener('click', function (e) {
        e.preventDefault();
        
        const targetId = this.getAttribute('href');
        if (targetId === '#') return;
        
        const targetElement = document.querySelector(targetId);
        if (targetElement) {
            window.scrollTo({
                top: targetElement.offsetTop - 80,
                behavior: 'smooth'
            });
        }
    });
});

const observerOptions = {
    threshold: 0.1,
    rootMargin: '0px 0px -50px 0px'
};

const observer = new IntersectionObserver((entries) => {
    entries.forEach(entry => {
        if (entry.isIntersecting) {
            entry.target.style.animation = 'fadeInUp 0.6s ease forwards';
            observer.unobserve(entry.target);
        }
    });
}, observerOptions);

document.querySelectorAll('.feature, .menu-item, .gallery-item, .testimonial').forEach(el => {
    observer.observe(el);
});

![sj](https://github.com/user-attachments/assets/e90c1a82-8c77-4670-987a-b756cf3ced0b)
![download](https://github.com/user-attachments/assets/18e760a3-41d6-46f6-9a32-716da6e85da5)

