<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Izalmodz Hosting Store</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            background: linear-gradient(135deg, #6a11cb 0%, #2575fc 100%);
            color: #fff;
            min-height: 100vh;
            padding: 20px;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
        }
        
        header {
            text-align: center;
            padding: 20px 0;
            margin-bottom: 30px;
        }
        
        .logo {
            font-size: 3rem;
            margin-bottom: 10px;
            color: #ffcc00;
        }
        
        h1 {
            font-size: 2.5rem;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.3);
            margin-bottom: 10px;
        }
        
        .tagline {
            font-size: 1.2rem;
            opacity: 0.9;
        }
        
        .products {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
            margin-bottom: 40px;
        }
        
        .product-card {
            background: rgba(255, 255, 255, 0.1);
            border-radius: 15px;
            padding: 25px;
            backdrop-filter: blur(10px);
            border: 1px solid rgba(255, 255, 255, 0.2);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
            display: flex;
            flex-direction: column;
        }
        
        .product-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.2);
        }
        
        .product-icon {
            font-size: 2.5rem;
            margin-bottom: 15px;
            color: #ffcc00;
            text-align: center;
        }
        
        .product-title {
            font-size: 1.5rem;
            margin-bottom: 10px;
            text-align: center;
        }
        
        .product-price {
            font-size: 1.8rem;
            font-weight: bold;
            color: #ffcc00;
            text-align: center;
            margin-bottom: 15px;
        }
        
        .product-description {
            margin-bottom: 20px;
            flex-grow: 1;
            opacity: 0.9;
            text-align: center;
        }
        
        .product-features {
            margin-bottom: 20px;
            padding-left: 20px;
        }
        
        .product-features li {
            margin-bottom: 8px;
            opacity: 0.9;
        }
        
        .cta-button {
            display: block;
            background: linear-gradient(to right, #ffcc00, #ff9900);
            color: #333;
            text-align: center;
            padding: 12px;
            border-radius: 50px;
            text-decoration: none;
            font-weight: bold;
            transition: all 0.3s ease;
            margin-top: auto;
        }
        
        .cta-button:hover {
            background: linear-gradient(to right, #ff9900, #ffcc00);
            transform: scale(1.05);
        }
        
        .telegram-float {
            position: fixed;
            bottom: 20px;
            right: 20px;
            z-index: 100;
        }
        
        .telegram-button {
            display: flex;
            align-items: center;
            justify-content: center;
            background: #0088cc;
            color: white;
            width: 60px;
            height: 60px;
            border-radius: 50%;
            text-decoration: none;
            font-size: 1.8rem;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.3);
            transition: all 0.3s ease;
        }
        
        .telegram-button:hover {
            transform: scale(1.1);
            background: #006da3;
        }
        
        footer {
            text-align: center;
            padding: 20px;
            margin-top: 40px;
            opacity: 0.8;
            font-size: 0.9rem;
        }
        
        @media (max-width: 768px) {
            .products {
                grid-template-columns: 1fr;
            }
            
            h1 {
                font-size: 2rem;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <div class="logo">
                <i class="fas fa-server"></i>
            </div>
            <h1>Izalmodz Hosting Store</h1>
            <p class="tagline">Layanan Hosting Terbaik dengan Harga Terjangkau</p>
        </header>
        
        <div class="products">
            <div class="product-card">
                <div class="product-icon">
                    <i class="fas fa-crown"></i>
                </div>
                <h3 class="product-title">Murband 15K</h3>
                <div class="product-price">Rp 15.000</div>
                <p class="product-description">Paket hosting murah dengan bandwidth besar</p>
                <ul class="product-features">
                    <li><i class="fas fa-check"></i> Unlimited Bandwidth</li>
                    <li><i class="fas fa-check"></i> 5 GB Storage</li>
                    <li><i class="fas fa-check"></i> Free SSL</li>
                    <li><i class="fas fa-check"></i> Support 24/7</li>
                </ul>
                <a href="https://t.me/Izalmodz" class="cta-button">Beli Sekarang</a>
            </div>
            
            <div class="product-card">
                <div class="product-icon">
                    <i class="fas fa-robot"></i>
                </div>
                <h3 class="product-title">Sewa Bot PushKontak</h3>
                <div class="product-price">Rp 25.000</div>
                <p class="product-description">Sewa bot untuk push kontak otomatis</p>
                <ul class="product-features">
                    <li><i class="fas fa-check"></i> Auto Push Kontak</li>
                    <li><i class="fas fa-check"></i> Support Massal</li>
                    <li><i class="fas fa-check"></i> Easy Configuration</li>
                    <li><i class="fas fa-check"></i> 24/7 Bot Active</li>
                </ul>
                <a href="https://t.me/Izalmodz" class="cta-button">Sewa Sekarang</a>
            </div>
            
            <div class="product-card">
                <div class="product-icon">
                    <i class="fas fa-user-graduate"></i>
                </div>
                <h3 class="product-title">Murid Unband 15K</h3>
                <div class="product-price">Rp 15.000</div>
                <p class="product-description">Khusus pelajar dengan unlimited bandwidth</p>
                <ul class="product-features">
                    <li><i class="fas fa-check"></i> Unlimited Bandwidth</li>
                    <li><i class="fas fa-check"></i> 3 GB Storage</li>
                    <li><i class="fas fa-check"></i> Free Domain</li>
                    <li><i class="fas fa-check"></i> Priority Support</li>
                </ul>
                <a href="https://t.me/Izalmodz" class="cta-button">Daftar Sekarang</a>
            </div>
            
            <div class="product-card">
                <div class="product-icon">
                    <i class="fas fa-code"></i>
                </div>
                <h3 class="product-title">SC PushKontak</h3>
                <div class="product-price">Rp 50.000</div>
                <p class="product-description">Source code aplikasi push kontak</p>
                <ul class="product-features">
                    <li><i class="fas fa-check"></i> Full Source Code</li>
                    <li><i class="fas fa-check"></i> Documentation</li>
                    <li><i class="fas fa-check"></i> Free Updates</li>
                    <li><i class="fas fa-check"></i> Support</li>
                </ul>
                <a href="https://t.me/Izalmodz" class="cta-button">Beli Sekarang</a>
            </div>
            
            <div class="product-card">
                <div class="product-icon">
                    <i class="fas fa-bug"></i>
                </div>
                <h3 class="product-title">SC Bug 15K</h3>
                <div class="product-price">Rp 15.000</div>
                <p class="product-description">Source code bug fixing untuk berbagai aplikasi</p>
                <ul class="product-features">
                    <li><i class="fas fa-check"></i> Bug Fix Solutions</li>
                    <li><i class="fas fa-check"></i> Step-by-Step Guide</li>
                    <li><i class="fas fa-check"></i> Compatible with多数Apps</li>
                    <li><i class="fas fa-check"></i> Lifetime Access</li>
                </ul>
                <a href="https://t.me/Izalmodz" class="cta-button">Beli Sekarang</a>
            </div>
            
            <div class="product-card">
                <div class="product-icon">
                    <i class="fas fa-columns"></i>
                </div>
                <h3 class="product-title">Panel 1-Unli 5K</h3>
                <div class="product-price">Rp 5.000</div>
                <p class="product-description">Panel hosting dengan unlimited resources</p>
                <ul class="product-features">
                    <li><i class="fas fa-check"></i> Unlimited Resources</li>
                    <li><i class="fas fa-check"></i> Easy Control Panel</li>
                    <li><i class="fas fa-check"></i> One-Click Install</li>
                    <li><i class="fas fa-check"></i> 99.9% Uptime</li>
                </ul>
                <a href="https://t.me/Izalmodz" class="cta-button">Beli Sekarang</a>
            </div>
        </div>
        
        <footer>
            <p>© 2023 Izalmodz Hosting Store. All rights reserved.</p>
            <p>Credits: @Izalmodz</p>
        </footer>
    </div>
    
    <div class="telegram-float">
        <a href="https://t.me/Izalmodz" class="telegram-button">
            <i class="fab fa-telegram"></i>
        </a>
    </div>
</body>
</html>