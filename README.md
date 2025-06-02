<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>German Esteban Barbosa</title>
    <style>
        body {
            font-family: 'Helvetica', sans-serif;
            background-color: #0a0e14;
            color: #d3dce6;
            margin: 0;
            padding: 20px;
        }
        .container {
            max-width: 900px;
            margin: 0 auto;
            text-align: center;
        }
        h1 {
            color: #f5a623;
            font-size: 2.5em;
            margin-bottom: 10px;
        }
        h2 {
            color: #a3bffa;
            margin-top: 30px;
            font-size: 1.5em;
        }
        .intro {
            background: #1c2526;
            padding: 20px;
            border-radius: 10px;
            margin-bottom: 20px;
            transition: transform 0.3s ease;
        }
        .intro:hover {
            transform: scale(1.02);
        }
        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
        }
        .card {
            background: #1c2526;
            padding: 15px;
            border-radius: 10px;
            transition: box-shadow 0.3s ease;
        }
        .card:hover {
            box-shadow: 0 0 15px rgba(245, 166, 35, 0.3);
        }
        ul {
            list-style-type: none;
            padding-left: 0;
            text-align: left;
        }
        ul li:before {
            content: "⚡";
            padding-right: 10px;
            color: #f5a623;
        }
        a {
            color: #a3bffa;
            text-decoration: none;
        }
        a:hover {
            color: #f5a623;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="intro">
            <h1>Hi there, I'm German Esteban Barbosa 👋</h1>
            <p>Passionate about leveraging data-driven insights to drive business growth and efficiency. 😊</p>
        </div>

        <div class="grid">
            <div class="card">
                <h2>About Me</h2>
                <p>I'm a Machine Learning & Data Analytics enthusiast with a background in business and a strong focus on AI-driven solutions. I specialize in leveraging data to optimize processes and drive insights.</p>
                <ul>
                    <li>MSc in Data Analytics for Business | BSc in Business Management</li>
                    <li>Interested in Fintech, AI-driven process optimization, and data governance</li>
                </ul>
            </div>

            <div class="card">
                <h2>Skills & Technologies</h2>
                <ul>
                    <li>Programming: Python (Pandas, NumPy, Scikit-Learn, TensorFlow, PyTorch), SQL, R</li>
                    <li>Machine Learning: Supervised & Unsupervised Learning, Time Series, NLP, Computer Vision</li>
                    <li>Tools & Frameworks: Jupyter, Google Cloud, AWS, Microsoft Azure, Git</li>
                    <li>Other: Agile (Scrum), Business Intelligence (Tableau, Power BI)</li>
                </ul>
            </div>

            <div class="card">
                <h2>Featured Projects</h2>
                <div><strong>L'Oreal Description Labeling</strong> - Prompt engineering using LLMs to label product descriptions into given categories (L'Oreal study case)</div>
                <div><strong>Spotify Playlist</strong> - Restoring top of the year playlist for users.</div>
            </div>

            <div class="card">
                <h2>Connect with Me</h2>
                <ul>
                    <li><a href="https://www.linkedin.com/in/germanebarbosa" target="_blank">LinkedIn: Germanebarbosa</a></li>
                    <li><a href="https://github.com/Germanebarbosa" target="_blank">GitHub: Germanebarbosa</a></li>
                    <li>Email: <a href="mailto:german.ebarbosa@hotmail.com">german.ebarbosa@hotmail.com</a></li>
                </ul>
            </div>
        </div>
    </div>
</body>
</html>
