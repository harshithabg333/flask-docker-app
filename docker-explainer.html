<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Docker Explained Simply</title>
<link href="https://fonts.googleapis.com/css2?family=Syne:wght@400;700;800&family=IBM+Plex+Mono:wght@400;600&family=DM+Sans:wght@300;400;500&display=swap" rel="stylesheet">
<style>
  :root {
    --bg: #0d1117;
    --card: #161b22;
    --card2: #1c2330;
    --border: #30363d;
    --blue: #2188ff;
    --cyan: #39d5c4;
    --orange: #f78166;
    --yellow: #e3b341;
    --green: #56d364;
    --text: #e6edf3;
    --muted: #8b949e;
  }

  * { margin: 0; padding: 0; box-sizing: border-box; }

  body {
    background: var(--bg);
    color: var(--text);
    font-family: 'DM Sans', sans-serif;
    line-height: 1.6;
  }

  /* HERO */
  .hero {
    text-align: center;
    padding: 80px 24px 60px;
    background: radial-gradient(ellipse 80% 60% at 50% 0%, #1a2a4a 0%, var(--bg) 70%);
    border-bottom: 1px solid var(--border);
    position: relative;
    overflow: hidden;
  }
  .hero::before {
    content: '';
    position: absolute;
    inset: 0;
    background: url("data:image/svg+xml,%3Csvg width='60' height='60' viewBox='0 0 60 60' xmlns='http://www.w3.org/2000/svg'%3E%3Cg fill='none' fill-rule='evenodd'%3E%3Cg fill='%232188ff' fill-opacity='0.04'%3E%3Cpath d='M36 34v-4h-2v4h-4v2h4v4h2v-4h4v-2h-4zm0-30V0h-2v4h-4v2h4v4h2V6h4V4h-4zM6 34v-4H4v4H0v2h4v4h2v-4h4v-2H6zM6 4V0H4v4H0v2h4v4h2V6h4V4H6z'/%3E%3C/g%3E%3C/g%3E%3C/svg%3E");
    pointer-events: none;
  }
  .whale-emoji { font-size: 72px; display: block; margin-bottom: 16px; animation: float 3s ease-in-out infinite; }
  @keyframes float { 0%,100%{transform:translateY(0)} 50%{transform:translateY(-12px)} }
  .hero h1 {
    font-family: 'Syne', sans-serif;
    font-size: clamp(2rem, 6vw, 3.5rem);
    font-weight: 800;
    letter-spacing: -1px;
    background: linear-gradient(135deg, #fff 30%, var(--cyan));
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    background-clip: text;
    margin-bottom: 12px;
  }
  .hero p {
    color: var(--muted);
    font-size: 1.1rem;
    max-width: 540px;
    margin: 0 auto;
  }

  /* NAV DOTS */
  .nav-dots {
    display: flex;
    justify-content: center;
    gap: 8px;
    padding: 24px;
    position: sticky;
    top: 0;
    z-index: 100;
    background: rgba(13,17,23,0.92);
    backdrop-filter: blur(12px);
    border-bottom: 1px solid var(--border);
  }
  .nav-dot {
    padding: 6px 16px;
    border-radius: 20px;
    border: 1px solid var(--border);
    font-size: 0.78rem;
    font-family: 'IBM Plex Mono', monospace;
    cursor: pointer;
    transition: all 0.2s;
    color: var(--muted);
    background: none;
    white-space: nowrap;
  }
  .nav-dot:hover, .nav-dot.active { background: var(--blue); border-color: var(--blue); color: #fff; }

  /* SECTIONS */
  section {
    max-width: 860px;
    margin: 0 auto;
    padding: 60px 24px;
    border-bottom: 1px solid var(--border);
  }
  .section-tag {
    font-family: 'IBM Plex Mono', monospace;
    font-size: 0.72rem;
    color: var(--cyan);
    letter-spacing: 2px;
    text-transform: uppercase;
    margin-bottom: 10px;
    display: block;
  }
  .section-title {
    font-family: 'Syne', sans-serif;
    font-size: clamp(1.6rem, 4vw, 2.2rem);
    font-weight: 700;
    margin-bottom: 20px;
    line-height: 1.2;
  }
  .section-title span { color: var(--cyan); }

  /* CARDS */
  .card {
    background: var(--card);
    border: 1px solid var(--border);
    border-radius: 12px;
    padding: 24px;
    margin-bottom: 16px;
  }
  .card-title {
    font-family: 'Syne', sans-serif;
    font-weight: 700;
    font-size: 1.05rem;
    margin-bottom: 8px;
  }
  .card p { color: var(--muted); font-size: 0.95rem; }

  /* PROBLEM SECTION */
  .problem-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
    gap: 16px;
    margin-top: 24px;
  }
  .problem-card {
    background: var(--card);
    border: 1px solid #3d1f1f;
    border-radius: 12px;
    padding: 24px;
    position: relative;
    overflow: hidden;
  }
  .problem-card::before {
    content: '';
    position: absolute;
    top: 0; left: 0; right: 0;
    height: 3px;
    background: var(--orange);
  }
  .problem-card .icon { font-size: 2rem; margin-bottom: 12px; }
  .problem-card h3 { font-family: 'Syne', sans-serif; font-size: 0.95rem; margin-bottom: 8px; color: var(--orange); }
  .problem-card p { color: var(--muted); font-size: 0.88rem; }

  /* ANALOGY BLOCK */
  .analogy-box {
    background: var(--card2);
    border: 1px solid #1e3a2f;
    border-radius: 14px;
    padding: 28px;
    margin-top: 24px;
    position: relative;
  }
  .analogy-box::before {
    content: '';
    position: absolute;
    top: 0; left: 0; right: 0;
    height: 3px;
    background: linear-gradient(90deg, var(--green), var(--cyan));
    border-radius: 14px 14px 0 0;
  }
  .analogy-label {
    font-family: 'IBM Plex Mono', monospace;
    font-size: 0.7rem;
    color: var(--green);
    letter-spacing: 2px;
    text-transform: uppercase;
    margin-bottom: 12px;
  }
  .analogy-box p { color: var(--muted); font-size: 0.95rem; margin-bottom: 10px; }
  .analogy-box p:last-child { margin-bottom: 0; }
  .analogy-box strong { color: var(--text); }

  /* IMAGE vs CONTAINER */
  .compare-wrap {
    display: grid;
    grid-template-columns: 1fr auto 1fr;
    gap: 16px;
    align-items: center;
    margin-top: 28px;
  }
  .compare-card {
    border-radius: 14px;
    padding: 28px 22px;
    text-align: center;
  }
  .compare-card.image-card {
    background: #1a1f35;
    border: 1px solid #2d3561;
  }
  .compare-card.container-card {
    background: #1a2a1f;
    border: 1px solid #2a4a30;
  }
  .compare-emoji { font-size: 3rem; display: block; margin-bottom: 14px; }
  .compare-card h3 {
    font-family: 'Syne', sans-serif;
    font-weight: 700;
    font-size: 1.15rem;
    margin-bottom: 10px;
  }
  .image-card h3 { color: var(--blue); }
  .container-card h3 { color: var(--green); }
  .compare-card p { color: var(--muted); font-size: 0.88rem; line-height: 1.6; }
  .compare-vs {
    font-family: 'Syne', sans-serif;
    font-size: 1.3rem;
    font-weight: 800;
    color: var(--muted);
    text-align: center;
  }
  .compare-tag {
    display: inline-block;
    font-family: 'IBM Plex Mono', monospace;
    font-size: 0.7rem;
    padding: 3px 10px;
    border-radius: 20px;
    margin-bottom: 10px;
  }
  .image-card .compare-tag { background: #1e2d5a; color: var(--blue); }
  .container-card .compare-tag { background: #1a3323; color: var(--green); }

  /* TABLE */
  .diff-table {
    width: 100%;
    border-collapse: collapse;
    margin-top: 24px;
    font-size: 0.9rem;
  }
  .diff-table th {
    background: var(--card2);
    padding: 12px 16px;
    text-align: left;
    font-family: 'IBM Plex Mono', monospace;
    font-size: 0.78rem;
    letter-spacing: 1px;
    color: var(--muted);
    border-bottom: 1px solid var(--border);
  }
  .diff-table td {
    padding: 12px 16px;
    border-bottom: 1px solid var(--border);
    vertical-align: top;
  }
  .diff-table tr:hover td { background: var(--card2); }
  .diff-table .attr { color: var(--muted); font-size: 0.85rem; }
  .diff-table .img-val { color: #7eb8ff; }
  .diff-table .con-val { color: var(--green); }

  /* KITCHEN ANALOGY */
  .kitchen-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(180px, 1fr));
    gap: 14px;
    margin-top: 24px;
  }
  .kitchen-card {
    background: var(--card);
    border: 1px solid var(--border);
    border-radius: 12px;
    padding: 20px;
    text-align: center;
  }
  .kitchen-card .icon { font-size: 2.4rem; margin-bottom: 10px; display: block; }
  .kitchen-card .label {
    font-family: 'IBM Plex Mono', monospace;
    font-size: 0.7rem;
    color: var(--cyan);
    letter-spacing: 1px;
    text-transform: uppercase;
    margin-bottom: 6px;
  }
  .kitchen-card h4 { font-family: 'Syne', sans-serif; font-size: 0.95rem; margin-bottom: 6px; }
  .kitchen-card p { color: var(--muted); font-size: 0.82rem; }

  /* COMMANDS */
  .cmd-block {
    background: #0d1117;
    border: 1px solid var(--border);
    border-radius: 10px;
    padding: 20px;
    font-family: 'IBM Plex Mono', monospace;
    font-size: 0.85rem;
    margin-top: 16px;
    position: relative;
    overflow-x: auto;
  }
  .cmd-block::before {
    content: '● ● ●';
    color: var(--border);
    font-size: 0.7rem;
    letter-spacing: 6px;
    display: block;
    margin-bottom: 12px;
  }
  .cmd { color: var(--cyan); }
  .arg { color: var(--yellow); }
  .comment { color: var(--muted); }
  .cmd-line { margin-bottom: 8px; }

  /* SUMMARY */
  .summary-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: 16px;
    margin-top: 24px;
  }
  .summary-card {
    background: var(--card);
    border: 1px solid var(--border);
    border-radius: 12px;
    padding: 22px;
  }
  .summary-num {
    font-family: 'Syne', sans-serif;
    font-size: 2.5rem;
    font-weight: 800;
    line-height: 1;
    margin-bottom: 8px;
  }
  .summary-card h4 { font-family: 'Syne', sans-serif; font-size: 1rem; margin-bottom: 6px; }
  .summary-card p { color: var(--muted); font-size: 0.84rem; }

  /* FOOTER */
  footer {
    text-align: center;
    padding: 40px 24px;
    color: var(--muted);
    font-size: 0.85rem;
    font-family: 'IBM Plex Mono', monospace;
  }

  @media (max-width: 600px) {
    .compare-wrap { grid-template-columns: 1fr; }
    .compare-vs { display: none; }
    .nav-dots { flex-wrap: wrap; gap: 6px; }
  }
</style>
</head>
<body>

<!-- HERO -->
<div class="hero">
  <span class="whale-emoji">🐳</span>
  <h1>Docker, Explained Simply</h1>
  <p>For freshers who want to <em>actually</em> understand containers — no jargon, just real-world analogies.</p>
</div>

<!-- NAV -->
<nav class="nav-dots">
  <button class="nav-dot active" onclick="scrollTo('what')">What is Docker?</button>
  <button class="nav-dot" onclick="scrollTo('problem')">The Problem</button>
  <button class="nav-dot" onclick="scrollTo('solution')">How Docker Helps</button>
  <button class="nav-dot" onclick="scrollTo('imgvcon')">Image vs Container</button>
  <button class="nav-dot" onclick="scrollTo('commands')">Quick Commands</button>
</nav>

<!-- SECTION 1: WHAT IS DOCKER -->
<section id="what">
  <span class="section-tag">01 — Intro</span>
  <h2 class="section-title">What is <span>Docker</span>?</h2>
  <p style="color:var(--muted); margin-bottom: 20px;">Docker is a tool that lets you <strong style="color:var(--text)">package your application and everything it needs to run</strong> — code, libraries, settings, even the OS pieces — into one neat, portable unit called a <strong style="color:var(--cyan)">container</strong>.</p>

  <div class="analogy-box">
    <div class="analogy-label">📦 Real-World Analogy</div>
    <p>Think of Docker like a <strong>lunchbox</strong>. You pack your food, spoon, napkin, and sauce — everything together. No matter where you go — office, picnic, friend's house — you open the box and your meal is ready exactly as you packed it.</p>
    <p>Docker does the same for your app. You pack it once, and it runs <strong>exactly the same</strong> on any machine — your laptop, your colleague's PC, a server in the cloud.</p>
  </div>
</section>

<!-- SECTION 2: THE PROBLEM -->
<section id="problem">
  <span class="section-tag">02 — The Problem</span>
  <h2 class="section-title">Life <span>before Docker</span> was painful</h2>
  <p style="color:var(--muted);">Every developer has heard this classic line… and it's a nightmare.</p>

  <div style="margin-top:24px; background:#1e1005; border:1px solid #4a3010; border-radius:14px; padding:24px; text-align:center;">
    <span style="font-size:3rem;">😤</span>
    <div style="font-family:'Syne',sans-serif; font-size:1.6rem; font-weight:800; color:var(--yellow); margin:10px 0;">"It works on my machine!"</div>
    <p style="color:var(--muted);">— Every developer, ever</p>
  </div>

  <div class="problem-grid">
    <div class="problem-card">
      <div class="icon">🖥️</div>
      <h3>Different OS, Different Behavior</h3>
      <p>Dev uses macOS, server runs Ubuntu. App behaves differently in each environment.</p>
    </div>
    <div class="problem-card">
      <div class="icon">⚙️</div>
      <h3>Dependency Hell</h3>
      <p>App A needs Python 3.8, App B needs Python 3.11. Installing both breaks things.</p>
    </div>
    <div class="problem-card">
      <div class="icon">📋</div>
      <h3>Setup Takes Forever</h3>
      <p>New team member joins. They spend 2 days setting up their environment, fixing errors.</p>
    </div>
    <div class="problem-card">
      <div class="icon">💥</div>
      <h3>Works in Dev, Breaks in Prod</h3>
      <p>App passes all tests locally but crashes on the production server. Panic mode activated.</p>
    </div>
  </div>

  <div class="analogy-box" style="margin-top:24px;">
    <div class="analogy-label">🍱 Real-World Analogy</div>
    <p>Imagine a chef cooks a perfect dish at home. He writes down the recipe and sends it to a restaurant. But the restaurant has a different oven, different spices, different utensils. The dish comes out totally different. <strong>Same recipe, different result.</strong></p>
    <p>This is exactly what happens to software without Docker. The "recipe" (code) is the same, but each "kitchen" (machine) is different.</p>
  </div>
</section>

<!-- SECTION 3: HOW DOCKER HELPS -->
<section id="solution">
  <span class="section-tag">03 — The Solution</span>
  <h2 class="section-title">How Docker <span>Fixes This</span></h2>
  <p style="color:var(--muted); margin-bottom:24px;">Docker ships the whole kitchen, not just the recipe.</p>

  <div class="kitchen-grid">
    <div class="kitchen-card">
      <span class="icon">📦</span>
      <div class="label">Package</div>
      <h4>Bundle Everything</h4>
      <p>Code + libraries + config + runtime — all in one container</p>
    </div>
    <div class="kitchen-card">
      <span class="icon">🚀</span>
      <div class="label">Run Anywhere</div>
      <h4>Any Machine</h4>
      <p>Laptop, server, cloud — same container, same result. Every time.</p>
    </div>
    <div class="kitchen-card">
      <span class="icon">🔒</span>
      <div class="label">Isolated</div>
      <h4>No Conflicts</h4>
      <p>App A and App B live in separate containers. They never interfere.</p>
    </div>
    <div class="kitchen-card">
      <span class="icon">⚡</span>
      <div class="label">Fast</div>
      <h4>Seconds to Start</h4>
      <p>Unlike Virtual Machines, containers start in milliseconds.</p>
    </div>
  </div>

  <div class="analogy-box" style="margin-top:24px;">
    <div class="analogy-label">🚢 The Shipping Container Analogy</div>
    <p>Before shipping containers were invented, loading a ship was chaotic — different shapes, sizes, items. After containers, everything is standardized. <strong>Doesn't matter if it's clothes, electronics, or food</strong> — it all fits in the same container, on any ship, to any port.</p>
    <p>Docker does the same for software. Standard container → runs on any machine. <strong>That's literally why it's called Docker</strong> (as in docking ships 🚢).</p>
  </div>
</section>

<!-- SECTION 4: IMAGE vs CONTAINER -->
<section id="imgvcon">
  <span class="section-tag">04 — Key Concept</span>
  <h2 class="section-title">Image <span>vs</span> Container</h2>
  <p style="color:var(--muted); margin-bottom:8px;">This is the most important distinction beginners need to understand.</p>

  <div class="compare-wrap">
    <div class="compare-card image-card">
      <span class="compare-tag">READ-ONLY</span>
      <span class="compare-emoji">📄</span>
      <h3>Docker Image</h3>
      <p>A <strong style="color:#7eb8ff">blueprint / template</strong>. It's static, like a recipe or a class in programming. You don't "run" an image — you use it to <em>create</em> containers.</p>
    </div>

    <div class="compare-vs">→</div>

    <div class="compare-card container-card">
      <span class="compare-tag">RUNNING</span>
      <span class="compare-emoji">🏃</span>
      <h3>Docker Container</h3>
      <p>A <strong style="color:var(--green)">live, running instance</strong> of an image. Like an object created from a class. It's actually executing your app right now.</p>
    </div>
  </div>

  <!-- 3 Analogies -->
  <div style="margin-top: 28px;">

    <div class="analogy-box" style="margin-bottom:14px;">
      <div class="analogy-label">🍪 Cookie Analogy</div>
      <p><strong>Image = Cookie Cutter</strong> — the mold/shape. It's the template. <strong>Container = Actual Cookie</strong> — made from the cutter. You can bake 100 cookies from one cutter. You can run 100 containers from one image.</p>
    </div>

    <div class="analogy-box" style="margin-bottom:14px;">
      <div class="analogy-label">💻 Code Analogy</div>
      <p><strong>Image = Class</strong> (definition of what something is). <strong>Container = Object</strong> (an actual running instance of that class). Just like <code style="color:var(--cyan);background:#0d1117;padding:1px 6px;border-radius:4px">new MyClass()</code> creates multiple objects, one image creates multiple containers.</p>
    </div>

    <div class="analogy-box">
      <div class="analogy-label">📺 Movie Analogy</div>
      <p><strong>Image = Movie File (MP4)</strong> — stored on your disk, not playing. <strong>Container = Movie Playing on Screen</strong> — it's active, consuming memory and CPU. You can play the same movie on 5 screens simultaneously.</p>
    </div>
  </div>

  <!-- Comparison Table -->
  <table class="diff-table" style="margin-top:28px;">
    <thead>
      <tr>
        <th>ATTRIBUTE</th>
        <th style="color:var(--blue)">🖼 IMAGE</th>
        <th style="color:var(--green)">📦 CONTAINER</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td class="attr">What it is</td>
        <td class="img-val">Blueprint / Template</td>
        <td class="con-val">Running instance</td>
      </tr>
      <tr>
        <td class="attr">State</td>
        <td class="img-val">Static (frozen)</td>
        <td class="con-val">Dynamic (alive)</td>
      </tr>
      <tr>
        <td class="attr">Read/Write</td>
        <td class="img-val">Read-only</td>
        <td class="con-val">Read + Write</td>
      </tr>
      <tr>
        <td class="attr">Where it lives</td>
        <td class="img-val">Disk (Docker Hub / local)</td>
        <td class="con-val">Memory + CPU (running)</td>
      </tr>
      <tr>
        <td class="attr">How to create</td>
        <td class="img-val"><code style="color:var(--blue)">docker build</code></td>
        <td class="con-val"><code style="color:var(--green)">docker run</code></td>
      </tr>
      <tr>
        <td class="attr">Analogy</td>
        <td class="img-val">Recipe / Class / Mold</td>
        <td class="con-val">Cooked dish / Object / Cookie</td>
      </tr>
    </tbody>
  </table>
</section>

<!-- SECTION 5: QUICK COMMANDS -->
<section id="commands">
  <span class="section-tag">05 — Commands</span>
  <h2 class="section-title">Essential <span>Docker Commands</span></h2>
  <p style="color:var(--muted);margin-bottom:4px;">Your first day Docker cheat sheet.</p>

  <div class="cmd-block">
    <div class="cmd-line"><span class="comment"># Pull an image from Docker Hub</span></div>
    <div class="cmd-line"><span class="cmd">docker pull</span> <span class="arg">nginx</span></div>
    <br>
    <div class="cmd-line"><span class="comment"># List all images you have locally</span></div>
    <div class="cmd-line"><span class="cmd">docker images</span></div>
    <br>
    <div class="cmd-line"><span class="comment"># Run a container from an image</span></div>
    <div class="cmd-line"><span class="cmd">docker run</span> <span class="arg">nginx</span></div>
    <br>
    <div class="cmd-line"><span class="comment"># Run in background (-d) with port mapping (-p)</span></div>
    <div class="cmd-line"><span class="cmd">docker run</span> -d -p 8080:80 <span class="arg">nginx</span></div>
    <br>
    <div class="cmd-line"><span class="comment"># List all running containers</span></div>
    <div class="cmd-line"><span class="cmd">docker ps</span></div>
    <br>
    <div class="cmd-line"><span class="comment"># Stop a running container</span></div>
    <div class="cmd-line"><span class="cmd">docker stop</span> <span class="arg">&lt;container_id&gt;</span></div>
    <br>
    <div class="cmd-line"><span class="comment"># Build image from a Dockerfile</span></div>
    <div class="cmd-line"><span class="cmd">docker build</span> -t <span class="arg">my-app:v1</span> .</div>
  </div>

  <!-- Summary -->
  <div style="margin-top: 40px; margin-bottom: 8px;">
    <span class="section-tag">✅ — Recap</span>
    <h2 class="section-title" style="font-size:1.5rem;">Key Takeaways</h2>
  </div>
  <div class="summary-grid">
    <div class="summary-card">
      <div class="summary-num" style="color:var(--cyan)">1</div>
      <h4>Docker packages your app</h4>
      <p>Code + all dependencies in a portable container. No more "works on my machine."</p>
    </div>
    <div class="summary-card">
      <div class="summary-num" style="color:var(--orange)">2</div>
      <h4>Solves environment problems</h4>
      <p>Same container runs on any OS — dev laptop, staging, production.</p>
    </div>
    <div class="summary-card">
      <div class="summary-num" style="color:var(--blue)">3</div>
      <h4>Image = Blueprint</h4>
      <p>Static, read-only template. Like a class, recipe, or cookie cutter.</p>
    </div>
    <div class="summary-card">
      <div class="summary-num" style="color:var(--green)">4</div>
      <h4>Container = Running App</h4>
      <p>A live instance from an image. One image → many containers.</p>
    </div>
  </div>
</section>

<footer>
  🐳 Docker Workshop — Made for freshers with ❤️ &nbsp;|&nbsp; Keep learning, keep shipping
</footer>

<script>
  function scrollTo(id) {
    document.getElementById(id).scrollIntoView({ behavior: 'smooth', block: 'start' });
    document.querySelectorAll('.nav-dot').forEach(d => d.classList.remove('active'));
    event.target.classList.add('active');
  }

  // Highlight active section on scroll
  const sections = ['what','problem','solution','imgvcon','commands'];
  const dots = document.querySelectorAll('.nav-dot');
  window.addEventListener('scroll', () => {
    let current = '';
    sections.forEach(id => {
      const el = document.getElementById(id);
      if (el && window.scrollY >= el.offsetTop - 120) current = id;
    });
    dots.forEach((d, i) => {
      d.classList.toggle('active', sections[i] === current);
    });
  });
</script>
</body>
</html>
