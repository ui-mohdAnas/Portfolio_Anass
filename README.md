# Portfolio_Anass
This is the repo of mine for portfolio.
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Mohammad Anas - Portfolio</title>
  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }
    
    body {
      font-family: 'Poppins', 'Segoe UI', sans-serif;
      background-color: #f8f9fa;
      color: #333;
      line-height: 1.6;
    }
    
    header {
      background: linear-gradient(135deg, #6e48aa 0%, #9d50bb 100%);
      color: #fff;
      text-align: center;
      padding: 80px 20px;
      position: relative;
      overflow: hidden;
    }
    
    <header>
  <div class="header-bg"></div>
  <div class="profile-container">
    <div class="profile-img">
      <!-- Updated img tag with reference to the name from PDF -->
      <img src="https://via.placeholder.com/180/6e48aa/ffffff?text=WAM" alt="WAM ARRIQAIE">
    </div>
    <div class="profile-text">
      <h1>WAM ARRIQAIE</h1>
      <p>AI/ML Student | Developer | Tech Enthusiast</p>
    </div>
  </div>
</header>
    
    .profile-img img {
      width: 180px;
      height: 180px;
      border-radius: 50%;
      object-fit: cover;
      border: 5px solid rgba(255, 255, 255, 0.2);
      box-shadow: 0 8px 32px rgba(0, 0, 0, 0.3);
    }
    
    .profile-text {
      text-align: center;
    }
    
    .profile-text h1 {
      font-size: 2.8em;
      margin-bottom: 10px;
      font-weight: 700;
    }
    
    .profile-text p {
      font-size: 1.2em;
      opacity: 0.9;
    }
    
    .header-bg {
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background: url('data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxMDAlIiBoZWlnaHQ9IjEwMCUiPjxkZWZzPjxwYXR0ZXJuIGlkPSJwYXR0ZXJuIiB3aWR0aD0iNDAiIGhlaWdodD0iNDAiIHBhdHRlcm5Vbml0cz0idXNlclNwYWNlT25Vc2UiIHBhdHRlcm5UcmFuc2Zvcm09InJvdGF0ZSg0NSkiPjxyZWN0IHdpZHRoPSIyMCIgaGVpZ2h0PSIyMCIgZmlsbD0icmdiYSgyNTUsMjU1LDI1NSwwLjA1KSIvPjwvcGF0dGVybj48L2RlZnM+PHJlY3Qgd2lkdGg9IjEwMCUiIGhlaWdodD0iMTAwJSIgZmlsbD0idXJsKCNwYXR0ZXJuKSIvPjwvc3ZnPg==');
      z-index: 1;
    }
    
    nav {
      background: #4a2c82;
      padding: 15px;
      text-align: center;
      position: sticky;
      top: 0;
      z-index: 100;
      box-shadow: 0 2px 10px rgba(0,0,0,0.1);
    }
    
    nav a {
      color: #fff;
      text-decoration: none;
      margin: 0 15px;
      font-weight: 500;
      font-size: 1.1em;
      padding: 5px 10px;
      border-radius: 4px;
      transition: all 0.3s ease;
    }
    
    nav a:hover {
      background-color: rgba(255, 255, 255, 0.2);
    }
    
    section {
      padding: 80px 20px;
      max-width: 1200px;
      margin: auto;
    }
    
    .about-card {
      background-color: #fff;
      border-radius: 12px;
      padding: 30px;
      box-shadow: 0 8px 24px rgba(0,0,0,0.08);
      max-width: 800px;
      margin: 0 auto;
      text-align: center;
    }
    
    section h2 {
      text-align: center;
      margin-bottom: 40px;
      color: #4a2c82;
      font-size: 2.2em;
      position: relative;
    }
    
    section h2::after {
      content: '';
      display: block;
      width: 80px;
      height: 4px;
      background: linear-gradient(to right, #6e48aa, #9d50bb);
      margin: 15px auto 0;
      border-radius: 2px;
    }
    
    .projects {
      display: flex;
      flex-wrap: wrap;
      gap: 30px;
      justify-content: center;
    }
    
    .project {
      background-color: #fff;
      border-radius: 12px;
      padding: 25px;
      box-shadow: 0 8px 24px rgba(0,0,0,0.08);
      width: 350px;
      transition: all 0.3s ease;
    }
    
    .project h3 {
      margin-bottom: 15px;
      color: #4a2c82;
    }
    
    .project p {
      font-size: 0.95em;
      color: #555;
      margin-bottom: 15px;
    }
    
    .project:hover {
      transform: translateY(-10px);
      box-shadow: 0 12px 28px rgba(0,0,0,0.15);
    }
    
    .contact-card {
      background-color: #fff;
      border-radius: 12px;
      padding: 30px;
      box-shadow: 0 8px 24px rgba(0,0,0,0.08);
      max-width: 600px;
      margin: 0 auto;
      text-align: center;
    }
    
    .contact-info {
      display: flex;
      flex-direction: column;
      gap: 15px;
      margin-top: 20px;
    }
    
    .contact-item {
      display: flex;
      align-items: center;
      justify-content: center;
      gap: 10px;
    }
    
    .contact-item i {
      color: #6e48aa;
      font-size: 1.2em;
    }
    
    footer {
      background: linear-gradient(135deg, #4a2c82 0%, #6e48aa 100%);
      color: #fff;
      text-align: center;
      padding: 30px;
      margin-top: 60px;
    }
    
    @media (max-width: 768px) {
      .profile-container {
        flex-direction: column;
      }
      
      nav a {
        display: block;
        margin: 10px 0;
      }
      
      .project {
        width: 100%;
      }
    }
  </style>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600;700&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
</head>
<body>

  <header>
    <div class="header-bg"></div>
    <div class="profile-container">
      <div class="profile-img">
        <img src="https://via.placeholder.com/180" alt="Mohammad Anas">
      </div>
      <div class="profile-text">
        <h1>Mohammad Anas</h1>
        <p>AI/ML Student | Developer | Tech Enthusiast</p>
      </div>
    </div>
  </header>

  <nav>
    <a href="#about"><i class="fas fa-user"></i> About</a>
    <a href="#projects"><i class="fas fa-code"></i> Projects</a>
    <a href="#contact"><i class="fas fa-envelope"></i> Contact</a>
  </nav>

  <section id="about">
    <h2>About Me</h2>
    <div class="about-card">
      <p>
        Hello! I'm Mohammad Anas, a passionate B.Tech student specializing in Artificial Intelligence and Machine Learning. I'm deeply fascinated by the potential of AI to transform our world and enjoy building practical solutions to real-world problems.
      </p>
      <p style="margin-top: 15px;">
        When I'm not coding, you can find me exploring new technologies, contributing to open-source projects, or mentoring fellow students in their tech journey.
      </p>
    </div>
  </section>

  <section id="projects">
    <h2>My Projects</h2>
    <div class="projects">
      <div class="project">
        <h3>AI-Based Health Assistant</h3>
        <p>A conversational AI that provides basic health advice and symptom checking using natural language processing and machine learning algorithms.</p>
        <p><i class="fas fa-tags"></i> Python, TensorFlow, NLP</p>
      </div>
      <div class="project">
        <h3>Smart Agriculture System</h3>
        <p>IoT-based solution that monitors soil conditions and optimizes irrigation using sensor data and predictive models.</p>
        <p><i class="fas fa-tags"></i> IoT, Machine Learning, Arduino</p>
      </div>
      <div class="project">
        <h3>E-Commerce Recommendation Engine</h3>
        <p>Personalized product recommendation system that increases conversion rates by analyzing user behavior patterns.</p>
        <p><i class="fas fa-tags"></i> Python, Scikit-learn, Collaborative Filtering</p>
      </div>
    </div>
  </section>

  <section id="contact">
    <h2>Get In Touch</h2>
    <div class="contact-card">
      <p>Feel free to reach out for collaborations or just to say hello!</p>
      <div class="contact-info">
        <div class="contact-item">
          <i class="fas fa-map-marker-alt"></i>
          <span>Yamuna Nagar, Haryana, India</span>
        </div>
        <div class="contact-item">
          <i class="fas fa-phone"></i>
          <span>+91 8053907780</span>
        </div>
        <div class="contact-item">
          <i class="fas fa-envelope"></i>
          <span>mohammadanas@example.com</span>
        </div>
        <div class="contact-item">
          <i class="fas fa-id-card"></i>
          <span> 23100010060</span>
        </div>
      </div>
    </div>
  </section>

  <footer>
    <p>&copy; 2023 Mohammad Anas. All rights reserved.</p>
    <div style="margin-top: 15px;">
      <a href="#" style="color: white; margin: 0 10px;"><i class="fab fa-github"></i></a>
      <a href="#" style="color: white; margin: 0 10px;"><i class="fab fa-linkedin"></i></a>
      <a href="#" style="color: white; margin: 0 10px;"><i class="fab fa-twitter"></i></a>
    </div>
  </footer>

</body>
</html>
