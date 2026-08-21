# Sladd

Et lite verktøy for å slå sammen og sladde PDF-dokumenter – helt lokalt i nettleseren, uten server og uten filopplasting.

## Funksjoner

- **Slå sammen PDF** – last opp flere PDF-filer, endre rekkefølge og slå dem sammen til ett dokument med bevart vektorkvalitet.
- **Sikker sladding** – tegn svarte sladdefelt over sider i et dokument, og eksporter et helt rasterisert (bildebasert) dokument der sladdet innhold og all opprinnelig tekst/metadata er permanent fjernet.

## Hvordan det virker

Alt prosesseres 100% lokalt i nettleseren med [pdf.js](https://mozilla.github.io/pdf.js/) (lesing/rendring) og [pdf-lib](https://pdf-lib.js.org/) (sammenslåing og eksport). Ingen filer sendes over internett – appen er en statisk `index.html` uten backend.

## Kjøre lokalt

Åpne `index.html` i en nettleser, eller kjør en enkel lokal server:

```bash
python3 -m http.server 8080
```

og gå til `http://localhost:8080`.

## Deploy

Siden er satt opp med GitHub Pages fra `main`-branchen.
