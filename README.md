# EXOTICAAA
# Ex02 Commercial Website
## Date:02.11.2026
## Name: Imesha S
## Reg no: 212225040131
## AIM
To create a commercial website using CSS Flexbox.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for Homepage, Products / Services, About Us, Contact Details and User Account.

### STEP 5
Include social media links at the footer with copyright information.

### STEP 6
Define global styles for fonts, colors, and layout.

### STEP 7
Style the header, navigation bar, and sections.

### STEP 8
Use Flexbox for layout design.

### STEP 9
Add hover effects and transitions for interactivity.

### STEP 10
Add Images and Media.

### STEP 11
Use optimized images for a professional look.

### STEP 12
Open the HTML file in a browser to check layout and functionality.

### STEP 13
Fix styling issues and refine content placement.

### STEP 14
Deploy the website.

### STEP 15
Upload to GitHub Pages for free hosting.

## PROGRAM
index.html
```
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>FRUITORA | Fresh Fruits Store</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <!-- NAVIGATION BAR -->
    <header>
        <nav class="navbar">
            <div class="logo">🍓 FRUITORA</div>

            <ul class="nav-links">
                <li><a href="#home">Home</a></li>
                <li><a href="#products">Fruits</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>

            <a href="#products" class="nav-btn">Shop Now</a>
        </nav>

        <!-- HERO SECTION -->
        <section class="hero" id="home">
            <div class="hero-text">
                <h1>Fresh Fruits, Healthy Life!</h1>
                <p>
                    Enjoy nature's goodness with our handpicked fresh fruits.
                    Quality, freshness and taste delivered directly to your doorstep.
                </p>
                <a href="#products" class="primary-btn">Explore Fruits</a>
            </div>

            <div class="hero-image">
                <img src="Screenshot 2026-11-02 233511.png"
                     alt="Fresh colourful fruits">
            </div>
        </section>
    </header>

    <!-- PRODUCTS SECTION -->
    <section class="products" id="products">
        <h2>Our Fresh Fruits</h2>
        <p class="section-description">
            Discover delicious fruits selected especially for you.
        </p>

        <div class="product-container">

            <div class="card">
                <img src="Screenshot 2026-11-02 233829.png"
                     alt="Fresh mangoes">
                <h3>Fresh Mango</h3>
                <p>Sweet, juicy and naturally delicious mangoes.</p>
                <h4>₹120 / kg</h4>
                <button>Add to Cart</button>
            </div>

            <div class="card">
                <img src="Screenshot 2026-11-02 234008.png"
                     alt="Fresh strawberries">
                <h3>Strawberry</h3>
                <p>Fresh and sweet strawberries full of flavour.</p>
                <h4>₹180 / box</h4>
                <button>Add to Cart</button>
            </div>

            <div class="card">
                <img src="Screenshot 2026-11-02 234222.png"
                     alt="Fresh kiwi">
                <h3>Kiwi</h3>
                <p>Delicious kiwi packed with natural goodness.</p>
                <h4>₹150 / pack</h4>
                <button>Add to Cart</button>
            </div>

            <div class="card">
                <img src="Screenshot 2026-11-02 234543.png"
                     alt="Fresh oranges">
                <h3>Orange</h3>
                <p>Refreshing oranges with a sweet citrus taste.</p>
                <h4>₹90 / kg</h4>
                <button>Add to Cart</button>
            </div>

            <div class="card">
                <img src="Screenshot 2026-11-02 234730.png"
                     alt="Fresh bananas">
                <h3>Banana</h3>
                <p>Fresh and naturally sweet everyday fruit.</p>
                <h4>₹60 / dozen</h4>
                <button>Add to Cart</button>
            </div>

            <div class="card">
                <img src="Screenshot 2026-11-02 234851.png"
                     alt="Fresh fruit selection">
                <h3>Fruit Basket</h3>
                <p>A colourful combination of seasonal fruits.</p>
                <h4>₹299 / basket</h4>
                <button>Add to Cart</button>
            </div>

        </div>
    </section>

    <!-- SERVICES SECTION -->
    <section class="services" id="services">

        <div class="service">
            <h2>🚚</h2>
            <h3>Fast Delivery</h3>
            <p>Fresh fruits delivered to your doorstep.</p>
        </div>

        <div class="service">
            <h2>🍃</h2>
            <h3>100% Fresh</h3>
            <p>Carefully selected fruits of excellent quality.</p>
        </div>

        <div class="service">
            <h2>💳</h2>
            <h3>Secure Payment</h3>
            <p>Safe and convenient payment experience.</p>
        </div>

    </section>

    <!-- ABOUT SECTION -->
    <section class="about" id="about">
        <div class="about-image">
            <img src="Screenshot 2026-11-02 235311.png"
                 alt="Fresh produce">
        </div>

        <div class="about-text">
            <h2>About FRUITORA</h2>
            <p>
                At FRUITORA, we believe healthy living begins with fresh food.
                Our goal is to bring nature's finest fruits to your home.
                We focus on freshness, quality and customer satisfaction.
            </p>
            <a href="#contact" class="primary-btn">Know More</a>
        </div>
    </section>

    <!-- CUSTOMER REVIEWS -->
    <section class="testimonial">
        <h2>What Our Customers Say</h2>

        <div class="review-box">
            <div class="review">
                <p>
                    "The fruits were fresh, delicious and beautifully packed.
                    I really loved the service!"
                </p>
                <h4>- Arun</h4>
            </div>

            <div class="review">
                <p>
                    "Excellent quality and timely delivery.
                    FRUITORA is now my favourite fruit store."
                </p>
                <h4>- Priya</h4>
            </div>
        </div>
    </section>

    <!-- NEWSLETTER SECTION -->
    <section class="newsletter">
        <h2>Stay Fresh With Us!</h2>
        <p>Subscribe to receive updates and special offers.</p>

        <div class="subscribe">
            <input type="email" placeholder="Enter your email address">
            <button>Subscribe</button>
        </div>
    </section>

    <!-- FOOTER -->
    <footer id="contact">
        <div class="footer-content">

            <div>
                <h3>🍓 FRUITORA</h3>
                <p>Your destination for fresh and healthy fruits.</p>
            </div>

            <div>
                <h3>Quick Links</h3>
                <p><a href="#home">Home</a></p>
                <p><a href="#products">Fruits</a></p>
                <p><a href="#about">About Us</a></p>
            </div>

            <div>
                <h3>Contact Us</h3>
                <p>support@fruitora.com</p>
                <p>+91 9876543210</p>
            </div>

        </div>

        <div class="student-details">
            <p>Designed by: Imesha</p>
            <p>Register Number: 212225040131</p>
        </div>

        <p class="copyright">
            © 2026 FRUITORA. All Rights Reserved.
        </p>
    </footer>

</body>
</html>
```
style.css
```
```css
/* GENERAL STYLING */

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Arial, Helvetica, sans-serif;
    scroll-behavior: smooth;
}

