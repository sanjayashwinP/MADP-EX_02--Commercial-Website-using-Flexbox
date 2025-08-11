# Ex02 Commercial Website
## Date: 11/08/2025

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
### index.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GadgetHub - Home</title>
    <link rel="stylesheet" href="css\style.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;700&display=swap" rel="stylesheet">
</head>
<body>
   
    <header class="header">
        <div class="logo">Gadget<span>Hub</span></div>
        <nav class="nav">
            <a href="index.html" class="nav-link active">Home</a>
            <a href="products.html" class="nav-link">Products</a>
            <a href="contact.html" class="nav-link">Contact</a>
        </nav>
    </header>

    <section class="hero">
        <div class="hero-content">
            <h1>Discover the Latest Tech</h1>
            <p>Shop the best gadgets from around the globe.</p>
            <a href="products.html" class="btn">Shop Now</a>
        </div>
        <div class="hero-image-container">
            <img src="images\Game.jpeg" alt="Latest Gadgets" class="hero-image">
        </div>
    </section>

    
    <section class="products-section">
        <h2>Featured Gadgets</h2>
        <div class="products-container">
            
            <div class="product-card">
                <img src="images\phone.jpeg" alt="Smartphone" class="product-image">
                <h3>Smartphone X</h3>
                <p class="price">₹69,999</p>
                <a href="#" class="add-to-cart-btn">Add to Cart</a>
            </div>
           
            <div class="product-card">
                <img src="images\laptop1.jpeg" alt="Laptop" class="product-image">
                <h3>UltraBook Pro</h3>
                <p class="price">₹89,999</p>
                <a href="#" class="add-to-cart-btn">Add to Cart</a>
            </div>
           
            <div class="product-card">
                <img src="images\watch12.jpg" alt="Smartwatch" class="product-image">
                <h3>Smart Watch Z</h3>
                <p class="price">₹14,999</p>
                <a href="#" class="add-to-cart-btn">Add to Cart</a>
            </div>
        </div>
    </section>

    <footer class="footer">
        <p>&copy; 2025 GadgetHub | All rights reserved.</p>
    </footer>
</body>
</html>

```
### products.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GadgetHub - Products</title>

    <link rel="stylesheet" href="css\style.css">
    
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;700&display=swap" rel="stylesheet">
</head>
<body>
    <header class="header">
        <div class="logo">Gadget<span>Hub</span></div>
        <nav class="nav">
            <a href="index.html" class="nav-link">Home</a>
            <a href="products.html" class="nav-link active">Products</a>
            <a href="contact.html" class="nav-link">Contact</a>
        </nav>
    </header>

    <main class="main-content">
        <h1 class="page-title">Our Products</h1>
        <section class="products-section">
            <div class="products-container">
              
                <div class="product-card">
                    <img src="images\phone2.jpg" alt="Smartphone" class="product-image">
                    <h3>Smartphone X</h3>
                    <p class="price">₹69,999</p>
                    <a href="#" class="add-to-cart-btn">Add to Cart</a>
                </div>
               
                <div class="product-card">
                    <img src="images\laptop2.jpg" alt="Laptop" class="product-image">
                    <h3>UltraBook Pro</h3>
                    <p class="price">₹89,999</p>
                    <a href="#" class="add-to-cart-btn">Add to Cart</a>
                </div>
            
                <div class="product-card">
                    <img src="images\watch11.jpeg" alt="Smartwatch" class="product-image">
                    <h3>Smart Watch Z</h3>
                    <p class="price">₹14,999</p>
                    <a href="#" class="add-to-cart-btn">Add to Cart</a>
                </div>
               
                <div class="product-card">
                    <img src="images\headphone.jpg" alt="Headphones" class="product-image">
                    <h3>Pro-Audio Headphones</h3>
                    <p class="price">₹9,999</p>
                    <a href="#" class="add-to-cart-btn">Add to Cart</a>
                </div>
               
                <div class="product-card">
                    <img src="images\tablet.jpg" alt="Tablet" class="product-image">
                    <h3>Tablet A1</h3>
                    <p class="price">₹34,999</p>
                    <a href="#" class="add-to-cart-btn">Add to Cart</a>
                </div>
                
                <div class="product-card">
                    <img src="images\camera.jpg" alt="Camera" class="product-image">
                    <h3>Mirrorless Camera</h3>
                    <p class="price">₹1,29,999</p>
                    <a href="#" class="add-to-cart-btn">Add to Cart</a>
                </div>
            </div>
        </section>
    </main>

  
    <footer class="footer">
        <p>&copy; 2025 GadgetHub | All rights reserved.</p>
    </footer>
</body>
</html>

```
### contact.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GadgetHub - Contact</title>
    <link rel="stylesheet" href="css\style.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;700&display=swap" rel="stylesheet">
