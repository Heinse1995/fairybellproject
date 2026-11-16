MIJN AFSTREEPKAART — STARTBESTANDEN

Wat zit erin?
- index.html: de app
- manifest.webmanifest: installatie-instellingen voor Android
- sw.js: cachet de basisbestanden van de app
- icon.svg: app-icoon

SNEL TESTEN
1. Pak de ZIP uit op je computer.
2. Open index.html in een browser met internet.
   Let op: sommige browserfuncties werken alleen via localhost of HTTPS.

INSTALLEREN OP ANDROID (GRATIS VIA GITHUB PAGES)
1. Maak gratis een account op https://github.com als je dat nog niet hebt.
2. Maak een nieuw repository, bijvoorbeeld "mijn-afstreepkaart".
3. Upload alle bestanden uit deze map (niet de ZIP zelf).
4. Ga naar Settings > Pages.
5. Kies bij Build and deployment: Deploy from a branch.
6. Kies branch "main" en map "/ (root)", klik Save.
7. Wacht tot GitHub Pages een websiteadres toont.
8. Open dat adres in Chrome op je Android-telefoon.
9. Kies Chrome-menu (⋮) > Toevoegen aan startscherm / App installeren.

GEBRUIK
- Tik op "Locatie toevoegen" en tik daarna op de kaart.
- Geef de plek een naam en eventueel een notitie.
- Groen vinkje = bezocht; rood kruis = nog te bezoeken.
- Maak via "Back-up" af en toe een JSON-back-up.

BELANGRIJK
- De app en jouw locaties worden lokaal op het apparaat bewaard.
- De kaarttegels worden geladen van OpenStreetMap en hebben internet nodig.
- De service worker bewaart alleen de basisbestanden van de app; geen complete kaart van Nederland.
- Locaties synchroniseren niet automatisch tussen apparaten.
- OpenStreetMap-kaartdata is gratis te gebruiken met zichtbare attributie. Gebruik de standaard OSM-tegelserver normaal en respecteer de gebruiksvoorwaarden: https://operations.osmfoundation.org/policies/tiles/
- Dit is een eerste basisversie. Bewaar je back-up op een veilige plek.
