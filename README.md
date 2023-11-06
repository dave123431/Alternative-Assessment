<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>E-Commerce Website</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #333;
            color: #fff;
            padding: 10px 0;
            text-align: center;
        }

        nav {
            background-color: #444;
            padding: 10px 0;
            text-align: center;
        }

        nav a {
            color: #fff;
            text-decoration: none;
            margin: 0 15px;
        }

        .product {
            margin: 20px;
            padding: 20px;
            border: 1px solid #ccc;
            text-align: center;
            width: 200px;
            display: inline-block;
        }

        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>

<body>
    <header>
        <h1>E-Commerce Store</h1>
    </header>

    <nav>
        <a href="#">Home</a>
        <a href="#">Products</a>
        <a href="#">Contact</a>
    </nav>

    <div class="product">
        <img src="product1.jpg" alt="Product 1">
        <h2>Product 1</h2>
        <p>Description of Product 1. Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
        <button>Add to Cart</button>
    </div>

    <div class="product">
        <img src="product2.jpg" alt="Product 2">
        <h2>Product 2</h2>
        <p>Description of Product 2. Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
        <button>Add to Cart</button>
    </div>

    <div class="product">
        <img src="product3.jpg" alt="Product 3">
        <h2>Product 3</h2>
        <p>Description of Product 3. Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
        <button>Add to Cart</button>
    </div>

    <footer>
        &copy; 2023 E-Commerce Store. All rights reserved.
    </footer>
</body>

</html>
