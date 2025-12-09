<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>minoveaz — README as HTML</title>
  <style>
    :root{
      --max-width:900px;
      --accent:#0366d6;
      --muted:#6b7280;
      --card-bg:#f8fafc;
      --mono: ui-monospace, SFMono-Regular, Menlo, Monaco, "Roboto Mono", "Segoe UI Mono", monospace;
      --serif: "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
    }
    body{
      font-family: var(--serif);
      line-height:1.6;
      color:#111827;
      background: #fff;
      display:flex;
      justify-content:center;
      padding:32px 16px;
    }
    .container{
      width:100%;
      max-width:var(--max-width);
    }
    header{
      display:flex;
      gap:16px;
      align-items:center;
      margin-bottom:18px;
    }
    header img.avatar{
      width:88px;
      height:88px;
      border-radius:12px;
      object-fit:cover;
      box-shadow:0 6px 18px rgba(2,6,23,0.08);
    }
    h1{ margin:0; font-size:1.6rem; }
    p.lead{ margin:6px 0 0; color:var(--muted); }

    .section{ background:var(--card-bg); padding:18px; border-radius:12px; margin-top:16px; }
    .badges img{ vertical-align:middle; margin-right:6px; }
    .projects{ display:flex; gap:12px; flex-wrap:wrap; margin-top:12px; }
    .project-card{
      flex:1 1 300px;
      background:white;
      border-radius:10px;
      padding:12px;
      box-shadow:0 6px 18px rgba(2,6,23,0.04);
      text-decoration:none;
      color:inherit;
    }
    .project-card h4{ margin:4px 0; }
    .meta{ color:var(--muted); font-size:0.95rem; }

    .follow a{ display:inline-block; margin-right:8px; margin-bottom:8px; text-decoration:none; }
    .techs img{ vertical-align:middle; margin:6px 6px 6px 0; }

    .stats-row{ display:flex; gap:12px; flex-wrap:wrap; margin-top:12px; align-items:center; }
    .waka pre{
      background:#0b1220;
      color:#d1d5db;
      padding:14px;
      border-radius:8px;
      overflow:auto;
      font-family:var(--mono);
      font-size:13px;
      line-height:1.3;
    }

    footer{ text-align:center; margin-top:18px; color:var(--muted); font-size:0.95rem; }
    /* Responsive */
    @media (max-width:680px){
      header{ flex-direction:column; align-items:flex-start; gap:8px; }
      .projects{ flex-direction:column; }
    }
  </style>
