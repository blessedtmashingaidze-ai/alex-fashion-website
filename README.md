<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <title>Alex Fashion Designer | Crystal Park</title>

  <meta name="description" content="Alex Fashion Designer offers wedding dresses, traditional outfits, men's suits, custom designs and clothing alterations in Crystal Park.">

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      scroll-behavior: smooth;
    }

    body {
      font-family: Arial, sans-serif;
      background: #fffaf7;
      color: #292323;
      line-height: 1.6;
    }

    header {
      background: #211a1d;
      color: white;
      text-align: center;
      padding: 28px 15px;
    }

    header h1 {
      font-family: Georgia, serif;
      font-size: clamp(28px, 5vw, 43px);
      letter-spacing: 2px;
    }

    header p {
      color: #f0c9d8;
      margin-top: 5px;
    }

    nav {
      background: #d7a1b5;
      padding: 13px;
      text-align: center;
    }

    nav a {
      color: #211a1d;
      text-decoration: none;
      font-weight: bold;
      margin: 0 12px;
      display: inline-block;
    }

    .hero {
      min-height: 420px;
      background:
        linear-gradient(#0005, #0007),
        url("https://images.unsplash.com/photo-1539109136881-3be0616acf4b?auto=format&fit=crop&w=1800&q=85")
        center 35% / cover;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
      color: white;
      padding: 45px 20px;
    }

    .hero h2 {
      font-family: Georgia, serif;
      font-size: clamp(32px, 6vw, 54px);
      margin-bottom: 12px;
    }

    .hero p {
      font-size: 18px;
      margin-bottom: 25px;
    }

    .button {
      display: inline-block;
      background: #d7a1b5;
      color: #211a1d;
      padding: 12px 23px;
      border-radius: 5px;
      text-decoration: none;
      font-weight: bold;
      margin: 5px;
    }

    section {
      padding: 55px 7%;
      text-align: center;
    }

    section h2 {
      font-family: Georgia, serif;
      font-size: 32px;
      margin-bottom: 12px;
    }

    .intro {
      max-width: 750px;
      margin: 0 auto;
    }

    .services {
      background: #f6e8ed;
    }

    .service-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(210px, 1fr));
      gap: 20px;
      max-width: 1100px;
      margin: 30px auto 0;
    }

    .service-card {
      background: white;
      padding: 25px 18px;
      border-radius: 10px;
      box-shadow: 0 3px 12px #00000010;
    }

    .service-card h3 {
      margin-bottom: 8px;
      color: #8a4965;
    }

    .gallery-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 18px;
      max-width: 1100px;
      margin: 28px auto 0;
    }

    .gallery-grid figure {
      overflow: hidden;
      background: white;
      border-radius: 9px;
      box-shadow: 0 3px 12px #00000015;
    }

    .gallery-grid img {
      width: 100%;
      height: 300px;
      object-fit: cover;
      display: block;
    }

    .gallery-grid figcaption {
      padding: 13px;
      font-weight: bold;
    }

    .contact {
      background: #211a1d;
      color: white;
    }

    .contact h2 {
      color: #f0c9d8;
    }

    .contact-details {
      max-width: 650px;
      margin: 25px auto;
      text-align: left;
      background: #ffffff10;
      border-radius: 10px;
      padding: 25px;
      overflow-wrap: anywhere;
    }

    .contact-details p {
      margin: 12px 0;
    }

    .contact-details a {
      color: #f4c8da;
    }

    footer {
      background: #130f11;
      color: white;
      text-align: center;
      padding: 20px 12px;
      font-size: 14px;
    }

    @media (max-width: 500px) {
      nav a {
        margin: 4px 7px;
        font-size: 14px;
      }

      section {
        padding: 40px 5%;
      }

      .gallery-grid img {
        height: 260px;
      }
    }
  </style>
</head>

