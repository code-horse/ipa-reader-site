---
layout: bare
title: IPA Reader-udvidelse — Brugervejledning
lang: da
---

# IPA Reader — Brugervejledning

> Version: v1.2.0

## Introduktion

IPA Reader er en browserudvidelse designet til engelskstuderende. Den tilføjer IPA-udtaleannoteringer (International Phonetic Alphabet) til engelske ord på websider og understøtter både amerikansk og britisk engelsk, så du lettere kan lære engelsk udtale.

---

## Hovedfunktioner

- **Tekstmarkeringsannotering** — Markér engelsk tekst på websider for automatisk at vise IPA og taleknapper
- **Helsides IPA-tilstand** — Tilføj IPA-annoteringer til alle engelske ord på siden med ét klik, med farvekodede IPA-symboler (vokaler, konsonanter, trykmarkeringer) for let læsning
- **Amerikansk og britisk accent** — Skift mellem amerikansk engelsk (en-US) og britisk engelsk (en-GB) IPA
- **Tekst-til-tale** — Klik på højttalerknappen for at høre udtale, der matcher din valgte accent
- **Markeringstale** — Markér enhver engelsk tekst, klik på den flydende knap eller højreklik "Speak Selection" for at læse højt
- **Svævetooltips** — Hold musen over annoterede ord for at se IPA og udtaleknapper
- **Svage/stærke former** — Vis automatisk svage og stærke udtalevarianter af funktionsord (f.eks. the, to, can) for at mestre naturlig sammenhængende tale
- **Homograf-disambiguation** — Identificerer automatisk ord med flere udtaler (f.eks. read, live) og vælger den korrekte baseret på kontekst
- **Flersproget grænseflade** — Understøtter 38 grænsefladesprog

---

## Sådan bruges det

### Trin 1: Installér udvidelsen

Installér **IPA Reader** fra [Chrome Web Store](https://chromewebstore.google.com/), eller indlæs den lokalt i udviklertilstand.

### Trin 2: Åbn en webside

Besøg en hvilken som helst webside med engelsk indhold.

### Trin 3: Markér tekst eller brug den flydende knap

Markér den engelske tekst, du vil annotere, eller klik på den flydende knap nederst til højre for at aktivere helsides IPA-tilstand.

### Trin 4: Se IPA

Hold musen over ord for at se IPA-tooltips, klik på højttalerikonet for at høre udtalen.

### Trin 5: Oplæs markeret tekst

Markér enhver engelsk tekst med musen, klik på den flydende 🔊-knap for at læse op; eller højreklik og vælg "Speak Selection".

> **Tip:** Klik på udvidelsesikonet i din browsers værktøjslinje for at åbne indstillingspanelet og justere accenttype, talehastighed og mere.

---

## Markeringstale

Markeringstalefunktionen giver dig mulighed for at markere enhver engelsk tekst og læse den højt med ét klik — perfekt til at lære sætningsudtale og læsepraksis.

**Metode 1: Flydende knap**  
Markér engelsk tekst med musen, en højttalerknap vises øverst til højre for markeringen — klik for at tale.

**Metode 2: Højrekliksmenu**  
Når du har markeret engelsk tekst, højreklik og vælg "Speak Selection" fra menuen.

> **Tip:** Markeringstale bruger den sætningstalehasighed, der er konfigureret i dine indstillinger. Enkelordudtale bruger standardhastigheden. TTS-stemmen matcher din valgte accenttype (amerikansk eller britisk).

---

## Indstillingsvejledning

| Indstilling | Beskrivelse |
|-------------|-------------|
| **Aktivér IPA** | Hovedkontakt til at aktivere eller deaktivere IPA-annoteringsfunktionen |
| **Helsides IPA** | Når aktiveret, vises IPA for alle engelske ord (kan påvirke sidelayout) |
| **Accenttype** | Vælg mellem amerikansk engelsk og britisk engelsk IPA og udtale |
| **Sætningstalehasighed** | Justér hastigheden for sætningsoplæsning (enkelordstale påvirkes ikke) |
| **Svage/stærke former** | Vis svage og stærke udtalevarianter af funktionsord |
| **Svævetooltips** | Vis IPA-tooltip ved museover |

---

## FAQ

**Sp: Hvorfor virker det ikke på nogle sider?**  
Sv: Af sikkerhedsmæssige årsager kan browserudvidelser ikke køre på specialsider som `chrome://`, browserindstillinger eller Chrome Web Store.

**Sp: Hvad hvis IPA mangler for nogle ord?**  
Sv: IPA-ordbogen dækker almindelige engelske ord. For ord uden for ordbogen genererer udvidelsen tilnærmelsesvis IPA via lemmatisering og G2P, markeret med ≈ eller ~ i tooltip.

**Sp: Ingen lyd fra tekst-til-tale?**  
Sv: Kontrollér venligst dine systemlydindstillinger og sørg for, at engelske stemmepakker er installeret. Taleunderstøttelse varierer på tværs af browsere og operativsystemer.

**Sp: Helsidestilstand påvirker layout?**  
Sv: IPA-annoteringer kræver ekstra plads, hvilket kan påvirke det originale sidelayout. Hvis det påvirker læsningen, deaktivér helsidestilstand og brug svævetooltips i stedet.

**Sp: Hvad betyder symbolerne ~ og ≈ i tooltips?**  
Sv: ~ betyder, at IPA er genereret af regler (G2P), og ≈ betyder, at den er afledt af et beslægtet grundord. Disse kan være mindre præcise end ordbogsopslag.

---

## Relaterede links

- [Privatlivspolitik](../privacy-policy)
- [Support og feedback](../support)

---
