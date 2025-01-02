# Hydroponic-Systems
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hydroponic Plants & Systems</title>
    <style>
        body {
            font-family: 'Roboto', Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
            color: #333;
        }
        header {
            background-color: #4CAF50;
            color: white;
            padding: 1.5em 0;
            text-align: center;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #333;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
        nav a {
            color: white;
            padding: 1em 2em;
            text-decoration: none;
            font-weight: bold;
        }
        nav a:hover {
            background-color: #575757;
            border-radius: 4px;
        }
        .hero {
            text-align: center;
            padding: 3em;
            background: linear-gradient(to right, #e0f7fa, #e8f5e9);
            border-bottom: 2px solid #ddd;
        }
        .hero h1 {
            color: #4CAF50;
            font-size: 2.5em;
        }
        .hero p {
            font-size: 1.2em;
            color: #555;
        }
        .products {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2em;
            padding: 2em;
            background-color: #fff;
        }
        .product {
            border: 1px solid #ddd;
            border-radius: 8px;
            padding: 1.5em;
            text-align: center;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease;
        }
        .product:hover {
            transform: translateY(-5px);
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }
        .product img {
            max-width: 100%;
            border-radius: 8px;
            margin-bottom: 1em;
        }
        .product h2 {
            color: #4CAF50;
            margin: 0.5em 0;
        }
        .product p {
            font-size: 1em;
            color: #555;
        }
        .footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 1.5em 0;
            margin-top: 2em;
        }
        .footer a {
            color: lightblue;
            text-decoration: none;
        }
        .footer a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <header>
        <h1>Hydroponic Plants & Systems</h1>
        <p>Grow Fresh, Live Green</p>
    </header>
    <nav>
        <a href="#plants">Plants</a>
        <a href="#systems">Systems</a>
        <a href="#contact">Contact</a>
    </nav>
    <section class="hero">
        <h1>Welcome to Your Hydroponic Garden</h1>
        <p>Discover sustainable solutions for growing plants efficiently.</p>
    </section>
    <section class="products" id="plants">
        <div class="product">
            <img src="https://via.placeholder.com/300" alt="Basil Plant">
            <h2>Basil Plant</h2>
            <p>Price: $5</p>
        </div>
        <div class="product">
            <img src="https://via.placeholder.com/300" alt="Lettuce Plant">
            <h2>Lettuce Plant</h2>
            <p>Price: $4</p>
        </div>
        <div class="product">
            <img src="https://via.placeholder.com/300" alt="Mint Plant">
            <h2>Mint Plant</h2>
            <p>Price: $6</p>
        </div>
    </section>
    <section class="products" id="systems">
        <div class="product">
            <img src="https://via.placeholder.com/300" alt="Starter Kit">
            <h2>Hydroponic Starter Kit</h2>
            <p>Price: $50</p>
        </div>
        <div class="product">
            <img src="https://via.placeholder.com/300" alt="Advanced Kit">
            <h2>Advanced Hydroponic System</h2>
            <p>Price: $120</p>
        </div>
    </section>
    <footer class="footer" id="contact">
        <p>Contact us at <a href="mailto:info@hydroponics.com">info@hydroponics.com</a></p>
        <p>Follow us on <a href="#">Social Media</a></p>
    </footer>
</body>
</html>
