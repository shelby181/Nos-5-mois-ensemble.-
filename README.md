<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Nos 5 mois ensemble ❤️</title>

<style>
* {
    box-sizing: border-box;
}

body {
    margin: 0;
    background: #0d0b12;
    color: white;
    font-family: Georgia, serif;
    text-align: center;
    overflow-x: hidden;
}

.container {
    max-width: 480px;
    margin: auto;
    padding: 20px;
}

header {
    color: #d6b46a;
    letter-spacing: 3px;
    padding: 20px;
    font-size: 13px;
}

h1, h2 {
    color: #e6c477;
}

.hero {
    padding: 55px 10px;
    background: linear-gradient(160deg, #171323, #32172c);
    border-radius: 22px;
    margin-top: 15px;
}

.hero h1 {
    font-size: 34px;
}

.hero p {
    color: #ffb6c9;
    line-height: 1.9;
}

.heart {
    color: #ff6b91;
    font-size: 40px;
    animation: beat 1.2s infinite;
}

.section {
    margin-top: 40px;
}

.card {
    background: #17131d;
    border: 1px solid #806536;
    border-radius: 18px;
    padding: 22px;
    margin-top: 20px;
    line-height: 1.9;
}

button {
    background: #d6b46a;
    color: #111;
    border: none;
    padding: 14px 22px;
    border-radius: 30px;
    font-size: 15px;
    font-family: Georgia, serif;
    cursor: pointer;
    margin: 10px;
    transition: 0.3s;
}

button:hover {
    transform: scale(1.05);
    background: #f0d28a;
}

.counter {
    display: flex;
    justify-content: center;
    gap: 10px;
    flex-wrap: wrap;
}

.counter div {
    background: #211724;
    border: 1px solid #806536;
    padding: 15px 12px;
    border-radius: 12px;
    min-width: 75px;
}

.counter strong {
    display: block;
    color: #e6c477;
    font-size: 24px;
}

.counter span {
    color: #ffb6c9;
    font-size: 12px;
}

/* LETTRES */

.envelope {
    background: linear-gradient(145deg, #211724, #151019);
    border: 1px solid #b89555;
    border-radius: 15px;
    margin: 17px 0;
    overflow: hidden;
}

.envelope summary {
    list-style: none;
    padding: 22px 12px;
    cursor: pointer;
    color: #e6c477;
    font-size: 17px;
}

.envelope summary::-webkit-details-marker {
    display: none;
}

.envelope .icon {
    display: block;
    font-size: 30px;
    margin-bottom: 10px;
}

.message {
    padding: 0 18px 20px;
    color: #f5e9ed;
    line-height: 1.9;
    animation: appear 0.8s ease;
}

/* CADEAU */

.gift {
    font-size: 75px;
    cursor: pointer;
    display: inline-block;
    transition: 0.5s;
}

.gift:hover {
    transform: rotate(12deg) scale(1.1);
}

#giftMessage {
    display: none;
    animation: appear 1s ease;
}

/* MUSIQUE */

.music-box {
    background: #211724;
    padding: 20px;
    border-radius: 18px;
    border: 1px solid #806536;
}

#musicPlayer {
    width: 100%;
    margin-top: 15px;
}

/* GALERIE */

.gallery {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 12px;
}

.gallery img {
    width: 100%;
    height: 170px;
    object-fit: cover;
    border-radius: 14px;
    border: 1px solid #b89555;
    cursor: pointer;
    transition: 0.3s;
}

.gallery img:hover {
    transform: scale(1.04);
}

#lightbox {
    display: none;
    position: fixed;
    inset: 0;
    background: #000e;
    z-index: 100;
    align-items: center;
    justify-content: center;
    padding: 20px;
}

#lightbox img {
    max-width: 100%;
    max-height: 80vh;
    border: 2px solid #d6b46a;
    border-radius: 15px;
}

/* MESSAGE FINAL */

.final {
    color: #ff9ab6;
    line-height: 2;
    font-size: 18px;
}

footer {
    margin-top: 45px;
    padding: 25px;
    background: #11111b;
    color: #c6a968;
    font-size: 13px;
    letter-spacing: 2px;
    line-height: 2;
}

/* ETINCELLES */

.sparkle {
    position: fixed;
    pointer-events: none;
    z-index: 999;
    animation: sparkle 1s ease-out forwards;
}

