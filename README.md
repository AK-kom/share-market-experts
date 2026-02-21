<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Share Market Experts</title>
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">
<style>
*{margin:0; padding:0; box-sizing:border-box; font-family:'Poppins', sans-serif; scroll-behavior:smooth;}
body{background:linear-gradient(135deg,#0f2027,#203a43,#2c5364); color:#fff;}
header{display:flex; justify-content:space-between; align-items:center; padding:20px 8%; position:fixed; width:100%; background:rgba(0,0,0,0.4); backdrop-filter:blur(10px); z-index:1000;}
header h1{font-weight:700; letter-spacing:1px;}
nav a{color:#fff; text-decoration:none; margin-left:25px; font-weight:500; transition:0.3s;}
nav a:hover{color:#00f5d4;}
.hero{height:100vh; display:flex; flex-direction:column; justify-content:center; align-items:center; text-align:center; padding:0 20px;}
.hero h2{font-size:50px; margin-bottom:20px; background:linear-gradient(90deg,#00f5d4,#00bbf9); -webkit-background-clip:text; -webkit-text-fill-color:transparent;}
.hero p{max-width:600px; opacity:0.8; margin-bottom:30px;}
.btn{padding:12px 30px; border:none; background:linear-gradient(90deg,#00f5d4,#00bbf9); color:#000; font-weight:600; border-radius:30px; cursor:pointer; transition:0.3s;}
.btn:hover{transform:scale(1.05);}
section{padding:100px 8%;}
.glass{background:rgba(255,255,255,0.08); border-radius:20px; padding:40px; backdrop-filter:blur(10px); box-shadow:0 8px 32px rgba(0,0,0,0.3);}
.services, .pricing{display:grid; grid-template-columns:repeat(auto-fit,minmax(250px,1fr)); gap:30px; margin-top:40px;}
.card{padding:30px; border-radius:15px; background:rgba(255,255,255,0.05); transition:0.4s;}
.card:hover{transform:translateY(-10px); background:rgba(0,245,212,0.1);}
.stats{display:flex; justify-content:space-around; flex-wrap:wrap; margin-top:40px;}
.stat{text-align:center; margin:20px;}
.stat h3{font-size:40px; color:#00f5d4;}
.contact form{max-width:500px; margin:auto; display:flex; flex-direction:column;}
.contact input, .contact textarea{margin-bottom:15px; padding:12px; border-radius:10px; border:none; background:rgba(255,255,255,0.1); color:#fff;}
.contact button{width:100%; padding:12px; border:none; border-radius:10px; background:linear-gradient(90deg,#00f5d4,#00bbf9); color:#000; font-weight:600; cursor:pointer; transition:0.3s;}
.contact button:hover{transform:scale(1.05);}
footer{text-align:center; padding:30px; background:rgba(0,0,0,0.5);}
h2{text-align:center; margin-bottom:30px;}
.pricing .card h3{text-align:center; margin-bottom:15px; color:#00f5d4;}
/* WhatsApp floating button */
#whatsapp-btn {
position: fixed;
bottom: 25px;
right: 25px;
background-color: #25D366;
color: #fff;
border-radius: 50%;
width: 60px;
height: 60px;
display: flex;
justify-content: center;
align-items: center;
font-size: 30px;
box-shadow: 0 5px 15px rgba(0,0,0,0.3);
cursor: pointer;
z-index: 10000;
transition: transform 0.3s;
}
#whatsapp-btn:hover{transform: scale(1.1);}
</style>
</head>
<body>

<header>
<h1>Share Market Experts</h1>
<nav>
<a href="#about">About</a>
<a href="#services">Services</a>
<a href="#pricing">Pricing</a>
<a href="#contact">Contact</a>
</nav>
</header>

<section class="hero">
<h2>Invest Smart. Grow Wealth.</h2>
<p>Data-driven stock market guidance designed to maximize returns and manage risks intelligently.</p>
<button class="btn" onclick="document.getElementById('contact').scrollIntoView()">Start Investing</button>
</section>

<section id="about">
<div class="glass">
<h2>Who We Are</h2>
<p>We provide advanced stock analysis, personalized portfolio strategies, and risk-managed investment planning to help you achieve long-term financial success.</p>
<div class="stats">
<div class="stat"><h3 id="clients">0</h3><p>Happy Clients</p></div>
<div class="stat"><h3 id="returns">0</h3><p>% Avg Returns</p></div>
<div class="stat"><h3 id="experience">0</h3><p>Years Experience</p></div>
</div>
</div>
</section>

<section id="services">
<h2>Our Services</h2>
<div class="services">
<div class="card">
<h3>Market Research</h3>
<p>Technical & fundamental analysis to identify high-growth opportunities.</p>
</div>
<div class="card">
<h3>Portfolio Strategy</h3>
<p>Diversified, risk-balanced portfolios tailored to your financial goals.</p>
</div>
<div class="card">
<h3>Wealth Planning</h3>
<p>Long-term investment roadmaps for sustainable wealth creation.</p>
</div>
</div>
</section>

<section id="pricing">
<h2>Service Charges</h2>
<div class="pricing">
<div class="card">
<h3>Basic Plan</h3>
<p>Rs 48,500 + 18% GST</p>
<p>Monthly stock tips + Weekly newsletter</p>
</div>
<div class="card">
<h3>Premium Plan</h3>
<p>Rs 75,000 + 18% GST</p>
<p>Portfolio review + Market insights + Weekly consultation</p>
</div>
<div class="card">
<h3>HNWI Services</h3>
<p>Rs 1,51,000 + 18% GST</p>
<p>Full portfolio management + Dedicated advisor + Daily tips</p>
</div>
</div>
</section>

<section id="contact">
<div class="glass contact">
<h2>Get In Touch</h2>
<p>Call us directly: <strong>7304190614</strong></p>
<form>
<input type="text" placeholder="Your Name" required>
<input type="email" placeholder="Your Email" required>
<textarea rows="5" placeholder="Your Message"></textarea>
<button type="submit">Send Message</button>
</form>
</div>
</section>

<footer>
© 2026 Share Market Experts | Designed for Financial Growth
</footer>

<!-- WhatsApp Button -->
<a id="whatsapp-btn" href="https://wa.me/917304190614" target="_blank">💬</a>

<script>
function animateValue(id, start, end, duration) {
let obj = document.getElementById(id);
let range = end - start;
let current = start;
let increment = end > start ? 1 : -1;
let stepTime = Math.abs(Math.floor(duration / range));
let timer = setInterval(function() {
current += increment;
obj.textContent = current;
if (current == end) clearInterval(timer);
}, stepTime);
}
window.onload = function(){
animateValue("clients",0,500,2000);
animateValue("returns",0,28,2000);
animateValue("experience",0,12,2000);
};
</script>

</body>
</html>
