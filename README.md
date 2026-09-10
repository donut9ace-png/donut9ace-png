<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width,initial-scale=1">
<title>Brejesh S. Com</title>

<style>
@import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700;800;900&display=swap');

* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
}

html {
    scroll-behavior: smooth;
}

body {
    font-family: Inter, Arial, sans-serif;
    background: #07070b;
    color: white;
    overflow-x: hidden;
}

/* Background glow */
body:before {
    content: "";
    position: fixed;
    width: 600px;
    height: 600px;
    background: #6d45ff;
    filter: blur(180px);
    opacity: .16;
    top: -250px;
    left: -150px;
    pointer-events: none;
}

/* Navigation */
nav {
    position: fixed;
    top: 0;
    left: 0;
    right: 0;
    z-index: 10;

    display: flex;
    justify-content: space-between;
    align-items: center;

    padding: 22px 7%;

    background: rgba(7,7,11,.65);
    backdrop-filter: blur(18px);
    border-bottom: 1px solid #ffffff12;
}

.logo {
    font-size: 20px;
    font-weight: 900;
}

.logo b {
    color: #8b6cff;
}

nav a {
    color: #aaaabe;
    text-decoration: none;
    margin-left: 28px;
    font-size: 14px;
    font-weight: 600;
    transition: .2s;
}

nav a:hover {
    color: white;
}

/* Hero */
.hero {
    min-height: 100vh;

    display: flex;
    align-items: center;
    justify-content: center;

    text-align: center;
    padding: 100px 20px 50px;
}

.badge {
    display: inline-block;

    padding: 8px 14px;
    border: 1px solid #ffffff18;
    background: #ffffff08;
    border-radius: 100px;

    color: #aaaabe;
    font-size: 12px;
    margin-bottom: 25px;
}

h1 {
    font-size: clamp(52px, 10vw, 120px);
    line-height: .92;
    letter-spacing: -7px;
    font-weight: 900;
}

.gradient {
    background: linear-gradient(
        90deg,
        #fff,
        #a88dff,
        #6d45ff
    );

    -webkit-background-clip: text;
    background-clip: text;
    color: transparent;
}

.hero p {
    max-width: 650px;
    margin: 30px auto;

    color: #9898a9;
    line-height: 1.7;
    font-size: 17px;
}

/* Buttons */
.buttons {
    display: flex;
    justify-content: center;
    gap: 12px;
    flex-wrap: wrap;
}

.btn {
    padding: 14px 23px;
    border-radius: 12px;

    text-decoration: none;
    font-weight: 700;
    font-size: 14px;

    transition: .25s;
}

.primary {
    background: white;
    color: #08080b;
}

.primary:hover {
    transform: translateY(-3px);
    box-shadow: 0 12px 35px #fff2;
}

.secondary {
    border: 1px solid #ffffff18;
    color: #ddd;
    background: #ffffff08;
}

.secondary:hover {
    background: #ffffff12;
}

/* Sections */
section {
    padding: 110px 8%;
    max-width: 1100px;
    margin: auto;
}

.kicker {
    color: #8f78ff;
    text-transform: uppercase;
    font-size: 12px;
    font-weight: 800;
    letter-spacing: 2px;
    margin-bottom: 12px;
}

h2 {
    font-size: 42px;
    letter-spacing: -2px;
    margin-bottom: 18px;
}

/* Cards */
.cardgrid {
    display: grid;
    grid-template-columns: repeat(3,1fr);
    gap: 16px;
    margin-top: 40px;
}

.card {
    padding: 28px;
    min-height: 190px;

    border: 1px solid #ffffff10;
    border-radius: 22px;

    background: linear-gradient(
        145deg,
        #111117,
        #0b0b10
    );

    transition: .3s;
}

.card:hover {
    transform: translateY(-6px);
    border-color: #8b6cff55;
}

.icon {
    font-size: 30px;
    margin-bottom: 25px;
}

.card h3 {
    margin-bottom: 10px;
}

.card p {
    color: #858596;
    line-height: 1.6;
    font-size: 14px;
}

/* Contact */
.contact {
    border: 1px solid #ffffff10;
    border-radius: 28px;

    background: linear-gradient(
        135deg,
        #12101d,
        #0b0b10
    );

    text-align: center;
    padding: 65px 25px;
}

.contact p {
    color: #9292a2;
    margin: 15px auto 25px;
}

/* Footer */
footer {
    text-align: center;
    padding: 45px 20px;

    border-top: 1px solid #ffffff0d;

    color: #6f6f7d;
    font-size: 12px;
    line-height: 1.8;
}

footer strong {
    color: #aaaabe;
}

/* Mobile */
@media(max-width:700px) {

    nav {
        padding: 18px 5%;
    }

    nav div:last-child a {
        margin-left: 12px;
        font-size: 12px;
    }

    .cardgrid {
        grid-template-columns: 1fr;
    }

    h1 {
        letter-spacing: -4px;
    }

    h2 {
        font-size: 34px;
    }
}
</style>
</head>

<body>

<!-- NAVIGATION -->
<nav>

    <div class="logo">
        BREJESH <b>S.</b> COM
    </div>

    <div>
        <a href="#about">About</a>
        <a href="#stuff">Stuff</a>
        <a href="#contact">Contact</a>
    </div>

</nav>


<!-- HERO -->
<header class="hero">

    <div>

        <div class="badge">
            WELCOME TO THE OFFICIAL WEBSITE
        </div>

        <h1>
            BREJESH<br>
            <span class="gradient">S. COM</span>
        </h1>

        <p>
            A place for greatness, questionable decisions,
            and absolutely unnecessary levels of style.
        </p>

        <div class="buttons">

            <a class="btn primary" href="#about">
                Enter Website →
            </a>

            <a class="btn secondary" href="#contact">
                Contact
            </a>

        </div>

    </div>

</header>


<!-- ABOUT -->
<section id="about">

    <div class="kicker">
        01 — About
    </div>

    <h2>
        Built different.
    </h2>

    <p style="
        color:#858596;
        max-width:650px;
        line-height:1.7;
    ">
        Welcome to Brejesh S. Com — a premium corner
        of the internet dedicated to Brejesh, his adventures,
        projects and whatever comes next.
    </p>


    <!-- CARDS -->
    <div class="cardgrid" id="stuff">

        <div class="card">

            <div class="icon">⚡</div>

            <h3>
                Energy
            </h3>

            <p>
                High levels of confidence.
                Questionable levels of sleep.
            </p>

        </div>


        <div class="card">

            <div class="icon">🚀</div>

            <h3>
                Projects
            </h3>

            <p>
                Cool ideas, experiments and
                things worth showing off.
            </p>

        </div>


        <div class="card">

            <div class="icon">★</div>

            <h3>
                Legend Status
            </h3>

            <p>
                Because apparently a normal
                website wasn't enough.
            </p>

        </div>

    </div>

</section>


<!-- CONTACT -->
<section id="contact">

    <div class="contact">

        <div class="kicker">
            02 — Contact
        </div>

        <h2>
            Say hello.
        </h2>

        <p>
            Got something to say?
            This is where your social links,
            email or Discord can go.
        </p>

        <a
            class="btn primary"
            href="mailto:hello@example.com"
        >
            Send a Message
        </a>

    </div>

</section>


<!-- FOOTER -->
<footer>

    © 2026 Brejesh S. Com
    <br>

    <strong>
        Built by The father of Brejesh
        "The great Sreehari" himself.
    </strong>

</footer>

</body>
</html>

