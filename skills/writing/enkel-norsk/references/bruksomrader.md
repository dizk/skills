# Bruksområder

Pragmatisk modus er standard for alle teksttypene nedenfor.
Bruk streng modus bare når brukeren uttrykkelig ber om kontrollert fagspråk eller faste språkkrav.
[Hovedregelen om meningsbevaring](../SKILL.md#hovedregel-bevar-meningen) gjelder i begge moduser.

## Issues, PR-er, kommentarer og commit-meldinger

- Gi issues en tittel som beskriver feilen, behovet eller spørsmålet.
- Skill mellom observert oppførsel, forventet oppførsel og forslag til løsning i feilrapporter.
- Bruk imperativ i PR-titler og commit-emnelinjer, som «Rett validering av eier-ID».
- Beskriv den faktiske endringen og grunnen i brødteksten til PR-er og commit-meldinger.
- Skill mellom spørsmål, anbefalinger og krav i kommentarer.
- Oppgi hvilke kontroller du kjørte, og hvilke resultater du fikk.
- Skill utført arbeid fra planlagt arbeid og forhold du ikke har kontrollert.
- Bruk 25 ord per beskrivende setning som rettesnor i pragmatisk modus.
- Behold saksnumre, filstier, kommandoer og tekniske navn.

Hvis kontrollene dokumenterer resultatet, kan teksten si «Testene bestod».
Hvis kontrollene ikke kjørte, skal teksten si det.
En språklig forenkling skal ikke gjøre «Testene kan avdekke feilen» til «Testene avdekket feilen».

## Feilmeldinger og tekst fra kommandolinjen

Beskriv hva som skjedde, og hva leseren kan gjøre.
Oppgi årsaken bare når den er kjent.
Skill mellom beskrivelsen av feilen og instruksen til leseren.

**Før:** Oi! Noe gikk galt under forsøket på å opprette en tilkobling. Vennligst sørg for at legitimasjonen din er riktig konfigurert, og prøv igjen.

**Etter:** Tilkoblingen mislyktes. Kontroller legitimasjonen. Prøv deretter på nytt.

Omskrivingen hevder ikke at passordet er feil. Kilden dokumenterer ikke en slik årsak.

## Driftsrutiner og prosedyrer

- Bruk imperativ for handlingene leseren skal utføre.
- Sett en nødvendig betingelse før handlingen.
- Plasser dokumenterte advarsler før handlingen de gjelder.
- Bruk 20 ord per instruks som rettesnor i pragmatisk modus og grense i streng modus.
- Skill forklaringer fra trinnene i prosedyren.

## Hendelsesrapporter og evalueringer

Bruk riktig verbtid for tidslinjen, dagens status og planlagte tiltak.
Behold usikkerhet om årsak, omfang og påvirkning.
Skill mellom observasjoner og hypoteser.

**Før:** Vi har identifisert en feil som kan ha påvirket enkelte brukeres mulighet til å benytte tjenesten.

**Etter:** Vi har funnet en feil som kan ha hindret noen brukere i å bruke tjenesten.

Begge tekstene uttrykker usikker påvirkning.
Ikke legg til klokkeslett, prosenttall eller årsaker som ikke finnes i kilden.

Med dokumenterte målinger kan teksten være mer konkret:

> Mellom 14.02 og 14.31 mislyktes 12 % av forespørslene.

Dette er et separat eksempel med måledata, ikke en omskriving av den usikre beskrivelsen over.

## Versjonsnotater og endringslogger

Beskriv én endring per oppføring når det gir en tydelig oversikt.
Skill mellom endret oppførsel og handlinger brukeren må utføre.
Behold forskjellen mellom et krav om oppgradering og en anbefaling om oppgradering.

## Instruksjoner til agenter

- Gjør handlinger, ansvar og betingelser tydelige.
- Skill mellom krav, anbefalinger og tillatte valg.
- Bruk «må» for krav og «bør» for anbefalinger når det stemmer med kilden.
- Behold forskjellige fagbegreper for forskjellige handlinger.
- Hvis nødvendig informasjon mangler, be om en presisering fremfor å anta svaret.

## Kundestøtte og statussider

Beskriv kjent status og hva brukeren kan gjøre.
Behold usikkerhet om omfang og rettetidspunkt.
Ikke gjør en forventet rettetid til et løfte gjennom omskriving.

## Oversettelse og lokalisering

Bruk konsekvent terminologi og tydelige henvisninger.
Behold nødvendige forskjeller mellom fagbegreper.
Kontroller at pronomen har en tydelig referanse.
Velg streng modus bare når oppgaven uttrykkelig krever det.

## Grensesnittekst og tomme tilstander

Gi en kort forklaring og en tydelig neste handling.
Følg dokumenterte plassbegrensninger uten å endre betydningen.
Eksisterende knappenavn og etiketter er urørlige når teksten viser til dem.
Ved en uttrykkelig oppgave om å omskrive selve grensesnitteksten kan du endre dem.

## Andre teksttyper

Tilpass tonen til oppgaven i markedsføring, blogger og merkevaretekst.
Ikke innfør streng modus uten et uttrykkelig ønske.
Bevar fakta og meningen også når teksten har et annet formål enn teknisk dokumentasjon.
