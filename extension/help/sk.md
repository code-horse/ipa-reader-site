---
layout: bare
title: Rozšírenie IPA Reader - Používateľská príručka
lang: sk
---

# IPA Reader - Používateľská príručka

> Verzia: v1.4.0

## Úvod

IPA Reader je rozšírenie prehliadača určené pre študentov angličtiny. Pridáva IPA (Medzinárodná fonetická abeceda) anotácie výslovnosti k anglickým slovám na webových stránkach a v PDF súboroch, podporuje americký aj britský anglický prízvuk. Obsahuje aj vstavaný anglický slovník, prevod textu na reč a funkcie prekladu — pomáha vám ľahšie sa učiť anglickú výslovnosť.

---

## Hlavné funkcie

- **Režim IPA celej stránky** — Pridajte IPA anotácie ku všetkým anglickým slovám na stránke jedným kliknutím; IPA symboly sú farebne kódované podľa typu (samohlásky, spoluhlásky, prízvuky) pre ľahké čítanie
- **Slovník pri najetí** — Najedením kurzora nad slová zobrazíte anglické definície (viac ako 82 000 slov z WordNet), IPA s farebne kódovanými symbolmi a tlačidlá výslovnosti; vyberte režim Slovník, Tooltip, Len prehrať alebo Vypnuté
- **Čítačka PDF** — Vstavaná čítačka PDF s IPA anotáciami, slovníkom, rečou a prekladom; podporuje pretiahnutie súborov, načítanie z URL a automatickú detekciu PDF so smart presmerovaním
- **Slabé/silné formy** — Automatické zobrazenie slabých a silných variantov výslovnosti bežných funkčných slov (napr. „the“, „to“, „can“) na zvládnutie prirodzenej plynulej reči
- **Americký a britský prízvuk** — Prepínajte medzi americkou angličtinou (en-US) a britskou angličtinou (en-GB) IPA
- **Text-to-Speech** — Kliknite na tlačidlo reproduktora pre prehratie výslovnosti podľa zvoleného prízvuku
- **Prehrávanie výberu s karaoke efektom** — Vyberte ľubovoľný anglický text; zobrazí sa kompaktný panel s tlačidlami pre prehrávanie a preklad; prehrávanie prebieha so zvýraznením slovo po slove v reálnom čase (karaoke efekt) synchronizovaným s audio
- **Preklad výberu** — Vyberte ľubovoľný text, kliknite na tlačidlo prekladu na paneli pre okamžitý preklad cez Bing alebo Google Translate zobrazený v inline bublinke
- **Rozlíšenie homografov** — Automatická identifikácia slov s viacerými výslovnosťami (napr. „read“, „live“) a výber správnej podľa kontextu
- **Klávesové skratky** — Rýchly prístup k hlavným funkciám cez prispôsobiteľné klávesové skratky
- **Viacjazyčné rozhranie** — Podporuje 38 jazykov rozhrania

---

## Ako používať

### Krok 1: Nainštalovať rozšírenie