</head>
<body>
  <div class="container" role="main">
    <header>
      <!-- avatar placeholder (optional) -->
      <img class="avatar" src="https://github.com/minoveaz.png" alt="minoveaz avatar" />
      <div>
        <h1>Hi there <span aria-hidden="true">👋</span></h1>
        <p class="lead">
          🌱 I’m currently learning Web Development Technologies in Frontend
          <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/angularjs/angularjs-original.svg" alt="angular-js" width="20" height="20" />
          <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" alt="react" width="20" height="20" />
          Backend
          <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" alt="nodejs" width="20" height="20" />
          and Databases (MongoDB). I like to use GCP for Cloud Solutions. :octocat:
        </p>
      </div>
    </header>

    <section class="section">
      <h3>🚀 Some of my main projects</h3>

      <div class="projects">
        <a class="project-card" href="https://github.com/minoveaz/angular-web-portfolio" target="_blank" rel="noopener noreferrer">
          <h4>angular-web-portfolio</h4>
          <p class="meta">Personal web portfolio built with Angular.</p>
          <img src="https://github-readme-stats.vercel.app/api/pin/?username=minoveaz&repo=angular-web-portfolio" alt="angular repo card" style="width:100%; margin-top:8px; border-radius:8px;" />
        </a>

        <a class="project-card" href="https://github.com/minoveaz/node-app" target="_blank" rel="noopener noreferrer">
          <h4>node-app</h4>
          <p class="meta">Server-side app using Node.js and MongoDB.</p>
          <img src="https://github-readme-stats.vercel.app/api/pin/?username=minoveaz&repo=node-app" alt="node repo card" style="width:100%; margin-top:8px; border-radius:8px;" />
        </a>
      </div>

      <p style="margin-top:12px;">
        - 🤖 I work in <strong>Deloitte Robotics Spain</strong><br>
        - :bar_chart: I love Stats and make cool Dashboards
      </p>

      <p style="margin-top:10px;">
        <strong>Born in Bogotá, Colombia</strong>
        <img src="https://image.flaticon.com/icons/svg/197/197575.svg" width="13" alt="Colombia" />
        &nbsp;&nbsp;
        <strong>Living in Madrid, Spain</strong>
        <img src="https://image.flaticon.com/icons/svg/197/197593.svg" width="13" alt="Spain" />
      </p>
    </section>

    <section class="section follow" aria-label="Follow">
      <h3>Follow Me</h3>

      <div style="margin-top:8px;">
        <a href="mailto:ing.miller.vega@gmail.com" title="Email">
          <img src="https://img.shields.io/badge/-ing.miller.vega@gmail.com-c14438?style=flat-square&logo=Gmail&logoColor=white" alt="Gmail Badge" />
        </a>
        <a href="https://www.linkedin.com/in/minoveaz/" target="_blank" rel="noopener noreferrer" title="LinkedIn">
          <img src="https://img.shields.io/badge/-minoveaz-blue?style=flat-square&logo=Linkedin&logoColor=white" alt="LinkedIn Badge" />
        </a>
        <a href="https://github.com/minoveaz" target="_blank" rel="noopener noreferrer" title="GitHub">
          <img src="https://img.shields.io/badge/-GitHub-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub Badge" />
        </a>
        <a href="https://twitter.com/intent/follow?screen_name=minoveaz" target="_blank" rel="noopener noreferrer" title="Twitter">
          <img src="https://img.shields.io/badge/-@minoveaz-00acee?style=flat&logo=Twitter&logoColor=white" alt="Twitter Badge" />
        </a>
      </div>
    </section>

    <section class="section">
      <h3>⚡ Technologies</h3>
      <div class="techs" style="margin-top:8px;">
        <img src="https://img.shields.io/badge/-JavaScript-black?style=flat-square&logo=javascript" alt="JavaScript" />
        <img src="https://img.shields.io/badge/-Nodejs-black?style=flat-square&logo=Node.js" alt="Nodejs" />
        <img src="https://img.shields.io/badge/-HTML5-E34F26?style=flat-square&logo=html5&logoColor=white" alt="HTML5" />
        <img src="https://img.shields.io/badge/-CSS3-1572B6?style=flat-square&logo=css3" alt="CSS3" />
        <img src="https://img.shields.io/badge/-Bootstrap-563D7C?style=flat-square&logo=bootstrap" alt="Bootstrap" />
        <img src="https://img.shields.io/badge/-MongoDB-black?style=flat-square&logo=mongodb" alt="MongoDB" />
        <img src="https://img.shields.io/badge/Google%20Cloud-black?style=flat-square&logo=google-cloud" alt="Google Cloud" />
        <img src="https://img.shields.io/badge/-Git-black?style=flat-square&logo=git" alt="Git" />
        <img src="https://img.shields.io/badge/-GitHub-181717?style=flat-square&logo=github" alt="GitHub" />
        <img src="https://img.shields.io/badge/-BitBucket-darkblue?style=flat-square&logo=bitbucket" alt="Bitbucket" />
      </div>
    </section>

    <section class="section">
      <h3>GitHub Stats</h3>
      <div class="stats-row">
        <img src="https://github-readme-stats.vercel.app/api?username=minoveaz&count_private=true&show_icons=true" alt="Github Stats" style="border-radius:8px; max-width:100%;" />
        <a href="https://github.com/anuraghazra/github-readme-stats" target="_blank" rel="noopener noreferrer">
          <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=minoveaz&layout=compact" alt="Top languages" style="border-radius:8px; max-width:260px;" />
        </a>
        <img src="https://visitor-badge.glitch.me/badge?page_id=minoveaz" alt="visitor badge" style="height:36px; border-radius:6px;" />
      </div>
    </section>

    <section class="section waka">
      <h3>Activity / Waka</h3>

      <p><img src="http://img.shields.io/badge/Code%20Time-643%20hrs-blue" alt="Code Time" /> <img src="http://img.shields.io/badge/Profile%20Views-108-blue" alt="Profile Views" /></p>

      <h4 style="margin-top:12px;">🐱 My GitHub Data</h4>
      <pre>
