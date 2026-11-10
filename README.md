## Hi there 👋

<!--
**terraexotic/TERRAEXOTIC** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

<!DOCTYPE html>
<html lang="pl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>TERRAEXOTIC – Discover the Exotic World</title>

<meta name="description" content="TERRAEXOTIC – hodowla karaczanów argentyńskich Blaptica dubia. Sprawdź ofertę, cennik i skontaktuj się z nami.">

<meta name="theme-color" content="#101610">

<style>
:root {
  --bg: #101610;
  --dark: #0b100c;
  --panel: #1c291f;
  --panel-light: #202d22;
  --gold: #d5ad62;
  --text: #f1f3ed;
  --muted: #bdc8bc;
  --border: #344536;
}

* {
  box-sizing: border-box;
}

html {
  scroll-behavior: smooth;
  scroll-padding-top: 90px;
}

body {
  margin: 0;
  background: var(--bg);
  color: var(--text);
  font-family: Arial, sans-serif;
  line-height: 1.7;
}

a {
  color: inherit;
}

header {
  position: sticky;
  top: 0;
  z-index: 100;
  background: rgba(21, 30, 23, 0.97);
  border-bottom: 1px solid var(--border);
}

nav {
  max-width: 1100px;
  margin: auto;
  padding: 17px 20px;
  display: flex;
  justify-content: space-between;
  align-items: center;
  gap: 15px;
}

.logo {
  font-size: 25px;
  font-weight: bold;
  letter-spacing: 3px;
  white-space: nowrap;
}

.logo span,
.gold {
  color: var(--gold);
}

nav .links {
  display: flex;
  flex-wrap: wrap;
  gap: 25px;
}

nav a {
  color: #ddd;
  text-decoration: none;
  font-size: 15px;
  transition: color .2s;
}

nav a:hover {
  color: var(--gold);
}

