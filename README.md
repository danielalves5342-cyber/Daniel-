<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>VipShop - Sua Loja de Dropshipping Premium</title>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;700&family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <style>
        :root {
            --primary: #1a1a2e;
            --secondary: #16213e;
            --accent: #e94560;
            --gold: #ffd700;
            --light: #f5f5f5;
            --white: #ffffff;
            --text: #333333;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Inter', sans-serif;
            color: var(--text);
            line-height: 1.6;
            overflow-x: hidden;
        }

        /* Header */
        header {
            background: linear-gradient(135deg, var(--primary) 0%, var(--secondary) 100%);
            color: var(--white);
            position: fixed;
            width: 100%;
            top: 0;
            z-index: 1000;
            box-shadow: 0 4px 20px rgba(0,0,0,0.3);
        }

        .top-bar {
            background: rgba(0,0,0,0.2);
            padding: 8px 0;
            font-size: 0.85rem;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }

        .top-bar-content {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .top-bar span {
            display: flex;
            align-items: center;
            gap: 8px;
        }

        nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 15px 0;
        }

        .logo {
            font-family: 'Playfair Display', serif;
            font-size: 2.5rem;
            font-weight: 700;
            color: var(--gold);
            text-decoration: none;
            display: flex;
            align-items: center;
            gap: 10px;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.3);
        }

        .logo i {
            color: var(--accent);
        }

        .nav-links {
            display: flex;
            list-style: none;
            gap: 30px;
        }

        .nav-links a {
            color: var(--white);
            text-decoration: none;
            font-weight: 500;
            transition: all 0.3s;
            position: relative;
        }

        .nav-links a::after {
            content: '';
            position: absolute;
            bottom: -5px;
            left: 0;
            width: 0;
            height: 2px;
            background: var(--accent);
            transition: width 0.3s;
        }

        .nav-links a:hover::after {
            width: 100%;
        }

        .nav-icons {
            display: flex;
            gap: 20px;
            align-items: center;
        }

        .nav-icons a {
            color: var(--white);
            font-size: 1.2rem;
            position: relative;
            transition: transform 0.3s;
        }

        .nav-icons a:hover {
            transform: translateY(-3px);
            color: var(--gold);
        }

        .cart-count {
            position: absolute;
            top: -8px;
            right: -8px;
            background: var(--accent);
            color: white;
            border-radius: 50%;
            width: 20px;
            height: 20px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 0.75rem;
            font-weight: bold;
        }

        /* Hero Section */
        .hero {
            margin-top: 120px;
            height: 90vh;
            background: linear-gradient(rgba(26,26,46,0.7), rgba(22,33,62,0.8)), 
                        url('https://images.unsplash.com/photo-1441986300917-64674bd600d8?ixlib=rb-4.0.3&auto=format&fit=crop&w=1950&q=80') center/cover;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            color: var(--white);
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
            background: url('data:image/svg+xml,<svg width="100" height="100" xmlns="http://www.w3.org/2000/svg"><defs><pattern id="grid" width="100" height="100" patternUnits="userSpaceOnUse"><path d="M 100 0 L 0 0 0 100" fill="none" stroke="rgba(255,255,255,0.03)" stroke-width="1"/></pattern></defs><rect width="100%" height="100%" fill="url(%23grid)"/></svg>');
            pointer-events: none;
        }

        .hero-content {
            position: relative;
            z-index: 2;
            max-width: 800px;
            padding: 0 20px;
            animation: fadeInUp 1s ease-out;
        }

        @keyframes fadeInUp {
            from {
                opacity: 0;
                transform: translateY(30px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        .hero h1 {
            font-family: 'Playfair Display', serif;
            font-size: 4rem;
            margin-bottom: 20px;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.5);
            line-height: 1.2;
        }

        .hero p {
            font-size: 1.3rem;
            margin-bottom: 30px;
            opacity: 0.9;
        }

        .cta-buttons {
            display: flex;
            gap: 20px;
            justify-content: center;
            flex-wrap: wrap;
        }

        .btn {
            padding: 15px 40px;
            border: none;
            border-radius: 50px;
            font-size: 1rem;
            font-weight: 600;
            cursor: pointer;
            transition: all 0.3s;
            text-decoration: none;
            display: inline-flex;
            align-items: center;
            gap: 10px;
        }

        .btn-primary {
            background: linear-gradient(135deg, var(--accent) 0%, #ff6b6b 100%);
            color: white;
            box-shadow: 0 4px 15px rgba(233, 69, 96, 0.4);
        }

        .btn-primary:hover {
            transform: translateY(-3px);
            box-shadow: 0 6px 20px rgba(233, 69, 96, 0.6);
        }

        .btn-secondary {
            background: transparent;
            color: white;
            border: 2px solid white;
        }

        .btn-secondary:hover {
            background: white;
            color: var(--primary);
        }

        /* Features */
        .features {
            padding: 80px 0;
            background: var(--light);
        }

        .section-title {
            text-align: center;
            margin-bottom: 50px;
        }

        .section-title h2 {
            font-family: 'Playfair Display', serif;
            font-size: 2.5rem;
            color: var(--primary);
            margin-bottom: 15px;
        }

        .section-title p {
            color: #666;
            font-size: 1.1rem;
        }

        .features-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 30px;
        }

        .feature-card {
            background: white;
            padding: 40px 30px;
            border-radius: 15px;
            text-align: center;
            box-shadow: 0 5px 20px rgba(0,0,0,0.08);
            transition: all 0.3s;
            border-bottom: 3px solid transparent;
        }

        .feature-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 15px 40px rgba(0,0,0,0.15);
            border-bottom-color: var(--accent);
        }

        .feature-icon {
            width: 80px;
            height: 80px;
            background: linear-gradient(135deg, var(--primary) 0%, var(--secondary) 100%);
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            margin: 0 auto 20px;
            font-size: 2rem;
            color: var(--gold);
        }

        .feature-card h3 {
            margin-bottom: 10px;
            color: var(--primary);
        }

        /* Products */
        .products {
            padding: 80px 0;
            background: white;
        }

        .products-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 30px;
        }

        .product-card {
            background: white;
            border-radius: 15px;
            overflow: hidden;
            box-shadow: 0 5px 20px rgba(0,0,0,0.08);
            transition: all 0.3s;
            position: relative;
        }

        .product-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 15px 40px rgba(0,0,0,0.15);
        }

        .product-badge {
            position: absolute;
            top: 15px;
            left: 15px;
            background: var(--accent);
            color: white;
            padding: 5px 15px;
            border-radius: 20px;
            font-size: 0.8rem;
            font-weight: 600;
            z-index: 2;
        }

        .product-image {
            height: 300px;
            background: #f0f0f0;
            position: relative;
            overflow: hidden;
        }

        .product-image img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            transition: transform 0.5s;
        }

        .product-card:hover .product-image img {
            transform: scale(1.1);
        }

        .product-actions {
            position: absolute;
            bottom: -50px;
            left: 0;
            right: 0;
            display: flex;
            justify-content: center;
            gap: 10px;
            padding: 15px;
            background: linear-gradient(to top, rgba(0,0,0,0.8), transparent);
            transition: bottom 0.3s;
        }

        .product-card:hover .product-actions {
            bottom: 0;
        }

        .action-btn {
            width: 40px;
            height: 40px;
            border-radius: 50%;
            background: white;
            border: none;
            cursor: pointer;
            display: flex;
            align-items: center;
            justify-content: center;
            transition: all 0.3s;
            color: var(--primary);
        }

        .action-btn:hover {
            background: var(--accent);
            color: white;
        }

        .product-info {
            padding: 20px;
        }

        .product-category {
            color: var(--accent);
            font-size: 0.85rem;
            font-weight: 600;
            text-transform: uppercase;
            letter-spacing: 1px;
        }

        .product-title {
            font-size: 1.1rem;
            margin: 10px 0;
            color: var(--primary);
            font-weight: 600;
        }

        .product-price {
            display: flex;
            align-items: center;
            gap: 10px;
        }

        .current-price {
            font-size: 1.4rem;
            font-weight: 700;
            color: var(--accent);
        }

        .old-price {
            text-decoration: line-through;
            color: #999;
            font-size: 0.9rem;
        }

        /* Categories */
        .categories {
            padding: 80px 0;
            background: linear-gradient(135deg, var(--primary) 0%, var(--secondary) 100%);
            color: white;
        }

        .categories .section-title h2,
        .categories .section-title p {
            color: white;
        }

        .categories-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 20px;
        }

        .category-card {
            background: rgba(255,255,255,0.1);
            backdrop-filter: blur(10px);
            border: 1px solid rgba(255,255,255,0.2);
            border-radius: 15px;
            padding: 40px 20px;
            text-align: center;
            transition: all 0.3s;
            cursor: pointer;
        }

        .category-card:hover {
            background: rgba(255,255,255,0.2);
            transform: translateY(-5px);
        }

        .category-icon {
            font-size: 3rem;
            margin-bottom: 15px;
            color: var(--gold);
        }

        .category-card h3 {
            font-size: 1.2rem;
            margin-bottom: 5px;
        }

        .category-card span {
            font-size: 0.9rem;
            opacity: 0.8;
        }

        /* Newsletter */
        .newsletter {
            padding: 100px 0;
            background: linear-gradient(rgba(26,26,46,0.9), rgba(26,26,46,0.9)), 
                        url('https://images.unsplash.com/photo-1556742049-0cfed4f6a45d?ixlib=rb-4.0.3&auto=format&fit=crop&w=1950&q=80') center/cover fixed;
            color: white;
            text-align: center;
        }

        .newsletter-form {
            max-width: 600px;
            margin: 30px auto 0;
            display: flex;
            gap: 10px;
            padding: 0 20px;
        }

        .newsletter-form input {
            flex: 1;
            padding: 15px 25px;
            border: none;
            border-radius: 50px;
            font-size: 1rem;
            outline: none;
        }

        .newsletter-form button {
            padding: 15px 30px;
            background: var(--accent);
            color: white;
            border: none;
            border-radius: 50px;
            font-weight: 600;
            cursor: pointer;
            transition: all 0.3s;
        }

        .newsletter-form button:hover {
            background: #ff6b6b;
            transform: scale(1.05);
        }

        /* Footer */
        footer {
            background: var(--primary);
            color: white;
            padding: 60px 0 20px;
        }

        .footer-content {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 40px;
            margin-bottom: 40px;
        }

        .footer-section h3 {
            color: var(--gold);
            margin-bottom: 20px;
            font-family: 'Playfair Display', serif;
        }

        .footer-section p {
            opacity: 0.8;
            line-height: 1.8;
            margin-bottom: 20px;
        }

        .footer-links {
            list-style: none;
        }

        .footer-links li {
            margin-bottom: 10px;
        }

        .footer-links a {
            color: rgba(255,255,255,0.8);
            text-decoration: none;
            transition: color 0.3s;
            display: flex;
            align-items: center;
            gap: 10px;
        }

        .footer-links a:hover {
            color: var(--gold);
            padding-left: 5px;
        }

        .social-links {
            display: flex;
            gap: 15px;
            margin-top: 20px;
        }

        .social-links a {
            width: 40px;
            height: 40px;
            background: rgba(255,255,255,0.1);
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            transition: all 0.3s;
        }

        .social-links a:hover {
            background: var(--accent);
            transform: translateY(-3px);
        }

        .footer-bottom {
            border-top: 1px solid rgba(255,255,255,0.1);
            padding-top: 20px;
            text-align: center;
            opacity: 0.6;
            font-size: 0.9rem;
        }

        .payment-methods {
            display: flex;
            gap: 15px;
            margin-top: 20px;
            font-size: 2rem;
            color: rgba(255,255,255,0.6);
        }

        /* Mobile Menu */
        .mobile-menu-btn {
            display: none;
            background: none;
            border: none;
            color: white;
            font-size: 1.5rem;
            cursor: pointer;
        }

        /* Responsive */
        @media (max-width: 768px) {
            .nav-links {
                display: none;
            }

            .mobile-menu-btn {
                display: block;
            }

            .hero {
                margin-top: 100px;
                height: 70vh;
            }

            .hero h1 {
                font-size: 2.5rem;
            }

            .hero p {
                font-size: 1rem;
            }

            .newsletter-form {
                flex-direction: column;
            }

            .logo {
                font-size: 1.8rem;
            }
        }

        /* Animations */
        .scroll-reveal {
            opacity: 0;
            transform: translateY(30px);
            transition: all 0.8s;
        }

        .scroll-reveal.active {
            opacity: 1;
            transform: translateY(0);
        }
    </style>
