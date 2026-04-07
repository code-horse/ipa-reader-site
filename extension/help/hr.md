---
layout: bare
title: IPA Reader proširenje - Korisnički vodič
lang: hr
---

# IPA Reader - Korisnički vodič

> Verzija: v1.4.1

## Uvod

IPA Reader je proširenje preglednika dizajnirano za učenike engleskog jezika. Dodaje IPA (Međunarodna fonetska abeceda) napomene izgovora engleskim riječima na web stranicama i u PDF-ovima, s podrškom za američki i britanski engleski naglasak. Uključuje i ugrađeni engleski rječnik, pretvaranje teksta u govor i značajke prijevoda — pomažući vam lakše učiti engleski izgovor.

---

## Glavne značajke

- **IPA na cijeloj stranici** — Dodajte IPA napomene svim engleskim riječima na stranici jednim klikom; IPA simboli su kodirani bojama prema vrsti (samoglasnici, suglasnici, naglasni znakovi) za lako čitanje
- **Rječnik pri prelasku (WordNet)** — Prijeđite mišem preko riječi da vidite engleske definicije (82 000+ riječi iz WordNeta), IPA s bojom kodiranim simbolima i gumbe za izgovor; odaberite način Rječnik, Tooltip ili Isključeno
- **Čitač PDF-a** — Ugrađeni čitač PDF-a s IPA napomenama, rječnikom, govorom i prijevodom; podržava povuci i ispusti, učitavanje URL-a te automatsku detekciju PDF-a sa pametnim preusmjeravanjem
- **Slabi/jaki oblici** — Automatski prikaz slabih i jakih izgovornih varijanti uobičajenih funkcijskih riječi (npr. "the", "to", "can") za svladavanje prirodnog povezanog govora
- **Američki i britanski naglasak** — Prelazite između američkog engleskog (en-US) i britanskog engleskog (en-GB) IPA
- **Text-to-Speech** — Kliknite na gumb zvučnika da biste čuli izgovor prema odabranom naglasku
- **Govor odabira s karaoke efektom** — Odaberite bilo koji engleski tekst; pojavljuje se kompaktna alatna traka s gumbima za govor i prijevod; govor se reproducira s istovremenim naglašavanjem riječ po riječ (karaoke efekt) sinkroniziranim s audioom
- **Prijevod odabira** — Odaberite bilo koji tekst, kliknite gumb za prijevod na alatnoj traci za trenutni prijevod putem Binga ili Google Translatea, prikazan u ugrađenom balončiću
- **Prepoznavanje homografa** — Automatska identifikacija riječi s više izgovora (npr. "read", "live") i odabir ispravnog prema kontekstu
- **Tipkovni prečaci** — Brz pristup glavnim značajkama putem prilagodljivih tipkovnih prečaca
- **Višejezično sučelje** — Podržava 41 jezika sučelja

---

## Kako koristiti

### Korak 1: Instalacija proširenja