</head>
<body>
    <header class="header">
        <div class="logo">Gadget<span>Hub</span></div>
        <nav class="nav">
            <a href="index.html" class="nav-link">Home</a>
            <a href="products.html" class="nav-link">Products</a>
            <a href="contact.html" class="nav-link active">Contact</a>
        </nav>
    </header>

    <main class="main-content">
        <h1 class="page-title">Contact Us</h1>
        <section class="contact-section">
            <div class="contact-info">
                <h3>Get in Touch</h3>
                <p>Have a question or need assistance? Fill out the form or contact us directly.</p>
                <div class="contact-details">
                    <p><strong>Email:</strong> support@sanjayashwingadgethub.com</p>
                    <p><strong>Phone:</strong> +91 12345 67890</p>
                    <p><strong>Address:</strong> 123 Tech Lane, Innovation City, TamilNadu, India</p>
                </div>
            </div>
            <form class="contact-form">
                <div class="form-group">
                    <label for="name">Your Name</label>
                    <input type="text" id="name" name="name" required>
                </div>
                <div class="form-group">
                    <label for="email">Your Email</label>
                    <input type="email" id="email" name="email" required>
                </div>
                <div class="form-group">
                    <label for="message">Message</label>
                    <textarea id="message" name="message" rows="5" required></textarea>
                </div>
                <button type="submit" class="btn">Send Message</button>
            </form>
        </section>
    </main>

    <footer class="footer">
        <p>&copy; 2025 GadgetHub | All rights reserved.</p>
    </footer>
</body>
</html>

```
style.css
```

* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
}

:root {
    --primary-color: #a5f3fc; /* A bright, vibrant cyan */
    --secondary-color: #1e293b; /* Dark slate blue */
    --text-color: #f1f5f9; /* Off-white */
    --bg-color: #0f172a; /* Very dark blue */
}

body {
    font-family: 'Inter', sans-serif;
    background-color: var(--bg-color);
    color: var(--text-color);
    line-height: 1.6;
}


.container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 2rem;
}

.btn {
    display: inline-block;
    padding: 0.75rem 2rem;
    background-color: var(--primary-color);
    color: var(--secondary-color);
    text-decoration: none;
    font-weight: bold;
    border-radius: 9999px; /* Fully rounded pill shape */
    border: none;
    cursor: pointer;
    font-size: 1rem;
    text-align: center;
}

.btn:hover {
    background-color: #67e8f9; /* A slightly lighter cyan */
}

h1, h2 {
    color: var(--primary-color);
    text-align: center;
    margin-bottom: 1.5rem;
}

h1 {
    font-size: 3.5rem;
}

h2 {
    font-size: 2.5rem;
}

.page-title {
    margin-top: 2rem;
}

/* Header */
.header {
    background-color: var(--secondary-color);
    padding: 1rem 2rem;
    display: flex; /* Use Flexbox for layout */
    justify-content: space-between;
    align-items: center;
    border-bottom: 2px solid var(--primary-color);
    flex-wrap: wrap; /* Allow wrapping on small screens */
}

.logo {
    font-size: 2rem;
    font-weight: bold;
    color: var(--text-color);
}

.logo span {
    color: var(--primary-color);
}

.nav {
    display: flex; /* Use Flexbox for navigation links */
    gap: 1.5rem;
    flex-wrap: wrap;
}

.nav-link {
    color: var(--text-color);
    text-decoration: none;
    font-weight: bold;
    font-size: 1.1rem;
    padding-bottom: 0.25rem;
    border-bottom: 2px solid transparent;
}

.nav-link:hover, .nav-link.active {
    color: var(--primary-color);
    border-bottom: 2px solid var(--primary-color);
}

/* Hero Section */
.hero {
    display: flex; /* Use Flexbox for hero section */
    flex-wrap: wrap;
    justify-content: center;
    align-items: center;
    padding: 4rem 2rem;
    text-align: center;
    gap: 3rem;
}

