<!DOCTYPE html>

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Amanda Christine Designs | Handmade Gemstone Accessories</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

```
    body {
        font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', 'Helvetica Neue', Arial, sans-serif;
        line-height: 1.6;
        color: #1a1a1a;
        background: #fffef0;
    }
    
    /* Hero Section */
    .hero {
        background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
        height: 500px;
        display: flex;
        align-items: center;
        justify-content: center;
        position: relative;
        overflow: hidden;
    }
    
    .hero::before {
        content: '';
        position: absolute;
        top: 0;
        left: 0;
        right: 0;
        bottom: 0;
        background: url('data:image/svg+xml,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 500"><circle cx="200" cy="200" r="150" fill="rgba(255,255,255,0.1)"/><circle cx="800" cy="300" r="200" fill="rgba(255,255,255,0.1)"/><circle cx="1000" cy="100" r="100" fill="rgba(255,255,255,0.1)"/></svg>');
        opacity: 0.3;
    }
    
    .hero-content {
        position: relative;
        z-index: 1;
        text-align: center;
        color: white;
        padding: 2rem;
    }
    
    .hero h1 {
        font-size: 3.5rem;
        font-weight: 300;
        letter-spacing: 3px;
        margin-bottom: 1rem;
        text-shadow: 2px 2px 4px rgba(0,0,0,0.2);
    }
    
    .hero p {
        font-size: 1.5rem;
        opacity: 0.95;
        text-shadow: 1px 1px 2px rgba(0,0,0,0.2);
    }
    
    /* CTA Section */
    .cta-section {
        background: #e8f5a8;
        padding: 4rem 2rem;
        text-align: center;
    }
    
    .cta-section h2 {
        font-size: 2.8rem;
        font-weight: 400;
        margin-bottom: 2rem;
        color: #1a1a1a;
    }
    
    .cta-button {
        display: inline-block;
        background: #1a1a1a;
        color: white;
        padding: 1.2rem 3.5rem;
        text-decoration: none;
        font-size: 1.1rem;
        transition: all 0.3s;
        border: none;
        cursor: pointer;
        text-transform: uppercase;
        letter-spacing: 1px;
    }
    
    .cta-button:hover {
        background: #333;
        transform: translateY(-2px);
        box-shadow: 0 4px 8px rgba(0,0,0,0.2);
    }
    
    /* Scrolling Banner */
    .scrolling-banner {
        background: #e8f5a8;
        border-top: 2px solid #1a1a1a;
        border-bottom: 2px solid #1a1a1a;
        padding: 1.5rem;
        overflow: hidden;
    }
    
    .scrolling-content {
        display: flex;
        animation: scroll 25s linear infinite;
    }
    
    .scrolling-text {
        font-size: 1.8rem;
        font-weight: 600;
        white-space: nowrap;
        padding-right: 3rem;
    }
    
    @keyframes scroll {
        0% { transform: translateX(0); }
        100% { transform: translateX(-50%); }
    }
    
    /* Special Offer */
    .special-offer {
        background: linear-gradient(135deg, #ffeaa7 0%, #fdcb6e 100%);
        padding: 5rem 2rem;
        text-align: center;
    }
    
    .special-offer h2 {
        font-size: 3rem;
        font-weight: 400;
        margin-bottom: 1rem;
        color: #1a1a1a;
    }
    
    .special-offer p {
        font-size: 1.4rem;
        margin-bottom: 2rem;
        color: #333;
    }
    
    /* Promo Banner */
    .promo-banner {
        background: #e8f5a8;
        padding: 4rem 2rem;
        text-align: center;
    }
    
    .promo-banner p {
        font-size: 1.4rem;
        line-height: 1.8;
        max-width: 800px;
        margin: 0 auto;
        color: #1a1a1a;
    }
    
    /* Products Section */
    .products-section {
        background: #fffef0;
        padding: 5rem 2rem;
    }
    
    .products-section h2 {
        font-size: 3rem;
        font-weight: 400;
        text-align: center;
        margin-bottom: 1rem;
    }
    
    .section-cta {
        text-align: center;
        margin-bottom: 4rem;
    }
    
    .products-grid {
        max-width: 1200px;
        margin: 0 auto;
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
        gap: 2.5rem;
    }
    
    .product-card {
        background: white;
        overflow: hidden;
        transition: all 0.3s;
        box-shadow: 0 2px 8px rgba(0,0,0,0.1);
    }
    
    .product-card:hover {
        transform: translateY(-8px);
        box-shadow: 0 8px 16px rgba(0,0,0,0.15);
    }
    
    .product-image {
        width: 100%;
        height: 350px;
        background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
        display: flex;
        align-items: center;
        justify-content: center;
        font-size: 5rem;
        position: relative;
        overflow: hidden;
    }
    
    .product-image::before {
        content: '';
        position: absolute;
        top: 0;
        left: 0;
        right: 0;
        bottom: 0;
        background: url('data:image/svg+xml,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 400 400"><circle cx="100" cy="100" r="80" fill="rgba(255,255,255,0.1)"/><circle cx="300" cy="250" r="100" fill="rgba(255,255,255,0.1)"/></svg>');
    }
    
    .product-image span {
        position: relative;
        z-index: 1;
    }
    
    .product-info {
        padding: 2rem;
        text-align: center;
        background: white;
    }
    
    .product-info h3 {
        font-size: 1.5rem;
        font-weight: 500;
        margin-bottom: 0.8rem;
        color: #1a1a1a;
    }
    
    .product-price {
        font-size: 1.2rem;
        color: #666;
    }
    
    /* About Section */
    .about-section {
        background: #e8f5a8;
        padding: 5rem 2rem;
    }
    
    .about-content {
        max-width: 1000px;
        margin: 0 auto;
    }
    
    .about-image-container {
        width: 100%;
        max-width: 700px;
        height: 450px;
        margin: 0 auto 3rem;
        background: linear-gradient(135deg, #a29bfe 0%, #6c5ce7 100%);
        display: flex;
        align-items: center;
        justify-content: center;
        font-size: 6rem;
        position: relative;
        overflow: hidden;
    }
    
    .about-image-container::before {
        content: '';
        position: absolute;
        top: 0;
        left: 0;
        right: 0;
        bottom: 0;
        background: url('data:image/svg+xml,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 700 450"><circle cx="150" cy="150" r="120" fill="rgba(255,255,255,0.1)"/><circle cx="550" cy="300" r="150" fill="rgba(255,255,255,0.1)"/></svg>');
    }
    
    .about-image-container span {
        position: relative;
        z-index: 1;
    }
    
    .about-section h2 {
        font-size: 3rem;
        font-weight: 400;
        margin-bottom: 3rem;
        text-align: center;
    }
    
    .about-section h3 {
        font-size: 2rem;
        font-weight: 500;
        margin: 2.5rem 0 1.2rem;
    }
    
    .about-section p {
        font-size: 1.2rem;
        line-height: 1.8;
        margin-bottom: 1.5rem;
    }
    
    /* Testimonials */
    .testimonials {
        background: #fffef0;
        padding: 5rem 2rem;
        text-align: center;
    }
    
    .testimonial-container {
        width: 100%;
        max-width: 700px;
        height: 450px;
        margin: 3rem auto;
        background: linear-gradient(135deg, #fdcb6e 0%, #e17055 100%);
        display: flex;
        align-items: center;
        justify-content: center;
        font-size: 6rem;
        position: relative;
        overflow: hidden;
    }
    
    .testimonial-container::before {
        content: '';
        position: absolute;
        top: 0;
        left: 0;
        right: 0;
        bottom: 0;
        background: url('data:image/svg+xml,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 700 450"><circle cx="200" cy="200" r="150" fill="rgba(255,255,255,0.1)"/><circle cx="500" cy="250" r="120" fill="rgba(255,255,255,0.1)"/></svg>');
    }
    
    .testimonial-container span {
        position: relative;
        z-index: 1;
    }
    
    .load-more {
        display: inline-block;
        background: #1a1a1a;
        color: white;
        padding: 1.2rem 3.5rem;
        text-decoration: none;
        font-size: 1.1rem;
        margin-top: 2rem;
        border: none;
        cursor: pointer;
        text-transform: uppercase;
        letter-spacing: 1px;
        transition: all 0.3s;
    }
    
    .load-more:hover {
        background: #333;
        transform: translateY(-2px);
    }
    
    /* Contact Section */
    .contact-section {
        background: #fffef0;
        padding: 5rem 2rem 3rem;
        text-align: center;
    }
    
    .contact-section h2 {
        font-size: 3rem;
        font-weight: 400;
        margin-bottom: 3rem;
    }
    
    .contact-info {
        font-size: 1.3rem;
        line-height: 2.2;
        margin-bottom: 3rem;
    }
    
    .social-icons {
        display: flex;
        justify-content: center;
        gap: 2rem;
        margin: 3rem 0;
    }
    
    .social-icon {
        width: 60px;
        height: 60px;
        background: #1a1a1a;
        border-radius: 50%;
        display: flex;
        align-items: center;
        justify-content: center;
        color: white;
        text-decoration: none;
        font-size: 1.5rem;
        transition: all 0.3s;
    }
    
    .social-icon:hover {
        background: #667eea;
        transform: translateY(-3px);
    }
    
    /* Footer Links */
    .footer-links {
        background: #fffef0;
        padding: 3rem 2rem;
        text-align: center;
        border-top: 1px solid #ddd;
    }
    
    .footer-links a {
        display: block;
        color: #1a1a1a;
        text-decoration: none;
        margin: 0.8rem 0;
        font-size: 1.1rem;
        transition: color 0.3s;
    }
    
    .footer-links a:hover {
        color: #667eea;
    }
    
    /* Footer */
    footer {
        background: #1a1a1a;
        color: white;
        padding: 2.5rem;
        text-align: center;
    }
    
    footer p {
        margin: 0.5rem 0;
        opacity: 0.9;
    }
    
    @media (max-width: 768px) {
        .hero {
            height: 400px;
        }
        
        .hero h1 {
            font-size: 2.5rem;
        }
        
        .hero p {
            font-size: 1.2rem;
        }
        
        .cta-section h2,
        .special-offer h2,
        .products-section h2,
        .about-section h2,
        .contact-section h2 {
            font-size: 2rem;
        }
        
        .products-grid {
            grid-template-columns: 1fr;
        }
        
        .scrolling-text {
            font-size: 1.3rem;
        }
    }
</style>
```

