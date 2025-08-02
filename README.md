<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Portfolio - Keng </title>
  <style>
    :root {
      --clr-bg: #f5f7fa;
      --clr-primary: #0066ff;
      --clr-primary-dark: #0047b3;
      --clr-text: #222;
    }
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
    }
    body {
      background: var(--clr-bg);
      color: var(--clr-text);
      line-height: 1.6;
    }
    header {
      background: var(--clr-primary);
      color: #fff;
      padding: 60px 20px;
      text-align: center;
    }
    header h1 {
      font-size: 2.5rem;
      margin-bottom: 0.5rem;
    }
    header p {
      font-size: 1.2rem;
      opacity: 0.8;
    }
    nav {
      background: #fff;
      box-shadow: 0 2px 8px rgba(0, 0, 0, 0.05);
      position: sticky;
      top: 0;
      z-index: 10;
    }
    nav ul {
      display: flex;
      justify-content: center;
      list-style: none;
    }
    nav ul li {
      margin: 0 15px;
    }
    nav ul li a {
      display: block;
      padding: 15px 0;
      color: var(--clr-primary);
      text-decoration: none;
      font-weight: 600;
      transition: color .3s;
    }
    nav ul li a:hover {
      color: var(--clr-primary-dark);
    }
    section {
      max-width: 900px;
      margin: 60px auto;
      padding: 0 20px;
    }
    section h2 {
      font-size: 2rem;
      margin-bottom: 20px;
      color: var(--clr-primary-dark);
    }
    .projects {
      display: grid;
      gap: 25px;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    }
    .card {
      background: #fff;
      border-radius: 8px;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.08);
      overflow: hidden;
      transition: transform .3s;
    }
    .card:hover {
      transform: translateY(-5px);
    }
    .card img {
      width: 100%;
      height: 160px;
      object-fit: cover;
    }
    .card-body {
      padding: 15px 20px 20px;
    }
    .card-body h3 {
      margin-bottom: 8px;
    }
    .card-body a {
      color: var(--clr-primary);
      text-decoration: none;
      font-weight: 600;
    }
    .skills {
      display: flex;
      flex-wrap: wrap;
      gap: 10px;
    }
    .skills span {
      background: #e0e7ff;
      color: var(--clr-primary-dark);
      padding: 6px 14px;
      border-radius: 20px;
      font-size: 0.9rem;
    }
    footer {
      background: var(--clr-primary-dark);
      color: #fff;
      text-align: center;
      padding: 25px 20px;
      font-size: 0.9rem;
    }
    footer .social {
      margin-top: 10px;
    }
    footer .social a {
      color: #fff;
      margin: 0 8px;
      font-size: 1.2rem;
      text-decoration: none;
    }
    @media (max-width: 600px) {
      header h1 { font-size: 2rem; }
      nav ul { flex-direction: column; padding: 5px 0; }
      nav ul li { margin: 0; }
    }
  </style>
</head>
<body>

  <header>
    <h1>Halo, saya <span id="Keng">Keng</span></h1>
    <p>Junior Full-Stack Developer & UI Enthusiast</p>
  </header>

  <nav>
    <ul>
      <li><a href="#about">Tentang</a></li>
      <li><a href="#projects">Projek</a></li>
      <li><a href="#skills">Skill</a></li>
      <li><a href="#contact">Kontak</a></li>
    </ul>
  </nav>

  <section id="about">
    <h2>Tentang Saya</h2>
    <p>
      Saya adalah lulusan Teknik Informatika yang senang membangun produk digital.
      Saat ini fokus pada React, Node.js, dan desain sistem yang scalable.
    </p>
  </section>

  <section id="projects">
    <h2>Projek Unggulan</h2>
    <div class="projects">
      <div class="card">
        <img src="https://images.unsplash.com/photo-1551650975-87deedd944c3?auto=format&fit=crop&w=600&q=60" alt="E-commerce">
        <div class="card-body">
          <h3>E-commerce Mini</h3>
          <p>Toko online sederhana dengan Stripe & Next.js.</p>
          <a href="https://github.com/username/shop-mini" target="_blank">Lihat di GitHub →</a>
        </div>
      </div>

      <div class="card">
        <img src="https://images.unsplash.com/photo-1586953208448-b95a79798f07?auto=format&fit=crop&w=600&q=60" alt="Weather App">
        <div class="card-body">
          <h3>Weather App</h3>
          <p>Prakiraan cuaca real-time menggunakan OpenWeather API.</p>
          <a href="https://weather-demo.netlify.app" target="_blank">Demo →</a>
        </div>
      </div>

      <div class="card">
        <img src="https://images.unsplash.com/photo-1520333789090-1afc82db536a?auto=format&fit=crop&w=600&q=60" alt="Task Manager">
        <div class="card-body">
          <h3>Task Manager</h3>
          <p>Aplikasi to-do berbasis Firebase Auth & Firestore.</p>
          <a href="https://task-mgr-demo.vercel.app" target="_blank">Demo →</a>
        </div>
      </div>
    </div>
  </section>

  <section id="skills">
    <h2>Skill</h2>
    <div class="skills">
      <span>JavaScript</span>
      <span>TypeScript</span>
      <span>React</span>
      <span>Next.js</span>
      <span>Node.js</span>
      <span>PostgreSQL</span>
      <span>Docker</span>
      <span>Figma</span>
    </div>
  </section>

  <section id="+6281316447919">
    <h2>Kontak</h2>
    <p>
      Email: <a href="barokbarok882@gmail.com">barokbarok882@gmail.com</a><br>
      LinkedIn: <a href="https://linkedin.com/in/username" target="_blank">linkedin.com/in/username</a>
    </p>
  </section>

  <footer>
    &copy; 2024 - <span id="year"></span> Nama Kamu
    <div class="social">
      <a href="https://github.com/username" target="_blank">GitHub</a>
      <a href="https://linkedin.com/in/username" target="_blank">LinkedIn</a>
      <a href="https://twitter.com/username" target="_blank">Twitter</a>
    </div>
  </footer>

  <script>
    // Auto update tahun di footer
    document.getElementById('year').textContent = new Date().getFullYear();

    // Smooth scroll untuk anchor link
    document.querySelectorAll('a[href^="#"]').forEach(anchor => {
      anchor.addEventListener('click', function (e) {
        e.preventDefault();
        const target = document.querySelector(this.getAttribute('href'));
        if (target) {
          target.scrollIntoView({ behavior: 'smooth', block: 'start' });
        }
      });
    });
  </script>
</body>
</html>
