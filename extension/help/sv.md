---
layout: bare
title: IPA Reader-tillägg — Användarhandbok
lang: sv
---

# IPA Reader - Användarhandbok

> Version: v1.4.0

## Introduktion

IPA Reader är ett webbläsartillägg utformat för engelsklärande. Det lägger till IPA (Internationella fonetiska alfabetet) uttalsannotationer till engelska ord på webbsidor och i PDF-filer, med stöd för både amerikansk och brittisk accent. Det inkluderar också en inbyggd engelsk ordbok, text-till-tal och översättning — vilket hjälper dig att lära dig engelskt uttal lättare.

---

## Huvudfunktioner

- **Hela sidan IPA-läge** — Lägg till IPA-annotationer till alla engelska ord på sidan med ett klick; IPA-symbolerna är färgkodade efter typ (vokaler, konsonanter, betoningstecken) för enkel läsning
- **Ordbok vid hovring** — Håll muspekaren över ord för att se engelska definitioner (över 82 000 ord från WordNet), IPA med färgkodade symboler och uttalsknappar; välj mellan Ordboksläge, Verktygstipsläge, Endast tal-läge eller Av
- **PDF-läsare** — Inbyggd PDF-läsare med IPA-annotationer, ordbok, tal och översättning; stöd för dra och släpp, URL-inläsning och automatisk PDF-detektering med smart omdirigering
- **Svaga/starka former** — Visa automatiskt svaga och starka uttalsvarianter av vanliga funktionsord (t.ex. „the“, „to“, „can“) för att bemästra naturligt sammanhängande tal
- **Amerikansk & brittisk accent** — Växla mellan amerikansk engelska (en-US) och brittisk engelska (en-GB) IPA
- **Text-to-Speech** — Klicka på högtalarknappen för att höra uttal som matchar din valda accent
- **Markeringstal med karaokeeffekt** — Markera valfri engelsk text; en kompakt verktygsrad visas med tal- och översättningsknappar; uppspelning sker med markering ord för ord i realtid (karaokeeffekt) synkad med ljudet
- **Markeringsöversättning** — Markera valfri text, klicka på översättningsknappen i verktygsraden för omedelbar översättning via Bing eller Google Translate, visad i en inline-bubbla
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

> **Tips:** Klicka på tilläggsikonen i webbläsarens verktygsfält för att öppna inställningspanelen och justera accenttyp, talhastighet, hover-läge, översättningsmotor med mera.

---

## Hela sidan IPA-läge

När hela sidan IPA-läge är aktiverat får varje engelskt ord på sidan en IPA-annotation ovanför sig med ruby-text. IPA-symbolerna är färgkodade för enkel läsning:

- **Vokaler** — markerade i blått
- **Konsonanter** — visade i grått
- **Betoningstecken** (ˈ ˌ) — markerade i rött
- **Längdtecken** (ː) — markerade i lila

Tillägget justerar automatiskt radhöjden så att annotationerna inte överlappar texten och skalar IPA-teckenstorleken efter ordlängd för en ren layout.

---

## Ordbok vid hovring

Tillägget inkluderar en inbyggd engelsk ordbok baserad på WordNet (över 82 000 ord). Du kan välja mellan flera hover-lägen i inställningarna:

| Läge | Beteende |
|------|----------|
| **Ordbok** | Hover visar IPA + engelsk definition + uttalsknapp |
| **Verktygstips** | Hover visar IPA + uttalsknapp (inga definitioner) |
| **Endast tal** | Klicka på ett ord för att höra uttal (inget verktygstips) |
| **Av** | Ingen hover-effekt |

I **Ordboksläge** visar verktygstipset:
- ordet och dess IPA-transkription
- en uttalsknapp (klicka för att höra)
- engelska definitioner från WordNet

> **Tips:** Ordboksdata laddas vid behov när Ordboksläge är aktiverat och avlastas när du byter till andra lägen för att spara minne.

---

## PDF-läsare

IPA Reader inkluderar en inbyggd PDF-läsare så att du kan läsa PDF-dokument med IPA-annotationer, ordbok, tal och översättning — samma funktioner som på webbsidor, nu även för PDF.

### Öppna en PDF

**Metod 1: Från popupen**  
Klicka på tilläggsikonen och sedan „Öppna PDF-läsare“. Dra och släpp en PDF-fil eller klicka „Välj fil“ för att öppna en lokal PDF. Du kan också klistra in en PDF-URL.

**Metod 2: Snabbmeny**  
Högerklicka på en `.pdf`-länk på en webbsida och välj „Öppna PDF med IPA Reader“.

