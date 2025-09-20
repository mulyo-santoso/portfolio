I'll create a complete, elegant portfolio website for Mulyo Santoso. Here's the full code:

## HTML (index.html)

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mulyo Santoso - Data Engineer & Data Scientist</title>
    <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Montserrat:wght@300;400;600;700&family=Open+Sans:wght@300;400;600&display=swap">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <link rel="stylesheet" href="styles.css">
    <link rel="icon" type="image/x-icon" href="/favicon.ico">
    <meta name="description" content="Mulyo Santoso - Data Engineer & Data Scientist specializing in ELT pipelines, cloud data engineering, and data wrangling">
</head>
<body>
    <!-- Header/Navbar -->
    <header class="header">
        <nav class="navbar" role="navigation" aria-label="Main navigation">
            <div class="nav-container">
                <div class="logo">
                    <a href="#home" aria-label="Home">MS Portfolio</a>
                </div>
                <ul class="nav-menu" id="nav-menu">
                    <li><a href="#home" class="nav-link">Home</a></li>
                    <li><a href="#about" class="nav-link">About</a></li>
                    <li><a href="#projects" class="nav-link">Projects</a></li>
                    <li><a href="#skills" class="nav-link">Skills</a></li>
                    <li><a href="#contact" class="nav-link">Contact</a></li>
                </ul>
                <div class="hamburger" id="hamburger" aria-label="Toggle menu" role="button" tabindex="0">
                    <span></span>
                    <span></span>
                    <span></span>
                </div>
            </div>
        </nav>
    </header>

    <!-- Hero Section -->
    <section id="home" class="hero">
        <div class="hero-container">
            <div class="hero-content">
                <h1 class="hero-title">Data Engineer & Data Scientist</h1>
                <p class="hero-subtitle">Building scalable data pipelines and transforming raw data into actionable insights</p>
                <a href="#projects" class="cta-button" aria-label="View my work">View My Work</a>
            </div>
            <div class="hero-visual">
                <div class="hero-pattern"></div>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="about">
        <div class="container">
            <h2 class="section-title">About Me</h2>
            <div class="about-content">
                <div class="about-image">
                    <img src="mulyo.jpg" alt="Mulyo Santoso - Data Engineer" loading="lazy">
                </div>
                <div class="about-text">
                    <p>I'm a passionate Data Engineer with expertise in building robust ELT pipelines and cloud data architectures. I specialize in transforming complex data challenges into scalable solutions that drive business value.</p>
                    <p>With hands-on experience in modern data stack technologies, I create efficient data workflows that enable data-driven decision making across organizations.</p>
                    <div class="highlights">
                        <h3>Key Highlights</h3>
                        <ul>
                            <li><i class="fas fa-check"></i> 5+ years in data engineering and analytics</li>
                            <li><i class="fas fa-check"></i> Expertise in cloud platforms (AWS, Snowflake)</li>
                            <li><i class="fas fa-check"></i> Orchestration with Airflow & Kubernetes</li>
                            <li><i class="fas fa-check"></i> Infrastructure as Code with Terraform</li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Projects Section -->
    <section id="projects" class="projects">
        <div class="container">
            <h2 class="section-title">Featured Projects</h2>
            <div class="projects-grid" role="region" aria-label="Project showcase">
                <article class="project-card" tabindex="0">
                    <div class="project-image">
                        <img src="k8s.png" alt="ELT Pipeline using Airflow and PostgreSQL in Kubernetes" loading="lazy">
                        <div class="project-overlay">
                            <a href="https://github.com/MSantoso52/K8S_ELT_Pipeline" target="_blank" class="project-link" aria-label="View project on GitHub">
                                <i class="fab fa-github"></i>
                            </a>
                        </div>
                    </div>
                    <div class="project-content">
                        <h3>ELT Pipeline using Airflow and PostgreSQL in Kubernetes</h3>
                        <p>Kubernetes orchestration for scalable ELT pipelines using Apache Airflow and PostgreSQL database.</p>
                        <div class="tech-stack">
                            <span class="tech-badge">Airflow</span>
                            <span class="tech-badge">PostgreSQL</span>
                            <span class="tech-badge">Kubernetes</span>
                            <span class="tech-badge">Python</span>
                        </div>
                    </div>
                </article>

                <article class="project-card" tabindex="0">
                    <div class="project-image">
                        <img src="terraform_workflow.png" alt="ELT Pipeline using AWS Glue with Terraform" loading="lazy">
                        <div class="project-overlay">
                            <a href="https://github.com/MSantoso52/Terraform_AWS_Glue_ELT_Pipeline" target="_blank" class="project-link" aria-label="View project on GitHub">
                                <i class="fab fa-github"></i>
                            </a>
                        </div>
                    </div>
                    <div class="project-content">
                        <h3>ELT Pipeline using AWS Glue with Terraform</h3>
                        <p>Infrastructure as Code implementation for AWS Glue ETL pipelines using Terraform automation.</p>
                        <div class="tech-stack">
                            <span class="tech-badge">Terraform</span>
                            <span class="tech-badge">AWS S3</span>
                            <span class="tech-badge">AWS Glue</span>
                            <span class="tech-badge">Python</span>
                        </div>
                    </div>
                </article>

                <article class="project-card" tabindex="0">
                    <div class="project-image">
                        <img src="elt_snowflake_dbt.png" alt="Data Pipeline on Snowflake with DBT" loading="lazy">
                        <div class="project-overlay">
                            <a href="https://github.com/MSantoso52/elt_snowflake_dbt" target="_blank" class="project-link" aria-label="View project on GitHub">
                                <i class="fab fa-github"></i>
                            </a>
                        </div>
                    </div>
                    <div class="project-content">
                        <h3>Building & Maintaining Data Pipeline on Snowflake</h3>
                        <p>Modern data transformation pipelines using DBT on Snowflake cloud data warehouse.</p>
                        <div class="tech-stack">
                            <span class="tech-badge">Snowflake</span>
                            <span class="tech-badge">DBT</span>
                            <span class="tech-badge">ELT</span>
                        </div>
                    </div>
                </article>

                <article class="project-card" tabindex="0">
                    <div class="project-image">
                        <img src="github_action.png" alt="CI/CD ELT Pipeline with GitHub Actions" loading="lazy">
                        <div class="project-overlay">
                            <a href="https://github.com/MSantoso52/GitHub-CI-CD-ELT-Pipeline" target="_blank" class="project-link" aria-label="View project on GitHub">
                                <i class="fab fa-github"></i>
                            </a>
                        </div>
                    </div>
                    <div class="project-content">
                        <h3>CI/CD ELT Pipeline using GitHub Actions</h3>
                        <p>Automated CI/CD workflows for Airflow DAGs using GitHub Actions and continuous deployment.</p>
                        <div class="tech-stack">
                            <span class="tech-badge">GitHub Actions</span>
                            <span class="tech-badge">ELT</span>
                            <span class="tech-badge">Airflow</span>
                        </div>
                    </div>
                </article>

                <article class="project-card" tabindex="0">
                    <div class="project-image">
                        <img src="mongodb_data_wrangling.png" alt="Data Wrangling on MongoDB" loading="lazy">
                        <div class="project-overlay">
                            <a href="https://github.com/MSantoso52/MongoDB_Data_Wrangling" target="_blank" class="project-link" aria-label="View project on GitHub">
                                <i class="fab fa-github"></i>
                            </a>
                        </div>
                    </div>
                    <div class="project-content">
                        <h3>Data Wrangling on MongoDB</h3>
                        <p>Comprehensive data wrangling and transformation workflows using MongoDB and JupyterLab.</p>
                        <div class="tech-stack">
                            <span class="tech-badge">MongoDB</span>
                            <span class="tech-badge">Data Wrangling</span>
                            <span class="tech-badge">JupyterLab</span>
                        </div>
                    </div>
                </article>

                <article class="project-card" tabindex="0">
                    <div class="project-image">
                        <img src="dbt_snowflake.png" alt="Data Quality & Reliability on Snowflake" loading="lazy">
                        <div class="project-overlay">
                            <a href="https://github.com/MSantoso52/dbt_on_snowflake" target="_blank" class="project-link" aria-label="View project on GitHub">
                                <i class="fab fa-github"></i>
                            </a>
                        </div>
                    </div>
                    <div class="project-content">
                        <h3>Ensuring Data Quality & Reliability on Snowflake</h3>
                        <p>DBT implementation for data pipeline management and quality assurance on Snowflake.</p>
                        <div class="tech-stack">
                            <span class="tech-badge">Snowflake</span>
                            <span class="tech-badge">DBT</span>
                            <span class="tech-badge">ELT</span>
                        </div>
                    </div>
                </article>
            </div>
        </div>
    </section>

    <!-- Skills Section -->
    <section id="skills" class="skills">
        <div class="container">
            <h2 class="section-title">Technical Skills</h2>
            <div class="skills-grid">
                <div class="skill-category">
                    <h3><i class="fas fa-database"></i> Databases</h3>
                    <div class="skill-items">
                        <div class="skill-item">
                            <i class="fab fa-python"></i>
                            <span>Python</span>
                            <div class="skill-bar">
                                <div class="skill-progress" data-width="95"></div>
                            </div>
                        </div>
                        <div class="skill-item">
                            <i class="fas fa-server"></i>
                            <span>PostgreSQL</span>
                            <div class="skill-bar">
                                <div class="skill-progress" data-width="90"></div>
                            </div>
                        </div>
                        <div class="skill-item">
                            <i class="fas fa-database"></i>
                            <span>MongoDB</span>
                            <div class="skill-bar">
                                <div class="skill-progress" data-width="85"></div>
                            </div>
                        </div>
                        <div class="skill-item">
                            <i class="fas fa-snowflake"></i>
                            <span>Snowflake</span>
                            <div class="skill-bar">
                                <div class="skill-progress" data-width="88"></div>
                            </div>
                        </div>
                    </div>
                </div>

                <div class="skill-category">
                    <h3><i class="fas fa-cogs"></i> Data Engineering</h3>
                    <div class="skill-items">
                        <div class="skill-item">
                            <i class="fas fa-project-diagram"></i>
                            <span>Apache Airflow</span>
                            <div class="skill-bar">
                                <div class="skill-progress" data-width="92"></div>
                            </div>
                        </div>
                        <div class="skill-item">
                            <i class="fas fa-fire"></i>
                            <span>Apache Spark</span>
                            <div class="skill-bar">
                                <div class="skill-progress" data-width="80"></div>
                            </div>
                        </div>
                        <div class="skill-item">
                            <i class="fas fa-broadcast-tower"></i>
                            <span>Apache Kafka</span>
                            <div class="skill-bar">
                                <div class="skill-progress" data-width="75"></div>
                            </div>
                        </div>
                        <div class="skill-item">
                            <i class="fas fa-cube"></i>
                            <span>DBT</span>
                            <div class="skill-bar">
                                <div class="skill-progress" data-width="87"></div>
                            </div>
                        </div>
                    </div>
                </div>

                <div class="skill-category">
                    <h3><i class="fas fa-cloud"></i> DevOps & Cloud</h3>
                    <div class="skill-items">
                        <div class="skill-item">
                            <i class="fab fa-docker"></i>
                            <span>Docker</span>
                            <div class="skill-bar">
                                <div class="skill-progress" data-width="85"></div>
                            </div>
                        </div>
                        <div class="skill-item">
                            <i class="fab fa-kubernetes"></i>
                            <span>Kubernetes</span>
                            <div class="skill-bar">
                                <div class="skill-progress" data-width="82"></div>
                            </div>
                        </div>
                        <div class="skill-item">
                            <i class="fas fa-code-branch"></i>
                            <span>Terraform</span>
                            <div class="skill-bar">
                                <div class="skill-progress" data-width="88"></div>
                            </div>
                        </div>
                        <div class="skill-item">
                            <i class="fab fa-aws"></i>
                            <span>AWS</span>
                            <div class="skill-bar">
                                <div class="skill-progress" data-width="85"></div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="contact">
        <div class="container">
            <h2 class="section-title">Get In Touch</h2>
            <div class="contact-content">
                <div class="contact-info">
                    <div class="contact-item">
                        <i class="fas fa-envelope"></i>
                        <div>
                            <h3>Email</h3>
                            <p><a href="mailto:mulyosantoso44@gmail.com">mulyosantoso44@gmail.com</a></p>
                        </div>
                    </div>
                    <div class="contact-item">
                        <i class="fab fa-linkedin"></i>
                        <div>
                            <h3>LinkedIn</h3>
                            <p><a href="https://www.linkedin.com/in/mulyo-santoso-b5255770" target="_blank">Mulyo Santoso</a></p>
                        </div>
                    </div>
                    <div class="contact-item">
                        <i class="fab fa-github"></i>
                        <div>
                            <h3>GitHub</h3>
                            <p><a href="https://github.com/MSantoso52" target="_blank">MSantoso52</a></p>
                        </div>
                    </div>
                </div>
                <form class="contact-form" id="contact-form" novalidate>
                    <div class="form-group">
                        <input type="text" id="name" name="name" placeholder="Your Name" required aria-label="Your name">
                        <span class="error-message" aria-live="polite"></span>
                    </div>
                    <div class="form-group">
                        <input type="email" id="email" name="email" placeholder="Your Email" required aria-label="Your email">
                        <span class="error-message" aria-live="polite"></span>
                    </div>
                    <div class="form-group">
                        <textarea id="message" name="message" placeholder="Your Message" rows="5" required aria-label="Your message"></textarea>
                        <span class="error-message" aria-live="polite"></span>
                    </div>
                    <button type="submit" class="submit-btn">
                        <span>Send Message</span>
                        <i class="fas fa-paper-plane"></i>
                    </button>
                </form>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="footer">
        <div class="container">
            <div class="footer-content">
                <div class="footer-text">
                    <p>&copy; 2025 Mulyo Santoso. All rights reserved.</p>
                </div>
                <div class="social-links">
                    <a href="https://www.linkedin.com/in/mulyo-santoso-b5255770" target="_blank" aria-label="LinkedIn" class="social-link">
                        <i class="fab fa-linkedin"></i>
                    </a>
                    <a href="https://github.com/MSantoso52" target="_blank" aria-label="GitHub" class="social-link">
                        <i class="fab fa-github"></i>
                    </a>
                    <a href="mailto:mulyosantoso44@gmail.com" aria-label="Email" class="social-link">
                        <i class="fas fa-envelope"></i>
                    </a>
                </div>
            </div>
            <button class="back-to-top" id="back-to-top" aria-label="Back to top">
                <i class="fas fa-chevron-up"></i>
            </button>
        </div>
    </footer>

    <script src="script.js"></script>
