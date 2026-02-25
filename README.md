# Web-site-
Salon website 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Beauty Salon - Blow Dry, Balayage, Waxing & More</title>
    <link rel="stylesheet" href="css/style.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
</head>
<body>
    <!-- NAVIGATION BAR -->
    <nav class="navbar">
        <div class="container">
            <div class="logo">
                <h1>✨ Beauty Salon</h1>
            </div>
            <ul class="nav-menu">
                <li><a href="#home">Home</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#reviews">Reviews</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
            <div class="hamburger">
                <span></span>
                <span></span>
                <span></span>
            </div>
        </div>
    </nav>

    <!-- HERO SECTION -->
    <section id="home" class="hero">
        <div class="hero-content">
            <h1>Welcome to Your Beauty Haven</h1>
            <p>Premium Beauty & Wellness Services</p>
            <button class="btn btn-primary" onclick="scrollToContact()">Book Now</button>
        </div>
    </section>

    <!-- SERVICES SECTION -->
    <section id="services" class="services">
        <div class="container">
            <h2>Our Services</h2>
            <div class="services-grid">
                <!-- Service 1: Blow Dry -->
                <div class="service-card">
                    <div class="service-icon">
                        <i class="fas fa-wind"></i>
                    </div>
                    <h3>Blow Dry</h3>
                    <p>Professional blow dry services for smooth, voluminous hair. Perfect for any occasion.</p>
                    <span class="price">₹500 - ₹1000</span>
                </div>

                <!-- Service 2: Balayage -->
                <div class="service-card">
                    <div class="service-icon">
                        <i class="fas fa-palette"></i>
                    </div>
                    <h3>Balayage</h3>
                    <p>Expert balayage coloring technique for natural, sun-kissed hair highlights.</p>
                    <span class="price">₹3000 - ₹7000</span>
                </div>

                <!-- Service 3: Body Waxing -->
                <div class="service-card">
                    <div class="service-icon">
                        <i class="fas fa-spa"></i>
                    </div>
                    <h3>Body Waxing</h3>
                    <p>Smooth, hair-free skin with our professional waxing services. Gentle and effective.</p>
                    <span class="price">₹300 - ₹1500</span>
                </div>

                <!-- Service 4: Braids -->
                <div class="service-card">
                    <div class="service-icon">
                        <i class="fas fa-ring"></i>
                    </div>
                    <h3>Braids</h3>
                    <p>Trendy and traditional braiding styles. From simple to elaborate designs.</p>
                    <span class="price">₹800 - ₹3000</span>
                </div>

                <!-- Service 5: Acne Treatments -->
                <div class="service-card">
                    <div class="service-icon">
                        <i class="fas fa-droplet"></i>
                    </div>
                    <h3>Acne Treatments</h3>
                    <p>Advanced facial treatments to clear acne and improve skin health naturally.</p>
                    <span class="price">₹1000 - ₹3000</span>
                </div>

                <!-- Service 6: Facial -->
                <div class="service-card">
                    <div class="service-icon">
                        <i class="fas fa-face-smile"></i>
                    </div>
                    <h3>Premium Facials</h3>
                    <p>Rejuvenating facials using premium skincare products for glowing skin.</p>
                    <span class="price">₹800 - ₹2500</span>
                </div>
            </div>
        </div>
    </section>

    <!-- ABOUT SECTION -->
    <section id="about" class="about">
        <div class="container">
            <h2>About Us</h2>
            <div class="about-content">
                <div class="about-text">
                    <h3>Welcome to Our Salon</h3>
                    <p>We are a premium beauty and wellness salon dedicated to making you feel beautiful and confident. With experienced professionals and premium products, we ensure every visit is a memorable experience.</p>
                    <div class="about-features">
                        <div class="feature">
                            <i class="fas fa-check-circle"></i>
                            <span>Expert Professionals</span>
                        </div>
                        <div class="feature">
                            <i class="fas fa-check-circle"></i>
                            <span>Premium Products</span>
                        </div>
                        <div class="feature">
                            <i class="fas fa-check-circle"></i>
                            <span>5-Star Service</span>
                        </div>
                        <div class="feature">
                            <i class="fas fa-check-circle"></i>
                            <span>Affordable Pricing</span>
                        </div>
                    </div>
                </div>
                <div class="about-stats">
                    <div class="stat">
                        <h4>4.9★</h4>
                        <p>Rating</p>
                    </div>
                    <div class="stat">
                        <h4>16</h4>
                        <p>Reviews</p>
                    </div>
                    <div class="stat">
                        <h4>5+</h4>
                        <p>Services</p>
                    </div>
                    <div class="stat">
                        <h4>1000+</h4>
                        <p>Happy Clients</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- REVIEWS SECTION -->
    <section id="reviews" class="reviews">
        <div class="container">
            <h2>Customer Reviews</h2>
            <div class="reviews-grid">
                <div class="review-card">
                    <div class="stars">★★★★★</div>
                    <p>"Amazing service! The balayage turned out perfectly. Highly recommended!"</p>
                    <h4>- Priya Sharma</h4>
                </div>
                <div class="review-card">
                    <div class="stars">★★★★★</div>
                    <p>"Best blow dry in town! My hair has never looked better. Great staff!"</p>
                    <h4>- Anjali Verma</h4>
                </div>
                <div class="review-card">
                    <div class="stars">★★★★★</div>
                    <p>"Acne treatment worked wonders for my skin. Professional and caring team."</p>
                    <h4>- Ritika Patel</h4>
                </div>
                <div class="review-card">
                    <div class="stars">★★★★★</div>
                    <p>"Love my braids! Creative designs and excellent customer service. Will visit again!"</p>
                    <h4>- Simran Kaur</h4>
                </div>
            </div>
        </div>
    </section>

    <!-- CONTACT SECTION -->
    <section id="contact" class="contact">
        <div class="container">
            <h2>Get In Touch</h2>
            <div class="contact-content">
                <div class="contact-info">
                    <h3>Contact Information</h3>
                    <div class="info-item">
                        <i class="fas fa-map-marker-alt"></i>
                        <div>
                            <h4>Location</h4>
                            <p>Main Bazar, Fateh Singh Colony<br>Amritsar, Punjab 143009</p>
                        </div>
                    </div>
                    <div class="info-item">
                        <i class="fas fa-phone"></i>
                        <div>
                            <h4>Phone</h4>
                            <p><a href="tel:+919781363233">+91 9781363233</a></p>
                        </div>
                    </div>
                    <div class="info-item">
                        <i class="fas fa-envelope"></i>
                        <div>
                            <h4>Email</h4>
                            <p><a href="mailto:info@beautysalon.com">info@beautysalon.com</a></p>
                        </div>
                    </div>
                    <div class="info-item">
                        <i class="fas fa-clock"></i>
                        <div>
                            <h4>Hours</h4>
                            <p>Mon - Sun: 10:00 AM - 8:00 PM</p>
                        </div>
                    </div>
                </div>

                <form class="contact-form" id="contactForm">
                    <h3>Send us a Message</h3>
                    <input type="text" placeholder="Your Name" required>
                    <input type="email" placeholder="Your Email" required>
                    <textarea placeholder="Your Message" rows="5" required></textarea>
                    <button type="submit" class="btn btn-primary">Send Message</button>
                </form>
            </div>
        </div>
    </section>

    <!-- FOOTER -->
    <footer class="footer">
        <div class="container">
            <p>&copy; 2026 Beauty Salon. All rights reserved.</p>
            <div class="social-links">
                <a href="#"><i class="fab fa-facebook"></i></a>
                <a href="#"><i class="fab fa-instagram"></i></a>
                <a href="#"><i class="fab fa-whatsapp"></i></a>
                <a href="#"><i class="fab fa-twitter"></i></a>
            </div>
        </div>
    </footer>

    <script src="js/script.js"></script>
