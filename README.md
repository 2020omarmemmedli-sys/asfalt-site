<!DOCTYPE html>
<html lang="az">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Premium Asfalt İşləri</title>

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

/* NAV */

nav{
position:fixed;
width:100%;
top:0;
background:rgba(0,0,0,.9);
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
margin-left:25px;
text-decoration:none;
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

/* BUTTON */

.btn{
margin-top:35px;
padding:15px 40px;
background:#FFD700;
color:black;
text-decoration:none;
border-radius:30px;
font-weight:700;
display:inline-block;
transition:.3s;
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
margin-bottom:60px;
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
grid-template-columns:repeat(auto-fit,minmax(260px,1fr));
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
<a href="#about">Haqqımızda</a>
<a href="#services">Xidmətlər</a>
<a href="#gallery">İşlərimiz</a>
<a href="#team">Komanda</a>
<a href="#contact">Əlaqə</a>
</div>
</nav>

<section class="hero">
<h1>PREMIUM ASFALT İŞLƏRİ</h1>

<p>Peşəkar işçi heyəti, müasir texnika və yüksək keyfiyyətli asfalt materialları ilə xidmətinizdəyik.</p>

<a class="btn" href="#contact">WhatsApp Yaz</a>
</section>

<section id="about">
<h2 class="title">Haqqımızda</h2>

<div class="card">
<p>
Biz yol asfaltlanması, həyət asfaltı və təmir işləri üzrə peşəkar xidmət göstəririk. 
Müasir texnika və təcrübəli ustalarımız ilə keyfiyyətli və davamlı asfalt örtüyü hazırlayırıq.
</p>
</div>
</section>

<section id="services">
<h2 class="title">Gördüyümüz İşlər</h2>

<div class="services">

<div class="card">
<h3>🚧 Yol Asfaltı</h3>
<p>Magistral və daxili yolların asfaltlanması.</p>
</div>

<div class="card">
<h3>🏠 Həyət Asfaltı</h3>
<p>Villa və obyekt həyətlərinin asfaltlanması.</p>
</div>

<div class="card">
<h3>🔧 Təmir İşləri</h3>
<p>Asfalt çatlarının professional bərpası.</p>
</div>

</div>
</section>

<section id="gallery">
<h2 class="title">Asfalt İşlərimiz</h2>

<div class="gallery">
<img src="https://images.unsplash.com/photo-1503387762-592deb58ef4e">
<img src="https://images.unsplash.com/photo-1541888946425-d81bb19240f5">
<img src="https://images.unsplash.com/photo-1504384308090-c894fdcc538">
<img src="https://images.unsplash.com/photo-1506521781263-d8422e82f27a">
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
