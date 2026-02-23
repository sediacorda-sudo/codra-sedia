# codra-sedia
<!DOCTYPE html>
<html lang="bs">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Corda Sedia | Namještaj Tuzla</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background: #f2f2f2;
            color: #333;
        }

        header {
            background: #222;
            color: white;
            padding: 20px;
            text-align: center;
        }

        nav {
            background: #333;
            text-align: center;
            padding: 10px;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
        }

        nav a:hover {
            text-decoration: underline;
        }

        .hero {
            background: url('https://images.pexels.com/photos/1571460/pexels-photo-1571460.jpeg') center/cover no-repeat;
            height: 60vh;
            display: flex;
            justify-content: center;
            align-items: center;
            color: white;
            flex-direction: column;
            text-shadow: 0 0 10px black;
        }

        .hero h1 {
            font-size: 50px;
            margin: 0;
        }

        .container {
            max-width: 1100px;
            margin: 40px auto;
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 20px rgba(0,0,0,0.1);
        }

        .section-title {
            text-align: center;
            font-size: 30px;
            margin-bottom: 20px;
        }

        .products {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
            gap: 20px;
        }

        .product {
            background: #fafafa;
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 0 15px rgba(0,0,0,0.1);
        }

        .product img {
            width: 100%;
            height: 200px;
            object-fit: cover;
        }

        .product .info {
            padding: 15px;
        }

        .contact-form input,
        .contact-form textarea {
            width: 100%;
            padding: 12px;
            margin: 10px 0;
            border-radius: 6px;
            border: 1px solid #ccc;
        }

        .contact-form button {
            padding: 12px 20px;
            background: #333;
            color: white;
            border: none;
            border-radius: 6px;
            cursor: pointer;
            font-size: 16px;
        }

        footer {
            background: #222;
            color: white;
            padding: 20px;
            text-align: center;
            margin-top: 40px;
        }
    </style>
</head>
<body>

<header>
    <h1>Corda Sedia</h1>
    <p>Prodaja kvalitetnog i modernog namještaja – Tuzla</p>
</header>

<nav>
    <a href="#pocetna">Početna</a>
    <a href="#proizvodi">Proizvodi</a>
    <a href="#onama">O nama</a>
    <a href="#kontakt">Kontakt</a>
</nav>

<!-- HERO -->
<div class="hero" id="pocetna">
    <h1>Dobrodošli u Corda Sedia</h1>
    <p>Namještaj koji traje.</p>
</div>

<!-- O NAMA -->
<div class="container" id="onama">
    <h2 class="section-title">O nama</h2>
    <p>
        Corda Sedia je porodična firma iz Tuzle koja se bavi izradom i prodajom namještaja.
        U ponudi imamo stolice, stolove, komode, garniture i namještaj po mjeri.
    </p>
    <p>
        Svi proizvodi kreirani su od visokokvalitetnih materijala, uz pažnju na detalje i moderan dizajn.
    </p>
    <p>
        Trenutno poslujemo na adresi: <strong>Nasumična Ulica bb, Tuzla</strong><br>
        Radno vrijeme: <strong>09:00 – 17:00</strong>
    </p>
</div>

<!-- PROIZVODI -->
<div class="container" id="proizvodi">
    <h2 class="section-title">Naši proizvodi</h2>

    <div class="products">

        <div class="product">
            <img src="https://images.pexels.com/photos/1866149/pexels-photo-1866149.jpeg" alt="">
            <div class="info">
                <h3>Moderna stolica</h3>
                <p>Cijena: 120 KM</p>
                <p>Kratki opis: Udobna, moderna i kvalitetna stolica za svaki dom.</p>
            </div>
        </div>

        <div class="product">
            <img src="https://images.pexels.com/photos/462235/pexels-photo-462235.jpeg" alt="">
            <div class="info">
                <h3>Trpezarijski sto</h3>
                <p>Cijena: 350 KM</p>
                <p>Kratki opis: Čvrst drveni sto idealan za trpezarije.</p>
            </div>
        </div>

        <div class="product">
            <img src="https://images.pexels.com/photos/245208/pexels-photo-245208.jpeg" alt="">
            <div class="info">
                <h3>Garnitura L-shape</h3>
                <p>Cijena: 950 KM</p>
                <p>Kratki opis: Prostrana garnitura, dostupna u više boja.</p>
            </div>
        </div>

        <div class="product">
            <img src="https://images.pexels.com/photos/276528/pexels-photo-276528.jpeg" alt="">
            <div class="info">
                <h3>Klubski sto</h3>
                <p>Cijena: 90 KM</p>
                <p>Kratki opis: Minimalistički dizajn za dnevni boravak.</p>
            </div>
        </div>

    </div>
</div>

<!-- KONTAKT -->
<div class="container" id="kontakt">
    <h2 class="section-title">Kontakt</h2>

    <p><strong>Telefon:</strong> +387 61 000 000</p>
    <p><strong>Email:</strong> corda.sedia@example.com</p>
    <p><strong>Adresa:</strong> Nasumična Ulica bb, Tuzla</p>

    <h3>Pošaljite poruku</h3>

    <form class="contact-form">
        <input type="text" placeholder="Vaše ime">
        <input type="email" placeholder="Email">
        <textarea rows="5" placeholder="Vaša poruka"></textarea>
        <button type="button">Pošalji</button>
    </form>

    <h3>Lokacija</h3>
    <div style="width:100%; height:300px; margin-top:20px; background:#ccc; display:flex; justify-content:center; align-items:center; border-radius:10px;">
        <p>Google mapa (placeholder)</p>
    </div>
</div>

<footer>
    © 2025 Corda Sedia • Sva prava zadržana
</footer>

</body>
</html>
