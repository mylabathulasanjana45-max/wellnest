<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>WELLNEST: Student Mental Health Support</title>
  <!-- Link CSS -->
  <link rel="stylesheet" href="style.css">
  <style>
    header {
      position: relative;
      padding: 20px;
      background: #2c3e50;
      text-align: center;
    }

    /* Logo placed between top-left and title */
    .logo {
      position: absolute;
      top: 20px;
      left: 120px; /* adjust this to move logo horizontally */
    }
    .logo img {
      height: 140px; /* increased size */
      width: auto;
    }

    header h1 {
      font-size: 3em;
      margin: 0;
      color: #f2f7fc;
    }
    header p {
      font-size: 1.2em;
      color: #fdf7f7;
      margin-top: 10px;
    }
    nav {
      margin-top: 15px;
    }
    nav a {
      margin: 0 10px;
      text-decoration: none;
      color: #0066cc;
      font-weight: bold;
    }
    nav a:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body>
  <header>
    <div class="logo">
      <img src="https://copilot.microsoft.com/th/id/BCO.494f0e47-c157-4b58-b01a-c8da0d3bc437.png" alt="Wellnest Logo">
    </div>
    <h1>WELLNEST</h1>
    <p>Psychological & Emotional Support System for Higher Education Students</p>
    <nav>
      <a href="#about">About</a>
      <a href="#features">Features</a>
      <a href="#resources">Resources</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>
</body>
</html>


  <section id="about">
    <h2>About the System</h2>
    <p>
      Wellnest is a digital platform designed to provide mental health and psychological 
      support for students in higher education. It includes motivational resources, stress relief 
      activities, yoga asanas, and direct access to counseling.
    </p>
  </section>
  <section id="features">
    <h2>Features</h2>

    <!-- Motivational Content -->
    <div class="feature">
      <h3>Motivational Content</h3>
      <p>Daily motivational quotes, images, and videos to inspire positivity and resilience.</p>
      <div class="links">
        <a href="https://www.youtube.com/watch?v=ESpZfmgUJFE" target="_blank">🎥 Power of Positivity (YouTube)</a>
        <a href="https://www.youtube.com/watch?v=BbEVumEOwoE" target="_blank">🎥 Stay Motivated Everyday (YouTube)</a>
        <a href="https://www.youtube.com/watch?v=4Si-XH-fh40" target="_blank">🎥 Student Motivation (YouTube)</a>
        <a href="https://images.meesho.com/images/products/263171045/dhx3z_512.webp" target="_blank">🖼️ Motivational Poster</a>
        <a href="https://www.avinashchandra.com/wp-content/uploads/2019/12/motivational-quotes-for-students-by-famous-people-1024x766.jpg" target="_blank">🖼️ Student Quotes</a>
      </div>
    </div>

    <!-- Stress Relief Games -->
    <div class="feature">
      <h3>Stress Relief Games</h3>
      <p>Interactive and fun activities designed to reduce stress and anxiety.</p>
      <div class="links">
        <a href="https://www.youtube.com/watch?v=BbEVumEOwoE" target="_blank">🎥 Relaxation Music Video (YouTube)</a>
      </div>
    </div>

    <!-- Yoga & Relaxation -->
    <div class="feature">
      <h3>Yoga & Relaxation</h3>
      <p>Guided yoga asanas and breathing exercises for mind relaxation.</p>
      <a href="https://thumbs.dreamstime.com/b/inspirational-motivational-quote-relax-do-not-rush-force-stress-trust-process-background-sunflower-bloom-field-166464660.jpg" target="_blank">Stress Relief</a>
      <div class="links">
        <a href="https://ncert.nic.in/pdf/publication/otherpublications/tiyhwlups1.pdf" target="_blank">📘 NCERT Yoga Asanas Guide (PDF)</a>
        <a href="http://www.vizagsteel.com/sports/HealthFitness_YOGA_Manual.pdf" target="_blank">📘 Vizag Steel Yoga Manual (PDF)</a>
      </div>
    </div>

    <!-- Counseling Access -->
    <div class="feature">
      <h3>Counseling Access</h3>
      <p>Book appointments and connect with trained mental health professionals.</p>
        <a href="#">📅 Campus Counseling Timetable</a>
      </div>
    </div>
  </section>

  <section id="resources">
    <h2>Resources</h2>
    <ul>
      <li><a href="https://www.youtube.com/watch?v=ESpZfmgUJFE" target="_blank">🎧 Guided Meditation (YouTube)</a></li>
      <li><a href="#">📄 Tips for Managing Exam Stress</a></li>
      <li><a href="#">📅 Campus Counseling Timetable</a></li>
    </ul>
  </section>

  <section id="contact">
    <h2>Contact & Support</h2>
    <p>If you need help, please reach out:</p>
    <form id="contactForm">
      <input type="text" placeholder="Your Name (optional)">
      <input type="email" placeholder="Your Email (optional)">
      <textarea placeholder="Your Message" rows="4"></textarea>
      <button type="submit">Send</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2025 Wellnest - Supporting Student Mental Well-being</p>
  </footer>

  <!-- Link JS -->
  <script src="script.js"></script>
</body>
</html>

