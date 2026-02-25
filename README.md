<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>EMIRG AI | Strategic AI for Global Supply Chains</title>

<link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">

<style>
:root{
--black:#0d0d0d;
--gold:#C6A75E;
--gray:#9a9a9a;
--light-gray:#cfcfcf;
--divider:rgba(255,255,255,0.06);
}

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:'Inter',sans-serif;
scroll-behavior:smooth;
}

body{
background:var(--black);
color:white;
line-height:1.6;
}

.container{
width:88%;
max-width:1100px;
margin:auto;
}

/* HEADER */
header{
position:fixed;
top:0;
width:100%;
background:rgba(13,13,13,0.97);
border-bottom:1px solid var(--divider);
z-index:1000;
}

.nav-wrapper{
display:flex;
justify-content:space-between;
align-items:center;
height:85px;
}

.logo{
font-weight:700;
letter-spacing:1px;
font-size:1.4rem;
color:white;
}

.logo span{
color:var(--gold);
}

nav ul{
display:flex;
gap:42px;
list-style:none;
}

nav a{
position:relative;
text-decoration:none;
color:var(--light-gray);
font-weight:500;
font-size:0.9rem;
}

nav a::after{
content:'';
position:absolute;
left:0;
bottom:-6px;
width:0;
height:1px;
background:var(--gold);
transition:width 0.3s ease;
}

nav a:hover{
color:white;
}

nav a:hover::after{
width:100%;
}

/* HERO */
.hero{
padding-top:180px;
padding-bottom:140px;
border-bottom:1px solid var(--divider);
}

.hero h1{
font-size:2.4rem;
font-weight:600;
margin-bottom:35px;
max-width:760px;
}

.hero-image img{
width:100%;
border-radius:4px;
margin-bottom:35px;
}

.hero p{
color:var(--gray);
max-width:600px;
margin-bottom:40px;
}

.cta-btn{
display:inline-block;
padding:14px 36px;
border:1px solid var(--gold);
color:var(--gold);
text-decoration:none;
font-weight:600;
font-size:0.85rem;
letter-spacing:0.5px;
transition:all 0.3s ease;
background:none;
cursor:pointer;
}

.cta-btn:hover{
background:var(--gold);
color:black;
}

/* SECTIONS */
section{
padding:130px 0;
border-bottom:1px solid var(--divider);
}

.section-title{
font-size:1.8rem;
font-weight:600;
margin-bottom:70px;
}

.grid{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(260px,1fr));
gap:60px;
}

.card{
padding-top:10px;
}

.card h3{
font-weight:600;
margin-bottom:12px;
}

.card p{
color:var(--gray);
margin-bottom:12px;
}

.metric{
color:var(--gold);
font-weight:600;
font-size:0.9rem;
}

/* REVIEWS */
.review{
background:#141414;
padding:30px;
border-radius:4px;
}

.review p{
color:var(--gray);
margin-bottom:15px;
font-style:italic;
}

.review strong{
color:white;
font-size:0.85rem;
}

/* ESTIMATOR */
.estimator{
max-width:650px;
}

select{
width:100%;
padding:14px;
margin-bottom:20px;
background:#111;
color:white;
border:1px solid var(--divider);
}

.result{
margin:20px 0;
color:var(--gold);
font-weight:600;
}

/* FORM */
form{
max-width:650px;
}

form input, form textarea{
width:100%;
padding:14px;
margin-bottom:20px;
background:#111;
border:1px solid var(--divider);
color:white;
}

/* FADE ANIMATION */
.fade{
opacity:0;
transform:translateY(25px);
transition:all 0.8s ease;
}

.fade.visible{
opacity:1;
transform:translateY(0);
}

/* MOBILE */
@media(max-width:768px){
.nav-wrapper{
flex-direction:column;
height:auto;
padding:20px 0;
gap:20px;
}
nav ul{
flex-wrap:wrap;
justify-content:center;
gap:20px;
}
.hero h1{
font-size:1.8rem;
}
}
</style>
</head>

<body>

<header>
<div class="container nav-wrapper">
<div class="logo">EMIRG <span>AI</span></div>
<nav>
<ul>
<li><a href="#solutions">Solutions</a></li>
<li><a href="#insights">Insights</a></li>
<li><a href="#reviews">Perspectives</a></li>
<li><a href="#estimator">AI Estimator</a></li>
<li><a href="#contact">Engage</a></li>
</ul>
</nav>
</div>
</header>

