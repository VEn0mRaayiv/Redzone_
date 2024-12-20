
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Red Zone - MMA Clothing</title>
    <style>
        /* General Styles */
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            background-color: #f4f4f4;
        }
        a {
            text-decoration: none;
            transition: all 0.3s ease;
        }
        h1, h2, h3, p {
            margin: 0;
            padding: 0;
        }
        img {
            max-width: 100%;
            height: auto;
        }

        /* Header */
        header {
            background-color: #000;
            color: #fff;
            padding: 20px 50px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            position: fixed;
            width: 100%;
            top: 0;
            z-index: 10;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.5);
        }
        header .logo {
            font-size: 28px;
            font-weight: bold;
            color: #e63946;
        }
        header nav a {
            color: #fff;
            margin: 0 15px;
            font-size: 16px;
        }
        header nav a:hover {
            color: #e63946;
        }

        /* Hero Section */
        .hero {
            background: url('https://via.placeholder.com/1500x800') no-repeat center center/cover;
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            color: #fff;
            text-align: center;
            position: relative;
        }
        .hero::after {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(0, 0, 0, 0.6);
            z-index: 1;
        }
        .hero-content {
            position: relative;
            z-index: 2;
        }
        .hero h1 {
            font-size: 60px;
            text-transform: uppercase;
        }
        .hero p {
            font-size: 24px;
            margin: 20px 0;
        }
        .hero a {
            background-color: #e63946;
            color: #fff;
            padding: 15px 40px;
            font-size: 18px;
            font-weight: bold;
            border-radius: 5px;
        }
        .hero a:hover {
            background-color: #c52f3a;
        }

        /* Categories Section */
        .categories {
            padding: 70px 20px;
            background-color: #fff;
            text-align: center;
        }
        .categories h2 {
            font-size: 36px;
            color: #e63946;
            margin-bottom: 20px;
        }
        .categories-grid {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
        }
        .category {
            width: 30%;
            margin: 15px;
            padding: 20px;
            background: #f4f4f4;
            border-radius: 10px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s;
        }
        .category:hover {
            transform: translateY(-10px);
        }
        .category img {
            border-radius: 10px;
        }
        .category h3 {
            margin: 15px 0;
            font-size: 20px;
            color: #333;
        }

        /* Footer */
        footer {
            background-color: #000;
            color: #fff;
            text-align: center;
            padding: 20px 0;
            margin-top: 50px;
        }
        footer p {
            font-size: 14px;
        }
    </style>
</head>
<body>
    <header>
        <div class="logo">Red Zone</div>
        <nav>
            <a href="#home">Home</a>
            <a href="#products">Products</a>
            <a href="#about">About</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <div class="hero" id="home">
        <div class="hero-content">
            <h1>Welcome to Red Zone</h1>
            <p>Gear Up. Fight Strong. Look Sharp.</p>
            <a href="#products">Shop Now</a>
        </div>
    </div>

    <section class="categories" id="products">
        <h2>Our Products</h2>
        <div class="categories-grid">
            <div class="category">
                <img src="https://via.placeholder.com/300x200" alt="T-Shirts">
                <h3>T-Shirts</h3>
            </div>
            <div class="category">
                <img src="https://via.placeholder.com/300x200" alt="Shorts">
                <h3>Shorts</h3>
            </div>
            <div class="category">
                <img src="https://via.placeholder.com/300x200" alt="Gloves">
                <h3>Gloves</h3>
            </div>
        </div>
    </section>

    <footer>
        <p>&copy; 2024 Red Zone. All Rights Reserved.</p>
    </footer>
</body>
</html