</body>
</html>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

:root {
    --primary-color: #e91e63;
    --secondary-color: #9c27b0;
    --text-color: #333;
    --light-bg: #f5f5f5;
    --white: #ffffff;
    --shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
}

body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    line-height: 1.6;
    color: var(--text-color);
}

.container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 20px;
}

/* ===== NAVBAR ===== */
.navbar {
    background: var(--white);
    box-shadow: var(--shadow);
    position: sticky;
    top: 0;
    z-index: 1000;
}

.navbar .container {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 1rem 20px;
}

.logo h1 {
    color: var(--primary-color);
    font-size: 1.8rem;
}

.nav-menu {
    display: flex;
    list-style: none;
    gap: 2rem;
}

.nav-menu a {
    text-decoration: none;
    color: var(--text-color);
    font-weight: 500;
    transition: color 0.3s ease;
}

.nav-menu a:hover {
    color: var(--primary-color);
}

.hamburger {
    display: none;
    flex-direction: column;
    cursor: pointer;
}

.hamburger span {
    width: 25px;
    height: 3px;
    background: var(--text-color);
    margin: 5px 0;
    transition: 0.3s;
}

/* ===== HERO SECTION ===== */
.hero {
    background: linear-gradient(135deg, var(--primary-color), var(--secondary-color));
    color: var(--white);
    padding: 120px 20px;
    text-align: center;
    min-height: 600px;
    display: flex;
    align-items: center;
    justify-content: center;
}

