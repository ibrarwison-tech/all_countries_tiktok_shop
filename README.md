<!DOCTYPE html>
<html lang="ur">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>VIP Global TikTok Studio</title>
    <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@400;700&family=Noto+Nastaliq+Urdu&display=swap" rel="stylesheet">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            background-color: #000000;
            color: #ffffff;
            font-family: 'Orbitron', 'Noto Nastaliq Urdu', sans-serif;
            overflow-x: hidden;
        }
        /* Nothing Neon Light Effect */
        .glow-bg {
            position: absolute;
            top: -10%;
            left: 50%;
            transform: translateX(-50%);
            width: 300px;
            height: 300px;
            background: radial-gradient(circle, rgba(255, 0, 0, 0.2) 0%, rgba(0,0,0,0) 70%);
            z-index: -1;
        }
        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 40px 20px;
            text-align: center;
        }
        /* Dot Matrix Header Look */
        h1 {
            font-size: 2.5rem;
            letter-spacing: 2px;
            text-transform: uppercase;
            margin-bottom: 10px;
            text-shadow: 0 0 10px rgba(255, 255, 255, 0.5);
        }
        .tagline {
            color: #ff4444;
            font-size: 1.2rem;
            margin-bottom: 40px;
            letter-spacing: 1px;
        }
        /* VIP Services Grid */
        .services-grid {
            display: grid;
            grid-template-columns: 1fr;
            gap: 20px;
            margin-bottom: 40px;
        }
        @media(min-width: 600px) {
            .services-grid { grid-template-columns: 1fr 1fr; }
        }
        /* Nothing Widget Style Cards */
        .card {
            background: #111111;
            border: 1px solid #222222;
            border-radius: 24px;
            padding: 25px;
            transition: all 0.3s ease;
            text-align: right;
            direction: rtl;
        }
        .card:hover {
            border-color: #ff4444;
            box-shadow: 0 0 15px rgba(255, 68, 68, 0.2);
        }
        .card h3 {
            color: #ffffff;
            font-size: 1.4rem;
            margin-bottom: 10px;
            border-bottom: 1px dotted #333333;
            padding-bottom: 5px;
        }
        .card p {
            color: #aaaaaa;
            font-size: 0.95rem;
            line-height: 1.6;
        }
        /* Flag Badge Style */
        .countries {
            margin-top: 15px;
            font-size: 0.85rem;
            color: #ff4444;
            letter-spacing: 1px;
        }
        /* Premium Action Button */
        .btn-whatsapp {
            display: inline-block;
            background-color: #ffffff;
            color: #000000;
            padding: 15px 40px;
            font-weight: bold;
            font-size: 1.1rem;
            border-radius: 50px;
            text-decoration: none;
            text-transform: uppercase;
            letter-spacing: 1px;
            transition: all 0.3s ease;
            box-shadow: 0 4px 15px rgba(255, 255, 255, 0.2);
        }
        .btn-whatsapp:hover {
            background-color: #ff4444;
            color: #ffffff;
            box-shadow: 0 4px 20px rgba(255, 68, 68, 0.4);
        }
        footer {
            margin-top: 60px;
            font-size: 0.8rem;
            color: #444444;
            letter-spacing: 1px;
        }
    </style>
</head>
<body>

    <div class="glow-bg"></div>

    <div class="container">
        <h1>Tiktok Global Studio</h1>
        <p class="tagline">VIP Accounts & Premium Device Setup</p>

        <div class="services-grid">
            
            <div class="card">
                <h3>انٹرنیشنل مونیٹائزڈ اکاؤنٹس 🌍</h3>
                <p>پاکستان، انڈیا، بنگلہ دیش، یوکے، یو ایس اے، یورپ، کینیڈا اور آسٹریلیا سمیت دنیا کے کسی بھی ملک کا آفیشل ٹک ٹاک اکاؤنٹ گھر بیٹھے حاصل کریں۔</p>
                <div class="countries">PK • IN • BD • UK • USA • CA • AU</div>
            </div>

            <div class="card">
                <h3>VIP ہوم اسکرین سیٹنگز 📱</h3>
                <p>اپنے موبائل کو عام لک سے نکال کر پریمیم انٹرنیشنل لک دیں۔ نتھنگ (Nothing) برانڈ کے آفیشل تھیمز، مونوکروم آئیکونز اور ڈاٹ میٹرکس ویجٹس کی کسٹم سیٹنگ۔</p>
                <div class="countries">ELITE BUSINESS DESIGN</div>
            </div>

            <div class="card">
                <h3>ٹارگٹڈ کنٹری مونیٹائزیشن 🚀</h3>
                <p>اگر آپ پاکستان یا انڈیا میں بیٹھ کر یوکے یا یو ایس اے کی آڈینس کو ٹارگٹ کرنا چاہتے ہیں، تو ہم آپ کو مکمل آرگینک اور سیف سیٹ اپ بنا کر دیں گے۔</p>
                <div class="countries">100% ELIGIBLE SERVICES</div>
            </div>

            <div class="card">
                <h3>پروفیشنل برانڈ گروتھ 📈</h3>
                <p>اکاؤنٹ بنانے سے لے کر اس کی بائیو، ہائی ریزولوشن لوگو ڈیزائننگ، وائرل ہیش ٹیگز اور مونیٹائزیشن اپروول تک مکمل ایگزیکٹو سپورٹ۔</p>
                <div class="countries">EXECUTIVE AGENCY CARE</div>
            </div>

        </div>

        <p style="margin-bottom: 20px; color: #888888;">اپنا VIP اکاؤنٹ اور سیٹنگز ابھی بک کرنے کے لیے رابطہ کریں</p>
        <a href="https://wa.me/+966561487768" class="btn-whatsapp" target="_blank">Contact VIP Order</a>

        <footer>
            &copy; 2026 TikTok Global Studio. All Rights Reserved. Designed for Elite Creators.
        </footer>
    </div>

</body>
</html>
