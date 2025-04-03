# Bikhasda-portfolio
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bikash Ghosh - Portfolio</title>
    <link rel="stylesheet" href="styles.css">
    <script defer src="script.js"></script>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(to right, #2c3e50, #4ca1af);
            color: white;
            text-align: center;
        }
        header {
            padding: 20px;
            background: rgba(0, 0, 0, 0.7);
        }
        section {
            margin: 40px;
            padding: 20px;
            background: rgba(255, 255, 255, 0.2);
            border-radius: 10px;
        }
        a {
            color: #f1c40f;
            text-decoration: none;
            font-weight: bold;
        }
        button {
            padding: 10px 20px;
            border: none;
            background: #f1c40f;
            color: #2c3e50;
            font-weight: bold;
            cursor: pointer;
            transition: 0.3s;
        }
        button:hover {
            background: #e67e22;
        }
    </style>
</head>
<body>
    <header>
        <h1>Bikash Ghosh</h1>
        <p>Aspiring Professional | Tech Enthusiast | Data Entry Operator</p>
    </header>
    
    <section id="about">
        <h2>About Me</h2>
        <p>I am eager to apply my knowledge and expertise in a professional setting. My goal is to continuously learn, grow, and make valuable contributions to the success of the team and the organization as a whole.</p>
    </section>
    
    <section id="education">
        <h2>Education</h2>
        <ul>
            <li><strong>B.Tech in CSE</strong> - Swami Vivekananda University (Ongoing, 2026)</li>
            <li><strong>Diploma in CST</strong> - MAKAUT (2023) - 77%</li>
            <li><strong>Higher Secondary</strong> - W.B.S.C.T.V.E.S.D (2021) - 64%</li>
            <li><strong>M.P</strong> - W.B.B.S.E (2019) - 34%</li>
        </ul>
    </section>
    
    <section id="skills">
        <h2>Skills</h2>
        <ul>
            <li>Word, Excel, PowerPoint</li>
            <li>C, Java, Python</li>
            <li>Ethical Hacking Essentials (EHE), Cyber Security, Python</li>
        </ul>
    </section>
    
    <section id="experience">
        <h2>Experience</h2>
        <p><strong>Data Entry Operator</strong> (Feb 2022 - Jan 2023)</p>
    </section>
    
    <section id="resume">
        <h2>Resume</h2>
        <p><a href="Bikash_Resume.pdf" download>Download Resume</a></p>
    </section>
    
    <section id="contact">
        <h2>Contact</h2>
        <p>Email: <a href="mailto:ghoshbikash198@gmail.com">ghoshbikash198@gmail.com</a></p>
        <p>Phone: ‪+91 9749661645‬</p>
        <p>Location: Chhatinasole, Gopiballavpur, Jhargram, West Bengal, 721506</p>
        <button onclick="showAlert()">Click to Connect</button>
    </section>
    
    <footer>
        <p>&copy; 2025 Bikash Ghosh. All rights reserved.</p>
    </footer>
    
    <script>
        function showAlert() {
            alert('Thank you for visiting my portfolio! Feel free to reach out.');
        }
    </script>
</body>
</html>