@keyframes sparkle {
    from {
        opacity: 1;
        transform: translateY(0) scale(1);
    }
    to {
        opacity: 0;
        transform: translateY(-80px) scale(0);
    }
}

@keyframes beat {
    50% {
        transform: scale(1.25);
    }
}

@keyframes appear {
    from {
        opacity: 0;
        transform: translateY(20px);
    }
    to {
        opacity: 1;
        transform: translateY(0);
    }
}

.heartFloat {
    position: fixed;
    bottom: -30px;
    pointer-events: none;
    z-index: 50;
    animation: floatUp 4s linear forwards;
}

@keyframes floatUp {
    to {
        transform: translateY(-110vh) rotate(360deg);
        opacity: 0;
    }
}
</style>
</head>

<body>

<header>
NOTRE PETIT UNIVERS ❤️
</header>

<div class="container">

<!-- ACCUEIL -->

<section class="hero">

<div class="heart">♥</div>

<h1>Joyeux 5 mois !</h1>

<p>
Cinq mois d'une belle histoire,
de complicité et de tendresse.
<br>
Aujourd'hui, cette petite surprise
est entièrement pour toi. 🥹
</p>

<button onclick="document.getElementById('counterSection').scrollIntoView({behavior:'smooth'})">
Découvrir notre univers ❤️
</button>

</section>


<!-- COMPTEUR -->

<section class="section" id="counterSection">

<h2>Notre histoire ⏳</h2>

<div class="card">

<p>
Depuis le 10 juillet 2026,
chaque instant écrit une nouvelle page
de notre histoire.
</p>

<div class="counter">

<div>
<strong id="days">0</strong>
<span>Jours</span>
</div>

<div>
<strong id="hours">0</strong>
<span>Heures</span>
</div>

<div>
<strong id="minutes">0</strong>
<span>Minutes</span>
</div>

<div>
<strong id="seconds">0</strong>
<span>Secondes</span>
</div>

</div>

</div>
</section>


<!-- LETTRES -->

<section class="section">

<h2>Quelques mots pour toi 💌</h2>

<p>Chaque enveloppe cache une petite partie de mon cœur.</p>

<details class="envelope">
<summary>
<span class="icon">💌</span>
Une pensée pour toi
</summary>

<div class="message">
Depuis que tu fais partie de ma vie,
j'ai découvert une nouvelle façon
de voir le bonheur.

Ta présence rend mes journées
plus belles et mon cœur plus léger.

Je suis heureux de t'avoir dans ma vie. ❤️
</div>
</details>


<details class="envelope">
<summary>
<span class="icon">🎀</span>
Ce que tu représentes
</summary>

<div class="message">
Tu es une personne précieuse
à mes yeux.

J'aime nos conversations,
nos petits moments et cette complicité
que nous construisons jour après jour.

Je ne veux jamais cesser
de te donner des raisons de sourire. 🥰
</div>
</details>


<details class="envelope">
<summary>
<span class="icon">❤️</span>
Une promesse du cœur
</summary>

<div class="message">
Je ne te promets pas que tout sera
toujours facile.

Mais je veux continuer à apprendre,
à comprendre, à respecter et à construire
avec toi.

Je souhaite que notre histoire
continue de grandir avec amour,
patience et sincérité. 💍
</div>
</details>

</section>


<!-- CADEAU -->

<section class="section">

<h2>Une petite surprise 🎁</h2>

<p>
J'ai quelque chose pour toi...
mais tu dois ouvrir le cadeau !
</p>

<div class="card">

<div class="gift" onclick="openGift()">🎁</div>

<div id="giftMessage">

<h2>Surprise, mon amour ! ❤️</h2>

<p>
Si je pouvais t'offrir une seule chose,
ce serait de te faire ressentir
chaque jour à quel point tu es aimée.

Tu mérites tellement de bonheur. 🥹💕
</p>

</div>

</div>
</section>


<!-- MUSIQUE -->

<section class="section">

<h2>Notre petite mélodie 🎵</h2>

<div class="music-box">

<p>
Une musique pour accompagner
ce petit moment rien qu'à nous. ❤️
</p>

<button onclick="playMusic()">
▶ Écouter notre musique
</button>

<div id="musicPlayer"></div>

</div>
</section>


<!-- GALERIE -->

<section class="section">

<h2>Nos souvenirs 📸</h2>

<p>
Quelques images pour garder
nos plus beaux moments.
</p>

<div class="gallery">

