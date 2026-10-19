# rohit-sharnagat
Digital Marketing Portfolio


<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Rohit | Digital Marketing</title>
  <meta name="description" content="Rohit's digital marketing portfolio featuring social media, paid ads and brand strategy.">
  <style>
    * { box-sizing: border-box; }
    body {
      margin: 0;
      background: #0b0b0b;
      color: #f7f7f7;
      font-family: Arial, sans-serif;
      line-height: 1.7;
    }
    header {
      padding: 22px 8%;
      border-bottom: 1px solid #333;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    header a { color: white; text-decoration: none; }
    .logo { font-size: 22px; font-weight: bold; }
    .yellow { color: #f5d547; }
    nav { display: flex; gap: 18px; }
    .hero { padding: 100px 8%; }
    .tag { color: #f5d547; letter-spacing: 2px; font-size: 13px; }
    h1 { font-size: clamp(42px, 8vw, 76px); line-height: 1.1; }
    p { color: #bbb; max-width: 650px; }
    .btn {
      display: inline-block; margin-top: 15px;
      padding: 12px 20px; border-radius: 5px;
      background: #f5d547; color: #111;
      text-decoration: none; font-weight: bold;
    }
    section { padding: 55px 8%; }
    .grid { display: grid; grid-template-columns: repeat(3, 1fr); gap: 18px; }
    .card { background: #191919; border: 1px solid #333; padding: 22px; border-radius: 10px; }
    footer { padding: 25px 8%; color: #aaa; border-top: 1px solid #333; }
    @media (max-width: 650px) {
      header { flex-wrap: wrap; gap: 12px; }
      nav { flex-wrap: wrap; gap: 12px; }
      .hero { padding: 65px 6%; }
      section { padding: 40px 6%; }
      .grid { grid-template-columns: 1fr; }
    }
  </style>
</head>
<body>
  <header>
    <a class="logo" href="#">ROHIT<span class="yellow">.</span></a>
    <nav>
      <a href="#about">About</a>
      <a href="#services">Services</a>
      <a href="#work">Work</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <main>
    <div class="hero">
      <div class="tag">DIGITAL MARKETING • BRAND STRATEGY</div>
      <h1>Building Brands.<br>Creating <span class="yellow">Impact.</span></h1>
      <p>I'm Rohit, a digital marketer focused on social media,
      content strategy, paid advertising and lead generation.</p>
      <a class="btn" href="#work">Explore My Work ↓</a>
    </div>

    <section id="about">
      <div class="tag">01 / ABOUT</div>
      <h2>Marketing with <span class="yellow">Purpose.</span></h2>
      <p>I help brands build a stronger digital presence through
      creative communication, content planning and performance-focused campaigns.</p>
    </section>

    <section id="services">
      <div class="tag">02 / SERVICES</div>
      <h2>What I <span class="yellow">Do</span></h2>
      <div class="grid">
        <div class="card"><h3>Social Media</h3><p>Content calendars, reels and captions.</p></div>
        <div class="card"><h3>Meta Ads</h3><p>Ad creative strategy and lead generation.</p></div>
        <div class="card"><h3>Brand Strategy</h3><p>Brand communication and digital campaigns.</p></div>
      </div>
    </section>

    <section id="work">
      <div class="tag">03 / PORTFOLIO</div>
      <h2>Selected <span class="yellow">Work</span></h2>
      <div class="grid">
        <div class="card"><h3>Automotive</h3><p>Social media content and service campaigns.</p></div>
        <div class="card"><h3>Fintech</h3><p>Short-form ad scripts and campaign concepts.</p></div>
        <div class="card"><h3>Building Materials</h3><p>Product communication and content planning.</p></div>
      </div>
      <p>Replace these examples with your approved work and verified results.</p>
    </section>

    <section id="contact">
      <div class="tag">04 / CONTACT</div>
      <h2>Let's <span class="yellow">Connect.</span></h2>
      <p>Have a project in mind? Let's talk.</p>
      <a class="btn" href="mailto:YOUR_EMAIL@example.com">Email Me</a>
    </section>
  </main>

  <footer>© 2026 Rohit | Digital Marketing Portfolio</footer>
</body>
</html>
