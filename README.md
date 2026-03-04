<!DOCTYPE html>
<html lang="az">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>GOLDEN TASTE RESTORAN</title>
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
<style>

body{
    margin:0;
    font-family: 'Segoe UI', sans-serif;
    background:#111;
    color:white;
}

header{
    background:url('https://images.unsplash.com/photo-1555396273-367ea4eb4db5') center/cover no-repeat;
    height:100vh;
    display:flex;
    align-items:center;
    justify-content:center;
    text-align:center;
    position:relative;
}

header::after{
    content:"";
    position:absolute;
    width:100%;
    height:100%;
    background:rgba(0,0,0,0.7);
}

.header-content{
    position:relative;
    z-index:2;
}

header h1{
    font-size:60px;
    color:gold;
    margin:0;
}

header p{
    font-size:22px;
    margin-top:15px;
}

section{
    padding:70px 20px;
    text-align:center;
}

h2{
    color:gold;
    font-size:35px;
    margin-bottom:30px;
}

.about{
    max-width:900px;
    margin:auto;
    font-size:18px;
    line-height:1.8;
}

.menu{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:25px;
}

.card{
    background:#1c1c1c;
    padding:25px;
    border-radius:15px;
    box-shadow:0 0 15px rgba(255,215,0,0.2);
}

.card h3{
    color:gold;
}

.gallery{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:20px;
}

.gallery img{
    width:100%;
    border-radius:15px;
}

.reservation{
    background:#1a1a1a;
    padding:40px;
    border-radius:15px;
    max-width:600px;
    margin:auto;
}

button{
    background:gold;
    border:none;
    padding:15px 30px;
    font-size:16px;
    cursor:pointer;
    border-radius:10px;
    font-weight:bold;
}

footer{
    background:black;
    padding:20px;
    text-align:center;
    border-top:2px solid gold;
}

.whatsapp{
    position:fixed;
    bottom:20px;
    right:20px;
    background:#25D366;
    color:white;
    padding:16px 20px;
    border-radius:50%;
    font-size:26px;
    box-shadow:0 0 15px rgba(0,0,0,0.5);
}

.whatsapp a{
    color:white;
}

</style>
</head>
<body>

<header>
<div class="header-content">
<h1>GOLDEN TASTE</h1>
<p>Dadın zirvəsi burada başlayır</p>
</div>
</header>

<section>
<h2>Haqqımızda</h2>
<div class="about">
<p>
Golden Taste Restoranı qonaqlarına unudulmaz dad təcrübəsi yaşatmaq üçün yaradılmışdır. 
Bizim məqsədimiz sadəcə yemək təqdim etmək deyil, hər müştəriyə xüsusi atmosfer və lüks xidmət hissi yaşatmaqdır.
</p>
<p>
Restoranımızda milli Azərbaycan mətbəxi ilə yanaşı dünya mətbəxinin seçilmiş ləziz təamları təqdim olunur. 
Peşəkar aşpaz komandamız hər yeməyi sevgi və ustalıqla hazırlayır.
</p>
<p>
Rahat interyer, canlı musiqi gecələri və ailəvi mühit Golden Taste-i şəhərin ən seçilən məkanlarından birinə çevirir.
</p>
</div>
</section>

<section>
<h2>Menyu</h2>
<div class="menu">
<div class="card">
<h3>Steyk Special</h3>
<p>Premium dana əti, xüsusi sous ilə.</p>
</div>

<div class="card">
<h3>Qarışıq Kabab</h3>
<p>Milli ləzzətlərin möhtəşəm seçimi.</p>
</div>

<div class="card">
<h3>Dəniz Məhsulları</h3>
<p>Təzə karides, balıq və midyə.</p>
</div>

<div class="card">
<h3>Şirniyyatlar</h3>
<p>Evdə hazırlanmış desertlər.</p>
</div>
</div>
</section>

<section>
<h2>Qalereya</h2>
<div class="gallery">
<img src="https://images.unsplash.com/photo-1544025162-d76694265947">
<img src="https://images.unsplash.com/photo-1559339352-11d035aa65de">
<img src="https://images.unsplash.com/photo-1528605248644-14dd04022da1">
</div>
</section>

<section>
<h2>Rezervasiya</h2>
<div class="reservation">
<p>Stol rezerv etmək üçün bizimlə WhatsApp vasitəsilə əlaqə saxlayın.</p>
<button onclick="window.location.href='https://wa.me/994553960085'">
Rezervasiya Et
</button>
</div>
</section>

<footer>
<p>© 2026 Golden Taste Restoran | Bütün hüquqlar qorunur</p>
</footer>

<div class="whatsapp">
<a href="https://wa.me/994553960085" target="_blank">
<i class="fab fa-whatsapp"></i>
</a>
</div>

</body>
</html></div>
</section>

<section>
<div class="card">
<h3>Yol Tikintisi</h3>
<p>Magistral və daxili yolların peşəkar tikintisi.</p>
</div>

<div class="card">
<h3>Asfaltlama</h3>
<p>Həyət, parking və sənaye sahələrinin asfalt örtüyü.</p>
</div>

<div class="card">
<h3>Təmir və Bərpa</h3>
<p>Köhnə asfaltın sökülməsi və yenilənməsi.</p>
</div>
</section>

<footer>
<p>© 2026 ASFALT AZƏRBAYCAN | Bütün hüquqlar qorunur</p>
</footer>

<div class="whatsapp">
<a href="https://wa.me/994702552530" target="_blank">
<i class="fab fa-whatsapp"></i>
</a>
</div>

</body>
</html>        </footer>
    </div>

</body>
</html>>
