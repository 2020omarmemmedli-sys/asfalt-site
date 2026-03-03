<!DOCTYPE html>
<html lang="az">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Premium Asfalt İşləri</title>
<meta name="description" content="Premium asfalt çəkilişi və yol işləri">

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700;800&display=swap" rel="stylesheet">

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Poppins,sans-serif;
scroll-behavior:smooth;
}

body{
background:#0b0b0b;
color:white;
}

/* NAVBAR */

nav{
position:fixed;
width:100%;
top:0;
background:rgba(0,0,0,0.9);
padding:15px 10%;
display:flex;
justify-content:space-between;
z-index:999;
}

nav h2{
color:#FFD700;
}

nav a{
color:white;
text-decoration:none;
margin-left:25px;
transition:.3s;
}

nav a:hover{
color:#FFD700;
}

/* HERO */

.hero{
height:100vh;
display:flex;
flex-direction:column;
justify-content:center;
align-items:center;
text-align:center;
background:linear-gradient(rgba(0,0,0,.7),rgba(0,0,0,.7)),
url("https://images.unsplash.com/photo-1503387762-592deb58ef4e") center/cover;
padding:0 10%;
}

.hero h1{
font-size:65px;
color:#FFD700;
}

.hero p{
margin-top:20px;
max-width:800px;
font-size:20px;
}

.btn{
margin-top:35px;
padding:15px 40px;
background:#FFD700;
color:black;
text-decoration:none;
border-radius:30px;
font-weight:700;
transition:.3s;
display:inline-block;
}

.btn:hover{
background:white;
}

/* SECTIONS */

section{
padding:120px 10%;
}

.title{
text-align:center;
font-size:42px;
color:#FFD700;
margin-bottom:70px;
}

/* SERVICES */

.services{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(280px,1fr));
gap:35px;
}

.card{
background:#151515;
padding:40px;
border-radius:25px;
transition:.4s;
box-shadow:0 0 30px rgba(0,0,0,.5);
}

.card:hover{
transform:translateY(-12px);
}

.card h3{
color:#FFD700;
margin-bottom:15px;
}

/* GALLERY */

.gallery{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:25px;
}

.gallery img{
width:100%;
border-radius:20px;
transition:.3s;
}

.gallery img:hover{
transform:scale(1.05);
}

/* CONTACT */

form{
max-width:600px;
margin:auto;
display:flex;
flex-direction:column;
gap:20px;
}

input,textarea{
padding:15px;
border-radius:12px;
border:none;
outline:none;
background:#1a1a1a;
color:white;
}

footer{
text-align:center;
padding:30px;
background:black;
color:gray;
}

@media(max-width:768px){
.hero h1{font-size:40px;}
nav{padding:15px 5%;}
}

</style>
</head>

<body>

<nav>
<h2>Premium Asfalt</h2>
<div>
<a href="#services">Xidmətlər</a>
<a href="#gallery">Qalereya</a>
<a href="#contact">Əlaqə</a>
</div>
</nav>

<section class="hero">
<h1>PREMIUM ASFALT İŞLƏRİ</h1>
<p>Yol, həyət və sənaye asfaltlanması üzrə peşəkar xidmət. Keyfiyyət və zəmanət bizim prioritetimizdir.</p>

<a class="btn" href="#contact">Əlaqə Saxla</a>
</section>

<section id="services">
<h2 class="title">Xidmətlərimiz</h2>

<div class="services">

<div class="card">
<h3>🚧 Yol Asfaltlanması</h3>
<p>Magistral və daxili yolların premium keyfiyyətlə asfaltlanması.</p>
</div>

<div class="card">
<h3>🏠 Həyət Asfaltlanması</h3>
<p>Villa və obyekt həyətlərinin modern asfalt örtüyü.</p>
</div>

<div class="card">
<h3>🔧 Təmir İşləri</h3>
<p>Çat və zədələnmiş asfaltların bərpası.</p>
</div>

</div>
</section>

<section id="gallery">
<h2 class="title">Qalereya</h2>

<div class="gallery">
<img src="https://images.unsplash.com/photo-1504384308090-c894fdcc538">
<img src="https://images.unsplash.com/photo-1541888946425-d81bb19240f5">
<img src="https://images.unsplash.com/photo-1503387762-592deb58ef4e">
</div>
</section>

<section id="contact">
<h2 class="title">Əlaqə</h2>

<form onsubmit="sendWhatsApp(event)">
<input id="name" placeholder="Ad Soyad">
<input id="phone" placeholder="Telefon">
<textarea id="message" placeholder="Mesaj"></textarea>

<button class="btn" type="submit">WhatsApp Yaz</button>
</form>

</section>

<footer>
© 2026 Premium Asfalt İşləri
</footer>

<script>
function sendWhatsApp(e){
e.preventDefault();

let name=document.getElementById("name").value;
let phone=document.getElementById("phone").value;
let message=document.getElementById("message").value;

let text="Ad: "+name+
"%0ATelefon: "+phone+
"%0AMesaj: "+message;

window.open("https://wa.me/994704131338?text="+text,"_blank");
}
</script>

</body>
</html>
