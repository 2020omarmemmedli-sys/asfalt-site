<!DOCTYPE html>
<html lang="az">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Lezzet Restoranı</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family: 'Poppins', sans-serif;
}

body{
    background:#111;
    color:white;
    overflow-x:hidden;
}

/* HEADER */
header{
    height:100vh;
    background:linear-gradient(rgba(0,0,0,0.6),rgba(0,0,0,0.6)),
    url('https://images.unsplash.com/photo-1555396273-367ea4eb4db5') center/cover no-repeat;
    display:flex;
    flex-direction:column;
    justify-content:center;
    align-items:center;
    text-align:center;
}

header h1{
    font-size:60px;
    color:#f4b400;
    animation:fadeDown 1.5s ease;
}

header p{
    font-size:20px;
    width:60%;
    margin-top:20px;
    animation:fadeUp 2s ease;
}

@keyframes fadeDown{
    from{opacity:0; transform:translateY(-50px);}
    to{opacity:1; transform:translateY(0);}
}

@keyframes fadeUp{
    from{opacity:0; transform:translateY(50px);}
    to{opacity:1; transform:translateY(0);}
}

/* HAQQIMIZDA */
.about{
    padding:80px 10%;
    display:flex;
    gap:50px;
    align-items:center;
    background:#1a1a1a;
}

.about img{
    width:50%;
    border-radius:20px;
    box-shadow:0 0 30px rgba(244,180,0,0.5);
}

.about-text{
    width:50%;
}

.about-text h2{
    color:#f4b400;
    font-size:40px;
    margin-bottom:20px;
}

.about-text p{
    line-height:1.8;
    font-size:18px;
}

/* KATALOQ */
.menu{
    padding:80px 10%;
    text-align:center;
}

.menu h2{
    font-size:40px;
    color:#f4b400;
    margin-bottom:50px;
}

.cards{
    display:flex;
    justify-content:center;
    gap:30px;
    flex-wrap:wrap;
}

.card{
    background:#222;
    padding:20px;
    border-radius:15px;
    width:280px;
    transition:0.4s;
}

.card:hover{
    transform:scale(1.05);
    box-shadow:0 0 20px #f4b400;
}

.card img{
    width:100%;
    border-radius:15px;
}

.card h3{
    margin-top:15px;
    color:#f4b400;
}

/* FOOTER */
footer{
    padding:30px;
    text-align:center;
    background:#000;
}

/* WHATSAPP BUTTON */
.whatsapp{
    position:fixed;
    bottom:20px;
    right:20px;
    background:#25D366;
    color:white;
    padding:15px 20px;
    border-radius:50px;
    text-decoration:none;
    font-weight:bold;
    box-shadow:0 0 15px rgba(0,0,0,0.5);
    transition:0.3s;
}

.whatsapp:hover{
    transform:scale(1.1);
}
</style>
</head>

<body>

<header>
    <h1>Lezzet Restoranı</h1>
    <p>Dadın zirvəsini bizimlə yaşa! Milli və Avropa mətbəxinin ən seçilmiş təamları bir arada.</p>
</header>

<section class="about">
    <img src="https://images.unsplash.com/photo-1541542684-4a9b0f6c2f7f">
    <div class="about-text">
        <h2>Haqqımızda</h2>
        <p>
        Lezzet Restoranı olaraq illərin təcrübəsi ilə qonaqlarımıza yüksək keyfiyyətli xidmət təqdim edirik.
        Bizim məqsədimiz sadəcə yemək təqdim etmək deyil, unudulmaz bir atmosfer yaratmaqdır.
        Ailəvi məclislər, romantik axşamlar və dost görüşləri üçün ideal məkandır.
        </p>
    </div>
</section>

<section class="menu">
    <h2>Populyar Yeməklər</h2>
    <div class="cards">
        <div class="card">
            <img src="https://images.unsplash.com/photo-1600891964599-f61ba0e24092">
            <h3>Steyk</h3>
            <p>Şef xüsusi sous ilə</p>
        </div>
        <div class="card">
            <img src="https://images.unsplash.com/photo-1565299624946-b28f40a0ae38">
            <h3>Pizza</h3>
            <p>Odun sobasında bişirilir</p>
        </div>
        <div class="card">
            <img src="https://images.unsplash.com/photo-1551782450-a2132b4ba21d">
            <h3>Burger</h3>
            <p>100% təbii ət</p>
        </div>
    </div>
</section>

<footer>
    © 2026 Lezzet Restoranı | Bütün hüquqlar qorunur
</footer>

<a class="whatsapp" href="https://wa.me/994553960085" target="_blank">
    WhatsApp ilə Sifariş
</a>

