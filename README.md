# Ons Huis · Barbarastraat 66

Webapp voor de aankoop van Barbarastraat 66 in Lent: tijdlijn, stappenplan, documenten voor Heleen en Nicky, kosten en belastingaftrek.

Alles wordt **alleen lokaal** bewaard, in de browser van het apparaat waarop je de app gebruikt. Er gaat niets naar een server.

## Online zetten met GitHub Pages

1. Maak op GitHub een nieuwe repository, bijvoorbeeld `ons-huis`.
2. Upload alle bestanden uit deze map: `index.html`, `manifest.webmanifest`, `sw.js`, `README.md` en de map `icons`. Dat kan via **Add file → Upload files**.
3. Ga naar **Settings → Pages**. Kies bij *Source* voor **Deploy from a branch**, branch `main`, map `/ (root)`, en klik **Save**.
4. Na een minuut staat de app op `https://<jouw-gebruikersnaam>.github.io/ons-huis/`.

Let op: in een openbare repository kan iedereen met de link de code zien, ook het adres, de koopsom en jullie namen. Jullie vinkjes en bedragen blijven wel altijd op je eigen apparaat. Wil je dat niet, maak de repository dan privé. GitHub Pages voor privé-repositories werkt alleen met een betaald GitHub-abonnement.

## Op je beginscherm zetten

- **iPhone/iPad (Safari):** open de link, tik op Delen → **Zet op beginscherm**.
- **Android (Chrome):** open de link, menu ⋮ → **App installeren** of **Toevoegen aan startscherm**.

De app werkt daarna ook zonder internet.

Let op: op iPhone en iPad heeft de app op je beginscherm een eigen opslag, los van Safari. Kies dus één plek waar je hem gebruikt. Wil je overstappen, gebruik dan de back-up.

## Back-up en ander apparaat

Op het tabblad **Overzicht** staat onderaan:

- **Back-up opslaan:** downloadt een `.json`-bestand met alles wat je hebt ingevuld.
- **Back-up terugzetten:** laadt zo'n bestand in, bijvoorbeeld op de telefoon van Heleen.

De app synchroniseert niet tussen apparaten. Werk je allebei in de app, spreek dan af wie bijhoudt en stuur af en toe een back-up door.

## Aanpassen

- Datums uit het contract staan bovenaan het script in `index.html` (`DEFAULT_DATES`). Je kunt ze ook gewoon in de app wijzigen onder Overzicht → Datums.
- Heb je een bestand aangepast? Verhoog dan `VERSION` in `sw.js` (bijv. `ons-huis-v2`). Dan halen telefoons de nieuwe versie op.
