<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Misfar Cargo Service</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

    <!-- Header Section -->
    <header>
        <div class="container">
            <div class="logo">
                <h1>Misfar Cargo Service</h1>
            </div>
            <nav>
                <ul>
                    <li><a href="#home">Home</a></li>
                    <li><a href="#services">Services</a></li>
                    <li><a href="#about">About Us</a></li>
                    <li><a href="#contact">Contact</a></li>
                    <li><a href="#track">Track Shipment</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <!-- Hero Section -->
    <section id="home" class="hero">
        <div class="hero-content">
            <h2>Your Trusted Partner in Cargo and Freight Solutions</h2>
            <p>Reliable, Fast, and Efficient Cargo Services for All Your Needs</p>
            <button><a href="#contact">Get a Quote</a></button>
        </div>
    </section>

    <!-- Services Section -->
    <section id="services">
        <div class="container">
            <h2>Our Services</h2>
            <div class="service">
                <img src="cargo1.jpg" alt="International Shipping">
                <h3>International Shipping</h3>
                <p>Efficient and cost-effective shipping solutions across the globe.</p>
            </div>
            <div class="service">
                <img src="cargo2.jpg" alt="Local Freight Solutions">
                <h3>Local Freight Solutions</h3>
                <p>Timely and reliable freight services within your region.</p>
            </div>
            <div class="service">
                <img src="cargo3.jpg" alt="Warehousing & Distribution">
                <h3>Warehousing & Distribution</h3>
                <p>Comprehensive storage and distribution services for your business.</p>
            </div>
            <div class="service">
                <img src="cargo4.jpg" alt="Cargo Insurance">
                <h3>Cargo Insurance</h3>
                <p>Secure your goods with our reliable cargo insurance options.</p>
            </div>
        </div>
    </section>

    <!-- About Us Section -->
    <section id="about">
        <div class="container">
            <h2>About Us</h2>
            <p>Misfar Cargo Service has been a leader in the cargo and logistics industry for over 10 years. Our mission is to provide reliable, efficient, and cost-effective transportation and storage solutions to businesses worldwide.</p>
            <div class="vision-mission">
                <h3>Our Vision</h3>
                <p>To become the most trusted cargo service provider globally.</p>
                <h3>Our Mission</h3>
                <p>To provide secure, timely, and affordable logistics services tailored to your needs.</p>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact">
        <div class="container">
            <h2>Contact Us</h2>
            <form action="submit-form.php" method="post">
                <input type="text" name="name" placeholder="Your Name" required>
                <input type="email" name="email" placeholder="Your Email" required>
                <textarea name="message" placeholder="Your Message" required></textarea>
                <button type="submit">Send Message</button>
            </form>
            <p>Address: 123 Cargo Lane, Logistics City, ABC 123</p>
            <p>Phone: 123-456-7890</p>
            <p>Email: contact@misfarcargo.com</p>
        </div>
    </section>

    <!-- Track Shipment Section -->
    <section id="track">
        <div class="container">
            <h2>Track Your Shipment</h2>
            <form>
                <input type="text" placeholder="Enter your tracking number" required>
                <button type="submit">Track</button>
            </form>
        </div>
    </section>

    <!-- Footer Section -->
    <footer>
        <div class="container">
            <div class="socials">
                <a href="#">Facebook</a>
                <a href="#">Twitter</a>
                <a href="#">LinkedIn</a>
                <a href="#">Instagram</a>
            </div>
            <div class="quick-links">
                <a href="#">Privacy Policy</a>
                <a href="#">Terms of Service</a>
                <a href="#">Sitemap</a>
            </div>
        </div>
    </footer>

</body>
</html>

