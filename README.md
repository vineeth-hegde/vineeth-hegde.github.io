<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Vineeth Hegde | Personal Website</title>
  <link href="https://fonts.googleapis.com/css2?family=Fira+Code:wght@400;600&display=swap" rel="stylesheet">
  <style>
    * { margin:0; padding:0; box-sizing:border-box; font-family: 'Fira Code', monospace; }
    body { background: #f0f4f8; color: #333; line-height: 1.6; scroll-behavior: smooth; }

    a { text-decoration:none; }

    /* Centered Sections */
    section { padding:60px 20px; text-align:center; }
    h1, h2 { margin-bottom:20px; }

    /* Profile Image */
    .profile-img {
      border-radius:50%;
      border: 4px solid #00c3ff;
      box-shadow: 0px 6px 20px rgba(0,0,0,0.4);
      width:200px;
      transition: transform 0.3s, box-shadow 0.3s;
    }
    .profile-img:hover {
      transform: scale(1.05);
      box-shadow: 0px 10px 30px rgba(0,195,255,0.6);
    }

    /* Hero / Greeting */
    .hero { background: linear-gradient(135deg, #00c3ff, #6a00ff); color:white; border-radius:20px; margin-bottom:40px; padding:60px 20px; }
    .hero h1 { font-size:2.5em; }
    .typing-container { margin-top:20px; font-size:22px; color:white; }

    /* Social Links */
    .social-links img { margin:10px; transition: transform 0.3s; }
    .social-links img:hover { transform: scale(1.1); }

    /* Cards */
    .cards-container {
      display:flex; flex-wrap:wrap; justify-content:center; gap:20px;
    }
    .card {
      background: #00c3ff; color:white; padding:20px; border-radius:15px;
      min-width:200px; flex:1; max-width:300px;
      transition: transform 0.3s, box-shadow 0.3s;
    }
    .card:hover { transform: scale(1.05); box-shadow:0px 10px 30px rgba(0,195,255,0.5); }

    /* Tech badges */
    .tech-badges img { margin:5px; transition: transform 0.3s; }
    .tech-badges img:hover { transform: scale(1.1); }

    /* Education / Certifications */
    .edu-cert { display:flex; flex-direction:column; align-items:center; gap:10px; }
    .edu-cert div { background:#6a00ff; color:white; padding:15px 20px; border-radius:15px; width:fit-content; }

    /* Interests */
    .interests span { display:inline-block; margin:10px; padding:10px 20px; background:#ff6f61; color:white; border-radius:15px; font-weight:bold; }

    /* Responsive */
    @media(max-width:768px) {
      .cards-container { flex-direction:column; align-items:center; }
      .edu-cert { width:100%; }
    }
  </style>
</head>
<body>

  <!-- Hero Section -->
  <section class="hero">
    <img src="Vineeth-Hegde.jpg" alt="Vineeth Hegde" class="profile-img">
    <h1>👋 Hey! I'm Vineeth Hegde</h1>
    <div class="typing-container">
      <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=22&pause=1000&color=FFFFFF&center=true&vCenter=true&width=600&lines=🚀+Senior+Java+Developer;☁️+Cloud+Enthusiast;💡+Problem+Solver;🏆+Awarded+at+DXC+Technology" alt="Typing SVG" />
    </div>
    <div class="social-links">
      <a href="https://www.linkedin.com/in/vineethhegde/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
      <a href="https://github.com/vineeth-hegde"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/></a>
      <a href="https://www.instagram.com/vineeth__hegde/"><img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white"/></a>
    </div>
  </section>

  <!-- About Me -->
  <section>
    <h2>💁 About Me</h2>
    <p>Hi! I’m Vineeth, born and brought up in Moodbidri 🌴. I love coding, cloud technologies, and building solutions that make a difference.</p>
    <p>I’m friendly, curious, and always up for learning new things!</p>
    <h3>🎯 Interests</h3>
    <div class="interests">
      <span>Travelling ✈️</span>
      <span>Cooking 🍳</span>
      <span>Photography 📸</span>
    </div>
  </section>

  <!-- Skills -->
  <section>
    <h2>🛠 Skills</h2>
    <div class="tech-badges">
      <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white"/>
      <img src="https://img.shields.io/badge/SpringBoot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white"/>
      <img src="https://img.shields.io/badge/Microservices-FF6F00?style=for-the-badge&logo=apache&logoColor=white"/>
      <img src="https://img.shields.io/badge/REST_API-02569B?style=for-the-badge&logo=postman&logoColor=white"/>
      <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white"/>
      <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white"/>
      <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
      <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white"/>
      <img src="https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white"/>
      <img src="https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white"/>
    </div>
  </section>

  <!-- Achievements -->
  <section>
    <h2>🏆 Achievements</h2>
    <div class="cards-container">
      <div class="card">Delivered inspection reporting solution used by 750+ engineers</div>
      <div class="card">Migrated enterprise apps from Java 6 → 11 and DB2 → SQL</div>
      <div class="card">Automated CI/CD pipelines with Jenkins & Kubernetes</div>
      <div class="card">Mentored junior developers improving team delivery & code quality</div>
      <div class="card">4+ awards in 3 years at DXC for collaboration and innovation</div>
    </div>
  </section>

  <!-- Education & Certifications -->
  <section>
    <h2>🎓 Education & Certifications</h2>
    <div class="edu-cert">
      <div>B.E. – NMAM Institute of Technology, Nitte (2019)</div>
      <div>Pre-University – Alvas PU College, Moodbidri (2015)</div>
      <div>SSLC – Rotary English Medium School, Moodbidri (2013)</div>
      <div>🌐 Azure Fundamentals (AZ-900)</div>
      <div>☁️ AWS Cloud Practitioner (CLF-C02)</div>
    </div>
  </section>

  <!-- Contact -->
  <section>
    <h2>📬 Say Hi!</h2>
    <p>You can reach me on social media or drop a message anytime. Always happy to connect!</p>
    <div class="social-links">
      <a href="https://www.linkedin.com/in/vineethhegde/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
      <a href="https://github.com/vineeth-hegde"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/></a>
      <a href="https://www.instagram.com/vineeth__hegde/"><img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white"/></a>
    </div>
  </section>

  <!-- Footer -->
  <footer style="padding:20px; text-align:center; background:#6a00ff; color:white;">
    Made with ❤️ by Vineeth | Built for fun & learning
  </footer>

</body>
</html>