</body>
</html>
```

## CSS (styles.css)

```css
/* Reset and Base Styles */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Open Sans', sans-serif;
    line-height: 1.6;
    color: #333;
    overflow-x: hidden;
}

h1, h2, h3, h4, h5, h6 {
    font-family: 'Montserrat', sans-serif;
    font-weight: 600;
    color: #2c3e50;
}

.container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 20px;
}

/* Header/Navbar */
.header {
    position: fixed;
    top: 0;
    width: 100%;
    background: rgba(255, 255, 255, 0.95);
    backdrop-filter: blur(10px);
    z-index: 1000;
    transition: all 0.3s ease;
    box-shadow: 0 2px 20px rgba(0, 0, 0, 0.1);
}

.nav-container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 20px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    height: 70px;
}

.logo a {
    font-family: 'Montserrat', sans-serif;
    font-size: 1.5rem;
    font-weight: 700;
    color: #3498db;
    text-decoration: none;
    transition: color 0.3s ease;
}

.logo a:hover {
    color: #2980b9;
}

.nav-menu {
    display: flex;
    list-style: none;
    gap: 2rem;
}

.nav-link {
    text-decoration: none;
    color: #2c3e50;
    font-weight: 500;
    transition: color 0.3s ease;
    position: relative;
}

.nav-link:hover,
.nav-link.active {
    color: #3498db;
}

