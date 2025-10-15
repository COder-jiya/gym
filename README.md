<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
        
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.8/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-sRIl4kxILFvY47J16cr9ZwB07vP4J8+LH7qKQnuqkuIAvNWLzeN8tE5YBujZqJLB" crossorigin="anonymous">

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
     body {
    margin: 0;
    font-family: Arial, sans-serif;
  }
  .hero {
    background-image: url('https://images.unsplash.com/photo-1517836357463-d25dfeac3438?ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&q=80&w=1170'); 
    background-size: cover;
    background-position: center;
    height: 100vh; /* full screen */
    display: flex;
    align-items: center;
    justify-content: center;
    color: white;
    text-shadow: 0 2px 10px rgba(0,0,0,0.5);
  }
  .hero h1 {
    font-size: 3rem;
    

  }
  .btnn{
    color: azure;
    
  }

nav:active{
  color: pink;
}

 :root{
      --bg:#0b0b0d;
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

</style>
</head>
<body>
  <!-- Navbar -->
  <nav>
    <a href="Index.html" class="logo">
  <!-- <img src="GYM_logo.jspg.png"height=50px; alt="Fitzone Gym Logo"> -->
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
  
    <!-- <section class="hero">
    <h1> <i>"Push Your Limits. Transform Your Life"</i></h1>
  </section> -->


  <section class="hero">
  <div class="overlay">
    <h1><i>"Transform Your Body. Elevate Your Mind."</i></h1>
    <p>Join <strong>Fitzone Gym</strong> — Where Strength Meets Discipline</p>
    <a href="#membership" class="btnn">Start Free Trial</a>
  </div>
</section>
<br> <br>

  <p>
    <H1><I>'Push Your Limits. Transform Your Life'</I></H1>
    </p>




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
