---
layout: bare
title: Rozšírenie IPA Reader - Používateľská príručka
lang: sk
---

# IPA Reader - Používateľská príručka

> Verzia: v1.1.0

## Úvod

IPA Reader je rozšírenie prehliadača určené pre študentov angličtiny. Pridáva IPA (Medzinárodná fonetická abeceda) anotácie výslovnosti k anglickým slovám na webových stránkach, podporuje americký aj britský anglický prízvuk a pomáha vám ľahšie sa učiť anglickú výslovnosť.

---

## Hlavné funkcie

- **Anotácia výberom textu** — Vyberte anglický text na webových stránkach pre automatické zobrazenie IPA a tlačidiel pre prehrávanie
- **Režim IPA celej stránky** — Pridajte IPA anotácie ku všetkým anglickým slovám na stránke jedným kliknutím, s farebne kódovanými IPA symbolmi (samohlásky, spoluhlásky, prízvuky) pre ľahké čítanie
- **Americký a britský prízvuk** — Prepínajte medzi americkou angličtinou (en-US) a britskou angličtinou (en-GB) IPA
- **Text-to-Speech** — Kliknite na tlačidlo reproduktora pre prehranie výslovnosti podľa zvoleného prízvuku
- **Prehrávanie výberu** — Vyberte ľubovoľný anglický text, kliknite na plávajúce tlačidlo alebo pravým tlačidlom zvoľte „Speak Selection“ pre hlasité predčítanie
- **Tipy pri najetí kurzorom** — Najetím kurzora nad anotované slová zobrazíte IPA a tlačidlá pre výslovnosť
- **Slabé/silné formy** — Automatické zobrazenie slabých a silných variantov výslovnosti funkčných slov (napr. the, to, can) na zvládnutie prirodzenej plynulej reči
- **Rozlíšenie homografov** — Automatická identifikácia slov s viacerými výslovnosťami (napr. read, live) a výber správnej podľa kontextu
- **Viacjazyčné rozhranie** — Podporuje 38 jazykov rozhrania

---

## Ako používať

### Krok 1: Nainštalovať rozšírenie

Nainštalujte **IPA Reader** z [Chrome Web Store](https://chromewebstore.google.com/) alebo ho načítajte lokálne v režime vývojára.

### Krok 2: Otvoriť ľubovoľnú webovú stránku

Navštívte ľubovoľnú webovú stránku obsahujúcu anglický obsah.

### Krok 3: Vybrať text alebo použiť plávajúce tlačidlo

Vyberte anglický text, ktorý chcete anotovať, alebo kliknite na plávajúce tlačidlo v pravom dolnom rohu pre zapnutie režimu IPA celej stránky.

### Krok 4: Zobraziť IPA

Najedte kurzorom nad slová pre zobrazenie IPA tipov, kliknite na ikonu reproduktora pre prehranie výslovnosti.

### Krok 5: Prehrať vybraný text

Vyberte ľubovoľný anglický text myšou, kliknite na plávajúce tlačidlo 🔊 pre prehrávanie; alebo kliknite pravým tlačidlom a zvoľte „Speak Selection“.

> **Tip:** Kliknutím na ikonu rozšírenia na lište prehliadača otvoríte panel nastavení a upravíte typ prízvuku, rýchlosť prehrávania a ďalšie.

---

## Prehrávanie výberu

Funkcia prehrávania výberu vám umožňuje vybrať ľubovoľný anglický text a prečítať ho nahlas jedným kliknutím — ideálne pre učenie výslovnosti viet a čitateľskú prax.

**Metóda 1: Plávajúce tlačidlo**  
Vyberte anglický text myšou, v pravom hornom rohu výberu sa zobrazí tlačidlo reproduktora — kliknite pre prehrávanie.

**Metóda 2: Kontextové menu**  
Po výbere anglického textu kliknite pravým tlačidlom a zvoľte „Speak Selection“ z menu.

> **Tip:** Prehrávanie výberu používa rýchlosť prehrávania viet nastavenú vo vašich nastaveniach. Výslovnosť jednotlivých slov používa predvolenú rýchlosť. Hlas TTS zodpovedá zvolenému typu prízvuku (americký alebo britský).

---

## Príručka nastavení

| Nastavenie | Popis |
|---------|-------------|
| **Povoliť IPA** | Hlavný prepínač pre zapnutie alebo vypnutie funkcie IPA anotácie |
| **IPA celej stránky** | Pri zapnutí zobrazuje IPA pre všetky anglické slová (môže ovplyvniť rozloženie stránky) |
| **Typ prízvuku** | Voľba medzi americkou a britskou angličtinou IPA a výslovnosťou |
| **Rýchlosť prehrávania viet** | Úprava rýchlosti čítania viet (prehrávanie jednotlivých slov nie je ovplyvnené) |
| **Slabé/silné formy** | Zobrazenie slabých a silných variantov výslovnosti funkčných slov |
| **Tipy pri najetí kurzorom** | Zobrazenie IPA tipu pri najetí kurzorom myši |

---

## Často kladené otázky

**O: Prečo to na niektorých stránkach nefunguje?**  
Odp: Z bezpečnostných dôvodov sa rozšírenia prehliadača nemôžu spúšťať na špeciálnych stránkach ako `chrome://`, nastavenia prehliadača alebo Chrome Web Store.

**O: Čo keď IPA chýba u niektorých slov?**  
Odp: Slovník IPA pokrýva bežné anglické slová. U niektorých vzácnych alebo špecializovaných slov nemusia byť záznamy IPA. Slovník postupne rozširujeme.

**O: Žiadny zvuk z text-to-speech?**  
Odp: Skontrolujte nastavenia hlasitosti systému a overte, že máte nainštalované anglické hlasové balíčky. Podpora reči sa líši v rôznych prehliadačoch a operačných systémoch.

**O: Režim celej stránky ovplyvňuje rozloženie?**  
Odp: IPA anotácie vyžadujú dodatočný priestor, čo môže ovplyvniť pôvodné rozloženie stránky. Ak to ovplyvňuje čítanie, vypnite režim celej stránky a namiesto toho použite tipy pri najetí kurzorom.


**O: Čo znamenajú symboly ~ a ≈ v nápovediach?**  
O: ~ znamená, že IPA bola vygenerovaná pravidlami (G2P), a ≈, že bola odvodená z príbuzného základného slova. Môžu byť menej presné ako slovníkové záznamy.

---

## Súvisiace odkazy

- [Zásady ochrany osobných údajov](../privacy-policy)
- [Podpora a spätná väzba](../support)

---
