# My Chilo – nieuwe uploadversie (31-10-2026)

Dit ZIP-bestand bevat de volledige statische app. De bestanden staan direct in de hoofdmap van de ZIP.

## Uploaden naar GitHub / Netlify
1. Pak dit ZIP-bestand uit.
2. Upload de bestanden uit deze map rechtstreeks naar de hoofdmap (root) van je GitHub-repository.
3. Controleer dat `index.html`, `manifest.webmanifest`, `service-worker.js` en de drie icon-bestanden direct in de repository-root staan.
4. Netlify kan de repository daarna als statische site publiceren. Build command: leeg. Publish directory: `.` (repository-root).

## Inbegrepen functies
- Dagelijkse en weektaken met punten en voortgang
- Eigen taken toevoegen en verwijderen
- 5-minutentimer met pauze en reset
- Voor- en nafoto's per opruimproject
- Spotify-link voor opruimmuziek
- App delen via de deelknop
- Lokale opslag in de browser
- PWA-manifest, beginschermiconen en service worker

## Let op
Taken, punten en foto's worden lokaal op het apparaat/de browser opgeslagen. Er is nog geen account- of cloudsynchronisatie tussen apparaten. Spotify opent via een link; muziek start niet automatisch.
