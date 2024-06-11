<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Vivek Bhurke</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
  <style>
    body {
      font-family: 'Arial', sans-serif;
      background-color: #f4f4f9;
      color: #333;
      margin: 0;
      padding: 0;
      overflow-x: hidden;
    }
    hr {
      border: none;
      height: 1px;
      background-color: #e0e0e0;
      margin: 40px 0;
    }
    h1, h3 {
      color: #333;
      animation: fadeInDown 1s ease-in-out;
    }
    h1 {
      font-size: 2.5em;
      margin-bottom: 0;
    }
    h3 {
      font-size: 1.5em;
    }
    p {
      font-size: 1.1em;
      line-height: 1.6em;
      margin: 20px 0;
      animation: fadeInUp 1s ease-in-out;
    }
    a {
      color: #0077b5;
      text-decoration: none;
    }
    a:hover {
      text-decoration: underline;
    }
    .center {
      text-align: center;
    }
    .img-container {
      margin: 20px 0;
      animation: zoomIn 1s ease-in-out;
    }
    .badge {
      margin: 10px 5px;
      animation: fadeInUp 1s ease-in-out;
    }
    .stats {
      display: flex;
      justify-content: center;
      align-items: center;
      flex-wrap: wrap;
    }
    .stats img {
      margin: 10px;
    }
    @keyframes fadeInDown {
      from {
        opacity: 0;
        transform: translateY(-20px);
      }
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }
    @keyframes fadeInUp {
      from {
        opacity: 0;
        transform: translateY(20px);
      }
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }
    @keyframes zoomIn {
      from {
        opacity: 0;
        transform: scale(0.5);
      }
      to {
        opacity: 1;
        transform: scale(1);
      }
    }
    .carousel {
      display: flex;
      overflow: hidden;
      max-width: 80%;
      margin: auto;
      position: relative;
    }
    .carousel img {
      width: 100%;
      transition: transform 0.5s ease-in-out;
    }
    .carousel-buttons {
      position: absolute;
      top: 50%;
      width: 100%;
      display: flex;
      justify-content: space-between;
      transform: translateY(-50%);
    }
    .carousel-buttons button {
      background-color: rgba(0,0,0,0.5);
      border: none;
      color: white;
      padding: 10px;
      cursor: pointer;
    }
  </style>
</head>
<body>

<hr>
<p class="center">
  <img src="https://user-images.githubusercontent.com/67046306/213246080-9240fb6d-95ab-44a6-ac9e-67fd5d277812.gif" alt="hitman" />
</p>

<hr>
<h1 class="center">Hi there! <img src="https://media.tenor.com/nebZyl8oN7IAAAAj/wave-hello.gif" alt="wave" width="30" height="30" />, I'm Vivek Bhurke</h1>
<h3 class="center">A passionate Photographer 📸 and Computer Science Student 💻</h3>

<p class="center img-container">
  <img src="https://media.giphy.com/media/l0HlRmPUe4jpJoqDe/giphy.gif" alt="camera" width="300" height="200" />
</p>

<hr>
<h3 class="center">About Me</h3>
<p class="center">
  I'm a creative soul who loves capturing moments and turning them into art. My passion for photography drives me to explore new techniques and continuously improve my skills. Besides photography, I'm a computer science student who loves diving into new technologies and programming languages.
</p>

<hr>
<h3 class="center">📚 What I'm Currently Learning</h3>
<p class="center">
  🌱 Currently diving into <strong>Java</strong> to expand my technical skillset and explore the world of programming.
</p>

<hr>
<h3 class="center">📫 How to Reach Me</h3>
<p class="center">
  Feel free to reach out via email at: <a href="mailto:vivekbhurke863@gmail.com"><strong>vivekbhurke863@gmail.com</strong></a>
</p>