</body>
</html><!DOCTYPE html>
<html lang="az">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Lezzet Restoranı</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family: 'Poppins', sans-serif;
}

body{
    background:#111;
    color:white;
    overflow-x:hidden;
}

/* HEADER */
header{
    height:100vh;
    background:linear-gradient(rgba(0,0,0,0.6),rgba(0,0,0,0.6)),
    url('https://images.unsplash.com/photo-1555396273-367ea4eb4db5') center/cover no-repeat;
    display:flex;
    flex-direction:column;
    justify-content:center;
    align-items:center;
    text-align:center;
}

header h1{
    font-size:60px;
    color:#f4b400;
    animation:fadeDown 1.5s ease;
}

header p{
    font-size:20px;
    width:60%;
    margin-top:20px;
    animation:fadeUp 2s ease;
}

@keyframes fadeDown{
    from{opacity:0; transform:translateY(-50px);}
    to{opacity:1; transform:translateY(0);}
}

@keyframes fadeUp{
    from{opacity:0; transform:translateY(50px);}
    to{opacity:1; transform:translateY(0);}
}

/* HAQQIMIZDA */
.about{
    padding:80px 10%;
    display:flex;
    gap:50px;
    align-items:center;
    background:#1a1a1a;
}

.about img{
    width:50%;
    border-radius:20px;
    box-shadow:0 0 30px rgba(244,180,0,0.5);
}

.about-text{
    width:50%;
}

.about-text h2{
    color:#f4b400;
    font-size:40px;
    margin-bottom:20px;
}

.about-text p{
    line-height:1.8;
    font-size:18px;
}

/* KATALOQ */
.menu{
    padding:80px 10%;
    text-align:center;
}

.menu h2{
    font-size:40px;
    color:#f4b400;
    margin-bottom:50px;
}

.cards{
    display:flex;
    justify-content:center;
    gap:30px;
    flex-wrap:wrap;
}

.card{
    background:#222;
    padding:20px;
    border-radius:15px;
    width:280px;
    transition:0.4s;
}

.card:hover{
    transform:scale(1.05);
    box-shadow:0 0 20px #f4b400;
}

.card img{
    width:100%;
    border-radius:15px;
}

.card h3{
    margin-top:15px;
    color:#f4b400;
}

/* FOOTER */
footer{
    padding:30px;
    text-align:center;
    background:#000;
}

/* WHATSAPP BUTTON */
.whatsapp{
    position:fixed;
    bottom:20px;
    right:20px;
    background:#25D366;
    color:white;
    padding:15px 20px;
    border-radius:50px;
    text-decoration:none;
    font-weight:bold;
    box-shadow:0 0 15px rgba(0,0,0,0.5);
    transition:0.3s;
}

.whatsapp:hover{
    transform:scale(1.1);
}
</style>
</head>

<body>

<header>
    <h1>Lezzet Restoranı</h1>
    <p>Dadın zirvəsini bizimlə yaşa! Milli və Avropa mətbəxinin ən seçilmiş təamları bir arada.</p>
</header>

<section class="about">
    <img src="https://images.unsplash.com/photo-1541542684-4a9b0f6c2f7f">
    <div class="about-text">
        <h2>Haqqımızda</h2>
        <p>
        Lezzet Restoranı olaraq illərin təcrübəsi ilə qonaqlarımıza yüksək keyfiyyətli xidmət təqdim edirik.
        Bizim məqsədimiz sadəcə yemək təqdim etmək deyil, unudulmaz bir atmosfer yaratmaqdır.
        Ailəvi məclislər, romantik axşamlar və dost görüşləri üçün ideal məkandır.
        </p>
    </div>
</section>

<section class="menu">
    <h2>Populyar Yeməklər</h2>
    <div class="cards">
        <div class="card">
            <img src="https://images.unsplash.com/photo-1600891964599-f61ba0e24092">
            <h3>Steyk</h3>
            <p>Şef xüsusi sous ilə</p>
        </div>
        <div class="card">
            <img src="https://images.unsplash.com/photo-1565299624946-b28f40a0ae38">
            <h3>Pizza</h3>
            <p>Odun sobasında bişirilir</p>
        </div>
        <div class="card">
            <img src="https://images.unsplash.com/photo-1551782450-a2132b4ba21d">
            <h3>Burger</h3>
            <p>100% təbii ət</p>
        </div>
    </div>
</section>

<footer>
    © 2026 Lezzet Restoranı | Bütün hüquqlar qorunur
</footer>

<a class="whatsapp" href="https://wa.me/994553960085" target="_blank">
    WhatsApp ilə Sifariş
</a>

</body>
</html><!DOCTYPE html>
<html lang="az">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Lezzet Restoranı</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family: 'Poppins', sans-serif;
}

