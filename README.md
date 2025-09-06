<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Vineeth Hegde | Portfolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Fira+Code:wght@400;600&display=swap" rel="stylesheet">
  <style>
    * { margin:0; padding:0; box-sizing:border-box; font-family: 'Fira Code', monospace; }
    body { background: #f0f4f8; color: #333; line-height: 1.6; }

    /* Centered sections */
    .section { padding:60px 20px; text-align:center; }
    h1, h2 { margin-bottom:20px; }

    /* Profile Image */
    .profile-img {
      border-radius: 50%;
      border: 4px solid #00c3ff;
      box-shadow: 0px 6px 20px rgba(0,0,0,0.4);
      width:200px;
      transition: transform 0.3s, box-shadow 0.3s;
    }
    .profile-img:hover {
      transform: scale(1.05);
      box-shadow: 0px 10px 30px rgba(0,195,255,0.6);
    }

    /* Gradient Headers */
    .gradient-bg {
      background: linear-gradient(135deg, #00c3ff, #6a00ff);
      color: white;
      padding:40px 20px;
      border-radius:20px;
      margin-bottom:40px;
    }

    /* Typing effect container */
    .typing-container {
      margin-top: 20px;
      font-size: 22px;
      color: #00c3ff;
    }

    /* Social Buttons */
    .social-links img {
      margin:10px;
      transition: transform 0.3s;
    }
    .social-links img:hover { transform: scale(1.1); }

    /* Cards for Achievements */
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

    /* Education & Certifications */
    .edu-cert { display:flex; flex-direction:column; align-items:center; gap:10px; }
    .edu-cert div { background:#6a00ff; color:white; padding:15px 20px; border-radius:15px; width:fit-content; }

    /* Responsive */
    @media(max-width:768px) {
      .cards-container { flex-direction:column; align-items:center; }
      .edu-cert { width:100%; }
    }
  </style>
</head>
<body>

  <!-- Profile Section -->
  <section class="section">
    <img src="Vineeth-Hegde.jpg" alt="Vineeth Hegde" class="profile-img">
    <h1>👋 Hi, I'm Vineeth Hegde</h1>
    <div class="typing-container">
      <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=22&pause=1000&color=00C3FF&center=true&vCenter=true&width=600&lines=🚀+Senior+Java+Developer;☁️+Cloud+Enthusiast;💡+Problem+Solver;🏆+Awarded+at+DXC+Technology" alt="Typing SVG" />
    </div>
  </section>

  <!-- Social Links -->
  <section class="section social-links">
    <a href="https://www.linkedin.com/in/vineethhegde/">
      <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/>
    </a>
    <a href="https://github.com/vineeth-hegde">
      <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>
    </a>
    <a href="https://www.facebook.com/vineeth.hegde.75">
      <img src="https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white"/>
    </a>
    <a href="https://www.instagram.com/vineeth__hegde/">
      <img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white"/>
    </a>
    <a href="https://x.com/vineethhegde68">
      <img src="https://img.shields.io/badge/Twitter(X)-000000?style=for-the-badge&logo=x&logoColor=white"/>
    </a>
  </section>

  <!-- Professional Summary -->
  <section class="section gradient-bg">
    <h2>🌟 Professional Summary</h2>
    <p>💻 Java Developer with <strong>5+ years</strong> of experience in designing, developing, and deploying enterprise applications.</p>
    <p>⚡ Proficient in <strong>Java, Spring Boot, Microservices, REST APIs</strong>, and modern DevOps practices.</p>
    <p>🏅 Recognized multiple times at DXC Technology for impactful contributions to <strong>large-scale modernization projects</strong>.</p>
    <p>🚀 Passionate about building <strong>scalable, secure, and high-performance solutions</strong>.</p>
  </section>

  <!-- Achievements -->
  <section class="section">
    <h2>🏆 Key Achievements</h2>
    <div class="cards-container">
      <div class="card">✅ Delivered inspection reporting solution used by 750+ engineers</div>
      <div class="card">✅ Migrated enterprise apps from Java 6 → 11 and DB2 → SQL</div>
      <div class="card">✅ Automated CI/CD pipelines with Jenkins & Kubernetes</div>
      <div class="card">✅ Mentored junior developers improving team delivery & code quality</div>
      <div class="card">✅ 4+ awards in 3 years at DXC for collaboration and innovation</div>
    </div>
  </section>

  <!-- Tech Stack -->
  <section class="section gradient-bg">
    <h2>🛠 Tech Stack Snapshot</h2>
    <p><strong>Languages & Frameworks:</strong> Java, Spring Boot, REST APIs, Microservices</p>
    <p><strong>Databases:</strong> MySQL, MongoDB, IBM DB2</p>
    <p><strong>DevOps & Tools:</strong> Docker, Kubernetes, Jenkins, Maven, Gradle</p>
    <p><strong>Version Control & Collaboration:</strong> GitHub, Bitbucket, Jira, Confluence</p>
    <p><strong>UI & Reporting:</strong> Angular, HTML/CSS, Jasper Reports</p>
    <p><strong>Cloud & Security:</strong> Azure, AWS, SonarQube, Veracode</p>
    <div class="tech-badges">
      <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white"/>
      <img src="https://img.shields.io/badge/SpringBoot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white"/>
      <img src="https://img.shields.io/badge/Microservices-FF6F00?style=for-the-badge&logo=apache&logoColor=white"/>
      <img src="https://img.shields.io/badge/REST_API-02569B?style=for-the-badge&logo=postman&logoColor=white"/>
      <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white"/>
      <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white"/>
      <img src="https://img.shields.io/badge/IBM_DB2-054ADA?style=for-the-badge&logo=ibm&logoColor=white"/>
      <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
      <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white"/>
      <img src="https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white"/>
      <img src="https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white"/>
      <img src="https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white"/>
    </div>
  </section>

  <!-- Education -->
  <section class="section">
    <h2>🎓 Education</h2>
    <div class="edu-cert">
      <div>🎓 Bachelor of Engineering – NMAM Institute of Technology, Nitte (2019)</div>
      <div>🏫 Pre-University – Alvas PU College, Moodbidri (2015)</div>
      <div>📘 SSLC – Rotary English Medium School, Moodbidri (2013)</div>
    </div>
  </section>

  <!-- Certifications -->
  <section class="section gradient-bg">
    <h2>📜 Certifications</h2>
    <div class="edu-cert">
      <div>🌐 Microsoft Certified: <a href="https://www.credly.com/earner/earned/badge/fafda2e1-12fd-4949-8c0f-f76b03c57c92" style="color:white;">Azure Fundamentals (AZ-900)</a></div>
      <div>☁️ AWS Certified: <a href="https://www.credly.com/badges/52ffe432-de0a-46b9-86d2-ebc7e65fee01" style="color:white;">Cloud Practitioner (CLF-C02)</a></div>
    </div>
  </section>

  <!-- Awards -->
  <section class="section">
    <h2>🏅 Awards</h2>
    <div class="cards-container">
      <div class="card">🏆 DXC India Quarterly Champs Award (2021, 2022, 2023)</div>
      <div class="card">🤝 DXC India Collaborators Award (2021, 2024)</div>
    </div>
  </section>

</body>
</html>