<hr>
<h3 class="center">🌐 Connect With Me</h3>
<p class="center">
  <a href="https://www.instagram.com/vivek__bhurke/" target="_blank"><i class="fab fa-instagram fa-2x badge"></i></a>
  <a href="https://www.linkedin.com/in/vivek-bhurke/" target="_blank"><i class="fab fa-linkedin fa-2x badge"></i></a>
  <a href="https://twitter.com/yourprofile" target="_blank"><i class="fab fa-twitter fa-2x badge"></i></a>
  <a href="https://leetcode.com/u/vivek_bhurke/" target="_blank"><i class="fas fa-code fa-2x badge"></i></a>
  <a href="https://www.facebook.com/vivek.bhurke.58" target="_blank"><i class="fab fa-facebook fa-2x badge"></i></a>
  <a href="https://github.com/VivekBhurke" target="_blank"><i class="fab fa-github fa-2x badge"></i></a>
</p>

<hr>
<h3 class="center">🎨 My Photography Portfolio</h3>
<p class="center">
  <a href="https://yourphotographyportfolio.com" target="_blank"><i class="fas fa-camera-retro fa-2x badge"></i></a>
</p>

<hr>
<h3 class="center">⚙️ Tools & Technologies</h3>
<p class="center">
  <i class="fab fa-java fa-2x badge" style="color: #007396;"></i>
  <i class="fab fa-python fa-2x badge" style="color: #3776AB;"></i>
  <i class="fab fa-html5 fa-2x badge" style="color: #E34F26;"></i>
  <i class="fab fa-css3 fa-2x badge" style="color: #1572B6;"></i>
  <i class="fab fa-js fa-2x badge" style="color: #F7DF1E;"></i>
  <i class="fab fa-adobe fa-2x badge" style="color: #FF0000;"></i>
</p>

<hr>
<h3 class="center">📊 GitHub Stats</h3>
<div class="stats">
  <img src="https://github-readme-stats.vercel.app/api?username=VivekBhurke&show_icons=true&theme=radical" alt="GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=VivekBhurke&layout=compact&theme=radical" alt="Top Languages" />
</div>

<hr>
<h3 class="center">💡 LeetCode Profile</h3>
<p class="center">
  <a href="https://leetcode.com/u/vivek_bhurke/" target="_blank"><i class="fas fa-code fa-2x badge"></i></a>
</p>

<hr>
<h3 class="center">🎬 Latest YouTube Videos</h3>
<p class="center">
  <a href="https://www.youtube.com/watch?v=videoid1" target="_blank"><i class="fab fa-youtube fa-2x badge" style="color: #FF0000;"></i></a>
  <a href="https://www.youtube.com/watch?v=videoid2" target="_blank"><i class="fab fa-youtube fa-2x badge" style="color: #FF0000;"></i></a>
</p>

<hr>
<h3 class="center">🎉 Fun Fact</h3>
<p class="center">
  Did you know? The world's oldest known photograph was taken by Joseph Nicéphore Niépce in 1826, and it took 8 hours to expose!
</p>

<hr>

<h3 class="center">📸 My Photographs</h3>
<div class="carousel">
  <img src="https://via.placeholder.com/800x400?text=Photo+1" alt="Photo 1">
  <img src="https://via.placeholder.com/800x400?text=Photo+2" alt="Photo 2">
  <img src="https://via.placeholder.com/800x400?text=Photo+3" alt="Photo 3">
  <img src="https://via.placeholder.com/800x400?text=Photo+4" alt="Photo 4">
</div>
<div class="carousel-buttons">
  <button onclick="prevSlide()">&#10094;</button>
  <button onclick="nextSlide()">&#10095;</button>
</div>

<script>
  let currentSlide = 0;
  const slides = document.querySelectorAll('.carousel img');

  function showSlide(index) {
    slides.forEach((slide, i) => {
      slide.style.transform = `translateX(${100 * (i - index)}%)`;
    });
  }

  function nextSlide() {
    currentSlide = (currentSlide + 1) % slides.length;
    showSlide(currentSlide);
  }

  function prevSlide() {
    currentSlide = (currentSlide - 1 + slides.length) % slides.length;
    showSlide(currentSlide);
  }

  showSlide(currentSlide);
</script>

</body>
</html>