.hero-content h1 {
    font-size: 3.5rem;
    margin-bottom: 1rem;
    animation: fadeInDown 0.8s ease;
}

.hero-content p {
    font-size: 1.5rem;
    margin-bottom: 2rem;
    animation: fadeInUp 0.8s ease;
}

@keyframes fadeInDown {
    from {
        opacity: 0;
        transform: translateY(-30px);
    }
    to {
        opacity: 1;
        transform: translateY(0);
    }
}

@keyframes fadeInUp {
    from {
        opacity: 0;
        transform: translateY(30px);
    }
    to {
        opacity: 1;
        transform: translateY(0);
    }
}

/* ===== BUTTONS ===== */
.btn {
    padding: 12px 30px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    font-size: 1rem;
    transition: all 0.3s ease;
    font-weight: 600;
}

.btn-primary {
    background: var(--primary-color);
    color: var(--white);
}

.btn-primary:hover {
    background: var(--secondary-color);
    transform: translateY(-3px);
    box-shadow: 0 5px 20px rgba(233, 30, 99, 0.4);
}

/* ===== SERVICES SECTION ===== */
.services {
    padding: 80px 20px;
    background: var(--light-bg);
}

.services h2 {
    text-align: center;
    font-size: 2.5rem;
    margin-bottom: 50px;
    color: var(--text-color);
}

.services-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 30px;
}

.service-card {
    background: var(--white);
    padding: 30px;
    border-radius: 10px;
    text-align: center;
    box-shadow: var(--shadow);
    transition: all 0.3s ease;
}

.service-card:hover {
    transform: translateY(-10px);
    box-shadow: 0 10px 30px rgba(0, 0, 0, 0.2);
}

.service-icon {
    font-size: 3rem;
    color: var(--primary-color);
    margin-bottom: 15px;
}

.service-card h3 {
    font-size: 1.5rem;
    margin-bottom: 10px;
    color: var(--text-color);
}

.service-card p {
    color: #666;
    margin-bottom: 15px;
    font-size: 0.95rem;
}

.price {
    display: block;
    font-size: 1.2rem;
    color: var(--primary-color);
    font-weight: bold;
}

/* ===== ABOUT SECTION ===== */
.about {
    padding: 80px 20px;
    background: var(--white);
}

.about h2 {
    text-align: center;
    font-size: 2.5rem;
    margin-bottom: 50px;
    color: var(--text-color);
}

.about-content {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 50px;
    align-items: center;
}

.about-text h3 {
    font-size: 2rem;
    margin-bottom: 20px;
    color: var(--primary-color);
}

.about-text p {
    color: #666;
    margin-bottom: 20px;
    font-size: 1rem;
    line-height: 1.8;
}

.about-features {
    display: grid;
    gap: 15px;
}

.feature {
    display: flex;
    align-items: center;
    gap: 10px;
    font-size: 1.1rem;
}

.feature i {
    color: var(--primary-color);
    font-size: 1.5rem;
}

.about-stats {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 20px;
}

