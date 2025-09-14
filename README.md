# Portfolio.Light
This repository hosts the source code for my personal portfolio website, highlighting my professional journey, skills, and projects.  I am a Salesforce Developer &amp; Administrator with expertise in Java, Python, SQL, and CRM solutions. I specialize in business process improvement, automation, and data-driven decision-making.
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Kommineni Rekha Chowdary - Portfolio</title>
  <style>
    /* Light Mode */
    body {
      font-family: 'Arial', sans-serif;
      margin: 0;
      padding: 0;
      color: #222;
      background-color: #ffffff;
      line-height: 1.6;
      transition: background 0.3s, color 0.3s;
    }

    a {
      color: #1e40af;
      text-decoration: none;
    }
    a:hover {
      text-decoration: underline;
    }

    header {
      background-color: #f8f9fa;
      padding: 20px 40px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
      display: flex;
      justify-content: space-between;
      align-items: center;
      position: sticky;
      top: 0;
      z-index: 1000;
    }

    nav a {
      margin-left: 20px;
      font-weight: bold;
      color: #222;
    }

    section {
      max-width: 1000px;
      margin: 50px auto;
      padding: 0 20px;
      text-align: center;
    }

    h1, h2, h3 {
      color: #1e40af;
    }
    h1 { font-size: 2.5rem; }
    h2 { font-size: 2rem; margin-bottom: 10px; }
    h3 { font-size: 1.5rem; margin-top: 20px; }

    .profile-img {
      width: 160px;
      height: 160px;
      border-radius: 50%;
      object-fit: cover;
      margin-bottom: 20px;
      border: 3px solid #1e40af;
    }

    .section-divider {
      height: 2px;
      width: 80px;
      background-color: #1e40af;
      margin: 10px auto 20px auto;
    }

    .skills, .services, .experience, .projects, .certifications, .education-cards {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
    }

    .card {
      background-color: #f8f9fa;
      border-radius: 8px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
      padding: 20px;
      margin: 10px;
      flex: 1 1 300px;
      color: #222;
      text-align: left;
    }

    button {
      background-color: #1e40af;
      color: #fff;
      padding: 10px 20px;
      border: none;
      border-radius: 25px;
      margin: 5px;
      cursor: pointer;
      transition: background 0.3s;
    }
    button:hover {
      background-color: #2563eb;
    }

    footer {
      text-align: center;
      padding: 20px;
      background-color: #1e3a8a;
      color: #ffffff;
      margin-top: 40px;
    }

    /* Education Cards */
    .education-cards .card {
      flex: 1 1 400px;
      text-align: left;
    }

    /* Responsive */
    @media(max-width:768px){
      header {
        flex-direction: column;
        align-items: flex-start;
      }
      nav a {
        margin-left: 0;
        margin-top: 10px;
      }
    }
  </style>