.nav-link::after {
    content: '';
    position: absolute;
    width: 0;
    height: 2px;
    bottom: -5px;
    left: 0;
    background-color: #3498db;
    transition: width 0.3s ease;
}

.nav-link:hover::after,
.nav-link.active::after {
    width: 100%;
}

.hamburger {
    display: none;
    flex-direction: column;
    cursor: pointer;
    padding: 5px;
}

.hamburger span {
    width: 25px;
    height: 3px;
    background: #2c3e50;
    margin: 3px 0;
    transition: 0.3s;
    border-radius: 2px;
}

/* Hero Section */
.hero {
    min-height: 100vh;
    display: flex;
    align-items: center;
    background: linear-gradient(135deg, #f5f7fa 0%, #c3cfe2 100%);
    position: relative;
    overflow: hidden;
}

.hero::before {
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    background: url('data:image/svg+xml,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 100 100"><defs><pattern id="grain" width="100" height="100" patternUnits="userSpaceOnUse"><circle cx="25" cy="25" r="1" fill="rgba(255,255,255,0.1)"/><circle cx="75" cy="75" r="1" fill="rgba(255,255,255,0.05)"/></pattern></defs><rect width="100" height="100" fill="url(%23grain)"/></svg>');
    pointer-events: none;
}

.hero-container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 20px;
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 4rem;
    align-items: center;
    position: relative;
    z-index: 1;
}

