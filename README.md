<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Dharashan Gowtham | Blog</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Poppins', sans-serif;
    }

    body {
      background-color: #002f6c;
      color: #ffffff;
      padding: 2rem;
      opacity: 0;
      animation: fadeInBody 1.5s ease forwards;
    }

    @keyframes fadeInBody {
      to {
        opacity: 1;
      }
    }

    header {
      background-color: #005fa3;
      color: #ffffff;
      padding: 3rem 1rem;
      text-align: center;
      border-radius: 10px;
      box-shadow: 0 2px 10px rgba(0, 0, 0, 0.2);
      animation: fadeInUp 1s ease-out;
    }

    header h1 {
      font-size: 3rem;
      margin-bottom: 1rem;
    }

    nav {
      margin-top: 1rem;
    }

    nav a {
      color: #ffffff;
      background-color: #0077cc;
      padding: 0.6rem 1.2rem;
      margin: 0 0.5rem;
      border-radius: 6px;
      text-decoration: none;
      transition: all 0.3s ease;
      display: inline-block;
    }

    nav a:hover {
      background-color: #003f75;
      transform: scale(1.05);
    }

    .content {
      max-width: 900px;
      margin: 3rem auto;
      background-color: rgba(255, 255, 255, 0.1);
      padding: 2rem 3rem;
      border-radius: 12px;
      box-shadow: 0 2px 20px rgba(0, 0, 0, 0.3);
      animation: fadeInUp 1.5s ease;
    }

    .content h2 {
      color: #aad4ff;
      margin-bottom: 1rem;
      font-size: 2rem;
    }

    .about, .skills, .certifications {
      margin-top: 3rem;
      opacity: 0;
      transform: translateY(40px);
      animation: fadeInUp 1s ease forwards;
      animation-delay: 0.5s;
    }

    .skills {
      animation-delay: 0.8s;
    }

    .certifications {
      animation-delay: 1s;
    }

    .about ul, .skills ul, .certifications ul {
      list-style: none;
      padding-left: 0;
    }

    .about li, .skills li {
      margin: 0.5rem 0;
      font-size: 1.1rem;
    }

    .skills li::before {
      content: "★ ";
      color: #aad4ff;
      margin-right: 0.3rem;
    }

    .certifications li {
      margin-bottom: 1.5rem;
      font-size: 1.05rem;
      background-color: rgba(255, 255, 255, 0.08);
      padding: 1rem;
      border-radius: 10px;
      border-left: 4px solid #aad4ff;
    }

    footer {
      text-align: center;
      margin-top: 4rem;
      font-size: 0.9rem;
      color: #cce6ff;
      animation: fadeInUp 2s ease;
    }

    @keyframes fadeInUp {
      from {
        opacity: 0;
        transform: translateY(40px);
      }
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }

    @media (max-width: 768px) {
      header h1 {
        font-size: 2rem;
      }

      .content {
        padding: 1.5rem;
      }

      nav a {
        display: inline-block;
        margin-top: 0.5rem;
      }
    }
  </style>
</head>
<body>
  <header>
    <h1>Dharashan Gowtham</h1>
    <nav>
      <a href="https://wa.me/yourwhatsapplink" target="_blank">WhatsApp</a>
      <a href="https://www.instagram.com/dharshangowtham_?igsh=bG9sZGpxemRrNzd5" target="_blank">Instagram</a>
      <a href="https://www.linkedin.com/in/dharshan-gowtham-297396372?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app" target="_blank">LinkedIn</a>
    </nav>
  </header>

  <section class="content">
    <h2>Welcome to My Blog</h2>
    <p>
      Hi, I’m Dharashan Gowtham. This is my space where I share my journey,
      passions, and ideas on a variety of topics including technology, creativity,
      self-growth, and more. Whether you're here for inspiration, connection,
      or curiosity — I'm glad to have you here!
    </p>
    <p>
      Connect with me through the links above and stay tuned for more engaging content.
    </p>

    <div class="about">
      <h2>About Me</h2>
      <ul>
        <li><strong>Date of Birth:</strong> 29 May 2025</li>
        <li><strong>Place:</strong> Tamil Nadu, Madurai</li>
        <li><strong>School:</strong> PSY Matriculation School</li>
        <li><strong>College Joining:</strong> Mepco Engineering College, Sivakasi</li>
        <li><strong>Course:</strong> B.Tech Information Technology</li>
        <li><strong>Aim:</strong> To become an interpreter in software development</li>
      </ul>
    </div>

    <div class="skills">
      <h2>My Skills</h2>
      <ul>
        <li>Beginner in Data Analytics</li>
        <li>Basic Knowledge of Artificial Intelligence (AI)</li>
        <li>Python Programming Fundamentals</li>
        <li>This is my first web project!</li>
      </ul>
    </div>

    <div class="certifications">
      <h2>Certifications</h2>
      <ul>
        <li>
          <strong>Course:</strong> Introduction to Data Analytics<br />
          <strong>Platform:</strong> Simplilearn SkillUp<br />
          <strong>Certificate Code:</strong> 8663441<br />
          <strong>Date:</strong> 21 July 2025<br />
          <strong>Issued by:</strong> Krishna Kumar, CEO, Simplilearn
        </li>
        <li>
          <strong>Course:</strong> AI for Beginners<br />
          <strong>Platform:</strong> HP LIFE (HP Foundation)<br />
          <strong>Certificate Code:</strong> e8743<br />
          <strong>Date:</strong> 17 July 2025<br />
          <strong>Issued by:</strong> Stephanie Bormann, Deputy Director, HP Foundation
        </li>
      </ul>
    </div>
  </section>

  <footer>
    <p>&copy; 2025 Dharashan Gowtham. All rights reserved.</p>
  </footer>
</body>
</html>