body{
    background:#111;
    color:white;
    overflow-x:hidden;
}

/* HEADER */
header{
    height:100vh;
    background:linear-gradient(rgba(0,0,0,0.6),rgba(0,0,0,0.6)),
    url('https://images.unsplash.com/photo-1555396273-367ea4eb4db5') center/cover no-repeat;
    display:flex;
    flex-direction:column;
    justify-content:center;
    align-items:center;
    text-align:center;
}

header h1{
    font-size:60px;
    color:#f4b400;
    animation:fadeDown 1.5s ease;
}

header p{
    font-size:20px;
    width:60%;
    margin-top:20px;
    animation:fadeUp 2s ease;
}

@keyframes fadeDown{
    from{opacity:0; transform:translateY(-50px);}
    to{opacity:1; transform:translateY(0);}
}

@keyframes fadeUp{
    from{opacity:0; transform:translateY(50px);}
    to{opacity:1; transform:translateY(0);}
}

/* HAQQIMIZDA */
.about{
    padding:80px 10%;
    display:flex;
    gap:50px;
    align-items:center;
    background:#1a1a1a;
}

.about img{
    width:50%;
    border-radius:20px;
    box-shadow:0 0 30px rgba(244,180,0,0.5);
}

.about-text{
    width:50%;
}

.about-text h2{
    color:#f4b400;
    font-size:40px;
    margin-bottom:20px;
}

.about-text p{
    line-height:1.8;
    font-size:18px;
}

/* KATALOQ */
.menu{
    padding:80px 10%;
    text-align:center;
}

.menu h2{
    font-size:40px;
    color:#f4b400;
    margin-bottom:50px;
}

.cards{
    display:flex;
    justify-content:center;
    gap:30px;
    flex-wrap:wrap;
}

.card{
    background:#222;
    padding:20px;
    border-radius:15px;
    width:280px;
    transition:0.4s;
}

.card:hover{
    transform:scale(1.05);
    box-shadow:0 0 20px #f4b400;
}

.card img{
    width:100%;
    border-radius:15px;
}

.card h3{
    margin-top:15px;
    color:#f4b400;
}

/* FOOTER */
footer{
    padding:30px;
    text-align:center;
    background:#000;
}

/* WHATSAPP BUTTON */
.whatsapp{
    position:fixed;
    bottom:20px;
    right:20px;
    background:#25D366;
    color:white;
    padding:15px 20px;
    border-radius:50px;
    text-decoration:none;
    font-weight:bold;
    box-shadow:0 0 15px rgba(0,0,0,0.5);
    transition:0.3s;
}

.whatsapp:hover{
    transform:scale(1.1);
}
</style>
</head>

<body>

<header>
    <h1>Lezzet Restoranı</h1>
    <p>Dadın zirvəsini bizimlə yaşa! Milli və Avropa mətbəxinin ən seçilmiş təamları bir arada.</p>
</header>

<section class="about">
    <img src="https://images.unsplash.com/photo-1541542684-4a9b0f6c2f7f">
    <div class="about-text">
        <h2>Haqqımızda</h2>
        <p>
        Lezzet Restoranı olaraq illərin təcrübəsi ilə qonaqlarımıza yüksək keyfiyyətli xidmət təqdim edirik.
        Bizim məqsədimiz sadəcə yemək təqdim etmək deyil, unudulmaz bir atmosfer yaratmaqdır.
        Ailəvi məclislər, romantik axşamlar və dost görüşləri üçün ideal məkandır.
        </p>
    </div>
</section>

<section class="menu">
    <h2>Populyar Yeməklər</h2>
    <div class="cards">
        <div class="card">
            <img src="https://images.unsplash.com/photo-1600891964599-f61ba0e24092">
            <h3>Steyk</h3>
            <p>Şef xüsusi sous ilə</p>
        </div>
        <div class="card">
            <img src="https://images.unsplash.com/photo-1565299624946-b28f40a0ae38">
            <h3>Pizza</h3>
            <p>Odun sobasında bişirilir</p>
        </div>
        <div class="card">
            <img src="https://images.unsplash.com/photo-1551782450-a2132b4ba21d">
            <h3>Burger</h3>
            <p>100% təbii ət</p>
        </div>
    </div>
</section>

<footer>
    © 2026 Lezzet Restoranı | Bütün hüquqlar qorunur
</footer>

<a class="whatsapp" href="https://wa.me/994553960085" target="_blank">
    WhatsApp ilə Sifariş
</a>

</body>
</html>Peşəkar aşpaz komandamız hər yeməyi sevgi və ustalıqla hazırlayır.
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
</html>
