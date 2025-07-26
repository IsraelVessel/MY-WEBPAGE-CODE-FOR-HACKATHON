# MY-WEBPAGE-CODE-FOR-HACKATHON
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Your Name | Portfolio</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body {
            font-family: 'Segoe UI', Arial, sans-serif;
            margin: 0;
            padding: 0;
            color: #222;
            background: #f7f8fa;
        }
        header {
            background: #264653;
            color: #fff;
            padding: 2rem 1rem;
            text-align: center;
        }
        nav {
            background: #2a9d8f;
            text-align: center;
            padding: 1rem 0;
        }
        nav a {
            color: #fff;
            margin: 0 1.2rem;
            text-decoration: none;
            font-weight: 500;
            transition: color 0.2s;
        }
        nav a:hover {
            color: #ffd166;
        }
        main {
            max-width: 900px;
            margin: 2rem auto;
            padding: 2rem;
            background: #fff;
            border-radius: 12px;
            box-shadow: 0 2px 20px rgba(41, 60, 85, 0.09);
        }
        section {
            margin-bottom: 2.5rem;
        }
        h2 {
            border-left: 5px solid #2a9d8f;
            padding-left: 0.7rem;
            margin-bottom: 1rem;
            color: #264653;
        }
        ul {
            list-style-type: disc;
            padding-left: 2rem;
        }
        .projects a, .download-link {
            color: #e76f51;
            text-decoration: underline;
        }
        .projects a:hover, .download-link:hover {
            color: #264653;
        }
        .contact-form label {
            display: block;
            margin-bottom: 0.3rem;
        }
        .contact-form input, .contact-form textarea {
            width: 100%;
            padding: 0.6rem;
            margin-bottom: 1rem;
            border: 1px solid #a8dadc;
            border-radius: 4px;
            font-size: 1rem;
        }
        .contact-form button {
            background: #2a9d8f;
            color: #fff;
            padding: 0.6rem 1.6rem;
            border: none;
            border-radius: 4px;
            cursor: pointer;
            font-size: 1rem;
        }
        .contact-form button:hover {
            background: #264653;
        }
        @media (max-width: 700px) {
            main {
                padding: 1rem;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>SOLOMON ISRAEL MAICHIBI</h1>
        <p>Welcome to my portfolio! I’m a passionate developer eager to build, learn, and collaborate.</p>
    </header>


    <nav>
        <a href="#about">About Me</a>
        <a href="#languages">Programming Languages</a>
        <a href="#education">Education</a>
        <a href="#interests">Interests</a>
        <a href="#projects">Projects</a>
        <a href="#contact">Contact</a>
    </nav>


    <main>
        <section id="about">
            <h2>📝 About Me</h2>
            <p>
                Hi! I’m <strong>SOLOMON ISRAEL MAICHIBI</strong>, a creative technology enthusiast with a deep passion for coding, problem-solving, and creating impactful digital experiences. My journey in tech is driven by curiosity and the desire to make a difference.
            </p>
        </section>
        
        <section id="languages">
            <h2>⚙️Programming Languages</h2>
            <ul>
                <li>HTML</li>
                <li>CSS</li>
                <li>Python</li>
            </ul>
        </section>
        
        <section id="education">
            <h2> 🎓Educational Background</h2>
            <p>
                I hold a <em>Bachelor of ART's in ENGLISH LANGUAGE</em> from <em>FEDERAL UNIVERSITY DUTSE</em>.
            </p>
            <p>
                <a class="download-link" href="https://github.com/IsraelVessel/SOLOMON-ISRAEL-MAICHIBICV/blob/main/Real%20IsraelVessel%20CV-1.docx" download>Download My CV</a>
            </p>
        </section>
        
        <section id="interests">
            <h2>💡 Interests</h2>
            <ul>
                <li>Web Development: Building responsive and user-friendly websites</li>
                <li>Tech Innovations: Exploring AI and emerging technologies</li>
                <li>Language Research: Integrating Computational methods to analyze language.</li>
                <li>Open Source: Contributing to collaborative projects</li>
            </ul>
        </section>
        
        <section id="projects" class="projects">
            <h2>🛠️ Projects</h2>
            <ul>
                <li>
                    <a href="https://github.com/users/IsraelVessel/projects/1" target="_blank">Project One</a>: A github repo on my first hackathon.
                </li>
                <li>
                    <a href="https://github.com/users/IsraelVessel/projects/3" target="_blank">Project Two</a>: A personal website showcasing my portforlio.
                </li>
            </ul>
        </section>
       
        <section id="contact">
            <h2>📬 Contact Me</h2>
            <form class="contact-form" action="mailto:your.email@example.com" method="POST" enctype="text/plain">
                <label for="name">Name:</label>
                <input type="text" name="name" id="name" required>
                
                <label for="email">Email:</label>
                <input type="email" name="email" id="email" required>
                
                <label for="message">Message:</label>
                <textarea name="message" id="message" rows="5" required></textarea>
                
                <button type="submit">Send</button>
            </form>
            <p>
                Or email me directly at <a href="mailto:your.email@example.com">solomonisraelmaichibi@gmail.com</a>
            </p>
        </section>
    </main>
</body>
</html>
