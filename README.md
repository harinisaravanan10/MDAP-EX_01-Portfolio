# MDAP-EX_01-Portfolio
## Date:

## AIM
To create a Portfolio using HTML and CSS.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for introduction, about, projects, and contact details.

### STEP 5
Define global styles for fonts, colors, and layout.

### STEP 6
Style the header, navigation bar, and sections.

### STEP 7
Use Flexbox or CSS Grid for layout design.

### STEP 8
Add hover effects and transitions for interactivity.

### STEP 9
Add Images and Media.

### STEP 10
Use optimized images for a professional look.

### STEP 11
Open the HTML file in a browser to check layout and functionality.

### STEP 12
Fix styling issues and refine content placement.

### STEP 13
Deploy the Portfolio.

### STEP 14
Upload to GitHub Pages for free hosting.

## PROGRAM
### index.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Harini S - Portfolio</title>
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
</head>
<body>
    <!-- Navigation -->
    <header>
        <div class="container">
            <div class="logo">
                <h1>Harini S</h1>
            </div>
            <input type="checkbox" id="nav-toggle" class="nav-toggle">
            <label for="nav-toggle" class="nav-toggle-label">
                <span></span>
            </label>
            <nav>
                <ul>
                    <li><a href="#home">Home</a></li>
                    <li><a href="#about">About</a></li>
                    <li><a href="#skills">Skills</a></li>
                    <li><a href="#projects">Projects</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>
    <!-- Hero Section -->
    <section id="home" class="hero">
        <div class="container">
            <div class="hero-content">
                <div class="hero-text">
                    <h1>Hi, I'm Harini S</h1>
                    <p>A passionate developer creating beautiful and functional digital experiences.</p>
                    <div class="hero-buttons">
                        <a href="#contact" class="btn btn-primary">Get in touch</a>
                        <a href="#projects" class="btn btn-secondary">View my work</a>
                    </div>
                </div>
                <div class="hero-image">
                    <div class="profile-image">
                        <!-- Replace with actual image -->
                        <img src="1.jpeg" alt="Harini S">
                    </div>
                </div>
            </div>
        </div>
    </section>
    <!-- About Section -->
    <section id="about" class="about">
        <div class="container">
            <div class="section-header">
                <h2>About Me</h2>
                <p>Get to know more about my background and experience</p>
            </div>
            <div class="about-cards">
                <div class="card">
                    <div class="card-header">
                        <h3>My Story</h3>
                        <p class="subtitle">A brief introduction</p>
                    </div>
                    <div class="card-content">
                        <p>
                            I am Harini S, a passionate developer with a keen eye for design and a love for creating 
                            intuitive user experiences. My journey in tech began with a curiosity about how digital 
                            products are built, which led me to pursue formal education and hands-on experience in the field.
                        </p>
                        <p>
                            I believe in the power of technology to solve real-world problems and enhance people's lives. 
                            My approach combines technical expertise with creative thinking to deliver solutions that are 
                            both functional and aesthetically pleasing.
                        </p>
                    </div>
                </div>
                <div class="card">
                    <div class="card-header">
                        <h3>Education & Experience</h3>
                        <p class="subtitle">My professional journey</p>
                    </div>
                    <div class="card-content">
                        <div class="experience-item">
                            <h4>Bachelor of Computer Science</h4>
                            <p class="date">University Name, 2018-2022</p>
                        </div>
                        <div class="experience-item">
                            <h4>Frontend Developer</h4>
                            <p class="date">Company Name, 2022-Present</p>
                            <p>
                                Developing responsive web applications, collaborating with design and backend teams, 
                                and implementing modern frontend technologies.
                            </p>
                        </div>
                        <div class="experience-item">
                            <h4>Web Design Intern</h4>
                            <p class="date">Company Name, 2021-2022</p>
                            <p>
                                Assisted in designing and developing websites, learned industry best practices, 
                                and contributed to client projects.
                            </p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <!-- Skills Section -->
    <section id="skills" class="skills">
        <div class="container">
            <div class="section-header">
                <h2>My Skills</h2>
                <p>Expertise and technologies I work with</p>
            </div>
            <div class="skills-cards">
                <div class="skill-card">
                    <div class="skill-icon">
                        <i class="fas fa-code"></i>
                    </div>
                    <h3>Frontend Development</h3>
                    <p>Creating responsive and interactive user interfaces with modern frameworks like React, Next.js, and Vue.</p>
                </div>
                <div class="skill-card">
                    <div class="skill-icon">
                        <i class="fas fa-database"></i>
                    </div>
                    <h3>Backend Development</h3>
                    <p>Building robust server-side applications with Node.js, Express, and database technologies.</p>
                </div>
                <div class="skill-card">
                    <div class="skill-icon">
                        <i class="fas fa-palette"></i>
                    </div>
                    <h3>UI/UX Design</h3>
                    <p>Designing intuitive and visually appealing user experiences with tools like Figma and Adobe XD.</p>
                </div>
                <div class="skill-card">
                    <div class="skill-icon">
                        <i class="fas fa-laptop-code"></i>
                    </div>
                    <h3>Full-Stack Development</h3>
                    <p>End-to-end application development from database design to frontend implementation.</p>
                </div>
                <div class="skill-card">
                    <div class="skill-icon">
                        <i class="fas fa-mobile-alt"></i>
                    </div>
                    <h3>Responsive Design</h3>
                    <p>Creating websites that work seamlessly across all devices and screen sizes.</p>
                </div>
                <div class="skill-card">
                    <div class="skill-icon">
                        <i class="fas fa-lightbulb"></i>
                    </div>
                    <h3>Creative Problem Solving</h3>
                    <p>Finding innovative solutions to complex technical and design challenges.</p>
                </div>
            </div>
        </div>
    </section>
    <!-- Projects Section -->
    <section id="projects" class="projects">
        <div class="container">
            <div class="section-header">
                <h2>My Projects</h2>
                <p>A selection of my recent work and personal projects</p>
            </div>
            <div class="projects-grid">
                <div class="project-card">
                    <div class="project-image">
                        <img src="https://placehold.co/600x400" alt="E-Commerce Platform">
                    </div>
                    <div class="project-content">
                        <h3>E-Commerce Platform</h3>
                        <p>
                            A full-featured online shopping platform with product catalog, cart functionality, 
                            and payment integration.
                        </p>
                        <div class="project-tags">
                            <span>React</span>
                            <span>Node.js</span>
                            <span>MongoDB</span>
                            <span>Stripe</span>
                        </div>
                        <div class="project-links">
                            <a href="#" class="btn btn-small btn-secondary">
                                <i class="fab fa-github"></i> Code
                            </a>
                            <a href="#" class="btn btn-small btn-primary">
                                <i class="fas fa-external-link-alt"></i> Live Demo
                            </a>
                        </div>
                    </div>
                </div>
                <div class="project-card">
                    <div class="project-image">
                        <img src="https://placehold.co/600x400" alt="Task Management App">
                    </div>
                    <div class="project-content">
                        <h3>Task Management App</h3>
                        <p>
                            A productivity application for managing tasks, projects, and team collaboration with real-time updates.
                        </p>
                        <div class="project-tags">
                            <span>Next.js</span>
                            <span>Firebase</span>
                            <span>Tailwind CSS</span>
                            <span>Redux</span>
                        </div>
                        <div class="project-links">
                            <a href="#" class="btn btn-small btn-secondary">
                                <i class="fab fa-github"></i> Code
                            </a>
                            <a href="#" class="btn btn-small btn-primary">
                                <i class="fas fa-external-link-alt"></i> Live Demo
                            </a>
                        </div>
                    </div>
                </div>
                <div class="project-card">
                    <div class="project-image">
                        <img src="https://placehold.co/600x400" alt="Portfolio Website">
                    </div>
                    <div class="project-content">
                        <h3>Portfolio Website</h3>
                        <p>
                            A personal portfolio website showcasing projects, skills, and professional experience with a modern design.
                        </p>
                        <div class="project-tags">
                            <span>HTML/CSS</span>
                            <span>JavaScript</span>
                            <span>GSAP</span>
                            <span>Responsive Design</span>
                        </div>
                        <div class="project-links">
                            <a href="#" class="btn btn-small btn-secondary">
                                <i class="fab fa-github"></i> Code
                            </a>
                            <a href="#" class="btn btn-small btn-primary">
                                <i class="fas fa-external-link-alt"></i> Live Demo
                            </a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <!-- Contact Section -->
    <section id="contact" class="contact">
        <div class="container">
            <div class="section-header">
                <h2>Get In Touch</h2>
                <p>Have a project in mind or want to collaborate? Feel free to reach out!</p>
            </div>
            <div class="contact-container">
                <div class="contact-info">
                    <div class="contact-card">
                        <div class="contact-icon">
                            <i class="fas fa-envelope"></i>
                        </div>
                        <h3>Email</h3>
                        <p><a href="mailto:harinisaravanan268@gmail.com">harinisaravanan268@gmail.com</a></p>
                    </div>
                    <div class="contact-card">
                        <div class="contact-icon">
                            <i class="fas fa-phone"></i>
                        </div>
                        <h3>Phone</h3>
                        <p><a href="tel:+1234567890">+1 (234) 567-890</a></p>
                    </div>
                    <div class="contact-card">
                        <div class="contact-icon">
                            <i class="fas fa-map-marker-alt"></i>
                        </div>
                        <h3>Location</h3>
                        <p>San Francisco, California</p>
                    </div>
                </div>
                <div class="contact-form-container">
                    <form class="contact-form">
                        <h3>Send Me a Message</h3>
                        <p>Fill out the form below and I'll get back to you as soon as possible.</p>
                        <div class="form-group">
                            <label for="name">Name</label>
                            <input type="text" id="name" name="name" placeholder="Your name" required>
                        </div>
                        <div class="form-group">
                            <label for="email">Email</label>
                            <input type="email" id="email" name="email" placeholder="Your email" required>
                        </div>
                        <div class="form-group">
                            <label for="subject">Subject</label>
                            <input type="text" id="subject" name="subject" placeholder="Subject" required>
                        </div>
                        <div class="form-group">
                            <label for="message">Message</label>
                            <textarea id="message" name="message" placeholder="Your message" rows="4" required></textarea>
                        </div>
                        <button type="submit" class="btn btn-primary btn-full">Send Message</button>
                    </form>
                </div>
            </div>
        </div>
    </section>
    <!-- Footer -->
    <footer>
        <div class="container">
            <div class="footer-content">
                <div class="copyright">
                    <p>&copy; <span id="current-year">2023</span> Harini S. All rights reserved.</p>
                </div>
                <div class="social-links">
                    <a href="#" aria-label="Github"><i class="fab fa-github"></i></a>
                    <a href="#" aria-label="LinkedIn"><i class="fab fa-linkedin"></i></a>
                    <a href="#" aria-label="Twitter"><i class="fab fa-twitter"></i></a>
                    <a href="#" aria-label="Instagram"><i class="fab fa-instagram"></i></a>
                    <a href="#" aria-label="Facebook"><i class="fab fa-facebook"></i></a>
                </div>
            </div>
        </div>
    </footer>
    <script>
        // Simple script to update the year in the footer
        document.getElementById('current-year').textContent = new Date().getFullYear();
    </script>
