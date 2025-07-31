<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>JAFETH NTIGAMAGWA | Web Developer & Python Programmer</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        /* === CSS Styles === */
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            color: #333;
            background-color: #f4f4f4;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
        }
        /* Header */
        header {
            background: #35424a;
            color: #fff;
            padding: 20px 0;
            text-align: center;
        }
        header h1 {
            margin: 0;
            font-size: 2.5em;
        }
        header p {
            margin: 5px 0 0;
            font-size: 1.2em;
        }
        /* Sections */
        section {
            padding: 20px 0;
            border-bottom: 1px solid #e1e1e1;
        }
        h2 {
            color: #35424a;
            text-align: center;
            margin-bottom: 20px;
        }
        /* Skills Grid */
        .skills-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
        }
        .skill-card, .project-card, .edu-card {
            background: #fff;
            padding: 20px;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            margin-bottom: 15px;
        }
        /* Projects Section */
        .projects-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
        }
        .project-card img {
            width: 100%;
            border-radius: 5px;
        }
        .project-links a {
            display: inline-block;
            margin-right: 10px;
            color: #35424a;
            text-decoration: none;
            font-weight: bold;
        }
        /* Contact Info */
        .contact-info {
            text-align: center;
        }
        .contact-info a {
            color: #35424a;
            text-decoration: none;
        }
        .contact-info i {
            margin-right: 10px;
        }
        /* Footer */
        footer {
            background: #35424a;
            color: #fff;
            text-align: center;
            padding: 10px 0;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <!-- Header Section -->
    <header>
        <div class="container">
            <h1>JAFETH NTIGAMAGWA</h1>
            <p>Web Developer | Python Programmer | Database Enthusiast</p>
        </div>
    </header>

    <!-- About Me Section -->
    <section id="about">
        <div class="container">
            <h2>👨‍💻 About Me</h2>
            <p>
                I am a passionate <strong>web developer and Python programmer</strong> with a strong interest in <strong>databases and backend systems</strong>. 
                Currently pursuing a <strong>Bachelor of Science with Education</strong> at <strong>Sokoine University of Agriculture (SUA)</strong>, 
                I am also enhancing my technical skills through the <strong>Power Learn Project (PLP) Scholarship</strong> in <strong>Software Development</strong>.
            </p>
        </div>
    </section>

    <!-- Skills Section -->
    <section id="skills">
        <div class="container">
            <h2>🛠 Technical Skills</h2>
            <div class="skills-grid">
                <div class="skill-card">
                    <h3>🌐 Web Development</h3>
                    <ul>
                        <li>HTML, CSS, JavaScript</li>
                        <li>React (Basic)</li>
                        <li>Django/Flask (Python)</li>
                    </ul>
                </div>
                <div class="skill-card">
                    <h3>🐍 Python Programming</h3>
                    <ul>
                        <li>Scripting & Automation</li>
                        <li>Pandas, NumPy</li>
                        <li>Web Scraping</li>
                    </ul>
                </div>
                <div class="skill-card">
                    <h3>🗃 Databases</h3>
                    <ul>
                        <li>PostgreSQL, MySQL</li>
                        <li>MongoDB (Basic)</li>
                        <li>Django ORM, SQLAlchemy</li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <!-- Projects Section -->
    <section id="projects">
        <div class="container">
            <h2>🚀 Projects</h2>
            <div class="projects-grid">
                <!-- Project 1 -->
                <div class="project-card">
                    <h3>Student Management System (Django)</h3>
                    <p>A web app to manage student records with PostgreSQL.</p>
                    <div class="project-links">
                        <a href="https://github.com/yourusername/student-mgmt" target="_blank"><i class="fab fa-github"></i> Code</a>
                        <a href="https://your-demo-link.com" target="_blank"><i class="fas fa-external-link-alt"></i> Live Demo</a>
                    </div>
                </div>
                <!-- Project 2 -->
                <div class="project-card">
                    <h3>Python Data Analysis</h3>
                    <p>Analyzed agricultural datasets using Pandas and Matplotlib.</p>
                    <div class="project-links">
                        <a href="https://github.com/yourusername/data-analysis" target="_blank"><i class="fab fa-github"></i> Code</a>
                    </div>
                </div>
                <!-- Project 3 -->
                <div class="project-card">
                    <h3>Portfolio Website (HTML/CSS)</h3>
                    <p>This responsive portfolio built from scratch.</p>
                    <div class="project-links">
                        <a href="https://github.com/yourusername/portfolio" target="_blank"><i class="fab fa-github"></i> Code</a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Education Section -->
    <section id="education">
        <div class="container">
            <h2>🎓 Education & Training</h2>
            <div class="edu-card">
                <h3>Sokoine University of Agriculture (SUA)</h3>
                <p><strong>Bachelor of Science with Education</strong> | 202X - Present</p>
            </div>
            <div class="edu-card">
                <h3>Power Learn Project (PLP) – Software Development</h3>
                <p><strong>Fully Funded Scholarship</strong> | 2024 - Present</p>
                <p>Intensive training in full-stack development, Python, and databases.</p>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact">
        <div class="container">
            <h2>📞 Contact Me</h2>
            <div class="contact-info">
                <p><i class="fas fa-envelope"></i> <a href="mailto:jafethfilimon321@gmail.com">jafethfilimon321@gmail.com</a></p>
                <p><i class="fas fa-phone"></i> <a href="tel:+255623647378">+255 623 647 378</a></p>
                <p><i class="fab fa-github"></i> <a href="https://github.com/yourusername" target="_blank">GitHub</a></p>
                <p><i class="fab fa-linkedin"></i> <a href="https://linkedin.com/in/yourprofile" target="_blank">LinkedIn</a></p>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <div class="container">
            <p>&copy; <span id="year"></span> JAFETH NTIGAMAGWA | Built with HTML & CSS</p>
        </div>
    </footer>

    <!-- === JavaScript === -->
    <script>
        // Dynamic year in footer
        document.getElementById('year').textContent = new Date().getFullYear();

        // Smooth scrolling (if you add navigation later)
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });
    </script>
</body>
</html>
