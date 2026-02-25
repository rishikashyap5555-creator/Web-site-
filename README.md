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