<body>

  <header>
    <h1>ALEX FASHION DESIGNER</h1>
    <p>Your Style. Your Design. Your Perfect Fit.</p>
  </header>

  <nav>
    <a href="#home">Home</a>
    <a href="#services">Services</a>
    <a href="#gallery">Gallery</a>
    <a href="#contact">Contact</a>
  </nav>

  <main>
    <section class="hero" id="home">
      <div>
        <h2>Fashion Made Just for You</h2>
        <p>Elegant designs for weddings, special occasions and everyday style.</p>
        <a class="button" href="#services">Explore Our Services</a>
        <a class="button" href="https://wa.me/27693336311">Contact on WhatsApp</a>
      </div>
    </section>

    <section>
      <div class="intro">
        <h2>Welcome to Alex Fashion Designer</h2>
        <p>
          We bring your fashion ideas to life with custom-made clothing,
          beautiful wedding dresses, traditional outfits, stylish men's suits
          and professional clothing alterations.
          Tell us what you want, and let's create a design for you!
        </p>
      </div>
    </section>

    <section class="services" id="services">
      <h2>Our Services</h2>
      <p>Designs and tailoring to suit your special occasion.</p>

      <div class="service-grid">
        <article class="service-card">
          <h3>Wedding Dresses</h3>
          <p>Beautiful bridal designs for your special day.</p>
        </article>

        <article class="service-card">
          <h3>Traditional Wear</h3>
          <p>Traditional outfits celebrating your style and culture.</p>
        </article>

        <article class="service-card">
          <h3>Men's Suits</h3>
          <p>Smart, elegant suits for weddings and special events.</p>
        </article>

        <article class="service-card">
          <h3>Custom Designs</h3>
          <p>Bring your ideas and let us create something special.</p>
        </article>

        <article class="service-card">
          <h3>Clothing Alterations</h3>
          <p>Modifying and adjusting clothes for a better fit.</p>
        </article>

        <article class="service-card">
          <h3>More Fashion Services</h3>
          <p>Contact us to discuss your design and tailoring needs.</p>
        </article>
      </div>
    </section>

    <section id="gallery">
      <h2>Our Fashion Inspiration</h2>
      <p>Explore styles and ideas for your next outfit.</p>

      <div class="gallery-grid">
        <figure>
          <img
            src="https://images.unsplash.com/photo-1595777457583-95e059d581b8?auto=format&fit=crop&w=800&q=85"
            alt="Elegant formal dress inspiration"
            loading="lazy">
          <figcaption>Elegant Dresses</figcaption>
        </figure>

        <figure>
          <img
            src="https://images.unsplash.com/photo-1519741497674-611481863552?auto=format&fit=crop&w=800&q=85"
            alt="Wedding celebration inspiration"
            loading="lazy">
          <figcaption>Wedding Style</figcaption>
        </figure>

        <figure>
          <img
            src="https://images.unsplash.com/photo-1617137968427-85924c800a22?auto=format&fit=crop&w=800&q=85"
            alt="Men's formal suit inspiration"
            loading="lazy">
          <figcaption>Men's Suits</figcaption>
        </figure>

        <figure>
          <img
            src="https://images.unsplash.com/photo-1539109136881-3be0616acf4b?auto=format&fit=crop&w=800&q=85"
            alt="Fashion and clothing design inspiration"
            loading="lazy">
          <figcaption>Fashion Designs</figcaption>
        </figure>
      </div>

      <p style="margin-top: 20px;">
        These are inspiration pictures. Ask us about creating your own design.
      </p>
    </section>

    <section class="contact" id="contact">
      <h2>Contact Us</h2>
      <p>Ready for your next design? Get in touch with us.</p>

      <div class="contact-details">
        <p><strong>Business:</strong> Alex Fashion Designer</p>

        <p>
          <strong>Address:</strong>
          517 Pretoria Road, Crystal Park
        </p>

        <p>
          <strong>Phone:</strong>
          <a href="tel:0693336311">069 333 6311</a>
        </p>

        <p>
          <strong>WhatsApp:</strong>
          <a href="https://wa.me/27693336311" target="_blank"
             rel="noopener noreferrer">
            Chat with us on WhatsApp
          </a>
        </p>

        <p><strong>We offer:</strong> Wedding dresses, traditional wear, men's suits, custom designs and alterations.</p>
      </div>

      <a class="button" href="https://wa.me/27693336311">
        Request a Design on WhatsApp
      </a>
    </section>
  </main>

  <footer>
    <p>&copy; 2026 Alex Fashion Designer. All rights reserved.</p>
    <p>517 Pretoria Road, Crystal Park | 069 333 6311</p>
  </footer>

</body>
</html>