Instalirajte **IPA Reader** s [Chrome Web Store](https://chromewebstore.google.com/), ili ga učitajte lokalno u načinu razvojnog okruženja.

### Korak 2: Otvorite bilo koju web stranicu

Posjetite bilo koju web stranicu koja sadrži engleski sadržaj.

### Korak 3: Omogućite IPA

Kliknite na ikonu proširenja u alatnoj traci preglednika. Uključite "Omogući IPA", zatim uključite "IPA na cijeloj stranici" da biste označili sve riječi na stranici. Možete i kliknuti plutajući gumb u donjem desnom kutu.

### Korak 4: Prikaz IPA

Prijeđite mišem preko riječi da vidite IPA tooltipove s bojom kodiranim fonetskim simbolima. Kliknite ikonu zvučnika da čujete izgovor. Za riječi sa slabim/jakim oblicima, tooltip prikazuje obje varijante.

### Korak 5: Govor i prijevod odabranog teksta

Odaberite bilo koji engleski tekst mišem. Pojavljuje se kompaktna alatna traka pokraj odabira s dva gumba:
- **🔊 Govor** — Čita odabrani tekst naglas s naglašavanjem riječ po riječ u karaoke stilu
- **🌐 Prijevod** — Prikazuje ugrađeni balončić prijevoda ispod alatne trake

Možete i desnim klikom odabrati "IPA Reader > Speak Selection" ili "IPA Reader > Translate Selection".

> **Savjet:** Kliknite na ikonu proširenja u alatnoj traci preglednika da otvorite ploču postavki i prilagodite vrstu naglaska, brzinu govora, način pri prelasku, mehanizam prijevoda i drugo.

---

## IPA na cijeloj stranici

Kada je omogućen način IPA na cijeloj stranici, svaka engleska riječ na stranici dobiva IPA napomenu iznad sebe pomoću ruby teksta. IPA simboli su kodirani bojama za lako čitanje:

- **Samoglasnici** — istaknuti plavom bojom
- **Suglasnici** — prikazani sivom bojom
- **Naglasni znakovi** (ˈ ˌ) — istaknuti crvenom bojom
- **Znakovi duljine** (ː) — istaknuti ljubičastom bojom

Proširenje automatski prilagođava visinu retka kako bi se napomene ne preklapale s tekstom i skalira veličinu fonta IPA prema duljini riječi za čist raspored.

---

## Rječnik pri prelasku (WordNet)

Proširenje uključuje ugrađeni engleski rječnik temeljen na WordNetu (82 000+ riječi). U postavkama možete odabrati više načina pri prelasku:

| Način | Ponašanje |
|-------|-----------|
| **Rječnik** | Pri prelasku: IPA + engleska definicija + gumb za izgovor |
| **Tooltip** | Pri prelasku: IPA + gumb za izgovor (bez definicija) |
| **Isključeno** | Nema efekta pri prelasku |

U **načinu Rječnik**, tooltip prikazuje:
- Riječ i njezin IPA prijepis
- Gumb za izgovor (kliknite za slušanje)
- Engleske definicije iz WordNeta

> **Savjet:** Podaci rječnika učitavaju se na zahtjev kada je omogućen način Rječnik, a uklanjaju pri prelasku na druge načine kako bi se uštedjela memorija.

---

## Čitač PDF-a

IPA Reader uključuje ugrađeni čitač PDF-a koji vam omogućuje čitanje PDF dokumenata s IPA napomenama, rječnikom, govorom i prijevodom — sve značajke koje imate na web stranicama sada su dostupne i za PDF-ove.

### Otvaranje PDF-a

**Metoda 1: Iz skočnog prozora**  
Kliknite na ikonu proširenja, zatim na "Open PDF Reader". Povucite i ispustite PDF datoteku ili kliknite "Choose File" da otvorite lokalni PDF. Možete i zalijepiti URL PDF-a.

**Metoda 2: Kontekstni izbornik**  
Desnim klikom na bilo koju `.pdf` poveznicu na stranici odaberite "Open PDF with IPA Reader".

**Metoda 3: Automatska detekcija**  
Kada je u postavkama omogućeno "PDF Smart Detection", proširenje automatski preusmjerava URL-ove koji završavaju na `.pdf` na ugrađeni čitač. Kada se PDF otkrije, ali se ne preusmjeri (npr. ugrađeni preglednik Chromea), vidjet ćete obavijesti i upite za otvaranje u IPA Readeru.

### Značajke čitača PDF-a

- **IPA napomene** — Sve IPA značajke rade na tekstu PDF-a, uključujući način cijele stranice i tooltipove pri prelasku
- **Rječnik klikom** — Kliknite na bilo koju riječ za definiciju (u PDF-u se umjesto prijelaza mišem koristi klik radi čitanja bez ometanja)
- **Alatna traka odabira** — Odaberite tekst za govor, prijevod ili kopiranje
- **Bočna traka** — Pregled sadržaja i minijature stranica
- **Pretraga** — Pretraživanje teksta u PDF-u
- **Teme** — Tamna, svijetla i sepija tema za čitanje
- **Zumiranje** — Više razina zumiranja uključujući Automatski, Prilagodba stranice i Širina stranice
- **Tipkovni prečaci** — Strelicama za navigaciju, +/- za zum, Ctrl/Cmd+F za pretragu

---

## Slabi/jaki oblici

Mnoge uobičajene engleske funkcijske riječi imaju dva izgovora:

- **Slabi oblik** — smanjeni izgovor u prirodnom povezanom govoru (npr. "the" → /ðə/)
- **Jaki oblik** — puni izgovor za naglasak ili u izolaciji (npr. "the" → /ðiː/)

Kada je omogućeno "Prikaži slabe/jake oblike", pri prelasku mišem preko tih riječi prikazuju se obje varijante u tooltipu, označene kao "WEAK" i "STRONG". To pomaže razumjeti kako se izgovor mijenja u prirodnom govoru.

Obuhvaćene riječi uključuju: članove (the, a, an), prijedloge (to, for, of, from, at, as, than), veznike (and, or, but), zamjenice (you, your, her, him, his, them, us, our, there), pomoćne glagole (am, is, are, was, were, been, can, could, would, should, must, shall, will, do, does, have, has, had) i više.

---

## Govor odabira i karaoke

Značajka govora odabira omogućuje vam odabir bilo kojeg engleskog teksta i čitanje naglas jednim klikom — savršeno za učenje izgovora rečenica i vježbu čitanja.

**Metoda 1: Alatna traka odabira**  
Odaberite engleski tekst mišem. Pojavljuje se kompaktna alatna traka pokraj odabira s gumbom 🔊 za govor i gumbom 🌐 za prijevod. Kliknite gumb za govor za reprodukciju. Dok se tekst čita naglas, svaka se riječ u stvarnom vremenu ističe (karaoke efekt), što pomaže pri praćenju.

**Metoda 2: Kontekstni izbornik**  
Nakon odabira engleskog teksta, desnim klikom odaberite "IPA Reader > Speak Selection".

**Metoda 3: Tipkovni prečac**  
Odaberite tekst i pritisnite `Alt+Shift+S` (Mac: `Ctrl+Shift+S`) za govor.

> **Savjet:** Karaoke isticanje najbolje radi kada preglednik podržava TTS događaje granica riječi. Ako nije podržano, proširenje koristi zamjenu temeljenu na vremenu za glatko isticanje.

---

## Prijevod

Odaberite bilo koji tekst na stranici i upotrijebite značajku prijevoda za trenutne prijevode.

**Metoda 1: Alatna traka odabira**  
Odaberite tekst, zatim kliknite gumb 🌐 za prijevod na alatnoj traci. Ispod se pojavljuje balončić prijevoda s rezultatom i gumbom za kopiranje.

**Metoda 2: Kontekstni izbornik**  
Odaberite tekst, desnim klikom odaberite "IPA Reader > Translate Selection".

**Metoda 3: Tipkovni prečac**  
Odaberite tekst i pritisnite `Alt+Shift+T` (Mac: `Ctrl+Shift+T`) za prijevod.

**Mehanizmi prijevoda:**
- **Bing Translate** (zadano) — pokreće Microsoft Translator
- **Google Translate** — pokreće Google

Oba motora podržavaju **108 ciljnih jezika**.

Mehanizam prijevoda i ciljni jezik možete promijeniti u postavkama proširenja. Ciljni jezik se automatski prepoznaje iz jezika preglednika.

> **Savjet:** Kliknite izvan alatne trake ili balončića da ih zatvorite.

---

## Tipkovni prečaci

| Prečac | Prečac na Macu | Radnja |
|----------|-------------|--------|
| `Alt+Shift+I` | `Ctrl+Shift+I` | Uključi/isključi IPA napomene |
| `Alt+Shift+S` | `Ctrl+Shift+S` | Govor odabranog teksta |
| `Alt+Shift+T` | `Ctrl+Shift+T` | Prijevod odabranog teksta |

> **Savjet:** Ove prečace možete prilagoditi u Chromeu na `chrome://extensions/shortcuts`.

---

## Vodič postavkama

| Postavka | Opis |
|---------|-------------|
| **Omogući IPA** | Glavni prekidač za omogućavanje ili onemogućavanje značajke IPA napomena |
| **IPA na cijeloj stranici** | Kada je omogućeno, prikazuje bojom kodirani IPA za sve engleske riječi iznad teksta |
| **Stil IPA** | Odaberite između američkog i britanskog engleskog IPA i izgovora |
| **Način pri prelasku** | Odaberite ponašanje: Rječnik (IPA + definicije + audio), Tooltip (IPA + audio) ili Isključeno |
| **Prikaži slabe/jake oblike** | Prikažite slabe i jake izgovorne varijante uobičajenih funkcijskih riječi |
| **Brzina govora rečenica** | Prilagodite brzinu čitanja rečenica (govor pojedinačnih riječi nije zahvaćen) |
| **Mehanizam prijevoda** | Odaberite između Bing Translate i Google Translate |
| **Ciljni jezik** | Postavite ciljni jezik prijevoda (automatski prepoznat iz jezika preglednika) |
| **Pametna detekcija PDF-a** | Kada je omogućeno, automatski preusmjerava URL-ove PDF-a na ugrađeni čitač i prikazuje obavijesti kada se otkriju PDF-ovi |

---

## Često postavljana pitanja

**P: Zašto ne radi na nekim stranicama?**  
O: Iz sigurnosnih razloga, proširenja preglednika ne mogu se pokretati na posebnim stranicama poput `chrome://`, postavki preglednika ili Chrome Web Store.

**P: Što ako nedostaje IPA za neke riječi?**  
O: IPA rječnik pokriva više od 134 000 američkih i više od 67 000 britanskih engleskih riječi. Za riječi izvan rječnika, proširenje generira približni IPA putem lematizacije i pravila G2P (grafem–fonem). Označeno je s ≈ ili ~ u savjetu.

**P: Nema zvuka iz text-to-speech?**  
O: Provjerite postavke glasnoće sustava i osigurajte da su instalirani engleski glasovni paketi. Podrška za govor varira među preglednicima i operacijskim sustavima.

**P: Način cijele stranice utječe na raspored?**  
O: IPA napomene zahtijevaju dodatni prostor. Proširenje automatski prilagođava visinu retka kako bi se smanjio utjecaj na raspored. Ako i dalje utječe na čitanje, onemogućite način cijele stranice i koristite tooltipove pri prelasku.

**P: Što znače simboli ~ i ≈ u savjetima?**  
O: ~ znači da je IPA generiran pravila pretvorbe (G2P), a ne iz rječnika. ≈ znači da je IPA izveden iz srodne osnovne riječi putem lematizacije. Mogu biti manje točni od rječničkih unosa.

**P: Prijevod ne radi?**  
O: Prijevod zahtijeva internetsku vezu. Ako Bing Translate ne uspije, pokušajte prebaciti na Google Translate u postavkama. Neke mreže mogu blokirati pristup uslugama prijevoda.

**P: Kako otvoriti PDF u IPA Readeru?**  
O: Možete na nekoliko načina: kliknite "Open PDF Reader" u skočnom prozoru, desnim klikom na poveznicu PDF-a odaberite "Open PDF with IPA Reader", ili omogućite "PDF Smart Detection" u postavkama za automatsko preusmjeravanje URL-ova PDF-a na ugrađeni čitač.

**P: PDF Smart Detection je uključen, ali neki PDF-ovi se ne preusmjeravaju?**  
O: Automatsko preusmjeravanje radi za URL-ove koji završavaju na `.pdf`. Za PDF-ove poslužene bez nastavka `.pdf` ili ugrađeni preglednik Chromea vidjet ćete obavijest i značku koja vas poziva da otvorite u IPA Readeru.

**P: Mogu li koristiti rječnik izvan mreže?**  
O: Da. WordNet rječnik (više od 82 000 riječi) u potpunosti je uključen u proširenje. Sva pretraživanja izvode se lokalno bez internetske veze.

---

## Povezane poveznice

- [Pravila o privatnosti](../privacy-policy)
- [Podrška i povratne informacije](../support)

---