.hero-title {
    font-size: clamp(2.5rem, 5vw, 4rem);
    margin-bottom: 1rem;
    color: #2c3e50;
    opacity: 0;
    transform: translateY(30px);
    animation: fadeInUp 1s ease forwards;
}

.hero-subtitle {
    font-size: 1.25rem;
    color: #7f8c8d;
    margin-bottom: 2rem;
    max-width: 500px;
    opacity: 0;
    transform: translateY(30px);
    animation: fadeInUp 1s ease 0.2s forwards;
}

.cta-button {
    display: inline-flex;
    align-items: center;
    gap: 0.5rem;
    background: linear-gradient(135deg, #3498db, #2980b9);
    color: white;
    padding: 1rem 2rem;
    text-decoration: none;
    border-radius: 50px;
    font-weight: 600;
    transition: all 0.3s ease;
    box-shadow: 0 4px 15px rgba(52, 152, 219, 0.3);
    opacity: 0;
    transform: translateY(30px);
    animation: fadeInUp 1s ease 0.4s forwards;
}

.cta-button:hover {
    transform: translateY(-2px);
    box-shadow: 0 8px 25px rgba(52, 152, 219, 0.4);
    background: linear-gradient(135deg, #2980b9, #3498db);
}

.hero-visual {
    display: flex;
    justify-content: center;
    align-items: center;
}

.hero-pattern {
    width: 400px;
    height: 400px;
    background: 
        radial-gradient(circle at 20% 80%, rgba(52, 152, 219, 0.1) 0%, transparent 50%),
        radial-gradient(circle at 80% 20%, rgba(52, 152, 219, 0.05) 0%, transparent 50%),
        linear-gradient(135deg, transparent 40%, rgba(52, 152, 219, 0.02) 50%, transparent 60%);
    border-radius: 50%;
    opacity: 0.6;
}

/* About Section */
.about {
    padding: 100px 0;
    background: #fff;
}

.section-title {
    font-size: 2.5rem;
    text-align: center;
    margin-bottom: 3rem;
    position: relative;
}

.section-title::after {
    content: '';
    position: absolute;
    bottom: -10px;
    left: 50%;
    transform: translateX(-50%);
    width: 60px;
    height: 3px;
    background: #3498db;
}

.about-content {
    display: grid;
    grid-template-columns: 1fr 2fr;
    gap: 4rem;
    align-items: center;
}

.about-image {
    position: relative;
}

.about-image img {
    width: 100%;
    height: 350px;
    object-fit: cover;
    border-radius: 20px;
    box-shadow: 0 20px 40px rgba(0, 0, 0, 0.1);
    transition: transform 0.3s ease;
}

.about-image:hover img {
    transform: scale(1.05);
}

.about-text p {
    font-size: 1.1rem;
    color: #555;
    margin-bottom: 1.5rem;
    line-height: 1.8;
}

.highlights {
    margin-top: 2rem;
}

.highlights h3 {
    color: #2c3e50;
    margin-bottom: 1rem;
    font-size: 1.3rem;
}

.highlights ul {
    list-style: none;
}

.highlights li {
    padding: 0.5rem 0;
    color: #555;
    display: flex;
    align-items: center;
    gap: 0.5rem;
}

.highlights i {
    color: #27ae60;
    width: 15px;
}

/* Projects Section */
.projects {
    padding: 100px 0;
    background: #f8f9fa;
}

.projects-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
    gap: 2rem;
}

.project-card {
    background: white;
    border-radius: 15px;
    overflow: hidden;
    box-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
    transition: all 0.3s ease;
    cursor: pointer;
}

.project-card:hover {
    transform: translateY(-10px);
    box-shadow: 0 20px 40px rgba(0, 0, 0, 0.15);
}

.project-image {
    position: relative;
    height: 200px;
    overflow: hidden;
}

.project-image img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    transition: transform 0.3s ease;
}

