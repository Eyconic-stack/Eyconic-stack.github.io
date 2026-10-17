<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>Godfrey Godwin Osagie | Power Platform Developer and AI/ML Engineer</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Bricolage+Grotesque:wght@500;700;800&family=Public+Sans:wght@400;500;600&display=swap" rel="stylesheet">
<style>
:root{
  --bg:#EEF2F6; --ink:#14213D; --muted:#4F5D75; --line:#C9D3E0; --accent:#2150C8; --accent2:#E8590C; --accent-ink:#fff; --panel:#E3E9F1; --card:#F8FAFC; --glow:rgba(33,80,200,.16); --dot:33,80,200;
  box-sizing:border-box; padding-top:env(safe-area-inset-top,0px); padding-bottom:env(safe-area-inset-bottom,0px);
}
@media (prefers-color-scheme: dark){:root:not([data-theme="light"]){--bg:#0C1424; --ink:#E8EDF5; --muted:#9FB0C8; --line:#25344D; --accent:#7EA2FF; --accent2:#FFA05C; --accent-ink:#0B1220; --panel:#16223A; --card:#111C31; --glow:rgba(126,162,255,.18); --dot:126,162,255; color-scheme:dark;}}
:root[data-theme="dark"]{--bg:#0C1424; --ink:#E8EDF5; --muted:#9FB0C8; --line:#25344D; --accent:#7EA2FF; --accent2:#FFA05C; --accent-ink:#0B1220; --panel:#16223A; --card:#111C31; --glow:rgba(126,162,255,.18); --dot:126,162,255; color-scheme:dark;}
html{scroll-padding-top:5rem;scroll-behavior:smooth;}
*,*::before,*::after{box-sizing:border-box;}
body{margin:0;background:var(--bg);color:var(--ink);font-family:"Public Sans",system-ui,-apple-system,"Segoe UI",sans-serif;font-size:1.05rem;line-height:1.6;overflow-x:hidden;}
.wrap{max-width:1080px;margin:0 auto;padding:0 1.25rem;}
h1,h2,h3{font-family:"Bricolage Grotesque","Segoe UI",system-ui,sans-serif;line-height:1.08;margin:0;}
a{color:var(--accent);text-underline-offset:3px;}
a:focus-visible,button:focus-visible{outline:3px solid var(--accent);outline-offset:3px;border-radius:4px;}

nav{position:sticky;top:0;z-index:20;background:color-mix(in srgb,var(--bg) 85%,transparent);backdrop-filter:blur(10px);border-bottom:1px solid var(--line);padding-top:env(safe-area-inset-top,0px);}
nav .wrap{display:flex;align-items:center;justify-content:space-between;height:3.5rem;}
.brand{font-family:"Bricolage Grotesque",sans-serif;font-weight:800;font-size:1.15rem;color:var(--ink);text-decoration:none;}
nav .links{display:flex;gap:1.2rem;align-items:center;}
nav .links a{color:var(--ink);text-decoration:none;font-weight:500;font-size:.95rem;}
nav .links a:hover{color:var(--accent);}
.theme{background:none;border:1.5px solid var(--line);color:var(--ink);border-radius:6px;padding:.3rem .65rem;font:inherit;font-size:.85rem;cursor:pointer;}
@media (max-width:620px){nav .links a.hide{display:none;}}

.hero{position:relative;padding:4rem 0 4.5rem;display:grid;gap:2.5rem;grid-template-columns:1fr;align-items:center;}
@media (min-width:900px){.hero{grid-template-columns:1.15fr .85fr;padding:5.5rem 0 5rem;}}
#net{position:absolute;inset:0 -50vw;width:100vw;height:100%;margin:0 auto;left:0;right:0;z-index:-1;pointer-events:none;}
.avatar{width:84px;height:84px;border-radius:50%;display:grid;place-items:center;font:800 1.6rem "Bricolage Grotesque",sans-serif;color:var(--accent-ink);background:linear-gradient(135deg,var(--accent),var(--accent2));position:relative;margin-bottom:1.3rem;}
.avatar::after{content:"";position:absolute;inset:-7px;border-radius:50%;border:2px dashed var(--accent);animation:spin 14s linear infinite;}
.hello{color:var(--muted);font-weight:500;margin:0 0 .2rem;}
.hero h1{font-size:clamp(2.7rem,8.4vw,5.2rem);font-weight:800;letter-spacing:-.03em;}
.role{font-family:"Bricolage Grotesque",sans-serif;font-size:clamp(1.3rem,3.4vw,1.9rem);font-weight:700;margin:1rem 0;min-height:2.3rem;color:var(--accent);}
.cursor{display:inline-block;width:3px;height:1.1em;background:var(--accent);margin-left:3px;vertical-align:-.15em;animation:blink 1s steps(1) infinite;}
.hero p.lead{max-width:54ch;color:var(--muted);margin:0 0 1.6rem;}
.btn{display:inline-block;background:var(--accent);color:var(--accent-ink);padding:.75rem 1.3rem;border-radius:8px;font-weight:600;text-decoration:none;transition:transform .2s,box-shadow .2s;margin:0 .4rem .5rem 0;border:1.5px solid var(--accent);cursor:pointer;font:inherit;font-weight:600;}
.btn:hover{transform:translateY(-3px);box-shadow:0 10px 24px var(--glow);}
.btn.ghost{background:transparent;color:var(--ink);border-color:var(--line);}

.term{background:#0B1220;color:#DCE6F7;border-radius:12px;box-shadow:0 24px 50px rgba(8,14,30,.3);overflow:hidden;font-family:ui-monospace,Consolas,"Cascadia Code",monospace;font-size:.86rem;}
.term .bar{display:flex;gap:6px;padding:.7rem .9rem;background:#16223A;}
.term .bar i{width:11px;height:11px;border-radius:50%;background:#3A4B6C;display:block;}
.term .bar span{margin-left:auto;font-size:.75rem;color:#8FA3C6;}
.term pre{margin:0;padding:1rem 1.1rem 1.2rem;min-height:17rem;white-space:pre-wrap;line-height:1.7;}
.term .k{color:#7EA2FF;} .term .s{color:#9BE3B0;} .term .o{color:#FFD479;}
.term .ln{opacity:0;} .term .ln.on{opacity:1;transition:opacity .25s;}

.ribbon{overflow:hidden;border-block:1px solid var(--line);background:var(--panel);padding:.8rem 0;}
.track{display:flex;gap:2.5rem;width:max-content;font-family:"Bricolage Grotesque",sans-serif;font-weight:700;font-size:1.2rem;animation:scroll 28s linear infinite;}
.track span::after{content:"/";margin-left:2.5rem;color:var(--accent);}

section{padding:3.4rem 0;}
h2.title{font-size:2.1rem;margin-bottom:.5rem;}
.sub{color:var(--muted);margin:0 0 2rem;max-width:56ch;}

.stats{display:grid;grid-template-columns:repeat(3,1fr);gap:1rem;margin-bottom:2.5rem;}
.stat{text-align:center;padding:1.2rem .5rem;border:1px solid var(--line);border-radius:12px;background:var(--card);}
.stat b{display:block;font:800 clamp(2rem,6vw,3rem) "Bricolage Grotesque",sans-serif;color:var(--accent);}
.stat span{color:var(--muted);font-size:.9rem;}

.tiles{display:grid;grid-template-columns:repeat(auto-fit,minmax(170px,1fr));gap:1rem;}
.tile{position:relative;padding:1.6rem 1rem 1.3rem;text-align:center;border:1px solid var(--line);border-radius:16px;background:var(--card);overflow:hidden;transition:transform .3s,box-shadow .3s,border-color .3s;}
.tile::before{content:"";position:absolute;inset:0 0 auto 0;height:4px;background:var(--c,var(--accent));transform:scaleX(0);transform-origin:left;transition:transform .4s;}
.tile::after{content:"";position:absolute;inset:auto -30% -60% -30%;height:80%;background:radial-gradient(circle,var(--c,var(--accent)),transparent 65%);opacity:.08;transition:opacity .3s;}
.tile:hover{transform:translateY(-6px);box-shadow:0 18px 36px color-mix(in srgb,var(--c,var(--accent)) 25%,transparent);border-color:var(--c,var(--accent));}
.tile:hover::before{transform:scaleX(1);} .tile:hover::after{opacity:.2;}
.tile .ico{position:relative;z-index:1;width:68px;height:68px;margin:0 auto .9rem;border-radius:18px;display:grid;place-items:center;background:#fff;box-shadow:0 4px 14px rgba(20,33,61,.12);transition:transform .45s cubic-bezier(.3,1.6,.5,1);}
.tile .ico svg{width:42px;height:42px;display:block;}
.tile:hover .ico{transform:translateY(-3px) rotate(-8deg) scale(1.14);}
.tile h3,.tile p{position:relative;z-index:1;}
#bar{position:fixed;top:0;left:0;height:3px;width:0;background:linear-gradient(90deg,var(--accent),var(--accent2));z-index:30;}
nav .links a.active{color:var(--accent);}
.grad{background:linear-gradient(90deg,var(--accent),var(--accent2));-webkit-background-clip:text;background-clip:text;color:transparent;}
.tile h3{font-size:1.1rem;} .tile p{margin:.3rem 0 0;color:var(--muted);font-size:.9rem;}

.project{position:relative;display:grid;grid-template-columns:1fr;gap:.8rem;padding:1.7rem;margin-bottom:1.2rem;background:var(--card);border:1px solid var(--line);border-radius:14px;overflow:hidden;transition:box-shadow .3s;transform-style:preserve-3d;}
.project::before{content:"";position:absolute;inset:0;background:radial-gradient(420px circle at var(--mx,50%) var(--my,0%),var(--glow),transparent 60%);opacity:0;transition:opacity .3s;pointer-events:none;}
.project:hover::before{opacity:1;}
.project:hover{box-shadow:0 18px 40px var(--glow);border-color:var(--accent);}
@media (min-width:760px){.project{grid-template-columns:250px 1fr;gap:2rem;}}
.project h3{font-size:1.5rem;margin-bottom:.5rem;}
.chips{display:flex;flex-wrap:wrap;gap:.4rem;}
.chips span{background:var(--panel);padding:.2rem .65rem;border-radius:999px;font-size:.82rem;font-weight:500;}
.project p{margin:0 0 .6rem;max-width:62ch;}
.learned{background:var(--panel);padding:.7rem .9rem;border-radius:8px;font-size:.95rem;max-width:62ch;margin-bottom:.8rem;}
.project .go{font-weight:600;}

.about{display:grid;gap:1rem;grid-template-columns:1fr;}
@media (min-width:720px){.about{grid-template-columns:1fr 1fr;}}
.box{padding:1.3rem;border:1px solid var(--line);border-radius:12px;background:var(--card);}
.box h3{font-size:1.15rem;margin-bottom:.5rem;} .box p{margin:0;color:var(--muted);}

.contact{text-align:center;}
.contact .sub{margin-inline:auto;}
.contact .row{display:flex;flex-wrap:wrap;gap:.6rem;justify-content:center;}
.toast{height:1.4rem;color:var(--accent);font-weight:600;margin-top:.8rem;}
footer{padding:2rem 0 3rem;color:var(--muted);font-size:.9rem;border-top:1px solid var(--line);text-align:center;}

.reveal{opacity:0;transform:translateY(26px);transition:opacity .7s ease,transform .7s ease;}
.reveal.in{opacity:1;transform:none;}
@keyframes blink{50%{opacity:0;}}
@keyframes spin{to{transform:rotate(360deg);}}
@keyframes scroll{to{transform:translateX(-50%);}}
@keyframes rise{from{opacity:0;transform:translateY(20px);}to{opacity:1;transform:none;}}
@media (prefers-reduced-motion:no-preference){
  .hero h1{animation:rise .8s ease-out both;} .hello{animation:rise .8s ease-out both;}
  .hero p.lead,.cta-row{animation:rise .8s .35s ease-out both;}
  .term{animation:rise .9s .25s ease-out both;}
}
@media (prefers-reduced-motion:reduce){.reveal{opacity:1;transform:none;transition:none;} .track,.avatar::after,.cursor{animation:none;}}
</style>
</head>
<body>
<nav><div class="wrap">
  <a class="brand" href="#top">Godwin Osagie</a>
  <div class="links"><a class="hide" href="#skills">Skills</a><a class="hide" href="#projects">Projects</a><a class="hide" href="#about">About</a><a class="hide" href="#contact">Contact</a><button class="theme" id="theme" type="button" aria-label="Switch light or dark theme">Theme</button></div>
</div></nav>

<div class="wrap" id="top">
<header class="hero">
  <canvas id="net" aria-hidden="true"></canvas>
  <div>
    <div class="avatar" aria-hidden="true">GO</div>
    <p class="hello">Hi, I am</p>
    <h1>Godfrey <span class="grad">Godwin</span> Osagie</h1>
    <div class="role"><span id="typed">Power Platform Developer</span><span class="cursor" aria-hidden="true"></span></div>
    <p class="lead">I build business workflow tools with Power Apps, Power Automate and SharePoint, and prediction models with Python. I am now adding JavaScript, React and SQL to put my models into public web apps. Based in Lagos, Nigeria.</p>
    <div class="cta-row"><a class="btn" href="#projects">See my projects</a><a class="btn ghost" href="mailto:godfreygodwin123@gmail.com?subject=Hello%20Godwin">Email me</a></div>
  </div>
  <div class="term" aria-label="Python code describing Godwin">
    <div class="bar"><i></i><i></i><i></i><span>godwin.py</span></div>
<pre id="code"><span class="ln"><span class="k">developer</span> = {</span>
<span class="ln">  <span class="s">"name"</span>: <span class="s">"Godfrey Godwin Osagie"</span>,</span>
<span class="ln">  <span class="s">"roles"</span>: [<span class="s">"Power Platform Developer"</span>,</span>
<span class="ln">            <span class="s">"AI/ML Engineer"</span>],</span>
<span class="ln">  <span class="s">"languages"</span>: [<span class="s">"Power Fx"</span>, <span class="s">"Python"</span>,</span>
<span class="ln">                <span class="s">"HTML"</span>, <span class="s">"CSS"</span>],</span>
<span class="ln">  <span class="s">"learning"</span>: [<span class="s">"JavaScript"</span>, <span class="s">"React"</span>, <span class="s">"SQL"</span>],</span>
<span class="ln">}</span>
<span class="ln"></span>
<span class="ln"><span class="k">print</span>(developer[<span class="s">"roles"</span>][1])</span>
<span class="ln o">AI/ML Engineer</span></pre>
  </div>
</header>
</div>

<div class="ribbon" aria-hidden="true"><div class="track" id="track"></div></div>

<section id="skills"><div class="wrap">
  <h2 class="title reveal">Languages and skills</h2>
  <p class="sub reveal">What I have learnt and use to build.</p>
  <div class="stats reveal">
    <div class="stat"><b data-n="3">0</b><span>projects built</span></div>
    <div class="stat"><b data-n="5">0</b><span>languages and skills</span></div>
    <div class="stat"><b data-n="2">0</b><span>certification paths</span></div>
  </div>
  <div class="tiles">
    <div class="tile reveal" style="--c:#3776AB"><div class="ico"><svg viewBox="0 0 24 24" aria-hidden="true"><path fill="#3776AB" d="M11.9 2C7.5 2 7.8 3.9 7.8 3.9v2h4.2v.6H6S3 6.2 3 11s2.6 4.6 2.6 4.6h1.6v-2.2s-.1-2.6 2.6-2.6h4.4s2.5 0 2.5-2.4V4.5S17.1 2 11.9 2z"/><circle cx="9.1" cy="4.2" r=".8" fill="#fff"/><path fill="#FFC331" transform="rotate(180 12 12)" d="M11.9 2C7.5 2 7.8 3.9 7.8 3.9v2h4.2v.6H6S3 6.2 3 11s2.6 4.6 2.6 4.6h1.6v-2.2s-.1-2.6 2.6-2.6h4.4s2.5 0 2.5-2.4V4.5S17.1 2 11.9 2z"/><circle cx="14.9" cy="19.8" r=".8" fill="#fff"/></svg></div><h3>Python</h3><p>Models, APIs, scripts</p></div>
    <div class="tile reveal" style="--c:#742774"><div class="ico"><svg viewBox="0 0 24 24" aria-hidden="true"><rect width="24" height="24" rx="6" fill="#742774"/><text x="12" y="16.5" text-anchor="middle" font-family="Georgia,serif" font-style="italic" font-weight="700" font-size="12" fill="#fff">fx</text></svg></div><h3>Power Fx</h3><p>Power Apps logic</p></div>
    <div class="tile reveal" style="--c:#0066FF"><div class="ico"><svg viewBox="0 0 24 24" aria-hidden="true"><rect width="24" height="24" rx="6" fill="#0066FF"/><path d="M6 7h8a3 3 0 0 1 0 6h-4a3 3 0 0 0 0 6h7" fill="none" stroke="#fff" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/><path d="M15.5 16.5 18 19l-2.5 2.5" fill="none" stroke="#fff" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/></svg></div><h3>Automation</h3><p>Power Automate, Office Scripts</p></div>
    <div class="tile reveal" style="--c:#E34F26"><div class="ico"><svg viewBox="0 0 24 24" aria-hidden="true"><path fill="#E34F26" d="M4 3l1.6 18L12 23l6.4-2L20 3z"/><path fill="#EF652A" d="M12 4.5v17l5.200-1.600L18.600 4.500z"/><text x="12" y="16.5" text-anchor="middle" font-family="Arial,sans-serif" font-weight="800" font-size="11" fill="#fff">5</text></svg></div><h3>HTML</h3><p>Page structure</p></div>
    <div class="tile reveal" style="--c:#1572B6"><div class="ico"><svg viewBox="0 0 24 24" aria-hidden="true"><path fill="#1572B6" d="M4 3l1.6 18L12 23l6.4-2L20 3z"/><path fill="#33A9DC" d="M12 4.5v17l5.200-1.600L18.600 4.500z"/><text x="12" y="16.5" text-anchor="middle" font-family="Arial,sans-serif" font-weight="800" font-size="11" fill="#fff">3</text></svg></div><h3>CSS</h3><p>Styling and layout</p></div>
  </div>
</div></section>

<section id="projects"><div class="wrap">
  <h2 class="title reveal">Projects</h2>
  <p class="sub reveal">Real code you can read on my GitHub.</p>

  <article class="project reveal tilt">
    <div><h3>Eyconic AI</h3><div class="chips"><span>Python</span><span>FastAPI</span><span>scikit-learn</span></div></div>
    <div>
      <p>A football match prediction API. Pick two teams and it returns expected goals, win, draw and loss chances, over and under probabilities, and the most likely score. It works for the Premier League and La Liga, and new leagues take one line to add.</p>
      <div class="learned">What I learned: Poisson regression, turning model output into a probability table, and serving a model through an API.</div>
      <a class="go" href="https://github.com/Eyconic-stack/Match-prediction-model" target="_blank" rel="noopener">View code on GitHub</a>
    </div>
  </article>

  <article class="project reveal tilt">
    <div><h3>Live Currency Converter</h3><div class="chips"><span>Python</span><span>REST API</span><span>JSON</span></div></div>
    <div>
      <p>A command-line app that downloads live exchange rates and converts between any two currencies, such as Naira to US dollars. If the internet fails, it shows a clear message instead of crashing.</p>
      <div class="learned">What I learned: calling an API, reading JSON, status codes, timeouts and error handling.</div>
      <a class="go" href="https://github.com/Eyconic-stack/LiveCurrency" target="_blank" rel="noopener">View code on GitHub</a>
    </div>
  </article>

  <article class="project reveal tilt">
    <div><h3>Contact Book</h3><div class="chips"><span>Python</span><span>JSON files</span></div></div>
    <div>
      <p>A command-line app to add, search, edit and delete contacts. Everything is saved to a file, so contacts are still there when the program is reopened.</p>
      <div class="learned">What I learned: lists, dictionaries, functions, reading and writing files.</div>
      <a class="go" href="https://github.com/Eyconic-stack/Contacts" target="_blank" rel="noopener">View code on GitHub</a>
    </div>
  </article>
</div></section>

<section id="about"><div class="wrap">
  <h2 class="title reveal">About me</h2>
  <p class="sub reveal">Business automation today, AI and full web apps next.</p>
  <div class="about">
    <div class="box reveal"><h3>Business automation</h3><p>Power Apps, Power Automate, SharePoint, Power BI, Excel and Office Scripts.</p></div>
    <div class="box reveal"><h3>AI and web</h3><p>Python machine learning and APIs now. JavaScript with React and Vue, then SQL, are next.</p></div>
    <div class="box reveal"><h3>Certification paths</h3><p>PL-400 Power Platform Developer Associate and AZ-102 Azure Administrator Associate.</p></div>
    <div class="box reveal"><h3>Education</h3><p>BSc/Ed Mathematics, Tai Solarin University.</p></div>
  </div>
</div></section>

<section class="contact" id="contact"><div class="wrap reveal">
  <h2 class="title">Let us work together</h2>
  <p class="sub">I am open to roles where I can build useful tools and keep growing as a developer. Send me a message.</p>
  <div class="row">
    <a class="btn" href="mailto:godfreygodwin123@gmail.com?subject=Hello%20Godwin">Send an email</a>
    <button class="btn ghost" id="copy" type="button">Copy my email</button>
    <a class="btn ghost" href="https://www.linkedin.com/in/godwin-godfrey-289428355" target="_blank" rel="noopener">LinkedIn</a>
    <a class="btn ghost" href="https://github.com/Eyconic-stack" target="_blank" rel="noopener">GitHub</a>
  </div>
  <div class="toast" id="toast" role="status"></div>
</div></section>

<footer><div class="wrap">Godfrey Godwin Osagie, Lagos, Nigeria</div></footer>

<script>
(function(){
  var root=document.documentElement,reduce=window.matchMedia("(prefers-reduced-motion: reduce)").matches;
  document.getElementById("theme").addEventListener("click",function(){
    var dark=window.matchMedia("(prefers-color-scheme: dark)").matches;
    var cur=root.getAttribute("data-theme")||(dark?"dark":"light");
    root.setAttribute("data-theme",cur==="dark"?"light":"dark");
  });
  var words=["Python","Power Fx","Automation","HTML","CSS","Power Apps","Power Automate","SharePoint","Power BI","Machine learning"],t=document.getElementById("track"),h="";
  for(var r=0;r<2;r++){words.forEach(function(w){h+="<span>"+w+"</span>";});}
  t.innerHTML=h;
  var lines=document.querySelectorAll("#code .ln");
  if(reduce){lines.forEach(function(l){l.classList.add("on");});}
  else{lines.forEach(function(l,i){setTimeout(function(){l.classList.add("on");},700+i*340);});}
  var roles=["Power Platform Developer","AI/ML Engineer"],ri=0,ci=roles[0].length,del=false,el=document.getElementById("typed");
  if(!reduce){(function tick(){
    var w=roles[ri];
    if(!del){ci++;el.textContent=w.slice(0,ci);if(ci>=w.length){del=true;return setTimeout(tick,1800);}return setTimeout(tick,85);}
    ci--;el.textContent=w.slice(0,ci);
    if(ci<=0){del=false;ri=(ri+1)%roles.length;return setTimeout(tick,300);}
    setTimeout(tick,45);
  })();}
  var items=document.querySelectorAll(".reveal");
  function count(el){var n=+el.dataset.n,i=0;(function s(){i++;el.textContent=i;if(i<n)setTimeout(s,260);})();}
  if("IntersectionObserver" in window&&!reduce){
    var io=new IntersectionObserver(function(es){es.forEach(function(e){if(e.isIntersecting){e.target.classList.add("in");e.target.querySelectorAll("[data-n]").forEach(count);io.unobserve(e.target);}});},{threshold:.15});
    items.forEach(function(i,k){i.style.transitionDelay=(k%5)*70+"ms";io.observe(i);});
  }else{items.forEach(function(i){i.classList.add("in");});document.querySelectorAll("[data-n]").forEach(function(e){e.textContent=e.dataset.n;});}
  document.querySelectorAll(".tilt").forEach(function(c){
    c.addEventListener("mousemove",function(e){
      var b=c.getBoundingClientRect(),x=e.clientX-b.left,y=e.clientY-b.top;
      c.style.setProperty("--mx",x+"px");c.style.setProperty("--my",y+"px");
      if(!reduce){c.style.transform="perspective(900px) rotateX("+((y/b.height-.5)*-4)+"deg) rotateY("+((x/b.width-.5)*5)+"deg)";}
    });
    c.addEventListener("mouseleave",function(){c.style.transform="";});
  });
  document.getElementById("copy").addEventListener("click",function(){
    var m="godfreygodwin123@gmail.com",tt=document.getElementById("toast");
    function ok(){tt.textContent="Email copied: "+m;setTimeout(function(){tt.textContent="";},2500);}
    try{navigator.clipboard.writeText(m).then(ok,function(){tt.textContent=m;});}catch(e){tt.textContent=m;}
  });
  var bar=document.createElement("div");bar.id="bar";document.body.appendChild(bar);
  var navLinks=document.querySelectorAll("nav .links a.hide"),secs=["skills","projects","about","contact"].map(function(id){return document.getElementById(id);});
  function onScroll(){
    var h=document.documentElement.scrollHeight-window.innerHeight;
    bar.style.width=(h>0?window.scrollY/h*100:0)+"%";
    var cur=-1;secs.forEach(function(s,i){if(s&&s.getBoundingClientRect().top<window.innerHeight*.4)cur=i;});
    navLinks.forEach(function(a,i){a.classList.toggle("active",i===cur);});
  }
  window.addEventListener("scroll",onScroll,{passive:true});onScroll();
  var cv=document.getElementById("net");
  if(cv&&!reduce){
    var cx=cv.getContext("2d"),W,H,P=[],mouse={x:-999,y:-999};
    function size(){W=cv.width=cv.offsetWidth;H=cv.height=cv.offsetHeight;var n=Math.min(70,Math.floor(W*H/14000));P=[];for(var i=0;i<n;i++)P.push({x:Math.random()*W,y:Math.random()*H,vx:(Math.random()-.5)*.5,vy:(Math.random()-.5)*.5});}
    size();window.addEventListener("resize",size);
    cv.parentNode.addEventListener("mousemove",function(e){var b=cv.getBoundingClientRect();mouse.x=e.clientX-b.left;mouse.y=e.clientY-b.top;});
    (function draw(){
      var c=getComputedStyle(root).getPropertyValue("--dot").trim()||"33,80,200";
      cx.clearRect(0,0,W,H);
      for(var i=0;i<P.length;i++){
        var p=P[i];p.x+=p.vx;p.y+=p.vy;
        if(p.x<0||p.x>W)p.vx*=-1;if(p.y<0||p.y>H)p.vy*=-1;
        cx.fillStyle="rgba("+c+",.55)";cx.beginPath();cx.arc(p.x,p.y,2,0,6.3);cx.fill();
        for(var j=i+1;j<P.length;j++){var q=P[j],d=Math.hypot(p.x-q.x,p.y-q.y);
          if(d<110){cx.strokeStyle="rgba("+c+","+(.28*(1-d/110))+")";cx.beginPath();cx.moveTo(p.x,p.y);cx.lineTo(q.x,q.y);cx.stroke();}}
        var m=Math.hypot(p.x-mouse.x,p.y-mouse.y);
        if(m<150){cx.strokeStyle="rgba("+c+","+(.5*(1-m/150))+")";cx.beginPath();cx.moveTo(p.x,p.y);cx.lineTo(mouse.x,mouse.y);cx.stroke();}
      }
      requestAnimationFrame(draw);
    })();
  }
})();
</script>
</body>
</html>
