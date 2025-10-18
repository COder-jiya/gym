<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
        <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.8/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-sRIl4kxILFvY47J16cr9ZwB07vP4J8+LH7qKQnuqkuIAvNWLzeN8tE5YBujZqJLB" crossorigin="anonymous">

</head>
<style>
h1{text-align: center;}
   nav {
      width: 100%;
     background: rgba(127, 60, 204, 0.4);
      backdrop-filter: blur(10px);
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 10px 20px;
      position: fixed;
      top: 0;
      left: 0;
      z-index: 1000;
    }

    nav .logo {
      color: white;
      font-size: 22px;
      font-weight: bold;
    }

    .nav-links {
      display: flex;
      gap: 20px;
    }

    .nav-links a {
      color: white;
      text-decoration: none;
      font-weight: 500;
      transition: color 0.3s;
    }

    .nav-links a:hover {
      color: #b3e5fc;
    }

    .menu-btn {
      display: none;
      font-size: 26px;
      color: white;
      cursor: pointer;
    }
    a:active{
       color: rgb(255, 0, 179);
    }

    /* Responsive Navbar for Mobile */
    @media (max-width: 768px) {
      .nav-links {
        display: none;
        flex-direction: column;
        width: 100%;
        background: rgba(128, 128, 128, 0.7);
        text-align: center;
        position: absolute;
        top: 60px;
        left: 0;
        padding: 10px 0;
      }
      .nav-links.show {
        display: flex;
      }
      .menu-btn {
        display: block;
      }
    }
    .hero{
      position:relative; isolation:isolate;
      min-height:52vh; display:grid; place-items:center;
      text-align:center; overflow:hidden;
      background:
        linear-gradient(180deg, rgba(0,0,0,.55), rgba(0,0,0,.65)),
        url('images/about-hero.jpg') center / cover no-repeat;
    }
    .hero h1{
      font-family:Montserrat, sans-serif; font-size:clamp(2rem, 4vw, 3rem);
      margin:6rem 0 .6rem;
    }
    .hero p{ color:var(--muted); margin:0 0 2rem }
    .badges{ display:flex; gap:12px; justify-content:center; flex-wrap:wrap; margin-bottom:3rem }
    .badge{
      border:1px solid rgba(255,255,255,.12); padding:8px 14px; border-radius:999px;
      background:rgba(255,255,255,.04); font-weight:600; color:var(--text);
    }
    @media (max-width: 560px){
         .stats{ grid-template-columns:1fr 1fr }
      .hero{ min-height:46vh }
    }
        /* Simple container */
    .container{ width:min(1100px, 92%); margin-inline:auto }

    :root{
      --bg:#040a69;
      --card:#121219;
      --text:#e8eaee;
      --muted:#a7adba;
      --brand:#00bfff;
      --accent:#1f8fff;
      --success:#42d392;
      --radius:16px;
      --shadow:0 10px 30px rgba(0,0,0,.35);
    }
    * { box-sizing:border-box }
    body{
      margin:0;
      background:var(--bg);
      color:var(--text);
      font-family:Inter, system-ui, -apple-system, Segoe UI, Roboto, Arial, sans-serif;
      line-height:1.6;
    }
    .stats{
      display:grid; grid-template-columns:repeat(4,1fr); gap:16px;
      background:linear-gradient(90deg, rgba(0,191,255,.08), transparent);
      border:1px solid rgba(255,255,255,.06);
      padding:18px; border-radius:var(--radius)
    }
    .stat{ text-align:center }
    .stat .n{ font-family:Montserrat; font-size:1.8rem; font-weight:800; color:var(--brand) }
    .stat .l{ color:var(--muted) }
     @media (max-width: 900px){

      .stats{ grid-template-columns:1fr 1fr }
     }
      .card{
      background:var(--card); border:1px solid rgba(255,255,255,.06);
      border-radius:var(--radius); box-shadow:var(--shadow);
      padding:26px;
    }
    h2{ font-family:Montserrat, sans-serif; font-size:clamp(1.5rem, 2.6vw, 2.1rem); margin:0 0 12px }
    .muted{ color:var(--muted) }

    section{ padding:70px 0 }
    .split{
      display:grid; gap:28px; align-items:center;
      grid-template-columns:1.2fr .8fr;
    }
   
    </style>
<body>
  <nav>
    <a href="Index.html" class="logo">
   <h3>❚█══█❚FitZone</h3>
</a>

    <!-- <div class="logo">Travel Explorer</div> -->
    <div class="menu-btn">☰</div>
    <div class="nav-links">
       
      <a href="index.html">Home</a>
      <a href="about.html">About us</a>
      <a href="contact.html">Contact</a>
      <a href="Class.html">Classes</a>
      <a href="Trainers.html">Trainers Detail</a>
     <a href="join.html">Join now</a>
      
    </div>
  </nav> 

   <!-- Hero -->
  <header class="hero">
    <div class="container">
      <h1>About Fitzone Gym</h1>
      <p>Where discipline meets performance. We build bodies, upgrade minds, and celebrate consistent progress.</p>
      <div class="badges">
        <span class="badge">Since 2019</span>
        <span class="badge">Delhi • NCR</span>
        <span class="badge">Strength • HIIT • Mobility</span>
      </div>
    </div>
  </header>
<section>
  </p>
        <div class="stats" style="margin-top:16px">
          <div class="stat"><div class="n">10,000+</div><div class="l">Sessions Coached</div></div>
          <div class="stat"><div class="n">1,200+</div><div class="l">Members Trained</div></div>
          <div class="stat"><div class="n">85%</div><div class="l">12-Week Completion</div></div>
          <div class="stat"><div class="n">4.8★</div><div class="l">Member Rating</div></div>
        </div>
      </div>
    </p>
  </section>
  
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.8/dist/js/bootstrap.bundle.min.js" integrity="sha384-FKyoEForCGlyvwx9Hj09JcYn3nv7wiPVlz7YYwJrWVcXK/BmnVDxM+D2scQbITxI" crossorigin="anonymous"></script>
<script>
    const menuBtn = document.querySelector('.menu-btn');
    const navLinks = document.querySelector('.nav-links');
    menuBtn.onclick = () => {
      navLinks.classList.toggle('show');
    };
  </script>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.8/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
