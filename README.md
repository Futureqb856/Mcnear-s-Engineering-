# Mcnear-s-Engineering-
Pratice Website 
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>McNear's Engineering</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet">
  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family: 'Poppins', sans-serif;
      background: linear-gradient(to right, #e0f7fa, #ffffff);
      color: #333;
      padding: 20px;
    }

    .container {
      max-width: 960px;
      margin: auto;
    }

    /* 🌟 HERO BANNER STYLES */
    .hero {
      position: relative;
      background-image: url('https://images.unsplash.com/photo-1605902711622-cfb43c4437f1?auto=format&fit=crop&w=1600&q=80');
      background-size: cover;
      background-position: center;
      height: 90vh;
      border-radius: 20px;
      overflow: hidden;
      margin-bottom: 50px;
    }

    .hero-overlay {
      background: rgba(0, 0, 0, 0.6);
      width: 100%;
      height: 100%;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
      padding: 20px;
    }

    .hero-content {
      color: #fff;
      max-width: 700px;
      padding: 30px;
    }

    .hero h1 {
      font-size: 3rem;
      font-weight: 600;
      margin-bottom: 20px;
      line-height: 1.3;
    }

    .hero p {
      font-size: 1.2rem;
      margin-bottom: 30px;
      color: #eee;
    }

    .hero-btn {
      background-color: #00bcd4;
      color: white;
      padding: 14px 28px;
      font-size: 16px;
      border-radius: 8px;
      text-decoration: none;
      transition: background 0.3s ease, transform 0.3s ease;
    }

    .hero-btn:hover {
      background-color: #0097a7;
      transform: translateY(-2px);
    }

    /* 🧩 HEADER AND SECTIONS */
    header {
      text-align: center;
      margin-bottom: 40px;
    }

    header img {
      max-width: 120px;
      border-radius: 50%;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
      margin-bottom: 10px;
    }

    h1 {
      font-size: 2.5rem;
      color: #007BFF;
    }

    p.tagline {
      font-size: 1.1rem;
      color: #555;
    }

    section {
      background: #fff;
      padding: 30px;
      margin-bottom: 25px;
      border-radius: 16px;
      box-shadow: 0 8px 20px rgba(0, 0, 0, 0.05);
      transition: transform 0.2s;
    }

    section:hover {
      transform: scale(1.01);
    }

    h2 {
      font-size: 1.8rem;
      margin-bottom: 15px;
      color: #333;
    }

    ul {
      list-style: disc;
      margin-left: 20px;
      color: #444;
    }

    button {
      background: #007BFF;
      color: white;
      padding: 14px 24px;
      border: none;
      border-radius: 8px;
      font-size: 16px;
      margin-top: 10px;
      cursor: pointer;
      transition: background 0.3s;
    }

    button:hover {
      background: #0056b3;
    }

    @media (max-width: 600px) {
      .hero h1 {
        font-size: 2rem;
      }

      .hero p {
        font-size: 1rem;
      }

      .hero-content {
        padding: 20px;
      }

      h1 {
        font-size: 1.8rem;
      }

      section {
        padding: 20px;
      }

      button {
        width: 100%;
      }
    }
  </style>
</head>
<body>
  <div class="container">

    <!-- ✅ HERO BANNER SECTION (added to the top) -->
    <section class="hero">
      <div class="hero-overlay">
        <div class="hero-content">
          <h1>Innovating One Project at a Time</h1>
          <p>Your trusted partner in design, development, and engineering.</p>
          <a href="#contact" class="hero-btn">Start Your Project</a>
        </div>
      </div>
    </section>

    <!-- ✅ ORIGINAL HEADER -->
    <header>
      <img src="https://th.bing.com/th/id/OIP._I9M8psZI1BzZhbyjV2K9AHaHa?rs=1&pid=ImgDetMain" alt="Business Logo" />
      <h1>McNear's Engineering</h1>
      <p class="tagline">Future engineer. Current learner. Always coding.</p>
    </header>

    <!-- ✅ SERVICES SECTION -->
    <section>
      <h2>Our Services</h2>
      <ul>
        <li>Design</li>
        <li>Develop</li>
        <li>Test Software</li>
      </ul>
    </section>

    <!-- ✅ ABOUT SECTION -->
    <section>
      <h2>About Us</h2>
      <p>
        At McNear's Engineering, we’re passionate about solving problems with smart technology.
        We’ve been helping clients succeed online and offline for over 5 years!
      </p>
    </section>

    <!-- ✅ CONTACT SECTION -->
    <section id="contact">
      <h2>Contact Us</h2>
      <p>Email: <a href="mailto:Futureqb856@gmail.com">Futureqb856@gmail.com</a></p>
      <p>Phone: <a href="tel:+14783187149">(478)-318-7149</a></p>
      <button onclick="alert('One project down, many more to go.')">
        Get in Touch
      </button>
    </section>

  </div>
</body>
</html>