body {
    background: #fffdf5;
    color: #333;
}

/* NAVIGATION BAR */

.navbar {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 20px 8%;
    background: #164b35;
    color: white;
    flex-wrap: wrap;
    gap: 20px;
}

.logo {
    font-size: 28px;
    font-weight: bold;
    color: #ffdf70;
}

.nav-links {
    display: flex;
    list-style: none;
    gap: 25px;
}

.nav-links a {
    text-decoration: none;
    color: white;
    font-weight: bold;
    transition: 0.3s;
}

.nav-links a:hover {
    color: #ffdf70;
}

.nav-btn {
    text-decoration: none;
    padding: 11px 22px;
    background: #f5b942;
    color: #164b35;
    border-radius: 6px;
    font-weight: bold;
}

/* HERO SECTION */

.hero {
    display: flex;
    justify-content: space-between;
    align-items: center;
    gap: 40px;
    padding: 70px 8%;
    background: linear-gradient(120deg, #e4f2df, #fff4d6);
    flex-wrap: wrap;
}

.hero-text {
    flex: 1;
    min-width: 280px;
}

.hero-text h1 {
    font-size: 48px;
    color: #164b35;
    margin-bottom: 20px;
    line-height: 1.2;
}

.hero-text p {
    font-size: 18px;
    line-height: 30px;
    margin-bottom: 30px;
}

.primary-btn {
    display: inline-block;
    text-decoration: none;
    padding: 14px 28px;
    background: #e99b24;
    color: white;
    border-radius: 7px;
    font-weight: bold;
    transition: 0.3s;
}

.primary-btn:hover {
    background: #164b35;
    transform: translateY(-3px);
}

.hero-image {
    flex: 1;
    min-width: 280px;
    display: flex;
    justify-content: center;
}

.hero-image img {
    width: 100%;
    max-width: 500px;
    height: 330px;
    object-fit: cover;
    border-radius: 18px;
    box-shadow: 0 12px 30px rgba(0,0,0,0.15);
}

/* PRODUCTS SECTION */

.products {
    padding: 70px 8%;
    text-align: center;
    background: #fffdf5;
}

.products h2,
.testimonial h2 {
    font-size: 36px;
    color: #164b35;
    margin-bottom: 15px;
}

.section-description {
    margin-bottom: 40px;
    color: #666;
}

.product-container {
    display: flex;
    justify-content: center;
    gap: 30px;
    flex-wrap: wrap;
}

.card {
    width: 300px;
    padding: 20px;
    background: white;
    border-radius: 15px;
    box-shadow: 0 8px 22px rgba(0,0,0,0.10);
    display: flex;
    flex-direction: column;
    align-items: center;
    transition: 0.3s;
}

.card:hover {
    transform: translateY(-10px);
    box-shadow: 0 15px 30px rgba(0,0,0,0.16);
}

.card img {
    width: 100%;
    height: 200px;
    object-fit: cover;
    border-radius: 10px;
}

.card h3 {
    margin: 18px 0 10px;
    color: #164b35;
}

.card p {
    line-height: 24px;
    margin-bottom: 15px;
}

.card h4 {
    color: #d88717;
    margin-bottom: 18px;
}

.card button {
    padding: 11px 25px;
    border: none;
    border-radius: 6px;
    background: #164b35;
    color: white;
    cursor: pointer;
    transition: 0.3s;
}

.card button:hover {
    background: #e99b24;
}

/* SERVICES SECTION */

.services {
    display: flex;
    justify-content: center;
    gap: 30px;
    flex-wrap: wrap;
    padding: 65px 8%;
    background: #eaf3e5;
}

.service {
    width: 280px;
    padding: 30px;
    text-align: center;
    background: white;
    border-radius: 12px;
    box-shadow: 0 6px 18px rgba(0,0,0,0.08);
    transition: 0.3s;
}

.service:hover {
    transform: translateY(-7px);
}

.service h2 {
    font-size: 45px;
    margin-bottom: 15px;
}

.service h3 {
    color: #164b35;
    margin-bottom: 12px;
}

.service p {
    line-height: 25px;
}

/* ABOUT SECTION */

.about {
    display: flex;
    align-items: center;
    justify-content: space-between;
    gap: 45px;
    padding: 70px 8%;
    flex-wrap: wrap;
    background: #fffdf5;
}

.about-image,
.about-text {
    flex: 1;
    min-width: 280px;
}

.about-image img {
    width: 100%;
    max-width: 500px;
    height: 300px;
    object-fit: cover;
    border-radius: 15px;
}

.about-text h2 {
    color: #164b35;
    font-size: 35px;
    margin-bottom: 20px;
}

.about-text p {
    line-height: 29px;
    margin-bottom: 25px;
}

/* CUSTOMER REVIEWS */

.testimonial {
    padding: 70px 8%;
    text-align: center;
    background: #f4f7ed;
}

.review-box {
    display: flex;
    justify-content: center;
    gap: 30px;
    flex-wrap: wrap;
    margin-top: 35px;
}

.review {
    width: 400px;
    padding: 30px;
    background: white;
    border-radius: 12px;
    box-shadow: 0 6px 18px rgba(0,0,0,0.08);
}

.review p {
    line-height: 27px;
    margin-bottom: 20px;
}

.review h4 {
    color: #e99b24;
}

/* NEWSLETTER SECTION */

.newsletter {
    padding: 65px 8%;
    text-align: center;
    background: #164b35;
    color: white;
}

.newsletter h2 {
    font-size: 34px;
    margin-bottom: 15px;
}

.newsletter p {
    margin-bottom: 20px;
}

.subscribe {
    display: flex;
    justify-content: center;
    gap: 12px;
    flex-wrap: wrap;
}

.subscribe input {
    width: 350px;
    max-width: 100%;
    padding: 14px;
    border: none;
    border-radius: 6px;
    font-size: 15px;
}

.subscribe button {
    padding: 14px 25px;
    border: none;
    border-radius: 6px;
    background: #f5b942;
    color: #164b35;
    font-weight: bold;
    cursor: pointer;
}

/* FOOTER */

footer {
    padding: 45px 8% 20px;
    background: #102f24;
    color: white;
}

.footer-content {
    display: flex;
    justify-content: space-between;
    gap: 35px;
    flex-wrap: wrap;
    margin-bottom: 30px;
}

.footer-content div {
    flex: 1;
    min-width: 200px;
}

.footer-content h3 {
    color: #ffdf70;
    margin-bottom: 15px;
}

.footer-content p {
    line-height: 30px;
}

.footer-content a {
    color: white;
    text-decoration: none;
}

.footer-content a:hover {
    color: #ffdf70;
}

.student-details {
    text-align: center;
    line-height: 28px;
    padding: 20px;
    border-top: 1px solid rgba(255,255,255,0.25);
}

.copyright {
    text-align: center;
    padding-top: 15px;
    border-top: 1px solid rgba(255,255,255,0.25);
    font-size: 14px;
}

/* RESPONSIVE DESIGN */

@media (max-width: 900px) {

    .navbar {
        flex-direction: column;
        gap: 20px;
    }

    .nav-links {
        justify-content: center;
        flex-wrap: wrap;
    }

    .hero {
        flex-direction: column;
        text-align: center;
    }

    .hero-text h1 {
        font-size: 38px;
    }

    .about {
        flex-direction: column;
        text-align: center;
    }

    .footer-content {
        flex-direction: column;
        text-align: center;
    }
}

@media (max-width: 600px) {

    .hero-text h1 {
        font-size: 32px;
    }

    .products h2,
    .testimonial h2 {
        font-size: 29px;
    }

    .product-container {
        flex-direction: column;
        align-items: center;
    }

    .card {
        width: 100%;
        max-width: 350px;
    }

    .service {
        width: 100%;
        max-width: 350px;
    }

    .review {
        width: 100%;
    }

    .subscribe {
        flex-direction: column;
        align-items: center;
    }

    .subscribe input {
        width: 100%;
    }
}
```


## OUTPUT


## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.