<img src="photo1.jpg" alt="Notre souvenir 1" onclick="showPhoto(this)">
<img src="photo2.jpg" alt="Notre souvenir 2" onclick="showPhoto(this)">
<img src="photo3.jpg" alt="Notre souvenir 3" onclick="showPhoto(this)">
<img src="photo4.jpg" alt="Notre souvenir 4" onclick="showPhoto(this)">

</div>

</section>


<!-- LIGHTBOX -->

<div id="lightbox" onclick="closePhoto()">
<img id="bigPhoto" src="" alt="Photo agrandie">
</div>


<!-- FINAL -->

<section class="section">

<div class="card">

<div class="heart">♥</div>

<h2>À nous deux, mon amour</h2>

<p class="final">
Cinq mois ne sont que le début
d'une histoire que j'espère
voir grandir encore et encore.

Merci pour ces beaux moments.
Merci d'être toi.

Joyeux cinq mois, Manmi. ❤️

<br><br>

Avec tout mon amour,
<br>
Papi ❤️
</p>

</div>

</section>

</div>


<footer>

FAIT AVEC AMOUR ♥
<br>
10 NOVEMBRE 2026
<br>
NOS 5 MOIS ENSEMBLE

</footer>


<script>

// COMPTEUR DEPUIS LE 10 JUILLET 2026

function updateCounter() {

    const start = new Date(2026, 6, 10, 0, 0, 0);
    const now = new Date();

    let difference = Math.max(0, now - start);

    const days = Math.floor(difference / 86400000);
    const hours = Math.floor((difference % 86400000) / 3600000);
    const minutes = Math.floor((difference % 3600000) / 60000);
    const seconds = Math.floor((difference % 60000) / 1000);

    document.getElementById("days").textContent = days;
    document.getElementById("hours").textContent = hours;
    document.getElementById("minutes").textContent = minutes;
    document.getElementById("seconds").textContent = seconds;
}

updateCounter();
setInterval(updateCounter, 1000);


// ETINCELLES AU CLIC

document.addEventListener("click", function(event) {

    for (let i = 0; i < 10; i++) {

        const sparkle = document.createElement("div");

        sparkle.className = "sparkle";
        sparkle.textContent = Math.random() > 0.5 ? "✨" : "♥";

        sparkle.style.left = event.clientX + (Math.random() * 100 - 50) + "px";
        sparkle.style.top = event.clientY + (Math.random() * 100 - 50) + "px";

        document.body.appendChild(sparkle);

        setTimeout(() => sparkle.remove(), 1000);
    }

});


// KÈ AP FLOTE

function floatingHearts() {

    const heart = document.createElement("div");

    heart.className = "heartFloat";
    heart.textContent = Math.random() > 0.5 ? "❤️" : "💕";

    heart.style.left = Math.random() * 100 + "vw";
    heart.style.fontSize = (15 + Math.random() * 20) + "px";

    document.body.appendChild(heart);

    setTimeout(() => heart.remove(), 4000);
}

setInterval(floatingHearts, 1200);


// OUVRI KADO

function openGift() {

    const message = document.getElementById("giftMessage");

    message.style.display = "block";

    for (let i = 0; i < 25; i++) {
        setTimeout(() => {
            const sparkle = document.createElement("div");

            sparkle.className = "sparkle";
            sparkle.textContent = "✨";

            sparkle.style.left = Math.random() * window.innerWidth + "px";
            sparkle.style.top = Math.random() * window.innerHeight + "px";

            document.body.appendChild(sparkle);

            setTimeout(() => sparkle.remove(), 1000);
        }, i * 30);
    }
}


// LAGE MIZIK

function playMusic() {

    const player = document.getElementById("musicPlayer");

    if (player.innerHTML !== "") {
        player.innerHTML = "";
        return;
    }

    player.innerHTML = `
    <iframe
        width="100%"
        height="180"
        src="https://www.youtube.com/embed/W1tzURKYFNs?autoplay=1"
        title="Notre musique"
        frameborder="0"
        allow="autoplay; encrypted-media; picture-in-picture"
        allowfullscreen>
    </iframe>
    `;
}


// GALERI FOTO

function showPhoto(photo) {

    document.getElementById("bigPhoto").src = photo.src;

    document.getElementById("lightbox").style.display = "flex";
}

function closePhoto() {

    document.getElementById("lightbox").style.display = "none";
}

</script>

</body>
</html>
