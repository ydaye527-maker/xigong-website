[网站.html](https://github.com/user-attachments/files/28951162/default.html)
# xigong-website
 KT board and PVC board factory website
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=yes">
    <title>Xigong | KT Board, PVC Board & Advertising Materials Manufacturer</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: 'Segoe UI', Roboto, 'Helvetica Neue', sans-serif;
            background: #fff;
            color: #1e2a3a;
            line-height: 1.5;
        }
        .container {
            max-width: 1280px;
            margin: 0 auto;
            padding: 0 24px;
        }
        header {
            background: #0f2b3d;
            color: white;
            padding: 16px 0;
            position: sticky;
            top: 0;
            z-index: 100;
        }
        .header-flex {
            display: flex;
            justify-content: space-between;
            align-items: center;
            flex-wrap: wrap;
            gap: 16px;
        }
        .logo h1 {
            font-size: 1.6rem;
            letter-spacing: -0.5px;
        }
        .logo p {
            font-size: 0.8rem;
            opacity: 0.8;
        }
        .nav a {
            color: white;
            text-decoration: none;
            margin-left: 24px;
            font-weight: 500;
            transition: 0.2s;
        }
        .nav a:hover {
            color: #ffb347;
        }
        .btn-wa {
            background: #25D366;
            padding: 8px 16px;
            border-radius: 40px;
            display: inline-flex;
            align-items: center;
            gap: 8px;
        }
        .btn-wa:hover {
            background: #128C7E;
            color: white;
        }
        .hero {
            background: linear-gradient(135deg, #eef2f5 0%, #ffffff 100%);
            padding: 60px 0;
        }
        .hero-grid {
            display: flex;
            align-items: center;
            gap: 40px;
            flex-wrap: wrap;
        }
        .hero-text {
            flex: 1;
        }
        .hero-text h2 {
            font-size: 2.8rem;
            margin-bottom: 20px;
            color: #0f2b3d;
        }
        .hero-text p {
            font-size: 1.2rem;
            margin-bottom: 30px;
            color: #2c3e50;
        }
        .hero-image {
            flex: 1;
            background: #e9eef3;
            border-radius: 20px;
            padding: 20px;
            text-align: center;
            min-height: 260px;
            display: flex;
            align-items: center;
            justify-content: center;
        }
        .hero-image img {
            max-width: 100%;
            border-radius: 16px;
            box-shadow: 0 8px 20px rgba(0,0,0,0.1);
        }
        .btn {
            display: inline-block;
            background: #ff8c00;
            color: white;
            padding: 12px 28px;
            border-radius: 40px;
            text-decoration: none;
            font-weight: bold;
            margin-right: 15px;
            transition: 0.2s;
        }
        .btn-outline {
            background: transparent;
            border: 2px solid #ff8c00;
            color: #ff8c00;
        }
        section {
            padding: 60px 0;
        }
        .section-title {
            text-align: center;
            font-size: 2rem;
            margin-bottom: 48px;
            color: #0f2b3d;
        }
        .cards {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
            gap: 30px;
        }
        .card {
            background: #f9fafb;
            border-radius: 24px;
            padding: 28px;
            box-shadow: 0 4px 12px rgba(0,0,0,0.05);
            transition: 0.2s;
            display: flex;
            flex-direction: column;
        }
        .card-img {
            width: 100%;
            height: 200px;
            object-fit: cover;
            border-radius: 16px;
            margin-bottom: 20px;
            background: #e2e8f0;
        }
        .card h3 {
            font-size: 1.5rem;
            margin-bottom: 12px;
        }
        .spec-list {
            list-style: none;
            margin: 20px 0;
            flex-grow: 1;
        }
        .spec-list li {
            padding: 6px 0;
            border-bottom: 1px solid #e2e8f0;
        }
        .badge {
            background: #ff8c00;
            color: white;
            padding: 4px 12px;
            border-radius: 30px;
            font-size: 0.8rem;
            display: inline-block;
            margin-bottom: 12px;
        }
        .contact-form {
            background: #f0f4f8;
            border-radius: 32px;
            padding: 40px;
            max-width: 700px;
            margin: 0 auto;
        }
        input, textarea {
            width: 100%;
            padding: 14px;
            margin-bottom: 20px;
            border: 1px solid #cbd5e1;
            border-radius: 12px;
            font-family: inherit;
        }
        button {
            background: #ff8c00;
            color: white;
            border: none;
            padding: 14px 28px;
            border-radius: 40px;
            font-weight: bold;
            cursor: pointer;
        }
        footer {
            background: #0f2b3d;
            color: white;
            text-align: center;
            padding: 32px 0;
            margin-top: 20px;
        }
        @media (max-width: 768px) {
            .hero-text h2 { font-size: 2rem; }
            .nav a { margin-left: 12px; }
            .header-flex { flex-direction: column; }
        }
    </style>
</head>
<body>
<header>
    <div class="container header-flex">
        <div class="logo">
            <h1>XIGONG</h1>
            <p>KT Board · PVC Board · Advertising Materials</p >
        </div>
        <div class="nav">
            <a href=" ">Home</a >
            <a href="#products">Products</a >
            <a href="#about">About</a >
            <a href="#contact">Contact</a >
            <a href="#" class="btn-wa" target="_blank">WhatsApp</a >
        </div>
    </div>
</header>

<section id="home" class="hero">
    <div class="container hero-grid">
        <div class="hero-text">
            <h2>Professional Advertising Materials<br>Made in Jiangsu, China</h2>
            <p>Factory direct: KT board, PVC foam board, and other sign & display materials. Standard 4'×8' sheets, 3mm–20mm thickness. Save 30–50% on material cost compared to US/EU suppliers. Free samples available.</p >
            <a href="#contact" class="btn">Request Free Sample</a >
            <a href="#products" class="btn btn-outline">View Products</a >
        </div>
        <div class="hero-image">
            <!-- 新：工厂板材堆放或生产线场景 -->
            < img src="https://images.pexels.com/photos/380768/pexels-photo-380768.jpeg?auto=compress&cs=tinysrgb&w=800" alt="Material Stack">
        </div>
    </div>
</section>

<section id="products">
    <div class="container">
        <h2 class="section-title">Our Main Product Lines</h2>
        <div class="cards">
            <div class="card">
                <!-- PVC板 相关：白色光滑板材特写 -->
                < img class="card-img" src="https://images.pexels.com/photos/2121121/pexels-photo-2121121.jpeg?auto=compress&cs=tinysrgb&w=400" alt="PVC Foam Board">
                <div class="badge">High density | durable</div>
                <h3>PVC Foam Board</h3>
                <ul class="spec-list">
                    <li>Thickness: 3mm – 20mm</li>
                    <li>Size: 4'×8' (1220×2440mm)</li>
                    <li>White, black, custom colors</li>
                    <li>Warp‑resistant, smooth surface, excellent for UV printing</li>
                </ul>
                <p><strong>30‑50% less</strong> than local distributors</p >
            </div>
            <div class="card">
                <!-- KT板 轻质板材展示 -->
                < img class="card-img" src="https://images.pexels.com/photos/209230/pexels-photo-209230.jpeg?auto=compress&cs=tinysrgb&w=400" alt="KT Board">
                <div class="badge">Lightweight & economical</div>
                <h3>KT Board (Foam Core)</h3>
                <ul class="spec-list">
                    <li>Thickness: 5mm – 10mm</li>
                    <li>Size: 4'×8' (1220×2440mm)</li>
                    <li>Paper or PVC laminated surface</li>
                    <li>Perfect for POP displays, exhibitions, indoor signage</li>
                </ul>
                <p>💡 Low MOQ, mixed pallet welcome</p >
            </div>
            <div class="card">
                <!-- 其他广告材料 综合展示 -->
                < img class="card-img" src="https://images.pexels.com/photos/386009/pexels-photo-386009.jpeg?auto=compress&cs=tinysrgb&w=400" alt="Other Advertising Materials">
                <div class="badge">More for sign shops</div>
                <h3>Other Advertising Materials</h3>
                <ul class="spec-list">
                    <li>Aluminum Composite Panel (ACP)</li>
                    <li>Acrylic sheet / Plexiglass</li>
                    <li>Coroplast (fluted polypropylene)</li>
                    <li>Self‑adhesive vinyl / car wrap film</li>
                </ul>
                <p>Complete your bill of materials with one factory.</p >
            </div>
        </div>
    </div>
</section>

<section id="about" style="background: #f9fafb;">
    <div class="container">
        <h2 class="section-title">About Xigong – Chinese Factory Since 2010</h2>
        <div class="cards">
            <div class="card">
                <h3>📍 Located in Jiangsu, China</h3>
                <p>Jiangsu Xigong New Material Technology Co., Ltd. is a professional manufacturer of KT board, PVC foam board, and a wide range of advertising & signage materials. We supply to wholesalers, sign shops, print houses, and exhibition companies worldwide.</p >
            </div>
            <div class="card">
                <h3>⚙️ 15+ years of experience</h3>
                <p>Our production lines are certified with ISO 9001. We control every step – from raw material to finished sheet – ensuring stable quality, on‑time delivery, and competitive pricing.</p >
            </div>
            <div class="card">
                <h3>🌎 Trusted by global buyers</h3>
                <p>We export to USA, Canada, Europe, Russia, Middle East, and Southeast Asia. Many customers switched to us and saved 30–50% on material costs. Free samples always ready.</p >
            </div>
        </div>
    </div>
</section>

<section id="contact">
    <div class="container">
        <h2 class="section-title">Send Inquiry | Get Free Sample</h2>
        <div class="contact-form">
            <form action="https://formsubmit.co/ydaye527@gmail.com" method="POST">
                <input type="text" name="name" placeholder="Your Name / Company" required>
                <input type="email" name="email" placeholder="Email address" required>
                <input type="tel" name="phone" placeholder="WhatsApp / Phone">
                <textarea rows="4" name="message" placeholder="Tell us which product & thickness you need... e.g. 9mm KT board, 4x8 ft, white"></textarea>
                <button type="submit">Send Inquiry →</button>
                <p style="font-size:0.8rem; margin-top:12px;">We reply within 24h. Free sample sent for serious inquiries.</p >
            </form>
        </div>
        <div style="text-align: center; margin-top: 40px;">
            <p>📧 ydaye527@gmail.com | 📞 WhatsApp: +86 17621656659</p >
        </div>
    </div>
</section>

<footer>
    <div class="container">
        <p>&copy; 2026 Jiangsu Xigong New Material Technology Co., Ltd. – Professional KT Board & PVC Board Manufacturer in China.</p >
        <p style="margin-top: 8px;">High density PVC board, KT board, aluminum composite panel, acrylic sheet – factory direct for global sign supply.</p >
    </div>
</footer>
</body>
</html>
