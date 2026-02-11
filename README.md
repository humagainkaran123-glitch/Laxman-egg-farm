# Laxman-egg-farm
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Karun Egg Farm</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #fff8f0;
            color: #333;
        }
        header {
            background-color: #f4a261;
            color: white;
            text-align: center;
            padding: 20px 0;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #e76f51;
        }
        nav a {
            color: white;
            text-decoration: none;
            padding: 15px 20px;
            font-weight: bold;
        }
        nav a:hover {
            background-color: #f4a261;
        }
        section {
            padding: 40px 20px;
            max-width: 1000px;
            margin: auto;
        }
        h2 {
            color: #e76f51;
        }
        .products {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
        }
        .product {
            flex: 1 1 200px;
            border: 1px solid #e0e0e0;
            padding: 20px;
            border-radius: 10px;
            background-color: #fff3e6;
            text-align: center;
        }
        .contact form {
            display: flex;
            flex-direction: column;
            max-width: 500px;
            margin: auto;
        }
        .contact input, .contact textarea {
            padding: 10px;
            margin: 10px 0;
            border-radius: 5px;
            border: 1px solid #ccc;
        }
        .contact button {
            padding: 10px;
            background-color: #e76f51;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-weight: bold;
        }
        .contact button:hover {
            background-color: #f4a261;
        }
        footer {
            background-color: #e76f51;
            color: white;
            text-align: center;
            padding: 15px 0;
            margin-top: 40px;
        }
    </style>
</head>
<body>

<header>
    <h1>Karun Egg Farm</h1>
    <p>Fresh & Healthy Eggs from Our Farm to Your Home</p>
</header>

<nav>
    <a href="#home">Home</a>
    <a href="#about">About Us</a>
    <a href="#products">Products</a>
    <a href="#contact">Contact</a>
</nav>

<section id="home">
    <h2>Welcome to Karun Egg Farm</h2>
    <p>We raise healthy hens and provide fresh eggs daily. Our farm is family-run, and we take pride in quality and care for our hens.</p>
</section>

<section id="about">
    <h2>About Us</h2>
    <p>Our farm is located in Nepal, and we have 260 hens raised in two spacious coops. We ensure proper feeding, sunlight, and care for all our hens. Our eggs are collected daily and delivered fresh to our customers.</p>
</section>

<section id="products">
    <h2>Our Products</h2>
    <div class="products">
        <div class="product">
            <h3>Fresh Eggs</h3>
            <p>Price: NPR 12 per dozen</p>
            <p>Collected daily from healthy hens.</p>
        </div>
        <div class="product">
            <h3>Bulk Orders</h3>
            <p>Special pricing for hotels, bakeries, and shops.</p>
            <p>Contact us for details.</p>
        </div>
    </div>
</section>

<section id="contact" class="contact">
    <h2>Contact Us / Order</h2>
    <form>
        <input type="text" placeholder="Your Name" required>
        <input type="email" placeholder="Your Email" required>
        <textarea placeholder="Message / Order Details" rows="5" required></textarea>
        <button type="submit">Send Message</button>
    </form>
    <p style="text-align:center; margin-top:10px;">Or contact us directly via WhatsApp: +977-XXXXXXXXX</p>
</section>

<footer>
    <p>© 2026 Karun Egg Farm. All Rights Reserved.</p>
</footer>

</body>
</html>
