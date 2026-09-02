<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Boluwatife Esther | Freelancer</title>

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: Arial, sans-serif;
      background: #f8f7ff;
      color: #222;
      line-height: 1.6;
    }

    nav {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 20px 8%;
      background: white;
      position: sticky;
      top: 0;
      z-index: 10;
    }

    nav h2 {
      color: #6c3cff;
    }

    nav a {
      text-decoration: none;
      color: #333;
      margin-left: 25px;
      font-weight: bold;
    }

    .hero {
      min-height: 85vh;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
      padding: 60px 20px;
    }

    .hero-content {
      max-width: 800px;
    }

    .hero h1 {
      font-size: 55px;
      margin-bottom: 15px;
    }

    .hero h1 span {
      color: #6c3cff;
    }

    .hero p {
      font-size: 20px;
      color: #666;
      margin-bottom: 30px;
    }

    .btn {
      display: inline-block;
      padding: 14px 28px;
      background: #6c3cff;
      color: white;
      text-decoration: none;
      border-radius: 8px;
      font-weight: bold;
    }

    section {
      padding: 80px 8%;
    }

    section h2 {
      text-align: center;
      font-size: 35px;
      margin-bottom: 40px;
    }

    .about {
      max-width: 800px;
      margin: auto;
      text-align: center;
      color: #555;
      font-size: 18px;
    }

    .services {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 25px;
    }

    .card {
      background: white;
      padding: 30px;
      border-radius: 15px;
      box-shadow: 0 5px 20px rgba(0,0,0,0.08);
      text-align: center;
    }

    .card h3 {
      margin-bottom: 12px;
      color: #6c3cff;
    }

    .contact {
      text-align: center;
      background: #eeeaff;
    }

    footer {
      text-align: center;
      padding: 25px;
      background: #222;
      color: white;
    }

    @media (max-width: 600px) {
      .hero h1 {
        font-size: 40px;
      }

      nav {
        flex-direction: column;
        gap: 10px;
      }

      nav a {
        margin-left: 10px;
      }
    }
  </style>
</head>

<body>

  <nav>
    <h2>Boluwatife</h2>

    <div>
      <a href="#about">About</a>
      <a href="#services">Services</a>
      <a href="#contact">Contact</a>
    </div>
  </nav>

  <section class="hero">
    <div class="hero-content">
      <h1>Hi, I'm <span>Boluwatife Esther</span></h1>

      <p>
        A creative freelancer helping businesses and creators
        grow through digital marketing, content creation and online solutions.
      </p>

      <a href="#contact" class="btn">Let's Work Together</a>
    </div>
  </section>

  <section id="about">
    <h2>About Me</h2>

    <p class="about">
      I'm a passionate freelancer specializing in digital marketing,
      YouTube growth, content creation and creative online services.
      I help brands, creators and businesses build a stronger online presence
      and turn their ideas into results.
    </p>
  </section>

  <section id="services">
    <h2>My Services</h2>

    <div class="services">

      <div class="card">
        <h3>Digital Marketing</h3>
        <p>
          Helping businesses reach the right audience and improve
          their online visibility.
        </p>
      </div>

      <div class="card">
        <h3>YouTube Growth</h3>
        <p>
          YouTube SEO, Shorts optimization, channel strategy
          and content growth support.
        </p>
      </div>

      <div class="card">
        <h3>Content Creation</h3>
        <p>
          Creative videos, social media content and engaging
          visual content for brands and creators.
        </p>
      </div>

      <div class="card">
        <h3>Freelance Services</h3>
        <p>
          Professional online services tailored to your business
          and personal brand.
        </p>
      </div>

    </div>
  </section>

  <section id="contact" class="contact">
    <h2>Let's Work Together</h2>

    <p>
      Have a project in mind? I'd love to hear from you.
    </p>

    <br>

    <a href="mailto:your@email.com" class="btn">
      Contact Me
    </a>
  </section>

  <footer>
    <p>© 2026 Boluwatife Esther. All Rights Reserved.</p>
  </footer>

</body>
</html>
