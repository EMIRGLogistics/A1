<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>EMIRG AI | Strategic AI for Logistics & Supply Chain</title>

<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@500;600&family=Inter:wght@300;400;500;600&display=swap" rel="stylesheet">

<style>
:root{
--black:#0b0b0b;
--gold:#C6A75E;
--dark:#161616;
--gray:#a8a8a8;
--white:#ffffff;
}

*{margin:0;padding:0;box-sizing:border-box;font-family:'Inter',sans-serif;scroll-behavior:smooth;}
body{background:var(--black);color:var(--white);line-height:1.7;}

.container{width:90%;max-width:1200px;margin:auto;}

/* HEADER */
header{
position:fixed;
width:100%;
top:0;
background:rgba(11,11,11,0.96);
border-bottom:1px solid rgba(198,167,94,0.2);
z-index:1000;
}

.nav-wrapper{
display:flex;
justify-content:space-between;
align-items:center;
height:80px;
}

.logo{
font-family:'Playfair Display',serif;
font-size:1.8rem;
color:var(--gold);
font-weight:600;
}

nav ul{
list-style:none;
display:flex;
gap:40px;
align-items:center;
}

nav a{
text-decoration:none;
color:var(--white);
font-weight:500;
transition:0.3s;
}

nav a:hover{color:var(--gold);}

/* HERO */
.hero{
padding-top:160px;
padding-bottom:120px;
}

.hero h1{
font-family:'Playfair Display',serif;
font-size:3rem;
margin-bottom:20px;
}

.hero p{color:var(--gray);margin-bottom:40px;}

.cta-btn{
display:inline-block;
padding:16px 40px;
border:2px solid var(--gold);
color:var(--gold);
text-decoration:none;
font-weight:600;
transition:0.3s;
cursor:pointer;
background:none;
}

.cta-btn:hover{
background:var(--gold);
color:var(--black);
}

section{padding:120px 0;}
.section-title{
font-family:'Playfair Display',serif;
font-size:2.3rem;
margin-bottom:60px;
}

.grid{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(280px,1fr));
gap:50px;
}

.card{
border-top:2px solid var(--gold);
padding-top:25px;
}

.card p{color:var(--gray);}

/* REVIEWS */
.review{
background:var(--dark);
padding:35px;
border-radius:4px;
}

.review p{
font-style:italic;
color:var(--gray);
margin-bottom:20px;
}

.review strong{color:var(--gold);}

