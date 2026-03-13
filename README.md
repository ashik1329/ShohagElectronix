<!DOCTYPE html>
<html lang="bn">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>সোহাগ ইলেকট্রনিক্স অ্যান্ড হার্ডওয়্যার | Adventure in Tech</title>
    
    <link href="https://fonts.googleapis.com/css2?family=Hind+Siliguri:wght@300;500;700&display=swap" rel="stylesheet">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    
    <style>
        :root {
            --primary-black: #1a1a1a;
            --pure-white: #ffffff;
            --accent-gray: #f4f4f4;
        }

        body { 
            font-family: 'Hind Siliguri', sans-serif; 
            background-color: var(--pure-white);
            color: var(--primary-black);
            overflow-x: hidden;
        }

        /* Adventure Style Hero */
        .hero-section { 
            background: var(--primary-black);
            color: var(--pure-white); 
            padding: 120px 0;
            position: relative;
            border-bottom: 10px solid var(--primary-black);
        }

        .hero-section::after {
            content: "";
            position: absolute;
            bottom: 0;
            left: 0;
            width: 100%;
            height: 50px;
            background: var(--pure-white);
            clip-path: polygon(0 100%, 100% 100%, 100% 0);
        }

        .btn-adventure {
            background: var(--pure-white);
            color: var(--primary-black);
            font-weight: 700;
            text-transform: uppercase;
            letter-spacing: 1px;
            padding: 12px 30px;
            border: 2px solid var(--pure-white);
            transition: 0.3s;
            text-decoration: none;
            display: inline-block;
        }

        .btn-adventure:hover {
            background: transparent;
            color: var(--pure-white);
        }

        /* Monochrome Service Cards */
        .service-card { 
            border: 2px solid var(--primary-black);
            border-radius: 0;
            transition: 0.4s;
            background: var(--pure-white);
        }

        .service-card:hover { 
            background: var(--primary-black);
            color: var(--pure-white);
            transform: scale(1.02);
        }

        .service-card i { font-size: 3rem; margin-bottom: 15px; }

        /* Helpful Feature: Quick Help Bar */
        .help-bar {
            background: var(--accent-gray);
            padding: 20px 0;
            border-top: 1px solid #ddd;
            border-bottom: 1px solid #ddd;
        }

        /* Adventure Map Style */
        .map-wrapper {
            border: 5px solid var(--primary-black);
            filter: grayscale(100%);
            transition: 0.5s;
        }

        .map-wrapper:hover {
            filter: grayscale(0%);
        }

        /* Floating Adventure Menu */
        .sticky-contact {
            position: fixed;
            bottom: 30px;
            right: 30px;
            z-index: 1000;
        }

        .floating-btn {
            width: 55px;
            height: 55px;
            background: var(--primary-black);
            color: var(--pure-white);
            display: flex;
            align-items: center;
            justify-content: center;
            margin-bottom: 10px;
            text-decoration: none;
            font-size: 20px;
            box-shadow: 5px 5px 0px #ccc;
        }

        footer {
            background: var(--primary-black);
            color: var(--pure-white);
            padding: 50px 0;
        }
    </style>
