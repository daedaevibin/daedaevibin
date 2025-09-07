<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dae Euhwa - GitHub Profile</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Delius&display=swap" rel="stylesheet">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Delius', Arial, sans-serif;
            background: linear-gradient(to bottom right, #1A1A1A, #333333);
            color: #F5DEB3;
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            padding: 20px;
        }
        
        .container {
            max-width: 1000px;
            width: 100%;
            background: rgba(30, 30, 30, 0.9);
            padding: 30px;
            border-radius: 15px;
            box-shadow: 0 0 15px rgba(230, 126, 34, 0.5);
            border: 1px solid #D5804F;
        }
        
        h1 {
            font-size: 2.8rem;
            color: #D5804F;
            text-shadow: 2px 2px 4px #A77250;
            margin-bottom: 20px;
        }
        
        h2 {
            color: #9B59B6;
            text-shadow: 2px 2px 4px #512DA8;
            margin: 25px 0 15px 0;
            padding-bottom: 8px;
            border-bottom: 1px solid #D5804F;
        }
        
        .stats-container {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin: 25px 0;
            flex-wrap: wrap;
        }
        
        .stat-box {
            flex: 1;
            min-width: 300px;
            border-radius: 10px;
            box-shadow: 0 0 5px rgba(230, 126, 34, 0.3);
            overflow: hidden;
        }
        
        p {
            line-height: 1.6;
            margin-bottom: 15px;
            text-align: center;
        }
        
        ul {
            list-style-type: none;
            padding-left: 0;
        }
        
        li {
            margin-bottom: 10px;
            padding-left: 20px;
            position: relative;
        }
        
        li:before {
            content: "•";
            color: #D5804F;
            font-weight: bold;
            position: absolute;
            left: 0;
        }
        
        a {
            color: #D5804F;
            text-decoration: none;
            font-weight: bold;
            transition: all 0.3s ease;
            display: inline-block;
            padding: 2px 5px;
        }
        
        a:hover {
            color: #F5DEB3;
            background-color: #D5804F;
            border-radius: 4px;
            transform: translateY(-2px);
        }
        
        .social-icons {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin-top: 20px;
        }
        
        .icon {
            width: 40px;
            height: 40px;
            border-radius: 50%;
            background-color: #D5804F;
            display: flex;
            align-items: center;
            justify-content: center;
            transition: all 0.3s ease;
        }
        
        .icon:hover {
            transform: translateY(-5px) rotate(5deg);
            box-shadow: 0 5px 10px rgba(213, 128, 79, 0.5);
        }
        
        @media (max-width: 768px) {
            h1 {
                font-size: 2.2rem;
            }
            
            .stats-container {
                flex-direction: column;
            }
            
            .stat-box {
                min-width: 100%;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div align="center">
            <h1>대 으화 / Dae Euhwa</h1>
            
            <div class="stats-container">
                <div class="stat-box">
                    <img src="https://github-readme-stats.vercel.app/api?username=daedaevibin&show_icons=true&title_color=D5804F&icon_color=A77250&text_color=F5DEB3&bg_color=1A1A1A" alt="GitHub Stats" width="100%"/>
                </div>
                <div class="stat-box">
                    <img src="https://github-readme-streak-stats.herokuapp.com?user=daedaevibin&theme=dark&background=1A1A1A&ring=D5804F&fire=A77250&currStreakLabel=D5804F&sideNums=F5DEB3&dates=F5DEB3&sideLabels=A77250" alt="Streak Stats" width="100%"/>
                </div>
            </div>

            <div class="content">
                <h2>About Me</h2>
                <p>I'm a passionate hobbyist developer who is tired of big companies.</p>
                
                <h2>Website</h2>
                <ul>
                    <li><a href="https://vz.trangled.net:777" target="_blank">vz.strangled.net</a></li>
                </ul>

                <h2>Connect with me</h2>
                <ul>
                    <li><a href="https://discord.com/users/daedaevibin/" target="_blank">Discord</a></li>
                    <li><a href="https://www.instagram.com/daedaevibin/" target="_blank">Instagram</a></li>
                    <li><a href="https://matrix.to/#/@daedaevibin:matrix.org" target="_blank">Matrix</a></li>
                </ul>
                
                <div class="social-icons">
                    <a href="https://discord.com/users/daedaevibin/" target="_blank" class="icon">D</a>
                    <a href="https://www.instagram.com/daedaevibin/" target="_blank" class="icon">I</a>
                    <a href="https://matrix.to/#/@daedaevibin:matrix.org" target="_blank" class="icon">M</a>
                </div>
            </div>
        </div>
    </div>
</body>
</html>