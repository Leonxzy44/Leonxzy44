
---

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=Leonxzy44&color=0A192F&label=Profile+Views&labelColor=000814&style=flat&labelTextColor=FFFFFF" alt="views badge" />
</p>




<h1 align="center">💼 Tech Stack </h1>

<!DOCTYPE html>
<html lang="hr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>LN XZ Portfolio</title>
    <style>
        :root {
            --bg-color: #0a0a0a;
            --neon-green: #b4ff00;
            --hex-gradient: linear-gradient(135deg, #4ade80, #22c55e);
            --icon-bg: #1a1c23;
        }

        body {
            background-color: var(--bg-color);
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 100vh;
            margin: 0;
            font-family: 'Inter', sans-serif;
        }

        /* --- LOGO SEKCIJA --- */
        .logo-container {
            margin-bottom: 50px;
            text-align: center;
        }

        .hexagon {
            width: 120px;
            height: 120px;
            background: var(--hex-gradient);
            clip-path: polygon(25% 0%, 75% 0%, 100% 50%, 75% 100%, 25% 100%, 0% 50%);
            display: flex;
            align-items: center;
            justify-content: center;
            position: relative;
            border: 4px solid black; /* Simulacija bordera */
        }

        .hexagon::before {
            content: 'k';
            font-size: 60px;
            font-weight: bold;
            color: black;
        }

        /* --- TECH STACK TRAKA --- */
        .tech-stack {
            display: flex;
            gap: 15px;
            padding: 20px;
            background: rgba(255, 255, 255, 0.05);
            border-radius: 12px;
        }

        .icon-box {
            width: 50px;
            height: 50px;
            border-radius: 10px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-weight: bold;
            color: white;
            font-size: 14px;
            transition: transform 0.2s;
            cursor: pointer;
        }

        .icon-box:hover {
            transform: translateY(-5px);
        }

        /* Boje inspirirane tvojom slikom */
        .py { background-color: #1e293b; color: #3776ab; }
        .h5 { background-color: #e34f26; }
        .c3 { background-color: #1572b6; }
        .git { background-color: #f05032; }
        .gh { background-color: #24292e; }

    </style>
</head>
<body>

    <div class="logo-container">
        <div class="hexagon"></div>
        <h1 style="color: white; margin-top: 20px; letter-spacing: 5px;">LN <br> XZ</h1>
    </div>

    <div class="tech-stack">
        <div class="icon-box py">Py</div>
        <div class="icon-box h5">HTML5</div>
        <div class="icon-box c3">CSS3</div>
        <div class="icon-box git">Git</div>
        <div class="icon-box gh">GitHub</div>
    </div>

</body>
</html>

---





