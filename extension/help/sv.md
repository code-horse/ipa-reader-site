---
layout: bare
title: IPA Reader-tillägg — Användarhandbok
lang: sv
---

# IPA Reader - Användarhandbok

> Version: v1.3.0

## Introduktion

IPA Reader är ett webbläsartillägg utformat för engelsklärande. Det lägger till IPA (Internationella fonetiska alfabetet) uttalsannotationer till engelska ord på webbsidor, med stöd för både amerikansk och brittisk accent, vilket hjälper dig att lära dig engelskt uttal lättare.

---

## Huvudfunktioner

- **Hela sidan IPA-läge** — Lägg till IPA-annotationer till alla engelska ord på sidan med ett klick; IPA-symbolerna är färgkodade efter typ (vokaler, konsonanter, betoningstecken) för enkel läsning
- **Svaga/starka former** — Visa automatiskt svaga och starka uttalsvarianter av vanliga funktionsord (t.ex. „the“, „to“, „can“) för att bemästra naturligt sammanhängande tal
- **Amerikansk & brittisk accent** — Växla mellan amerikansk engelska (en-US) och brittisk engelska (en-GB) IPA
- **Text-to-Speech** — Klicka på högtalarknappen för att höra uttal som matchar din valda accent
- **Markeringstal med karaokeeffekt** — Markera valfri engelsk text; en kompakt verktygsrad visas med tal- och översättningsknappar; uppspelning sker med markering ord för ord i realtid (karaokeeffekt) synkad med ljudet
- **Markeringsöversättning** — Markera valfri text, klicka på översättningsknappen i verktygsraden för omedelbar översättning via Bing eller Google Translate, visad i en inline-bubbla
- **Hover-verktygstips** — Håll muspekaren över annoterade ord för att se IPA med färgkodade symboler och uttalsknappar
- **Homografigenkänning** — Automatisk identifiering av ord med flera uttal (t.ex. „read“, „live“) och val av rätt uttal baserat på kontext
- **Tangentbordsgenvägar** — Snabb åtkomst till kärnfunktioner via anpassningsbara genvägar
- **Flerspråkigt gränssnitt** — Stödjer 38 gränssnittsspråk

---

## Så använder du

### Steg 1: Installera tillägget

