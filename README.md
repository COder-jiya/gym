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
      background-image: url(https://images.unsplash.com/photo-1710166755608-58b3d62db3a8?ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&q=80&w=1932); background-repeat: no-repeat; background-size: cover;
      
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

    @import url('https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css');

  .trainers-section {
    /* background: linear-gradient(to right, #0a0a0a, #111); */
    padding: 70px 10%;
    text-align: center;
    color: #fff;
  }

  .trainers-section h2 {
    font-size: 2.4rem;
    color: #42a5f5;
    margin-bottom: 10px;
  }

  .trainers-subtext {
    font-size: 1rem;
    color: #bbb;
    margin-bottom: 50px;
  }

  .trainer-container {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 30px;
  }

  .trainer-card {
    background: linear-gradient(145deg, #1a1a1a, #0f0f0f);
    border-radius: 20px;
    width: 250px;
    overflow: hidden;
    transition: 0.3s;
    box-shadow: 0 0 20px rgba(66, 165, 245, 0.3);
  }

  .trainer-card:hover {
    transform: translateY(-10px);
    box-shadow: 0 0 30px rgba(66, 165, 245, 0.6);
  }

  .trainer-card img {
    width: 100%;
    height: 250px;
    object-fit: cover;
  }

  .trainer-info {
    padding: 20px;
  }

  .trainer-info h3 {
    color: #42a5f5;
    margin-bottom: 8px;
  }

  .trainer-info p {
    font-size: 0.95rem;
    color: #bbb;
  }

  .trainer-socials {
    margin-top: 15px;
  }

  .trainer-socials a {
    color: #42a5f5;
    margin: 0 8px;
    font-size: 1.2rem;
    transition: 0.3s;
  }

  .trainer-socials a:hover {
    color: #fff;
    transform: scale(1.2);
  }

  @media (max-width: 768px) {
    .trainer-card {
      width: 90%;
    }
  }
   @import url('https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css');

  .gym-footer {
    background: linear-gradient(to right, #0a0a0a, #111);
    color: #ccc;
    padding: 60px 10% 20px;
    font-family: 'Poppins', sans-serif;
  }

  .footer-container {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
    gap: 40px;
    border-bottom: 1px solid #222;
    padding-bottom: 30px;
  }

  .footer-column {
    flex: 1;
    min-width: 220px;
  }

  .footer-logo {
    color: #42a5f5;
    font-size: 1.8rem;
    margin-bottom: 15px;
  }

  .footer-logo span {
    color: #fff;
  }

  .footer-column h3 {
    color: #42a5f5;
    margin-bottom: 15px;
    font-size: 1.1rem;
  }

  .footer-column p {
    color: #aaa;
    font-size: 0.95rem;
    line-height: 1.6;
  }

  .footer-column ul {
    list-style: none;
    padding: 0;
  }

  .footer-column ul li {
    margin: 8px 0;
  }

  .footer-column ul li a {
    color: #bbb;
    text-decoration: none;
    transition: 0.3s;
  }

  .footer-column ul li a:hover {
    color: #42a5f5;
    text-shadow: 0 0 8px rgba(66, 165, 245, 0.8);
  }

  .footer-socials a {
    color: #42a5f5;
    font-size: 1.2rem;
    margin-right: 15px;
    transition: 0.3s;
  }

  .footer-socials a:hover {
    color: #fff;
    text-shadow: 0 0 10px #42a5f5;
  }

  .footer-bottom {
    text-align: center;
    padding-top: 20px;
    font-size: 0.9rem;
    color: #888;
  }

  .footer-bottom p {
    margin: 0;
  }

  .footer-column i {
    color: #42a5f5;
    margin-right: 8px;
  }

  @media (max-width: 768px) {
    .footer-container {
      flex-direction: column;
      text-align: center;
    }

    .footer-socials a {
      margin: 0 10px;
    }
  }
   

</style>
</head>
<body>
  <!-- Navbar -->
  <nav>
    <a href="Index.html" class="logo">
  <!-- <img src="GYM_logo.jspg.png"height=50px; alt="Fitzone Gym Logo"> -->
   <h3><span style="color: #0a0a0a;">❚█══█❚</span>FitZone</h3>
</a>

    <!-- <div class="logo">Travel Explorer</div> -->
    <div class="menu-btn">☰</div>
    <div class="nav-links">
      <a href="index.html">Home</a>
      <a href="about.html">About us</a>
      <a href="contact.html">Contact</a>
      <a href="classes.html">Classes</a>
      <a href="trainers.html">Trainers Detail</a>
     <a href="membership.html">Membership</a>
      <a href="login.html">Login</a>
      <a href="Join.html"><button style="border-radius: 20px;background-color: rgb(228, 167, 176);">Join now</button></a>
      
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
  
   <p> <H1 style="color: #02074d;">This is best time to JOIN US</H1>
     <p style="font-size: 30px; text-align: center;"> <i>'Push Your Limits. Transform Your Life'</i></p>
     <p style="font-size: 20px; text-align: center; ">At FitZone Gym, we believe in empowering individuals to achieve their fitness goals through a combination of expert guidance, state-of-the-art facilities, and a supportive community. Our mission is to provide a welcoming environment where everyone, regardless of their fitness level, can thrive and transform their lives.</p>
   
     <div class="paraI">
      <div class="video1">
        <video src="3195395-uhd_3840_2160_25fps.mp4" width="50%" height="auto" controls>workout</video>
       <p> <b style="color: #192002;">What makes FitZone the best gym in India? </b>
        <span style="color: white;"> FitZone offers a personalized, accessible, and inclusive place for your workout!
        Offering the opportunity to stay healthy to people from all walks of life, FitZone offers avant-garde equipment and the latest fitness trends to keep you motivated, 
        no matter your level of fitness.</span>
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
    </div>  
        
<!-- ====== TRAINER PROFILE SECTION ====== -->
<section class="trainers-section">
  <h2>Meet Our Expert Trainers</h2>
  <p class="trainers-subtext"> <strong>Certified professionals dedicated to helping you achieve your fitness goals.</strong></p>

  <div class="trainer-container">
    <!-- Trainer 1 -->
    <div class="trainer-card">
      <img src="https://images.unsplash.com/photo-1633008692730-ff6cdbdb7621?ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&q=80&w=688" alt="Trainer 1">
      <div class="trainer-info">
        <h3>John Carter</h3>
        <p>Strength & Conditioning Coach</p>
        <div class="trainer-socials">
          <a href="#"><i class="fab fa-instagram"></i></a>
          <a href="#"><i class="fab fa-facebook"></i></a>
          <a href="#"><i class="fab fa-twitter"></i></a>
          <button style="background-color: rgb(10, 132, 247); border-radius: 20px;">Book</button>
        </div>
      </div>
    </div>

    <!-- Trainer 2 -->
    <div class="trainer-card">
      <img src="https://images.unsplash.com/photo-1605296867304-46d5465a13f1" alt="Trainer 2">
      <div class="trainer-info">
        <h3>Sophia Brown</h3>
        <p>Yoga & Flexibility Expert</p>
        <div class="trainer-socials">
          <a href="#"><i class="fab fa-instagram"></i></a>
          <a href="#"><i class="fab fa-facebook"></i></a>
          <a href="#"><i class="fab fa-twitter"></i></a>
           <button style="background-color: rgb(10, 132, 247); border-radius: 20px;">Book</button>
        </div>
      </div>
    </div>

    <!-- Trainer 3 -->
    <div class="trainer-card">
      <img src="https://images.unsplash.com/photo-1646072507419-9f836f8d3f67?ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxzZWFyY2h8OTV8fGd5bSUyMHRyYWluZXIlMjBwcm9maWxlJTIwcGljY2hlcnxlbnwwfHwwfHx8MA%3D%3D&auto=format&fit=crop&q=60&w=500" alt="Trainer 3">
      <div class="trainer-info">
        <h3>Michael Lee</h3>
        <p>Cardio & Endurance Trainer</p>
        <div class="trainer-socials">
          <a href="#"><i class="fab fa-instagram"></i></a>
          <a href="#"><i class="fab fa-facebook"></i></a>
          <a href="#"><i class="fab fa-twitter"></i></a>
           <button style="background-color: rgb(10, 132, 247); border-radius: 20px;">Book</button>
        </div>
      </div>
    </div>

    <!-- Trainer 4 -->
    <div class="trainer-card">
      <img src="https://plus.unsplash.com/premium_photo-1663099447613-88d6d3ec66a7?ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxzZWFyY2h8ODl8fGd5bSUyMHRyYWluZXIlMjBwcm9maWxlJTIwcGljY2hlcnxlbnwwfHwwfHx8MA%3D%3D&auto=format&fit=crop&q=60&w=500" alt="Trainer 4">
      <div class="trainer-info">
        <h3>Emma Davis</h3>
        <p>Nutrition & Wellness Coach</p>
        <div class="trainer-socials">
          <a href="#"><i class="fab fa-instagram"></i></a>
          <a href="#"><i class="fab fa-facebook"></i></a>
          <a href="#"><i class="fab fa-twitter"></i></a>
           <button style="background-color: rgb(10, 132, 247); border-radius: 20px;">Book</button>
        </div>
      </div>
    </div>

    <!-- Trainer 5 -->
    <div class="trainer-card">
      <img src="https://images.unsplash.com/photo-1700784795176-7ff886439d79?ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&q=80&w=1170" alt="Trainer 5">
      <div class="trainer-info">
        <h3>David Johnson</h3>
        <p>Personal Trainer & Bodybuilding Expert</p>
        <div class="trainer-socials">
          <a href="#"><i class="fab fa-instagram"></i></a>
          <a href="#"><i class="fab fa-facebook"></i></a>
          <a href="#"><i class="fab fa-twitter"></i></a>
           <button style="background-color: rgb(10, 132, 247); border-radius: 20px;">Book</button>
        </div>
      </div>
    </div>
  </div>
</section>





   


<div id="carouselExampleDark" class="carousel carousel-dark slide" data-bs-ride="carousel" style="width: 60%; height: 30%; margin-left: auto; margin-right: auto; padding: 20px;">
  <div class="carousel-indicators">
    <button type="button" data-bs-target="#carouselExampleDark" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
    <button type="button" data-bs-target="#carouselExampleDark" data-bs-slide-to="1" aria-label="Slide 2"></button>
    <button type="button" data-bs-target="#carouselExampleDark" data-bs-slide-to="2" aria-label="Slide 3"></button>
    <button type="button" data-bs-target="#carouselExampleDark" data-bs-slide-to="3" aria-label="Slide 4"></button>
  </div>
  <div class="carousel-inner">
    <div class="carousel-item active" data-bs-interval="1000">
      <img src="https://media.istockphoto.com/id/2175627902/photo/female-athlete-performing-battle-rope-exercise-in-a-gym-front-view-of-a-woman-doing.webp?a=1&b=1&s=612x612&w=0&k=20&c=_w_6GhJTFHLP2NF-K7bpPj9b_egjxBP85QO2I1LezZg=" class="d-block w-100" alt="...">
      <div class="carousel-caption d-none d-md-block">
        <h5></h5>
        <p>first slide.</p>
      </div>
    </div>
    <div class="carousel-item" data-bs-interval="1000">
      <img src="https://plus.unsplash.com/premium_photo-1661284821625-9400498df354?ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxzZWFyY2h8Mjl8fGd5bXxlbnwwfHwwfHx8MA%3D%3D&auto=format&fit=crop&q=60&w=500" class="d-block w-100" alt="...">
      <div class="carousel-caption d-none d-md-block">
        <p>second slide.</p>
      </div>
    </div>
    <div class="carousel-item">
      <img src="https://images.unsplash.com/photo-1542766788-a2f588f447ee?ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&q=80&w=1176" class="d-block w-100" alt="...">
      <div class="carousel-caption d-none d-md-block">
        <p>third slide.</p>
      </div>
    </div>
    <div class="carousel-item">
      <img src="https://plus.unsplash.com/premium_photo-1661604462106-25b406913827?ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxzZWFyY2h8MTY5fHxneW18ZW58MHx8MHx8fDA%3D&auto=format&fit=crop&q=60&w=500" class="d-block w-100" alt="...">
      <div class="carousel-caption d-none d-md-block">
        <p>fourth slide.</p>
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

<!-- ====== FOOTER SECTION ====== -->
<footer class="gym-footer">
  <div class="footer-container">
    <!-- Brand / About -->
    <div class="footer-column">
      <h2 class="footer-logo">FitZone <span>Gym</span></h2>
      <p>Transform your body, mind, and lifestyle with professional fitness programs designed for all levels. Join us and start your journey to a stronger you.</p>
    </div>

    <!-- Quick Links -->
    <div class="footer-column">
      <h3>Quick Links</h3>
      <ul>
        <li><a href="Index.html">Home</a></li>
        <li><a href="about.html">About Us</a></li>
        <li><a href="classes.html">Classes</a></li>
        <li><a href="trainers.html">Trainers</a></li>
        <li><a href="contact.html">Contact</a></li>
      </ul>
    </div>

    <!-- Contact Info -->
    <div class="footer-column">
      <h3>Contact</h3>
      <p><i class="fas fa-map-marker-alt"></i> 123 Fitness Street, Delhi, India</p>
      <p><i class="fas fa-phone"></i> +91 98765 43210</p>
      <p><i class="fas fa-envelope"></i> info@fitzonegym.com</p>
    </div>

    <!-- Social Media -->
    <div class="footer-column">
      <h3>Follow Us</h3>
      <div class="footer-socials">
        <a href="#"><i class="fab fa-facebook-f"></i></a>
        <a href="#"><i class="fab fa-instagram"></i></a>
        <a href="#"><i class="fab fa-twitter"></i></a>
        <a href="#"><i class="fab fa-youtube"></i></a>
      </div>
    </div>
  </div>

  <div class="footer-bottom">
    <p>© 2025 FitZone Gym | Designed with 💙 for Fitness Lovers</p>
  </div>
</footer>





<!-- ====== OPTIONAL JS ANIMATION ====== -->
<script>
  // Fade-in animation when section appears
  const trainerCards = document.querySelectorAll('.trainer-card');

  window.addEventListener('scroll', () => {
    trainerCards.forEach(card => {
      const cardTop = card.getBoundingClientRect().top;
      if (cardTop < window.innerHeight - 100) {
        card.style.opacity = '1';
        card.style.transform = 'translateY(0)';
        card.style.transition = 'all 0.6s ease';
      }
    });
  });
</script>

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