.hero {
  min-height: 520px;
  padding: 110px 20px;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
  background:
    radial-gradient(ellipse at center, #29452e 0%, #17251a 48%, #101610 100%);
}

.hero h1 {
  font-size: clamp(40px, 8vw, 72px);
  letter-spacing: 3px;
  margin: 0;
  line-height: 1.2;
}

.hero .tagline {
  color: var(--gold);
  letter-spacing: 4px;
  font-weight: bold;
  font-size: 14px;
}

.hero p {
  max-width: 650px;
  color: #c4cec3;
  font-size: 18px;
}

.btn {
  display: inline-block;
  background: var(--gold);
  color: #171a12;
  padding: 13px 27px;
  border-radius: 5px;
  text-decoration: none;
  font-weight: bold;
  margin-top: 15px;
  transition: .2s;
}

.btn:hover {
  background: #e8c780;
  transform: translateY(-2px);
}

section {
  padding: 75px 20px;
}

.container {
  max-width: 1100px;
  margin: auto;
}

h2 {
  font-size: clamp(28px, 5vw, 36px);
  margin: 0 0 10px;
}

.subtitle {
  color: var(--muted);
}

.cards {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 22px;
  margin-top: 35px;
}

.card {
  background: var(--panel);
  border: 1px solid var(--border);
  border-radius: 12px;
  padding: 30px 20px;
  text-align: center;
  transition: transform .2s, border-color .2s;
}

.card:hover {
  transform: translateY(-5px);
  border-color: var(--gold);
}

.card h3 {
  font-size: 23px;
  margin: 0;
}

.card p {
  color: var(--muted);
}

.price {
  color: var(--gold);
  font-size: 40px;
  font-weight: bold;
  margin: 10px 0;
}

.about {
  background: #151e17;
}

.about-content {
  max-width: 900px;
}

.about h3 {
  font-size: 22px;
  margin-top: 30px;
}

.about p {
  color: #c4cec3;
}

.features {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 18px;
  margin-top: 35px;
}

.feature {
  padding: 22px;
  background: var(--panel-light);
  border-radius: 9px;
  border: 1px solid var(--border);
  color: var(--muted);
}

.feature strong {
  color: var(--gold);
  display: block;
  margin-bottom: 8px;
}

.contact {
  background: var(--panel);
  border: 1px solid var(--border);
  padding: 30px;
  border-radius: 12px;
  max-width: 650px;
  margin-top: 25px;
}

.contact p {
  color: var(--muted);
}

.contact strong {
  color: var(--gold);
}

.contact a {
  color: var(--text);
  text-decoration: none;
}

.contact a:hover {
  color: var(--gold);
}

footer {
  background: var(--dark);
  padding: 30px 20px;
  text-align: center;
  color: #9da99d;
  border-top: 1px solid var(--border);
}

footer .logo {
  color: var(--text);
}

footer p {
  margin: 7px 0;
  font-size: 14px;
}

:focus-visible {
  outline: 2px solid var(--gold);
  outline-offset: 4px;
}

@media (max-width: 700px) {
  nav {
    flex-direction: column;
    padding: 14px;
  }

  nav .links {
    justify-content: center;
    gap: 20px;
  }

  .hero {
    min-height: 430px;
    padding: 75px 18px;
  }

  .hero p {
    font-size: 16px;
  }

  .cards,
  .features {
    grid-template-columns: 1fr;
  }

  section {
    padding: 55px 18px;
  }

  .contact {
    padding: 22px;
  }
}

@media (prefers-reduced-motion: reduce) {
  html {
    scroll-behavior: auto;
  }

  *,
  *::before,
  *::after {
    transition-duration: 0.01ms !important;
    animation-duration: 0.01ms !important;
  }
}
</style>
</head>

<body>

<header>
<nav aria-label="Menu główne">

  <a href="#" class="logo" aria-label="TERRAEXOTIC – strona główna">
    TERRA<span>EXOTIC</span>
  </a>

  <div class="links">
    <a href="#oferta">Oferta</a>
    <a href="#hodowla">Hodowla</a>
    <a href="#kontakt">Kontakt</a>
  </div>

</nav>
</header>

<main>

<section class="hero">
  <h1>TERRA<span class="gold">EXOTIC</span></h1>

  <p class="tagline">DISCOVER THE EXOTIC WORLD</p>

  <p>
    Egzotyczna pasja, staranna hodowla
    i wartościowa karmówka.
    Poznaj naszą ofertę!
  </p>

  <a class="btn" href="#oferta">ZOBACZ OFERTĘ</a>
</section>

<section id="oferta">
<div class="container">

  <h2>Nasza oferta</h2>

  <p class="subtitle">
    Karaczan argentyński – Blaptica dubia
  </p>

  <div class="cards">

    <article class="card">
      <h3>Wylęg</h3>
      <p>Najmniejsze osobniki</p>
      <div class="price">15 zł</div>
      <p>za 100 sztuk</p>
    </article>

    <article class="card">
      <h3>1–2 cm</h3>
      <p>Młode osobniki</p>
      <div class="price">25 zł</div>
      <p>za 100 sztuk</p>
    </article>

    <article class="card">
      <h3>3–4 cm</h3>
      <p>Większe osobniki</p>
      <div class="price">30 zł</div>
      <p>za 100 sztuk</p>
    </article>

  </div>

  <p class="subtitle">
    Wszystkie podane ceny dotyczą 100 sztuk.
  </p>

</div>
</section>

<section class="about" id="hodowla">
<div class="container about-content">

  <h2>O naszej hodowli</h2>

  <h3>
    Karaczan argentyński (Blaptica dubia) –
    zdrowa i wartościowa karma dla Twoich zwierząt!
  </h3>

  <p>
    Oferuję karaczany argentyńskie hodowane
    w bardzo dobrych, kontrolowanych warunkach.
    Owady mają zapewnioną odpowiednią temperaturę,
    właściwą wilgotność oraz stały dostęp do świeżej,
    odpowiednio dobranej karmy.
  </p>

  <p>
    Hodowla prowadzona jest z dbałością o higienę
    i czystość. Karaczany przebywają z dala od
    zanieczyszczeń, a ich środowisko jest regularnie
    utrzymywane w odpowiednim stanie.
  </p>

  <p>
    Stawiam na jakość, zdrowie i dobrą kondycję
    owadów, aby zapewnić wartościowy pokarm dla
    gadów, płazów, ptaszników i innych zwierząt
    owadożernych.
  </p>

  <p>
    Wybierając moje karaczany, wybierasz staranną
    hodowlę, odpowiednie żywienie i dbałość
    o każdy szczegół!
  </p>

  <div class="features">

    <div class="feature">
      <strong>Odpowiednie warunki</strong>
      Kontrolowana temperatura i wilgotność.
    </div>

    <div class="feature">
      <strong>Dobre żywienie</strong>
      Stały dostęp do odpowiednio dobranej karmy.
    </div>

    <div class="feature">
      <strong>Higiena</strong>
      Dbałość o czystość środowiska hodowli.
    </div>

  </div>

</div>
</section>

<section id="kontakt">
<div class="container">

  <h2>Kontakt</h2>

  <p class="subtitle">
    Jesteś zainteresowany ofertą? Skontaktuj się!
  </p>

  <div class="contact">

    <h3>TERRAEXOTIC</h3>

    <p>
      W sprawie dostępności, zamówień
      i szczegółów oferty zapraszam do kontaktu.
    </p>

    <p>
      <strong>Facebook:</strong>
      Do uzupełnienia
    </p>

    <p>
      <strong>Telefon:</strong>
      Do uzupełnienia
    </p>

    <p>
      <strong>E-mail:</strong>
      Do uzupełnienia
    </p>

  </div>

</div>
</section>

</main>

<footer>

  <div class="logo">TERRA<span>EXOTIC</span></div>

  <p>DISCOVER THE EXOTIC WORLD</p>

  <p>© 2026 TERRAEXOTIC</p>

</footer>

</body>
</html>
