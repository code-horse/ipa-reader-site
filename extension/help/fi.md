---
layout: bare
title: IPA Reader -laajennus - Käyttöopas
lang: fi
---

# IPA Reader - Käyttöopas

> Versio: v1.1.1

## Johdanto

IPA Reader on selainlaajennus, joka on suunniteltu englannin oppijoille. Se lisää IPA (International Phonetic Alphabet) -äänneasun merkinnät englanninkielisiin sanoihin verkkosivuilla, tukee sekä amerikanenglantia että brittienglantia ja auttaa sinua oppimaan englannin ääntämistä helpommin.

---

## Pääominaisuudet

- **Tekstin valinnan merkinnät** — Valitse englanninkielistä tekstiä verkkosivuilla nähdäksesi IPA- ja puhepainikkeet automaattisesti
- **Koko sivun IPA-tila** — Lisää IPA-merkinnät kaikkiin englanninkielisiin sanoihin sivulla yhdellä napsautuksella
- **Amerikkalainen ja brittiläinen aksentti** — Vaihda amerikanenglannin (en-US) ja brittienglannin (en-GB) IPA:n välillä
- **Tekstistä puheeksi** — Napsauta kaiutinpainiketta kuullaksesi ääntämisen valitsemasi aksentin mukaan
- **Valitun tekstin puhe** — Valitse mitä tahansa englanninkielistä tekstiä, napsauta kelluvaa painiketta tai napsauta hiiren kakkospainikkeella "Speak Selection" lukeaksesi ääneen
- **Kohdistetyökalut** — Vie hiiren osoitin merkityn sanan päälle nähdäksesi IPA:n ja ääntämispainikkeet
- **Heikot/vahvat muodot** — Näyttää automaattisesti funktiosanojen heikot ja vahvat ääntämisvariantit (esim. the, to, can) luonnollisen puheen hallitsemiseksi
- **Homografien tunnistus** — Tunnistaa automaattisesti sanat, joilla on useita ääntämyksiä (esim. read, live), ja valitsee oikean kontekstin perusteella
- **Monikielinen käyttöliittymä** — Tukee 38 käyttöliittymän kieltä

---

## Käyttöohje

### Vaihe 1: Asenna laajennus

Asenna **IPA Reader** [Chrome Web Store](https://chromewebstore.google.com/)-stä tai lataa se paikallisesti kehittäjätilassa.

### Vaihe 2: Avaa mikä tahansa verkkosivu

Vieraile millä tahansa englanninkielistä sisältöä sisältävällä verkkosivulla.

### Vaihe 3: Valitse teksti tai käytä kelluvaa painiketta

Valitse englanninkielinen teksti, jota haluat merkitä, tai napsauta oikeassa alareunassa olevaa kelluvaa painiketta ottamaan koko sivun IPA-tila käyttöön.

### Vaihe 4: Näytä IPA

Vie hiiren osoitin sanojen päälle nähdäksesi IPA-kohtaisohjeet, napsauta kaiutinikonia kuullaksesi ääntämisen.

### Vaihe 5: Lue valittu teksti ääneen

Valitse mitä tahansa englanninkielistä tekstiä hiirellä, napsauta kelluvaa 🔊 kaiutinpainiketta puhuaksesi; tai napsauta hiiren kakkospainikkeella ja valitse "Speak Selection".

> **Vinkki:** Napsauta laajennuksen kuvaketta selaimen työkalupalkissa avataksesi asetuspanelin ja säädäksesi aksenttityyppiä, puhenopeutta ja muuta.

---

## Valitun tekstin puhe

Valitun tekstin puhe -ominaisuus mahdollistaa englanninkielisen tekstin valitsemisen ja lukemisen ääneen yhdellä napsautuksella — täydellinen lauseen ääntämisen oppimiseen ja lukuharjoitteluun.

**Menetelmä 1: Kelluva painike**  
Valitse englanninkielinen teksti hiirellä, kaiutinpainike ilmestyy valinnan oikeaan yläkulmaan — napsauta puhuaksesi.

**Menetelmä 2: Hiiren kakkospainikkeen valikko**  
Valitse englanninkielinen teksti, napsauta hiiren kakkospainikkeella ja valitse valikosta "Speak Selection".

> **Vinkki:** Valitun tekstin puhe käyttää asetuksissasi määritettyä lausepuhenopeutta. Yhden sanan ääntämisessä käytetään oletusnopeutta. TTS-ääni vastaa valitsemaasi aksenttityyppiä (amerikkalainen tai brittiläinen).

---

## Asetusohje

| Asetus | Kuvaus |
|--------|--------|
| **Enable IPA** | Pääkytkin IPA-merkintäominaisuuden käyttöön tai pois käytöstä |
| **Whole Page IPA** | Käytössä näyttää IPA:n kaikille englanninkielisille sanoille (voi vaikuttaa sivun asetteluun) |
| **Accent Type** | Valitse amerikanenglannin ja brittienglannin IPA ja ääntämisen välillä |
| **Sentence Speech Rate** | Säädä lauselukemisen nopeutta (yhden sanan puhe ei vaikutu) |
| **Heikot/vahvat muodot** | Näytä funktiosanojen heikot ja vahvat ääntämisvariantit |
| **Hover Tooltips** | Näytä IPA-kohtaisohje hiiren osoittamisen yhteydessä |

---

## UKK

**K: Miksi se ei toimi joillakin sivuilla?**  
V: Tietoturvasyistä selainlaajennukset eivät voi toimia erikoissivuilla kuten `chrome://`, selaimen asetukset tai Chrome Web Store.

**K: Mitä jos IPA puuttuu joistakin sanoista?**  
V: IPA-sanakirja kattaa yleiset englannin sanat. Sanakirjan ulkopuolisille sanoille laajennus luo likimääräisen IPA:n lemmauksen ja G2P:n avulla, merkittynä ≈ tai ~ työkaluvihjeessä.

**K: Ei ääntä tekstistä puheeksi -ominaisuudesta?**  
V: Tarkista järjestelmän äänenvoimakkuusasetukset ja varmista, että englanninkieliset äänipaketit on asennettu. Puhetuki vaihtelee selaimittain ja käyttöjärjestelmittäin.

**K: Koko sivun tila vaikuttaa asetteluun?**  
V: IPA-merkinnät vaativat lisätilaa, mikä voi vaikuttaa alkuperäiseen sivun asetteluun. Jos se vaikuttaa lukemiseen, poista koko sivun tila käytöstä ja käytä sen sijaan kohdistetyökaluja.


**K: Mitä symbolit ~ ja ≈ tarkoittavat työkaluvihjeissä?**  
V: ~ tarkoittaa, että IPA on luotu sääntöpohjaisesti (G2P), ja ≈, että se on johdettu liittyvästä perusmuodosta. Ne voivat olla vähemmän tarkkoja kuin sanakirjamerkinnät.

---

## Aiheeseen liittyvät linkit

- [Privacy Policy](../privacy-policy)
- [Support & Feedback](../support)

---