</body>
</html>
```
### style.css:
```
/* Variables */
:root {
    --primary-color: #7c3aed;
    --primary-color-light: #8b5cf6;
    --secondary-color: #f3f4f6;
    --text-color: #1f2937;
    --text-color-light: #6b7280;
    --background-color: #ffffff;
    --background-alt: #f9fafb;
    --card-bg-color: #ffffff;
    --border-color: #e5e7eb;
    --shadow-sm: 0 1px 2px 0 rgba(0, 0, 0, 0.05);
    --shadow-md: 0 4px 6px -1px rgba(0, 0, 0, 0.1), 0 2px 4px -1px rgba(0, 0, 0, 0.06);
    --shadow-lg: 0 10px 15px -3px rgba(0, 0, 0, 0.1), 0 4px 6px -2px rgba(0, 0, 0, 0.05);
    --border-radius: 0.5rem;
    --border-radius-sm: 0.25rem;
    --transition: all 0.3s ease;
    --max-width: 1200px;
    --header-height: 64px;
  }
  
  /* Reset & Base Styles */
  * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }
  
  html {
    scroll-behavior: smooth;
  }
  
  body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    color: var(--text-color);
    line-height: 1.6;
    background-color: var(--background-color);
    min-height: 100vh;
  }
  
  img {
    max-width: 100%;
    height: auto;
    display: block;
  }
  
  a {
    text-decoration: none;
    color: inherit;
    transition: var(--transition);
  }
  
  ul {
    list-style: none;
  }
  
  .container {
    max-width: var(--max-width);
    margin: 0 auto;
    padding: 0 1.5rem;
    width: 100%;
  }
  
  section {
    padding: 5rem 0;
  }
  
  .section-header {
    text-align: center;
    margin-bottom: 3rem;
  }
  
  .section-header h2 {
    font-size: 2.5rem;
    margin-bottom: 0.5rem;
    position: relative;
    display: inline-block;
  }
  
  .section-header p {
    color: var(--text-color-light);
    max-width: 600px;
    margin: 0 auto;
  }
  
  /* Buttons */
  .btn {
    display: inline-flex;
    align-items: center;
    justify-content: center;
    padding: 0.75rem 1.5rem;
    border-radius: var(--border-radius);
    font-weight: 600;
    transition: var(--transition);
    cursor: pointer;
    border: none;
    outline: none;
  }
  
  .btn-small {
    padding: 0.5rem 1rem;
    font-size: 0.875rem;
  }
  
  .btn-primary {
    background-color: var(--primary-color);
    color: white;
  }
  
  .btn-primary:hover {
    background-color: var(--primary-color-light);
  }
  
  .btn-secondary {
    background-color: var(--secondary-color);
    color: var(--text-color);
  }
  
  .btn-secondary:hover {
    background-color: #e5e7eb;
  }
  
  .btn-full {
    width: 100%;
  }
  
  /* Card Styles */
  .card {
    background-color: var(--card-bg-color);
    border-radius: var(--border-radius);
    box-shadow: var(--shadow-md);
    padding: 1.5rem;
    transition: var(--transition);
  }
  
  .card:hover {
    box-shadow: var(--shadow-lg);
    transform: translateY(-5px);
  }
  
  .card-header {
    margin-bottom: 1rem;
  }
  
  .card-header h3 {
    margin-bottom: 0.5rem;
    font-size: 1.25rem;
  }
  
  .subtitle {
    color: var(--text-color-light);
    font-size: 0.875rem;
  }
  
  /* Header / Navigation */
  header {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    background-color: rgba(255, 255, 255, 0.95);
    backdrop-filter: blur(10px);
    z-index: 1000;
    box-shadow: var(--shadow-sm);
    height: var(--header-height);
  }
  
  header .container {
    display: flex;
    justify-content: space-between;
    align-items: center;
    height: 100%;
  }
  
  .logo h1 {
    font-size: 1.5rem;
    font-weight: 700;
    color: var(--text-color);
  }
  
  nav ul {
    display: flex;
    gap: 1.5rem;
  }
  
  nav a {
    font-weight: 500;
    padding: 0.5rem 0;
    position: relative;
  }
  
  nav a:hover {
    color: var(--primary-color);
  }
  
  nav a::after {
    content: '';
    position: absolute;
    bottom: 0;
    left: 0;
    width: 0;
    height: 2px;
    background-color: var(--primary-color);
    transition: var(--transition);
  }
  
  nav a:hover::after {
    width: 100%;
  }
  
  .nav-toggle {
    display: none;
  }
  
  .nav-toggle-label {
    display: none;
    cursor: pointer;
  }
  
  /* Hero Section */
  .hero {
    padding: calc(5rem + var(--header-height)) 0 5rem;
    background-color: var(--background-color);
  }
  
  .hero-content {
    display: flex;
    align-items: center;
    gap: 3rem;
  }
  
  .hero-text {
    flex: 1;
  }
  
  .hero-text h1 {
    font-size: 3rem;
    line-height: 1.2;
    margin-bottom: 1rem;
  }
  
  .hero-text p {
    font-size: 1.125rem;
    color: var(--text-color-light);
    margin-bottom: 2rem;
    max-width: 600px;
  }
  
  .hero-buttons {
    display: flex;
    gap: 1rem;
  }
  
  .hero-image {
    flex: 1;
    display: flex;
    justify-content: center;
  }
  
  .profile-image {
    width: 280px;
    height: 280px;
    border-radius: 50%;
    overflow: hidden;
    border: 4px solid var(--background-color);
    box-shadow: var(--shadow-lg);
  }
  
  /* About Section */
  .about {
    background-color: var(--background-alt);
  }
  
  .about-cards {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 2rem;
  }
  
  .experience-item {
    margin-bottom: 1.5rem;
  }
  
  .experience-item h4 {
    font-size: 1.125rem;
    margin-bottom: 0.25rem;
  }
  
  .date {
    font-size: 0.875rem;
    color: var(--text-color-light);
    margin-bottom: 0.5rem;
  }
  
  /* Skills Section */
  .skills-cards {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
    gap: 1.5rem;
  }
  
  .skill-card {
    background-color: var(--card-bg-color);
    border-radius: var(--border-radius);
    padding: 1.5rem;
    text-align: center;
    box-shadow: var(--shadow-md);
    transition: var(--transition);
  }
  
  .skill-card:hover {
    box-shadow: var(--shadow-lg);
    transform: translateY(-5px);
  }
  
  .skill-icon {
    font-size: 2.5rem;
    color: var(--primary-color);
    margin-bottom: 1rem;
  }
  
  .skill-card h3 {
    margin-bottom: 0.75rem;
    font-size: 1.25rem;
  }
  
  .skill-card p {
    color: var(--text-color-light);
    font-size: 0.95rem;
  }
  
  /* Projects Section */
  .projects {
    background-color: var(--background-alt);
  }
  
  .projects-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(320px, 1fr));
    gap: 2rem;
  }
  
  .project-card {
    background-color: var(--card-bg-color);
    border-radius: var(--border-radius);
    overflow: hidden;
    box-shadow: var(--shadow-md);
    transition: var(--transition);
  }
  
  .project-card:hover {
    box-shadow: var(--shadow-lg);
    transform: translateY(-5px);
  }
  
  .project-image {
    height: 200px;
    overflow: hidden;
  }
  
  .project-image img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    transition: transform 0.5s ease;
  }
  
  .project-card:hover .project-image img {
    transform: scale(1.05);
  }
  
  .project-content {
    padding: 1.5rem;
  }
  
  .project-content h3 {
    margin-bottom: 0.75rem;
    font-size: 1.25rem;
  }
  
  .project-content p {
    color: var(--text-color-light);
    margin-bottom: 1rem;
    font-size: 0.95rem;
  }
  
  .project-tags {
    display: flex;
    flex-wrap: wrap;
    gap: 0.5rem;
    margin-bottom: 1.5rem;
  }
  
  .project-tags span {
    background-color: rgba(124, 58, 237, 0.1);
    color: var(--primary-color);
    padding: 0.25rem 0.75rem;
    border-radius: 999px;
    font-size: 0.75rem;
    font-weight: 500;
  }
  
  .project-links {
    display: flex;
    justify-content: space-between;
  }
  
  /* Contact Section */
  .contact-container {
    display: grid;
    grid-template-columns: 1fr 2fr;
    gap: 2rem;
  }
  
  .contact-info {
    display: flex;
    flex-direction: column;
    gap: 1.5rem;
  }
  
  .contact-card {
    background-color: var(--card-bg-color);
    border-radius: var(--border-radius);
    padding: 1.5rem;
    box-shadow: var(--shadow-md);
    transition: var(--transition);
  }
  
  .contact-card:hover {
    box-shadow: var(--shadow-lg);
    transform: translateY(-5px);
  }
  
  .contact-icon {
    font-size: 1.5rem;
    color: var(--primary-color);
    margin-bottom: 0.75rem;
  }
  
  .contact-card h3 {
    margin-bottom: 0.5rem;
    font-size: 1.125rem;
  }
  
  .contact-card a:hover {
    color: var(--primary-color);
  }
  
  .contact-form-container {
    background-color: var(--card-bg-color);
    border-radius: var(--border-radius);
    box-shadow: var(--shadow-md);
    padding: 2rem;
  }
  
  .contact-form h3 {
    margin-bottom: 0.5rem;
    font-size: 1.25rem;
  }
  
  .contact-form > p {
    color: var(--text-color-light);
    margin-bottom: 1.5rem;
    font-size: 0.95rem;
  }
  
  .form-group {
    margin-bottom: 1.25rem;
  }
  
  .form-group label {
    display: block;
    margin-bottom: 0.5rem;
    font-weight: 500;
  }
  
  .form-group input,
  .form-group textarea {
    width: 100%;
    padding: 0.75rem;
    border: 1px solid var(--border-color);
    border-radius: var(--border-radius-sm);
    font-family: inherit;
    font-size: 1rem;
    transition: var(--transition);
  }
  
  .form-group input:focus,
  .form-group textarea:focus {
    outline: none;
    border-color: var(--primary-color);
    box-shadow: 0 0 0 2px rgba(124, 58, 237, 0.2);
  }
  
  /* Footer */
  footer {
    background-color: var(--background-color);
    border-top: 1px solid var(--border-color);
    padding: 2rem 0;
  }
  
  .footer-content {
    display: flex;
    align-items: center;
    justify-content: space-between;
  }
  
  .copyright {
    font-size: 0.875rem;
    color: var(--text-color-light);
  }
  
  .social-links {
    display: flex;
    gap: 1rem;
  }
  
  .social-links a {
    display: flex;
    align-items: center;
    justify-content: center;
    width: 36px;
    height: 36px;
    border-radius: 50%;
    background-color: var(--secondary-color);
    color: var(--text-color);
    transition: var(--transition);
  }
  
  .social-links a:hover {
    background-color: var(--primary-color);
    color: white;
    transform: translateY(-3px);
  }
  
  /* Mobile Menu */
  @media (max-width: 768px) {
    .nav-toggle-label {
      display: block;
      position: relative;
      height: 24px;
      width: 30px;
    }
  
    .nav-toggle-label span,
    .nav-toggle-label span::before,
    .nav-toggle-label span::after {
      display: block;
      position: absolute;
      height: 3px;
      width: 100%;
      border-radius: 3px;
      background-color: var(--text-color);
      transition: all 0.3s ease;
    }
  
    .nav-toggle-label span {
      top: 50%;
      transform: translateY(-50%);
    }
  
    .nav-toggle-label span::before {
      content: '';
      top: -8px;
    }
  
    .nav-toggle-label span::after {
      content: '';
      bottom: -8px;
    }
  
    nav {
      position: absolute;
      top: var(--header-height);
      left: 0;
      width: 100%;
      background-color: var(--background-color);
      box-shadow: var(--shadow-md);
      padding: 1.5rem;
      transform: translateY(-100%);
      opacity: 0;
      transition: all 0.3s ease;
      pointer-events: none;
    }
  
    .nav-toggle:checked ~ nav {
      transform: translateY(0);
      opacity: 1;
      pointer-events: auto;
    }
  
    .nav-toggle:checked ~ .nav-toggle-label span {
      background-color: transparent;
    }
  
    .nav-toggle:checked ~ .nav-toggle-label span::before {
      transform: rotate(45deg) translate(5px, 5px);
    }
  
    .nav-toggle:checked ~ .nav-toggle-label span::after {
      transform: rotate(-45deg) translate(6px, -5px);
    }
  
    nav ul {
      flex-direction: column;
      gap: 1rem;
    }
  
    nav a {
      display: block;
      padding: 0.5rem 0;
    }
  }
  
  /* Responsive Styles */
  @media (max-width: 992px) {
    .contact-container {
      grid-template-columns: 1fr;
    }
  
    .contact-info {
      flex-direction: row;
      flex-wrap: wrap;
    }
  
    .contact-card {
      flex: 1;
      min-width: 200px;
    }
  }
  
  @media (max-width: 768px) {
    .hero-content {
      flex-direction: column-reverse;
      text-align: center;
      gap: 2rem;
    }
  
    .hero-text h1 {
      font-size: 2.5rem;
    }
  
    .hero-buttons {
      justify-content: center;
    }
  
    .section-header h2 {
      font-size: 2rem;
    }
    
    .profile-image {
      width: 220px;
      height: 220px;
    }
  }
  
  @media (max-width: 576px) {
    .about-cards, 
    .skills-cards, 
    .projects-grid {
      grid-template-columns: 1fr;
    }
  
    .contact-info {
      flex-direction: column;
    }
  
    .footer-content {
      flex-direction: column;
      gap: 1rem;
    }
  
    .hero-text h1 {
      font-size: 2rem;
    }
  
    .section-header h2 {
      font-size: 1.75rem;
    }
  }
  
  /* Utility Classes */
  .text-center {
    text-align: center;
  }
  
  .mb-1 {
    margin-bottom: 0.5rem;
  }
  
  .mb-2 {
    margin-bottom: 1rem;
  }
  
  .mb-3 {
    margin-bottom: 1.5rem;
  }
  
  .mb-4 {
    margin-bottom: 2rem;
  }
```
## OUTPUT


## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
