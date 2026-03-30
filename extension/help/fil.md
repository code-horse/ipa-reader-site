---
layout: bare
title: IPA Reader - Gabay ng Gumagamit
lang: fil
---

# IPA Reader - Gabay ng Gumagamit

> Bersyon: v1.3.0

## Panimula

Ang IPA Reader ay isang browser extension na dinisenyo para sa mga nag-aaral ng Ingles. Nagdadagdag ito ng IPA (International Phonetic Alphabet) pronunciation annotations sa mga English na salita sa mga web page, sumusuporta sa parehong American at British English accent, na tumutulong sa iyo na matutuhan ang English pronunciation nang mas madali.

---

## Mga Pangunahing Feature

- **Whole Page IPA Mode** — Magdagdag ng IPA annotation sa lahat ng English na salita sa page sa isang click; ang mga IPA symbol ay may kulay ayon sa uri (vowels, consonants, stress marks) para madaling basahin
- **Weak/Strong Forms** — Awtomatikong ipakita ang mahina at malakas na mga variant ng pronunciation para sa mga karaniwang function word (hal. "the", "to", "can"), para matutunan mo ang natural na connected speech
- **American at British Accent** — Lumipat sa pagitan ng American English (en-US) at British English (en-GB) IPA
- **Text-to-Speech** — I-click ang speaker button para marinig ang pronunciation na tumutugma sa iyong napiling accent
- **Selection Speech na may Karaoke Effect** — Pumili ng anumang English text, may lilitaw na compact toolbar na may speak at translate buttons; ang speech ay may real-time na word-by-word highlighting (karaoke effect) na naka-sync sa audio
- **Selection Translation** — Pumili ng anumang text, i-click ang translate button sa toolbar para sa instant translation sa pamamagitan ng Bing o Google Translate, ipinapakita sa inline bubble
- **Hover Tooltips** — Mag-hover sa mga annotated na salita para makita ang IPA na may color-coded na symbols at pronunciation buttons
- **Heteronym Disambiguation** — Awtomatikong kilalanin ang mga salitang may maraming pronunciation (hal. "read", "live") at piliin ang tamang isa batay sa konteksto
- **Keyboard Shortcuts** — Mabilis na access sa core features sa pamamagitan ng customizable keyboard shortcuts
- **Multilingual Interface** — Sumasuporta sa 38 na wika ng interface

---

## Paano Gamitin

### Hakbang 1: I-install ang Extension

