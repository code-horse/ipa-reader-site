---
layout: bare
title: IPA Reader-udvidelse — Brugervejledning
lang: da
---

# IPA Reader — Brugervejledning

> Version: v1.4.4

## Introduktion

IPA Reader er en browserudvidelse designet til engelskstuderende. Den tilføjer IPA-udtaleannoteringer (International Phonetic Alphabet) til engelske ord på websider og i PDF-filer og understøtter både amerikansk og britisk engelsk. Den indeholder også en indbygget engelsk ordbog, tekst-til-tale og oversættelsesfunktioner — så du lettere kan lære engelsk udtale.

---

## Hovedfunktioner

- **Helsides IPA-tilstand** — Tilføj IPA-annoteringer til alle engelske ord på siden med ét klik; IPA-symboler er farvekodet efter type (vokaler, konsonanter, trykmarkeringer) for let læsning
- **Svæveordbog** — Hold musen over ord for at se engelske definitioner (82.000+ ord fra WordNet), IPA med farvekodede symboler og udtaleknapper; vælg mellem tilstandene Ordbog, Tooltip eller Fra
- **PDF-læser** — Indbygget PDF-læser med IPA-annoteringer, ordbog, tale og oversættelse; understøtter træk-og-slip, URL-indlæsning og automatisk PDF-detektion med smart omdirigering
- **Svage/stærke former** — Vis automatisk svage og stærke udtalevarianter af almindelige funktionsord (f.eks. "the", "to", "can") for at mestre naturlig sammenhængende tale
- **Amerikansk og britisk accent** — Skift mellem amerikansk engelsk (en-US) og britisk engelsk (en-GB) IPA
- **Tekst-til-tale** — Klik på højttalerknappen for at høre udtale, der matcher din valgte accent
- **Markeringstale med karaokeeffekt** — Markér enhver engelsk tekst; en kompakt værktøjslinje vises med tale- og oversættelsesknapper; tale afspilles med ord-for-ord-fremhævelse i realtid (karaokeeffekt) synkroniseret med lyden
- **Markeringsoversættelse** — Markér enhver tekst, klik på oversættelsesknappen på værktøjslinjen for øjeblikkelig oversættelse via Bing eller Google Translate vist i en inline-boble
- **Homograf-disambiguation** — Identificerer automatisk ord med flere udtaler (f.eks. "read", "live") og vælger den korrekte baseret på kontekst
- **Tastaturgenveje** — Hurtig adgang til kernefunktioner via tilpasselige tastaturgenveje
- **Flersproget grænseflade** — Understøtter 41 grænsefladesprog

---

## Sådan bruges det

### Trin 1: Installér udvidelsen

