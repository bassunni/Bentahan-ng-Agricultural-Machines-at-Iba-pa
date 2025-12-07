<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Basunni Agri Store</title>
    <link rel="stylesheet" href="style.css">
    <script defer src="script.js"></script>
</head>
<body>

<header>
    <h1>Basunni Agri Store</h1>
    <p>Fresh • Wholesale • Direct from Farmers</p>
</header>

<nav>
    <a href="index.html">Products</a>
    <a href="#about">About</a>
    <a href="#contact">Contact</a>
    <a href="cart.html" class="cart-link">🛒 Cart (<span id="cart-count">0</span>)</a>
</nav>

<section id="hero">
    <h2>Quality Agricultural Goods at Affordable Prices</h2>
    <a href="#products" class="btn">Shop Now</a>
</section>

<section id="products">
    <h2>Our Products</h2>

    <div class="grid">

        <div class="card">
            <img src="https://via.placeholder.com/400x250" alt="Vegetables">
            <h3>Assorted Vegetables (per kilo)</h3>
            <p>Carrots, cabbage, onions, tomatoes, leafy greens.</p>
            <span class="price">₱120</span>
            <button onclick="addToCart('Assorted Vegetables', 120)">Add to Cart</button>
        </div>

        <div class="card">
            <img src="https://via.placeholder.com/400x250" alt="Rice">
            <h3>Well-Milled Rice (per sack)</h3>
            <p>High-quality rice, wholesale available.</p>
            <span class="price">₱2,200</span>
            <button onclick="addToCart('Well-Milled Rice', 2200)">Add to Cart</button>
        </div>

        <div class="card">
            <img src="https://via.placeholder.com/400x250" alt="Corn">
            <h3>Yellow Corn (per kilo)</h3>
            <p>Fresh and clean corn for feeds or consumption.</p>
            <span class="price">₱35</span>
            <button onclick="addToCart('Yellow Corn', 35)">Add to Cart</button>
        </div>

        <div class="card">
            <img src="https://via.placeholder.com/400x250" alt="Equipment">
            <h3>Mini Tiller Machine</h3>
            <p>Available in diesel and gasoline versions.</p>
            <span class="price">₱18,000</span>
            <button onclick="addToCart('Mini Tiller Machine', 18000)">Add to Cart</button>
        </div>

    </div>
</section>

<section id="about">
    <h2>About Us</h2>
    <p>
        Basunni Agri Store delivers affordable, high-quality farm products straight from growers and suppliers.
        We serve Negros Oriental and nearby islands with honesty, fairness, and fresh goods.
    </p>
</section>

<section id="contact">
    <h2>Contact & Orders</h2>

    <div class="contact-box">
        <p><strong>Phone:</strong> 0912-345-6789</p>
        <p><strong>Email:</strong> basunni.agri@gmail.com</p>
        <p><strong>Facebook:</strong> Basunni Agri Store</p>
    </div>

    <p>For faster orders, use the **Cart + Checkout** system.</p>
</section>

<footer>
    <p>© 2025 Basunni Agri Store</p>
</footer>

</body>
</html># Bentahan-ng-Agricultural-Machines-at-Iba-pa
Agricultural Machines Store and more
