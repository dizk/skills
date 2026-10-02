# Regelkatalog for enkel norsk

Katalogen inneholder 53 nummererte regler og utdypende skriveråd.
Numrene er beholdt fra versjon 1.0.0. Ordlyden er tilpasset meningsbevaring og de to modusene.

## Prioritet og bruk

[Hovedveiledningens regel om meningsbevaring](../SKILL.md#hovedregel-bevar-meningen) går foran alle reglene i katalogen.
Kode, tekniske navn, tall og sitater skal stå urørt.

I pragmatisk modus er lengdegrenser og stilvalg rettesnorer.
I streng modus gjelder de oppgitte grensene, med unntak for meningsbevaring og urørlig innhold.
Hvis en grense krever et slikt unntak, oppgi grunnen ved tekstkontroll.
Krav til en bestemt ordliste gjelder bare når oppgaven har en dokumentert ordliste.

## Del 1 — Ord

| Regel | Instruksjon |
|---|---|
| 1.1 | Følg oppgavens dokumenterte ordliste i streng modus når en slik liste finnes. Ellers bruk vanlig bokmål og etablerte fagord. |
| 1.2 | Hvis ordlisten begrenser ordklassen til et ord, følg denne begrensningen uten å endre meningen. |
| 1.3 | Bruk fagord med den betydningen de har i den aktuelle sammenhengen. |
| 1.4 | Følg dokumenterte ordformer når oppgaven krever en bestemt ordliste. Ellers bruk vanlige bokmålsformer. |
| 1.5 | Bruk etablerte fagsubstantiv, som «webhook», «commit» og «endepunkt». |
| 1.6 | Hvis ordlisten mangler et nødvendig fagord, forklar ordet fremfor å erstatte det med et upresist ord. |
| 1.7 | Unngå å lage nye verb av substantiv når et etablert verb uttrykker handlingen. |
| 1.8 | Bruk fagbegrepene i prosjektet eller bransjen. |
| 1.9 | Velg korte og klare fagbegreper når de er like presise som alternativene. |
| 1.10 | Unngå slang og sjargong som målgruppen ikke kjenner. Behold etablerte fagbegreper. |
| 1.11 | Bruk samme ord for samme betydning. Behold forskjellige ord for forskjellige begreper eller handlinger. |
| 1.12 | Bruk etablerte fagverb, som «kompilere», «validere» og «autorisere». |
| 1.13 | Foretrekk verb fremfor tunge substantivuttrykk når de beskriver den samme handlingen. |
| 1.14 | Skriv konsekvent bokmål med samme formvalg gjennom dokumentet. |

«Bekrefte» kan bety å godkjenne et valg. «Kontrollere» kan bety å undersøke om et vilkår er oppfylt.
Disse handlingene skal ikke få samme navn bare for å redusere antall ord i teksten.
Det samme gjelder «validere», «autentisere» og «autorisere».

## Del 2 — Sammensatte substantiv

| Regel | Instruksjon |
|---|---|
| 2.1 | Unngå tunge sammensetninger. I streng modus er grensen høyst tre ledd, med unntak for urørlige tekniske navn. |
| 2.2 | Del lange sammensetninger med preposisjoner, eller innfør en forklart kortform. Bruk bindestrek der norsk rettskriving krever det. |

**Tungt:** tilkoblingspooltidsavbruddskonfigurasjonsverdien
**Feil særskriving:** tilkoblingspool tidsavbrudd verdi
**Tydeligere:** tidsavbruddsverdien for tilkoblingspoolen

## Del 3 — Verb

| Regel | Instruksjon |
|---|---|
| 3.1 | Bruk verbformer som uttrykker handlingen og tidspunktet riktig. Følg en dokumentert ordliste når den er relevant. |
| 3.2 | Bevar forskjellen mellom krav, anbefaling, tillatelse og mulighet. Ikke erstatt «bør» med «må» uten grunnlag i kilden. |
| 3.3 | Bruk partisipp som adjektiv eller i verbformer når det uttrykker meningen presist, som «det bufrede svaret» og «vi har rettet feilen». |
| 3.4 | Foretrekk enkle verbformer når de bevarer meningen. Behold perfektum og andre sammensatte former når tidsforhold eller usikkerhet krever dem. |
| 3.5 | Unngå verbalsubstantiv som skjuler handlingen. Skriv «installer tjenesten» fremfor «utfør installering av tjenesten». Behold fagord som «logging». |
| 3.6 | Foretrekk aktiv form når aktøren er kjent og relevant. Passiv er tillatt når den gir en mer presis eller naturlig beskrivelse. |
| 3.7 | Beskriv handlinger med konkrete verb, som «komprimer filen» fremfor «foreta komprimering av filen». |

### Kravstyrke, usikkerhet og tid

| Kildetekst | Bevar dette |
|---|---|
| «Klienten må sende et token.» | Et krav, ikke en anbefaling. |
| «Du bør øke tidsavbruddet.» | En anbefaling, ikke et krav. |
| «Endringen kan ha påvirket noen brukere.» | Usikker påvirkning i fortiden, ikke en bekreftet hendelse. |
| «Før rettingen kunne klienten sende samme melding to ganger.» | En tidligere mulighet, ikke nødvendigvis dagens oppførsel. |
| «Vi har rettet feilen.» | En utført handling med relevans nå. Perfektum er tillatt. |

Ord som «muligens», «trolig» og «kunne» er ikke regelbrudd i seg selv.
Fjern dem bare når de er fyllord, og omskrivingen bevarer graden av sikkerhet og riktig tidspunkt.

## Del 4 — Setninger

| Regel | Instruksjon |
|---|---|
| 4.1 | Skriv korte og klare setninger. Del lange setninger når delingen gjør sammenhengen tydeligere. |
| 4.2 | Behold nødvendige ord som «at», «som» og «å». Ikke bruk telegramstil for å nå en ordgrense. |
| 4.3 | Bruk punktlister når teksten inneholder flere selvstendige punkter. |
| 4.4 | Bruk bindeord som tydeliggjør sammenhengen. Ikke legg til «derfor» hvis kilden ikke dokumenterer en årsakssammenheng. |
| 4.5 | Bruk artikler og pekende ord der norsk grammatikk krever dem. |

**Telegramstil:** Kontroller fil finnes før kjøring.
**Tydeligere:** Kontroller at filen finnes før du kjører kommandoen.

En leddsetning med «noe som» eller «slik at» kan være tydelig og nødvendig.
Vurder lesbarheten etter regel 4.1. Ikke behandle uttrykket som et verbalsubstantiv etter regel 3.5.

## Del 5 — Prosedyretekst

| Regel | Instruksjon |
|---|---|
| 5.1 | Bruk 20 ord per setning som rettesnor i pragmatisk modus og grense i streng modus. Meningsbevaring går foran grensen. |
| 5.2 | Gi normalt én instruksjon per setning. Handlinger som skal skje samtidig, kan stå sammen. |
| 5.3 | Bruk imperativ for direkte instrukser, som «Kjør migreringen». Behold anbefalinger som anbefalinger. |
| 5.4 | Sett en nødvendig betingelse før handlingen i instrukser: «Hvis byggingen mislykkes, les loggen.» |
| 5.5 | Skill forklarende merknader fra handlingene leseren skal utføre. Merknader følger reglene for beskrivende tekst. |

**Før:** Øk tidsavbruddet hvis nettverket er tregt.
**Etter:** Hvis nettverket er tregt, øk tidsavbruddet.

## Del 6 — Beskrivende tekst

| Regel | Instruksjon |
|---|---|
| 6.1 | Presenter nye fakta gradvis. Hold sammen fakta som trenger hverandre for å gi mening. |
| 6.2 | Bruk nøkkelord og tydelige henvisninger for å vise sammenhengen. |
| 6.3 | Bruk 25 ord per setning som rettesnor i pragmatisk modus og grense i streng modus. Meningsbevaring går foran grensen. |
| 6.4 | Samle informasjon som hører sammen, i samme avsnitt. |
| 6.5 | Hold hvert avsnitt til ett hovedtema. |
| 6.6 | Bruk maks seks setninger per avsnitt som rettesnor i pragmatisk modus og grense i streng modus. |

«Tjenesten stopper når forbindelsen brytes» er en gyldig beskrivelse.
Regel 5.4 gjelder plassering av betingelser i instrukser, ikke alle forekomster av «hvis», «dersom» eller «når».

## Del 7 — Sikkerhetsinstruksjoner

| Regel | Instruksjon |
|---|---|
| 7.1 | Behold dokumenterte advarsler og risikonivåer. Ikke legg til advarsler uten grunnlag i oppgaven eller kilden. |
| 7.2 | Plasser en nødvendig advarsel før handlingen den gjelder, med en klar betingelse eller instruksjon. |
| 7.3 | Forklar den kjente risikoen eller det mulige resultatet. Behold usikkerheten i kilden. |

«Flagget kan slette data» skal ikke bli «Flagget sletter data» uten grunnlag i kilden.

## Del 8 — Tegnsetting og ordtelling

| Regel | Instruksjon |
|---|---|
| 8.1 | Foretrekk punktum fremfor semikolon når det gjør teksten lettere å lese. I streng modus skal du dele ved semikolon når meningen bevares. |
| 8.2 | Bruk bindestrek etter norsk rettskriving, som i «API-nøkkel» og «PostgreSQL-serveren». |
| 8.3 | Bruk parenteser til korte presiseringer. Flytt viktig informasjon ut av parentesen. |
| 8.4 | I punktlister teller innledningen før kolon som én setning ved lengdekontroll. |
| 8.5 | Tell vanlig tekst i parentes som vanlige ord. Parenteser gir ikke unntak fra lesbarhetsvurderingen. |
| 8.6 | Tell en urørlig kommando, kodefrase, etikett eller et teknisk navn som én enhet. Tall med enhet teller også som én enhet. |
| 8.7 | Et ord med bindestrek teller som ett ord. |

Ordgrenser skal hjelpe leseren, ikke skjule lange forklaringer i parenteser eller sitater.
Vanlig sitert prosa er urørlig, men kan fortsatt være vanskelig å lese.
Ikke endre sitatet for å oppfylle en ordgrense.

## Del 9 — Skrivepraksis

| Regel | Instruksjon |
|---|---|
| 9.1 | Hvis ordbytte gir dårlig språk eller feil mening, bygg om setningen. |
| 9.2 | Kontroller betydningen i sammenheng fremfor å følge en erstatningstabell mekanisk. |
| 9.3 | Velg konkrete verb når de er mer presise enn uttrykket de erstatter. Behold etablerte uttrykk som allerede er tydelige. |
| 9.4 | Hold en konsekvent stil og terminologi uten å slå sammen forskjellige betydninger. |

## Ordvalg som kan forenkles

Tabellen gir forslag, ikke automatiske erstatninger.
Bruk et forslag bare når det bevarer betydningen i sammenhengen.

| Uttrykk | Mulig omskriving |
|---|---|
| benytte, anvende | bruke |
| foreta en vurdering av | vurdere |
| i forkant av | før |
| i etterkant av | etter |
| grunnet at | fordi |
| det er verdt å merke seg at | Fjern innledningen hvis den ikke tilfører mening. |
| sømløst, robust, lynraskt | Beskriv en dokumentert egenskap, eller fjern udokumentert ros. |
| ved behov | Oppgi betingelsen hvis den er kjent. Ellers behold uttrykket eller be om en presisering. |
| f.eks., dvs. | for eksempel, det vil si |
| osv. | Nevn kjente eksempler uten å late som listen er fullstendig. |

## Eksempler som bevarer meningen

### Anbefaling

**Før:** Det anbefales at tidsavbruddet økes.
**Etter:** Du bør øke tidsavbruddet.

Omskrivingen gjør aktøren tydelig uten å gjøre anbefalingen til et krav.

### Historisk mulighet

**Før:** Før rettingen var det mulig for klienten å sende samme melding to ganger.
**Etter:** Før rettingen kunne klienten sende samme melding to ganger.

«Kunne» bevarer tidspunktet. «Kan» ville ha beskrevet en nåværende mulighet.

### Forskjellige handlinger

- «Bekreft slettingen» ber leseren godkjenne en handling.
- «Kontroller at slettingen er fullført» ber leseren undersøke resultatet.

Begge formuleringene er gyldige. De skal ikke erstatte hverandre som et stilgrep.