<section class="hero fade">
<div class="container">
<h1>AI Strategy for Global Logistics & Supply Chain Leadership</h1>

<div class="hero-image">
<img src="https://images.unsplash.com/photo-1581091012184-5c6d1d3f6b56" alt="Global supply chain control tower">
</div>

<p>Operational visibility. Predictive precision. Autonomous execution across complex global networks.</p>

<a href="#contact" class="cta-btn">Request Strategic Assessment →</a>
</div>
</section>

<section id="solutions" class="fade">
<div class="container">
<h2 class="section-title">Advisory Solutions</h2>

<div class="grid">

<div class="card">
<h3>Operational Mapping</h3>
<p>End-to-end AI visibility frameworks identifying structural inefficiencies.</p>
<div class="metric">18–30% Potential Cost Reduction</div>
</div>

<div class="card">
<h3>Forecasting & Demand Planning</h3>
<p>Advanced predictive models stabilizing demand volatility.</p>
<div class="metric">25–35% Forecast Accuracy Improvement</div>
</div>

<div class="card">
<h3>Intelligent Autonomy</h3>
<p>Autonomous execution systems enhancing decision velocity.</p>
<div class="metric">2–3x Faster Operational Decisions</div>
</div>

<div class="card">
<h3>AI Risk & Resilience Modeling</h3>
<p>Scenario modeling to mitigate systemic supply disruptions.</p>
<div class="metric">20–40% Risk Exposure Reduction</div>
</div>

</div>
</div>
</section>

<section id="estimator" class="fade">
<div class="container">
<h2 class="section-title">AI Readiness & ROI Estimator</h2>

<div class="estimator">

<select id="companySize">
<option value="">Company Size</option>
<option value="1">Small (1-100)</option>
<option value="2">Mid-Market (100-1000)</option>
<option value="3">Enterprise (1000+)</option>
</select>

<select id="complexity">
<option value="">Operational Complexity</option>
<option value="1">Single Region</option>
<option value="2">Multi-Region</option>
<option value="3">Global Network</option>
</select>

<div class="result" id="result"></div>

<button class="cta-btn" onclick="transferEstimator()">Continue to Strategic Inquiry →</button>

</div>
</div>
</section>

<section id="contact" class="fade">
<div class="container">
<h2 class="section-title">Strategic Inquiry</h2>

<form onsubmit="sendEmail(); return false;">
<input type="text" id="name" placeholder="Full Name" required>
<input type="text" id="company" placeholder="Company Name" required>
<textarea id="message" placeholder="Describe your objectives..." required></textarea>
<button class="cta-btn" type="submit">Submit Strategic Request →</button>
</form>

</div>
</section>

<script>
let storedData="";

document.getElementById("complexity").addEventListener("change", calculateROI);

function calculateROI(){
let size=parseInt(document.getElementById("companySize").value);
let complexity=parseInt(document.getElementById("complexity").value);
if(size && complexity){
let score=size*complexity;
let roi=(score*8)+10;
storedData=`AI Readiness Assessment:
Company Size Score: ${size}
Complexity Score: ${complexity}
Estimated ROI Potential: ${roi}%+
Recommended Engagement: Enterprise AI Transformation`;
document.getElementById("result").innerHTML=
`Estimated ROI Potential: ${roi}%+`;
}
}

function transferEstimator(){
if(!storedData){
alert("Please complete the estimator selections.");
return;
}
document.getElementById("message").value=storedData+"\n\nObjectives:\n";
document.getElementById("contact").scrollIntoView({behavior:"smooth"});
}

function sendEmail(){
let name=document.getElementById("name").value;
let company=document.getElementById("company").value;
let message=document.getElementById("message").value;

window.location.href=
`mailto:logistics@emirg-group.com?subject=Strategic AI Inquiry - ${company}&body=Name: ${name}%0ACompany: ${company}%0A%0A${encodeURIComponent(message)}`;
}

/* Fade In Observer */
const faders=document.querySelectorAll('.fade');
const observer=new IntersectionObserver(entries=>{
entries.forEach(entry=>{
if(entry.isIntersecting){
entry.target.classList.add('visible');
}
});
},{threshold:0.2});

faders.forEach(el=>observer.observe(el));
</script>

</body>
</html>
