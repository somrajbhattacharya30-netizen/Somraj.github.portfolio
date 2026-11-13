# Somraj.github.portfolio<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Somraj Bhattacharya | Portfolio</title>
    <style>
        :root {
            --bg-color: #0f172a;
            --card-bg: #1e293b;
            --text-primary: #f8fafc;
            --text-secondary: #94a3b8;
            --accent: #38bdf8;
            --border: #334155;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
        }

        body {
            background-color: var(--bg-color);
            color: var(--text-primary);
            line-height: 1.6;
            padding: 20px;
        }

        .container {
            max-width: 800px;
            margin: 40px auto;
            padding: 20px;
        }

        header {
            display: flex;
            align-items: center;
            gap: 30px;
            background: var(--card-bg);
            padding: 30px;
            border-radius: 12px;
            border: 1px solid var(--border);
            margin-bottom: 30px;
        }

        .profile-img {
            width: 140px;
            height: 140px;
            border-radius: 50%;
            object-fit: cover;
            border: 3px solid var(--accent);
        }

        .profile-info h1 {
            font-size: 2rem;
            margin-bottom: 5px;
            color: var(--text-primary);
        }

        .profile-info p {
            color: var(--accent);
            font-size: 1.1rem;
            font-weight: 500;
            margin-bottom: 10px;
        }

        .profile-info span {
            color: var(--text-secondary);
            font-size: 0.95rem;
        }

        section {
            background: var(--card-bg);
            padding: 25px 30px;
            border-radius: 12px;
            border: 1px solid var(--border);
            margin-bottom: 25px;
        }

        section h2 {
            font-size: 1.4rem;
            margin-bottom: 15px;
            color: var(--accent);
            border-bottom: 2px solid var(--border);
            padding-bottom: 8px;
        }

        p, ul {
            color: var(--text-secondary);
            font-size: 1rem;
            margin-bottom: 10px;
        }

        ul {
            list-style-type: disc;
            padding-left: 20px;
        }

        ul li {
            margin-bottom: 8px;
        }

        .skills-grid {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
            margin-top: 10px;
        }

        .skill-tag {
            background: rgba(56, 189, 248, 0.1);
            color: var(--accent);
            padding: 6px 14px;
            border-radius: 20px;
            font-size: 0.9rem;
            border: 1px solid rgba(56, 189, 248, 0.2);
        }

        .social-links {
            display: flex;
            gap: 15px;
            margin-top: 15px;
        }

        .social-links a {
            color: var(--accent);
            text-decoration: none;
            font-weight: 500;
        }

        .social-links a:hover {
            text-decoration: underline;
        }

        footer {
            text-align: center;
            color: var(--text-secondary);
            font-size: 0.85rem;
            margin-top: 40px;
        }

        @media (max-width: 600px) {
            header {
                flex-direction: column;
                text-align: center;
            }
            .social-links {
                justify-content: center;
            }
        }
    </style>
</head>
<body>

    <div class="container">
        <!-- Header / Bio Section -->
        <header>
            <!-- Name your cropped photo file 'profile.jpg' and place it in the same folder -->
            <img src="profile.jpg" alt="Somraj Bhattacharya" class="profile-img">
            <div class="profile-info">
                <h1>Somraj Bhattacharya</h1>
                <p>B.Tech Genetics & Artificial Intelligence</p>
                <span>Lovely Professional University • 1st Year</span>
                <div class="social-links">
                    <a href="https://github.com/somrajbhattacharya30-netizen" target="_blank">GitHub</a>
                    <!-- Add your LinkedIn or other links here if desired -->
                </div>
            </div>
        </header>

        <!-- About Me -->
        <section>
            <h2>About Me</h2>
            <p>Hello! I am Somraj, currently pursuing my first year of B.Tech in Genetics and Artificial Intelligence. I am deeply fascinated by the intersection of computational logic and biological sciences, exploring how machine learning and data-driven models can unlock insights in genomics and healthcare.</p>
        </section>

        <!-- Education -->
        <section>
            <h2>Education</h2>
            <p><strong>Bachelor of Technology (B.Tech) in Genetics and Artificial Intelligence</strong></p>
            <p>Lovely Professional University (LPU)</p>
            <p><em>Current Year: 1st Year</em></p>
        </section>

        <!-- Areas of Interest & Skills -->
        <section>
            <h2>Interests & Focus Areas</h2>
            <ul>
                <li>Artificial Intelligence & Algorithmic Problem Solving</li>
                <li>Computational Genetics & Bioinformatics</li>
                <li>Software Development Fundamentals</li>
            </ul>
            <div class="skills-grid">
                <span class="skill-tag">Python</span>
                <span class="skill-tag">Data Structures</span>
                <span class="skill-tag">Genetics</span>
                <span class="skill-tag">Git & GitHub</span>
                <span class="skill-tag">Problem Solving</span>
            </div>
        </section>

        <!-- Contact -->
        <section>
            <h2>Get in Touch</h2>
            <p>Feel free to check out my repositories or reach out if you share similar academic and technical interests!</p>
            <div class="social-links">
                <a href="https://github.com/somrajbhattacharya30-netizen" target="_blank">GitHub Profile</a>
            </div>
        </section>

        <footer>
            <p>&copy; 2026 Somraj Bhattacharya. Built for GitHub Pages.</p>
        </footer>
    </div>

</body>
</html>
