<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Your Business Name</title>
  <link rel="stylesheet" href="style.css">

</head>
<!--form of this website-->
<body>
  <header></header>
    <div class="container">
      <h1><span  style="color: RED;">A</span>&nbsp;&nbsp;
        <span style="color: blueviolet;">Y</span>&nbsp;
          <span style="color: gold;">A</span>&nbsp;&nbsp;&nbsp;
          <span style="color: dimgrey;">L</span> &nbsp;&nbsp;
          <span style="color: lawngreen;">S</span>&nbsp;&nbsp;
          <span style="color: yellow;">E</span>&nbsp;&nbsp;&nbsp;
          <span style="color: violet;">W</span>&nbsp;&nbsp;&nbsp;
          <span style="color: darkred;">B</span>&nbsp;&nbsp;&nbsp;
          <span style="color: darkorchid;">U </span>&nbsp;&nbsp;
          <span style="color: darkmagenta;">S</span>&nbsp;&nbsp;
          <span style="color: darkkhaki;">I</span>&nbsp;&nbsp;
            <span style="color: lightseagreen;">E</span>&nbsp;&nbsp;
            <span style="color: springgreen;">S</span>&nbsp;
            <span style="color: indianred;">S</span></h1>
            <h1 style="text-align: center;"> &nbsp;&nbsp;&nbsp;
            <span style="color: #007bff;">C</span><span style="color: blue;">E</span>
            <span style="color: deeppink;">N</span>
            <span style="color: darkturquoise;">T</span><span style="color: red;">E</span>
            <span style="color: blueviolet;">R</span></h1>
      <nav>
        <ul>
          <li><a href="#home">Home</a></li>&nbsp;&nbsp;&nbsp;
          <li><a href="#about">About</a></li>&nbsp;&nbsp;&nbsp;
          <li><a href="#services">Services</a></li>&nbsp;&nbsp;&nbsp;
          <li><a href="#contact">Contact</a></li>&nbsp;&nbsp;&nbsp;
        </ul>
      </nav>
    </div>
  </header>
  <section>
<div>
<UL>
<link  href="#" type="background">
<link    href="#" type="displayM ">
<link href="#" type="button">
</UL>
</div>
  </section>
<!--section one /part 1-->
  <section id="home" class="hero" >
    <div class="container"   >
      <h2>Welcome to My  Business Website  Gage</h2>
      <p>We help you grow with confidence.</p>
      <a href="#contact" class="btn">Get in Touch</a>
    </div>
  </section>
<!---section  two / part 2-->
  <section id="about">
    <div class="container">
      <h2>About Us</h2>
      <p>We are a dedicated team providing top-notch services to help businesses thrive.</p>
      <ol type="A">
        <h1><U><A href="#">Get Information About Here</A></U></h1>
<li>this is best ioportinouty of  the education </li>
<li>command of can be respect  </li>
<li> education is the best chance of any level of peoples</li>
<li>finally every one can manage of her self/him self</li>

      </ol>
    </div>
  </section>
<!--section three /part 3-->
  <section id="services">
    <div class="container">
      <h2>Our Services</h2>
      <ul class="services-list">
<li>goal of save </li>
<li>physical fittness</li>
<li>play ball</li>
<li>log out</li>
        <li>Consulting</li>
        <li>Marketing Strategy</li>
        <li>Web Development</li>
      </ul>
    </div>
  </section>
<!--section four /part 4-->
  <section id="contact">
    <div class="container">
      <h2>Contact Us</h2>
      <form id="contact-form">
        <input type="text" placeholder="Your Name" required />
        <input type="email" placeholder="Your Email" required />
        <textarea placeholder="Your Message" required></textarea>
        <button type="submit">Send</button>
      </form>
    </div>
  </section>
  <!--next  style -->
<style>* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  color: white;
 
}

body {
  background-image: url('https://images.pexels.com/photos/8938679/pexels-photo-8938679.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=2');
  font-family: 'Segoe UI', sans-serif;
  line-height: 1.6;
  color: #fff;
}

h1 {
  color: greenyellow;
  text-align: center;
}

h1 u a {
  color: blueviolet;
  text-decoration: underline;
}

.container {
  width: 80%;
  max-width: 1100px;
  margin: auto;
  padding: 15px;
}

header {
  background: #333;
  color: #fff;
  padding: 20px 0;
}

nav {
  float: right;
}

nav ul {
  list-style: none;
  display: flex;
  gap: 15px;
}

nav ul li a {
  text-underline-position: below;
  color:magenta;
  padding-left: ;
 text-align: right;
  text-decoration:lawngreen;
  font-weight: bold;
}

section {
  background-color: red;
  padding: 60px 0;
}

.hero {
  background-image: url('https://images.pexels.com/photos/8938679/pexels-photo-8938679.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=2');
  color: white;
  width: 100%;
  padding: 60px 0;
  height: 654px;
  text-align: center;
}

.hero h2 {
  font-size: 2.5rem;
  background-color: black;
}

.btn {
  background: #ffffff;
  color: #007bff;
  padding: 10px 20px;
  text-decoration: none;
  display: inline-block;
  margin-top: 20px;
  border-radius: 5px;
}

.services-list {
  list-style: none;
  display: flex;
  flex-wrap: wrap;
  gap: 20px;
}

.services-list li {
  background: #f4f4f4;
  color: #000;
  padding: 20px;
  flex: 1;
  text-align: center;
  border-radius: 5px;
}

form input,
form textarea {
  display: block;
  width: 100%;
  margin-bottom: 20px;
  padding: 10px;
  border: none;
  border-radius: 4px;
}

form button {
  padding: 10px 20px;
  background: #007bff;
  color: #fff;
  border: none;
  cursor: pointer;
  border-radius: 4px;
}

input:hover,
textarea:hover {
  background-color: black;
  color: white;
}

footer {
  background: #222;
  color: #fff;
  text-align: center;
  padding: 20px 0;
}
</style>
  <footer>
    <div class="container">
      <p>&copy; 2025 Your Business. All rights reserved.</p>
    </div>
  </footer>

  
</body>
</html>
