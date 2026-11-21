<!DOCTYPE html>
<html lang="ro">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>KIRU FUNERALE</title>

<style>
*{margin:0;padding:0;box-sizing:border-box;scroll-behavior:smooth}
body{font-family:Arial,sans-serif;background:#101010;color:#eee}
header{background:#080808;padding:22px 7%;display:flex;justify-content:space-between;align-items:center;border-bottom:1px solid #c5a45b}
.logo{font-size:25px;color:#d4af62;font-weight:bold;letter-spacing:3px}
nav a{color:white;text-decoration:none;margin:10px;font-size:14px}
nav a:hover{color:#d4af62}
.hero{min-height:650px;display:flex;align-items:center;justify-content:center;text-align:center;padding:40px 20px;background:linear-gradient(#0009,#000b),url('https://victorysculptures.com/cdn/shop/files/marble-angel-tombstone-cemetery-remembrance-sculpture-VSM-131.webp?v=1779680449&width=1024') center/cover}
.hero h1{font-size:clamp(38px,7vw,65px);color:#e0c17b;letter-spacing:5px}
.hero p{font-size:19px;margin:20px 0;color:#fff}
.btn{display:inline-block;background:#c5a45b;color:#111;text-decoration:none;padding:14px 27px;margin:10px;font-weight:bold;border-radius:3px}
.btn:hover{background:#ebd18f}
section{padding:80px 8%;text-align:center}
h2{font-size:34px;color:#d4af62;margin-bottom:20px}
.subtitle{color:#bbb;max-width:750px;margin:0 auto 35px;line-height:1.8}
.gallery{display:grid;grid-template-columns:repeat(auto-fit,minmax(250px,1fr));gap:25px}
.item{background:#1c1c1c;border:1px solid #55452b;border-radius:5px;overflow:hidden}
.item img{width:100%;height:260px;object-fit:cover}
.item h3{color:#d4af62;padding:15px}
.item p{color:#bbb;padding:0 18px 20px}
#despre{background:#191919}
#contact{background:#080808}
.contact-box{max-width:600px;margin:30px auto;background:#1c1c1c;border:1px solid #c5a45b;padding:35px}
.contact-box p{margin:15px;color:#ddd}
.phone{font-size:24px;color:#e0c17b;font-weight:bold}
footer{background:#050505;text-align:center;padding:25px;color:#999;border-top:1px solid #80683d}
@media(max-width:650px){
header{flex-direction:column;gap:15px}
nav{display:flex;flex-wrap:wrap;justify-content:center}
.hero{min-height:500px}
}
</style>
</head>

<body>

<header>
<div class="logo">KIRU FUNERALE</div>
<nav>
<a href="#acasa">Acasă</a>
<a href="#produse">Produse</a>
<a href="#despre">Despre noi</a>
<a href="#contact">Contact</a>
</nav>
</header>

<div class="hero" id="acasa">
<div>
<h1>KIRU FUNERALE</h1>
<p>Respect. Demnitate. Amintire eternă.</p>
<a href="#produse" class="btn">DESCOPERĂ PRODUSELE</a>
<a href="#contact" class="btn">CONTACT</a>
</div>
</div>

<section id="produse">
<h2>Produsele noastre</h2>
<p class="subtitle">
Produse comemorative realizate pentru a păstra vie amintirea celor dragi.
</p>

<div class="gallery">

<div class="item">
<img src="https://www.cnstatue.com/wp-content/uploads/2025/02/white-marble-cemetery-angel-statue.jpg" alt="Înger din marmură">
<h3>Statui cu îngeri</h3>
<p>Modele comemorative cu îngeri din marmură.</p>
</div>

<div class="item">
<img src="https://finestsculpture.com/cdn/shop/files/FINEST-FM-201-white-marble-praying-angel-pedestal-memorial-garden.jpg?v=1781457346&width=2000" alt="Înger în rugăciune">
<h3>Îngeri în rugăciune</h3>
<p>Statui elegante pentru monumente comemorative.</p>
</div>

<div class="item">
<img src="https://victorysculptures.com/cdn/shop/files/marble-angel-tombstone-cemetery-remembrance-sculpture-VSM-131.webp?v=1779680449&width=1024" alt="Monument cu înger">
<h3>Monumente funerare</h3>
<p>Modele de monumente pentru comemorarea celor dragi.</p>
</div>

</div>
</section>

<section id="despre">
<h2>Despre KIRU</h2>
<p class="subtitle">
KIRU FUNERALE își propune să ofere produse și servicii
cu respect, seriozitate și atenție față de fiecare familie.
Ne dorim să oferim sprijin și informații într-un mod
respectuos și profesionist.
</p>
</section>

<section id="contact">
<h2>Contactează-ne</h2>
<p class="subtitle">
Pentru informații despre produse și servicii, ne poți contacta telefonic.
</p>

<div class="contact-box">
<p> KIRU FUNERALE</p>
<p class="phone">0768445419</p>
<a class="btn" href="tel:0768445419">SUNĂ ACUM</a>
</div>
</section>

<footer>
© 2026 KIRU FUNERALE | Toate drepturile rezervate.
</footer>

</body>
</html>
