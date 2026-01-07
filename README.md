# <!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Restoran</title>
  <link rel="stylesheet" href="gg.css">
</head>
<body>
  <header>
    <div class="logo">🍴 Restorant</div>
    <nav>
      <a href="food.html">Home</a>
      <a href="food2.html">About</a>
      <a href="services.html">Service</a>
      <a href="menu.html">Menu</a>
      <a href="chef.html">Pages</a>
      <a href="contact.html">Contact</a>
    </nav>
    <a class="btn6" href="book.html">Book a Table</a>
  </header>

  
  <section class="hero">
    <div class="hero-text">
      <h1>Enjoy Our <br> Delicious Meal !</h1><br>
      <p>Welcome to our resturant.. franch italian all food avilable here
        this is the best restorant inthis area all food avialble of your choice include veg non veg chinese italian
      </p><br><br>
      <a href="book.html" class="btn6">Book a Table</a>
    </div>
    <div class="hero-img">
      
    </div>
  </section>


  <h2>Trending Foods</h2>

  <div class="slider-container">
    <div class="slider" id="slider">
      <div class="slide"><img src="springroll.jpg" alt="Food 1"></div>
      <div class="slide"><img src="jhgj.jpg" alt="Food 2"></div>
      <div class="slide"><img src="dal.jpg" alt="Food 3"></div>
      <div class="slide"><img src="fd.jpg" alt="Food 3"></div>
      <div class="slide"><img src="pratha.jpg" alt="Food 3"></div>
    </div>

    
    <button class="btn prev" onclick="prevSlide()">&#10094;</button>
    <button class="btn next" onclick="nextSlide()">&#10095;</button>
  </div>




  
<section class="services">
  <div class="service-box highlight">
    <i class="icon">👨‍🍳</i>
    <h3>Master Chefs</h3>
    <p>Experienced chief avialabe </p>
  </div>

  <div class="service-box">
    <i class="icon">🍽️</i>
    <h3>Quality Food</h3>
    <p>best quality food with clean vegetables</p>
  </div>

  <div class="service-box">
    <i class="icon">🛒</i>
    <h3>Online Order</h3>
    <p>online booking also avilable dial given no </p>
  </div>

  <div class="service-box">
    <i class="icon">🎧</i>
    <h3>24/7 Service</h3>
    <p>services avilable 24 hours night+day </p>
  </div>
</section>

 
  <button class="scroll-top" onclick="scrollToTop()">↑</button>
  <footer style="background-color: #0f172b; color: white; padding: 50px 20px;">
  <div style="display: flex; flex-wrap: wrap; justify-content: space-between; max-width: 1200px; margin: auto;">
    
    
    <div style="flex: 1 1 200px; margin: 10px;">
      <h3 style="color: #f4a51c;">Company <span style="color: #f4a51c;">—</span></h3><br>   
      <ul style="list-style: none; padding: 0;">
        <li><a href="#" style="color: white; text-decoration: none;">› About Us</a></li><br>
        <li><a href="#" style="color: white; text-decoration: none;">› Contact Us</a></li><br>
        <li><a href="#" style="color: white; text-decoration: none;">› Reservation</a></li><br>
        <li><a href="#" style="color: white; text-decoration: none;">› Privacy Policy</a></li><br>
        <li><a href="#" style="color: white; text-decoration: none;">› Terms & Condition</a></li><br>
      </ul>
    </div>

   
    <div style="flex: 1 1 200px; margin: 10px;">
      <h3 style="color: #f4a51c;">Contact <span style="color: #f4a51c;">—</span></h3><br>
      <p>123 Street, New York, USA</p><br>
      <p>+012 999 869766</p><br>
      <p>info@example.com</p>
      <div style="margin-top: 10px;">
        <a href="#" style="color: white; margin-right: 10px;">🌐</a>
        <a href="#" style="color: white; margin-right: 10px;">📘</a>
        <a href="#" style="color: white; margin-right: 10px;">▶️</a>
        <a href="#" style="color: white;">🔗</a>
      </div>
    </div>

   
    <div style="flex: 1 1 200px; margin: 10px;">
      <h3 style="color: #f4a51c;">Opening <span style="color: #f4a51c;">—</span></h3><br>
      <p>Monday - Saturday<br><br>09AM - 09PM</p>
      <p>Sunday<br><br>10AM - 08PM</p>
    </div>

    
    <div style="flex: 1 1 250px; margin: 10px;">
      <h3 style="color: #f4a51c;">Newsletter <span style="color: #f4a51c;">—</span></h3><br>    
      <p>take news  let reads some information!!</p><br>    
      <form style="display: flex;">
        <input type="email" placeholder="Your email" style="padding: 10px; border: none; border-radius: 5px 0 0 5px; outline: none;">
        <button style="background-color: #f4a51c; border: none; color: white; padding: 10px 15px; border-radius: 0 5px 5px 0; cursor: pointer;">SIGNUP</button>
      </form>
    </div>

  </div>

  <div style="text-align: center; margin-top: 40px; border-top: 1px solid #222; padding-top: 20px;">
    <p style="color: white;">© Your Site Name, All Right Reserved. Designed By Anjali saini</p>
    <div style="margin-top: 10px;">
      <a href="#" style="color: white; margin: 0 10px;">Home</a>
      <a href="#" style="color: white; margin: 0 10px;">Cookies</a>
      <a href="#" style="color: white; margin: 0 10px;">Help</a>
      <a href="#" style="color: white; margin: 0 10px;">FAQs</a>
    </div>
    <div style="position: fixed; bottom: 20px; right: 20px;">
      <a href="#" style="background-color: #f4a51c; padding: 10px; border-radius: 5px; color: white; text-decoration: none;">↑</a>
    </div>
  </div>
</footer>

  <script >
    function scrollToTop() {
  window.scrollTo({
    top: 0,
    behavior: 'smooth'
  });
}

  let currentIndex = 0;
    const slider = document.getElementById("slider");
    const totalSlides = document.querySelectorAll(".slide").length;

    function showSlide(index) {
      if (index >= totalSlides) {
        currentIndex = 0;
      } else if (index < 0) {
        currentIndex = totalSlides - 1;
      } else {
        currentIndex = index;
      }
      slider.style.transform = `translateX(${-currentIndex * 100}%)`;
    }

    function nextSlide() {
      showSlide(currentIndex + 1);
    }

    function prevSlide() {
      showSlide(currentIndex - 1);
    }
  </script>
  </script>
</body>
</html>


Restaurent-website
5 pages html css js project frontend devlopment
