---
layout: bare
title: IPA Reader-utvidelse — Brukerveiledning
lang: no
---

# IPA Reader - Brukerveiledning

> Versjon: v1.4.3

## Introduksjon

IPA Reader er en nettleserutvidelse designet for engelskelever. Den legger til IPA (Det internasjonale fonetiske alfabetet) uttaleanmerkninger til engelske ord på nettsider og i PDF-filer, med støtte for både amerikansk og britisk engelsk accent. Den inkluderer også en innebygd engelsk ordbok, tekst-til-tale og oversettelse — slik at du lettere kan lære engelsk uttale.

---

## Hovedfunksjoner

- **Hele siden IPA-modus** — Legg til IPA-anmerkninger til alle engelske ord på siden med ett klikk; IPA-symbolene er fargekodet etter type (vokaler, konsonanter, trykkmerker) for enkel lesing
- **Ordbok ved musepeker** — Hold musen over ord for å se engelske definisjoner (82 000+ ord fra WordNet), IPA med fargekodede symboler og uttaleknapper; velg mellom Ordbok-modus, Verktøytips-modus eller Av
- **PDF-leser** — Innebygd PDF-leser med IPA-anmerkninger, ordbok, tale og oversettelse; støtter dra-og-slipp, lasting fra URL og automatisk PDF-gjenkjenning med smart omdirigering
- **Svake/sterke former** — Vis automatisk svake og sterke uttalevarianter av vanlige funksjonsord (f.eks. «the», «to», «can») for å mestre naturlig sammenhengende tale
- **Amerikansk & britisk accent** — Bytt mellom amerikansk engelsk (en-US) og britisk engelsk (en-GB) IPA
- **Text-to-Speech** — Klikk på høyttalerknappen for å høre uttale som matcher din valgte accent
- **Valg-tale med karaokeeffekt** — Velg vilkårlig engelsk tekst; en kompakt verktøylinje vises med tale- og oversettelsesknapper; tale spilles av med sanntids ord-for-ord markering (karaokeeffekt) synkronisert med lyden
- **Valg-oversettelse** — Velg vilkårlig tekst, klikk oversettelsesknappen i verktøylinjen for øyeblikkelig oversettelse via Bing eller Google Translate, vist i en inline-boble
- **Homografgjenkjenning** — Automatisk identifisering av ord med flere uttaler (f.eks. «read», «live») og valg av riktig uttale basert på kontekst
- **Hurtigtaster** — Rask tilgang til kjernefunksjoner via tilpassbare hurtigtaster
- **Fler språk grensesnitt** — Støtter 41 grensesnittspråk

---

## Slik bruker du

### Steg 1: Installer utvidelsen