</head>
<body>

    <!-- Header -->
    <header>
        <div class="top-bar">
            <div class="container">
                <div class="top-bar-content">
                    <span><i class="fas fa-truck"></i> Frete Grátis para todo o Pará em compras acima de R$ 199</span>
                    <span><i class="fas fa-phone"></i> (91) 98765-4321</span>
                </div>
            </div>
        </div>
        <div class="container">
            <nav>
                <a href="#" class="logo">
                    <i class="fas fa-crown"></i>
                    VipShop
                </a>
                <ul class="nav-links">
                    <li><a href="#home">Início</a></li>
                    <li><a href="#produtos">Produtos</a></li>
                    <li><a href="#categorias">Categorias</a></li>
                    <li><a href="#ofertas">Ofertas</a></li>
                    <li><a href="#contato">Contato</a></li>
                </ul>
                <div class="nav-icons">
                    <a href="#"><i class="fas fa-search"></i></a>
                    <a href="#"><i class="fas fa-user"></i></a>
                    <a href="#"><i class="fas fa-heart"></i></a>
                    <a href="#" style="position: relative;">
                        <i class="fas fa-shopping-bag"></i>
                        <span class="cart-count">3</span>
                    </a>
                    <button class="mobile-menu-btn"><i class="fas fa-bars"></i></button>
                </div>
            </nav>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="hero" id="home">
        <div class="hero-content">
            <h1>Eleve Seu Estilo com a VipShop</h1>
            <p>Produtos selecionados de alta qualidade com entrega rápida para todo o Brasil. Sua satisfação é nossa prioridade.</p>
            <div class="cta-buttons">
                <a href="#produtos" class="btn btn-primary">
                    <i class="fas fa-shopping-bag"></i>
                    Comprar Agora
                </a>
                <a href="#categorias" class="btn btn-secondary">
                    Ver Coleções
                </a>
            </div>
        </div>
    </section>

    <!-- Features -->
    <section class="features">
        <div class="container">
            <div class="section-title scroll-reveal">
                <h2>Por que escolher a VipShop?</h2>
                <p>Oferecemos a melhor experiência de compra online</p>
            </div>
            <div class="features-grid">
                <div class="feature-card scroll-reveal">
                    <div class
