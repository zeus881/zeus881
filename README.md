<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8"/>
<meta name="viewport" content="width=device-width, initial-scale=1.0"/>
<title>Sanjay Kumar | Software Engineer</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">

<style>

*{
    margin:0;
    padding:0;
    box-sizing:border-box;
}

html{
    scroll-behavior:smooth;
}

body{
    background:#060B14;
    color:white;
    font-family:'Poppins',sans-serif;
    overflow-x:hidden;
}

/* =========================
   HERO SECTION
========================= */

.banner{
    position:relative;
    width:100%;
    height:100vh;
    overflow:hidden;
    background:#060B14;
}

canvas{
    position:absolute;
    top:0;
    left:0;
    width:100%;
    height:100%;
}

.content{
    position:absolute;
    z-index:5;
    width:100%;
    height:100%;
    display:flex;
    flex-direction:column;
    justify-content:center;
    padding:0 8%;
}

.tag{
    color:#5DCAA5;
    font-size:14px;
    letter-spacing:3px;
    margin-bottom:20px;
    text-transform:uppercase;
}

.name{
    font-size:72px;
    font-weight:800;
    line-height:1;
    background:linear-gradient(90deg,#ffffff,#C8C4FF,#5DCAA5);
    -webkit-background-clip:text;
    -webkit-text-fill-color:transparent;
    margin-bottom:18px;
}

.role{
    font-size:18px;
    color:#bfc8d8;
    max-width:800px;
    line-height:1.8;
    margin-bottom:30px;
}

.hero-buttons{
    display:flex;
    gap:20px;
    flex-wrap:wrap;
}

.btn{
    padding:14px 28px;
    border-radius:50px;
    text-decoration:none;
    font-weight:600;
    transition:0.3s;
}

.btn-primary{
    background:linear-gradient(90deg,#7F77DD,#1D9E75);
    color:white;
}

.btn-primary:hover{
    transform:translateY(-3px);
    box-shadow:0 0 20px rgba(127,119,221,0.5);
}

.btn-secondary{
    border:1px solid rgba(255,255,255,0.2);
    color:white;
}

.btn-secondary:hover{
    background:rgba(255,255,255,0.08);
}

.location{
    position:absolute;
    bottom:25px;
    right:35px;
    color:#5f718b;
    font-size:12px;
    letter-spacing:2px;
}

/* =========================
   SECTION STYLE
========================= */

section{
    padding:100px 8%;
}

.section-title{
    font-size:42px;
    margin-bottom:50px;
    font-weight:700;
    background:linear-gradient(90deg,#ffffff,#5DCAA5);
    -webkit-background-clip:text;
    -webkit-text-fill-color:transparent;
}

/* =========================
   ABOUT
========================= */

.about{
    display:grid;
    grid-template-columns:1fr 1fr;
    gap:60px;
    align-items:center;
}

.about-card{
    background:rgba(255,255,255,0.03);
    border:1px solid rgba(255,255,255,0.08);
    padding:40px;
    border-radius:24px;
    backdrop-filter:blur(10px);
}

.about-card p{
    color:#b8c1d1;
    line-height:1.9;
    font-size:16px;
}

/* =========================
   SKILLS
========================= */

.skills-grid{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:25px;
}

.skill-card{
    background:rgba(255,255,255,0.03);
    border:1px solid rgba(255,255,255,0.08);
    padding:30px;
    border-radius:20px;
    transition:0.3s;
}

.skill-card:hover{
    transform:translateY(-8px);
    border-color:#5DCAA5;
}

.skill-card h3{
    margin-bottom:15px;
    color:#5DCAA5;
}

.skill-card p{
    color:#b8c1d1;
    line-height:1.8;
}

/* =========================
   PROJECTS
========================= */

.projects-grid{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(300px,1fr));
    gap:30px;
}

.project-card{
    background:rgba(255,255,255,0.03);
    border-radius:24px;
    padding:30px;
    border:1px solid rgba(255,255,255,0.08);
    transition:0.3s;
}

.project-card:hover{
    transform:translateY(-8px);
    border-color:#7F77DD;
}

.project-card h3{
    margin-bottom:15px;
    color:#AFA9EC;
}

.project-card p{
    color:#b8c1d1;
    line-height:1.8;
    margin-bottom:20px;
}

.tech{
    color:#5DCAA5;
    font-size:14px;
}

/* =========================
   EXPERIENCE
========================= */

.timeline{
    border-left:2px solid rgba(255,255,255,0.1);
    padding-left:30px;
}

.timeline-item{
    margin-bottom:40px;
    position:relative;
}

.timeline-item::before{
    content:'';
    width:16px;
    height:16px;
    background:#5DCAA5;
    position:absolute;
    left:-39px;
    top:5px;
    border-radius:50%;
}

.timeline-item h3{
    margin-bottom:10px;
}

.timeline-item span{
    color:#5DCAA5;
    font-size:14px;
}

.timeline-item p{
    margin-top:12px;
    color:#b8c1d1;
    line-height:1.8;
}

/* =========================
   FOOTER
========================= */

footer{
    padding:40px 8%;
    text-align:center;
    border-top:1px solid rgba(255,255,255,0.08);
    color:#7d8ca5;
}

@media(max-width:900px){

    .name{
        font-size:52px;
    }

    .about{
        grid-template-columns:1fr;
    }

}

</style>
</head>

<body>

<!-- HERO -->

<div class="banner">

<canvas id="c"></canvas>

<div class="content">

<div class="tag">Software Engineer • Backend • AI • Cloud</div>

<div class="name">Sanjay Kumar</div>

<div class="role">
Building scalable backend systems, AI-powered automation platforms,
real-time IoT solutions, and cloud-native applications with modern technologies.
</div>

<div class="hero-buttons">
<a href="https://github.com/zeus881" class="btn btn-primary">View GitHub</a>

<a href="https://www.linkedin.com/in/sanjay-kumar-7689531b5/" class="btn btn-secondary">
LinkedIn Profile
</a>
</div>

</div>

<div class="location">
Greater Noida, India
</div>

</div>

<!-- ABOUT -->

<section>

<h2 class="section-title">About Me</h2>

<div class="about">

<div class="about-card">
<p>
Software Engineer with hands-on experience developing scalable backend systems,
real-time retail automation platforms, cloud infrastructure,
and AI-driven client targeting solutions.

Currently working at Rebhu Computing Pvt. Ltd.,
where I build enterprise-level applications using Elixir, Phoenix,
Docker, MQTT, and modern AI technologies.
</p>
</div>

<div class="about-card">
<p>
Previously worked with Yottec System LLP on Ministry of Defence projects,
creating real-time algorithms, drone software systems,
and automation solutions using Python and AWS cloud services.
</p>
</div>

</div>

</section>

<!-- SKILLS -->

<section>

<h2 class="section-title">Core Expertise</h2>

<div class="skills-grid">

<div class="skill-card">
<h3>Backend Engineering</h3>
<p>
Elixir, Phoenix, Python, Node.js, REST APIs,
Microservices, Distributed Systems
</p>
</div>

<div class="skill-card">
<h3>Cloud & DevOps</h3>
<p>
AWS, Docker, Kubernetes, Podman,
CI/CD, Linux Infrastructure
</p>
</div>

<div class="skill-card">
<h3>AI & Automation</h3>
<p>
LLMs, Ollama, Streamlit,
AI Client Targeting, Automation Systems
</p>
</div>

<div class="skill-card">
<h3>IoT & Real-Time Systems</h3>
<p>
MQTT, ESL Devices,
Real-Time Sync Systems,
Retail Automation
</p>
</div>

</div>

</section>

<!-- PROJECTS -->

<section>

<h2 class="section-title">Featured Projects</h2>

<div class="projects-grid">

<div class="project-card">
<h3>Retail ESL Automation</h3>

<p>
Real-time retail automation platform with live price synchronization,
barcode updates, and IoT communication across multiple ESL devices.
</p>

<div class="tech">
Elixir • Phoenix • MQTT • Docker
</div>
</div>

<div class="project-card">
<h3>AI Client Ranking System</h3>

<p>
AI-powered client ranking and targeting solution using local LLMs,
web scraping, and intelligent summarization pipelines.
</p>

<div class="tech">
Python • Ollama • Streamlit • AI
</div>
</div>

<div class="project-card">
<h3>Drone Software System</h3>

<p>
Defence-oriented drone software platform with automation algorithms,
real-time communication systems, and AWS integration.
</p>

<div class="tech">
Python • AWS • Real-Time Systems
</div>
</div>

</div>

</section>

<!-- EXPERIENCE -->

<section>

<h2 class="section-title">Experience</h2>

<div class="timeline">

<div class="timeline-item">
<h3>Software Engineer — Rebhu Computing Pvt. Ltd.</h3>
<span>Feb 2026 — Present</span>

<p>
Building scalable backend systems, AI automation platforms,
and secure containerized enterprise applications.
</p>
</div>

<div class="timeline-item">
<h3>Junior Engineer Project Coordinator — Yottec System LLP</h3>
<span>Jan 2025 — Feb 2026</span>

<p>
Worked on Ministry of Defence software systems,
automation tools, and real-time algorithm development.
</p>
</div>

</div>

</section>

<!-- FOOTER -->

<footer>

© 2026 Sanjay Kumar • Software Engineer • AI & Cloud Enthusiast

</footer>

<!-- ORIGINAL BANNER ANIMATION CODE (UNCHANGED) -->

<script>

const canvas = document.getElementById('c');
const ctx = canvas.getContext('2d');

function resize() {
  canvas.width = window.innerWidth;
  canvas.height = window.innerHeight;
}
resize();
window.addEventListener('resize', resize);

const COLORS = ['#7F77DD','#1D9E75','#185FA5','#5DCAA5','#AFA9EC'];

function hexToRgb(hex) {
  const r = parseInt(hex.slice(1,3),16);
  const g = parseInt(hex.slice(3,5),16);
  const b = parseInt(hex.slice(5,7),16);
  return `${r},${g},${b}`;
}

const dots = Array.from({length: 90}, () => ({
  x: Math.random() * canvas.width,
  y: Math.random() * canvas.height,
  vx: (Math.random() - 0.5) * 0.4,
  vy: (Math.random() - 0.5) * 0.4,
  r: Math.random() * 1.8 + 0.5,
  color: COLORS[Math.floor(Math.random() * COLORS.length)],
  opacity: Math.random() * 0.55 + 0.2
}));

function draw() {
  const W = canvas.width, H = canvas.height;
  ctx.clearRect(0, 0, W, H);

  ctx.fillStyle = '#060B14';
  ctx.fillRect(0, 0, W, H);

  const g1 = ctx.createRadialGradient(W * 0.78, H * 0.2, 0, W * 0.78, H * 0.2, 260);
  g1.addColorStop(0, 'rgba(127,119,221,0.09)');
  g1.addColorStop(1, 'transparent');
  ctx.fillStyle = g1;
  ctx.fillRect(0, 0, W, H);

  const g2 = ctx.createRadialGradient(W * 0.15, H, 0, W * 0.15, H, 220);
  g2.addColorStop(0, 'rgba(29,158,117,0.08)');
  g2.addColorStop(1, 'transparent');
  ctx.fillStyle = g2;
  ctx.fillRect(0, 0, W, H);

  for (let i = 0; i < dots.length; i++) {
    for (let j = i + 1; j < dots.length; j++) {
      const dx = dots[i].x - dots[j].x;
      const dy = dots[i].y - dots[j].y;
      const dist = Math.sqrt(dx * dx + dy * dy);

      if (dist < 120) {
        const alpha = (1 - dist / 120) * 0.2;

        ctx.beginPath();
        ctx.strokeStyle = `rgba(${hexToRgb(dots[i].color)},${alpha})`;
        ctx.lineWidth = 0.6;
        ctx.moveTo(dots[i].x, dots[i].y);
        ctx.lineTo(dots[j].x, dots[j].y);
        ctx.stroke();
      }
    }
  }

  dots.forEach(d => {

    ctx.beginPath();
    ctx.arc(d.x, d.y, d.r, 0, Math.PI * 2);
    ctx.fillStyle = `rgba(${hexToRgb(d.color)},${d.opacity})`;
    ctx.fill();

    d.x += d.vx;
    d.y += d.vy;

    if (d.x < 0 || d.x > W) d.vx *= -1;
    if (d.y < 0 || d.y > H) d.vy *= -1;
  });

  requestAnimationFrame(draw);
}

draw();

</script>

</body>
</html>
