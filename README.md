My Web Ferdi Adillah (Versi Lengkap)

<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>My Web Ferdi Adillah</title>

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Arial,sans-serif;
scroll-behavior:smooth;
}

body{
background:#0f172a;
color:white;
}

header{
background:linear-gradient(135deg,#2563eb,#7c3aed);
padding:25px;
text-align:center;
position:sticky;
top:0;
z-index:1000;
}

header h1{
font-size:2rem;
}

nav{
margin-top:10px;
}

nav a{
color:white;
text-decoration:none;
margin:0 15px;
font-weight:bold;
transition:.3s;
}

nav a:hover{
color:#facc15;
}

.hero{
height:100vh;
display:flex;
flex-direction:column;
justify-content:center;
align-items:center;
text-align:center;
padding:20px;
}

.hero h2{
font-size:3rem;
animation:glow 2s infinite alternate;
}

@keyframes glow{
from{
text-shadow:0 0 10px #60a5fa;
}
to{
text-shadow:0 0 30px #60a5fa;
}
}

.hero p{
margin-top:15px;
max-width:700px;
color:#cbd5e1;
}

button{
padding:12px 25px;
border:none;
border-radius:10px;
background:#2563eb;
color:white;
cursor:pointer;
margin-top:20px;
font-size:16px;
}

button:hover{
background:#1d4ed8;
}

.clock{
font-size:2rem;
margin-top:20px;
font-weight:bold;
color:#60a5fa;
}

.section{
padding:70px 20px;
max-width:1000px;
margin:auto;
}

.section h2{
margin-bottom:20px;
text-align:center;
}

.card{
background:#1e293b;
padding:25px;
border-radius:15px;
margin-top:20px;
box-shadow:0 0 15px rgba(0,0,0,0.3);
}

.social{
display:inline-block;
padding:12px 20px;
margin:10px;
border-radius:10px;
text-decoration:none;
color:white;
font-weight:bold;
}

.wa{
background:#25D366;
}

.ig{
background:#E1306C;
}

footer{
background:#020617;
padding:25px;
text-align:center;
margin-top:50px;
}

</style>
</head>
<body>

<header>

<h1>MY WEB FERDI ADILLAH</h1>

<nav>
<a href="#home">Home</a>
<a href="#about">Tentang</a>
<a href="#project">Project</a>
<a href="#contact">Kontak</a>
</nav>

</header>

<section class="hero" id="home">

<h2>Selamat Datang 👋</h2>

<p>
Halo! Saya Ahmad Ferdi Adillah.
Pelajar SMK yang tertarik pada dunia teknologi,
website, jaringan komputer, AI, dan game strategi.
</p>

<button onclick="halo()">
Klik Saya
</button>

<div class="clock" id="clock">
00:00:00
</div>

</section>

<section class="section" id="about">

<h2>Tentang Saya</h2>

<div class="card">

<p>
Nama saya Ahmad Ferdi Adillah.

Saya sedang belajar HTML, CSS, JavaScript,
jaringan komputer, kecerdasan buatan (AI),
serta berbagai teknologi modern.

Cita-cita saya adalah menjadi programmer profesional
dan terus mengembangkan kemampuan di bidang IT.
</p>

</div>

</section>

<section class="section" id="project">

<h2>Project Saya</h2>

<div class="card">
<h3>🌐 Website Pribadi</h3>
<p>Website yang dibuat menggunakan HTML, CSS dan JavaScript.</p>
</div>

<div class="card">
<h3>🤖 Belajar AI</h3>
<p>Sedang mempelajari chatbot dan kecerdasan buatan.</p>
</div>

<div class="card">
<h3>💻 Coding Journey</h3>
<p>Mendalami dunia pemrograman dan pengembangan web.</p>
</div>

</section>

<section class="section" id="contact">

<h2>Kontak Saya</h2>

<div class="card" style="text-align:center;">

<a class="social wa"
href="https://wa.me/6283832841068"
target="_blank">
📱 WhatsApp
</a>

<a class="social ig"
href="https://instagram.com/ahmadferdiadillah"
target="_blank">
📸 Instagram
</a>

<p style="margin-top:20px;">
Terima kasih telah mengunjungi website saya 🚀
</p>

</div>

</section>

<footer>

<p>
© 2026 My Web Ferdi Adillah
</p>

</footer>

<script>

function halo(){
alert("Halo! Selamat datang di website Ahmad Ferdi Adillah 🚀");
}

function updateClock(){

let now = new Date();

let jam = String(now.getHours()).padStart(2,'0');
let menit = String(now.getMinutes()).padStart(2,'0');
let detik = String(now.getSeconds()).padStart(2,'0');

document.getElementById("clock").innerHTML =
jam + ":" + menit + ":" + detik;

}

setInterval(updateClock,1000);
updateClock();

</script>

</body>
</html>
