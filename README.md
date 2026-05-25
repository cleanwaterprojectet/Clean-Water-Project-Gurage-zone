<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Clean Water Project Ethiopia Enemor/Gurage Region by Amy Tesfaye</title>

  <style>
    *{
      box-sizing:border-box;
      scroll-behavior:smooth;
    }

    body{
      margin:0;
      font-family:Arial, Helvetica, sans-serif;
      background:#f8fafc;
      color:#0f172a;
      line-height:1.6;
    }

    header{
      position:sticky;
      top:0;
      z-index:10;
      background:rgba(255,255,255,.95);
      border-bottom:1px solid #e2e8f0;
    }

    .nav{
      max-width:1150px;
      margin:auto;
      padding:18px 24px;
      display:flex;
      align-items:center;
      justify-content:space-between;
      gap:20px;
    }

    .logo{
      font-weight:800;
      font-size:18px;
      color:#0f172a;
    }

    .nav-links{
      display:flex;
      gap:22px;
      font-size:14px;
      font-weight:600;
    }

    .nav-links a{
      color:#334155;
      text-decoration:none;
    }

    .btn{
      display:inline-block;
      padding:13px 22px;
      border-radius:999px;
      background:#2563eb;
      color:white;
      text-decoration:none;
      font-weight:700;
    }

    .btn.light{
      background:white;
      color:#1d4ed8;
    }

    .btn.outline{
      background:transparent;
      border:2px solid white;
      color:white;
    }

    .hero{
      background:linear-gradient(135deg,#0f172a,#1d4ed8,#0891b2);
      color:white;
      padding:88px 24px;
    }

    .hero-inner{
      max-width:1150px;
      margin:auto;
      display:grid;
      grid-template-columns:1fr 1fr;
      gap:48px;
      align-items:center;
    }

    .eyebrow{
      text-transform:uppercase;
      letter-spacing:2px;
      font-size:13px;
      color:#bfdbfe;
      font-weight:700;
      margin-bottom:16px;
    }

    h1{
      font-size:clamp(42px,6vw,68px);
      line-height:1.02;
      margin:0 0 22px;
    }

    .hero p{
      font-size:20px;
      color:#e0f2fe;
      margin-bottom:28px;
    }

    .actions{
      display:flex;
      gap:14px;
      flex-wrap:wrap;
    }

    .video-card{
      background:rgba(255,255,255,.14);
      border:1px solid rgba(255,255,255,.22);
      border-radius:28px;
      padding:16px;
      box-shadow:0 24px 70px rgba(0,0,0,.28);
    }

    video{
      width:100%;
      border-radius:20px;
      display:block;
      background:black;
    }

    section{
      padding:80px 24px;
    }

    .container{
      max-width:1100px;
      margin:auto;
    }

    .section-title{
      max-width:780px;
      margin-bottom:34px;
    }

    .section-title span{
      color:#2563eb;
      text-transform:uppercase;
      letter-spacing:1.8px;
      font-size:13px;
      font-weight:800;
    }

    h2{
      font-size:clamp(30px,4vw,44px);
      line-height:1.12;
      margin:10px 0 16px;
    }

    .grid{
      display:grid;
      grid-template-columns:repeat(3,1fr);
      gap:22px;
    }

    .card{
      background:white;
      border:1px solid #e2e8f0;
      border-radius:24px;
      padding:28px;
      box-shadow:0 12px 30px rgba(15,23,42,.06);
    }

    .card h3{
      margin-top:0;
      font-size:22px;
    }

    .about{
      display:grid;
      grid-template-columns:1.1fr .9fr;
      gap:40px;
      align-items:center;
    }

    .photo-placeholder{
      background:linear-gradient(135deg,#dbeafe,#ecfeff);
      border-radius:28px;
      min-height:320px;
      display:flex;
      align-items:center;
      justify-content:center;
      text-align:center;
      padding:28px;
      color:#334155;
      border:1px dashed #60a5fa;
    }

    .white{
      background:#ffffff;
    }

    .donate{
      background:#0f172a;
      color:white;
      text-align:center;
    }

    .donate p{
      color:#cbd5e1;
      max-width:780px;
      margin:0 auto 28px;
      font-size:18px;
    }

    footer{
      background:#020617;
      color:white;
      text-align:center;
      padding:38px 20px;
    }

    footer p{
      margin:6px 0;
      color:#cbd5e1;
    }

    @media(max-width:850px){
      .hero-inner,.about{
        grid-template-columns:1fr;
      }

      .grid{
        grid-template-columns:1fr;
      }

      .nav-links{
        display:none;
      }

      .hero{
        padding:64px 20px;
      }
    }
  </style>
</head>

<body>

<header>
  <div class="nav">
    <div class="logo">💧 Clean Water Project Ethiopia Enemor/Gurage Region by Amy Tesfaye</div>

    <div class="nav-links">
      <a href="#about">About</a>
      <a href="#problem">The Problem</a>
      <a href="#solution">Solution</a>
      <a href="#donate">Donate</a>
    </div>

    <a class="btn" href="#donate">Donate Now</a>
  </div>
</header>

<main>

<section class="hero">
  <div class="hero-inner">

    <div>
      <div class="eyebrow">
        Student-led initiative supporting clean water access in Ethiopia
      </div>

      <h1>Clean Water Changes Everything.</h1>

      <p>
        Clean Water Project Ethiopia is working to support safe and reliable water access for families in Ethiopia’s Enemor/Gurage region through fundraising, awareness, and long-term community support.
      </p>

      <div class="actions">
        <a class="btn light" href="#donate">Donate to the Project</a>
        <a class="btn outline" href="#about">Learn More</a>
      </div>
    </div>

    <div class="video-card">
      <video controls autoplay muted loop>
        <source src="Clean Water Project by Amy Tesfaye .mov" type="video/mp4">
      </video>
    </div>

  </div>
</section>

<section class="container" style="padding-top:50px;padding-bottom:20px">
  <div class="grid">

    <div class="card">
      <h3>Families</h3>
      <p>Supporting healthier daily life through clean water access.</p>
    </div>

    <div class="card">
      <h3>Community</h3>
      <p>Working toward sustainable solutions shaped by local needs.</p>
    </div>

    <div class="card">
      <h3>Future</h3>
      <p>Helping create long-term change for children and families.</p>
    </div>

  </div>
</section>

<section id="about">

  <div class="container about">

    <div>

      <div class="section-title">
        <span>About the Project</span>
        <h2>A personal mission led by Amy Tesfaye</h2>
      </div>

      <p>
        Clean Water Project Ethiopia is a student-led initiative focused on supporting access to safe drinking water for communities in Ethiopia, beginning with the Enemor/Gurage region.
      </p>

      <p>
        After visiting Ethiopia and seeing firsthand the challenges many families face accessing clean and reliable water, Amy Tesfaye wanted to turn awareness into action.
      </p>

      <p>
        Through fundraising, storytelling, and partnerships, Clean Water Project Ethiopia aims to support sustainable water solutions that can improve health, education, and daily life for families and children across Ethiopia.
      </p>

    </div>

    <div class="photo-placeholder">
      <div>
        <h3>Photo Placeholder</h3>
        <p>Add a real photo from Ethiopia or the community here.</p>
      </div>
    </div>

  </div>

</section>

<section id="problem" class="white">

  <div class="container">

    <div class="section-title">
      <span>The Problem</span>

      <h2>
        Without clean water, everyday life becomes harder.
      </h2>

      <p>
        In many parts of Ethiopia, families may spend hours collecting water each day, and the water available is not always safe to drink.
      </p>
    </div>

    <div class="grid">

      <div class="card">
        <h3>Health Risks</h3>
        <p>Unsafe water can expose families to illness and make daily life more difficult.</p>
      </div>

      <div class="card">
        <h3>Time Burden</h3>
        <p>Collecting water can take time away from school, work, and family life.</p>
      </div>

      <div class="card">
        <h3>Limited Opportunity</h3>
        <p>Water access impacts education, development, and the future of children.</p>
      </div>

    </div>

  </div>

</section>

<section id="solution">

  <div class="container">

    <div class="section-title">
      <span>The Solution</span>

      <h2>Fundraising for sustainable water access.</h2>

      <p>
        Donations will help support clean water solutions based on community needs and guidance from local partners in Ethiopia.
      </p>
    </div>

    <div class="grid">

      <div class="card">
        <h3>Water Access Points</h3>
        <p>Support wells or improved water access points.</p>
      </div>

      <div class="card">
        <h3>Filtration</h3>
        <p>Explore filtration and purification systems to improve water safety.</p>
      </div>

      <div class="card">
        <h3>Local Partnership</h3>
        <p>Work with local leaders and organizations to support lasting solutions.</p>
      </div>

    </div>

  </div>

</section>

<section id="donate" class="donate">

  <div class="container">

    <div class="eyebrow">Donate</div>

    <h2>Every donation helps bring clean water closer.</h2>

    <p>
      Your support can help fund clean water access improvements for families in Ethiopia.
    </p>

    <a class="btn light" href="#">
      GoFundMe Link Coming Soon
    </a>

  </div>

</section>

<footer>
  <strong>
    Clean Water Project Ethiopia Enemor/Gurage Region by Amy Tesfaye
  </strong>

  <p>
    A student-led initiative supporting clean water access for communities in Ethiopia.
  </p>

  <p>Water Is Life.</p>
</footer>

</body>
</html>
