# developer-dashboard
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Developer Dashboard</title>
<style>
*{box-sizing:border-box}
body{margin:0;background:#0c101b;color:#edf1ff;font-family:Arial;padding:24px}
main{max-width:1000px;margin:auto}
header{display:flex;justify-content:space-between;align-items:center;flex-wrap:wrap;gap:12px}
.muted{color:#a0abc4}
.grid,.projects{display:grid;grid-template-columns:repeat(auto-fit,minmax(190px,1fr));gap:15px;margin:25px 0}
.card{background:#171f31;border:1px solid #293650;border-radius:15px;padding:20px}
.num{font-size:2rem;font-weight:bold;color:#75f0d0}
.bar{height:8px;background:#2b354a;border-radius:10px;margin:12px 0;overflow:hidden}
.bar span{display:block;height:100%;background:#75f0d0}
button{background:#75f0d0;color:#071c18;padding:11px 15px;border:0;border-radius:8px;cursor:pointer;font-weight:bold}
</style>
</head>
<body>
<main>
<header><div><p class="muted">WORKSPACE / OVERVIEW</p><h1>Developer Hub</h1></div><button onclick="alert('This is a demo dashboard. Connect a data source for live statistics.')">Connect Source</button></header>
<p class="muted">A snapshot of your learning journey.</p>
<section class="grid">
<div class="card"><p class="muted">Projects Built</p><div class="num" id="projects">10</div><p class="muted">Personal portfolio goal</p></div>
<div class="card"><p class="muted">Learning Streak</p><div class="num">7 days</div><p class="muted">Sample data</p></div>
<div class="card"><p class="muted">Skills Progress</p><div class="num">68%</div><div class="bar"><span style="width:68%"></span></div></div>
<div class="card"><p class="muted">Next Milestone</p><div class="num">15</div><p class="muted">Project target</p></div>
</section>
<h2>Project Board</h2>
<section class="projects">
<article class="card"><h3>Portfolio Website</h3><p class="muted">HTML · CSS</p><div class="bar"><span style="width:100%"></span></div>Complete</article>
<article class="card"><h3>Daily Report</h3><p class="muted">JavaScript · Storage</p><div class="bar"><span style="width:80%"></span></div>In Progress</article>
<article class="card"><h3>Weather App</h3><p class="muted">API · JavaScript</p><div class="bar"><span style="width:45%"></span></div>Learning</article>
</section>
<p class="muted">Statistics displayed here are examples, not live GitHub statistics.</p>
</main>
</body>
</html>
