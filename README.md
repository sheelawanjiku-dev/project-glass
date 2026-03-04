<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Project Glass & Aluminium | Mariakani</title>
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@300;600&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <style>
        :root { --black: #000000; --white: #ffffff; --grey: #f4f4f4; }
        * { margin: 0; padding: 0; box-sizing: border-box; }
        body { font-family: 'Montserrat', sans-serif; background: var(--white); color: var(--black); }
        
        nav { padding: 2rem; text-align: center; border-bottom: 1px solid #eee; }
        .logo-img { width: 150px; border-radius: 50%; }
        .brand-title { text-transform: uppercase; letter-spacing: 12px; font-weight: 600; font-size: 1.4rem; margin-top: 10px; }

        section { padding: 4rem 5%; }
        .section-title { text-align: center; text-transform: uppercase; letter-spacing: 6px; margin-bottom: 3rem; font-weight: 600; }
        
        /* Gallery */
        .gallery-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 20px; }
        .gallery-item { position: relative; overflow: hidden; height: 350px; border: 1px solid #eee; }
        .gallery-item img { width: 100%; height: 100%; object-fit: cover; transition: 0.5s; }
        .gallery-item:hover img { transform: scale(1.1); }
        .caption { position: absolute; bottom: 0; left: 0; right: 0; background: rgba(0,0,0,0.7); color: white; padding: 15px; font-size: 0.8rem; text-transform: uppercase; letter-spacing: 2px; }

        /* Testimonials */
        .reviews { background: var(--grey); }
        .review-card { background: white; padding: 2rem; margin-bottom: 20px; border-left: 5px solid var(--black); }
        .review-text { font-style: italic; margin-bottom: 10px; }
        .reviewer { font-weight: 600; font-size: 0.8rem; text-transform: uppercase; letter-spacing: 1px; }

        /* Location Section */
        .location-box { text-align: center; border: 1px solid #eee; padding: 3rem; }
        .map-btn { 
            display: inline-block; margin-top: 20px; padding: 12px 25px; 
            background: var(--black); color: white; text-decoration: none; 
            text-transform: uppercase; letter-spacing: 2px; font-size: 0.8rem; transition: 0.3s;
        }
        .map-btn:hover { opacity: 0.8; }

        .contact-buttons { position: fixed; bottom: 30px; right: 20px; display: flex; flex-direction: column; gap: 15px; z-index: 1000; }
        .btn-float { width: 60px; height: 60px; border-radius: 50%; display: flex; align-items: center; justify-content: center; font-size: 28px; color: white; text-decoration: none; box-shadow: 0 4px 12px rgba(0,0,0,0.3); }
        .whatsapp { background: #25d366; }
        .phone { background: var(--black); }

        footer { padding: 3rem; text-align: center; background: var(--black); color: white; font-size: 0.7rem; letter-spacing: 3px; }
    </style>
</head>
<body>

    <nav>
        <img src="logo.jpg" alt="Logo" class="logo-img">
        <div class="brand-title">Project</div>
    </nav>

    <section class="portfolio">
        <h2 class="section-title">Recent Work</h2>
        <div class="gallery-grid">
            <div class="gallery-item"><img src="work1.jpg" alt="Folding Doors"><div class="caption">Aluminium Folding Doors</div></div>
            <div class="gallery-item"><img src="work2.jpg" alt="Shower"><div class="caption">Frameless Shower Cubicle</div></div>
            <div class="gallery-item"><img src="work3.jpg" alt="Windows"><div class="caption">Sliding Windows</div></div>
            <div class="gallery-item"><img src="work4.jpg" alt="Outdoor Door"><div class="caption">Premium Sliding Doors</div></div>
        </div>
    </section>

    <section class="reviews">
        <h2 class="section-title">Client Feedback</h2>
        <div class="review-card">
            <p class="review-text">"High quality aluminium work! My sliding windows look amazing and were installed perfectly."</p>
            <p class="reviewer">- Happy Client, Mariakani</p>
        </div>
        <div class="review-card">
            <p class="review-text">"Very professional service. The frameless shower cubicle changed my whole bathroom vibe."</p>
            <p class="reviewer">- Local Business Owner</p>
        </div>
    </section>

    <section class="location">
        <h2 class="section-title">Find Us</h2>
        <div class="location-box">
            <i class="fas fa-map-marker-alt" style="font-size: 2rem; margin-bottom: 1rem;"></i>
            <h3>Mariakani Shop</h3>
            <p>Kaloleni Highway, Near Timbers Hardware</p>
            <a href="https://www.google.com/maps/search/?api=1&query=Timbers+Hardware+Mariakani+Kaloleni+Highway" target="_blank" class="map-btn">
                <i class="fas fa-directions"></i> Get Directions
            </a>
        </div>
    </section>

    <div class="contact-buttons">
        <a href="tel:0719488872" class="btn-float phone"><i class="fas fa-phone"></i></a>
        <a href="https://api.whatsapp.com/send?phone=254719488872" class="btn-float whatsapp"><i class="fab fa-whatsapp"></i></a>
    </div>

    <footer>&copy; 2026 Project Glass & Aluminium</footer>

</body>
</html>