Nainštalujte **IPA Reader** z [Chrome Web Store](https://chromewebstore.google.com/) alebo ho načítajte lokálne v režime vývojára.

### Krok 2: Otvoriť ľubovoľnú webovú stránku

Navštívte ľubovoľnú webovú stránku obsahujúcu anglický obsah.

### Krok 3: Zapnúť IPA

Kliknite na ikonu rozšírenia na lište prehliadača. Zapnite „Povoliť IPA“, potom „IPA celej stránky“ na anotovanie všetkých slov na stránke. Môžete tiež kliknúť na plávajúce tlačidlo v pravom dolnom rohu.

### Krok 4: Zobraziť IPA

Najedte kurzorom nad slová pre zobrazenie IPA tipov s farebne kódovanými fonetickými symbolmi. Kliknite na ikonu reproduktora pre prehratie výslovnosti. Pri slovách so slabými/silnými formami tip zobrazí obe varianty.

### Krok 5: Prehrať a preložiť vybraný text

Vyberte ľubovoľný anglický text myšou. Zobrazí sa kompaktný panel pri výbere s dvoma tlačidlami:
- **🔊 Prehrať** — Prečíta vybraný text nahlas so zvýraznením slovo po slove v štýle karaoke
- **🌐 Preložiť** — Zobrazí inline bublinu s prekladom pod panelom

Môžete tiež kliknúť pravým tlačidlom a zvoliť „IPA Reader > Speak Selection“ alebo „IPA Reader > Translate Selection“.

> **Tip:** Kliknutím na ikonu rozšírenia na lište prehliadača otvoríte panel nastavení a upravíte typ prízvuku, rýchlosť prehrávania, režim pri najetí, prekladový engine a ďalšie.

---

## Režim IPA celej stránky

Keď je zapnutý režim IPA celej stránky, každé anglické slovo na stránke dostane IPA anotáciu nad sebou pomocou ruby textu. IPA symboly sú farebne kódované pre ľahké čítanie:

- **Samohlásky** — zvýraznené modrou
- **Spoluhlásky** — zobrazené sivou
- **Prízvuky** (ˈ ˌ) — zvýraznené červenou
- **Dĺžkové značky** (ː) — zvýraznené fialovou

Rozšírenie automaticky upravuje výšku riadku, aby sa anotácie neprekrývali s textom, a škáluje veľkosť písma IPA podľa dĺžky slova pre čisté rozloženie.

---

## Slovník pri najetí

Rozšírenie obsahuje vstavaný anglický slovník založený na WordNet (viac ako 82 000 slov). V nastaveniach si môžete vybrať z viacerých režimov pri najetí:

| Režim | Správanie |
|-------|-----------|
| **Slovník** | Pri najetí: IPA + anglická definícia + tlačidlo výslovnosti |
| **Tooltip** | Pri najetí: IPA + tlačidlo výslovnosti (bez definícií) |
| **Len prehrať** | Kliknutím na slovo počujete výslovnosť (bez tooltipu) |
| **Vypnuté** | Žiadny efekt pri najetí |

V **režime Slovník** tooltip zobrazuje:
- Slovo a jeho IPA prepis
- Tlačidlo výslovnosti (kliknutím prehráte)
- Anglické definície z WordNet

> **Tip:** Dáta slovníka sa načítajú na požiadanie, keď je aktívny režim Slovník, a uvoľnia sa pri prepnutí na iné režimy, aby sa šetrila pamäť.

---

## Čítačka PDF

IPA Reader obsahuje vstavanú čítačku PDF, ktorá umožňuje čítať dokumenty PDF s IPA anotáciami, slovníkom, rečou a prekladom — rovnaké funkcie ako na webových stránkach, teraz aj pre PDF.

### Otvorenie PDF

**Metóda 1: Z popupu**  
Kliknite na ikonu rozšírenia a potom na „Otvoriť čítačku PDF“. Pretiahnite PDF súbor alebo kliknite na „Vybrať súbor“ pre otvorenie lokálneho PDF. Môžete tiež vložiť URL PDF.

**Metóda 2: Kontextové menu**  
Kliknite pravým tlačidlom na odkaz `.pdf` na stránke a zvoľte „Otvoriť PDF v IPA Reader“.

**Metóda 3: Automatická detekcia**  
Keď je v nastaveniach zapnutá „Inteligentná detekcia PDF“, rozšírenie automaticky presmeruje URL končiace na `.pdf` do vstavanej čítačky. Ak je PDF zistené, ale nepresmeruje sa (napr. vstavaný prehliadač Chrome), zobrazia sa upozornenia a výzvy na otvorenie v IPA Reader.

### Funkcie čítačky PDF

- **IPA anotácie** — Všetky IPA funkcie fungujú na texte PDF vrátane režimu celej stránky a tooltipov pri najetí
- **Slovník kliknutím** — Kliknutím na ľubovoľné slovo zobrazíte definíciu (v PDF sa namiesto hover používa klik pre nerušené čítanie)
- **Panel výberu** — Vyberte text na prehratie, preklad alebo kopírovanie
- **Bočný panel** — Obsah a miniatúry strán
- **Vyhľadávanie** — Vyhľadávanie textu v PDF vrátane vyhľadávania pinyin–znak pre čínske PDF
- **Motívy** — Čítacie motívy Tmavý, Svetlý a Sépiový
- **Priblíženie** — Viaceré úrovne vrátane Automaticky, Prispôsobiť stránku a Šírka stránky
- **Klávesové skratky** — Šípky na navigáciu, +/- na zoom, Ctrl/Cmd+F na vyhľadávanie

---

## Slabé/silné formy

Mnohé bežné anglické funkčné slová majú dve výslovnosti:

- **Slabá forma** — zredukovaná výslovnosť v prirodzenej plynulej reči (napr. „the“ → /ðə/)
- **Silná forma** — plná výslovnosť pri dôraze alebo izolovane (napr. „the“ → /ðiː/)

Keď je zapnuté „Zobraziť slabé/silné formy“, pri najetí na tieto slová tip zobrazí obe varianty označené ako „WEAK“ a „STRONG“. Pomáha to pochopiť, ako sa výslovnosť mení v prirodzenej reči.

Zahrnuté slová zahŕňajú: členy (the, a, an), predložky (to, for, of, from, at, as, than), spojky (and, or, but), zámená (you, your, her, him, his, them, us, our, there), pomocné slovesá (am, is, are, was, were, been, can, could, would, should, must, shall, will, do, does, have, has, had) a ďalšie.

---

## Prehrávanie výberu a karaoke

Funkcia prehrávania výberu vám umožňuje vybrať ľubovoľný anglický text a prečítať ho nahlas jedným kliknutím — ideálne pre učenie výslovnosti viet a čitateľskú prax.

**Metóda 1: Panel výberu**  
Vyberte anglický text myšou. Zobrazí sa kompaktný panel pri výbere s tlačidlom 🔊 pre prehrávanie a tlačidlom 🌐 pre preklad. Kliknite na tlačidlo pre prehrávanie. Počas čítania nahlas sa každé slovo v reálnom čase zvýrazní (karaoke efekt), čo pomáha sledovať text.

**Metóda 2: Kontextové menu**  
Po výbere anglického textu kliknite pravým tlačidlom a zvoľte „IPA Reader > Speak Selection“.

**Metóda 3: Klávesová skratka**  
Vyberte text a stlačte `Alt+Shift+S` (Mac: `Ctrl+Shift+S`) na prehratie.

> **Tip:** Karaoke zvýraznenie funguje najlepšie, keď prehliadač podporuje TTS udalosti hraníc slov. Ak nie sú podporované, rozšírenie použije záložné riešenie založené na časovaní pre plynulé zvýraznenie.

---

## Preklad

Vyberte ľubovoľný text na stránke a použite funkciu prekladu na okamžité preklady.

**Metóda 1: Panel výberu**  
Vyberte text, potom kliknite na tlačidlo 🌐 prekladu na paneli. Pod panelom sa zobrazí bublina s prekladom a tlačidlom kopírovania.

**Metóda 2: Kontextové menu**  
Vyberte text, kliknite pravým tlačidlom a zvoľte „IPA Reader > Translate Selection“.

**Metóda 3: Klávesová skratka**  
Vyberte text a stlačte `Alt+Shift+T` (Mac: `Ctrl+Shift+T`) na preklad.

**Prekladové enginy:**
- **Bing Translate** (predvolené) — poháňaný Microsoft Translatorom
- **Google Translate** — poháňaný Googlom

Oba motory podporujú **108 cieľových jazykov**.

Prekladový engine a cieľový jazyk môžete prepnúť v nastaveniach rozšírenia. Cieľový jazyk sa automaticky zistí z jazyka prehliadača.

> **Tip:** Kliknite mimo panel alebo bubliny na zatvorenie.

---

## Klávesové skratky

| Skratka | Skratka na Macu | Akcia |
|----------|-------------|--------|
| `Alt+Shift+I` | `Ctrl+Shift+I` | Zapnúť/vypnúť IPA anotácie |
| `Alt+Shift+S` | `Ctrl+Shift+S` | Prehrať vybraný text |
| `Alt+Shift+T` | `Ctrl+Shift+T` | Preložiť vybraný text |

> **Tip:** Tieto skratky môžete prispôsobiť v Chrome na `chrome://extensions/shortcuts`.

---

## Príručka nastavení

| Nastavenie | Popis |
|---------|-------------|
| **Povoliť IPA** | Hlavný prepínač pre zapnutie alebo vypnutie funkcie IPA anotácie |
| **IPA celej stránky** | Pri zapnutí zobrazuje farebne kódované IPA pre všetky anglické slová nad textom |
| **Štýl IPA** | Voľba medzi americkou a britskou angličtinou IPA a výslovnosťou |
| **Režim pri najetí** | Správanie pri najetí: Slovník (IPA + definície + zvuk), Tooltip (IPA + zvuk), Len prehrať (klik pre počutie) alebo Vypnuté |
| **Zobraziť slabé/silné formy** | Zobrazenie slabých a silných variantov výslovnosti bežných funkčných slov |
| **Rýchlosť prehrávania viet** | Úprava rýchlosti čítania viet (prehrávanie jednotlivých slov nie je ovplyvnené) |
| **Prekladový engine** | Voľba medzi Bing Translate a Google Translate |
| **Cieľový jazyk** | Nastavenie cieľového jazyka prekladu (automaticky zistený z jazyka prehliadača) |
| **Inteligentná detekcia PDF** | Pri zapnutí automaticky presmeruje URL PDF do vstavanej čítačky a zobrazí upozornenia pri zistení PDF |

---

## Často kladené otázky

**O: Prečo to na niektorých stránkach nefunguje?**  
Odp: Z bezpečnostných dôvodov sa rozšírenia prehliadača nemôžu spúšťať na špeciálnych stránkach ako `chrome://`, nastavenia prehliadača alebo Chrome Web Store.

**O: Čo keď IPA chýba u niektorých slov?**  
Odp: IPA slovník pokrýva viac ako 134 000 amerických a viac ako 67 000 britských anglických slov. Pre slová mimo slovníka rozšírenie generuje približné IPA pomocou lematizácie a pravidlovej G2P (grafém–foném) konverzie. V tooltipe sú označené ≈ alebo ~.

**O: Žiadny zvuk z text-to-speech?**  
Odp: Skontrolujte nastavenia hlasitosti systému a overte, že máte nainštalované anglické hlasové balíčky. Podpora reči sa líši v rôznych prehliadačoch a operačných systémoch.

**O: Režim celej stránky ovplyvňuje rozloženie?**  
Odp: IPA anotácie vyžadujú dodatočný priestor. Rozšírenie automaticky upravuje výšku riadku, aby sa minimalizoval vplyv na rozloženie. Ak to stále ovplyvňuje čítanie, vypnite režim celej stránky a namiesto toho použite tipy pri najetí kurzorom.

**O: Čo znamenajú symboly ~ a ≈ v nápovedách?**  
Odp: ~ znamená, že IPA bola vygenerovaná pravidlovou konverziou (G2P), nie zo slovníka. ≈ znamená, že IPA bola odvodená z príbuzného základného slova lematizáciou. Môžu byť menej presné ako slovníkové záznamy.

**O: Preklad nefunguje?**  
Odp: Preklad vyžaduje internetové pripojenie. Ak Bing Translate zlyhá, skúste prepnúť na Google Translate v nastaveniach. Niektoré sieťové prostredia môžu blokovať prístup k prekladovým službám.

**O: Ako otvorím PDF v IPA Reader?**  
Odp: PDF môžete otvoriť viacerými spôsobmi: v popupe kliknite na „Otvoriť čítačku PDF“, kliknite pravým tlačidlom na odkaz PDF a zvoľte „Otvoriť PDF v IPA Reader“, alebo v nastaveniach zapnite „Inteligentná detekcia PDF“ na automatické presmerovanie URL PDF do vstavanej čítačky.

**O: Inteligentná detekcia PDF je zapnutá, ale niektoré PDF sa nepresmerujú?**  
Odp: Automatické presmerovanie funguje pre URL končiace na `.pdf`. Pre PDF servované bez prípony `.pdf` alebo zobrazené vo vstavanom prehliadači Chrome sa zobrazí upozornenie a odznak s výzvou na otvorenie v IPA Reader.

**O: Funguje slovník offline?**  
Odp: Áno. Slovník WordNet (viac ako 82 000 slov) je plne zabalený v rozšírení. Všetky vyhľadávania prebiehajú lokálne bez sieťového pripojenia.

---

## Súvisiace odkazy

- [Zásady ochrany osobných údajov](../privacy-policy)
- [Podpora a spätná väzba](../support)

---
