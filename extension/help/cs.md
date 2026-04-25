---
layout: bare
title: Rozšíření IPA Reader - Uživatelská příručka
lang: cs
---

# IPA Reader - Uživatelská příručka

> Verze: v1.4.4

## Úvod

IPA Reader je rozšíření prohlížeče určené pro studenty angličtiny. Přidává IPA (Mezinárodní fonetická abeceda) anotace výslovnosti k anglickým slovům na webových stránkách i v PDF, podporuje americký i britský anglický přízvuk. Obsahuje také vestavěný anglický slovník, převod textu na řeč a funkce překladu — vše vám pomáhá snadněji se učit anglickou výslovnost.

---

## Hlavní funkce

- **Režim IPA celé stránky** — Přidejte IPA anotace ke všem anglickým slovům na stránce jedním kliknutím; IPA symboly jsou barevně kódovány podle typu (samohlásky, souhlásky, přízvuky) pro snadné čtení
- **Slovník při najetí** — Najeďte na slova a uvidíte anglické definice (82 000+ slov z WordNetu), IPA s barevně kódovanými symboly a tlačítka výslovnosti; zvolte režim Slovník, Tooltip nebo Vypnuto
- **Čtečka PDF** — Vestavěná čtečka PDF s IPA anotacemi, slovníkem, řečí a překladem; podpora přetažení souboru, načtení z URL a automatická detekce PDF s chytrým přesměrováním
- **Slabé/silné formy** — Automatické zobrazení slabých a silných variant výslovnosti běžných funkčních slov (např. „the“, „to“, „can“) pro zvládnutí přirozené plynulé řeči
- **Americký a britský přízvuk** — Přepínejte mezi americkou angličtinou (en-US) a britskou angličtinou (en-GB) IPA
- **Text-to-Speech** — Klikněte na tlačítko reproduktoru pro přehrání výslovnosti podle zvoleného přízvuku
- **Řeč výběru s karaoke efektem** — Vyberte libovolný anglický text; zobrazí se kompaktní panel nástrojů s tlačítky pro mluvení a překlad; řeč se přehrává s zvýrazňováním slovo po slově v reálném čase (karaoke efekt) synchronizovaným se zvukem
- **Překlad výběru** — Vyberte libovolný text, klikněte na tlačítko překladu na panelu pro okamžitý překlad přes Bing nebo Google Translate zobrazený v inline bublině
- **Rozlišení homografů** — Automatická identifikace slov s více výslovnostmi (např. „read“, „live“) a výběr správné podle kontextu
- **Klávesové zkratky** — Rychlý přístup k hlavním funkcím pomocí přizpůsobitelných klávesových zkratek
- **Vícejazyčné rozhraní** — Podporuje 41 jazyků rozhraní

---

## Jak používat

### Krok 1: Nainstalovat rozšíření

