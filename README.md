<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>README Preview</title>
<style>
  :root{
    --bg:#0d1117; --bg-card:#161b22; --border:#30363d;
    --text:#c9d1d9; --text-dim:#8b949e; --accent:#00FFC8; --link:#58a6ff;
  }
  *{box-sizing:border-box;}
  body{
    margin:0; background:var(--bg); color:var(--text);
    font-family:-apple-system,BlinkMacSystemFont,"Segoe UI",Helvetica,Arial,sans-serif;
    line-height:1.6;
  }
  .wrap{max-width:900px;margin:0 auto;padding:40px 24px;}
  .browser-chrome{
    max-width:900px;margin:24px auto 0;background:#161b22;border:1px solid var(--border);
    border-radius:10px 10px 0 0;padding:10px 14px;display:flex;align-items:center;gap:8px;
  }
  .dot{width:11px;height:11px;border-radius:50%;}
  .dot.r{background:#ff5f56;} .dot.y{background:#ffbd2e;} .dot.g{background:#27c93f;}
  .url{margin-left:12px;font-family:ui-monospace,monospace;font-size:12px;color:var(--text-dim);
    background:#0d1117;padding:4px 10px;border-radius:6px;flex:1;}
  .frame{max-width:900px;margin:0 auto;border:1px solid var(--border);border-top:none;border-radius:0 0 10px 10px;overflow:hidden;}

  center, .center{text-align:center;}
  img.banner{width:100%;display:block;border-radius:8px;margin-bottom:16px;}
  code.block{
    display:block;background:#010409;border:1px solid var(--border);border-radius:8px;
    padding:16px;font-family:ui-monospace,"SF Mono",Menlo,monospace;font-size:13px;
    color:#c9d1d9; white-space:pre; overflow-x:auto; margin:16px 0; text-align:left;
  }
  .kw{color:#ff7b72;} .str{color:var(--accent);} .prop{color:#79c0ff;} .com{color:var(--text-dim);}
  .typing{
    font-family:ui-monospace,monospace;color:var(--accent);text-align:center;font-size:18px;
    margin:14px 0 20px;min-height:26px;
  }
  .badges{text-align:center;margin:14px 0;}
  .badge{
    display:inline-block;padding:6px 14px;border-radius:6px;font-size:12px;font-weight:600;
    margin:4px;color:#fff;
  }
  .b-linkedin{background:#0A66C2;} .b-github{background:#181717;border:1px solid #30363d;}
  .b-portfolio{background:var(--accent);color:#0d1117;} .b-visits{background:var(--accent);color:#0d1117;}

  h2.section{
    font-size:20px;border-bottom:1px solid var(--border);padding-bottom:8px;margin-top:36px;
  }
  h2.section .num{color:var(--accent);font-family:ui-monospace,monospace;margin-right:6px;}
  p.sub{color:var(--text-dim);}

  table{width:100%;border-collapse:collapse;margin:12px 0;font-size:14px;}
  td,th{border:1px solid var(--border);padding:8px 12px;text-align:left;}
  tr:nth-child(odd){background:#161b22;}

  .skillrow{display:flex;align-items:center;gap:12px;margin:10px 0;}
  .skillname{width:150px;font-size:13px;color:var(--text);flex-shrink:0;}
  .barbg{flex:1;background:#010409;border:1px solid var(--border);border-radius:6px;height:16px;overflow:hidden;}
  .barfill{height:100%;background:linear-gradient(90deg,#00FFC8,#00b894);}
  .pct{width:44px;text-align:right;font-size:12px;color:var(--text-dim);}
  .note{font-size:12px;color:var(--text-dim);margin-top:6px;}

  .repo-grid{display:grid;grid-template-columns:1fr 1fr;gap:14px;margin:14px 0;}
  .repo-card{
    border:1px solid var(--border);border-radius:8px;padding:14px;background:#161b22;
  }
  .repo-card .name{color:var(--link);font-weight:600;font-size:14px;margin-bottom:6px;}
  .repo-card .desc{font-size:12px;color:var(--text-dim);margin-bottom:10px;height:32px;}
  .repo-card .meta{font-size:12px;color:var(--text-dim);display:flex;gap:14px;}
  .dotlang{display:inline-block;width:9px;height:9px;border-radius:50%;background:var(--accent);margin-right:4px;}

  details{border:1px solid var(--border);border-radius:8px;padding:10px 14px;margin:10px 0;background:#161b22;}
  summary{cursor:pointer;font-weight:600;font-size:13px;}

  .warn{
    border-left:3px solid #f0883e;background:#3a2a10;color:#f0c674;font-size:12.5px;
    padding:10px 14px;border-radius:0 6px 6px 0;margin:14px 0;
  }
  .divider{border:none;border-top:1px solid var(--border);margin:32px 0;}
  .footer{text-align:center;color:var(--text-dim);font-size:13px;margin-top:30px;}
  .footer .accent{color:var(--accent);}
  .fadewrap{position:relative;}
  .fadewrap::after{
    content:"↓ rest of README (Achievements, Certifications, Tech Stack, GitHub Analytics, Goals) stays exactly as you had it ↓";
    display:block;text-align:center;font-size:12px;color:var(--text-dim);padding:24px 10px;
    border-top:1px dashed var(--border);margin-top:20px;
  }
</style>
</head>
<body>

<div class="browser-chrome">
  <div class="dot r"></div><div class="dot y"></div><div class="dot g"></div>
  <div class="url">github.com / MannatRawat-22</div>
</div>

<div class="frame">
<div class="wrap">

  <div class="center">
    <img class="banner" src="https://raw.githubusercontent.com/MannatRawat-22/MannatRawat-22/main/images/banner.png" onerror="this.style.display='none'">

    <code class="block"><span class="kw">const</span> mannat = {
  <span class="prop">role</span>: <span class="str">"Full Stack Web Developer"</span>,
  <span class="prop">education</span>: <span class="str">"BCA @ SRM Institute of Science & Technology, Delhi NCR"</span>,
  <span class="prop">focus</span>: [<span class="str">"MERN Stack"</span>, <span class="str">"AI-Powered Interfaces"</span>, <span class="str">"Cybersecurity Fundamentals"</span>],
  <span class="prop">status</span>: <span class="str">"🟢 open to Web Development Internships"</span>,
  <span class="prop">currentlyBuilding</span>: <span class="str">"production-grade full stack projects"</span>
};</code>

    <div class="typing" id="typing"></div>

    <div class="badges">
      <span class="badge b-linkedin">LinkedIn</span>
      <span class="badge b-github">GitHub</span>
      <span class="badge b-portfolio">Portfolio</span>
      <span class="badge b-visits">👁 1,204 profile views</span>
    </div>
  </div>

  <h2 class="section"><span class="num">01</span>About</h2>
  <p>I turn ideas into responsive, production-ready web apps — and I'm never more than one tab away from documentation for something new. Currently deep in the MERN stack, poking at AI-driven interfaces, and picking up cybersecurity fundamentals along the way.</p>
  <table>
    <tr><td>🎓</td><td>BCA Student, 2025 – 2028</td></tr>
    <tr><td>🧠</td><td>Learning: React · Node · Express · MongoDB · REST APIs · Auth · Cybersecurity</td></tr>
    <tr><td>🛠</td><td>Building clean, accessible, responsive UI</td></tr>
    <tr><td>📡</td><td>Open to Web Development Internships</td></tr>
  </table>

  <h2 class="section"><span class="num">02</span>Skill Matrix</h2>
  <div id="skills"></div>
  <p class="note">Percentages are self-rated confidence, not a certification — a compass, not a scoreboard.</p>

  <h2 class="section"><span class="num">03</span>Experience Log</h2>
  <code class="block com">$ git log --oneline --graph --all</code>
  <table>
    <tr><th>Role</th><th>Organization</th><th>Focus</th></tr>
    <tr><td>💻 Web Development Intern</td><td>Prodigy InfoTech</td><td>Responsive websites, modern UI</td></tr>
    <tr><td>🤖 Front-end AI Engineering Intern</td><td>FlyRank AI</td><td>AI-powered web interfaces</td></tr>
    <tr><td>🛡 Cyber Security Intern</td><td>CodeAlpha</td><td>Networking & security fundamentals</td></tr>
    <tr><td>🎨 Web Dev & Designing Intern</td><td>Oasis Infobyte</td><td>Responsive web applications</td></tr>
    <tr><td>🌐 Web Dev & Designing Intern</td><td>Synent Technologies</td><td>Responsive websites, frontend</td></tr>
    <tr><td>❤️ AI & Web Development Intern</td><td>InAmigo</td><td>Frontend + AI-based web apps</td></tr>
    <tr><td>📈 Business Research Intern</td><td>Prashant Kumar LTD</td><td>Competitor research, market analysis</td></tr>
  </table>

  <h2 class="section"><span class="num">04</span>Featured Repositories</h2>
  <p class="sub">Live pinned repo cards pull real stars/forks/language stats straight from GitHub.</p>
  <div class="repo-grid" id="repos"></div>
  <div class="warn">⚠️ Pin cards only render for repos that actually exist and are public on your GitHub — swap the placeholder repo names (weather-app, chronos-stopwatch, etc.) for your real repo slugs.</div>

  <div class="fadewrap"></div>

</div>
</div>

<div class="footer">Preview approximates GitHub's dark-mode markdown rendering · actual look may vary slightly by theme</div>

<script>
const lines = [
  'console.log("Hello, World");',
  "Building Full Stack Web Applications",
  "Shipping Clean, Responsive UI",
  'git commit -m "learning something new"'
];
let li=0, ci=0, el=document.getElementById('typing');
function type(){
  if(ci<=lines[li].length){
    el.textContent = lines[li].slice(0,ci);
    ci++; setTimeout(type, 45);
  } else {
    setTimeout(()=>{ci=0; li=(li+1)%lines.length; type();}, 1200);
  }
}
type();

const skills = [
  ["JavaScript",80],["React.js",70],["Node / Express",65],
  ["MongoDB",60],["Python",75],["Cybersecurity Basics",45]
];
document.getElementById('skills').innerHTML = skills.map(([n,p])=>`
  <div class="skillrow">
    <div class="skillname">${n}</div>
    <div class="barbg"><div class="barfill" style="width:${p}%"></div></div>
    <div class="pct">${p}%</div>
  </div>`).join('');

const repos = [
  ["weather-app","Responsive weather app using a REST API","JavaScript","★ 4"],
  ["chronos-stopwatch","Real-time stopwatch with timer controls","JavaScript","★ 2"],
  ["responsive-landing-page","Modern landing page, smooth scroll","HTML","★ 3"],
  ["tic-tac-toe","Interactive browser Tic Tac Toe game","JavaScript","★ 2"],
  ["hopehands","Accessible NGO website","JavaScript","★ 5"],
  ["MannatRawat-22.github.io","Personal portfolio site","HTML","★ 6"]
];
document.getElementById('repos').innerHTML = repos.map(([n,d,l,s])=>`
  <div class="repo-card">
    <div class="name">📦 ${n}</div>
    <div class="desc">${d}</div>
    <div class="meta"><span><span class="dotlang"></span>${l}</span><span>${s}</span></div>
  </div>`).join('');
</script>

</body>
</html>