Installér **IPA Reader** fra [Chrome Web Store](https://chromewebstore.google.com/), eller indlæs den lokalt i udviklertilstand.

### Trin 2: Åbn en webside

Besøg en hvilken som helst webside med engelsk indhold.

### Trin 3: Aktivér IPA

Klik på udvidelsesikonet i din browsers værktøjslinje. Slå "Enable IPA" til, og slå derefter "Whole Page IPA" til for at annotere alle ord på siden. Du kan også klikke på den flydende knap nederst til højre.

### Trin 4: Se IPA

Hold musen over ord for at se IPA-tooltips med farvekodede fonetiske symboler. Klik på højttalerikonet for at høre udtalen. For ord med svage/stærke former viser tooltip begge varianter.

### Trin 5: Læs og oversæt markeret tekst

Markér enhver engelsk tekst med musen. En kompakt værktøjslinje vises nær markeringen med to knapper:
- **🔊 Tal** — Læser den markerede tekst højt med karaoke-lignende ord-for-ord-fremhævelse
- **🌐 Oversæt** — Viser en inline-oversættelsesboble under værktøjslinjen

Du kan også højreklikke og vælge "IPA Reader > Speak Selection" eller "IPA Reader > Translate Selection".

> **Tip:** Klik på udvidelsesikonet i din browsers værktøjslinje for at åbne indstillingspanelet og justere accenttype, talehastighed, svævetilstand, oversættelsesmotor og mere.

---

## Helsides IPA-tilstand

Når helsides IPA-tilstand er aktiveret, får hvert engelske ord på siden en IPA-annotering over sig med ruby-tekst. IPA-symbolerne er farvekodede for let læsning:

- **Vokaler** — fremhævet i blåt
- **Konsonanter** — vist i gråt
- **Trykmarkeringer** (ˈ ˌ) — fremhævet i rødt
- **Længdemarkeringer** (ː) — fremhævet i lilla

Udvidelsen justerer automatisk linjehøjde for at forhindre overlap mellem annoteringer og tekst og skalerer IPA-skriftstørrelse baseret på ordlængde for et rent layout.

---

## Svæveordbog

Udvidelsen indeholder en indbygget engelsk ordbog baseret på WordNet (mere end 82.000 ord). Du kan vælge mellem flere svævetilstande i indstillingerne:

| Tilstand | Adfærd |
|----------|--------|
| **Ordbog** | Svæv viser IPA + engelsk definition + udtaleknap |
| **Tooltip** | Svæv viser IPA + udtaleknap (ingen definitioner) |
| **Fra** | Ingen svæveeffekt |

I **Ordbog**-tilstand viser tooltip:
- Ordet og dets IPA-transkription
- En udtaleknap (klik for at høre)
- Engelske definitioner fra WordNet

> **Tip:** Ordbogsdata indlæses efter behov, når Ordbog-tilstand er aktiveret, og frigives ved skift til andre tilstande for at spare hukommelse.

---

## PDF-læser

IPA Reader indeholder en indbygget PDF-læser, så du kan læse PDF-dokumenter med IPA-annoteringer, ordbog, tale og oversættelse — de samme funktioner som på websider, nu også til PDF.

### Åbne en PDF

**Metode 1: Fra popup**  
Klik på udvidelsesikonet og derefter på "Open PDF Reader". Træk og slip en PDF-fil eller klik på "Choose File" for at åbne en lokal PDF. Du kan også indsætte en PDF-URL.

**Metode 2: Kontekstmenu**  
Højreklik på et `.pdf`-link på en webside og vælg "Open PDF with IPA Reader".

**Metode 3: Automatisk detektion**  
Når "PDF Smart Detection" er aktiveret i indstillingerne, omdirigerer udvidelsen automatisk `.pdf`-URL'er til den indbyggede læser. Når en PDF registreres uden omdirigering (f.eks. Chromes indbyggede fremviser), vises meddelelser og opfordringer til at åbne i IPA Reader.

### PDF-læserfunktioner

- **IPA-annoteringer** — Alle IPA-funktioner virker på PDF-tekst, herunder helsidestilstand og svævetooltips
- **Klikordbog** — Klik på et ord for at se definitionen (i PDF bruges klik i stedet for svæv for en rolig læseoplevelse)
- **Markeringsværktøjslinje** — Markér tekst for at tale, oversætte eller kopiere
- **Sidebjælke** — Indholdsfortegnelse og sideskabeloner
- **Søgning** — Søg efter tekst i PDF
- **Temaer** — Mørkt, lyst og sepia-læsetema
- **Zoom** — Flere zoomniveauer, herunder Auto, Side passer og Sidebredde
- **Tastaturgenveje** — Piletaster til navigation, +/- til zoom, Ctrl/Cmd+F til søgning

---

## Svage/stærke former

Mange almindelige engelske funktionsord har to udtaler:

- **Svag form** — den reducerede udtale i naturlig sammenhængende tale (f.eks. "the" → /ðə/)
- **Stærk form** — den fulde udtale til betoning eller isoleret (f.eks. "the" → /ðiː/)

Når "Show weak/strong forms" er aktiveret, viser hovering over disse ord begge varianter i tooltip mærket "WEAK" og "STRONG". Det hjælper dig med at forstå, hvordan udtale ændrer sig i naturlig tale.

Dækkede ord omfatter: artikler (the, a, an), præpositioner (to, for, of, from, at, as, than), konjunktioner (and, or, but), pronomen (you, your, her, him, his, them, us, our, there), hjælpeverber (am, is, are, was, were, been, can, could, would, should, must, shall, will, do, does, have, has, had) og mere.

---

## Markeringstale og karaoke

Markeringstalefunktionen giver dig mulighed for at markere enhver engelsk tekst og læse den højt med ét klik — perfekt til at lære sætningsudtale og læsepraksis.

**Metode 1: Markeringens værktøjslinje**  
Markér engelsk tekst med musen. En kompakt værktøjslinje vises med 🔊 tale- og 🌐 oversættelsesknap. Klik på tale for at afspille. Mens teksten læses, fremhæves hvert ord i realtid (karaokeeffekt).

**Metode 2: Højrekliksmenu**  
Når du har markeret engelsk tekst, højreklik og vælg "IPA Reader > Speak Selection".

**Metode 3: Tastaturgenvej**  
Markér tekst og tryk `Alt+Shift+S` (Mac: `Ctrl+Shift+S`) for at tale.

> **Tip:** Karaoke-fremhævelse fungerer bedst, når din browser understøtter TTS ordgrænse-hændelser. Hvis ikke understøttet, bruger udvidelsen et tidsbaseret fallback for jævn fremhævelse.

---

## Oversættelse

Markér enhver tekst på siden og brug oversættelsesfunktionen til øjeblikkelige oversættelser.

**Metode 1: Markeringens værktøjslinje**  
Markér tekst, og klik derefter på 🌐 oversættelsesknappen på værktøjslinjen. En oversættelsesboble vises nedenfor med resultatet og en kopier-knap.

**Metode 2: Højrekliksmenu**  
Markér tekst, højreklik og vælg "IPA Reader > Translate Selection".

**Metode 3: Tastaturgenvej**  
Markér tekst og tryk `Alt+Shift+T` (Mac: `Ctrl+Shift+T`) for at oversætte.

**Oversættelsesmotorer:**
- **Bing Translate** (standard) — Drevet af Microsoft Translator
- **Google Translate** — Drevet af Google

Begge motorer understøtter **108 målsprog**.

Du kan skifte oversættelsesmotor og målsprog i udvidelsesindstillingerne. Målsprog detekteres automatisk fra browserens sprog.

> **Tip:** Klik et vilkårligt sted uden for værktøjslinjen eller boblen for at lukke dem.

---

## Tastaturgenveje

| Genvej | Mac-genvej | Handling |
|--------|------------|----------|
| `Alt+Shift+I` | `Ctrl+Shift+I` | Slå IPA-annoteringer til/fra |
| `Alt+Shift+S` | `Ctrl+Shift+S` | Læs markeret tekst højt |
| `Alt+Shift+T` | `Ctrl+Shift+T` | Oversæt markeret tekst |

> **Tip:** Du kan tilpasse disse genveje i Chrome på `chrome://extensions/shortcuts`.

---

## Indstillingsvejledning

| Indstilling | Beskrivelse |
|-------------|-------------|
| **Aktivér IPA** | Hovedkontakt til at aktivere eller deaktivere IPA-annoteringsfunktionen |
| **Helsides IPA** | Når aktiveret, vises farvekodet IPA for alle engelske ord over teksten |
| **IPA Style** | Vælg mellem amerikansk og britisk engelsk IPA og udtale |
| **Svævetilstand** | Vælg adfærd ved svæv: Ordbog (IPA + definitioner + lyd), Tooltip (IPA + lyd), eller Fra |
| **Show weak/strong forms** | Vis svage og stærke udtalevarianter af almindelige funktionsord |
| **Sætningstalehasighed** | Justér hastigheden for sætningsoplæsning (enkelordstale påvirkes ikke) |
| **Translation Engine** | Vælg mellem Bing Translate og Google Translate |
| **Target Language** | Angiv oversættelsens målsprog (autodetekteret fra browsersprog) |
| **PDF Smart Detection** | Når aktiveret, omdirigeres PDF-URL'er automatisk til den indbyggede læser, og der vises meddelelser ved registrering af PDF |

---

## FAQ

**Sp: Hvorfor virker det ikke på nogle sider?**  
Sv: Af sikkerhedsmæssige årsager kan browserudvidelser ikke køre på specialsider som `chrome://`, browserindstillinger eller Chrome Web Store.

**Sp: Hvad hvis IPA mangler for nogle ord?**  
Sv: IPA-ordbogen dækker mere end 134.000 amerikanske og mere end 67.000 britiske engelske ord. For ord uden for ordbogen bruger udvidelsen lemmatisering og regelbaseret G2P til at generere omtrentlig IPA markeret med ≈ eller ~ i tooltip.

**Sp: Ingen lyd fra tekst-til-tale?**  
Sv: Kontrollér venligst dine systemlydindstillinger og sørg for, at engelske stemmepakker er installeret. Taleunderstøttelse varierer på tværs af browsere og operativsystemer.

**Sp: Helsidestilstand påvirker layout?**  
Sv: IPA-annoteringer kræver ekstra plads. Udvidelsen justerer automatisk linjehøjde for at minimere layoutpåvirkning. Hvis det stadig påvirker læsningen, deaktivér helsidestilstand og brug svævetooltips i stedet.

**Sp: Hvad betyder symbolerne ~ og ≈ i tooltips?**  
Sv: ~ betyder, at IPA er genereret af regelbaseret konvertering (G2P) snarere end fra ordbogen. ≈ betyder, at IPA er afledt af et beslægtet grundord via lemmatisering. Disse kan være mindre præcise end ordbogsopslag.

**Sp: Oversættelse virker ikke?**  
Sv: Oversættelse kræver internetforbindelse. Hvis Bing Translate fejler, kan du prøve at skifte til Google Translate i indstillingerne. Nogle netværksmiljøer kan blokere adgang til oversættelsestjenester.

**Sp: Hvordan åbner jeg en PDF med IPA Reader?**  
Sv: Du kan åbne PDF'er på flere måder: klik på "Open PDF Reader" i popup'en, højreklik på et PDF-link og vælg "Open PDF with IPA Reader", eller aktivér "PDF Smart Detection" i indstillingerne for automatisk at omdirigere PDF-URL'er til den indbyggede læser.

**Sp: PDF Smart Detection er aktiveret, men nogle PDF'er omdirigeres ikke?**  
Sv: Auto-omdirigering virker for URL'er, der ender på `.pdf`. For PDF'er uden `.pdf`-endelse eller vist i Chromes indbyggede fremviser vises en meddelelse og et badge, der opfordrer til at åbne i IPA Reader.

**Sp: Kan jeg bruge ordbogen offline?**  
Sv: Ja. WordNet-ordbogen (mere end 82.000 ord) er fuldt indlejret i udvidelsen. Alle opslag sker lokalt uden netværksforbindelse.

---

## Relaterede links

- [Privatlivspolitik](../privacy-policy)
- [Support og feedback](../support)

---
