# varun-fitness
My gym website

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewportu" content="width=device-width, initial-scale=1.0">
  <title>Varun Fitness | Transform Yourself</title>
  <meta name="description" content="Varun Fitness - Workout, fitness and nutrition. Start your fitness journey today.">

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    html {
      scroll-behavior: smooth;
    }

    body {
      background: #090909;
      color: #ffffff;
      font-family: Arial, sans-serif;
      line-height: 1.6;
    }

    header {
      background: #111111;
      padding: 18px 6%;
      display: flex;
      justify-content: space-between;
      align-items: center;
      border-bottom: 1px solid #292929;
    }

    .logo {
      color: #ff3030;
      font-size: 23px;
      font-weight: 900;
    }

    .logo span {
      color: white;
    }

    nav a {
      color: white;
      text-decoration: none;
      margin-left: 13px;
      font-size: 13px;
    }

    .hero {
      min-height: 540px;
      padding: 75px 7%;
      display: flex;
      align-items: center;
      background:
        linear-gradient(90deg, #090909 5%, rgba(9,9,9,.82) 48%, rgba(9,9,9,.25)),
        url("https://images.unsplash.com/photo-1534438327276-14e5300c3a48?auto=format&fit=crop&w=1400&q=85")
        center/cover no-repeat;
    }

    .hero-content {
      max-width: 600px;
    }

    .tag {
      color: #ff4545;
      font-weight: bold;
      letter-spacing: 3px;
      font-size: 13px;
    }

    h1 {
      font-size: clamp(42px, 8vw, 72px);
      line-height: 1.05;
      margin: 18px 0;
      font-weight: 900;
    }

    h1 span {
      color: #ff3030;
    }

    .hero p {
      color: #dddddd;
      max-width: 480px;
      margin-bottom: 27px;
    }

    .btn {
      display: inline-block;
      background: #ff3030;
      color: white;
      padding: 13px 22px;
      border-radius: 5px;
      text-decoration: none;
      font-weight: bold;
      margin: 5px 7px 5px 0;
    }

    .btn-outline {
      background: transparent;
      border: 1px solid #ff3030;
    }

    section {
      padding: 65px 7%;
    }

    .section-title {
      text-align: center;
      font-size: 32px;
      margin-bottom: 12px;
    }

    .section-title span {
      color: #ff3030;
    }

    .subtitle {
      color: #aaaaaa;
      text-align: center;
      margin-bottom: 35px;
    }

    .cards {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 22px;
    }

    .card {
      background: #151515;
      border: 1px solid #292929;
      border-radius: 10px;
      overflow: hidden;
      transition: transform .25s, border-color .25s;
    }

    .card:hover {
      transform: translateY(-5px);
      border-color: #ff3030;
    }

    .card img {
      width: 100%;
      height: 210px;
      object-fit: cover;
      display: block;
    }

    .card-content {
      padding: 20px;
    }

    .card h3 {
      color: #ff4545;
      margin-bottom: 8px;
    }

    .card p {
      color: #cccccc;
      font-size: 14px;
    }

    .about {
      background: #111111;
      text-align: center;
    }

    .about p {
      color: #cccccc;
      max-width: 700px;
      margin: 15px auto;
    }

    .contact {
      text-align: center;
    }

    footer {
      background: #111111;
      border-top: 1px solid #292929;
      text-align: center;
      padding: 22px;
      color: #aaaaaa;
      font-size: 13px;
    }

    @media (max-width: 600px) {
      header {
        padding: 15px 4%;
        flex-wrap: wrap;
        gap: 10px;
      }

      nav a {
        margin-left: 8px;
        font-size: 12px;
      }

      .hero {
        min-height: 500px;
        padding: 55px 6%;
        background-position: center;
      }

      section {
        padding: 50px 6%;
      }
    }
  </style>
</head>

<body>
  <header>
    <div class="logo">VARUN <span>FITNESS</span></div>
    <nav>
      <a href="#home">Home</a>
      <a href="#workouts">Workouts</a>
      <a href="#about">About</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <main>
    <section class="hero" id="home">
      <div class="hero-content">
        <div class="tag">NO EXCUSES. JUST RESULTS.</div>
        <h1>BUILD YOUR<br><span>BEST SELF.</span></h1>
        <p>Train hard, eat smart and become stronger every day. Your fitness journey starts here.</p>
        <a class="btn" href="#workouts">EXPLORE WORKOUTS</a>
        <a class="btn btn-outline"
          href="https://wa.me/919532356538?text=Hello%20Varun%20Fitness%2C%20mujhe%20fitness%20ke%20baare%20mein%20jaankari%20chahiye.">
          JOIN ON WHATSAPP
        </a>
      </div>
    </section>

    <section id="workouts">
      <h2 class="section-title">OUR <span>FITNESS</span> ZONE</h2>
      <p class="subtitle">Choose your goal. Work for it. Get stronger.</p>

      <div class="cards">
        <article class="card">
          <img src="https://images.unsplash.com/photo-1583454110551-21f2fa2afe61?auto=format&fit=crop&w=800&q=80" alt="Strength training with weights">
          <div class="card-content">
            <h3>Strength Training</h3>
            <p>Build strength and muscle with consistent workouts and correct form.</p>
          </div>
        </article>

        <article class="card">
          <img src="https://images.unsplash.com/photo-1534258936925-c58bed479fcb?auto=format&fit=crop&w=800&q=80" alt="Cardio workout">
          <div class="card-content">
            <h3>Cardio Fitness</h3>
            <p>Improve stamina, endurance and overall fitness with regular activity.</p>
          </div>
        </article>

        <article class="card">
          <img src="https://images.unsplash.com/photo-1517836357463-d25dfeac3438?auto=format&fit=crop&w=800&q=80" alt="Athlete training in gym">
          <div class="card-content">
            <h3>Body Transformation</h3>
            <p>Work towards your goals with training, recovery and balanced nutrition.</p>
          </div>
        </article>
      </div>
    </section>
    

<section id="membership" style="background:#090909;padding:55px 6%;color:white;">
  <h2 style="text-align:center;font-size:32px;margin-bottom:10px;">
    OUR <span style="color:#ff3030;">MEMBERSHIPS</span>
  </h2>
  <p style="text-align:center;color:#aaa;margin-bottom:30px;">
    Choose your fitness journey
  </p>

  <div style="display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:20px;">

    <div style="background:#151515;border:1px solid #333;border-radius:10px;padding:25px;text-align:center;">
      <h3 style="color:#ff3030;">BASIC</h3>
      <h2 style="margin:15px 0;">Starter Plan</h2>
      <p style="color:#ccc;">Workout guidance</p>
      <p style="color:#ccc;">Beginner fitness tips</p>
      <a href="https://wa.me/919532356538?text=Hello%2C%20mujhe%20Basic%20membership%20ki%20jaankari%20chahiye."
      style="display:inline-block;background:#ff3030;color:white;padding:12px 18px;border-radius:5px;text-decoration:none;margin-top:20px;font-weight:bold;">
        ENQUIRE NOW
      </a>
    </div>

    <div style="background:#151515;border:2px solid #ff3030;border-radius:10px;padding:25px;text-align:center;">
      <h3 style="color:#ff3030;">STANDARD</h3>
      <h2 style="margin:15px 0;">Fitness Plan</h2>
      <p style="color:#ccc;">Workout routine guidance</p>
      <p style="color:#ccc;">Nutrition guidance</p>
      <a href="https://wa.me/919532356538?text=Hello%2C%20mujhe%20Standard%20membership%20ki%20jaankari%20chahiye."
      style="display:inline-block;background:#ff3030;color:white;padding:12px 18px;border-radius:5px;text-decoration:none;margin-top:20px;font-weight:bold;">
        ENQUIRE NOW
      </a>
    </div>

    <div style="background:#151515;border:1px solid #333;border-radius:10px;padding:25px;text-align:center;">
      <h3 style="color:#ff3030;">PREMIUM</h3>
      <h2 style="margin:15px 0;">Personal Plan</h2>
      <p style="color:#ccc;">Personalised workout guidance</p>
      <p style="color:#ccc;">Fitness goal planning</p>
      <a href="https://wa.me/919532356538?text=Hello%2C%20mujhe%20Premium%20membership%20ki%20jaankari%20chahiye."
      style="display:inline-block;background:#ff3030;color:white;padding:12px 18px;border-radius:5px;text-decoration:none;margin-top:20px;font-weight:bold;">
        ENQUIRE NOW
      </a>
    </div>

  </div>
</section>



    <section class="about" id="about">
      <h2 class="section-title">ABOUT <span>VARUN FITNESS</span></h2>
      <p>Fitness is not just about lifting weights. It is about discipline, confidence and becoming better every day.</p>
      <p>Start small, stay consistent and keep moving forward.</p>
    </section>

    <section class="contact" id="contact">
      <h2 class="section-title">START YOUR <span>JOURNEY</span></h2>
      <p class="subtitle">Have a fitness question? Get in touch with us.</p>
      <a class="btn"
        href="https://wa.me/919532356538?text=Hello%20Varun%20Fitness%2C%20mujhe%20fitness%20ke%20baare%20mein%20jaankari%20chahiye.">
        CHAT ON WHATSAPP
      </a>
      <a class="btn btn-outline"
        href="upi://pay?pa=Shuklavarunji99@okaxis&pn=Varun%20Shukla&cu=INR">
        PAY WITH UPI
      </a>
    </section>
  </main>

  <footer>
    <p>© 2026 Varun Fitness. Stay Strong. Stay Consistent.</p>
  </footer>
</body>
</html>
