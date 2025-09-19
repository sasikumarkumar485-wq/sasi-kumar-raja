<!DOCTYPE html>
<html lang="en">  
<head>  
  <meta charset="UTF-8">  
  <meta name="viewport" content="width=device-width, initial-scale=1.0">  
  <title>Student Portfolio - Sasi Kumar Raja</title>  
  <style>  
    body {  
      font-family: Arial, sans-serif;  
      margin: 0; padding: 0;  
      background: #f9f9f9; color: #333;  
    }  
    header {  
      background: darkblue; color: white;   /* Changed colour */  
      padding: 20px; text-align: center;  
    }  
    nav a {  
      margin: 0 10px; color: white; text-decoration: none;  
      font-weight: bold;  
    }  
    section {  
      padding: 40px; max-width: 900px; margin: auto;  
    }  
    .skills, .projects {  
      display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));  
      gap: 15px;  
    }  
    .card {  
      background: white; padding: 20px; border-radius: 10px;  
      box-shadow: 0 4px 6px rgba(0,0,0,0.1);  
      transition: transform 0.2s;  
    }  
    .card:hover {  
      transform: scale(1.05);  
    }  
    footer {  
      text-align: center; padding: 20px;  
      background: darkblue; color: white;  
    }  
    button {  
      background: darkblue; color: white; border: none; padding: 10px;  
      border-radius: 5px; cursor: pointer;  
    }  
    input, textarea {  
      width: 100%; padding: 8px; margin: 5px 0;  
      border: 1px solid #ccc; border-radius: 5px;  
    }  
    #contactDetails {  
      margin-top: 20px; padding: 15px;  
      background: #e6e6e6; border-radius: 8px;  
      border: 1px solid #ccc;  
    }  
  </style>  
</head>  
<body>  
  <header>  
    <h1>Sasi Kumar Raja - Student Portfolio</h1>  
    <nav>  
      <a href="#about">About</a>  
      <a href="#education">Education</a>  
      <a href="#skills">Skills</a>  
      <a href="#projects">Projects</a>  
      <a href="#contact">Contact</a>  
    </nav>  
  </header>  

  <!-- About Section -->  
  <section id="about">  
    <h2>About Me</h2>  
    <p>Hello! I am <b>Sasi Kumar Raja</b>, currently pursuing BCA. My ambition is to become a <b>Software Engineer</b>. This portfolio showcases my education, skills, and projects.</p>  
  </section>  

  <!-- Education Section -->  
  <section id="education">  
    <h2>Education</h2>  
    <ul>  
      <li><b>BCA</b> - (Ongoing)</li>  
      <li><b>12th Standard</b> - Completed</li>  
      <li><b>10th Standard</b> - Completed</li>  
    </ul>  
  </section>  

  <!-- Skills Section -->  
  <section id="skills">  
    <h2>Skills</h2>  
    <div class="skills">  
      <div class="card">HTML</div>  
      <div class="card">CSS</div>  
      <div class="card">JavaScript</div>  
      <div class="card">Python</div>  
      <div class="card">AI (Artificial Intelligence)</div>  
      <div class="card">UI & UX Design</div>  
      <div class="card">DCA (Diploma in Computer Applications)</div>  
    </div>  
  </section>  

  <!-- Projects Section -->  
  <section id="projects">  
    <h2>Projects</h2>  
    <div class="projects">  
      <div class="card">  
        <h3>Portfolio Website</h3>  
        <p>Created using HTML, CSS, JavaScript</p>  
      </div>  
      <div class="card">  
        <h3>Library Management System</h3>  
        <p>Mini project using Python</p>  
      </div>  
    </div>  
  </section>  

  <!-- Contact Section -->  
  <section id="contact">  
    <h2>Contact Me</h2>  
    <div id="contactDetails">  
      <h3>Contact Details:</h3>  
      <p><b>Name:</b> Sasi Kumar Raja</p>  
      <p><b>Email:</b> sasikumarraja@example.com</p>  
      <p><b>Message:</b> Feel free to contact me for collaboration!</p>  
    </div>  
  </section>  

  <!-- Footer -->  
  <footer>  
    <p>&copy; 2025 Sasi Kumar Raja | Student Portfolio</p>  
  </footer>  
</body>  
</html>
