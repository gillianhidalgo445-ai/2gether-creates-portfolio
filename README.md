# 2gether-creates-portfolio
Team portfolio website for 2GETHER CREATES - Section NO1. Built with HTML and CSS as part of our Introduction to Computing course project.
[2GETHER_CREATES_NO1_Portfolio.css](https://github.com/user-attachments/files/24355094/2GETHER_CREATES_NO1_Portfolio.css)
/* Reset and Base Styles */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Poppins', Arial, sans-serif;
    line-height: 1.6;
    color: #333;
    background-color: #f8f9fa;
}

/* Container */
.container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 20px;
}

/* Header & Navigation */
header {
    background-color: #1e3a8a;
    color: white;
    padding: 1rem 0;
    position: sticky;
    top: 0;
    z-index: 1000;
    box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
}

nav {
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 20px;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.logo {
    font-size: 1.5rem;
    font-weight: 700;
    letter-spacing: 1px;
}

.nav-links {
    display: flex;
    list-style: none;
    gap: 2rem;
}

.nav-links a {
    color: white;
    text-decoration: none;
    font-weight: 500;
    transition: color 0.3s ease;
}

.nav-links a:hover {
    color: #60a5fa;
}

/* Sections General Styling */
section {
    padding: 4rem 0;
}

section h2 {
    font-size: 2.5rem;
    color: #1e3a8a;
    text-align: center;
    margin-bottom: 1rem;
}

.section-subtitle {
    text-align: center;
    color: #64748b;
    font-size: 1.1rem;
    margin-bottom: 3rem;
}

/* Home Section */
.home-section {
    background: linear-gradient(135deg, #1e3a8a 0%, #3b82f6 100%);
    color: white;
    padding: 5rem 0;
}

.welcome-box {
    text-align: center;
    margin-bottom: 4rem;
}

.welcome-box h1 {
    font-size: 3rem;
    margin-bottom: 1rem;
    color: white;
}

.subtitle {
    font-size: 1.3rem;
    margin-bottom: 1.5rem;
    color: #e0e7ff;
}

.intro-text {
    max-width: 800px;
    margin: 0 auto 2rem;
    font-size: 1.1rem;
    line-height: 1.8;
}

.cta-button {
    display: inline-block;
    background-color: white;
    color: #1e3a8a;
    padding: 0.9rem 2rem;
    text-decoration: none;
    border-radius: 8px;
    font-weight: 600;
    transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.cta-button:hover {
    transform: translateY(-2px);
    box-shadow: 0 10px 20px rgba(0, 0, 0, 0.2);
}

/* Team Members */
.team-members {
    margin-top: 3rem;
}

.team-members h2 {
    color: white;
    margin-bottom: 2rem;
}

.members-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 2rem;
    max-width: 900px;
    margin: 0 auto;
}

.member-card {
    background-color: white;
    padding: 2rem;
    border-radius: 12px;
    text-align: center;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    transition: transform 0.3s ease;
}

.member-card:hover {
    transform: translateY(-5px);
}

.member-avatar {
    width: 100px;
    height: 100px;
    background: linear-gradient(135deg, #3b82f6, #1e3a8a);
    color: white;
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 2rem;
    font-weight: 700;
    margin: 0 auto 1rem;
}

.member-card h3 {
    color: #1e3a8a;
    margin-bottom: 0.5rem;
}

.member-card p {
    color: #64748b;
    font-size: 0.95rem;
}

/* Projects Section */
.projects-section {
    background-color: white;
}

.projects-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 2rem;
}

.project-card {
    background-color: #f8f9fa;
    padding: 2rem;
    border-radius: 12px;
    border: 2px solid #e2e8f0;
    transition: transform 0.3s ease, border-color 0.3s ease;
}

.project-card:hover {
    transform: translateY(-5px);
    border-color: #3b82f6;
}

.project-icon {
    font-size: 3rem;
    margin-bottom: 1rem;
}

.project-card h3 {
    color: #1e3a8a;
    margin-bottom: 1rem;
}

.project-card p {
    color: #64748b;
    margin-bottom: 1.5rem;
}

.tech-tags {
    display: flex;
    gap: 0.5rem;
    flex-wrap: wrap;
}

.tag {
    background-color: #dbeafe;
    color: #1e3a8a;
    padding: 0.3rem 0.8rem;
    border-radius: 20px;
    font-size: 0.85rem;
    font-weight: 500;
}

/* Skills Section */
.skills-section {
    background-color: #f1f5f9;
}

.skills-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 2rem;
    max-width: 900px;
    margin: 0 auto 3rem;
}

.skill-category {
    background-color: white;
    padding: 2rem;
    border-radius: 12px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}

.skill-category h3 {
    color: #1e3a8a;
    margin-bottom: 1.5rem;
    font-size: 1.4rem;
}

.skills-list {
    list-style: none;
}

.skills-list li {
    padding: 0.7rem 0;
    border-bottom: 1px solid #e2e8f0;
    color: #475569;
}

.skills-list li:last-child {
    border-bottom: none;
}

.skills-list li:before {
    content: "✓ ";
    color: #3b82f6;
    font-weight: 700;
    margin-right: 0.5rem;
}

/* Certifications Section */
.certifications-section {
    max-width: 900px;
    margin: 0 auto;
    background-color: white;
    padding: 2rem;
    border-radius: 12px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}

.certifications-section h3 {
    color: #1e3a8a;
    margin-bottom: 1.5rem;
    font-size: 1.4rem;
    text-align: center;
}

.cert-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 1.5rem;
}

