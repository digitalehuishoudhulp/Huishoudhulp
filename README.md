# My Chilo

Dit is de publicatieversie van My Chilo. Zet de bestanden uit deze map rechtstreeks in de hoofdmap van de GitHub-repository die aan Netlify gekoppeld wordt.

## Aanwezig
- Dagelijkse en weektaken met punten en voortgang
- Eigen taken toevoegen en verwijderen
- 5-minutentimer met pauze en reset
- Voor- en nafoto’s per opruimproject
- Spotify-link voor opruimmuziek (muziek start niet automatisch)
- App delen via de deelknop
- Gegevens lokaal opslaan in de browser
- PWA-manifest, beginschermicoon en service worker voor offline openen na de eerste online laadbeurt

## Belangrijke grenzen
- Taken, punten en foto’s worden lokaal op het apparaat/de browser opgeslagen; er is nog geen account- of cloudsynchronisatie tussen apparaten.
- Er zijn nog geen geplande pushmeldingen. De timer kan een trilling proberen te geven wanneer de browser dit ondersteunt.
- De Spotify-link opent Spotify; de app speelt geen muziek zelfstandig af.

## Netlify
Gebruik de repository-root als publicatiemap. Er is geen build command nodig; dit is een statische HTML-app.