</head>
<body>
    <!-- Hero Section -->
    <div class="hero">
        <div class="hero-content">
            <h1>AMANDA CHRISTINE DESIGNS</h1>
            <p>✨ Handcrafted Gemstone Accessories ✨</p>
        </div>
    </div>

```
<!-- Quality CTA -->
<div class="cta-section">
    <h2>Quality You Can Trust</h2>
    <a href="#products" class="cta-button">Shop Now</a>
</div>

<!-- Scrolling Banner -->
<div class="scrolling-banner">
    <div class="scrolling-content">
        <span class="scrolling-text">❋ New Arrivals ❋ New Arrivals ❋ New Arrivals ❋ New Arrivals ❋ New Arrivals ❋ New Arrivals ❋ New Arrivals ❋ New Arrivals ❋</span>
    </div>
</div>

<!-- Special Offer -->
<div class="special-offer">
    <h2>Special Offer</h2>
    <p>Exclusive Discounts Inside</p>
    <a href="#contact" class="cta-button">Grab Now</a>
</div>

<!-- Promo Banner -->
<div class="promo-banner">
    <p>Enjoy 15% off your first purchase! Discover the beauty of handmade products at Amanda Christine Designs.</p>
</div>

<!-- Products Section -->
<div class="products-section" id="products">
    <h2>Top Picks</h2>
    <div class="section-cta">
        <a href="#contact" class="cta-button">Shop Now</a>
    </div>
    
    <div class="products-grid">
        <div class="product-card">
            <div class="product-image"><span>💎</span></div>
            <div class="product-info">
                <h3>Gemstone Lanyards</h3>
                <p class="product-price">Handcrafted with genuine stones</p>
            </div>
        </div>
        
        <div class="product-card">
            <div class="product-image" style="background: linear-gradient(135deg, #74b9ff 0%, #0984e3 100%);"><span>📱</span></div>
            <div class="product-info">
                <h3>Phone Lanyards</h3>
                <p class="product-price">Stylish & functional</p>
            </div>
        </div>
        
        <div class="product-card">
            <div class="product-image" style="background: linear-gradient(135deg, #fd79a8 0%, #e84393 100%);"><span>🔑</span></div>
            <div class="product-info">
                <h3>Custom Keychains</h3>
                <p class="product-price">Unique designs</p>
            </div>
        </div>
        
        <div class="product-card">
            <div class="product-image" style="background: linear-gradient(135deg, #55efc4 0%, #00b894 100%);"><span>🏋️</span></div>
            <div class="product-info">
                <h3>Built Different Co.</h3>
                <p class="product-price">Gym apparel - Coming Soon</p>
            </div>
        </div>
    </div>
</div>

<!-- About Section -->
<div class="about-section">
    <div class="about-content">
        <div class="about-image-container">
            <span>👩‍🎨</span>
        </div>
        
        <h2>Our Passion</h2>
        
        <h3>Who We Are</h3>
        <p>At Amanda Christine Designs, we focus on providing unique handmade accessories. Our collection includes beaded lanyards, key chains, phone lanyards, and custom graphic shirts, all crafted with care and creativity.</p>
        
        <h3>Our Mission</h3>
        <p>We aim to deliver exceptional quality and distinctive designs. Our new sub clothing line, Built Different Co, features stylish gym apparel that inspires and motivates.</p>
        
        <h3>Quality</h3>
        <p>Every piece we create is one-of-a-kind, utilizing genuine stones to add a special touch to our lanyards. We are committed to delivering products that combine functionality and aesthetic appeal.</p>
    </div>
</div>

<!-- Testimonials -->
<div class="testimonials">
    <div class="testimonial-container">
        <span>⭐</span>
    </div>
    <button class="load-more">Load More</button>
</div>

<!-- Contact Section -->
<div class="contact-section" id="contact">
    <h2>Amanda Christine Designs</h2>
    
    <div class="contact-info">
        <p><strong>📞 123-456-7890</strong></p>
        <p><strong>✉️ info@amandachristinedesigns.com</strong></p>
        <p>Your Address Here<br>City, State ZIP</p>
    </div>
    
    <div class="social-icons">
        <a href="#" class="social-icon" title="Facebook">f</a>
        <a href="#" class="social-icon" title="Instagram">📷</a>
        <a href="#" class="social-icon" title="Twitter/X">𝕏</a>
        <a href="#" class="social-icon" title="TikTok">♪</a>
    </div>
</div>

<!-- Footer Links -->
<div class="footer-links">
    <a href="#">Privacy Policy</a>
    <a href="#">Accessibility Statement</a>
    <a href="#">Shipping Policy</a>
    <a href="#">Terms & Conditions</a>
    <a href="#">Refund Policy</a>
</div>

<!-- Footer -->
<footer>
    <p>© 2026 Amanda Christine Designs</p>
    <p>Handcrafted with ❤️</p>
</footer>
```

</body>
</html>