.cert-item {
    background-color: #f8f9fa;
    padding: 1.5rem;
    border-radius: 8px;
    border-left: 4px solid #3b82f6;
}

.cert-item p {
    margin-bottom: 0.5rem;
}

.cert-item strong {
    color: #1e3a8a;
}

/* Contact Section */
.contact-section {
    background-color: white;
}

.contact-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 2rem;
    max-width: 900px;
    margin: 0 auto 3rem;
}

.contact-card {
    background-color: #f8f9fa;
    padding: 2rem;
    border-radius: 12px;
    border: 2px solid #e2e8f0;
    transition: transform 0.3s ease, border-color 0.3s ease;
}

.contact-card:hover {
    transform: translateY(-5px);
    border-color: #3b82f6;
}

.contact-card h3 {
    color: #1e3a8a;
    margin-bottom: 1rem;
    font-size: 1.3rem;
    text-align: center;
}

.contact-details {
    text-align: center;
}

.contact-details p {
    margin: 0.8rem 0;
    color: #475569;
}

.contact-details a {
    color: #3b82f6;
    text-decoration: none;
    font-weight: 500;
}

.contact-details a:hover {
    text-decoration: underline;
}

.location-info {
    text-align: center;
    padding: 2rem;
    background-color: #f1f5f9;
    border-radius: 12px;
    max-width: 500px;
    margin: 0 auto;
}

.location-info .contact-icon {
    font-size: 3rem;
    margin-bottom: 1rem;
}

.location-info h3 {
    color: #1e3a8a;
    margin-bottom: 0.5rem;
}

.location-info p {
    color: #475569;
    font-weight: 500;
}

/* Footer */
footer {
    background-color: #1e3a8a;
    color: white;
    padding: 2rem 0;
    text-align: center;
}

.members-footer {
    margin-top: 0.5rem;
    font-size: 0.9rem;
    opacity: 0.9;
}

/* Responsive Design - Mobile */
@media (max-width: 768px) {
    .nav-links {
        gap: 1rem;
        font-size: 0.9rem;
    }

    .logo {
        font-size: 1.2rem;
    }

    .welcome-box h1 {
        font-size: 2rem;
    }

    .subtitle {
        font-size: 1.1rem;
    }

    section h2 {
        font-size: 2rem;
    }

    .members-grid,
    .projects-grid,
    .skills-grid,
    .contact-info {
        grid-template-columns: 1fr;
    }

    section {
        padding: 3rem 0;
    }
}

/* Responsive Design - Tablet */
@media (min-width: 769px) and (max-width: 1023px) {
    .members-grid,
    .projects-grid {
        grid-template-columns: repeat(2, 1fr);
    }
}