</head>
<body>

    <nav class="navbar navbar-expand-lg navbar-light bg-white border-bottom py-3">
        <div class="container">
            <a class="navbar-brand fw-bold fs-3" href="#">SOHAG ELECTRONICS & HARDWARE</a>
            <div class="ms-auto">
                <a href="tel:01798639323" class="fw-bold text-dark text-decoration-none"><i class="fas fa-bolt"></i> ০১৭৯৮৬৩৯৩২৩</a>
            </div>
        </div>
    </nav>

    <header class="hero-section">
        <div class="container">
            <div class="row align-items-center">
                <div class="col-lg-7">
                    <h1 class="display-3 fw-bold mb-3">আমরা ঠিক করি, <br>আপনি সামনে এগিয়ে যান।</h1>
                    <p class="fs-5 mb-5 opacity-75">ইলেকট্রনিক্স এবং হার্ডওয়্যারের দুনিয়ায় নির্ভুল সমাধানের এক নতুন অভিযান। গাইবান্ধা নিউ মার্কেটে আমরাই আপনার বিশ্বস্ত সঙ্গী।</p>
                    <div class="d-flex gap-3">
                        <a href="#booking" class="btn-adventure">সার্ভিস বুক করুন</a>
                        <a href="#location" class="btn btn-outline-light rounded-0 px-4">আমাদের খুঁজুন</a>
                    </div>
                </div>
            </div>
        </div>
    </header>

    <div class="help-bar">
        <div class="container d-flex justify-content-around text-center flex-wrap">
            <div class="p-2"><i class="fas fa-check-circle"></i> দ্রুত ডেলিভারি</div>
            <div class="p-2"><i class="fas fa-shield-alt"></i> অরিজিনাল পার্টস</div>
            <div class="p-2"><i class="fas fa-tools"></i> দক্ষ টেকনিশিয়ান</div>
        </div>
    </div>

    <section class="container my-5 py-5">
        <div class="mb-5">
            <h2 class="fw-bold text-uppercase">আমাদের এক্সপার্ট এরিয়া</h2>
            <div style="width: 100px; height: 8px; background: #000;"></div>
        </div>
        <div class="row g-4">
            <div class="col-md-4">
                <div class="card service-card p-5 h-100">
                    <i class="fas fa-tv"></i>
                    <h3 class="fw-bold">টিভি রিপেয়ার</h3>
                    <p>স্মার্ট এবং এলইডি টিভির মাদারবোর্ড থেকে ডিসপ্লে—সব সমস্যার সমাধান।</p>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card service-card p-5 h-100">
                    <i class="fas fa-microchip"></i>
                    <h3 class="fw-bold">হার্ডওয়্যার</h3>
                    <p>উন্নত মানের পার্টস এবং জটিল হার্ডওয়্যার সলিউশন।</p>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card service-card p-5 h-100">
                    <i class="fas fa-bolt"></i>
                    <h3 class="fw-bold">ইলেকট্রিক</h3>
                    <p>আপনার বাসা বা অফিসের নিরাপদ ওয়্যারিং এবং ইলেকট্রিক সলিউশন।</p>
                </div>
            </div>
        </div>
    </section>

    <section class="container my-5" id="location">
        <div class="row g-0 align-items-center bg-light border shadow-sm">
            <div class="col-lg-6 p-5">
                <h2 class="fw-bold mb-4">আমাদের অবস্থান</h2>
                <p class="fs-5"><i class="fas fa-map-marker-alt"></i> ১৭ নং দোকান, নিউ মার্কেট, গাইবান্ধা।</p>
                <p><i class="fas fa-clock"></i> সকাল ৯টা থেকে রাত ১০টা পর্যন্ত খোলা।</p>
                <hr>
                <div id="booking">
                    <h4 class="mb-3">অভিযান শুরু হোক (বুকিং)</h4>
                    <form id="whatsappForm">
                        <input type="text" id="custName" class="form-control mb-2 rounded-0 border-dark" placeholder="আপনার নাম" required>
                        <input type="tel" id="custPhone" class="form-control mb-3 rounded-0 border-dark" placeholder="আপনার ফোন নম্বর" required>
                        <button type="button" onclick="sendToWhatsApp()" class="btn btn-dark w-100 rounded-0 py-3">হোয়াটসঅ্যাপে মেসেজ পাঠান</button>
                    </form>
                </div>
            </div>
            <div class="col-lg-6">
                <div class="map-wrapper">
                    <iframe 
                        src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3593.5471469399475!2d89.5413156!3d25.7524274!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x39f0cd3830ca068f%3A0x63345862d2d9f3f!2sGaibandha%20New%20Market!5e0!3m2!1sen!2sbd!4v1700000000000" 
                        width="100%" height="500" style="border:0;" allowfullscreen="" loading="lazy">
                    </iframe>
                </div>
            </div>
        </div>
    </section>

    <footer>
        <div class="container text-center">
            <h2 class="fw-bold mb-4">SOHAG ELECTRONICS</h2>
            <p class="opacity-50">গাইবান্ধার প্রযুক্তিগত উৎকর্ষের একমাত্র ঠিকানা।</p>
            <div class="mt-4">
                <p>© ২০২৬ | সর্বস্বত্ব সংরক্ষিত</p>
            </div>
        </div>
    </footer>

    <div class="sticky-contact">
        <a href="https://wa.me/8801798639323" target="_blank" class="floating-btn"><i class="fab fa-whatsapp"></i></a>
        <a href="tel:01798639323" class="floating-btn"><i class="fas fa-phone-alt"></i></a>
        <a href="#location" class="floating-btn"><i class="fas fa-location-arrow"></i></a>
    </div>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>

    <script>
        function sendToWhatsApp() {
            const name = document.getElementById('custName').value;
            const phone = document.getElementById('custPhone').value;
            
            if(name === "" || phone === "") {
                alert("অনুগ্রহ করে নাম এবং ফোন নম্বর দিন।");
                return;
            }

            const whatsappNumber = "8801798639323";
            const message = "নতুন বুকিং অনুরোধ:%0A" + 
                            "নাম: " + name + "%0A" + 
                            "ফোন: " + phone + "%0A" + 
                            "আমি একটি সার্ভিসের জন্য আলোচনা করতে চাই।";

            const url = "https://wa.me/" + whatsappNumber + "?text=" + message;
            window.open(url, '_blank');
        }
    </script>
</body>
</html>
