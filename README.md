
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Omkar Chavan - Resume</title>

  <!-- Google Fonts -->
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet" />
  
  <!-- AOS Library for Animations -->
  <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet" />

  <style>
    :root {
      --bg-color: #ffffff;
      --text-color: #333;
      --primary-color: #007bff;
      --secondary-color: #f4f4f4;
      --heading-color: #111;
    }

    body.dark-mode {
      --bg-color: #1a1a1a;
      --text-color: #ddd;
      --primary-color: #00bcd4;
      --secondary-color: #2a2a2a;
      --heading-color: #fff;
    }

    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Poppins', sans-serif;
      background: var(--bg-color);
      color: var(--text-color);
      line-height: 1.6;
      scroll-behavior: smooth;
    }

    .navbar {
      background: var(--primary-color);
      color: white;
      padding: 15px 30px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      position: sticky;
      top: 0;
      z-index: 1000;
    }

    .toggle-btn {
      background: none;
      border: 2px solid white;
      color: white;
      padding: 5px 10px;
      border-radius: 5px;
      cursor: pointer;
      font-weight: 600;
      font-size: 0.9rem;
      transition: background-color 0.3s ease, color 0.3s ease;
    }
    .toggle-btn:hover {
      background-color: white;
      color: var(--primary-color);
    }

    .container {
      max-width: 1000px;
      margin: auto;
      padding: 40px 20px;
    }

    header.hero-background {
      background: linear-gradient(rgba(0, 0, 0, 0.6), rgba(0, 0, 0, 0.6)),
                  url('https://images.unsplash.com/photo-1504384308090-c894fdcc538d?ixlib=rb-4.0.3&auto=format&fit=crop&w=1470&q=80') no-repeat center center/cover;
      color: white;
      padding: 120px 20px;
      text-align: center;
      border-radius: 10px;
      margin-bottom: 50px;
      box-shadow: 0 8px 24px rgba(0,0,0,0.3);
    }

    h1, h2 {
      color: var(--heading-color);
    }

    section {
      margin-bottom: 40px;
    }

    .cards {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }

    .card {
      background: var(--secondary-color);
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 8px 20px rgba(0,0,0,0.05);
      transition: transform 0.3s ease;
    }

    .card:hover {
      transform: translateY(-5px);
      box-shadow: 0 12px 28px rgba(0,0,0,0.15);
    }

    ul {
      list-style: none;
      padding-left: 0;
      display: flex;
      flex-wrap: wrap;
      gap: 10px;
    }

    ul li {
      background: var(--secondary-color);
      padding: 8px 12px;
      border-radius: 5px;
      box-shadow: inset 1px 1px 4px rgba(0,0,0,0.05);
      font-weight: 500;
    }

    a {
      color: var(--primary-color);
      text-decoration: none;
    }
    a:hover {
      text-decoration: underline;
    }

    .contact a {
      display: block;
      margin: 5px 0;
      word-break: break-word;
    }

    @media (max-width: 600px) {
      .navbar h1 {
        font-size: 1rem;
      }

      .toggle-btn {
        font-size: 0.8rem;
      }
    }
  </style>
</head>
<body>

  <div class="navbar">
    <h1>Omkar Chavan</h1>
    <button class="toggle-btn" onclick="toggleDarkMode()">🌙 Toggle Mode</button>
  </div>

  <div class="container">

    <header class="hero-background" data-aos="fade-down">
      <h1>Omkar Chavan</h1>
      <p>BCS Student | Developer | Problem Solver</p>
    </header>

    <section class="about" data-aos="fade-up">
      <h2>About Me</h2>
      <p>
        I am a motivated and enthusiastic Bachelor of Computer Science (BCS) student with a strong passion for software development, problem-solving, and innovative technology.
        I enjoy learning new programming languages and frameworks, building web applications, and contributing to open-source projects.
      </p>
    </section>

    <section class="personal-info" data-aos="fade-up">
      <h2>Personal Information</h2>
      <p><strong>Age:</strong> 22</p>
      <p><strong>Date of Birth:</strong> Jun 27, 2003</p>
      <p><strong>Nationality:</strong> Indian</p>
      <p><strong>Address:</strong> AT post old loha Dist: Nanded, Maharashtra, India</p>
    </section>

    <section class="education" data-aos="fade-up">
      <h2>Education</h2>
      <div class="cards">
        <div class="card">
          <h3>BCS - Swami Ramanand Teerth Marathwada University</h3>
          <p>2023 – 2026</p>
          <p><strong>Overall CGPA:</strong> 8.6</p>
          <ul>
            <li>Sem 1: 8.15</li>
            <li>Sem 2: 7.83</li>
            <li>Sem 3: 8.33</li>
            <li>Sem 4: 7.08</li>
          </ul>
        </div>
        <div class="card">
          <h3>12th (HSC)</h3>
          <p><strong>Percentage:</strong> 82.00%</p>
        </div>
        <div class="card">
          <h3>10th (SSC)</h3>
          <p><strong>Percentage:</strong> 69.00%</p>
        </div>
        <div class="card">
          <h3>MS-CIT</h3>
          <p><strong>Percentage:</strong> 79%</p>
        </div>
      </div>
    </section>

    <section class="skills" data-aos="fade-up">
      <h2>Skills</h2>
      <ul>
        <li>C++</li>
        <li>Python</li>
        <li>HTML</li>
        <li>CSS</li>
        <li>Java</li>
      </ul>
    </section>

    <section class="languages" data-aos="fade-up">
      <h2>Languages Known</h2>
      <ul>
        <li>English – Fluent</li>
        <li>Hindi – Fluent</li>
        <li>Marathi – Native</li>
      </ul>
    </section>

    <section class="hobbies" data-aos="fade-up">
      <h2>Hobbies & Interests</h2>
      <ul>
        <li>Coding Challenges</li>
        <li>Creating Web Pages</li>
        <li>Reading Tech Blogs</li>
        <li>Gaming</li>
      </ul>
    </section>

    <section class="projects" data-aos="fade-up">
      <h2>Projects</h2>
      <div class="cards">
        <div class="card">
          <h3>Portfolio Website</h3>
          <p>A personal portfolio to showcase my projects and skills.</p>
          <p><strong>Tech Used:</strong> HTML, CSS, JS, Bootstrap</p>
          <a href="https://omkarpatilchavan0712.github.io/responsiveportfolio1/" target="_blank" rel="noopener noreferrer">View Project</a>
        </div>
        <div class="card">
          <h3>Event Management</h3>
          <p>A class project for managing event registrations and scheduling.</p>
          <p><strong>Tech Used:</strong> HTML, CSS, JavaScript</p>
          <a href="https://omkarpatilchavan0712.github.io/eventmanagment1/" target="_blank" rel="noopener noreferrer">View Project</a>
        </div>
      </div>
    </section>

    <section class="contact" data-aos="fade-up">
      <h2>Contact</h2>
      <p><strong>Email:</strong> <a href="mailto:chavanomiipatil@gmail.com">chavanomiipatil@gmail.com</a></p>
      <p><strong>Mobile Number:</strong> 7385977821</p>
    </section>

  </div>

  <!-- Scripts -->
  <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
  <script>
    AOS.init({
      duration: 1000,
      once: true,
    });

    function toggleDarkMode() {
      document.body.classList.toggle("dark-mode");
    }
  </script>
</body>
</html>