/* Smooth Scrolling */
html {
    scroll-behavior: smooth;[2GETHER_CREATES_NO1_Portfolio.html](https://github.com/user-attachments/files/24355097/2GETHER_CREATES_NO1_Portfolio.html)
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>2GETHER CREATES - Team Portfolio</title>
    <link rel="stylesheet" href="2GETHER_CREATES_NO1_Portfolio.css">
    <!-- Font from Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">
</head>
<body>
    <!-- Header & Navigation -->
    <header>
        <nav>
            <div class="logo">2GETHER CREATES</div>
            <ul class="nav-links">
                <li><a href="#home">Home</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#skills">Skills</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <!-- Home / About Section -->
        <section id="home" class="home-section">
            <div class="container">
                <div class="welcome-box">
                    <h1>Welcome to 2GETHER CREATES</h1>
                    <p class="subtitle">Building digital solutions, one project at a time</p>
                    <p class="intro-text">
                        We are first-year students from Section NO1, passionate about learning web development 
                        and creating meaningful digital experiences. Our team combines creativity, attention to 
                        detail, and dedication to deliver quality work.
                    </p>
                    <a href="#projects" class="cta-button">View Our Projects</a>
                </div>

                <div class="team-members">
                    <h2>Meet Our Team</h2>
                    <div class="members-grid">
                        <div class="member-card">
                            <div class="member-avatar">KC</div>
                            <h3>Ken Chan Cabebe</h3>
                            <p>Responsible for research and content writing. Detail-oriented and helps ensure accuracy and clarity in projects.</p>
                        </div>
                        <div class="member-card">
                            <div class="member-avatar">GH</div>
                            <h3>Gillian Hidalgo</h3>
                            <p>A detail-oriented student with interest in design and documentation. Responsible for layout, visuals, and project organization.</p>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Projects Section -->
        <section id="projects" class="projects-section">
            <div class="container">
                <h2>Our Projects</h2>
                <p class="section-subtitle">Showcasing our learning journey through hands-on activities</p>
                
                <div class="projects-grid">
                    <div class="project-card">
                        <div class="project-icon">🌐</div>
                        <h3>Basic HTML Page Activity</h3>
                        <p>Created a simple web page using HTML elements such as headings, paragraphs, lists, images, and links as part of a classroom activity.</p>
                        <div class="tech-tags">
                            <span class="tag">HTML</span>
                            <span class="tag">Web Design</span>
                        </div>
                    </div>

                    <div class="project-card">
                        <div class="project-icon">🎨</div>
                        <h3>CSS Styling Exercise</h3>
                        <p>Applied basic CSS properties including colors, fonts, spacing, and layout to improve the visual appearance of a web page.</p>
                        <div class="tech-tags">
                            <span class="tag">CSS</span>
                            <span class="tag">Design</span>
                        </div>
                    </div>

                    <div class="project-card">
                        <div class="project-icon">📝</div>
                        <h3>Form Creation Activity</h3>
                        <p>Developed a basic HTML form with input fields, labels, and a submit button to practice user input handling.</p>
                        <div class="tech-tags">
                            <span class="tag">HTML</span>
                            <span class="tag">Forms</span>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Skills & Hobbies Section -->
        <section id="skills" class="skills-section">
            <div class="container">
                <h2>Skills & Competencies</h2>
                <p class="section-subtitle">Our toolkit for success</p>

                <div class="skills-grid">
                    <div class="skill-category">
                        <h3>💻 Technical Skills</h3>
                        <ul class="skills-list">
                            <li>Basic HTML (Certified - Sololearn)</li>
                            <li>Basic CSS (Certified - Sololearn)</li>
                            <li>Microsoft Word</li>
                            <li>Microsoft PowerPoint</li>
                            <li>Microsoft Excel</li>
                            <li>File Management</li>
                            <li>Internet Research</li>
                        </ul>
                    </div>

                    <div class="skill-category">
                        <h3>🤝 Soft Skills</h3>
                        <ul class="skills-list">
                            <li>Teamwork</li>
                            <li>Communication</li>
                            <li>Collaboration</li>
                            <li>Time Management</li>
                            <li>Responsibility</li>
                            <li>Meeting Deadlines</li>
                        </ul>
                    </div>
                </div>

                <div class="certifications-section">
                    <h3>🏆 Certifications</h3>
                    <div class="cert-grid">
                        <div class="cert-item">
                            <p><strong>Ken Chan Cabebe</strong></p>
                            <p>✓ Introduction to HTML (Sololearn)</p>
                            <p>✓ Introduction to CSS (Sololearn)</p>
                        </div>
                        <div class="cert-item">
                            <p><strong>Gillian Hidalgo</strong></p>
                            <p>✓ Introduction to HTML (Sololearn)</p>
                            <p>✓ Introduction to CSS (Sololearn)</p>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Contact Section -->
        <section id="contact" class="contact-section">
            <div class="container">
                <h2>Get In Touch</h2>
                <p class="section-subtitle">We'd love to hear from you!</p>

                <div class="contact-grid">
                    <div class="contact-card">
                        <h3>Ken Chan Cabebe</h3>
                        <div class="contact-details">
                            <p>📧 <a href="mailto:kenchancabebe@gmail.com">kenchancabebe@gmail.com</a></p>
                            <p>📱 <a href="https://www.facebook.com/kenchan.cabebe" target="_blank">Facebook Profile</a></p>
                        </div>
                    </div>

                    <div class="contact-card">
                        <h3>Gillian Hidalgo</h3>
                        <div class="contact-details">
                            <p>📧 <a href="mailto:gillian.hidalgo@carsu.edu.ph">gillian.hidalgo@carsu.edu.ph</a></p>
                            <p>📱 <a href="https://www.facebook.com/Gi11hid" target="_blank">Facebook Profile</a></p>
                        </div>
                    </div>
                </div>

                <div class="location-info">
                    <div class="contact-icon">📍</div>
                    <h3>Location</h3>
                    <p>Butuan City, Agusan Del Norte, Philippines</p>
                </div>
            </div>
        </section>
    </main>

    <!-- Footer -->
    <footer>
        <div class="container">
            <p>&copy; 2025 2GETHER CREATES | Section NO1</p>
            <p class="members-footer">Group Members: Ken Chan Cabebe, Gillian Hidalgo</p>
        </div>
    </footer>
</body>
</html>
}
