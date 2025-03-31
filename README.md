<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mon Profil GitHub</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background-color: #f5f5f5;
            margin: 0;
            padding: 0;
            color: #333;
        }

        .container {
            width: 80%;
            margin: auto;
            padding: 50px 0;
            text-align: center;
        }

        h1 {
            font-size: 3em;
            color: #1e90ff;
            margin-bottom: 20px;
            text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.1);
        }

        h2 {
            font-size: 2em;
            color: #333;
            margin-bottom: 10px;
        }

        .skills {
            display: flex;
            justify-content: center;
            gap: 30px;
            margin-top: 30px;
        }

        .skill-card {
            background-color: #fff;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            width: 150px;
            transition: transform 0.3s ease;
        }

        .skill-card:hover {
            transform: scale(1.1);
        }

        .skill-card h3 {
            font-size: 1.5em;
            color: #4caf50;
            margin-bottom: 10px;
        }

        .progress-bar {
            width: 100%;
            height: 15px;
            border-radius: 10px;
            background-color: #e0e0e0;
            margin-top: 10px;
            position: relative;
        }

        .progress-bar span {
            height: 100%;
            border-radius: 10px;
            display: block;
            position: absolute;
            top: 0;
        }

        .java { width: 80%; background-color: #f44336; }
        .python { width: 85%; background-color: #4caf50; }
        .html { width: 90%; background-color: #ff9800; }
        .css { width: 75%; background-color: #2196f3; }
        .sql { width: 70%; background-color: #9c27b0; }

        .cta {
            margin-top: 40px;
            font-size: 1.2em;
        }

        .cta a {
            color: #fff;
            background-color: #1e90ff;
            padding: 10px 20px;
            text-decoration: none;
            border-radius: 5px;
            font-weight: bold;
        }

        .cta a:hover {
            background-color: #0056b3;
        }

        /* Animations */
        @keyframes fadeIn {
            0% { opacity: 0; }
            100% { opacity: 1; }
        }

        .animated {
            animation: fadeIn 2s ease-in-out;
        }
    </style>
</head>
<body>

    <div class="container">
        <h1 class="animated">Bonjour, je suis **[Votre Nom]** 👋</h1>
        <h2 class="animated">Développeur passionné par les technologies et le code 💻✨</h2>

        <p class="animated">Je me spécialise dans plusieurs langages de programmation et je suis toujours à la recherche de nouvelles opportunités pour apprendre et contribuer. Voici un aperçu de mes compétences :</p>

        <div class="skills animated">
            <div class="skill-card">
                <h3>Java</h3>
                <div class="progress-bar">
                    <span class="java"></span>
                </div>
            </div>
            <div class="skill-card">
                <h3>Python</h3>
                <div class="progress-bar">
                    <span class="python"></span>
                </div>
            </div>
            <div class="skill-card">
                <h3>HTML</h3>
                <div class="progress-bar">
                    <span class="html"></span>
                </div>
            </div>
            <div class="skill-card">
                <h3>CSS</h3>
                <div class="progress-bar">
                    <span class="css"></span>
                </div>
            </div>
            <div class="skill-card">
                <h3>SQL</h3>
                <div class="progress-bar">
                    <span class="sql"></span>
                </div>
            </div>
        </div>

        <div class="cta">
            <p class="animated">Vous souhaitez discuter de projets intéressants ou de collaborations ?</p>
            <a href="https://github.com/votre-username" class="animated">Visitez mon GitHub</a>
        </div>
    </div>

</body>
</html>
