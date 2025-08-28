<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Jocode | Skills You’ll Learn</title>

  <!-- Devicon (icons) -->
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/devicons/devicon@v2.15.1/devicon.min.css"/>

  <style>
    :root{
      --bg: #0b0f14;
      --card: #0f1520;
      --text: #e6edf3;
      --muted:#8b9bb0;
      --ring: rgba(255,255,255,.12);

      /* Brand colors */
      --html:#E34F26; --css:#1572B6; --js:#F7DF1E; --react:#61DAFB;
      --node:#339933; --express:#111111; --mongodb:#47A248; --mysql:#00758F;
      --git:#F05032; --github:#181717; --tailwind:#38B2AC; --bootstrap:#7952B3;
      --next:#000000; --firebase:#FFCA28; --supabase:#3ECF8E; --stripe:#635BFF;
      --youtube:#FF0000; --unsplash:#000000;
    }

    *{box-sizing:border-box}
    html,body{height:100%}
    body{
      margin:0;
      font-family: system-ui, -apple-system, Segoe UI, Roboto, Ubuntu, "Helvetica Neue", Arial, "Noto Sans", "Liberation Sans", sans-serif;
      background: radial-gradient(1200px 800px at 10% -10%, #122033 0%, transparent 60%),
                  radial-gradient(900px 600px at 110% 10%, #1a2130 0%, transparent 60%),
                  var(--bg);
      color:var(--text);
    }

    .wrap{
      max-width:1100px;
      margin:0 auto;
      padding:48px 20px 80px;
    }

    .title{
      font-size: clamp(28px, 3.4vw, 40px);
      line-height:1.1;
      margin:0 0 10px;
      letter-spacing:.2px;
    }
    .sub{
      color:var(--muted);
      margin:0 0 28px;
      font-size:clamp(14px, 1.8vw, 16px);
    }

    .skills{
      display:grid;
      grid-template-columns: repeat(auto-fit, minmax(180px, 1fr));
      gap:16px;
    }

    .skill-btn{
      display:flex;
      align-items:center;
      gap:12px;
      padding:14px 16px;
      border-radius:16px;
      text-decoration:none;
      color:#fff;
      box-shadow: 0 0 0 1px var(--ring) inset, 0 10px 20px rgba(0,0,0,.25);
      transition: transform .15s ease, box-shadow .15s ease, filter .15s ease;
      will-change: transform, filter;
    }
    .skill-btn:hover{ transform: translateY(-2px); filter: brightness(1.05); }
    .skill-btn:active{ transform: translateY(0); filter: brightness(.98); }

    .icon-wrap{
      display:inline-grid;
      place-items:center;
      width:42px; height:42px;
      border-radius:12px;
      background: rgba(255,255,255,.15);
      box-shadow: 0 1px 0 rgba(255,255,255,.15) inset;
      flex: 0 0 42px;
    }
    .skill-btn i{ font-size:22px; color:#fff; }

    .label{
      display:flex;
      flex-direction:column;
      line-height:1.15;
    }
    .label b{ font-size:15px; font-weight:700; letter-spacing:.2px; }
    .label span{ font-size:12px; opacity:.85; }

    /* Brand backgrounds */
    .html{ background: var(--html); }
    .css{ background: var(--css); }
    .js{ background: var(--js); }
    .react{ background: var(--react); color:#0b1b22; }
    .node{ background: var(--node); }
    .express{ background: var(--express); }
    .mongodb{ background: var(--mongodb); }
    .mysql{ background: var(--mysql); }
    .git{ background: var(--git); }
    .github{ background: var(--github); }
    .tailwind{ background: var(--tailwind); }
    .bootstrap{ background: var(--bootstrap); }
    .next{ background: var(--next); }
    .firebase{ background: var(--firebase); color:#1a1a1a; }
    .supabase{ background: var(--supabase); color:#0f1a14; }
    .stripe{ background: var(--stripe); }
    .youtube{ background: var(--youtube); }
    .unsplash{ background: var(--unsplash); }

    /* Ensure icon contrast on light backgrounds */
    .js i, .firebase i { color:#111; }
    .react i, .supabase i { color:#0a0a0a; }
    .label.darktext b, .label.darktext span { color:#0b0f14; }
  </style>
</head>
<body>
  <main class="wrap">
    <h1 class="title">Skills you’ll learn on <span style="opacity:.9;">Jocode</span></h1>
    <p class="sub">Beginner-friendly code + real projects. Click any to explore in the repo or pair with your YouTube lesson links.</p>

    <section class="skills">

      <!-- Web fundamentals -->
      <a class="skill-btn html" href="#" aria-label="HTML">
        <span class="icon-wrap"><i class="devicon-html5-plain"></i></span>
        <span class="label"><b>HTML5</b><span>structure</span></span>
      </a>

      <a class="skill-btn css" href="#" aria-label="CSS">
        <span class="icon-wrap"><i class="devicon-css3-plain"></i></span>
        <span class="label"><b>CSS3</b><span>layouts & flex/grid</span></span>
      </a>

      <a class="skill-btn js" href="#" aria-label="JavaScript">
        <span class="icon-wrap"><i class="devicon-javascript-plain"></i></span>
        <span class="label darktext"><b>JavaScript</b><span>DOM, fetch, ES6+</span></span>
      </a>

      <!-- Frontend frameworks -->
      <a class="skill-btn react" href="#" aria-label="React">
        <span class="icon-wrap"><i class="devicon-react-original"></i></span>
        <span class="label darktext"><b>React</b><span>hooks & router</span></span>
      </a>

      <a class="skill-btn tailwind" href="#" aria-label="Tailwind CSS">
        <span class="icon-wrap"><i class="devicon-tailwindcss-plain"></i></span>
        <span class="label"><b>Tailwind</b><span>utility-first CSS</span></span>
      </a>

      <a class="skill-btn bootstrap" href="#" aria-label="Bootstrap">
        <span class="icon-wrap"><i class="devicon-bootstrap-plain"></i></span>
        <span class="label"><b>Bootstrap</b><span>rapid UI</span></span>
      </a>

      <a class="skill-btn next" href="#" aria-label="Next.js">
        <span class="icon-wrap"><i class="devicon-nextjs-original"></i></span>
        <span class="label"><b>Next.js</b><span>SSR & routing</span></span>
      </a>

      <!-- Backend & DB -->
      <a class="skill-btn node" href="#" aria-label="Node.js">
        <span class="icon-wrap"><i class="devicon-nodejs-plain"></i></span>
        <span class="label"><b>Node.js</b><span>runtime</span></span>
      </a>

      <a class="skill-btn express" href="#" aria-label="Express">
        <span class="icon-wrap"><i class="devicon-express-original"></i></span>
        <span class="label"><b>Express</b><span>REST APIs</span></span>
      </a>

      <a class="skill-btn mysql" href="#" aria-label="MySQL">
        <span class="icon-wrap"><i class="devicon-mysql-plain"></i></span>
        <span class="label"><b>MySQL</b><span>SQL & schema</span></span>
      </a>

      <a class="skill-btn mongodb" href="#" aria-label="MongoDB">
        <span class="icon-wrap"><i class="devicon-mongodb-plain"></i></span>
        <span class="label"><b>MongoDB</b><span>NoSQL</span></span>
      </a>

      <!-- Services -->
      <a class="skill-btn firebase" href="#" aria-label="Firebase">
        <span class="icon-wrap"><i class="devicon-firebase-plain"></i></span>
        <span class="label darktext"><b>Firebase</b><span>auth & db</span></span>
      </a>

      <a class="skill-btn supabase" href="#" aria-label="Supabase">
        <span class="icon-wrap"><i class="devicon-supabase-plain"></i></span>
        <span class="label darktext"><b>Supabase</b><span>Postgres + auth</span></span>
      </a>

      <a class="skill-btn stripe" href="#" aria-label="Stripe">
        <span class="icon-wrap"><i class="devicon-stripe-plain"></i></span>
        <span class="label"><b>Stripe</b><span>payments</span></span>
      </a>

      <!-- Tools -->
      <a class="skill-btn git" href="#" aria-label="Git">
        <span class="icon-wrap"><i class="devicon-git-plain"></i></span>
        <span class="label"><b>Git</b><span>version control</span></span>
      </a>

      <a class="skill-btn github" href="#" aria-label="GitHub">
        <span class="icon-wrap"><i class="devicon-github-original"></i></span>
        <span class="label"><b>GitHub</b><span>projects & CI</span></span>
      </a>

      <!-- Media/APIs -->
      <a class="skill-btn youtube" href="#" aria-label="YouTube API">
        <span class="icon-wrap"><i class="devicon-youtube-plain"></i></span>
        <span class="label"><b>YouTube API</b><span>data & embeds</span></span>
      </a>

      <a class="skill-btn unsplash" href="#" aria-label="Unsplash API">
        <span class="icon-wrap"><i class="devicon-photoshop-plain"></i></span>
        <span class="label"><b>Unsplash API</b><span>images</span></span>
      </a>

    </section>
  </main>
</body>
</html>