.project-card:hover .project-image img {
    transform: scale(1.1);
}

.project-overlay {
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    background: rgba(52, 152, 219, 0.9);
    display: flex;
    align-items: center;
    justify-content: center;
    opacity: 0;
    transition: opacity 0.3s ease;
}

.project-card:hover .project-overlay {
    opacity: 1;
}

.project-link {
    color: white;
    font-size: 1.5rem;
    transition: transform 0.3s ease;
}

.project-link:hover {
    transform: scale(1.2);
}

.project-content {
    padding: 1.5rem;
}

.project-content h3 {
    margin-bottom: 0.5rem;
    color: #2c3e50;
    font-size: 1.2rem;
}

.project-content p {
    color: #666;
    margin-bottom: 1rem;
    line-height: 1.6;
}

.tech-stack {
    display: flex;
    flex-wrap: wrap;
    gap: 0.5rem;
}

.tech-badge {
    background: #e3f2fd;
    color: #1976d2;
    padding: 0.25rem 0.75rem;
    border-radius: 15px;
    font-size: 0.8rem;
    font-weight: 500;
}

/* Skills Section */
.skills {
    padding: 100px 0;
    background: #fff;
}

.skills-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 3rem;
}

.skill-category {
    background: #f8f9fa;
    padding: 2rem;
    border-radius: 15px;
    box-shadow: 0 5px 15px rgba(0, 0, 0, 0.05);
}

.skill-category h3 {
    display: flex;
    align-items: center;
    gap: 0.5rem;
    margin-bottom: 1.5rem;
    color: #2c3e50;
    font-size: 1.3rem;
}

.skill-items {
    display: flex;
    flex-direction: column;
    gap: 1rem;
}

.skill-item {
    display: flex;
    flex-direction: column;
    gap: 0.5rem;
}

.skill-item i {
    color: #3498db;
    font-size: 1.1rem;
    margin-right: 0.5rem;
}

.skill-bar {
    width: 100%;
    height: 8px;
    background: #e0e0e0;
    border-radius: 4px;
    overflow: hidden;
}

