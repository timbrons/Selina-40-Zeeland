# Dagje Zeeland — Selina 40 jaar

Een mobielvriendelijk, printbaar programma voor het dagje Zeeland op **zaterdag 29 augustus 2026**, te hosten via GitHub Pages.

## Bestanden

- **index.html** — de volledige website (één bestand; de illustratie op de cover is ingesloten als SVG).
- **.nojekyll** — leeg bestandje dat voorkomt dat GitHub Pages de pagina onnodig verwerkt.
- **README.md** — dit bestand.

> De lettertypen laden via Google Fonts, dus de pagina heeft bij het bekijken internet nodig. Verder zijn er geen externe bestanden.

## Online zetten via GitHub Pages

1. Ga in deze repository naar **Settings → Pages**.
2. Kies bij **Source**: *Deploy from a branch*, branch **main** en map **/ (root)**, en klik **Save**.
3. Wacht ~1 minuut. De site staat dan op:
   `https://timbrons.github.io/Selina-40-Zeeland/`

Staat de inhoud nog op een andere branch? Merge die eerst naar `main`, of kies bij **Source** die branch.

## Aanpassen

Alle inhoud staat in `index.html`. De opzet:

- `header.cover` — titelblok met stempel en illustratie.
- `.legend` / `.cadeau` / `.basecamp` — leeswijzer, aanleiding en de dag in het kort.
- `section.day--1 / --2 / --3` — de drie dagdelen (Middelburg, Deltawerken, strand).
  Binnen een dagdeel wisselen `.stop-card` (een halte) en `.leg-body` (het stuk reizen ertussen) elkaar af.
- `section.depart` — de terugreis.
- `section.tips` — praktische tips.

Kleuren staan bovenin de `<style>` in `:root`; elk dagdeel heeft een eigen accentkleur via `--accent`.

## Nog te doen vóór 29 augustus

- Vertrektijd uit Hilversum definitief maken (voorstel in de pagina: 07:15 uur).
- Tickets Deltapark Neeltje Jans online kopen op datum.
- Reserveren: MarktCafé Middelburg (lunch) en Beachclub Lekker (diner, met vermelding 40e verjaardag).
- Vlak vooraf openingstijden, prijzen en de weersverwachting nog even checken.