/* ESTIMATOR */
.estimator{
background:linear-gradient(135deg,#1a1a1a,#0b0b0b);
padding:50px;
border-radius:6px;
}

.estimator select{
width:100%;
padding:15px;
margin-bottom:20px;
background:#111;
color:white;
border:1px solid var(--gold);
}

.result{
margin:20px 0;
font-weight:600;
color:var(--gold);
}

/* FORM */
form input, form textarea{
width:100%;
padding:15px;
margin-bottom:20px;
background:#111;
border:1px solid var(--gold);
color:white;
}

footer{
padding:40px 0;
border-top:1px solid rgba(198,167,94,0.2);
text-align:center;
color:var(--gray);
}

/* MOBILE */
@media(max-width:768px){
.nav-wrapper{flex-direction:column;height:auto;padding:20px 0;gap:15px;}
nav ul{gap:20px;flex-wrap:wrap;justify-content:center;}
.hero h1{font-size:2rem;}
}
</style>
</head>

<body>

<header>
<div class="container nav-wrapper">
<div class="logo">EMIRG AI</div>
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

<section class="hero">
<div class="container">
<h1>AI Strategy for Global Logistics & Supply Chain Leadership</h1>
<p>Operational visibility. Predictive precision. Autonomous execution.</p>
<a href="#contact" class="cta-btn">Request Strategic Assessment →</a>
</div>
</section>

<section id="solutions">
<div class="container">
<h2 class="section-title">Advisory Solutions</h2>
<div class="grid">
<div class="card"><h3>Operational Mapping</h3><p>End-to-end AI visibility and structural optimization.</p></div>
<div class="card"><h3>Forecasting & Demand Planning</h3><p>Predictive intelligence improving forecast accuracy.</p></div>
<div class="card"><h3>Intelligent Autonomy</h3><p>Autonomous systems accelerating execution.</p></div>
<div class="card"><h3>AI Risk & Resilience Modeling</h3><p>Disruption simulation across global supply networks.</p></div>
</div>
</div>
</section>

<section id="insights">
<div class="container">
<h2 class="section-title">AI Market Insights</h2>
<p style="color:var(--gray);max-width:700px;">
AI adoption in global logistics is accelerating due to geopolitical volatility,
inventory compression, and demand unpredictability. Enterprise supply chains
are leveraging AI control towers to improve forecasting precision by up to 35%
and reduce operational friction by nearly 30%.
</p>
</div>
</section>

<section id="reviews">
<div class="container">
<h2 class="section-title">Client Perspectives</h2>
<div class="grid">
<div class="review"><p>"EMIRG AI redefined our operational transparency."</p><strong>COO, Global Freight Enterprise</strong></div>
<div class="review"><p>"Forecast accuracy improved materially across regions."</p><strong>VP Supply Chain Strategy</strong></div>
<div class="review"><p>"Autonomous execution reduced manual friction."</p><strong>Director Logistics Innovation</strong></div>
<div class="review"><p>"Resilience modeling prepared us for systemic disruptions."</p><strong>Chief Strategy Officer</strong></div>
</div>
</div>
</section>

<section id="estimator">
<div class="container">
<h2 class="section-title">AI Readiness Estimator</h2>

<div class="estimator">

<select id="companySize">
<option value="">Company Size</option>
<option value="Small">Small (1-100)</option>
<option value="Mid">Mid-Market (100-1000)</option>
<option value="Enterprise">Enterprise (1000+)</option>
</select>

<select id="complexity">
<option value="">Operational Complexity</option>
<option value="Single Region">Single Region</option>
<option value="Multi-Region">Multi-Region</option>
<option value="Global Network">Global Network</option>
</select>

<div class="result" id="result"></div>

<button class="cta-btn" onclick="transferEstimator()">Continue to Strategic Inquiry →</button>

</div>
</div>
</section>

<section id="contact">
<div class="container">
<h2 class="section-title">Strategic Inquiry</h2>

<form onsubmit="sendEmail(); return false;">
<input type="text" id="name" placeholder="Full Name" required>
<input type="text" id="company" placeholder="Company Name" required>
<textarea id="message" placeholder="Describe your operational objectives..." required></textarea>
<button class="cta-btn" type="submit">Submit Strategic Request →</button>
</form>

</div>
</section>

<footer>
<div class="container">
<p>© 2026 EMIRG AI. All rights reserved.</p>
</div>
</footer>

<script>
let storedSize="";
let storedComplexity="";

document.getElementById("complexity").addEventListener("change", function(){
storedSize=document.getElementById("companySize").value;
storedComplexity=this.value;
if(storedSize && storedComplexity){
document.getElementById("result").innerHTML=
"Recommended Engagement: Enterprise AI Strategy & Autonomy Assessment";
}
});

function transferEstimator(){
if(!storedSize || !storedComplexity){
alert("Please complete the estimator selections.");
return;
}
document.getElementById("message").value =
"AI Readiness Inputs:\nCompany Size: "+storedSize+
"\nOperational Complexity: "+storedComplexity+
"\n\nObjectives:\n";
document.getElementById("contact").scrollIntoView({behavior:"smooth"});
}

function sendEmail(){
let name=document.getElementById("name").value;
let company=document.getElementById("company").value;
let message=document.getElementById("message").value;

window.location.href=
`mailto:logistics@emirg-group.com?subject=Strategic AI Inquiry - ${company}&body=Name: ${name}%0ACompany: ${company}%0A%0A${encodeURIComponent(message)}`;
}
</script>

</body>
</html>