</head>
<body>

  <!-- Header -->
  <header>
    <h1>Kommineni Rekha Chowdary</h1>
    <nav>
      <a href="#home">Home</a>
      <a href="#about">About</a>
      <a href="#education">Education</a>
      <a href="#skills">Skills</a>
      <a href="#experience">Experience</a>
      <a href="#certifications">Certifications</a>
      <a href="#services">Services</a>
      <a href="#projects">Projects</a>
      <a href="#resume">Resume</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <!-- Home Section -->
  <section id="home">
    <img src="https://i.ibb.co/Q7T3dndL/IMG-20250514-103030.jpg" 
         alt="Kommineni Rekha Chowdary" 
         class="profile-img">
    <h2>Hello, I'm Rekha</h2>
    <p>Salesforce Developer & Administrator | Java, Python, SQL | CRM & Business Process Improvement</p>
    <a href="#contact"><button>Get In Touch</button></a>
    <a href="https://drive.google.com/file/d/1RXs2nhh9wJCX_vbnm56g5hHIKDuL-m6F/view?usp=drive_link" target="_blank">
      <button>Download Resume</button>
    </a>
  </section>

  <!-- About Section -->
  <section id="about">
    <h2>About Me</h2>
    <div class="section-divider"></div>
    <p>I am a Salesforce Developer and Administrator with a strong background in Java, Python, and SQL. 
       I specialize in CRM solutions, data analysis, and business process improvement, combining technical 
       expertise with a focus on delivering impactful results. Passionate about continuous learning, I aim 
       to leverage my skills to solve complex problems and drive efficiency, while connecting with professionals 
       who value innovation and collaboration.</p>
  </section>

  <!-- Education Section -->
  <section id="education">
    <h2>Education</h2>
    <div class="section-divider"></div>
    <div class="education-cards">
      <div class="card">
        <h3>MBA – HR & IT</h3>
        <p>Dr. AER MBA College, Sri Venkateswara University (2023–2025)</p>
        <p>CGPA: 7.18</p>
      </div>
      <div class="card">
        <h3>B.Com – Computer Applications</h3>
        <p>Dr. AER Degree/PG College, Sri Venkateswara University (2020–2023)</p>
        <p>CGPA: 8.6</p>
      </div>
      <div class="card">
        <h3>Intermediate (Class 12)</h3>
        <p>Sri Chaitanya Junior College (2018–2020)</p>
        <p>CGPA: 8.25</p>
      </div>
      <div class="card">
        <h3>10th Standard (SSC)</h3>
        <p>Sri Chaitanya School (2017–2018)</p>
        <p>CGPA: 9.8</p>
      </div>
    </div>
  </section>

  <!-- Skills Section -->
  <section id="skills">
    <h2>Skills</h2>
    <div class="section-divider"></div>
    <h3>Technical Skills</h3>
    <div class="skills">
      <div class="card">Salesforce (Developer & Administrator)</div>
      <div class="card">Java</div>
      <div class="card">Python</div>
      <div class="card">SQL</div>
      <div class="card">Cybersecurity Fundamentals</div>
      <div class="card">MS Excel & MS PowerPoint</div>
      <div class="card">Accounting Software</div>
    </div>
    <h3>Professional Skills</h3>
    <div class="skills">
      <div class="card">Data Analysis</div>
      <div class="card">Business Process Improvement</div>
      <div class="card">CRM Management</div>
      <div class="card">Financial Reporting</div>
      <div class="card">Communication</div>
      <div class="card">Team Collaboration</div>
      <div class="card">Research & Documentation</div>
    </div>
  </section>

  <!-- Experience Section -->
  <section id="experience">
    <h2>Experience</h2>
    <div class="section-divider"></div>
    <div class="experience">
      <div class="card">
        <h3>Finance & Accounts Intern – Amara Raja Energy & Mobility Ltd</h3>
        <p>Aug 2024 – Apr 2025 | India</p>
        <ul>
          <li>Assisted in financial reporting, budgeting, and account reconciliations.</li>
          <li>Gained hands-on experience in accounting software and financial analysis.</li>
          <li>Supported the finance team in optimizing accounting processes.</li>
        </ul>
      </div>
      <div class="card">
        <h3>Sales & Accounts Intern – Aqua Group: Texmo (Sri Ganesh Electricals)</h3>
        <p>Dec 2022 – May 2023 | India</p>
        <ul>
          <li>Assisted in managing physical sales operations, including billing, invoicing, and payment tracking.</li>
          <li>Gained practical experience in handling accounts, maintaining financial records, and preparing sales reports.</li>
          <li>Supported the team in streamlining sales and accounting processes to improve efficiency and accuracy.</li>
        </ul>
      </div>
      <div class="card">
        <h3>Salesforce Developer Intern – Salesforce, SmartInternz</h3>
        <p>Aug 2022 – Oct 2022 | Remote</p>
        <ul>
          <li>Gained hands-on experience in Salesforce development and customization.</li>
          <li>Assisted in creating workflows, reports, and dashboards.</li>
          <li>Enhanced knowledge of CRM processes and business automation.</li>
        </ul>
      </div>
      <div class="card">
        <h3>Cybersecurity Virtual Intern – Palo Alto Networks</h3>
        <p>Sep 2022 – Nov 2022 | Remote</p>
        <ul>
          <li>Learned cybersecurity fundamentals and network security protocols.</li>
          <li>Assisted in vulnerability assessment and threat analysis exercises.</li>
          <li>Gained exposure to real-world cybersecurity tools and practices.</li>
        </ul>
      </div>
      <div class="card">
        <h3>Salesforce Administrator Intern – Salesforce, SmartInternz</h3>
        <p>Apr 2023 – May 2023 | Remote</p>
        <ul>
          <li>Learned Salesforce administration tasks including user management and data maintenance.</li>
          <li>Assisted in configuring Salesforce objects, fields, and reports.</li>
          <li>Supported teams in optimizing CRM workflows and business processes.</li>
        </ul>
      </div>
    </div>
  </section>

  <!-- Certifications Section -->
  <section id="certifications">
    <h2>Certifications</h2>
    <div class="section-divider"></div>
    <div class="certifications">
      <div class="card">Cybersecurity Essentials – Cisco</div>
      <div class="card">Master Class on Java Programming – Pantech E-Learning</div>
      <div class="card">Master Class on Python Programming – Skill AP (APSSDC)</div>
      <div class="card">Essential Program in Python – LetsUpgrade</div>
      <div class="card">AWS Security Fundamentals – AWS</div>
    </div>
  </section>

  <!-- Services Section -->
  <section id="services">
    <h2>Services</h2>
    <div class="section-divider"></div>
    <div class="services">
      <div class="card">
        <h3>Salesforce Solutions</h3>
        <p>Customization, administration, and development of Salesforce solutions.</p>
      </div>
      <div class="card">
        <h3>Software Development</h3>
        <p>Building applications using Java, Python, or SQL.</p>
      </div>
      <div class="card">
        <h3>Finance & Accounts Support</h3>
        <p>Data management, process improvement, and reporting support.</p>
      </div>
      <div class="card">
        <h3>Business Process Improvement</h3>
        <p>Analyzing workflows and suggesting better solutions.</p>
      </div>
    </div>
  </section>

  <!-- Projects Section -->
  <section id="projects">
    <h2>Projects</h2>
    <div class="section-divider"></div>
    <div class="projects">
      <div class="card">
        <h3>Community Service Project – Enhancing the Awareness of Dairy Business</h3>
        <p>Dec 2022 – Jan 2023</p>
        <ul>
          <li>Conducted awareness campaigns to educate local communities about dairy business practices.</li>
          <li>Assisted in creating informational materials and presentations.</li>
          <li>Gained experience in community engagement, research, and communication skills.</li>
        </ul>
      </div>
      <div class="card">
        <h3>Research Project – A Study on Job Enrichment in APSPDCL</h3>
        <p>Sep 2024 – Nov 2024</p>
        <ul>
          <li>Analyzed job enrichment practices and their impact on employee motivation.</li>
          <li>Collected and interpreted data through surveys and interviews.</li>
          <li>Developed insights to improve organizational efficiency and employee satisfaction.</li>
        </ul>
      </div>
    </div>
  </section>

  <!-- Resume Section -->
  <section id="resume">
    <h2>Resume</h2>
    <div class="section-divider"></div>
    <p style="max-width:700px; margin: 0 auto 20px auto;">
      I am a dedicated Salesforce Developer & Administrator with expertise in Java, Python, and SQL. 
      With hands-on experience in CRM solutions, finance, and cybersecurity, I bring both technical 
      and analytical skills to deliver efficient business process improvements. Passionate about learning 
      and innovation, I aim to create impactful solutions that drive growth and efficiency.
    </p>
    <a href="https://drive.google.com/file/d/1RXs2nhh9wJCX_vbnm56g5hHIKDuL-m6F/view?usp=drive_link" target="_blank">
      <button>Download Resume</button>
    </a>
  </section>

  <!-- Contact Section -->
  <section id="contact">
    <h2>Contact</h2>
    <div class="section-divider"></div>
    <p>Phone: +91 79012 66761</p>
    <p>Email: <a href="mailto:rekhachowdarykommineni@gmail.com">rekhachowdarykommineni@gmail.com</a></p>
    <p>LinkedIn: <a href="https://www.linkedin.com/in/kommineni-rekha-chowdary" target="_blank">linkedin.com/in/kommineni-rekha-chowdary</a></p>
    <p>GitHub: <a href="https://github.com/Komminenirekha" target="_blank">github.com/Komminenirekha</a></p>
    <a href="mailto:rekhachowdarykommineni@gmail.com"><button>Get In Touch</button></a>
  </section>

  <footer>
    <p>© 2025 Kommineni Rekha Chowdary. All rights reserved.</p>
  </footer>

  <!-- Smooth Scroll JS -->
  <script>
    document.querySelectorAll('a[href^="#"]').forEach(anchor => {
      anchor.addEventListener('click', function(e) {
        e.preventDefault();
        const target = document.querySelector(this.getAttribute('href'));
        if(target){
          target.scrollIntoView({ behavior: 'smooth', block: 'start' });
        }
      });
    });
  </script>

</body>
</html>
