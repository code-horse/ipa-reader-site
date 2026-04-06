---
layout: bare
title: IPA Reader-extensie - Gebruikershandleiding
lang: nl
---

# IPA Reader - Gebruikershandleiding

> Versie: v1.4.0

## Introductie

IPA Reader is een browserextensie ontworpen voor mensen die Engels leren. Het voegt IPA (Internationaal Fonetisch Alfabet) uitspraakannotaties toe aan Engelse woorden op webpagina's en in PDF's, met ondersteuning voor zowel Amerikaans als Brits Engels. Het bevat ook een ingebouwd Engels woordenboek, tekst-naar-spraak en vertaalfuncties — zodat je de Engelse uitspraak makkelijker kunt leren.

---

## Belangrijkste functies

- **Hele pagina IPA-modus** — Voeg IPA-annotaties toe aan alle Engelse woorden op de pagina met één klik; IPA-symbolen zijn kleurgecodeerd per type (klinkers, medeklinkers, klemtoontekens) voor eenvoudig lezen
- **Hover-woordenboek** — Beweeg over woorden om Engelse definities te zien (82K+ woorden uit WordNet), IPA met kleurgecodeerde symbolen en uitspraakknoppen; kies tussen Woordenboekmodus, Tooltipmodus of Uit
- **PDF-lezer** — Ingebouwde PDF-lezer met IPA-annotaties, woordenboek, spraak en vertaling; ondersteunt slepen en neerzetten, laden via URL en automatische PDF-detectie met slimme omleiding
- **Zwakke/sterke vormen** — Automatisch de zwakke en sterke uitspraakvarianten van functiewoorden (bijv. „the”, „to”, „can”) weergeven om natuurlijk vloeiend spreken te beheersen
- **Amerikaans & Brits accent** — Schakel tussen Amerikaans Engels (en-US) en Brits Engels (en-GB) IPA
- **Text-to-Speech** — Klik op de luidsprekerknop om de uitspraak te horen die overeenkomt met je gekozen accent
- **Selectiespraak met karaoke-effect** — Selecteer willekeurige Engelse tekst: er verschijnt een compacte werkbalk met knoppen voor voorlezen en vertalen; spraak wordt afgespeeld met woord-voor-woord markering in realtime (karaoke-effect), gesynchroniseerd met de audio
- **Selectievertaling** — Selecteer willekeurige tekst, klik op de vertaalknop in de werkbalk voor directe vertaling via Bing of Google Translate in een inline-bubbel
- **Homograafherkenning** — Automatische identificatie van woorden met meerdere uitspraken (bijv. read, live) en selectie van de juiste op basis van context
- **Sneltoetsen** — Snelle toegang tot kernfuncties via aanpasbare sneltoetsen
- **Meertalige interface** — Ondersteunt 41 interfacetalen

---

## Gebruik

### Stap 1: Extensie installeren

