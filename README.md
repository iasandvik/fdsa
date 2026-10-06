# FDSA landingsside (prototype)

Klikkbar prototype for en landingsside om Forsvarets datasentriske arkitektur (FDSA), bygget på målbildet med ikrafttredelse 5. oktober 2026, Digital reguleringsplan (DRP 2026) og Forsvarets skystrategi.

**Status:** Utkast og spesifikasjonsgrunnlag. Ikke en offisiell publisering fra Forsvaret. Innholdet er ikke godkjent av Forsvarsstaben (FST).

## Åpne siden

Åpne `index.html` i en nettleser. Filen er selvstendig, med fonter, logo og bilder innebygd. Eneste eksterne avhengighet er Google Fonts (Source Sans 3), med reservefont hvis den ikke lastes.

## Filer

| Fil | Innhold |
|---|---|
| `index.html` | Ferdig samlet side i én fil. Det er denne som publiseres. |
| `FDSA Landingsside v2.dc.html` | Kildefilen for gjeldende versjon. |
| `FDSA Landingsside v2 export.dc.html` | Kildefilen klargjort for samling til `index.html`. |
| `FDSA Landingsside.dc.html` | Forrige versjon (åtte arkitekturplan), beholdt for sporbarhet. |
| `assets/`, `fonts/` | Bilder, illustrasjoner, logo og Forsvaret-fonter. |
| `support.js`, `image-slot.js` | Kjøremiljø for kildefilene. |

## Hva siden inneholder

- **Hvorfor:** tre drivere fra kapittel 2 i målbildet, inkludert Innst. 440 S.
- **Pilarer og fundamenter:** tre pilarer og ni fundamenter med alle underpunkter (1.1 til 9.4), forklaring og eksempel.
- **DRP:** alle ti innsatsområder og 37 prinsipper. Viser at FDSA operasjonaliserer 16 av dem, og hvilke fundamenter de er koblet til.
- **Styrende dokumenter:** DRP, FDSA, skystrategien og KI-policyen, med hva hvert dokument styrer.
- **Konseptuell arkitektur:** de ti kapabilitetsområdene med nivå 2-kapabiliteter, realiserende initiativ (FDDP, MilSky, Datasenter, FKI, ERP) og koblinger til fundamentene.
- **FDDP:** noder i cloud, core, fog og edge, tilgangsmekanismer og FAKTISK.
- **Scenarier:** Link 16/22, P-8, Skjold-klassen og Arctic Eye, steg for steg.
- **Samarbeid, nyheter og kontaktskjema.**

Siden finnes på norsk og engelsk og er tilpasset mobil, nettbrett og PC.

## Interaksjon

- Nodene i forsidebildet er klikkbare og åpner forklaring av objektet og nodetypen.
- DRP-prinsipper, nivå 2-kapabiliteter, FAKTISK-bokstaver og noder åpner sidepaneler. Esc lukker.
- Initiativvelgeren og «Vis i arkitekturen» i scenariene markerer områdene i arkitekturfiguren.

## Kilder

- Målbilde for Forsvarets datasentriske arkitektur (FDSA), ikrafttredelse 2026-10-05
- Digital reguleringsplan (DRP), ikrafttredelse 2026-10-05
- Forsvarets skystrategi, ikrafttredelse 2026-10-05
- [Digital transformasjon i Forsvaret](https://www.forsvaret.no/om-forsvaret/digital-transformasjon-i-forsvaret)
- [NATO DCRA](https://nhqc3s.hq.nato.int/apps/DCRA_Report/index.html)
- [Federated Mission Networking](https://www.act.nato.int/activities/federated-mission-networking/)

## Må avklares før publisering

**Innhold som er tolkning, ikke målbildetekst**
- Koblingene mellom nivå 2-kapabiliteter og fundamenter. Dette er merket på siden.
- Plasseringen av scenariesteg på noder. Bare Skjold-klassen (FDDP ombord) er forankret i målbildet.
- Tekstene om enkeltobjektene i forsidebildet.
- Sammendragene av DRP-prinsippene. Ordlyden i DRP er styrende.

**Avvik mellom dokumentene**
- Skystrategien kaller fog «regionale noder». FDSA kaller dem «fremskutte noder». Siden følger FDSA.

**Bilder**
- Forsidebildet er KI-generert (Astra) og merket slik. Godkjenning av bruk må avklares.
- Nodemerkene i bildet er på engelsk, og allierte flagg kan tolkes som konkret tilstedeværelse.
- Hvis bildet byttes, må klikkflatene over nodene justeres.

**Teknisk og formelt**
- KI-policyen er ikke publisert eksternt. Kortet viser bare DRP-prinsippet DAT3.
- Kontaktskjemaet åpner e-postprogrammet. Mottakeradressen må byttes til en funksjonsadresse.
- Nyhetssaker og datoer er eksempler.
- Universell utforming (WCAG 2.1 AA) er ikke testet.
- Body-fonten er Source Sans 3 som erstatning for Akkurat.

## Videre arbeid

Produksjonsversjonen bygges i publiseringsløsningen til forsvaret.no. Bruk prototypen som spesifikasjon for struktur, innhold og interaksjon.

## Kontakt

Inge Andre Sandvik, FST Teknologi, Cyber og IKT
