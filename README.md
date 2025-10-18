<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>❚█══█❚FitZone</title>
              <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/7.0.1/css/all.min.css" integrity="sha512-2SwdPD6INVrV/lHTZbO2nodKhrnDdJK9/kg2XD1r9uGqPo1cUbujc+IYdlYdEErWNu69gVcYgdxlmVmzTWnetw==" crossorigin="anonymous" referrerpolicy="no-referrer" />
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/7.0.1/css/all.min.css" />

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
      --bg:#0b0220;
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
      background-image: url(https://images.freeimages.com/images/large-previews/ac2/soft-gradient-background-0410-5713724.jpg?fmt=webp&w=500); background-repeat: no-repeat; background-size: cover;
      
      color:var(--text);
      font-family:Inter, system-ui, -apple-system, Segoe UI, Roboto, Arial, sans-serif;
      line-height:1.6;
    }
    button:hover
    {
      cursor: pointer;
      background-color: rgba(98, 140, 204, 0.1);
      color: #e03065;

    }
    .paraI{
      font-size: 20px;
      text-align: center;
      margin: 0 30px;
      padding: 20px;
    }


    h1{
      color: rgb(255, 255, 255);
      text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.7);
    }
.video1{
  display:flex;
  justify-content: left;
  align-items: center;
  margin: 20px;
  padding: 30px;

}
/* .imgbg{
  background-image: url('https://images.unsplash.com/photo-1554284126-4c2b5f3f0b1e?ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&q=80&w=1470');
  background-size: cover;
  background-position: center;
  padding: 20px;
  border-radius: 10px;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
  margin: 20px;
} */

 /* Cards Layout */
    .card-container {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
      padding: 20px;
      max-width: 1100px;
      margin: 0 auto 40px auto;
    }

    /* Card Styling */
    .price-card {
      background: rgba(227, 186, 218, 0.8);
      border-radius: 15px;
      padding: 25px;
      text-align: center;
      transition: 0.3s;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
    }

    .price-card:hover {
      transform: scale(1.05);
      background: rgba(100, 181, 246, 0.9);
      color: white;
    }

    .price-card h3 {
      margin-bottom: 10px;
      font-size: 20px;
      color: #004d40;
    }

    .price-card p {
      margin: 5px 0;
      font-size: 15px;
      color: #121219;
    }

    .price-card a {
      margin-top: 10px;
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
     <a href="membership.html">Membership</a>
      <a href="login.html">Login</a>
      <a href="join.html"><button style="border-radius: 20px;background-color: rgb(228, 167, 176);">Join now</button></a>
      
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

  
    <div class="imgbg">
  
   <p> <H1 style="color: #0b0220;">This is best time to JOIN US</H1>
     <p style="font-size: 30px; text-align: center;"> <i>'Push Your Limits. Transform Your Life'</i></p>
     <p style="font-size: 20px; text-align: center; color: #36074a;">At FitZone Gym, we believe in empowering individuals to achieve their fitness goals through a combination of expert guidance, state-of-the-art facilities, and a supportive community. Our mission is to provide a welcoming environment where everyone, regardless of their fitness level, can thrive and transform their lives.</p>
   
     <div class="paraI">
      <div class="video1">
        <video src="3195395-uhd_3840_2160_25fps.mp4" width="50%" height="auto" controls>workout</video>
       <p> <b style="color: #0b0220;">What makes FitZone the best gym in India? </b>
         FitZone offers a personalized, accessible, and inclusive place for your workout!
        Offering the opportunity to stay healthy to people from all walks of life, FitZone offers avant-garde equipment and the latest fitness trends to keep you motivated, 
        no matter your level of fitness.
        <a href="knowmore.html"><button style="border-radius: 20px;background-color: rgb(15, 94, 168);">Know More...</button></a>
        
      </p>
        </div>
        <h1 style="padding: 1%;">WHY JOIN OUR CLASSES </h1>
       
        <p style="color: #0b0220;text-align: left;">At FitZone Gym, our certified trainers, modern equipment, and motivating community help you reach your fitness goals faster.
           We offer a variety of workouts — from strength training and cardio to yoga and Zumba — all tailored to your body and lifestyle. 
           With personal guidance, flexible timings, and affordable memberships, we make fitness simple, fun, and effective for everyone.</p>
        <iframe width="814" height="414" src="https://www.youtube.com/embed/tUykoP30Gb0" title="Gym cinematic promotion video" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
     
        <h2 style="color: #121219;text-shadow: #a7adba; margin: 10px;">About Us</h2>
        <div class="card-container">
    <div class="price-card">
      <h3>💪1.Expert Trainers</h3>
      <p><strong>Our certified and experienced trainers guide you with proper techniques, personalized workouts, and motivation to achieve your goals faster and safely</strong></p>
      <a href="Booking.html" class="btn btn-primary">Trainers</a>
    </div>
    <div class="price-card">
      <h3>🕒2.Flexible Timings</h3>
      <p><strong>We offer early morning, evening, and weekend sessions — choose what fits your lifestyle best.</strong></p>
      <a href="Booking.html" class="btn btn-primary">Schedule</a>
    
    </div>
    <div class="price-card">
      <h3>🧘‍♂️3.Variety of Classes</h3>
      <p><strong>From strength training and HIIT to yoga, Zumba, and functional workouts — there’s something for everyone.</strong></p>

      <a href="Booking.html" class="btn btn-primary">Join Classes</a>
    
    </div>
    <div class="price-card">
      <h3>💸4.Affordable Memberships</h3>
      <p><strong>Flexible plans, seasonal discounts, and value-for-money packages for every fitness goal.</strong></p>
      <a href="Booking.html" class="btn btn-primary">Membership</a>
    </div>
        
    
        </div>
        <h1>🧑‍🏫Meet Our Trainers</h1>
        <p style="color: #0b0220;">Our certified trainers are dedicated to helping you achieve your fitness goals with personalized guidance and support. Whether you're a beginner or an experienced athlete, our team is here to motivate and inspire you every step of the way.</p>
      
        



   


<div id="carouselExampleDark" class="carousel carousel-dark slide">
  <div class="carousel-indicators">
    <button type="button" data-bs-target="#carouselExampleDark" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
    <button type="button" data-bs-target="#carouselExampleDark" data-bs-slide-to="1" aria-label="Slide 2"></button>
    <button type="button" data-bs-target="#carouselExampleDark" data-bs-slide-to="2" aria-label="Slide 3"></button>
  </div>
  <div class="carousel-inner">
    <div class="carousel-item active" data-bs-interval="10000">
      <img src="https://media.istockphoto.com/id/2175627902/photo/female-athlete-performing-battle-rope-exercise-in-a-gym-front-view-of-a-woman-doing.webp?a=1&b=1&s=612x612&w=0&k=20&c=_w_6GhJTFHLP2NF-K7bpPj9b_egjxBP85QO2I1LezZg=" class="d-block w-100" alt="...">
      <div class="carousel-caption d-none d-md-block">
        <h5>First slide label</h5>
        <p>Some representative placeholder content for the first slide.</p>
      </div>
    </div>
    <div class="carousel-item" data-bs-interval="2000">
      <img src="..." class="d-block w-100" alt="...">
      <div class="carousel-caption d-none d-md-block">
        <h5>Second slide label</h5>
        <p>Some representative placeholder content for the second slide.</p>
      </div>
    </div>
    <div class="carousel-item">
      <img src="..." class="d-block w-100" alt="...">
      <div class="carousel-caption d-none d-md-block">
        <h5>Third slide label</h5>
        <p>Some representative placeholder content for the third slide.</p>
      </div>
    </div>
  </div>
  <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleDark" data-bs-slide="prev">
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Previous</span>
  </button>
  <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleDark" data-bs-slide="next">
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Next</span>
  </button>
</div>
</div>

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