**Metod 3: Automatisk detektering**  
När „Smart PDF-detektering“ är aktiverat i inställningarna omdirigerar tillägget automatiskt `.pdf`-URL:er till den inbyggda läsaren. Om en PDF upptäcks men inte omdirigeras (t.ex. Chromes inbyggda visare) visas aviseringar och uppmaningar att öppna i IPA Reader.

### Funktioner i PDF-läsaren

- **IPA-annotationer** — Alla IPA-funktioner fungerar på PDF-text, inklusive hela sidan-läge och hover-verktygstips
- **Klickordbok** — Klicka på ett ord för att se definitionen (i PDF används klick i stället för hover för störningsfri läsning)
- **Markeringsverktygsrad** — Markera text för att tala, översätta eller kopiera
- **Sidopanel** — Innehållsförteckning och miniatyrer av sidor
- **Sök** — Sök text i PDF, inklusive pinyin-till-tecken-sökning för kinesiska PDF
- **Teman** — Mörkt, ljust och sepia-lästeman
- **Zoom** — Flera zoomnivåer inklusive Auto, Anpassa sida och Sidbredd
- **Tangentbordsgenvägar** — Piltangenter för navigering, +/- för zoom, Ctrl/Cmd+F för sökning

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
| **Hover-läge** | Välj hover-beteende: Ordbok (IPA + definitioner + ljud), Verktygstips (IPA + ljud), Endast tal (klicka för att höra) eller Av |
| **Visa svaga/starka former** | Visa svaga och starka uttalsvarianter av vanliga funktionsord |
| **Meningsuppläsningshastighet** | Justera hastigheten för meningsläsning (enskilde ordutal påverkas inte) |
| **Översättningsmotor** | Välj mellan Bing Translate och Google Translate |
| **Målspråk** | Ange översättningens målspråk (automatiskt från webbläsarspråk) |
| **Smart PDF-detektering** | När aktiverat omdirigeras PDF-URL:er automatiskt till den inbyggda läsaren och aviseringar visas när PDF upptäcks |

---

## FAQ

**F: Varför fungerar det inte på vissa sidor?**  
S: Av säkerhetsskäl kan webbläsartillägg inte köras på specialsidor som `chrome://`, webbläsarinställningar eller Chrome Web Store.

**F: Vad om IPA saknas för vissa ord?**  
S: IPA-ordboken täcker över 134 000 amerikanska och över 67 000 brittiska engelska ord. För ord utanför ordboken genererar tillägget ungefärlig IPA via lemmatisering och regelbaserad G2P (grafem–fonem). Detta markeras med ≈ eller ~ i verktygstipset.

**F: Inget ljud från text-to-speech?**  
S: Kontrollera dina systemvolyminställningar och se till att engelska röstpaket är installerade. Talstöd varierar mellan webbläsare och operativsystem.

**F: Hela sidan-läge påverkar layout?**  
S: IPA-annotationer kräver extra utrymme. Tillägget justerar automatiskt radhöjden för att minimera layoutpåverkan. Om det fortfarande påverkar läsningen, inaktivera hela sidan-läge och använd hover-verktygstips istället.

**F: Vad betyder symbolerna ~ och ≈ i verktygstipsen?**  
S: ~ betyder att IPA har genererats med regelbaserad konvertering (G2P) i stället från ordboken. ≈ betyder att IPA härletts från ett besläktat grundord via lemmatisering. Dessa kan vara mindre exakta än ordboksuppgifter.

**F: Översättning fungerar inte?**  
S: Översättning kräver internetanslutning. Om Bing Translate misslyckas, prova att byta till Google Translate i inställningarna. Vissa nätverk kan blockera åtkomst till översättningstjänster.

**F: Hur öppnar jag en PDF med IPA Reader?**  
S: Du kan öppna PDF på flera sätt: klicka „Öppna PDF-läsare“ i popupen, högerklicka på en PDF-länk och välj „Öppna PDF med IPA Reader“, eller aktivera „Smart PDF-detektering“ i inställningarna för att automatiskt omdirigera PDF-URL:er till den inbyggda läsaren.

**F: Smart PDF-detektering är aktiverad men vissa PDF omdirigeras inte?**  
S: Auto-omdirigering fungerar för URL:er som slutar på `.pdf`. För PDF som levereras utan `.pdf`-ändelse eller visas i Chromes inbyggda visare visas en avisering och en bricka som uppmanar dig att öppna i IPA Reader.

**F: Kan jag använda ordboken offline?**  
S: Ja. WordNet-ordboken (över 82 000 ord) är fullt inbunden i tillägget. Alla uppslag görs lokalt utan nätverksanslutning.

---

## Relaterade länkar

- [Privacy Policy](../privacy-policy)
- [Support & Feedback](../support)

---
