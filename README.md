<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Tooth or Dare Dental Clinic</title>
  <style>
    body { font-family: 'Poppins', Arial, sans-serif; margin: 0; padding: 0; background-color: #fefefe; color: #333; }
    header { background: linear-gradient(135deg, #00b4d8, #0077b6); color: #fff; padding: 3rem 1rem; text-align: center; }
    header h1 { font-size: 2.5rem; margin: 0; font-weight: 700; }
    header p { margin-top: 0.5rem; font-size: 1.2rem; }
    nav { margin-top: 1.5rem; }
    nav a { margin: 0 1rem; color: #fff; text-decoration: none; font-weight: 600; transition: color 0.3s; }
    nav a:hover { color: #caf0f8; }
    section { padding: 3rem 2rem; max-width: 1100px; margin: auto; }
    h2 { color: #0077b6; font-size: 2rem; margin-bottom: 1rem; border-bottom: 3px solid #00b4d8; display: inline-block; padding-bottom: 0.3rem; }
    p { line-height: 1.7; }
    .services, .achievements { display: grid; grid-template-columns: repeat(auto-fit, minmax(280px, 1fr)); gap: 1.5rem; margin-top: 1.5rem; }
    .card { border-radius: 12px; padding: 1.5rem; background: #ffffff; box-shadow: 0 4px 8px rgba(0,0,0,0.05); transition: transform 0.3s; }
    .card:hover { transform: translateY(-5px); }
    .card h3 { margin-top: 0; color: #00b4d8; }
    form { margin-top: 2rem; background: #f1faff; padding: 2rem; border-radius: 12px; box-shadow: 0 4px 6px rgba(0,0,0,0.05); }
    form label { font-weight: 600; }
    form input, form textarea { width: 100%; padding: 0.8rem; margin-top: 0.5rem; margin-bottom: 1rem; border: 1px solid #ccc; border-radius: 8px; }
    form button { background: #00b4d8; color: #fff; padding: 0.8rem 1.5rem; border: none; border-radius: 8px; cursor: pointer; font-weight: 600; }
    form button:hover { background: #0077b6; }
    footer { background: #0077b6; color: #fff; text-align: center; padding: 1.5rem; margin-top: 3rem; }
    footer p { margin: 0.3rem 0; }
  </style>
</head>
<body>
  <header>
    <h1>Tooth or Dare Dental Clinic</h1>
    <p>Truth is, your smile deserves care. Dare to keep it healthy!</p>
    <nav>
      <a href="#home">Home</a>
      <a href="#about">About Us</a>
      <a href="#services">Services</a>
      <a href="#contact">Contact Us</a>
    </nav>
  </header>

  <section id="home">
    <h2>Welcome to Tooth or Dare Dental Clinic</h2>
    <p>
      Welcome to Tooth or Dare Dental Clinic, your trusted partner in achieving and maintaining the perfect smile. Our playful name reflects our philosophy: dental care doesn’t have to be intimidating—it can be fun, professional, and life-changing. 
    </p>
    <p>
      At Tooth or Dare, we dare you to dream of a brighter, healthier smile—and we’ll provide the truth about how to achieve it. With our state-of-the-art facilities, compassionate dentists, and innovative treatments, you can feel confident that your oral health is in safe hands.
    </p>
  </section>

  <section id="about">
    <h2>About Us</h2>
    <p>
      Tooth or Dare Dental Clinic was built on the vision of transforming smiles while making dental visits enjoyable. Based in Plaridel, Bulacan, we are proud to be a modern clinic where advanced dental technology meets a welcoming atmosphere. Our team is passionate about breaking the stereotype that dental visits are scary. Instead, we make it a positive experience—one that’s focused on comfort, education, and results.
    </p>
    <p>
      Our professionals have years of expertise in orthodontics, cosmetic dentistry, restorative treatments, and preventive care. More than providing services, we educate our patients about oral health, empowering them to take charge of their smiles. Through outreach programs, we’ve also helped schools and communities build better dental habits.
    </p>

    <h3>Our Achievements</h3>
    <div class="achievements">
      <div class="card">🏆 Recognized as one of Bulacan’s Top Dental Clinics (2024).</div>
      <div class="card">🎓 Over 15 years of combined professional experience among our dentists.</div>
      <div class="card">🦷 Served 1,500+ satisfied patients with exceptional dental care.</div>
      <div class="card">🌐 Active participants in Philippine Dental Association seminars and conventions.</div>
      <div class="card">💡 Introduced the innovative “Truth or Dare” oral health program for schools.</div>
      <div class="card">💎 Excellence in orthodontics, cosmetic dentistry, and advanced restorative care.</div>
      <div class="card">❤️ Consistently maintaining a 95% patient satisfaction rating.</div>
    </div>
  </section>

  <section id="services">
    <h2>Our Services</h2>
    <div class="services">
      <div class="card">
        <h3>General Check-Up & Cleaning</h3>
        <p>Maintain healthy teeth and gums with regular preventive check-ups.</p>
      </div>
      <div class="card">
        <h3>Fillings & Restorative Care</h3>
        <p>Restore damaged teeth with durable fillings and restorative solutions.</p>
      </div>
      <div class="card">
        <h3>Orthodontics</h3>
        <p>Braces and aligners that align your teeth and boost your confidence.</p>
      </div>
      <div class="card">
        <h3>Teeth Whitening</h3>
        <p>Brighten your smile with safe and effective cosmetic treatments.</p>
      </div>
      <div class="card">
        <h3>Pediatric Dentistry</h3>
        <p>Gentle, fun, and educational care for our younger patients.</p>
      </div>
      <div class="card">
        <h3>Emergency Services</h3>
        <p>Quick and compassionate care for urgent dental problems.</p>
      </div>
    </div>
  </section>

  <section id="contact">
    <h2>Contact Us</h2>
    <p><strong>Address:</strong> Plaridel, Bulacan, Philippines</p>
    <p><strong>Phone:</strong> +63 912 345 6789</p>
    <p><strong>Email:</strong> toothordareclinic@gmail.com</p>
    <p><strong>Website:</strong> www.toothordareclinic.com</p>
    <form>
      <label for="name">Name:</label><br />
      <input type="text" id="name" name="name" required /><br />

      <label for="phone">Phone:</label><br />
      <input type="text" id="phone" name="phone" /><br />

      <label for="message">Message:</label><br />
      <textarea id="message" name="message" rows="4"></textarea><br />

      <button type="submit">Submit</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2025 Tooth or Dare Dental Clinic. All Rights Reserved.</p>
    <p><em>For educational purposes only.</em></p>
  </footer>
</body>
</html>
# toothordaredentalclinic-