.hero-content {
    flex: 1 1 500px;
    max-width: 600px;
}

.hero-content h1 {
    font-size: 4rem;
    text-align: left;
    margin-bottom: 1rem;
}

.hero-content p {
    font-size: 1.25rem;
    text-align: left;
    margin-bottom: 2rem;
}

.hero-image-container {
    flex: 1 1 500px;
    max-width: 600px;
}

.hero-image {
    max-width: 100%;
    height: auto;
    border-radius: 1rem;
    box-shadow: 0 10px 20px rgba(0, 0, 0, 0.5);
}

/* Products Section (for Home and Products pages) */
.products-section {
    padding: 4rem 2rem;
    text-align: center;
}

.products-container {
    display: flex; /* Use Flexbox for product cards */
    flex-wrap: wrap;
    justify-content: center;
    gap: 2rem;
    margin-top: 2rem;
}

.product-card {
    background-color: var(--secondary-color);
    padding: 1.5rem;
    border-radius: 1rem;
    box-shadow: 0 5px 15px rgba(0, 0, 0, 0.3);
    text-align: center;
    max-width: 300px;
    display: flex; /* Flexbox inside the card for alignment */
    flex-direction: column;
    align-items: center;
    gap: 0.75rem;
    flex: 1 1 250px;
}

.product-image {
    max-width: 100%;
    height: auto;
    border-radius: 0.5rem;
}

.product-card h3 {
    color: var(--primary-color);
    font-size: 1.5rem;
}

.price {
    font-weight: bold;
    font-size: 1.2rem;
}

.add-to-cart-btn {
    display: block;
    width: 100%;
    text-align: center;
    padding: 0.5rem 1rem;
    background-color: #67e8f9;
    color: var(--bg-color);
    border-radius: 9999px;
    text-decoration: none;
    font-weight: bold;
}

.add-to-cart-btn:hover {
    background-color: #38bdf8;
}


.contact-section {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    align-items: center;
    gap: 3rem;
    padding: 4rem 2rem;
}

.contact-info {
    flex: 1 1 400px;
    max-width: 500px;
}

.contact-info h3 {
    font-size: 2rem;
    color: var(--primary-color);
    margin-bottom: 1rem;
}

.contact-details {
    margin-top: 1rem;
    font-size: 1.1rem;
}

.contact-form {
    flex: 1 1 400px;
    max-width: 500px;
    display: flex;
    flex-direction: column;
    gap: 1.5rem;
    background-color: var(--secondary-color);
    padding: 2rem;
    border-radius: 1rem;
    box-shadow: 0 5px 15px rgba(0, 0, 0, 0.3);
}

.form-group {
    display: flex;
    flex-direction: column;
}

.form-group label {
    font-size: 1.1rem;
    font-weight: bold;
    margin-bottom: 0.5rem;
}

.form-group input,
.form-group textarea {
    background-color: var(--bg-color);
    border: 1px solid var(--primary-color);
    color: var(--text-color);
    padding: 0.75rem;
    border-radius: 0.5rem;
    font-size: 1rem;
}

.form-group textarea {
    resize: vertical;
}


.footer {
    background-color: var(--secondary-color);
    padding: 1.5rem;
    text-align: center;
    border-top: 2px solid var(--primary-color);
}



@media (max-width: 768px) {
    .header {
        flex-direction: column;
        text-align: center;
        gap: 1rem;
    }

    .hero-content {
        text-align: center;
    }

    .hero-content h1 {
        font-size: 2.5rem;
        text-align: center;
    }

    .hero-content p {
        font-size: 1rem;
        text-align: center;
    }

    .products-container {
        flex-direction: column;
        align-items: center;
    }

    .contact-section {
        flex-direction: column;
        text-align: center;
    }

    .contact-info {
        max-width: 100%;
    }
}

```
## OUTPUT
![first commercial](https://github.com/user-attachments/assets/1c65db9b-0fe3-4715-8e75-af98f4cffe9c)

<img width="1889" height="858" alt="image" src="https://github.com/user-attachments/assets/964010e0-5266-4204-b316-73ba78b30651" />
<img width="1898" height="907" alt="image" src="https://github.com/user-attachments/assets/f0611d85-0678-4cb8-a3b9-a9abdbc97c0f" />
<img width="1897" height="909" alt="image" src="https://github.com/user-attachments/assets/f646c746-8f79-4b9f-ba37-ee0f172f2b91" />


## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