Installeer **IPA Reader** via de [Chrome Web Store](https://chromewebstore.google.com/), of laad deze lokaal in ontwikkelaarsmodus.

### Stap 2: Een webpagina openen

Bezoek een willekeurige webpagina met Engelse inhoud.

### Stap 3: IPA inschakelen

Klik op het extensie-icoon in de werkbalk van je browser. Schakel „IPA inschakelen” in, daarna „Hele pagina IPA” om alle woorden op de pagina te annoteren. Je kunt ook de zwevende knop rechtsonder gebruiken.

### Stap 4: IPA bekijken

Hover over woorden om IPA-tooltips te zien met kleurgecodeerde fonetische symbolen. Klik op het luidsprekericoon om de uitspraak te horen. Voor woorden met zwakke/sterke vormen toont de tooltip beide varianten.

### Stap 5: Geselecteerde tekst voorlezen en vertalen

Selecteer willekeurige Engelse tekst met de muis. Er verschijnt een compacte werkbalk bij de selectie met twee knoppen:
- **🔊 Voorlezen** — leest de selectie voor met karaoke-achtige woord-voor-woord markering
- **🌐 Vertalen** — toont een inline vertaalbubbel onder de werkbalk

Je kunt ook rechtsklikken en „IPA Reader > Speak Selection” of „IPA Reader > Translate Selection” kiezen.

> **Tip:** Klik op het extensie-icoon in de werkbalk om het instellingenpaneel te openen: accenttype, spraaksnelheid, hovermodus, vertaalengine en meer.

---

## Hele pagina IPA-modus

Wanneer de hele-pagina IPA-modus is ingeschakeld, krijgt elk Engels woord een IPA-annotatie erboven als ruby-tekst. De IPA-symbolen zijn kleurgecodeerd:

- **Klinkers** — blauw gemarkeerd
- **Medeklinkers** — grijs weergegeven
- **Klemtoontekens** (ˈ ˌ) — rood gemarkeerd
- **Lengtetekens** (ː) — paars gemarkeerd

De extensie past automatisch de regelhoogte aan om overlapping te voorkomen en schaalt de IPA-lettergrootte op basis van de woordlengte.

---

## Hover-woordenboek

De extensie bevat een ingebouwd Engels woordenboek op basis van WordNet (82.000+ woorden). Je kunt in de instellingen meerdere hovermodi kiezen:

| Modus | Gedrag |
|-------|--------|
| **Woordenboek** | Hover toont IPA + Engelse definitie + uitspraakknop |
| **Tooltip** | Hover toont IPA + uitspraakknop (geen definities) |
| **Uit** | Geen hover-effect |

In **woordenboekmodus** toont de tooltip:
- Het woord en de IPA-transcriptie
- Een uitspraakknop (klik om te horen)
- Engelse definities uit WordNet

> **Tip:** De woordenboekgegevens worden op aanvraag geladen als woordenboekmodus aan staat en uit het geheugen gehaald bij andere modi om geheugen te besparen.

---

## PDF-lezer

IPA Reader bevat een ingebouwde PDF-lezer waarmee je PDF-documenten kunt lezen met IPA-annotaties, woordenboek, spraak en vertaling — alle functies die je op webpagina's hebt, nu ook voor PDF's.

### Een PDF openen

**Methode 1: Via de popup**  
Klik op het extensie-icoon en daarna op „Open PDF Reader”. Sleep een PDF-bestand naar het venster of klik op „Choose File” om een lokale PDF te openen. Je kunt ook een PDF-URL plakken.

**Methode 2: Contextmenu**  
Rechtsklik op een `.pdf`-link op een webpagina en kies „Open PDF with IPA Reader”.

**Methode 3: Automatische detectie**  
Als „PDF Smart Detection” in de instellingen aan staat, leidt de extensie `.pdf`-URL's automatisch om naar de ingebouwde lezer. Wordt een PDF wel gedetecteerd maar niet omgeleid (bijv. in de ingebouwde Chrome-viewer), dan zie je meldingen en aanwijzingen om deze in IPA Reader te openen.

### Functies van de PDF-lezer

- **IPA-annotaties** — Alle IPA-functies werken op PDF-tekst, inclusief hele-paginamodus en hover-tooltips
- **Klik-woordenboek** — Klik op een woord om de definitie te zien (in PDF wordt klikken gebruikt in plaats van hover voor rustiger lezen)
- **Selectiewerkbalk** — Selecteer tekst om voor te lezen, te vertalen of te kopiëren
- **Zijbalk** — Inhoudsopgave en paginaminiaturen
- **Zoeken** — Zoeken in de PDF
- **Thema's** — Donker, licht en sepia leesthema's
- **Zoom** — Meerdere zoomniveaus, waaronder Auto, Pagina passend en Paginabreedte
- **Sneltoetsen** — Pijltoetsen voor navigatie, +/- voor zoom, Ctrl/Cmd+F voor zoeken

---

## Zwakke/sterke vormen

Veel gangbare functiewoorden hebben twee uitspraken:

- **Zwakke vorm** — de gereduceerde uitspraak in natuurlijke vloeiende spraak (bijv. „the” → /ðə/)
- **Sterke vorm** — de volledige uitspraak bij nadruk of in isolatie (bijv. „the” → /ðiː/)

Als „Zwakke/sterke vormen tonen” is ingeschakeld, toont hoveren over deze woorden beide varianten in de tooltip, gelabeld als „WEAK” en „STRONG”. Zo zie je hoe uitspraak verandert in natuurlijke spraak.

Onder meer gedekt: lidwoorden (the, a, an), voorzetsels (to, for, of, from, at, as, than), voegwoorden (and, or, but), voornaamwoorden (you, your, her, him, his, them, us, our, there), hulpwerkwoorden (am, is, are, was, were, been, can, could, would, should, must, shall, will, do, does, have, has, had) en meer.

---

## Selectiespraak & karaoke

Met selectiespraak kun je willekeurige Engelse tekst selecteren en met één klik voorlezen — ideaal voor zinsuitspraak en leesoefeningen.

**Methode 1: Selectiewerkbalk**  
Selecteer Engelse tekst met de muis. Er verschijnt een compacte werkbalk bij de selectie met een 🔊 voorleesknop en een 🌐 vertaalknop. Klik op voorlezen om af te spelen. Tijdens het voorlezen wordt elk woord in realtime gemarkeerd (karaoke-effect).

**Methode 2: Rechtsklikmenu**  
Selecteer Engelse tekst, rechtsklik en kies „IPA Reader > Speak Selection”.

**Methode 3: Sneltoets**  
Selecteer tekst en druk op `Alt+Shift+S` (Mac: `Ctrl+Shift+S`) om voor te lezen.

> **Tip:** Karaoke-markering werkt het best als je browser TTS-woordgrensevenementen ondersteunt. Zo niet, gebruikt de extensie een tijdgebaseerde fallback voor vloeiende markering.

---

## Vertaling

Selecteer willekeurige tekst op de pagina en gebruik vertaling voor directe resultaten.

**Methode 1: Selectiewerkbalk**  
Selecteer tekst en klik op de 🌐 vertaalknop in de werkbalk. Er verschijnt een vertaalbubbel met het resultaat en een kopieerknop.

**Methode 2: Rechtsklikmenu**  
Selecteer tekst, rechtsklik en kies „IPA Reader > Translate Selection”.

**Methode 3: Sneltoets**  
Selecteer tekst en druk op `Alt+Shift+T` (Mac: `Ctrl+Shift+T`) om te vertalen.

**Vertaalengines:**
- **Bing Translate** (standaard) — Microsoft Translator
- **Google Translate** — Google

Beide engines ondersteunen **108 doeltalen**.

Je kunt de vertaalengine en doeltaal wijzigen in de extensie-instellingen. De doeltaal wordt standaard afgeleid van je browsertaal.

> **Tip:** Klik buiten de werkbalk of bubbel om ze te sluiten.

---

## Sneltoetsen

| Sneltoets | Mac | Actie |
|-----------|-----|-------|
| `Alt+Shift+I` | `Ctrl+Shift+I` | IPA-annotaties aan/uit |
| `Alt+Shift+S` | `Ctrl+Shift+S` | Geselecteerde tekst voorlezen |
| `Alt+Shift+T` | `Ctrl+Shift+T` | Geselecteerde tekst vertalen |

> **Tip:** Pas sneltoetsen aan in Chrome via `chrome://extensions/shortcuts`.

---

## Instellingengids

| Instelling | Beschrijving |
|---------|-------------|
| **IPA inschakelen** | Hoofdschakelaar om de IPA-annotatiefunctie in of uit te schakelen |
| **Hele pagina IPA** | Toont kleurgecodeerde IPA voor alle Engelse woorden boven de tekst |
| **IPA-stijl** | Keuze tussen Amerikaans en Brits Engels IPA en uitspraak |
| **Hovermodus** | Kies hovergedrag: Woordenboek (IPA + definities + audio), Tooltip (IPA + audio) of Uit |
| **Zwakke/sterke vormen tonen** | Zwakke en sterke uitspraakvarianten van functiewoorden |
| **Zinspraaksnelheid** | Snelheid van zinsvoorlezing (losse woorden niet beïnvloed) |
| **Vertaalengine** | Keuze tussen Bing Translate en Google Translate |
| **Doeltaal** | Doeltaal voor vertaling (standaard afgeleid van browsertaal) |
| **PDF Smart Detection** | Schakel in om PDF-URL's automatisch naar de ingebouwde lezer om te leiden en meldingen te tonen bij gedetecteerde PDF's |

---

## FAQ

**V: Waarom werkt het niet op sommige pagina's?**  
A: Om veiligheidsredenen kunnen browserextensies niet draaien op speciale pagina's zoals `chrome://`, browserinstellingen of de Chrome Web Store.

**V: Wat als IPA ontbreekt voor sommige woorden?**  
A: Het IPA-woordenboek dekt 134.000+ Amerikaanse en 67.000+ Britse Engelse woorden. Voor woorden buiten het woordenboek genereert de extensie benaderde IPA via lemmatisering en regelgebaseerde G2P, gemarkeerd met ≈ of ~ in de tooltip.

**V: Geen geluid bij text-to-speech?**  
A: Controleer je systeemvolume en of Engelse stemmen zijn geïnstalleerd. Spraakondersteuning verschilt per browser en besturingssysteem.

**V: Hele-paginamodus beïnvloedt lay-out?**  
A: IPA-annotaties nemen extra ruimte in. De extensie past regelhoogte aan om impact te beperken. Blijft het storend, schakel hele-paginamodus uit en gebruik hover-tooltips.

**V: Wat betekenen de symbolen ~ en ≈ in de tooltips?**  
A: ~ betekent dat de IPA regelgebaseerd (G2P) is gegenereerd, niet uit het woordenboek. ≈ betekent afgeleid van een verwant basiswoord via lemmatisering. Deze kunnen minder nauwkeurig zijn dan woordenboekitems.

**V: Vertaling werkt niet?**  
A: Vertaling vereist internet. Als Bing Translate faalt, probeer in de instellingen over te schakelen op Google Translate. In sommige netwerken kan toegang tot vertaaldiensten geblokkeerd zijn.

**V: Hoe open ik een PDF in IPA Reader?**  
A: Je kunt PDF's op meerdere manieren openen: klik op „Open PDF Reader” in de popup, rechtsklik op een PDF-link en kies „Open PDF with IPA Reader”, of schakel „PDF Smart Detection” in de instellingen in om PDF-URL's automatisch naar de ingebouwde lezer om te leiden.

**V: PDF Smart Detection staat aan maar sommige PDF's worden niet omgeleid?**  
A: Automatische omleiding werkt voor URL's die eindigen op `.pdf`. Voor PDF's zonder `.pdf` in de URL of die in de ingebouwde Chrome-viewer openen, zie je een melding en badge om ze in IPA Reader te openen.

**V: Kan ik het woordenboek offline gebruiken?**  
A: Ja. Het WordNet-woordenboek (82.000+ woorden) zit volledig in de extensie. Alle opzoekacties gebeuren lokaal, zonder netwerkverbinding.

---

## Gerelateerde links

- [Privacy Policy](../privacy-policy)
- [Support & Feedback](../support)

---