Installer **IPA Reader** fra [Chrome Web Store](https://chromewebstore.google.com/), eller last den inn lokalt i utviklermodus.

### Steg 2: Åpne en vilkårlig nettside

Besøk en vilkårlig nettside med engelsk innhold.

### Steg 3: Aktiver IPA

Klikk på utvidelsesikonet i nettleserens verktøylinje. Slå på «Aktiver IPA», deretter «Hele siden IPA» for å anmerke alle ord på siden. Du kan også klikke på den flytende knappen nederst til høyre.

### Steg 4: Vis IPA

Hold musen over ord for å se IPA-verktøytips med fargekodede fonetiske symboler. Klikk på høyttalerikonet for å høre uttale. For ord med svake/sterke former viser verktøytipset begge variantene.

### Steg 5: Tala og oversett valgt tekst

Velg vilkårlig engelsk tekst med musen. En kompakt verktøylinje vises nær markeringen med to knapper:
- **🔊 Tala** — Leser den valgte teksten høyt med karaoke-lignende ord-for-ord markering
- **🌐 Oversett** — Viser en inline oversettelsesboble under verktøylinjen

Du kan også høyreklikke og velge «IPA Reader > Speak Selection» eller «IPA Reader > Translate Selection».

> **Tips:** Klikk på utvidelsesikonet i nettleserens verktøylinje for å åpne innstillingspanelet og justere accenttype, talehastighet, musepeker-modus, oversettelsesmotor med mer.

---

## Hele siden IPA-modus

Når hele siden IPA-modus er aktivert, får hvert engelske ord på siden en IPA-anmerkning over seg med ruby-tekst. IPA-symbolene er fargekodet for enkel lesing:

- **Vokaler** — uthevet i blått
- **Konsonanter** — vist i grått
- **Trykkmerker** (ˈ ˌ) — uthevet i rødt
- **Lengdemerker** (ː) — uthevet i lilla

Utvidelsen justerer automatisk linjehøyden slik at anmerkningene ikke overlapper teksten, og skalerer IPA-skriftstørrelsen etter ordlengde for et ryddig oppsett.

---

## Ordbok ved musepeker

Utvidelsen har en innebygd engelsk ordbok basert på WordNet (82 000+ ord). Du kan velge mellom flere musepeker-moduser i innstillingene:

| Modus | Oppførsel |
|-------|-----------|
| **Ordbok** | Musepeker viser IPA + engelsk definisjon + uttaleknapp |
| **Verktøytips** | Musepeker viser IPA + uttaleknapp (ingen definisjoner) |
| **Av** | Ingen musepeker-effekt |

I **Ordbok**-modus viser verktøytipset:
- Ordet og IPA-transkripsjonen
- Uttaleknapp (klikk for å høre)
- Engelske definisjoner fra WordNet

> **Tips:** Ordbokdata lastes ved behov når Ordbok-modus er på, og lastes ut ved bytte til andre moduser for å spare minne.

---

## PDF-leser

IPA Reader har en innebygd PDF-leser slik at du kan lese PDF-dokumenter med IPA-anmerkninger, ordbok, tale og oversettelse — de samme funksjonene som på nettsider, nå også for PDF.

### Åpne en PDF

**Metode 1: Fra popup-vinduet**  
Klikk på utvidelsesikonet, deretter «Open PDF Reader». Dra og slipp en PDF-fil eller klikk «Choose File» for å åpne en lokal PDF. Du kan også lime inn en PDF-URL.

**Metode 2: Kontekstmeny**  
Høyreklikk en `.pdf`-lenke på en nettside og velg «Open PDF with IPA Reader».

**Metode 3: Automatisk gjenkjenning**  
Når «PDF Smart Detection» er aktivert i innstillingene, omdirigerer utvidelsen automatisk `.pdf`-URL-er til den innebygde leseren. Når en PDF oppdages men ikke omdirigeres (f.eks. i Chromes innebygde visning), får du varsler og oppfordringer om å åpne i IPA Reader.

### Funksjoner i PDF-leseren

- **IPA-anmerkninger** — Alle IPA-funksjoner fungerer på PDF-tekst, inkludert hele-siden-modus og musepeker-verktøytips
- **Klikk-ordbok** — Klikk et ord for å se definisjonen (i PDF brukes klikk i stedet for musepeker for mindre forstyrrende lesing)
- **Valg-verktøylinje** — Velg tekst for å tale, oversette eller kopiere
- **Sidefelt** — Innholdsfortegnelse og miniatyrbilder av sider
- **Søk** — Søk i PDF-teksten
- **Temaer** — Mørkt, lyst og sepia lesetema
- **Zoom** — Flere zoomnivåer, inkludert Auto, Tilpass side og Sidbredde
- **Hurtigtaster** — Piltaster for navigasjon, +/- for zoom, Ctrl/Cmd+F for søk

---

## Svake/sterke former

Mange vanlige engelske funksjonsord har to uttaler:

- **Svak form** — den reduserte uttalen i naturlig sammenhengende tale (f.eks. «the» → /ðə/)
- **Sterk form** — den fulle uttalen ved betoning eller isolert (f.eks. «the» → /ðiː/)

Når «Vis svake/sterke former» er aktivert, viser verktøytipset begge variantene for disse ordene, merket «WEAK» og «STRONG». Dette hjelper deg å forstå hvordan uttalen endrer seg i naturlig tale.

Omfattet ord inkluderer: artikler (the, a, an), preposisjoner (to, for, of, from, at, as, than), konjunksjoner (and, or, but), pronomen (you, your, her, him, his, them, us, our, there), hjelpeverb (am, is, are, was, were, been, can, could, would, should, must, shall, will, do, does, have, has, had) med mer.

---

## Valg-tale og karaoke

Valg-tale-funksjonen lar deg velge vilkårlig engelsk tekst og lese den høyt med ett klikk — perfekt for å lære setningsuttale og leseøvelse.

**Metode 1: Valg-verktøylinje**  
Velg engelsk tekst med musen. En kompakt verktøylinje vises nær markeringen med 🔊 taleknapp og 🌐 oversettelsesknapp. Klikk taleknappen for avspilling. Mens teksten leses høyt, markeres hvert ord i sanntid (karaokeeffekt), slik at du kan følge med.

**Metode 2: Høyreklikk-meny**  
Etter å ha valgt engelsk tekst, høyreklikk og velg «IPA Reader > Speak Selection».

**Metode 3: Hurtigtast**  
Velg tekst og trykk `Alt+Shift+S` (Mac: `Ctrl+Shift+S`) for å tale.

> **Tips:** Karaoke-markering fungerer best når nettleseren støtter TTS ordgrensehendelser. Hvis ikke støttet, bruker utvidelsen et tidsbasert reserveoppsett for jevn markering.

---

## Oversettelse

Velg vilkårlig tekst på siden og bruk oversettelsesfunksjonen for øyeblikkelige oversettelser.

**Metode 1: Valg-verktøylinje**  
Velg tekst, klikk deretter på 🌐 oversettelsesknappen i verktøylinjen. En oversettelsesboble vises under med resultatet og en kopieringsknapp.

**Metode 2: Høyreklikk-meny**  
Velg tekst, høyreklikk og velg «IPA Reader > Translate Selection».

**Metode 3: Hurtigtast**  
Velg tekst og trykk `Alt+Shift+T` (Mac: `Ctrl+Shift+T`) for å oversette.

**Oversettelsesmotorer:**
- **Bing Translate** (standard) — drevet av Microsoft Translator
- **Google Translate** — drevet av Google

Begge motorene støtter **108 målspråk**.

Du kan bytte oversettelsesmotor og målspråk i utvidelsesinnstillingene. Målspråket oppdages automatisk fra nettleserspråket ditt.

> **Tips:** Klikk utenfor verktøylinjen eller boblen for å lukke dem.

---

## Hurtigtaster

| Hurtigtast | Mac-hurtigtast | Handling |
|----------|-------------|--------|
| `Alt+Shift+I` | `Ctrl+Shift+I` | Slå IPA-anmerkninger av/på |
| `Alt+Shift+S` | `Ctrl+Shift+S` | Tal valgt tekst |
| `Alt+Shift+T` | `Ctrl+Shift+T` | Oversett valgt tekst |

> **Tips:** Du kan tilpasse disse hurtigtastene i Chrome på `chrome://extensions/shortcuts`.

---

## Innstillingsveiledning

| Innstilling | Beskrivelse |
|---------|-------------|
| **Aktiver IPA** | Hovedbryter for å aktivere eller deaktivere IPA-anmerkningsfunksjonen |
| **Hele siden IPA** | Når aktivert, vises fargekodet IPA for alle engelske ord over teksten |
| **IPA-stil** | Velg mellom amerikansk engelsk og britisk engelsk IPA og uttale |
| **Musepeker-modus** | Velg oppførsel: Ordbok (IPA + definisjoner + lyd), Verktøytips (IPA + lyd) eller Av |
| **Vis svake/sterke former** | Vis svake og sterke uttalevarianter av vanlige funksjonsord |
| **Setnings-talehastighet** | Juster hastigheten for setningslesing (enkeltsordsuttale påvirkes ikke) |
| **Oversettelsesmotor** | Velg mellom Bing Translate og Google Translate |
| **Målspråk** | Angi oversettelsens målspråk (automatisk fra nettleserspråk) |
| **PDF Smart Detection** | Når aktivert, omdirigeres PDF-URL-er automatisk til den innebygde leseren, og du får varsler når PDF-er oppdages |

---

## FAQ

**S: Hvorfor fungerer det ikke på noen sider?**  
S: Av sikkerhetsgrunner kan nettleserutvidelser ikke kjøre på spesielle sider som `chrome://`, nettleserinnstillinger eller Chrome Web Store.

**S: Hva hvis IPA mangler for noen ord?**  
S: IPA-ordboka dekker over 134 000 amerikanske og over 67 000 britiske engelske ord. For ord utenfor ordboka genererer utvidelsen tilnærmet IPA via lemmatisering og regelbasert G2P (grafem–fonem). Dette merkes med ≈ eller ~ i verktøytipset.

**S: Ingen lyd fra text-to-speech?**  
S: Sjekk systemlydinnstillingene dine og sørg for at engelske stemmepakker er installert. Talestøtte varierer mellom nettlesere og operativsystemer.

**S: Hele siden-modus påvirker layout?**  
S: IPA-anmerkninger krever ekstra plass. Utvidelsen justerer automatisk linjehøyden for å minimere layoutpåvirkning. Hvis det fortsatt påvirker lesingen, deaktiver hele siden-modus og bruk musepeker-verktøytips i stedet.

**S: Hva betyr symbolene ~ og ≈ i verktøytipsa?**  
S: ~ betyr at IPA er generert med regelbasert konvertering (G2P) i stedet fra ordboka. ≈ betyr at IPA er avledet fra et beslektet grunnord via lemmatisering. Disse kan være mindre nøyaktige enn ordbokoppføringer.

**S: Oversettelse fungerer ikke?**  
S: Oversettelse krever internettforbindelse. Hvis Bing Translate feiler, prøv å bytte til Google Translate i innstillingene. Noen nettverk kan blokkere tilgang til oversettelsestjenester.

**S: Hvordan åpner jeg en PDF med IPA Reader?**  
S: Du kan åpne PDF-er på flere måter: klikk «Open PDF Reader» i popup-vinduet, høyreklikk en PDF-lenke og velg «Open PDF with IPA Reader», eller aktiver «PDF Smart Detection» i innstillingene for automatisk omdirigering av PDF-URL-er til den innebygde leseren.

**S: PDF Smart Detection er på, men noen PDF-er omdirigeres ikke?**  
S: Auto-omdirigering gjelder URL-er som ender på `.pdf`. For PDF-er uten `.pdf`-endelse eller vist i Chromes innebygde visning får du varsel og merke som oppfordrer deg til å åpne i IPA Reader.

**S: Kan jeg bruke ordboka offline?**  
S: Ja. WordNet-ordboka (82 000+ ord) er fullstendig innebygd i utvidelsen. Alle oppslag skjer lokalt uten nettverkstilkobling.

---

## Relaterte lenker

- [Privacy Policy](../privacy-policy)
- [Support & Feedback](../support)

---