I-install ang **IPA Reader** mula sa [Chrome Web Store](https://chromewebstore.google.com/), o i-load ito nang lokal sa developer mode.

### Hakbang 2: Buksan ang Anumang Web Page

Bisitahin ang anumang web page na may English na nilalaman.

### Hakbang 3: Paganahin ang IPA

I-click ang extension icon sa browser toolbar mo. I-on ang "Enable IPA", pagkatapos i-on ang "Whole Page IPA" para i-annotate ang lahat ng salita sa page. Maaari mo ring i-click ang floating button sa ibaba sa kanan.

### Hakbang 4: Tingnan ang IPA

Mag-hover sa mga salita para makita ang IPA tooltips na may color-coded na phonetic symbols. I-click ang speaker icon para marinig ang pronunciation. Para sa mga salitang may weak/strong forms, ipinapakita ng tooltip ang parehong variant.

### Hakbang 5: Magsalita at Magsalin ng Napiling Text

Pumili ng anumang English text gamit ang mouse. May lilitaw na compact toolbar malapit sa selection na may dalawang button:
- **🔊 Speak** — Binabasa nang malakas ang napiling text na may karaoke-style na word-by-word highlighting
- **🌐 Translate** — Nagpapakita ng inline translation bubble sa ibaba ng toolbar

Maaari mo ring mag-right-click at piliin ang "IPA Reader > Speak Selection" o "IPA Reader > Translate Selection".

> **Tip:** I-click ang extension icon sa browser toolbar mo para buksan ang settings panel at i-adjust ang accent type, speech rate, translation engine, at iba pa.

---

## Whole Page IPA Mode

Kapag naka-on ang whole page IPA mode, ang bawat English na salita sa page ay may IPA annotation sa ibabaw nito gamit ang ruby text. Ang mga IPA symbol ay may kulay para madaling basahin:

- **Vowels** — naka-highlight sa asul
- **Consonants** — nakadisplay sa kulay-abo
- **Stress marks** (ˈ ˌ) — naka-highlight sa pula
- **Length marks** (ː) — naka-highlight sa lila

Awtomatikong ina-adjust ng extension ang line height para hindi mag-overlap ang annotations sa text, at ini-scale ang IPA font size batay sa haba ng salita para malinis ang layout.

---

## Weak/Strong Forms

Maraming karaniwang English function words ang may dalawang pronunciation:

- **Weak form** — ang binabawas na pronunciation sa natural na connected speech (hal. "the" → /ðə/)
- **Strong form** — ang buong pronunciation para sa emphasis o kapag nag-iisa (hal. "the" → /ðiː/)

Kapag naka-on ang "Show weak/strong forms", ang pag-hover sa mga salitang ito ay nagpapakita ng parehong variant sa tooltip, na may label na "WEAK" at "STRONG". Tumutulong ito na maintindihan kung paano nagbabago ang pronunciation sa natural na speech.

Kasama ang: articles (the, a, an), prepositions (to, for, of, from, at, as, than), conjunctions (and, or, but), pronouns (you, your, her, him, his, them, us, our, there), auxiliary verbs (am, is, are, was, were, been, can, could, would, should, must, shall, will, do, does, have, has, had), at iba pa.

---

## Selection Speech at Karaoke

Ang selection speech feature ay nagpapahintulot na pumili ng anumang English text at basahin ito nang malakas sa isang click — perpekto para sa pag-aaral ng pronunciation ng pangungusap at pagsasanay sa pagbabasa.

**Paraan 1: Selection Toolbar**  
Pumili ng English text gamit ang mouse. May lilitaw na compact toolbar malapit sa selection na may 🔊 speak button at 🌐 translate button. I-click ang speak button para i-play. Habang binabasa ang text nang malakas, bawat salita ay naka-highlight nang real time (karaoke effect), tumutulong sa iyo na sundan.

**Paraan 2: Right-Click Menu**  
Pagkatapos pumili ng English text, mag-right-click at piliin ang "IPA Reader > Speak Selection".

**Paraan 3: Keyboard Shortcut**  
Pumili ng text at pindutin ang `Alt+Shift+S` (Mac: `Ctrl+Shift+S`) para magsalita.

> **Tip:** Pinakamahusay ang karaoke highlighting kapag sinusuportahan ng browser ang TTS word boundary events. Kung hindi suportado, gumagamit ang extension ng timing-based fallback para sa smooth na highlighting.

---

## Pagsasalin

Pumili ng anumang text sa page at gamitin ang translation feature para sa instant na mga pagsasalin.

**Paraan 1: Selection Toolbar**  
Pumili ng text, pagkatapos i-click ang 🌐 translate button sa toolbar. May lilitaw na translation bubble sa ibaba na nagpapakita ng resulta, na may copy button.

**Paraan 2: Right-Click Menu**  
Pumili ng text, mag-right-click at piliin ang "IPA Reader > Translate Selection".

**Paraan 3: Keyboard Shortcut**  
Pumili ng text at pindutin ang `Alt+Shift+T` (Mac: `Ctrl+Shift+T`) para magsalin.

**Mga Translation Engine:**
- **Bing Translate** (default) — Pinapagana ng Microsoft Translator
- **Google Translate** — Pinapagana ng Google

Parehong engine ay sumusuporta ng **108 target languages**.

Maaari mong palitan ang translation engine at target language sa extension settings. Awtomatikong natutukoy ang target language mula sa wika ng browser mo.

> **Tip:** Mag-click kahit saan sa labas ng toolbar o bubble para isara ang mga ito.

---

## Keyboard Shortcuts

| Shortcut | Mac Shortcut | Aksyon |
|----------|-------------|--------|
| `Alt+Shift+I` | `Ctrl+Shift+I` | I-toggle ang IPA annotations on/off |
| `Alt+Shift+S` | `Ctrl+Shift+S` | Magsalita ng napiling text |
| `Alt+Shift+T` | `Ctrl+Shift+T` | Magsalin ng napiling text |

> **Tip:** Maaari mong i-customize ang mga shortcut na ito sa Chrome sa `chrome://extensions/shortcuts`.

---

## Gabay sa mga Setting

| Setting | Paglalarawan |
|---------|-------------|
| **Enable IPA** | Master switch para i-enable o i-disable ang IPA annotation feature |
| **Whole Page IPA** | Kapag naka-enable, nagpapakita ng color-coded IPA para sa lahat ng English na salita sa ibabaw ng text |
| **IPA Style** | Pumili sa pagitan ng American English at British English IPA at pronunciation |
| **Show hover tooltip** | Ipakita ang IPA tooltip na may pronunciation button kapag nag-hover ang mouse |
| **Show weak/strong forms** | Ipakita ang weak at strong pronunciation variants para sa karaniwang function words |
| **Sentence Speech Rate** | I-adjust ang bilis ng pagbasa ng pangungusap (hindi apektado ang single word speech) |
| **Translation Engine** | Pumili sa pagitan ng Bing Translate at Google Translate |
| **Target Language** | Itakda ang target language ng pagsasalin (awto-detect mula sa wika ng browser) |

---

## FAQ

**T: Bakit hindi ito gumagana sa ilang mga page?**  
S: Para sa mga dahilan ng seguridad, ang mga browser extension ay hindi maaaring tumakbo sa mga espesyal na page tulad ng `chrome://`, mga setting ng browser, o ang Chrome Web Store.

**T: Paano kung walang IPA para sa ilang mga salita?**  
S: Ang IPA dictionary ay sumasaklaw sa mga karaniwang English na salita. Para sa mga salitang wala sa dictionary, ang extension ay gumagawa ng approximate na IPA sa pamamagitan ng lemmatization at rule-based G2P (grapheme-to-phoneme) conversion. Ang mga ito ay minamarkahan ng ≈ o ~ sa tooltip.

**T: Walang tunog mula sa text-to-speech?**  
S: Pakisuri ang mga volume setting ng iyong system at tiyaking naka-install ang mga English voice pack. Ang suporta sa speech ay nag-iiba-iba sa iba't ibang browser at operating system.

**T: Ang whole page mode ba ay nakakaapekto sa layout?**  
S: Ang mga IPA annotation ay nangangailangan ng karagdagang espasyo. Awtomatikong ina-adjust ng extension ang line height para mabawasan ang epekto sa layout. Kung nakakaapekto pa rin sa pagbabasa, i-disable ang whole page mode at gumamit ng hover tooltips sa halip.

**T: Ano ang ibig sabihin ng ~ at ≈ sa mga tooltip?**  
S: Ang ~ ay nangangahulugang ang IPA ay na-generate sa pamamagitan ng rule-based conversion (G2P) imbes na mula sa dictionary. Ang ≈ ay nangangahulugang ang IPA ay hinango mula sa kaugnay na base word sa pamamagitan ng lemmatization. Maaaring mas hindi tumpak kaysa sa mga entry sa dictionary.

**T: Hindi gumagana ang pagsasalin?**  
S: Ang pagsasalin ay nangangailangan ng internet connection. Kung nabigo ang Bing Translate, subukang lumipat sa Google Translate sa mga setting. Maaaring harangin ng ilang network environment ang access sa translation services.

---

## Mga Kaugnay na Link

- [Privacy Policy](../privacy-policy)
- [Suporta at Feedback](../support)

---
