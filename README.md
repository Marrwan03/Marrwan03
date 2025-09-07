<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Marwan Alawlaqi - .NET Developer</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/devicons/devicon@v2.15.1/devicon.min.css">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            background-color: #0d1117;
            color: #c9d1d9;
            line-height: 1.6;
            padding: 20px;
            max-width: 1000px;
            margin: 0 auto;
        }
        
        h1, h2, h3 {
            color: #58a6ff;
            margin: 20px 0;
        }
        
        h1 {
            font-size: 2.5rem;
            border-bottom: 2px solid #30363d;
            padding-bottom: 10px;
        }
        
        h2 {
            font-size: 1.8rem;
            margin-top: 30px;
        }
        
        h3 {
            font-size: 1.4rem;
            margin-top: 25px;
        }
        
        .container {
            background-color: #161b22;
            border-radius: 10px;
            padding: 30px;
            margin: 20px 0;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }
        
        .skills-container {
            display: flex;
            flex-wrap: wrap;
            gap: 15px;
            margin: 15px 0;
        }
        
        .skill-item {
            display: flex;
            align-items: center;
            background-color: #21262d;
            padding: 10px 15px;
            border-radius: 6px;
            border: 1px solid #30363d;
        }
        
        .skill-item img {
            margin-right: 10px;
            width: 30px;
            height: 30px;
        }
        
        .stats-container {
            display: flex;
            justify-content: center;
            gap: 20px;
            flex-wrap: wrap;
            margin: 30px 0;
        }
        
        .stats-container img {
            border-radius: 10px;
            border: 1px solid #30363d;
        }
        
        .centered {
            text-align: center;
        }
        
        .social-links {
            display: flex;
            gap: 15px;
            margin: 20px 0;
            justify-content: center;
        }
        
        .social-links a {
            color: #58a6ff;
            font-size: 1.5rem;
            transition: color 0.3s;
        }
        
        .social-links a:hover {
            color: #79c0ff;
        }
        
        @media (max-width: 768px) {
            .stats-container {
                flex-direction: column;
                align-items: center;
            }
            
            .stats-container img {
                width: 100%;
                max-width: 400px;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1 align="left">Hi 👋! I'm Marwan Alawlaqi</h1>
        
        <h3 align="center">👨‍💻 - I am a Full stack desktop developer using .NET Framework, C#, SQL Server.</h3>
        
        <div class="social-links">
            <a href="https://www.linkedin.com/in/marwan-alawlaqi-0890192b5" target="_blank">
                <i class="fab fa-linkedin"></i>
            </a>
            <a href="https://github.com/Marrwan03" target="_blank">
                <i class="fab fa-github"></i>
            </a>
            <a href="https://youtube.com/@marwanal-awlaki" target="_blank">
                <i class="fab fa-youtube"></i>
            </a>
            <a href="mailto:MarwanAlawlaki2@gmail.com">
                <i class="fas fa-envelope"></i>
            </a>
        </div>
    </div>
    
    <div class="container">
        <h3 align="left">Languages:</h3>
        <div class="skills-container">
            <div class="skill-item">
                <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/csharp/csharp-original.svg" alt="C#" />
                <span>C#</span>
            </div>
            <div class="skill-item">
                <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/cplusplus/cplusplus-original.svg" alt="C++" />
                <span>C++</span>
            </div>
        </div>
        
        <h3 align="left">Frameworks:</h3>
        <div class="skills-container">
            <div class="skill-item">
                <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/dot-net/dot-net-original.svg" alt=".NET" />
                <span>.NET Framework</span>
            </div>
            <div class="skill-item">
                <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/dotnetcore/dotnetcore-original.svg" alt=".NET Core" />
                <span>ADO.NET</span>
            </div>
        </div>
        
        <h3 align="left">Databases:</h3>
        <div class="skills-container">
            <div class="skill-item">
                <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/microsoftsqlserver/microsoftsqlserver-plain.svg" alt="SQL Server" />
                <span>SQL Server</span>
            </div>
        </div>
        
        <h3 align="left">Tools & Technologies:</h3>
        <div class="skills-container">
            <div class="skill-item">
                <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/visualstudio/visualstudio-plain.svg" alt="Visual Studio" />
                <span>Visual Studio</span>
            </div>
            <div class="skill-item">
                <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/windows8/windows8-original.svg" alt="Windows" />
                <span>Windows Forms</span>
            </div>
            <div class="skill-item">
                <i class="fas fa-database" style="font-size: 24px; margin-right: 10px;"></i>
                <span>T-SQL</span>
            </div>
        </div>
    </div>
    
    <div class="container">
        <h3 align="left">Build my projects using:</h3>
        <div class="skills-container">
            <div class="skill-item">
                <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/visualstudio/visualstudio-plain.svg" alt="Visual Studio" />
                <span>Visual Studio</span>
            </div>
        </div>
        
        <br clear="both">
        
        <div class="stats-container">
            <img src="https://github-readme-stats.vercel.app/api?username=Marrwan03&hide_title=false&hide_rank=false&show_icons=true&include_all_commits=true&count_private=true&disable_animations=false&theme=dracula&locale=en&hide_border=false&order=1" alt="GitHub stats" />
            <img src="https://github-readme-stats.vercel.app/api/top-langs?username=Marrwan03&locale=en&hide_title=false&layout=compact&card_width=320&langs_count=5&theme=dracula&hide_border=false&order=2" alt="Top languages" />
        </div>
    </div>
    
    <div class="container">
        <h2>Featured Projects</h2>
        
        <h3>🚗 Driving & Vehicle License Department (DVLD) - Version 1.1</h3>
        <p>A comprehensive desktop application for managing local and international driving licenses with modern UI and complete operational management.</p>
        <p><strong>Technologies:</strong> .NET Framework (C#), SQL Server, WinForms</p>
        <p>
            <a href="https://youtu.be/uLdCdyXtdwI" target="_blank">📺 YouTube Demo</a> | 
            <a href="https://github.com/Marrwan03/DVLD-Version1.1" target="_blank">💻 GitHub Code</a>
        </p>
        
        <h3>💾 Database Backup Windows Service</h3>
        <p>Automated database backup solution with version monitoring and integrity verification.</p>
        <p><strong>Technologies:</strong> .NET Framework (C#), SQL Server, FileSystemWatcher</p>
        <p>
            <a href="https://youtu.be/Iwdep2kdi0s" target="_blank">📺 YouTube Demo</a> | 
            <a href="https://github.com/Marrwan03/Database-Backup" target="_blank">💻 GitHub Code</a>
        </p>
        
        <h3>📁 File Monitoring Windows Service</h3>
        <p>Folder monitoring service with automated file processing and logging capabilities.</p>
        <p><strong>Technologies:</strong> .NET Framework (C#), FileSystemWatcher</p>
        <p>
            <a href="https://youtu.be/QLLA7U1FuvA" target="_blank">📺 YouTube Demo</a> | 
            <a href="https://github.com/Marrwan03/File-Monitoring-Windows-Service" target="_blank">💻 GitHub Code</a>
        </p>
        
        <p class="centered">
            <a href="https://github.com/Marrwan03?tab=repositories" target="_blank">View all projects →</a>
        </p>
    </div>
</body>
</html>