.stat {
    background: linear-gradient(135deg, var(--primary-color), var(--secondary-color));
    color: var(--white);
    padding: 30px;
    border-radius: 10px;
    text-align: center;
}

.stat h4 {
    font-size: 2.5rem;
    margin-bottom: 10px;
}

.stat p {
    font-size: 1rem;
}

/* ===== REVIEWS SECTION ===== */
.reviews {
    padding: 80px 20px;
    background: var(--light-bg);
}

.reviews h2 {
    text-align: center;
    font-size: 2.5rem;
    margin-bottom: 50px;
    color: var(--text-color);
}

.reviews-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
    gap: 30px;
}

.review-card {
    background: var(--white);
    padding: 25px;
    border-radius: 10px;
    box-shadow: var(--shadow);
    transition: all 0.3s ease;
}

.review-card:hover {
    box-shadow: 0 10px 25px rgba(0, 0, 0, 0.15);
}

.stars {
    color: #ffc107;
    font-size: 1.2rem;
    margin-bottom: 10px;
}

.review-card p {
    color: #666;
    margin-bottom: 15px;
    font-style: italic;
    line-height: 1.6;
}

.review-card h4 {
    color: var(--primary-color);
    font-size: 0.95rem;
}

/* ===== CONTACT SECTION ===== */
.contact {
    padding: 80px 20px;
    background: var(--white);
}

.contact h2 {
    text-align: center;
    font-size: 2.5rem;
    margin-bottom: 50px;
    color: var(--text-color);
}

.contact-content {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 50px;
}

.contact-info h3 {
    font-size: 1.5rem;
    margin-bottom: 30px;
    color: var(--primary-color);
}

.info-item {
    display: flex;
    gap: 15px;
    margin-bottom: 25px;
}

.info-item i {
    font-size: 1.5rem;
    color: var(--primary-color);
    min-width: 30px;
}

.info-item h4 {
    margin-bottom: 5px;
    color: var(--text-color);
}

.info-item p {
    color: #666;
    font-size: 0.95rem;
}

.info-item a {
    color: var(--primary-color);
    text-decoration: none;
}

.contact-form {
    background: var(--light-bg);
    padding: 30px;
    border-radius: 10px;
}

.contact-form h3 {
    font-size: 1.5rem;
    margin-bottom: 20px;
    color: var(--primary-color);
}

.contact-form input,
.contact-form textarea {
    width: 100%;
    padding: 12px;
    margin-bottom: 15px;
    border: 1px solid #ddd;
    border-radius: 5px;
    font-family: inherit;
    font-size: 1rem;
    transition: border 0.3s ease;
}

.contact-form input:focus,
.contact-form textarea:focus {
    outline: none;
    border-color: var(--primary-color);
    box-shadow: 0 0 5px rgba(233, 30, 99, 0.3);
}

.contact-form button {
    width: 100%;
}

/* ===== FOOTER ===== */
.footer {
    background: #333;
    color: var(--white);
    padding: 30px 20px;
    text-align: center;
}

.footer .container {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.social-links {
    display: flex;
    gap: 20px;
}

.social-links a {
    color: var(--white);
    font-size: 1.5rem;
    transition: color 0.3s ease;
}

.social-links a:hover {
    color: var(--primary-color);
}

/* ===== RESPONSIVE DESIGN ===== */
@media (max-width: 768px) {
    .nav-menu {
        display: none;
    }

    .hamburger {
        display: flex;
    }

    .hero-content h1 {
        font-size: 2rem;
    }

    .hero-content p {
        font-size: 1rem;
    }

    .services h2,
    .about h2,
    .reviews h2,
    .contact h2 {
        font-size: 2rem;
    }

    .about-content,
    .contact-content {
        grid-template-columns: 1fr;
    }

    .about-stats {
        grid-template-columns: 1fr;
    }

    .footer .container {
        flex-direction: column;
        gap: 15px;
    }

    .nav-menu.active {
        display: flex;
        position: absolute;
        top: 70px;
        left: 0;
        width: 100%;
        background: var(--white);
        flex-direction: column;
        padding: 20px;
        gap: 1rem;
        box-shadow: var(--shadow);
    }
}
