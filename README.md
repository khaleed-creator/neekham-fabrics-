# neekham-fabrics-
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Neekham Fabrics | Quality Fashion & Fabrics</title>

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }

        body {
            background: #fffaf5;
            color: #222;
        }

        /* HEADER */
        header {
            background: linear-gradient(135deg, #5b0f0f, #9e2a2a);
            color: white;
            padding: 18px 5%;
            position: sticky;
            top: 0;
            z-index: 1000;
            box-shadow: 0 3px 10px rgba(0,0,0,0.2);
        }

        .navbar {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .logo {
            font-size: 26px;
            font-weight: bold;
        }

        .logo span {
            color: #ffd166;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin-left: 20px;
            font-weight: bold;
        }

        nav a:hover {
            color: #ffd166;
        }

        /* HERO */
        .hero {
            min-height: 85vh;
            display: flex;
            justify-content: center;
            align-items: center;
            text-align: center;
            padding: 40px 20px;
            background:
                linear-gradient(rgba(50,0,0,0.65), rgba(50,0,0,0.65)),
                url("https://images.unsplash.com/photo-1558769132-cb1aea458c5e?auto=format&fit=crop&w=1600&q=80");
            background-size: cover;
            background-position: center;
        }

        .hero-content {
            color: white;
            max-width: 750px;
        }

        .hero h1 {
            font-size: 55px;
            margin-bottom: 15px;
        }

        .hero h1 span {
            color: #ffd166;
        }

        .hero p {
            font-size: 20px;
            line-height: 1.6;
            margin-bottom: 25px;
        }

        .btn {
            display: inline-block;
            background: #ffd166;
            color: #5b0f0f;
            padding: 14px 25px;
            border-radius: 30px;
            text-decoration: none;
            font-weight: bold;
            margin: 5px;
            transition: 0.3s;
        }

        .btn:hover {
            transform: scale(1.05);
            background: white;
        }

        .btn-whatsapp {
            background: #25D366;
            color: white;
        }

        /* SECTIONS */
        section {
            padding: 70px 7%;
        }

        .section-title {
            text-align: center;
            margin-bottom: 40px;
        }

        .section-title h2 {
            color: #5b0f0f;
            font-size: 35px;
            margin-bottom: 10px;
        }

        .section-title p {
            color: #666;
        }

        /* PRODUCTS */
        .products {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 25px;
        }

        .product {
            background: white;
            border-radius: 15px;
            overflow: hidden;
            box-shadow: 0 5px 20px rgba(0,0,0,0.12);
            transition: 0.3s;
            text-align: center;
        }

        .product:hover {
            transform: translateY(-8px);
        }

        .product img {
            width: 100%;
            height: 200px;
            object-fit: cover;
        }

        .product h3 {
            color: #5b0f0f;
            padding: 15px 10px 5px;
        }

        .product p {
            color: #777;
            padding: 5px 15px 20px;
        }

        /* ABOUT */
        .about {
            background: #f5e9df;
        }

        .about-content {
            max-width: 850px;
            margin: auto;
            text-align: center;
        }

        .about-content p {
            font-size: 18px;
            line-height: 1.8;
            color: #444;
        }

        /* CONTACT */
        .contact {
            background: #5b0f0f;
            color: white;
        }

        .contact .section-title h2 {
            color: #ffd166;
        }

        .contact-container {
            max-width: 700px;
            margin: auto;
            text-align: center;
        }

        .contact-item {
            background: rgba(255,255,255,0.1);
            margin: 15px 0;
            padding: 18px;
            border-radius: 12px;
        }

        .contact-item a {
            color: white;
            text-decoration: none;
            font-size: 18px;
        }

        .contact-item a:hover {
            color: #ffd166;
        }

        /* FOOTER */
        footer {
            background: #260606;
            color: white;
            text-align: center;
            padding: 25px;
        }

        footer span {
            color: #ffd166;
        }

        /* MOBILE */
        @media (max-width: 700px) {

            .navbar {
                flex-direction: column;
                gap: 12px;
            }

            nav a {
                margin: 0 7px;
                font-size: 14px;
            }

            .hero h1 {
                font-size: 38px;
            }

            .hero p {
                font-size: 17px;
            }

            section {
                padding: 50px 5%;
            }
        }
    </style>
</head>

<body>

<!-- HEADER -->
<header>
    <div class="navbar">

        <div class="logo">
            NEEKHAM <span>FABRICS</span>
        </div>

        <nav>
            <a href="#home">Home</a>
            <a href="#products">Products</a>
            <a href="#about">About</a>
            <a href="#contact">Contact</a>
        </nav>

    </div>
</header>


<!-- HERO -->
<section class="hero" id="home">

    <div class="hero-content">

        <h1>
            Welcome to <span>Neekham Fabrics</span>
        </h1>

        <p>
            Your trusted destination for quality fabrics,
            fashionable clothing and stylish ready-to-wear outfits.
        </p>

        <a href="#products" class="btn">
            Explore Our Products
        </a>

        <a href="https://wa.me/2348152648027" class="btn btn-whatsapp">
            💬 Chat on WhatsApp
        </a>

    </div>

</section>


<!-- PRODUCTS -->
<section id="products">

    <div class="section-title">
        <h2>Our Products</h2>
        <p>Quality fashion materials and clothing for every occasion.</p>
    </div>

    <div class="products">

        <div class="product">
            <img src="https://images.unsplash.com/photo-1594633312681-425c7b97ccd1?auto=format&fit=crop&w=600&q=80">
            <h3>Clothes</h3>
            <p>Beautiful and quality clothing.</p>
        </div>

        <div class="product">
            <img src="https://images.unsplash.com/photo-1610030469983-98e550d6193c?auto=format&fit=crop&w=600&q=80">
            <h3>Damask</h3>
            <p>Elegant and premium Damask fabrics.</p>
        </div>

        <div class="product">
            <img src="https://images.unsplash.com/photo-1551488831-00ddcb6c6bd3?auto=format&fit=crop&w=600&q=80">
            <h3>Lace</h3>
            <p>Beautiful lace materials for special occasions.</p>
        </div>

        <div class="product">
            <img src="https://images.unsplash.com/photo-1605763240000-7e93b172d754?auto=format&fit=crop&w=600&q=80">
            <h3>Swiss Lace</h3>
            <p>Stylish Swiss lace designs.</p>
        </div>

        <div class="product">
            <img src="https://images.unsplash.com/photo-1601121141461-9d6647bca1ed?auto=format&fit=crop&w=600&q=80">
            <h3>French Lace</h3>
            <p>Premium French lace collections.</p>
        </div>

        <div class="product">
            <img src="https://images.unsplash.com/photo-1583743814966-8936f37f4f3a?auto=format&fit=crop&w=600&q=80">
            <h3>Ankara</h3>
            <p>Colorful and fashionable Ankara prints.</p>
        </div>

        <div class="product">
            <img src="https://images.unsplash.com/photo-1551488831-00ddcb6c6bd3?auto=format&fit=crop&w=600&q=80">
            <h3>Ready-to-Wear</h3>
            <p>Trendy outfits ready for you to wear.</p>
        </div>

        <div class="product">
            <img src="https://images.unsplash.com/photo-1542272604-787c3835535d?auto=format&fit=crop&w=600&q=80">
            <h3>Jeans</h3>
            <p>Stylish jeans for everyday fashion.</p>
        </div>

        <div class="product">
            <img src="https://images.unsplash.com/photo-1521369909029-2afed882baee?auto=format&fit=crop&w=600&q=80">
            <h3>Caps</h3>
            <p>Fashionable caps to complete your outfit.</p>
        </div>

    </div>

</section>


<!-- ABOUT -->
<section class="about" id="about">

    <div class="section-title">
        <h2>About Neekham Fabrics</h2>
    </div>

    <div class="about-content">

        <p>
            At <strong>Neekham Fabrics</strong>, we provide quality fabrics
            and fashionable clothing for people who love to look stylish.
            From beautiful Damask, Lace, Swiss Lace, French Lace and Ankara
            to Ready-to-Wear outfits, Jeans and Caps, we have something
            for everyone.
        </p>

        <br>

        <p>
            Our goal is to provide quality fashion products while giving
            our customers a great shopping experience.
        </p>

    </div>

</section>


<!-- CONTACT -->
<section class="contact" id="contact">

    <div class="section-title">
        <h2>Contact Us</h2>
        <p>We would love to hear from you!</p>
    </div>

    <div class="contact-container">

        <div class="contact-item">
            📞
            <a href="tel:08152648027">
                08152648027
            </a>
        </div>

        <div class="contact-item">
            📞
            <a href="tel:09071305235">
                09071305235
            </a>
        </div>

        <div class="contact-item">
            📧
            <a href="mailto:Meddynataromire@gmail.com">
                Meddynataromire@gmail.com
            </a>
        </div>

        <br>

        <a href="https://wa.me/2348152648027" class="btn btn-whatsapp">
            💬 Message Us on WhatsApp
        </a>

    </div>

</section>


<!-- FOOTER -->
<footer>

    <p>
        © 2026 <span>Neekham Fabrics</span>.
        All Rights Reserved.
    </p>

</footer>

</body>
</html>