Installera **IPA Reader** från [Chrome Web Store](https://chromewebstore.google.com/), eller ladda det lokalt i utvecklarläge.

### Steg 2: Öppna valfri webbsida

Besök valfri webbsida med engelskt innehåll.

### Steg 3: Aktivera IPA

Klicka på tilläggsikonen i webbläsarens verktygsfält. Slå på „Aktivera IPA“, sedan „Hela sidan IPA“ för att annotera alla ord på sidan. Du kan också klicka på den flytande knappen nere till höger.

### Steg 4: Visa IPA

Håll muspekaren över ord för att se IPA-verktygstips med färgkodade fonetiska symboler. Klicka på högtalarikonen för att höra uttal. För ord med svaga/starka former visar verktygstipset båda varianterna.

### Steg 5: Tala och översätt markerad text

Markera valfri engelsk text med musen. En kompakt verktygsrad visas nära markeringen med två knappar:
- **🔊 Tala** — Läser den markerade texten högt med karaoke-liknande ord-för-ord markering
- **🌐 Översätt** — Visar en inline översättningsbubbla under verktygsraden

Du kan också högerklicka och välja „IPA Reader > Speak Selection“ eller „IPA Reader > Translate Selection“.

> **Tips:** Klicka på tilläggsikonen i webbläsarens verktygsfält för att öppna inställningspanelen och justera accenttyp, talhastighet, översättningsmotor med mera.

---

## Hela sidan IPA-läge

När hela sidan IPA-läge är aktiverat får varje engelskt ord på sidan en IPA-annotation ovanför sig med ruby-text. IPA-symbolerna är färgkodade för enkel läsning:

- **Vokaler** — markerade i blått
- **Konsonanter** — visade i grått
- **Betoningstecken** (ˈ ˌ) — markerade i rött
- **Längdtecken** (ː) — markerade i lila

Tillägget justerar automatiskt radhöjden så att annotationerna inte överlappar texten och skalar IPA-teckenstorleken efter ordlängd för en ren layout.

---

## Svaga/starka former

Många vanliga engelska funktionsord har två uttal:

- **Svag form** — det reducerade uttalet i naturligt sammanhängande tal (t.ex. „the“ → /ðə/)
- **Stark form** — det fulla uttalet vid betoning eller isolerat (t.ex. „the“ → /ðiː/)

När „Visa svaga/starka former“ är aktiverat visar verktygstipset båda varianterna för dessa ord, märkta „WEAK“ och „STRONG“. Det hjälper dig förstå hur uttal förändras i naturligt tal.

Täckta ord inkluderar: artiklar (the, a, an), prepositioner (to, for, of, from, at, as, than), konjunktioner (and, or, but), pronomen (you, your, her, him, his, them, us, our, there), hjälpverb (am, is, are, was, were, been, can, could, would, should, must, shall, will, do, does, have, has, had) med mera.

---

## Markeringstal och karaoke

Funktionen markeringstal låter dig markera valfri engelsk text och läsa den högt med ett klick — perfekt för att lära sig meningsuttal och läsoövning.

**Metod 1: Markeringsverktygsrad**  
Markera engelsk text med musen. En kompakt verktygsrad visas nära markeringen med 🔊 tala-knapp och 🌐 översättningsknapp. Klicka på tala-knappen för uppspelning. Medan texten läses högt markeras varje ord i realtid (karaokeeffekt), vilket hjälper dig följa med.

**Metod 2: Högerklicksmeny**  
Efter att ha markerat engelsk text, högerklicka och välj „IPA Reader > Speak Selection“.

**Metod 3: Tangentbordsgenväg**  
Markera text och tryck `Alt+Shift+S` (Mac: `Ctrl+Shift+S`) för att tala.

> **Tips:** Karaoke-markering fungerar bäst när webbläsaren stöder TTS ordgränshändelser. Om det inte stöds använder tillägget en tidsbaserad reserv för jämn markering.

---

## Översättning

Markera valfri text på sidan och använd översättningsfunktionen för omedelbara översättningar.

**Metod 1: Markeringsverktygsrad**  
Markera text, klicka sedan på 🌐 översättningsknappen i verktygsraden. En översättningsbubbla visas under med resultatet och en kopieringsknapp.

**Metod 2: Högerklicksmeny**  
Markera text, högerklicka och välj „IPA Reader > Translate Selection“.

**Metod 3: Tangentbordsgenväg**  
Markera text och tryck `Alt+Shift+T` (Mac: `Ctrl+Shift+T`) för att översätta.

**Översättningsmotorer:**
- **Bing Translate** (standard) — drivs av Microsoft Translator
- **Google Translate** — drivs av Google

Båda motorerna stöder **108 målspråk**.

Du kan byta översättningsmotor och målspråk i tilläggsinställningarna. Målspråket identifieras automatiskt från webbläsarspråket.

> **Tips:** Klicka utanför verktygsraden eller bubblan för att stänga dem.

---

## Tangentbordsgenvägar

| Genväg | Mac-genväg | Åtgärd |
|----------|-------------|--------|
| `Alt+Shift+I` | `Ctrl+Shift+I` | Växla IPA-annotationer av/på |
| `Alt+Shift+S` | `Ctrl+Shift+S` | Tala markerad text |
| `Alt+Shift+T` | `Ctrl+Shift+T` | Översätt markerad text |

> **Tips:** Du kan anpassa dessa genvägar i Chrome på `chrome://extensions/shortcuts`.

---

## Inställningsguide

| Inställning | Beskrivning |
|---------|-------------|
| **Aktivera IPA** | Huvudströmbrytare för att aktivera eller inaktivera IPA-annotationsfunktionen |
| **Hela sidan IPA** | När aktiverat visas färgkodad IPA för alla engelska ord ovanför texten |
| **IPA-stil** | Välj mellan amerikansk engelska och brittisk engelska IPA och uttal |
| **Visa hover-verktygstips** | Visa IPA-verktygstips med uttalsknapp vid muspekare |
| **Visa svaga/starka former** | Visa svaga och starka uttalsvarianter av vanliga funktionsord |
| **Meningsuppläsningshastighet** | Justera hastigheten för meningsläsning (enskilde ordutal påverkas inte) |
| **Översättningsmotor** | Välj mellan Bing Translate och Google Translate |
| **Målspråk** | Ange översättningens målspråk (automatiskt från webbläsarspråk) |

---

## FAQ

**F: Varför fungerar det inte på vissa sidor?**  
S: Av säkerhetsskäl kan webbläsartillägg inte köras på specialsidor som `chrome://`, webbläsarinställningar eller Chrome Web Store.

**F: Vad om IPA saknas för vissa ord?**  
S: IPA-ordboken täcker vanliga engelska ord. För ord utanför ordboken genererar tillägget ungefärlig IPA via lemmatisering och regelbaserad G2P (grafem–fonem). Detta markeras med ≈ eller ~ i verktygstipset.

**F: Inget ljud från text-to-speech?**  
S: Kontrollera dina systemvolyminställningar och se till att engelska röstpaket är installerade. Talstöd varierar mellan webbläsare och operativsystem.

**F: Hela sidan-läge påverkar layout?**  
S: IPA-annotationer kräver extra utrymme. Tillägget justerar automatiskt radhöjden för att minimera layoutpåverkan. Om det fortfarande påverkar läsningen, inaktivera hela sidan-läge och använd hover-verktygstips istället.

**F: Vad betyder symbolerna ~ och ≈ i verktygstipsen?**  
S: ~ betyder att IPA har genererats med regelbaserad konvertering (G2P) i stället från ordboken. ≈ betyder att IPA härletts från ett besläktat grundord via lemmatisering. Dessa kan vara mindre exakta än ordboksuppgifter.

**F: Översättning fungerar inte?**  
S: Översättning kräver internetanslutning. Om Bing Translate misslyckas, prova att byta till Google Translate i inställningarna. Vissa nätverk kan blockera åtkomst till översättningstjänster.

---

## Relaterade länkar

- [Privacy Policy](../privacy-policy)
- [Support & Feedback](../support)

---
