---
layout: bare
title: IPA Reader - Gabay ng Gumagamit
lang: fil
---

# IPA Reader - Gabay ng Gumagamit

> Bersyon: v1.1.2

## Panimula

Ang IPA Reader ay isang browser extension na dinisenyo para sa mga nag-aaral ng Ingles. Nagdadagdag ito ng IPA (International Phonetic Alphabet) pronunciation annotations sa mga English na salita sa mga web page, sumusuporta sa parehong American at British English accent, na tumutulong sa iyo na matutuhan ang English pronunciation nang mas madali.

---

## Mga Pangunahing Feature

- **Text Selection Annotation** — Pumili ng English text sa mga web page para awtomatikong ipakita ang IPA at mga speech button
- **Whole Page IPA Mode** — Magdagdag ng IPA annotation sa lahat ng English na salita sa page sa isang click, na may color-coded na IPA symbol (vowel, consonant, stress mark) para sa madaling pagbasa
- **American at British Accent** — Lumipat sa pagitan ng American English (en-US) at British English (en-GB) IPA
- **Text-to-Speech** — I-click ang speaker button para marinig ang pronunciation na tumutugma sa iyong napiling accent
- **Selection Speech** — Pumili ng anumang English text, i-click ang floating button o i-right-click "Speak Selection" para basahin nang malakas
- **Hover Tooltips** — Mag-hover sa mga annotated na salita para makita ang IPA at mga pronunciation button
- **Weak/Strong Forms** — Awtomatikong ipakita ang mahina at malakas na mga variant ng pronunciation para sa mga function word (hal. the, to, can) para sa natural na connected speech
- **Heteronym Disambiguation** — Awtomatikong kilalanin ang mga salitang may maraming pronunciation (hal. read, live) at piliin ang tamang isa batay sa konteksto
- **Multilingual Interface** — Sumusuporta sa 38 na wika ng interface

---

## Paano Gamitin

### Hakbang 1: I-install ang Extension

I-install ang **IPA Reader** mula sa [Chrome Web Store](https://chromewebstore.google.com/), o i-load ito nang lokal sa developer mode.

### Hakbang 2: Buksan ang Anumang Web Page

Bisitahin ang anumang web page na may English na nilalaman.

### Hakbang 3: Pumili ng Text o Gamitin ang Floating Button

Pumili ng English text na gusto mong i-annotate, o i-click ang floating button sa ibaba sa kanan para i-enable ang whole page IPA mode.

### Hakbang 4: Tingnan ang IPA

Mag-hover sa mga salita para makita ang IPA tooltip, i-click ang speaker icon para marinig ang pronunciation.

### Hakbang 5: Basahin ang Napiling Text nang Malakas

Pumili ng anumang English text gamit ang mouse, i-click ang 🔊 floating button para basahin; o i-right-click at piliin ang "Speak Selection".

> **Tip:** I-click ang extension icon sa browser toolbar mo para buksan ang settings panel at i-adjust ang accent type, speech rate, at iba pa.

---

## Gabay sa mga Setting

| Setting | Paglalarawan |
|---------|-------------|
| **Enable IPA** | Master switch para i-enable o i-disable ang IPA annotation feature |
| **Whole Page IPA** | Kapag naka-enable, ipinapakita ang IPA para sa lahat ng English na salita (maaaring maapektuhan ang page layout) |
| **Accent Type** | Pumili sa pagitan ng American English at British English IPA at pronunciation |
| **Sentence Speech Rate** | I-adjust ang bilis ng pagbasa ng pangungusap (hindi apektado ang single word speech) |
| **Ipakita ang weak/strong forms** | Ipakita ang mahina at malakas na pronunciation variant para sa mga function word |
| **Hover Tooltips** | Ipakita ang IPA tooltip sa mouse hover |

---

## FAQ

**T: Bakit hindi ito gumagana sa ilang mga page?**  
S: Para sa mga dahilan ng seguridad, ang mga browser extension ay hindi maaaring tumakbo sa mga espesyal na page tulad ng `chrome://`, mga setting ng browser, o ang Chrome Web Store.

**T: Paano kung walang IPA para sa ilang mga salita?**  
S: Ang IPA dictionary ay sumasaklaw sa mga karaniwang English na salita. Para sa mga salitang wala sa dictionary, ang extension ay gumagawa ng approximate na IPA sa pamamagitan ng lemmatization at G2P, na may markang ≈ o ~ sa tooltip.

**T: Walang tunog mula sa text-to-speech?**  
S: Pakisuri ang mga volume setting ng iyong system at tiyaking naka-install ang mga English voice pack. Ang suporta sa speech ay nag-iiba-iba sa iba't ibang browser at operating system.

**T: Ang whole page mode ba ay nakakaapekto sa layout?**  
S: Ang mga IPA annotation ay nangangailangan ng karagdagang espasyo, na maaaring makaapekto sa orihinal na layout ng page. Kung nakakaapekto ito sa pagbabasa, i-disable ang whole page mode at gumamit ng hover tooltip sa halip.


**T: Ano ang ibig sabihin ng ~ at ≈ sa mga tooltip?**  
S: ~ ay nangangahulugang ang IPA ay na-generate sa pamamagitan ng mga panuntunan (G2P), at ≈ ay na-derive mula sa isang kaugnay na base word. Maaaring hindi ito kasing-tumpak ng mga dictionary entry.

---

## Mga Kaugnay na Link

- [Privacy Policy](../privacy-policy)
- [Suporta at Feedback](../support)

---
