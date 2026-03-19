# Boorpunt V4 — Ground Research BV

Interactieve kaartapplicatie voor het visualiseren en beheren van bronsystemen (bodemenergie). Gebouwd als standalone HTML — geen server nodig.

## Features

- **Kaartweergave** — Satelliet, hybride, OSM + OpenStreetMap met Leaflet
- **Boorpunten beheren** — Handmatig toevoegen, bewerken en verwijderen van boorpunten op de kaart
- **CSV/Excel import** — Sleep CSV of XLSX bestanden met boorpuntdata (fuzzy kolomherkenning voor diepte, diameter, coördinaten)
- **KLIC import** — Kadaster KLIC ZIP-bestanden importeren (IMKL v2), met kleurcodering per netwerk:
  - 🔴 Elektra | 🟡 Gas | 🔵 Water | 🟢 Telecom | 🟤 Riool | 🟠 Warmte
- **Adres zoeken** — Zoek op adres en centreer de kaart
- **Meetfunctie** — Afstanden meten op de kaart met stippellijnen en labels
- **Dynamische legenda** — Kleuren passen zich aan op werkelijke dieptes in de data
- **PDF export** — Genereer PDF inclusief kaart, boorpunttabel en KLIC lagen
- **RD-coördinaten** — Werkt met Rijksdriehoekscoördinaten (EPSG:28992)

## Gebruik

Open `boorpunt-v4.html` in een browser. Geen installatie of server nodig.

### Live demo

🔗 [https://pimgroot.github.io/boorpunt/](https://pimgroot.github.io/boorpunt/)

### Lokaal

```bash
# Clone en open
git clone https://github.com/Pimgroot/boorpunt.git
open boorpunt-v4.html
```

## Screenshots

_Satellietweergave met boorpunten en KLIC lagen_

## Tech

- **Leaflet.js** — Kaartweergave
- **jsPDF** — PDF generatie
- **SheetJS (xlsx)** — Excel/CSV parsing
- **JSZip** — KLIC ZIP parsing
- Geen backend, geen build stap — puur HTML/CSS/JS

## Licentie

© Ground Research BV — Vrijheidweg 45, Wormerveer
