# Renaice
Airbrush artist
Da setter vi opp et grunnleggende HTML/CSS-oppsett for hjemmesiden din. Dette vil inkludere de viktigste seksjonene: Hjem, Om Meg, Galleri, Bestillingsverk, og Kontakt. Du kan bruke denne malen til å begynne med og tilpasse den videre etter behov.

Her er et forslag:

Struktur og kode for hjemmesiden

1. HTML-koden:

<!DOCTYPE html>
<html lang="no">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kunsterens Hjemmeside</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- Header og navigasjon -->
    <header>
        <h1>Kunst av [Ditt Navn]</h1>
        <nav>
            <ul>
                <li><a href="#hjem">Hjem</a></li>
                <li><a href="#om-meg">Om Meg</a></li>
                <li><a href="#galleri">Galleri</a></li>
                <li><a href="#bestillingsverk">Bestillingsverk</a></li>
                <li><a href="#kontakt">Kontakt</a></li>
            </ul>
        </nav>
    </header>

    <!-- Hjem seksjonen -->
    <section id="hjem">
        <h2>Velkommen til min kunstverden</h2>
        <p>Jeg lager portretter, fantasy-motiver og veggmalerier tilpasset ditt ønske. Sammen skaper vi noe unikt.</p>
    </section>

    <!-- Om Meg seksjonen -->
    <section id="om-meg">
        <h2>Om Meg</h2>
        <p>Jeg er en kunstner med lidenskap for airbrush og skreddersydde verk. Her kan vi samarbeide om unike kunstverk som gjenspeiler din visjon.</p>
    </section>

    <!-- Galleri seksjonen -->
    <section id="galleri">
        <h2>Galleri</h2>
        <div class="gallery">
            <img src="bilde1.jpg" alt="Eksempelverk 1">
            <img src="bilde2.jpg" alt="Eksempelverk 2">
            <img src="bilde3.jpg" alt="Eksempelverk 3">
            <!-- Legg til flere bilder etter behov -->
        </div>
    </section>

    <!-- Bestillingsverk seksjonen -->
    <section id="bestillingsverk">
        <h2>Bestillingsverk</h2>
        <p>Jeg tilbyr bestillinger der vi samarbeider om farger og motiv. Ta kontakt for å skape ditt eget verk!</p>
    </section>

    <!-- Kontakt seksjonen -->
    <section id="kontakt">
        <h2>Kontakt</h2>
        <form>
            <label for="navn">Navn:</label>
            <input type="text" id="navn" name="navn" required>

            <label for="email">E-post:</label>
            <input type="email" id="email" name="email" required>

            <label for="melding">Melding:</label>
            <textarea id="melding" name="melding" rows="4" required></textarea>

            <button type="submit">Send</button>
        </form>
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; [Ditt Navn] - Alle rettigheter reservert</p>
        <!-- Legg til sosiale medier-lenker hvis ønskelig -->
    </footer>
</body>
</html>

2. CSS-koden (styles.css):

/* Generelle stiler */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    background-color: #f9f9f9;
    color: #333;
}

header {
    background-color: #333;
    color: #fff;
    padding: 1em 0;
    text-align: center;
}

header h1 {
    margin: 0;
    font-size: 2em;
}

nav ul {
    list-style: none;
    display: flex;
    justify-content: center;
}

nav ul li {
    margin: 0 1em;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
    font-weight: bold;
}

nav ul li a:hover {
    text-decoration: underline;
}

section {
    padding: 2em 1em;
    max-width: 800px;
    margin: auto;
}

h2 {
    font-size: 1.8em;
    color: #333;
    margin-bottom: 0.5em;
}

/* Galleri */
.gallery {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
    gap: 1em;
    margin-top: 1em;
}

.gallery img {
    width: 100%;
    height: auto;
    border-radius: 5px;
}

/* Kontakt-skjema */
form {
    display: flex;
    flex-direction: column;
}

form label {
    margin-top: 1em;
}

form input, form textarea, form button {
    padding: 0.5em;
    margin-top: 0.5em;
    border: 1px solid #ccc;
    border-radius: 5px;
}

form button {
    background-color: #333;
    color: #fff;
    cursor: pointer;
    margin-top: 1em;
}

form button:hover {
    background-color: #555;
}

/* Footer */
footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 1em 0;
    margin-top: 2em;
}

Bruke koden

1. Lag to filer:

Opprett en fil som heter index.html og lim inn HTML-koden der.

Opprett en fil som heter styles.css og lim inn CSS-koden der.



2. Legg til bilder:

I Galleri-seksjonen, er det lagt inn plass for bilder (bilde1.jpg, bilde2.jpg, osv.). Bytt ut disse navnene med faktiske bildefiler og legg dem i samme mappe som HTML-filen, eller spesifiser filbanen hvis de er i en annen mappe.



3. Publisering:

Last opp filene til en webserver, eller bruk en gratis hostingplattform som GitHub Pages for å publisere siden på nettet.




Dette gir deg et godt grunnlag, og du kan tilpasse videre etter behov!


