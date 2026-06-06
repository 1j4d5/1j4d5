<!DOCTYPE html>

<html lang="en">
  
<head>
  
<meta charset="UTF-8">

<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>@1j4d5</title>

<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@tabler/icons-webfont@latest/tabler-icons.min.css">

<style>
@import url('https://fonts.googleapis.com/css2?family=Space+Mono:wght@400;700&family=Syne:wght@400;700;800&display=swap');
*{margin:0;padding:0;box-sizing:border-box;}
body{background:#050505;display:flex;justify-content:center;align-items:center;min-height:100vh;}
.wrap{font-family:'Syne',sans-serif;padding:2rem;max-width:680px;width:100%;}
.matrix-bg{position:relative;border-radius:16px;overflow:hidden;background:#0a0a0a;padding:2rem 2rem 1.5rem;margin-bottom:1.5rem;border:0.5px solid #2a2a2a;}
.scanlines{position:absolute;inset:0;background:repeating-linear-gradient(0deg,transparent,transparent 2px,rgba(0,255,136,0.015) 2px,rgba(0,255,136,0.015) 4px);pointer-events:none;z-index:0;}
.matrix-bg > *:not(.scanlines){position:relative;z-index:1;}
.handle{font-family:'Space Mono',monospace;font-size:11px;color:#00ff88;letter-spacing:2px;text-transform:uppercase;margin-bottom:1rem;opacity:0.7;}
.name{font-size:2.8rem;font-weight:800;color:#fff;line-height:1;margin-bottom:0.5rem;letter-spacing:-1px;}
.name span{color:#00ff88;}
.tagline{font-family:'Space Mono',monospace;font-size:12px;color:#555;margin-bottom:1.5rem;}
.stats-row{display:flex;gap:12px;flex-wrap:wrap;margin-bottom:1.5rem;}
.stat{background:#111;border:0.5px solid #222;border-radius:8px;padding:10px 16px;flex:1;min-width:80px;}
.stat-num{font-family:'Space Mono',monospace;font-size:18px;font-weight:700;color:#00ff88;}
.stat-label{font-size:11px;color:#444;margin-top:2px;text-transform:uppercase;letter-spacing:1px;}
.langs{display:flex;gap:8px;flex-wrap:wrap;margin-bottom:1.5rem;}
.lang{font-family:'Space Mono',monospace;font-size:11px;padding:5px 12px;border-radius:100px;border:0.5px solid;cursor:default;transition:transform 0.2s;}
.lang:hover{transform:translateY(-2px);}
.lang.py{color:#00ff88;border-color:#00ff8844;background:#00ff8810;}
.lang.cpp{color:#4fc3f7;border-color:#4fc3f744;background:#4fc3f710;}
.lang.cs{color:#ce93d8;border-color:#ce93d844;background:#ce93d810;}
.lang.c{color:#ffb74d;border-color:#ffb74d44;background:#ffb74d10;}
.lang.js{color:#fff176;border-color:#fff17644;background:#fff17610;}
.lang.ws{color:#f48fb1;border-color:#f48fb144;background:#f48fb110;}
.info-grid{display:grid;grid-template-columns:1fr 1fr;gap:10px;}
.info-card{background:#111;border:0.5px solid #1e1e1e;border-radius:10px;padding:12px 14px;}
.info-icon{font-size:16px;color:#00ff88;margin-bottom:6px;}
.info-title{font-size:10px;color:#444;text-transform:uppercase;letter-spacing:1.5px;margin-bottom:4px;}
.info-text{font-size:13px;color:#ccc;line-height:1.4;}
.info-text a{color:#00ff88;text-decoration:none;}
.info-text a:hover{text-decoration:underline;}
.collab{grid-column:1/-1;background:#00ff8808;border-color:#00ff8822;}
.collab .info-text{font-size:13px;color:#aaa;}
.cursor{display:inline-block;width:2px;height:1em;background:#00ff88;margin-left:2px;vertical-align:text-bottom;animation:blink 1s step-end infinite;}
@keyframes blink{0%,100%{opacity:1}50%{opacity:0}}
</style>

</head>
<body>
<div class="wrap">
  <div class="matrix-bg">
    <div class="scanlines"></div>
    <div class="handle">// @1j4d5 &nbsp;&nbsp; github.com</div>
    <div class="name">ijad<span>.</span>dev<span class="cursor"></span></div>
    <div class="tagline">websockets · web APIs · web development</div>
    <div class="stats-row">
      <div class="stat"><div class="stat-num">5+</div><div class="stat-label">Languages</div></div>
      <div class="stat"><div class="stat-num">∞</div><div class="stat-label">Curiosity</div></div>
    </div>
    <div class="langs">
      <span class="lang py">Python</span>
      <span class="lang cpp">C++</span>
      <span class="lang cs">C#</span>
      <span class="lang c">C</span>
      <span class="lang js">JavaScript</span>
      <span class="lang ws">WebSockets</span>
    </div>
    <div class="info-grid">
      <div class="info-card">
        <div class="info-icon"><i class="ti ti-brand-github"></i></div>
        <div class="info-title">Profile</div>
        <div class="info-text"><a href="https://github.com/1j4d5">github.com/1j4d5</a></div>
      </div>
      <div class="info-card">
        <div class="info-icon"><i class="ti ti-mail"></i></div>
        <div class="info-title">Contact</div>
        <div class="info-text"><a href="mailto:ijads.main@gmail.com">ijads.main@gmail.com</a></div>
      </div>
      <div class="info-card collab">
        <div class="info-icon"><i class="ti ti-rocket"></i></div>
        <div class="info-title">Mission</div>
        <div class="info-text">Building easy, fresh dependencies for the dev community — and looking for the right collab to build something real.</div>
      </div>
    </div>
  </div>
</div>
</body>
</html>