.skill-progress {
    height: 100%;
    background: linear-gradient(90deg, #3498db, #2980b9);
    border-radius: 4px;
    width: 0;
    transition: width 2s ease-in-out;
}

/* Contact Section */
.contact {
    padding: 100px 0;
    background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
    color: white;
}

.contact .section-title {
    color: white;
}

.contact-content {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 4rem;
    align-items: start;
}

.contact-item {
    display: flex;
    gap: 1rem;
    margin-bottom: 2rem;
    align-items: flex-start;
}

.contact-item i {
    font-size: 1.5rem;
    color: #3498db;
    margin-top: 0.2rem;
    width: 30px;
}

.contact-item h3 {
    color: white;
    margin-bottom: 0.5rem;
    font-size: 1.1rem;
}

.contact-item p {
    color: rgba(255, 255, 255, 0.9);
    margin: 0;
}

.contact-item a {
    color: rgba(255, 255, 255, 0.9);
    text-decoration: none;
    transition: color 0.3s ease;
}

.contact-item a:hover {
    color: white;
}

.contact-form {
    background: rgba(255, 255, 255, 0.1);
    padding: 2rem;
    border-radius: 15px;
    backdrop-filter: blur(10px);
    border: 1px solid rgba(255, 255, 255, 0.2);
}

.form-group {
    margin-bottom: 1.5rem;
    position: relative;
}

.form-group input,
.form-group textarea {
    width: 100%;
    padding: 1rem;
    border: none;
    border-radius: 8px;
    background: rgba(255, 255, 255, 0.9);
    color: #333;
    font-size: 1rem;
    transition: all 0.3s ease;
}

.form-group input:focus,
.form-group textarea:focus {
    outline: none;
    background: white;
    box-shadow: 0 0 0 3px rgba(52, 152, 219, 0.1);
}

.form-group textarea {
    resize: vertical;
    min-height: 120px;
}

.submit-btn {
    width: 100%;
    background: linear-gradient(135deg, #3498db, #2980b9);
    color: white;
    border: none;
    padding: 1rem;
    border-radius: 8px;
    font-size: 1rem;
    font-weight: 600;
    cursor: pointer;
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 0.5rem;
    transition: all 0.3s ease;
}

.submit-btn:hover {
    transform: translateY(-2px);
    box-shadow: 0 8px 25px rgba(52, 152, 219, 0.3);
}

.error-message {
    color: #e74c3c;
    font-size: 0.875rem;
    margin-top: 0.25rem;
    display: block;
}

/* Footer */
.footer {
    background: #2c3e50;
    color: white;
    padding: 2rem 0;
    position: relative;
}

.footer-content {
    display: flex;
    justify-content: space-between;
    align-items: center;
    flex-wrap: wrap;
    gap: 1rem;
}

.footer-text p {
    margin: 0;
    opacity: 0.8;
}

.social-links {
    display: flex;
    gap: 1rem;
}

.social-link {
    color: white;
    font-size: 1.2rem;
    transition: color 0.3s ease;
    padding: 0.5rem;
}

.social-link:hover {
    color: #3498db;
}

.back-to-top {
    position: fixed;
    bottom: 2rem;
    right: 2rem;
    background: #3498db;
    color: white;
    border: none;
    width: 50px;
    height: 50px;
    border-radius: 50%;
    cursor: pointer;
    opacity: 0;
    visibility: hidden;
    transition: all 0.3s ease;
    z-index: 100;
}

.back-to-top.show {
    opacity: 1;
    visibility: visible;
}

.back-to-top:hover {
    background: #2980b9;
    transform: translateY(-3px);
}

/* Animations */
@keyframes fadeInUp {
    to {
        opacity: 1;
        transform: translateY(0);
    }
}

/* Responsive Design */
@media (max-width: 768px) {
    .hamburger {
        display: flex;
    }

    .nav-menu {
        position: fixed;
        left: -100%;
        top: 70px;
        flex-direction: column;
        background-color: white;
        width: 100%;
        text-align: center;
        transition: 0.3s;
        box-shadow: 0 10px 27px rgba(0, 0, 0, 0.05);
        padding: 2rem 0;
    }

    .nav-menu.active {
        left: 0;
    }

    .nav-menu li {
        margin: 1rem 0;
    }

    .hero-container {
        grid-template-columns: 1fr;
        text-align: center;
        gap: 2rem;
    }

    .about-content {
        grid-template-columns: 1fr;
        text-align: center;
        gap: 2rem;
    }

    .contact-content {
        grid-template-columns: 1fr;
        gap: 2rem;
    }

    .skills-grid {
        grid-template-columns: 1fr;
        gap: 2rem;
    }

    .footer-content {
        flex-direction: column;
        text-align: center;
    }

    .back-to-top {
        bottom: 1rem;
        right: 1rem;
    }
}

@media (max-width: 480px) {
    .container {
        padding: 0 15px;
    }

    .projects-grid {
        grid-template-columns: 1fr;
        gap: 1.5rem;
    }

    .project-content {
        padding: 1rem;
    }

    .contact-form {
        padding: 1.5rem;
    }
}

/* Accessibility */
@media (prefers-reduced-motion: reduce) {
    * {
        animation-duration: 0.01ms !important;
        animation-iteration-count: 1 !important;
        transition-duration: 0.01ms !important;
    }
}

/* Focus styles for keyboard navigation */
.nav-link:focus,
.cta-button:focus,
.project-card:focus,
.submit-btn:focus,
.social-link:focus,
.back-to-top:focus {
    outline: 2px solid #3498db;
    outline-offset: 2px;
}

/* Smooth scrolling */
html {
    scroll-behavior: smooth;
}

/* Loading animation for images */
img {
    opacity: 0;
    transition: opacity 0.3s ease;
}

img.loaded {
    opacity: 1;
}
```

## JavaScript (script.js)

```javascript
// Mobile Navigation Toggle
const hamburger = document.getElementById('hamburger');
const navMenu = document.getElementById('nav-menu');

hamburger.addEventListener('click', () => {
    hamburger.classList.toggle('active');
    navMenu.classList.toggle('active');
});

// Close mobile menu when clicking on a link
document.querySelectorAll('.nav-link').forEach(link => {
    link.addEventListener('click', () => {
        hamburger.classList.remove('active');
        navMenu.classList.remove('active');
    });
});

// Add keyboard support for hamburger menu
hamburger.addEventListener('keydown', (e) => {
    if (e.key === 'Enter' || e.key === ' ') {
        e.preventDefault();
        hamburger.click();
    }
});

// Navbar background on scroll
window.addEventListener('scroll', () => {
    const header = document.querySelector('.header');
    if (window.scrollY > 100) {
        header.style.background = 'rgba(255, 255, 255, 0.98)';
        header.style.boxShadow = '0 2px 20px rgba(0, 0, 0, 0.15)';
    } else {
        header.style.background = 'rgba(255, 255, 255, 0.95)';
        header.style.boxShadow = '0 2px 20px rgba(0, 0, 0, 0.1)';
    }
});

// Active nav link on scroll
window.addEventListener('scroll', () => {
    let current = '';
    const sections = document.querySelectorAll('section');
    
    sections.forEach(section => {
        const sectionTop = section.offsetTop;
        const sectionHeight = section.clientHeight;
        if (scrollY >= (sectionTop - 200)) {
            current = section.getAttribute('id');
        }
    });

    document.querySelectorAll('.nav-link').forEach(link => {
        link.classList.remove('active');
        if (link.getAttribute('href') === `#${current}`) {
            link.classList.add('active');
        }
    });
});

// Back to top button
const backToTop = document.getElementById('back-to-top');

window.addEventListener('scroll', () => {
    if (window.scrollY > 300) {
        backToTop.classList.add('show');
    } else {
        backToTop.classList.remove('show');
    }
});

backToTop.addEventListener('click', () => {
    window.scrollTo({
        top: 0,
        behavior: 'smooth'
    });
});

// Skills progress bars animation
const observerOptions = {
    threshold: 0.5,
    rootMargin: '0px 0px -50px 0px'
};

const observer = new IntersectionObserver((entries) => {
    entries.forEach(entry => {
        if (entry.isIntersecting) {
            const progressBars = entry.target.querySelectorAll('.skill-progress');
            progressBars.forEach(bar => {
                const width = bar.getAttribute('data-width');
                bar.style.width = width + '%';
            });
            observer.unobserve(entry.target);
        }
    });
}, observerOptions);

// Observe skill categories
document.querySelectorAll('.skill-category').forEach(category => {
    observer.observe(category);
});

// Contact form handling
const contactForm = document.getElementById('contact-form');

contactForm.addEventListener('submit', async (e) => {
    e.preventDefault();
    
    // Get form data
    const formData = new FormData(contactForm);
    const data = Object.fromEntries(formData);
    
    // Reset previous error messages
    contactForm.querySelectorAll('.error-message').forEach(msg => {
        msg.textContent = '';
        msg.style.display = 'none';
    });
    
    // Client-side validation
    let isValid = true;
    const emailRegex = /^[^\s@]+@[^\s@]+\.[^\s@]+$/;
    
    if (!data.name.trim()) {
        showFieldError('name', 'Name is required');
        isValid = false;
    }
    
    if (!emailRegex.test(data.email)) {
        showFieldError('email', 'Please enter a valid email address');
        isValid = false;
    }
    
    if (!data.message.trim()) {
        showFieldError('message', 'Message is required');
        isValid = false;
    }
    
    if (!isValid) return;
    
    try {
        // Simulate form submission (replace with actual API call)
        const submitBtn = contactForm.querySelector('.submit-btn');
        const originalText = submitBtn.innerHTML;
        
        submitBtn.innerHTML = '<span>Sending...</span> <i class="fas fa-spinner fa-spin"></i>';
        submitBtn.disabled = true;
        
        // Simulate API call
        await new Promise(resolve => setTimeout(resolve, 2000));
        
        // Show success message
        alert('Thank you for your message! I\'ll get back to you soon.');
        contactForm.reset();
        
    } catch (error) {
        alert('Sorry, there was an error sending your message. Please try again.');
    } finally {
        submitBtn.innerHTML = originalText;
        submitBtn.disabled = false;
    }
});

function showFieldError(fieldId, message) {
    const field = document.getElementById(fieldId);
    const errorElement = field.parentNode.querySelector('.error-message');
    errorElement.textContent = message;
    errorElement.style.display = 'block';
    field.style.borderColor = '#e74c3c';
    
    // Remove error styling on input
    field.addEventListener('input', () => {
        field.style.borderColor = '';
        errorElement.style.display = 'none';
    }, { once: true });
}

// Image lazy loading
document.addEventListener('DOMContentLoaded', () => {
    const images = document.querySelectorAll('img[loading="lazy"]');
    
    const imageObserver = new IntersectionObserver((entries, observer) => {
        entries.forEach(entry => {
            if (entry.isIntersecting) {
                const img = entry.target;
                img.src = img.dataset.src || img.src;
                img.classList.add('loaded');
                observer.unobserve(img);
            }
        });
    });
    
    images.forEach(img => imageObserver.observe(img));
});

// Smooth scrolling for anchor links
document.querySelectorAll('a[href^="#"]').forEach(anchor => {
    anchor.addEventListener('click', function (e) {
        e.preventDefault();
        const target = document.querySelector(this.getAttribute('href'));
        if (target) {
            target.scrollIntoView({
                behavior: 'smooth',
                block: 'start'
            });
        }
    });
});

// Add loading animation to hero elements
window.addEventListener('load', () => {
    document.body.classList.add('loaded');
});

// Service Worker for offline support (optional)
if ('serviceWorker' in navigator) {
    window.addEventListener('load', () => {
        navigator.serviceWorker.register('/sw.js')
            .then(registration => {
                console.log('SW registered: ', registration);
            })
            .catch(registrationError => {
                console.log('SW registration failed: ', registrationError);
            });
    });
}
```

## Key Features Implemented:

### 🎨 **Design & Layout**
- **Elegant minimalist design** with soft grays, whites, and teal/blue accents
- **Responsive grid system** using CSS Grid and Flexbox (no frameworks)
- **Google Fonts**: Montserrat for headings, Open Sans for body text
- **Smooth animations** with CSS transitions and keyframe animations

### 📱 **Mobile-First Responsiveness**
- **Hamburger menu** for mobile navigation
- **Adaptive typography** using clamp() for responsive font sizes
- **Touch-friendly** buttons and interactive elements
- **Optimized layouts** for tablet and mobile devices

### ♿ **Accessibility**
- **Semantic HTML5** structure with proper ARIA labels
- **Keyboard navigation** support throughout
- **Alt text** for all images
- **Focus indicators** for interactive elements
- **Reduced motion** support for users with vestibular disorders

### ⚡ **Performance Optimizations**
- **Lazy loading** for images
- **Minified CSS** structure (ready for production minification)
- **Efficient animations** using transform and opacity
- **Optimized selectors** for better rendering performance

### 🎯 **Interactive Features**
- **Smooth scrolling** navigation
- **Active link highlighting** on scroll
- **Progress bars** animation for skills section
- **Hover effects** on project cards
- **Form validation** with real-time feedback
- **Back-to-top button** with smooth scroll

### 📂 **Project Showcase**
All 6 projects are featured with:
- Professional card layouts with hover effects
- Tech stack badges for each project
- Direct GitHub links
- Responsive image containers
- Proper alt text descriptions

### ✉️ **Contact Form**
- **Client-side validation** with visual feedback
- **Form submission simulation** (ready for API integration)
- **Social media links** with proper icons
- **Professional styling** matching the overall design

## Setup Instructions:

1. **Create the folder structure**:
```
portfolio/
├── index.html
├── styles.css
├── script.js
├── mulyo.jpg (your profile photo)
├── k8s.png
├── terraform_workflow.png
├── elt_snowflake_dbt.png
├── github_action.png
├── mongodb_data_wrangling.png
└── dbt_snowflake.png
```

2. **Replace placeholder images** with your actual project screenshots and profile photo

3. **Customize content**:
   - Update the bio in the About section
   - Modify project descriptions if needed
   - Adjust skill percentages in the data-width attributes
   - Replace form submission with your preferred backend service

4. **Deploy**:
   - Works perfectly with Netlify, Vercel, or GitHub Pages
   - Can be hosted on any static hosting service

The portfolio is production-ready, fully responsive, and follows modern web development best practices. It's lightweight (no heavy frameworks) and optimized for both performance and user experience.
