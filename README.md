```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Electric Film TX</title>
  <meta name="description" content="Electric Film TX - Premium smart window tinting, automotive film, residential & commercial window film in El Paso, TX.">
  <style>
    :root {
      --accent: #ff6600;
      --dark: #1a1a1a;
      --max-width: 1100px;
    }
    * { box-sizing: border-box; }
    body {
      margin: 0;
      font-family: Arial, Helvetica, sans-serif;
      color: #333;
      background: #f5f5f5;
    }

    /* Header */
    header {
      background: var(--dark);
      color: white;
    }
    .header-inner {
      max-width: var(--max-width);
      margin: 0 auto;
      padding: 14px 18px;
      display: flex;
      align-items: center;
      justify-content: space-between;
      flex-wrap: wrap;
    }
    .brand {
      display: flex;
      align-items: center;
      gap: 12px;
    }
    .logo {
      height: 64px;
      width: auto;
    }
    nav a {
      color: white;
      text-decoration: none;
      margin-left: 14px;
      font-weight: 600;
    }
    nav a:hover { text-decoration: underline; }

    /* Hero */
    .hero {
      height: 420px;
      background: url("https://i.postimg.cc/jWnHKjY6/your-image.jpg") center/cover no-repeat;
      display: flex;
      align-items: center;
      justify-content: center;
      color: white;
      text-shadow: 0 2px 8px rgba(0,0,0,0.7);
    }
    .hero h2 {
      font-size: 2rem;
      background: rgba(0,0,0,0.4);
      padding: 10px 20px;
      border-radius: 6px;
    }

    /* Sections */
    main { max-width: var(--max-width); margin: 28px auto; padding: 0 18px 80px; }
    section { margin-bottom: 36px; }
    h1, h2 { color: var(--dark); margin: 0 0 14px 0; }
    p { line-height: 1.6; margin: 0 0 12px 0; }
    ul { margin: 0 0 12px 20px; }

    /* Buttons */
    .cta-button {
      display: inline-block;
      background: var(--accent);
      color: #fff;
      padding: 10px 14px;
      border-radius: 6px;
      text-decoration: none;
      font-weight: bold;
      margin-top: 10px;
    }
    .cta-button:hover { opacity: 0.9; }

    /* Contact form */
    form {
      display: flex;
      flex-direction: column;
      gap: 12px;
      max-width: 520px;
    }
    input, textarea {
      padding: 10px 12px;
      border: 1px solid #ccc;
      border-radius: 6px;
      font-size: 15px;
    }
    button {
      background: var(--accent);
      color: #fff;
      border: none;
      padding: 10px 14px;
      border-radius: 6px;
      font-weight: bold;
      cursor: pointer;
    }
    button:hover { opacity: 0.95; }

    /* Footer */
    footer {
      background: var(--dark);
      color: white;
      text-align: center;
      padding: 18px;
    }

    /* Responsive */
    @media (max-width: 640px) {
      .hero h2 { font-size: 1.4rem; text-align: center; }
    }
  </style>
</head>
<body>

  <!-- Header -->
  <header>
    <div class="header-inner">
      <div class="brand">
        <img src="https://i.postimg.cc/4Y6NGfDV/logo.jpg" alt="Electric Film Logo" class="logo">
        <h1>Electric Film TX</h1>
      </div>
      <nav>
        <a href="#about">About</a>
        <a href="#services">Services</a>
        <a href="#contact">Contact</a>
      </nav>
    </div>
  </header>

  <!-- Hero -->
  <section class="hero">
    <h2>Your Vehicle, Your Style, Our Protection</h2>
  </section>

  <main>
    <!-- About -->
    <section id="about">
      <h2>About Us</h2>
      <p>At Electric Film, we specialize in smart window tint solutions that combine style, comfort, and cutting-edge technology. Our films provide privacy, UV protection, heat reduction, and an instant upgrade to any space—whether it’s your home, office, or vehicle.</p>
      <p>We are committed to delivering high-quality products and professional installation with a focus on customer satisfaction. Our smart window tints are designed to enhance your lifestyle by improving comfort, energy efficiency, and aesthetics without compromising on style.</p>
      <ul>
        <li><strong>Smart Technology:</strong> Modern, responsive window films that adapt to your needs.</li>
        <li><strong>UV & Heat Protection:</strong> Keep interiors cool and safe from harmful rays.</li>
        <li><strong>Privacy & Style:</strong> Sleek, modern designs while maintaining discretion.</li>
        <li><strong>Professional Service:</strong> Expert installation and support from start to finish.</li>
      </ul>
    </section>

    <!-- Services -->
    <section id="services">
      <h2>Our Services</h2>
      <ul>
        <li>Automotive Window Tinting</li>
        <li>Residential & Commercial Window Film</li>
        <li>Paint Protection Film</li>
        <li>Custom Solutions for Your Vehicle or Home</li>
      </ul>
      <a href="#contact" class="cta-button">Get a Quote</a>
    </section>

    <!-- Contact -->
    <section id="contact">
      <h2>Contact Us</h2>
      <form action="mailto:electricfilm@outlook.com" method="post" enctype="text/plain">
        <input type="text" name="name" placeholder="Your Name" required>
        <input type="email" name="email" placeholder="Your Email" required>
        <textarea name="message" rows="5" placeholder="Your Message" required></textarea>
        <button type="submit">Send Message</button>
      </form>
      <p style="margin-top:14px">
        Email: <a href="mailto:electricfilm@outlook.com">electricfilm@outlook.com</a><br>
        Phone: 915-238-7847<br>
        Instagram: <a href="https://www.instagram.com/electricfilmep/" target="_blank">@electricfilmep</a>
      </p>
    </section>
  </main>

  <!-- Footer -->
  <footer>
    <small>&copy; 2025 Electric Film TX. All rights reserved.</small>
  </footer>

</body>
</html>
```