Nainstalujte **IPA Reader** z [Chrome Web Store](https://chromewebstore.google.com/) nebo jej načtěte lokálně v režimu vývojáře.

### Krok 2: Otevřít libovolnou webovou stránku

Navštivte libovolnou webovou stránku obsahující anglický obsah.

### Krok 3: Zapnout IPA

Klikněte na ikonu rozšíření na liště prohlížeče. Zapněte „Enable IPA“, poté zapněte „Whole Page IPA“ pro anotaci všech slov na stránce. Můžete také kliknout na plovoucí tlačítko v pravém dolním rohu.

### Krok 4: Zobrazit IPA

Najeďte kurzorem nad slova pro zobrazení IPA tipů s barevně kódovanými fonetickými symboly. Klikněte na ikonu reproduktoru pro přehrání výslovnosti. U slov se slabými/silnými formami tip zobrazí obě varianty.

### Krok 5: Mluvit a překládat vybraný text

Vyberte libovolný anglický text myší. U výběru se zobrazí kompaktní panel nástrojů se dvěma tlačítky:
- **🔊 Mluvit** — Přečte vybraný text nahlas se zvýrazňováním slovo po slově ve stylu karaoke
- **🌐 Přeložit** — Zobrazí inline překladovou bublinu pod panelem

Můžete také kliknout pravým tlačítkem a zvolit „IPA Reader > Speak Selection“ nebo „IPA Reader > Translate Selection“.

> **Tip:** Kliknutím na ikonu rozšíření na liště prohlížeče otevřete panel nastavení a upravte typ přízvuku, rychlost přehrávání, režim najetí kurzoru, překladový engine a další.

---

## Režim IPA celé stránky

Když je zapnut režim IPA celé stránky, každé anglické slovo na stránce má IPA anotaci nad sebou pomocí ruby textu. IPA symboly jsou barevně kódovány pro snadné čtení:

- **Samohlásky** — zvýrazněny modře
- **Souhlásky** — zobrazeny šedě
- **Přízvuky** (ˈ ˌ) — zvýrazněny červeně
- **Délky** (ː) — zvýrazněny fialově

Rozšíření automaticky upravuje výšku řádku, aby se anotace nepřekrývaly s textem, a škáluje velikost IPA písma podle délky slova pro čisté rozvržení.

---

## Slovník při najetí

Rozšíření obsahuje vestavěný anglický slovník založený na WordNetu (více než 82 000 slov). V nastavení si můžete zvolit několik režimů při najetí kurzorem:

| Režim | Chování |
|------|---------|
| **Slovník** | Při najetí se zobrazí IPA + anglická definice + tlačítko výslovnosti |
| **Tooltip** | Při najetí se zobrazí IPA + tlačítko výslovnosti (bez definic) |
| **Vypnuto** | Žádný efekt při najetí |

V **režimu Slovník** tooltip zobrazuje:
- Slovo a jeho IPA přepis
- Tlačítko výslovnosti (kliknutím přehrajete)
- Anglické definice z WordNetu

> **Tip:** Data slovníku se načítají na vyžádání, když je zapnut režim Slovník, a uvolní se při přepnutí na jiné režimy kvůli úspoře paměti.

---

## Čtečka PDF

IPA Reader obsahuje vestavěnou čtečku PDF, ve které můžete číst dokumenty s IPA anotacemi, slovníkem, řečí a překladem — stejné funkce jako na webových stránkách, nyní i pro PDF.

### Otevření PDF

**Způsob 1: Z vyskakovacího okna**  
Klikněte na ikonu rozšíření a poté na „Open PDF Reader“. Přetáhněte soubor PDF nebo klikněte na „Choose File“ pro otevření lokálního PDF. Můžete také vložit URL adresu PDF.

**Způsob 2: Kontextové menu**  
Klikněte pravým tlačítkem na odkaz na `.pdf` na stránce a zvolte „Open PDF with IPA Reader“.

**Způsob 3: Automatická detekce**  
Když je v nastavení zapnuto „PDF Smart Detection“, rozšíření automaticky přesměruje URL končící na `.pdf` do vestavěné čtečky. Pokud je PDF rozpoznáno, ale nepřesměrováno (např. vestavěný prohlížeč Chrome), uvidíte upozornění a výzvu k otevření v IPA Readeru.

### Funkce čtečky PDF

- **IPA anotace** — Všechny funkce IPA fungují na textu v PDF včetně režimu celé stránky a tooltipů při najetí
- **Slovník kliknutím** — Kliknutím na slovo zobrazíte definici (v PDF se místo najetí používá kliknutí pro nerušivé čtení)
- **Panel výběru** — Vyberte text pro mluvení, překlad nebo kopírování
- **Postranní panel** — Obsah (obsah dokumentu) a náhledy stránek
- **Vyhledávání** — Hledání textu v PDF
- **Motivy** — Tmavý, světlý a sépiový motiv čtení
- **Lupa** — Úrovně přiblížení včetně Auto, Vejde se na stránku a Šířka stránky
- **Klávesové zkratky** — Šipky pro navigaci, +/- pro zoom, Ctrl/Cmd+F pro vyhledávání

---

## Slabé/silné formy

Mnoho běžných anglických funkčních slov má dvě výslovnosti:

- **Slabá forma** — redukovaná výslovnost v přirozené plynulé řeči (např. „the“ → /ðə/)
- **Silná forma** — plná výslovnost pro důraz nebo izolovaně (např. „the“ → /ðiː/)

Když je zapnuto „Show weak/strong forms“, najetím nad tato slova se v tipu zobrazí obě varianty označené jako „WEAK“ a „STRONG“. Pomáhá to pochopit, jak se výslovnost v přirozené řeči mění.

Pokrytá slova zahrnují: členy (the, a, an), předložky (to, for, of, from, at, as, than), spojky (and, or, but), zájmena (you, your, her, him, his, them, us, our, there), pomocná slovesa (am, is, are, was, were, been, can, could, would, should, must, shall, will, do, does, have, has, had) a další.

---

## Přehrání výběru a karaoke

Funkce přehrání výběru umožňuje vybrat libovolný anglický text a přečíst jej nahlas jedním kliknutím — ideální pro učení výslovnosti vět a čtecí praxi.

**Metoda 1: Panel nástrojů výběru**  
Vyberte anglický text myší. Zobrazí se kompaktní panel s tlačítkem 🔊 mluvit a tlačítkem 🌐 přeložit. Klikněte na mluvit pro přehrání. Během čtení se každé slovo zvýrazňuje v reálném čase (karaoke efekt).

**Metoda 2: Kontextové menu**  
Po výběru anglického textu klikněte pravým tlačítkem a zvolte „IPA Reader > Speak Selection“.

**Metoda 3: Klávesová zkratka**  
Vyberte text a stiskněte `Alt+Shift+S` (Mac: `Ctrl+Shift+S`) pro mluvení.

> **Tip:** Zvýrazňování ve stylu karaoke funguje nejlépe, když prohlížeč podporuje TTS události hranic slov. Pokud ne, rozšíření použije časově založený fallback pro plynulé zvýrazňování.

---

## Překlad

Vyberte libovolný text na stránce a použijte funkci překladu pro okamžité překlady.

**Metoda 1: Panel nástrojů výběru**  
Vyberte text, poté klikněte na tlačítko 🌐 přeložit na panelu. Pod ním se zobrazí překladová bublina s výsledkem a tlačítkem kopírování.

**Metoda 2: Kontextové menu**  
Vyberte text, klikněte pravým tlačítkem a zvolte „IPA Reader > Translate Selection“.

**Metoda 3: Klávesová zkratka**  
Vyberte text a stiskněte `Alt+Shift+T` (Mac: `Ctrl+Shift+T`) pro překlad.

**Překladové enginy:**
- **Bing Translate** (výchozí) — Provozováno Microsoft Translator
- **Google Translate** — Provozováno Google

Oba motory podporují **108 cílových jazyků**.

Překladový engine a cílový jazyk můžete změnit v nastavení rozšíření. Cílový jazyk se automaticky detekuje z jazyka prohlížeče.

> **Tip:** Kliknutím mimo panel nebo bublinu je zavřete.

---

## Klávesové zkratky

| Zkratka | Mac zkratka | Akce |
|---------|-------------|------|
| `Alt+Shift+I` | `Ctrl+Shift+I` | Zapnout/vypnout IPA anotace |
| `Alt+Shift+S` | `Ctrl+Shift+S` | Mluvit vybraný text |
| `Alt+Shift+T` | `Ctrl+Shift+T` | Přeložit vybraný text |

> **Tip:** Tyto zkratky můžete přizpůsobit v Chrome na `chrome://extensions/shortcuts`.

---

## Průvodce nastavením

| Nastavení | Popis |
|---------|-------------|
| **Povolit IPA** | Hlavní přepínač pro zapnutí nebo vypnutí funkce IPA anotace |
| **IPA celé stránky** | Při zapnutí zobrazuje barevně kódované IPA pro všechna anglická slova nad textem |
| **IPA Style** | Volba mezi americkou a britskou angličtinou IPA a výslovností |
| **Režim najetí** | Chování při najetí: Slovník (IPA + definice + zvuk), Tooltip (IPA + zvuk), Vypnuto |
| **Show weak/strong forms** | Zobrazení slabých a silných variant běžných funkčních slov |
| **Rychlost přehrávání vět** | Úprava rychlosti čtení vět (přehrání jednotlivých slov není ovlivněno) |
| **Translation Engine** | Volba mezi Bing Translate a Google Translate |
| **Target Language** | Nastavení cílového jazyka překladu (automaticky z jazyka prohlížeče) |
| **PDF Smart Detection** | Při zapnutí automaticky přesměruje URL PDF do vestavěné čtečky a zobrazí upozornění při detekci PDF |

---

## Časté dotazy

**Q: Proč to na některých stránkách nefunguje?**  
A: Z bezpečnostních důvodů se rozšíření prohlížeče nemohou spouštět na speciálních stránkách jako `chrome://`, nastavení prohlížeče nebo Chrome Web Store.

**Q: Co když IPA chybí u některých slov?**  
A: IPA slovník pokrývá více než 134 000 amerických a více než 67 000 britských anglických slov. Pro slova mimo slovník rozšíření používá lematizaci a pravidlové G2P (grafém–foném) pro přibližné IPA. V tooltipu jsou označena ≈ nebo ~.

**Q: Žádný zvuk z text-to-speech?**  
A: Zkontrolujte nastavení hlasitosti systému a ověřte, že máte nainstalované anglické hlasové balíčky. Podpora řeči se liší v různých prohlížečích a operačních systémech.

**Q: Režim celé stránky ovlivňuje rozložení?**  
A: IPA anotace vyžadují dodatečný prostor. Rozšíření automaticky upravuje výšku řádku, aby minimalizovalo dopad na rozložení. Pokud stále ovlivňuje čtení, vypněte režim celé stránky a místo toho použijte tipy při najetí kurzorem.

**Q: Co znamenají symboly ~ a ≈ v nápovědách?**  
A: ~ znamená, že IPA byla vygenerována pravidlovou konverzí (G2P), nikoli ze slovníku. ≈ znamená, že IPA byla odvozena z příbuzného základního slova lematizací. Mohou být méně přesné než slovníkové záznamy.

**Q: Překlad nefunguje?**  
A: Překlad vyžaduje připojení k internetu. Pokud Bing Translate selže, zkuste v nastavení přepnout na Google Translate. Některá síťová prostředí mohou blokovat přístup k překladovým službám.

**Q: Jak otevřu PDF v IPA Readeru?**  
A: PDF můžete otevřít několika způsoby: v rozbalovacím okně klikněte na „Open PDF Reader“, klikněte pravým tlačítkem na odkaz na PDF a zvolte „Open PDF with IPA Reader“, nebo v nastavení zapněte „PDF Smart Detection“ pro automatické přesměrování URL PDF do vestavěné čtečky.

**Q: PDF Smart Detection je zapnuto, ale některá PDF se nepřesměrují?**  
A: Automatické přesměrování funguje pro URL končící na `.pdf`. U PDF servírovaných bez přípony `.pdf` nebo zobrazených ve vestavěném prohlížeči Chrome uvidíte upozornění a odznak s výzvou k otevření v IPA Readeru.

**Q: Lze používat slovník offline?**  
A: Ano. Slovník WordNet (více než 82 000 slov) je plně součástí rozšíření. Všechna vyhledávání probíhají lokálně bez připojení k internetu.

---

## Související odkazy

- [Zásady ochrany osobních údajů](../privacy-policy)
- [Podpora a zpětná vazba](../support)

---
