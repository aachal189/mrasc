# mrasc front page                                                                                                                                                                                                              
HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Maxar-Like Front Page</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <!-- Navigation Bar -->
    <header>
        <div class="container">
            <div class="logo">
                <img src="logo.png" alt="Maxar Logo">  <!-- Logo Added -->
            </div>
            <nav>
                <ul class="nav-links">
                    <li><a href="#home">Home</a></li>
                    <li><a href="#services">Services</a></li>
                    <li><a href="#about">About Us</a></li>
                    <li><a href="#solutions">Solutions</a></li>
                    <li><a href="#news">News</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
            <div class="menu-icon" onclick="toggleMenu()">&#9776;</div>
        </div>
    </header>

    <!-- Hero Section -->
    <section id="home" class="hero">
        <div class="hero-text">
            <h1>See the Earth Like Never Before</h1>
            <p>Powering innovation with world-leading satellite imagery.</p>
            <a href="#services" class="btn">Explore Our Solutions</a>
        </div>
    </section>

    <!-- Services Section -->
    <section id="services">
        <div class="container">
            <h2>Our Core Services</h2>
            <div class="service-boxes">
                <div class="service">
                    <h3>Satellite Imagery</h3>
                    <p>Discover high-quality satellite images for industries ranging from defense to environmental research.</p>
                </div>
                <div class="service">
                    <h3>Geospatial Analytics</h3>
                    <p>Analyze data to deliver the most accurate and actionable insights.</p>
                </div>
                <div class="service">
                    <h3>AI & Machine Learning</h3>
                    <p>Leveraging AI for image recognition and data analysis to support decision making.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <div class="container">
            <p>&copy; 2024 MRSAC. All rights reserved. | <a href="#privacy">Privacy Policy</a></p>
        </div>
    </footer>

    <script src="script.js"></script>
</body>
</html>