📦 125.2 kB Used in GitHub's Storage
🏆 39 Contributions in the Year 2025
🚫 Not Opted to Hire
📜 24 Public Repositories
🔑 5 Private Repositories

I'm a Night 🦉

🌞 Morning                33 commits          ██░░░░░░░░░░░░░░░░░░░░░░░   07.14 %
🌆 Daytime                85 commits          █████░░░░░░░░░░░░░░░░░░░░   18.40 %
🌃 Evening                292 commits         ████████████████░░░░░░░░░   63.20 %
🌙 Night                  52 commits          ███░░░░░░░░░░░░░░░░░░░░░░   11.26 %

📅 I'm Most Productive on Wednesday

Monday                   82 commits          ████░░░░░░░░░░░░░░░░░░░░░   17.75 %
Tuesday                  83 commits          ████░░░░░░░░░░░░░░░░░░░░░   17.97 %
Wednesday                108 commits         ██████░░░░░░░░░░░░░░░░░░░   23.38 %
Thursday                 73 commits          ████░░░░░░░░░░░░░░░░░░░░░   15.80 %
Friday                   61 commits          ███░░░░░░░░░░░░░░░░░░░░░░   13.20 %
Saturday                 33 commits          ██░░░░░░░░░░░░░░░░░░░░░░░   07.14 %
Sunday                   22 commits          █░░░░░░░░░░░░░░░░░░░░░░░░   04.76 %

This Week I Spent My Time On

Time Zone: Europe/Madrid

Programming Languages:
HTML                     11 hrs 48 mins      ████████████████░░░░░░░░░   62.40 %
Markdown                 3 hrs 7 mins        ████░░░░░░░░░░░░░░░░░░░░░   16.51 %
CSS                      2 hrs 22 mins       ███░░░░░░░░░░░░░░░░░░░░░░   12.57 %
JavaScript               58 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   05.18 %
YAML                     12 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   01.07 %

Editors:
VS Code                  18 hrs 55 mins      █████████████████████████   100.00 %

Projects:
Coding                   12 hrs 34 mins      █████████████████░░░░░░░░   66.43 %
Robot 4                  5 hrs 32 mins       ███████░░░░░░░░░░░░░░░░░░   29.31 %
CRM                      35 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   03.15 %
codespaces-blank         12 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   01.11 %

Operating System:
Windows                  18 hrs 7 mins       ████████████████████████░   95.74 %
Linux                    48 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   04.26 %
      </pre>

      <p style="font-size:0.9rem; color:var(--muted); margin-top:8px;">
        <em>Timeline / Lines of Code chart</em><br/>
        <img src="https://raw.githubusercontent.com/minoveaz/minoveaz/master/assets/bar_graph.png" alt="Lines of Code chart" style="max-width:100%; border-radius:8px; margin-top:8px;" />
        <br/>
        <small>Last Updated on 08/12/2025 18:52:45 UTC</small>
      </p>
    </section>

    <footer>
      <p>💻 Check Out My Repos — <a href="https://github.com/minoveaz" target="_blank" rel="noopener noreferrer">github.com/minoveaz</a></p>
    </footer>
  </div>
</body>
</html>

