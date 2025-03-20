<!DOCTYPE html>
<html>
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <link rel="stylesheet" href="styles.css">
    <title>Planetarium Fritzlar</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #000;
            color: #fff;
        }
        header {
            background-color: #111;
            text-align: center;
            padding: 20px;
        }
        nav {
            display: flex;
            flex-direction: column;
            background-color: #111;
            padding: 10px;
        }
        nav a {
            color: white;
            text-decoration: none;
            padding: 10px;
        }
        nav a:last-child {
            border-bottom: none;
        }
        .container {
            padding: 20px;
        }
        section {
            margin-bottom: 30px;
        }
        .highlight {
            font-size: 1.2em;
            font-weight: bold;
            color: #8dc8f2;
        }
        footer {
            background-color: #111;
            text-align: center;
            padding: 10px;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <a href="#start">
            <img src="logo.png" alt="Planetarium Fritzlar Logo" width="150">
        </a>
        <h1>&#127758; Planetarium Fritzlar</h1> 
        <br>
        <p> Wir entführen Sie ins Weltall</p>
    </header>

    <nav>
        <a href="#werwirsind">Wer wir sind</a>
        <a href="#programm">Programm</a>
        <a href="#besuch">Ihr Besuch</a>
    </nav>

    <div class="container">
        <section id="werwirsind">
            <h2>Wer wir sind</h2>
            <p class="highlight">6-Meter-Kuppel | 360-Grad-Fulldome-Technik | Neue Location</p>
            <p>Die Sternfreunde Fritzlar sind in die Gießener Straße 77 umgezogen. Besuchen Sie unser hochmodernes Planetarium mit neuester Technik.</p>
            <img src="images/Bild1.jpg" alt="Website-Logo" width="150">
        </section>

        <section>
            <h3>Technische Ausstattung</h3>
            <p>Das Planetarium verfügt über ein computergesteuertes Projektionssystem, das Sterne in erstaunlicher Schärfe zeigt. 30 Plätze stehen unter unserer sechs Meter großen Kuppel zur Verfügung.</p>
            <img src="images/Bild2.jpg" alt="Website-Logo" width="150">

        </section>

        <section id="programm">
            <h2>Programm</h2>
            <h3>&#127756; Expedition in die Milchstraße</h3>
            <p>Häufig ist das leuchtend helle Band der Milchstraße sogar mit dem bloßen Auge zu erkennen: Was wir da sehen, ist unsere eigene Galaxie. <br> In diesem Vortrag zoomen wir so nah heran, dass sich Milliarden Einzelsterne zeigen, aus der die Milchstraße besteht.<br><br>Samstags, 15 Uhr</p>

            <h3>&#129513; Schwarze Löcher</h3>
            <p>Was einem Schwarzen Loch zu nahe kommt, verschwindet für immer. Sogar Licht! <br>In diesem Vortrag wagen wir uns dennoch ganz nah an die größten Geheimnisse des Weltalls heran.<br><br>Sonntags, 15 Uhr</p>

            <h3>&#128761; Auf der Suche nach Leben</h3>
            <p>Sind wir allein? Generationen von Wissenschaftlern stellten sich bereits diese Frage. <br>In diesem Vortrag besuchen wir nicht nur den Mars, auf dem bereits Wasser entdeckt wurde, sondern auch Meteoriten, die als Transportmittel für biochemische Moleküle dienen können.
                <br><br>Termine nach Vereinbarung</p>
                <img src="images/Bild_03.jpg" alt="Website-Logo" width="150">

        </section>

        <section id="besuch">
            <h2>Ihr Besuch</h2>
            <p class="highlight">Adresse:</p>
            <p>Planetarium Fritzlar<br>Gießener Straße 77, 34560 Fritzlar</p>
            <p>Tel.: 05622 9118896660<br>E-Mail: info@planetarium-fritzlar.de</p>

            <p class="highlight">Öffnungszeiten:</p>
            <p>Mittwoch–Freitag: 12–17 Uhr<br>Samstag–Sonntag: 12–20 Uhr</p>

            <p class="highlight">Eintritt:</p>
            <p>Erwachsene: 6€ | Ermäßigt: 4€ | Kinder bis 18: 2€</p>
        </section>
    </div>

    <footer id="kontakt">
        <h2>Kontakt</h2>
        <p>☎️ 05622 9118896660</p>
        <p>✉️ info@planetarium-fritzlar.de</p>
        <p><a href="#">Impressum</a> | <a href="#">Datenschutz</a></p>
    </footer>

</body>
</html>

body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background: radial-gradient(circle, #02010a 10%, #000000 90%);
    color: #000;
}

/* Header */
header {
    background: linear-gradient(to bottom, #111 0%, #111 100%);
    display: flex;
    flex-direction: column; /* Stellt sicher, dass Logo über der Überschrift ist */
    align-items: center;
    justify-content: center;
    text-align: center;
    padding: 20px;
}

header a {
    display: block; /* Stellt sicher, dass das Logo korrekt angezeigt wird */
}

header img {
    width: 150px; /* Logo-Größe anpassen */
    height: auto;
    margin-bottom: 10px; /* Abstand zwischen Logo und Überschrift */
}

header h1 {
    margin: 0;
    font-size: 1.8em;
    color: #fff;
    text-shadow: 0px 0px 10px rgb(200, 233, 243);
}

header p {
    font-size: 1.2em;
    color: #e0e0e0;
}

/* Navigation */
nav {
    display: flex;
    flex-direction: column;
    align-items: center;
    background-color: rgba(255, 255, 255, 0.9);
    padding: 10px;
}

nav a {
    color: #000;
    text-decoration: none;
    padding: 12px;
    border-bottom: 1px solid #555;
    text-align: center;
    font-size: 1.1em;
}

nav a:last-child {
    border-bottom: none;
}

nav a:hover {
    color:#8dc8f2;
}

/* Inhalt */
.container {
    padding: 20px;
}

section {
    margin-bottom: 30px;
    background-color: rgba(20, 20, 20, 0.85);
    padding: 15px;
    border-radius: 10px;
}

h2 {
    font-size: 1.6em;
    color: #8dc8f2;
    text-shadow: 0px 0px 10px rgb(0, 200, 255);
}

h3 {
    font-size: 1.3em;
    color: #ddd;
}

.highlight {
    font-size: 1.2em;
    font-weight: bold;
    color: #8dc8f2;
}

/* Footer */
footer {
    background: linear-gradient(to top, #111 0%, #000 100%);
    text-align: center;
    padding: 15px;
    margin-top: 20px;
}

footer a {
    color: #a9d2f0 !important;
    text-decoration: none;
    font-weight: bold;
}

footer a:hover {
    text-decoration: underline;
}

header {
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column; /* Falls mobil */
}


