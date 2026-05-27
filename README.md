<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />

  <title>Mathew Luv Christe | AI Portfolio</title>

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      scroll-behavior: smooth;
    }

    body {
      background: #050505;
      color: white;
      font-family: Arial, sans-serif;
      line-height: 1.6;
    }

    nav {
      position: fixed;
      width: 100%;
      top: 0;
      background: rgba(0, 0, 0, 0.8);
      backdrop-filter: blur(10px);
      padding: 20px;
      z-index: 1000;
    }

    nav ul {
      display: flex;
      justify-content: center;
      gap: 40px;
      list-style: none;
    }

    nav a {
      color: white;
      text-decoration: none;
      transition: 0.3s;
      font-weight: bold;
    }

    nav a:hover {
      color: cyan;
    }

    .hero {
      min-height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      text-align: center;
      padding: 40px;
      background:
        radial-gradient(circle at top, rgba(0,255,255,0.2), transparent 40%),
        #050505;
    }

    .hero-content {
      max-width: 900px;
    }

    .profile-img {
      width: 180px;
      height: 180px;
      border-radius: 50%;
      object-fit: cover;
      border: 5px solid cyan;
      box-shadow: 0 0 30px cyan;
      margin-bottom: 30px;
    }

    h1 {
      font-size: 70px;
      margin-bottom: 10px;
    }

    .typing {
      color: cyan;
      font-size: 28px;
      margin-bottom: 25px;
    }

    .btn {
      display: inline-block;
      padding: 14px 30px;
      background: cyan;
      color: black;
      text-decoration: none;
      border-radius: 40px;
      font-weight: bold;
      margin: 10px;
      transition: 0.3s;
    }

    .btn:hover {
      transform: scale(1.08);
      box-shadow: 0 0 20px cyan;
    }

    section {
      max-width: 1200px;
      margin: auto;
      padding: 100px 30px;
    }

    .section-title {
      text-align: center;
      font-size: 45px;
      margin-bottom: 50px;
      color: cyan;
    }

    .card {
      background: #111;
      border-radius: 25px;
      padding: 40px;
      margin-top: 20px;
      transition: 0.3s;
      border: 1px solid #222;
    }

    .card:hover {
      transform: translateY(-10px);
      box-shadow: 0 0 20px rgba(0,255,255,0.3);
    }

    .skills {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
      justify-content: center;
    }

    .skill {
      background: cyan;
      color: black;
      padding: 12px 25px;
      border-radius: 30px;
      font-weight: bold;
    }

    .projects {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(300px,1fr));
      gap: 30px;
    }

    .project-card {
      background: #111;
      padding: 30px;
      border-radius: 25px;
      transition: 0.3s;
      border: 1px solid #222;
    }

    .project-card:hover {
      transform: translateY(-10px);
      box-shadow: 0 0 20px rgba(0,255,255,0.4);
    }

    .project-card h3 {
      margin-bottom: 15px;
      color: cyan;
    }

    footer {
      text-align: center;
      padding: 40px;
      color: #777;
    }

    @media(max-width:768px) {
      h1 {
        font-size: 45px;
      }

      .typing {
        font-size: 20px;
      }

      nav ul {
        gap: 20px;
      }
    }
  </style>
</head>

<body>

  <nav>
    <ul>
      <li><a href="#about">About</a></li>
      <li><a href="#skills">Skills</a></li>
      <li><a href="#projects">Projects</a></li>
      <li><a href="#research">Research</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
  </nav>

  <div class="hero">

    <div class="hero-content">

      <!-- GANTI FOTO -->
      <img src="yourphoto.jpg" class="profile-img">

      <h1>Mathew Luv Christe</h1>

      <div class="typing">
        Artificial Intelligence Student
      </div>

      <p>
        Nanjing University of Information Science and Technology
      </p>

      <br>

      <a href="https://github.com" class="btn">
        GitHub
      </a>

      <a href="#contact" class="btn">
        Contact Me
      </a>

    </div>

  </div>

  <section id="about">

    <h2 class="section-title">About Me</h2>

    <div class="card">

      <p>
        I am Mathew Luv Christe, an Artificial Intelligence student at
        Nanjing University of Information Science and Technology.
        I was born on May 26, 2006 and come from Indonesia.
      </p>

      <br>

      <p>
        I am passionate about artificial intelligence,
        computer vision, machine learning, embedded systems,
        and interactive technology development.
      </p>

      <br>

      <p>
        I am also a recipient of the Excellent Scholarship
        with 100% full scholarship coverage.
      </p>

    </div>

  </section>

  <section id="skills">

    <h2 class="section-title">Languages & Skills</h2>

    <div class="card">

      <h3>Languages</h3>

      <br>

      <div class="skills">
        <div class="skill">Indonesian — Native</div>
        <div class="skill">English — Intermediate</div>
        <div class="skill">Chinese — Intermediate</div>
      </div>

      <br><br>

      <h3>Technical Skills</h3>

      <br>

      <div class="skills">
        <div class="skill">Python</div>
        <div class="skill">Machine Learning</div>
        <div class="skill">Computer Vision</div>
        <div class="skill">Arduino</div>
        <div class="skill">C++</div>
        <div class="skill">AI Development</div>
        <div class="skill">Hand Gesture Recognition</div>
        <div class="skill">Game Development</div>
        <div class="skill">HTML & CSS</div>
      </div>

    </div>

  </section>

  <section id="projects">

    <h2 class="section-title">Projects</h2>

    <div class="projects">

      <div class="project-card">
        <h3>Hand Gesture Recognition</h3>

        <p>
          AI-based computer vision system capable of detecting
          and classifying hand gestures in real-time using webcam input.
        </p>
      </div>

      <div class="project-card">
        <h3>AI Boxing Detection Game</h3>

        <p>
          Interactive boxing game using body tracking and
          motion detection technology powered by AI.
        </p>
      </div>

      <div class="project-card">
        <h3>Body Detection System</h3>

        <p>
          Human body detection system designed for interactive
          gaming and motion analysis applications.
        </p>
      </div>

      <div class="project-card">
        <h3>Machine Learning Applications</h3>

        <p>
          Development of AI and machine learning solutions
          for image recognition and smart systems.
        </p>
      </div>

    </div>

  </section>

  <section id="research">

    <h2 class="section-title">Research Topic</h2>

    <div class="card">

      <h3>DE Water Research Website</h3>

      <br>

      <p>
        Research and development website focused on water-related
        environmental technology and intelligent monitoring systems.
      </p>

    </div>

  </section>

  <section id="contact">

    <h2 class="section-title">Contact</h2>

    <div class="card">

      <p>Email : yourmail@gmail.com</p>

      <br>

      <p>GitHub : github.com/yourusername</p>

      <br>

      <p>LinkedIn : linkedin.com/in/yourname</p>

    </div>

  </section>

  <footer>
    © 2026 Mathew Luv Christe | AI Portfolio
  </footer>

</body>

</html>
