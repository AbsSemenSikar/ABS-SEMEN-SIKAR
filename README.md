# ABS-SEMEN-SIKAR
Animal Frozen Semen Agency 
<!DOCTYPE html>
<html lang="hi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ABS Semen Sikar | बोवाइन जेनेटिक्स में विश्व नेता - लंबी उम्र की गायें पालें</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@300;400;700&display=swap" rel="stylesheet">
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; }
        body { font-family: 'Roboto', sans-serif; line-height: 1.6; color: #333; }
        
        /* हेडर */
        header { background: #fff; box-shadow: 0 2px 5px rgba(0,0,0,0.1); position: fixed; width: 100%; top: 0; z-index: 1000; }
        nav { display: flex; justify-content: space-between; align-items: center; padding: 1rem 5%; max-width: 1200px; margin: 0 auto; }
        .logo { font-size: 1.5rem; font-weight: 700; color: #007bff; } /* नीला कलर ABS जैसा */
        .nav-links { display: flex; list-style: none; }
        .nav-links li { margin-left: 2rem; }
        .nav-links a { text-decoration: none; color: #333; font-weight: 400; transition: color 0.3s; }
        .nav-links a:hover { color: #007bff; }
        
        /* हिरो सेक्शन */
        .hero { background: url('https://via.placeholder.com/1920x600?text=ABS+Semen+Sikar+Hero+Image+(Cow+Farm)') no-repeat center/cover; height: 100vh; display: flex; align-items: center; justify-content: center; text-align: center; color: white; padding-top: 80px; }
        .hero-content h1 { font-size: 3.5rem; margin-bottom: 1rem; text-shadow: 2px 2px 4px rgba(0,0,0,0.5); }
        .hero-content p { font-size: 1.5rem; margin-bottom: 2rem; }
        .cta-btn { background: #007bff; color: white; padding: 1rem 2rem; border: none; border-radius: 5px; font-size: 1.2rem; cursor: pointer; transition: background 0.3s; }
        .cta-btn:hover { background: #0056b3; }
        
        /* अबाउट सेक्शन */
        .about { padding: 5rem 5%; max-width: 1200px; margin: 0 auto; text-align: center; background: #f8f9fa; }
        .about h2 { font-size: 2.5rem; margin-bottom: 1rem; color: #007bff; }
        .about p { font-size: 1.1rem; max-width: 800px; margin: 0 auto; }
        
        /* प्रोडक्ट्स सेक्शन */
        .products { padding: 5rem 5%; max-width: 1200px; margin: 0 auto; }
        .products h2 { font-size: 2.5rem; text-align: center; margin-bottom: 3rem; color: #007bff; }
        .product-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 2rem; }
        .product-card { background: white; padding: 2rem; border-radius: 10px; box-shadow: 0 5px 15px rgba(0,0,0,0.1); text-align: center; }
        .product-card img { width: 100%; height: 200px; object-fit: cover; border-radius: 10px; margin-bottom: 1rem; }
        .product-card h3 { font-size: 1.5rem; margin-bottom: 1rem; }
        .product-card p { margin-bottom: 1rem; }
        
        /* न्यूज़लेटर */
        .newsletter { background: #007bff; color: white; padding: 3rem 5%; text-align: center; }
        .newsletter h2 { font-size: 2rem; margin-bottom: 1rem; }
        .newsletter form { display: flex; justify-content: center; max-width: 500px; margin: 0 auto; }
        .newsletter input { padding: 0.8rem; flex: 1; border: none; border-radius: 5px 0 0 5px; }
        .newsletter button { padding: 0.8rem 2rem; background: #fff; color: #007bff; border: none; border-radius: 0 5px 5px 0; cursor: pointer; }
        
        /* फुटर */
        footer { background: #333; color: white; padding: 2rem 5%; text-align: center; }
        .footer-links { display: flex; justify-content: center; list-style: none; margin-bottom: 1rem; }
        .footer-links li { margin: 0 1rem; }
        .footer-links a { color: white; text-decoration: none; }
        
        /* रेस्पॉन्सिव */
        @media (max-width: 768px) {
            .nav-links { display: none; } /* मोबाइल पर हैमबर्गर ऐड कर सकते हो */
            .hero-content h1 { font-size: 2.5rem; }
            .product-grid { grid-template-columns: 1fr; }
        }
    </style>
</head>
<body>
    <!-- हेडर -->
    <header>
        <nav>
            <div class="logo">ABS Semen Sikar</div>
            <ul class="nav-links">
                <li><a href="#home">होम</a></li>
                <li><a href="#about">हमारे बारे में</a></li>
                <li><a href="#products">उत्पाद</a></li>
                <li><a href="#sexcel">सेक्सेल</a></li>
                <li><a href="#contact">संपर्क</a></li>
            </ul>
        </nav>
    </header>

    <!-- हिरो -->
    <section id="home" class="hero">
        <div class="hero-content">
            <h1>बोवाइन जेनेटिक्स में विश्व नेता</h1>
            <p>लंबी उम्र की गायें पालें - ABS Semen Sikar के साथ उच्च गुणवत्ता वाले सेमेन और जेनेटिक्स</p>
            <button class="cta-btn" onclick="document.getElementById('products').scrollIntoView();">उत्पाद देखें</button>
        </div>
    </section>

    <!-- अबाउट -->
    <section id="about" class="about">
        <h2>हमारे बारे में</h2>
        <p>ABS Semen Sikar, Genus ABS Global का हिस्सा, भारत का अग्रणी बोवाइन जेनेटिक्स प्रदाता है। हम साहिवाल, गिर, रेड सिंधी, HF और जर्सी क्रॉसब्रीड्स के एलीट सिरों से सेमेन उत्पादित करते हैं। सीकर में स्थित हमारी सुविधा उच्च गुणवत्ता वाले कन्वेंशनल और सेक्स्ड सेमेन प्रदान करती है। हमारी जेनेटिक्स दूध उत्पादन बढ़ाती हैं और आपके हर्ड को मजबूत बनाती हैं।</p>
    </section>

    <!-- प्रोडक्ट्स -->
    <section id="products" class="products">
        <h2>हमारे उत्पाद</h2>
        <div class="product-grid">
            <div class="product-card">
                <img src="https://via.placeholder.com/300x200?text=Sexcel+Semen" alt="सेक्सेल सेमेन">
                <h3>सेक्सेल™ सेमेन</h3>
                <p>उच्च प्रजनन क्षमता वाला सेक्स्ड सेमेन। 90% सटीकता से मादा बछड़ों के लिए। आपके हर्ड में अधिक मूल्यवान मादा गर्भावस्थाएं।</p>
                <button class="cta-btn" style="width:100%; margin-top:1rem;">और जानें</button>
            </div>
            <div class="product-card">
                <img src="https://via.placeholder.com/300x200?text=Conventional+Semen" alt="कन्वेंशनल सेमेन">
                <h3>कन्वेंशनल सेमेन</h3>
                <p>एलीट सिरों से उच्च गुणवत्ता वाला सेमेन। दूध उत्पादन और स्वास्थ्य में सुधार। साहिवाल, गिर आदि नस्लों के लिए।</p>
                <button class="cta-btn" style="width:100%; margin-top:1rem;">और जानें</button>
            </div>
            <div class="product-card">
                <img src="https://via.placeholder.com/300x200?text=Genomic+Bulls" alt="जीनोमिक बुल्स">
                <h3>जीनोमिक मूल्यांकित बुल्स</h3>
                <p>उन्नत तकनीक से चुने गए बुल्स। तेजी से जेनेटिक प्रगति और लाभदायक प्रजनन।</p>
                <button class="cta-btn" style="width:100%; margin-top:1rem;">और जानें</button>
            </div>
        </div>
    </section>

    <!-- न्यूज़लेटर -->
    <section class="newsletter">
        <h2>न्यूज़लेटर के लिए साइन अप करें</h2>
        <p>नई जेनेटिक्स और ऑफर्स की अपडेट पाएं।</p>
        <form onsubmit="alert('धन्यवाद! आप साइन अप हो गए।'); return false;">
            <input type="email" placeholder="आपका ईमेल" required>
            <button type="submit">साइन अप</button>
        </form>
    </section>

    <!-- फुटर -->
    <footer id="contact">
        <ul class="footer-links">
            <li><a href="#about">हमारे बारे में</a></li>
            <li><a href="#products">उत्पाद</a></li>
            <li><a href="#">गोपनीयता नीति</a></li>
            <li><a href="#">शर्तें</a></li>
        </ul>
        <p>&copy; 2025 ABS Semen Sikar. सभी अधिकार सुरक्षित। सीकर, राजस्थान। संपर्क: info@abssemensikar.com | +91-XXXX-XXXXXX</p>
    </footer>

    <script>
        // स्मूथ स्क्रॉल
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                document.querySelector(this.getAttribute('href')).scrollIntoView({ behavior: 'smooth' });
            });
        });
    </script>
</body>
</html>
