<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Lucas Barrett Photography</title>

<link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@300;600&display=swap" rel="stylesheet">

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Montserrat', sans-serif;
}

body {
  background: #0a0a0a;
  color: #fff;
  scroll-behavior: smooth;
}

/* NAV */
nav {
  position: fixed;
  width: 100%;
  padding: 20px 50px;
  display: flex;
  justify-content: space-between;
  background: rgba(0,0,0,0.7);
  backdrop-filter: blur(10px);
  z-index: 1000;
}

nav a {
  color: white;
  text-decoration: none;
  margin-left: 25px;
  font-weight: 300;
}

/* HERO */
.hero {
  height: 100vh;
  background: url('hero.jpg') center/cover no-repeat;
  display: flex;
  align-items: center;
  justify-content: center;
  text-align: center;
}

.hero h1 {
  font-size: 3.5rem;
  letter-spacing: 3px;
  background: rgba(0,0,0,0.5);
  padding: 20px 40px;
}

/* GALLERY */
.gallery {
  column-count: 3;
  column-gap: 12px;
  padding: 80px 40px;
}

.gallery img {
  width: 100%;
  margin-bottom: 12px;
  border-radius: 6px;
  transition: 0.3s;
}

.gallery img:hover {
  transform: scale(1.02);
}

/* ABOUT */
.about {
  padding: 80px 40px;
  text-align: center;
  background: #111;
}

.about p {
  max-width: 700px;
  margin: auto;
  line-height: 1.6;
}

/* CONTACT */
.contact {
  padding: 80px 40px;
  text-align: center;
}

.socials a {
  margin: 0 10px;
  color: white;
  font-size: 1.2rem;
  text-decoration: none;
}

/* FOOTER */
footer {
  padding: 20px;
  text-align: center;
  background: black;
  font-size: 0.8rem;
}

/* MOBILE */
@media(max-width: 900px) {
  .gallery {
    column-count: 2;
  }
}

@media(max-width: 600px) {
  .gallery {
    column-count: 1;
  }

  .hero h1 {
    font-size: 2rem;
  }
}
</style>
</head>

<body>

<nav>
  <h2>LB Photography</h2>
  <div>
    <a href="#gallery">Gallery</a>
    <a href="#about">About</a>
    <a href="#contact">Contact</a>
  </div>
</nav>

<section class="hero">
  <h1>Lucas Barrett Photography</h1>
</section>

<section id="gallery" class="gallery">
  <img src="photo1.jpg">
  <img src="photo2.jpg">
  <img src="photo3.jpg">
  <img src="photo4.jpg">
  <img src="photo5.jpg">
  <img src="photo6.jpg">
</section>

<section id="about" class="about">
  <h2>About Me</h2>
  <p>
    I’m a New Zealand photographer specialising in automotive and landscape
    photography, capturing moments, machines, and scenery with a cinematic style.
  </p>
</section>

<section id="contact" class="contact">
  <h2>Contact</h2>
  <p>Email: your@email.com</p>

  <div class="socials">
    <a href="#">Instagram</a>
    <a href="#">Facebook</a>
    <a href="#">TikTok</a>
  </div>
</section>

<footer>
  © 2026 Lucas Barrett Photography
</footer>

</body>
</html>
