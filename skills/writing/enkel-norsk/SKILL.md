---
name: enkel-norsk
description: |
  Skriv, omskriv eller kontroller teknisk tekst på norsk bokmål.
  Bruk ferdigheten til norske issue- og PR-titler, beskrivelser, kommentarer,
  commit-meldinger, dokumentasjon, README-filer, feilmeldinger, driftsrutiner,
  versjonsnotater og hendelsesrapporter. Bruk den også ved ønsker om klarspråk, enkel norsk,
  mindre AI-preg eller tekst som er lett å oversette.
  Bevar fakta, usikkerhet, tidspunkt og kravstyrke. Standardmodusen gir
  fleksible skriveråd. Bruk streng modus bare etter uttrykkelig ønske
  om kontrollert fagspråk eller faste språkkrav.
license: MIT
compatibility: claude-code cursor codex gemini-cli opencode
metadata:
  version: "1.1.0"
---

# Enkel norsk

Skriv klar teknisk tekst på norsk bokmål. Tilpass teksten til leseren og oppgaven.

## Hovedregel: bevar meningen

Bevar fakta, usikkerhet, tidspunkt og kravstyrke.
Hvis en språkregel endrer meningen, behold meningen og velg en annen formulering.
Dette gjelder i begge moduser.

- Behold forskjellen mellom krav, anbefalinger, tillatelser og muligheter.
- Behold nødvendige forbehold, som «kan ha påvirket» eller «trolig».
- Bruk verbformen som uttrykker riktig tidspunkt og sammenheng.
- Hent tall, årsaker og andre fakta fra kilden. Ikke fyll inn manglende opplysninger.

## Velg modus

| Modus | Bruk | Setningslengde |
|---|---|---|
| **Pragmatisk** (standard) | Issues, PR-er, kommentarer, commit-meldinger, dokumentasjon og annen teknisk tekst | 20 ord i instrukser og 25 ord i beskrivelser er rettesnorer. |
| **Streng** | Brukeren ber uttrykkelig om kontrollert fagspråk eller faste språkkrav | 20/25 ord er grenser. Meningsbevaring og urørlig innhold går foran grensene. |

I pragmatisk modus kan en lengre setning være tydeligere enn flere korte.
Ord som «bør», «kunne» og «muligens» er tillatt når de uttrykker meningen presist.
Perfektum og andre sammensatte verbformer er også tillatt.

For vanlige skriveoppgaver er denne hovedveiledningen tilstrekkelig.
Les [regelkatalogen](references/regelkatalog.md) hvis du bruker streng modus.
Hvis oppgaven har en dokumentert ordliste, bruk den. Ikke finn på godkjente eller forbudte ord.

## Skriv teksten

1. Skill mellom instrukser til leseren og beskrivelser av systemet.
2. Skriv hovedpoenget først.
3. Bruk aktive verb når det gjør ansvar og handling tydeligere.
4. Del lange setninger når delingen gjør teksten lettere å forstå.
5. Behold nødvendige ord som «at», «som» og «å».
6. Sett en nødvendig betingelse før handlingen i instrukser.
7. Fjern fyllord som ikke tilfører mening.

Beskrivelser trenger ikke å begynne med betingelsen: «Tjenesten stopper når forbindelsen brytes» er en gyldig forklaring.

## Bruk presise begreper

Bruk samme ord for samme betydning.
Behold forskjellige ord når de beskriver forskjellige handlinger.
«Bekreft slettingen» betyr noe annet enn «Kontroller at slettingen er fullført».
Behold fagbegreper som «validere» og «autorisere» når de uttrykker den faktiske handlingen.

## La teknisk innhold stå

Behold kode, kommandoer, flagg, filstier, identifikatorer, produktnavn og siterte feilmeldinger nøyaktig som de er.
Behold tall og enheter.
Bruk etablerte norske fagord der de finnes, og behold engelske fagord uten et etablert norsk motstykke.

## Egenkontroll

Før du leverer, kontroller at:

- teksten bevarer fakta, usikkerhet, tidspunkt og kravstyrke
- lange setninger er forståelige i valgt modus
- ordvalget skiller mellom ulike begreper og handlinger
- betingelser i instrukser står før handlingen
- teknisk innhold og sitater er urørt

Les [sjekklisten](references/sjekkliste.md) før du kontrollerer en tekst.
Vurder søketreff i sammenheng. Et treff er ikke automatisk et regelbrudd.
Skill mellom regelbrudd og valgfrie forbedringer.
Hvis du oppgir regelnumre, les de aktuelle reglene i [regelkatalogen](references/regelkatalog.md) først.

For eksempler til issues, PR-er, kommentarer og andre teksttyper, se [bruksområder](references/bruksomrader.md).
