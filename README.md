<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>FinFuse</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <style>
{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: Arial, sans-serif;
  color: #333;
  line-height: 1.6;
}

.container {
  width: 90%;
  max-width: 1200px;
  margin: auto;
}

/* Header */
.header {
  background-color: #00363a;
  color: #fff;
  padding: 1rem 0;
  display: flex;
  justify-content: space-between;
  align-items: center;
  text-align: right;
}
.navbar {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 20px;
    background-color:  #00363a;
}


.navbar ul {
    list-style: none;
    display: flex;
}

.navbar li {
    margin: 0 15px;
}


.header .logo {
  font-size: 1.5rem;
}

.header .nav ul {
  list-style: none;
  display: flex;
}

.header .nav ul li {
  margin-left: 1rem;
}

.header .nav ul li a {
  color: #fff;
  text-decoration: none;
}

/* Hero Section */
.hero {
  display: flex;
  align-items: center;
  padding: 2rem 0;
  background-color: #e6f7ff;
}

.hero-content {
  flex: 1;
}

.hero-content h2 {
  font-size: 2.5rem;
  color: #00363a;
}

.hero-content p {
  margin: 1rem 0;
}

.cta-button {
  background-color: #00796b;
  color: #fff;
  padding: 0.5rem 1rem;
  border: none;
  cursor: pointer;
}

.hero-image img {
  width: 100%;
  max-width: 400px;
  border-radius: 8px;
}

/* Features Section */
.features {
  background-color: #f2f2f2;
  padding: 2rem 0;
  text-align: center;
}

.feature-box {
  margin: 1rem 0;
}

.feature-box h3 {
  font-size: 2rem;
  color: #00796b;
}

/* Partnerships Section */
.partnerships {
  padding: 2rem 0;
  text-align: center;
}

.social-icons {
  display: flex;
  justify-content: center;
  gap: 1rem;
}

/* Services Section */
.services {
  background-color: #e0f2f1;
  padding: 2rem 0;
}

.services h2 {
  text-align: center;
  margin-bottom: 1rem;
}

.service {
  background: #fff;
  padding: 1rem;
  border-radius: 8px;
  margin-bottom: 1rem;
  display: inline-flex;
}
.serviced {
  background: #fff;
  padding: 1rem;
  border-radius: 8px;
  margin-bottom: 1rem;
  display:inline-flex ;
}


/* Testimonials Section */
.testimonials {
  padding: 2rem 0;
  background-color: #fafafa;
 
}

.testimonial {
  background: #fff;
  padding: 1rem;
  margin: 2rem 0;
  border-radius: 8px;
  display: inline-block;
}
.testimonial1 {
  background: blue;
  padding: 1rem;
  margin: 10px;
  border-radius: 8px;
  display: inline-block;
}

/* FAQ Section */
.faq {
  padding: 2rem 0;
}

.faq-item {
  background: #fff;
  padding: 1rem;
  margin: 1rem 0;
  border-radius: 8px;
}

/* Footer */
.footer {
  background-color: #00363a;
  color: #fff;
  text-align: center;
  padding: 1rem 0;
}
  </style>
  <!-- Header Section -->
  <header class="header">
    <div class="navbar">
      <h1 class="logo">FinFuse</h1>
      <nav>
          <ul>
              <li><a href="#features">Features</a></li>
              <li><a href="#testimonials">Testimonials</a></li>
              <li><a href="#faq">FaQ</a></li>
              <li><a href="#contact">Contact</a></li>
              <li><a href="about.html">About Us</a></li>
          </ul>
      </nav>
      <div class="auth-buttons">
          <a href="login.html" class="btn">Log In</a>
          <button><a href="signup.html" class="btn primary">Sign Up</a></button>
      </div>
  </div>
  

  </header>

  <!-- Hero Section -->
  <section class="hero">
    <div class="container">
      <div class="hero-content">
        <h2>Your Secure And Trusted Financial Partner.</h2>
        <p>Join FinFuse, where technology meets finance for a secure and innovative financial journey.</p>
        <button class="cta-button">Get Started</button>
      </div>
      <div class="hero-image">
        <img src="your-image.png" alt="Financial Partner">
      </div>
    </div>
  </section>

  <!-- Features Section -->
  <section id="features" class="features">
    <div class="container">
      <div class="feature-box">
        <h3>5.65%</h3>
        <p>Highest Annual Yield</p>
      </div>
      <div class="feature-box">
        <h3>920+</h3>
        <p>Trusted Partners</p>
      </div>
      <div class="feature-box">
        <h3>2.23%</h3>
        <p>Lower Service Fee</p>
      </div>
    </div>
  </section>

  <!-- Partnerships Section -->
  <section class="partnerships">
    <div class="container">
      <h2>Joining Forces With Our Diverse Network</h2>
      <div class="social-icons">
        <!-- Add icons here -->
      </div>
    </div>
  </section>

  <!-- Services Section -->
  <section class="services">
    <div class="container">
      <h2>Empowering Your Financial Future</h2>
      <div class="service">
        <h1>Fintech Solutions</h1>
        <p>Providing cutting-edge<br> technology to manage your finances.</p>
      </div>
      <div  class="serviced"><img src="download (1).jfif"></div>
      <div class="service">
        <h3>Empowering Your Financial Journey</h3>
        <p>Helping you achieve financial success through innovative solutions.</p>
      </div>
     
    </div>
  </section>

  <!-- Testimonials Section -->
  <section id="testimonials" class="testimonials">
    <div class="container">
      <h2>Hear What Our Customers Have To Say</h2>
      <div class="testimonial">
        <img src="download (1).jfif" >
        <p>"FinFuse has transformed my<br> financial journey!"</p>
        <h4>Rachel Parker</h4>
      </div>
      <div class="testimonial1">
        <img src="" >
        <p>"FinFuse has transformed my <br> journey!"</p>
        <h4>Rachel Parker</h4>
      </div>
      <div class="testimonial1">
        <img src="" >
        <p>"FinFuse has transformed my<br> financial journey!"</p>
        <h4>Rachel Parker</h4>
      </div>
      <div class="testimonial">
        <img src="download (1).jfif" >
        <p>"FinFuse has transformed my<br> financial journey!"</p>
        <h4>Rachel Parker</h4>
      </div>
      <!-- Add more testimonials here -->
    </div>
  </section>

  <!-- FAQ Section -->
  <section id="faq" class="faq">
    <div class="container">
      <h2>Frequently Asked Questions</h2>
      <div class="faq-item">
        <h3>How can I start with FinFuse?</h3>
        <p>Simply create an account and follow the setup process.</p>
      </div>
      <!-- Add more FAQs here -->
    </div>
  </section>

  <!-- Footer Section -->
  <footer class="footer">
    <div class="container">
      <h2>Let's Join FinFuse, We Protect Your Money</h2>
      <p>Secure your future with innovative financial solutions.</p>
      <p>&copy; 2024 FinFuse. All rights reserved.</p>
    </div>
  </footer>

</body>
</html>
