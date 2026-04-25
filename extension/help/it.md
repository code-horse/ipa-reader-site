---
layout: bare
title: Estensione IPA Reader - Guida utente
lang: it
---

# IPA Reader - Guida utente

> Versione: v1.4.4

## Introduzione

IPA Reader è un'estensione per browser progettata per chi studia l'inglese. Aggiunge annotazioni di pronuncia IPA (alfabeto fonetico internazionale) alle parole in inglese nelle pagine web e nei PDF, supportando sia l'accento americano che quello britannico. Include anche un dizionario inglese integrato, sintesi vocale e funzioni di traduzione — per imparare la pronuncia dell'inglese con maggiore facilità.

---

## Funzionalità principali

- **Modalità IPA pagina intera** — Aggiunge annotazioni IPA a tutte le parole in inglese della pagina con un clic; i simboli IPA sono codificati a colori per tipo (vocali, consonanti, segni d'accento) per una lettura più chiara
- **Dizionario al passaggio (WordNet)** — Passa il mouse sulle parole per vedere le definizioni in inglese (oltre 82.000 parole da WordNet), IPA con simboli a colori e pulsanti di pronuncia; scegli tra modalità Dizionario, Tooltip o Disattivato
- **Lettore PDF** — Lettore PDF integrato con annotazioni IPA, dizionario, sintesi vocale e traduzione; supporta trascinamento, caricamento da URL e rilevamento automatico dei PDF con reindirizzamento intelligente
- **Forme deboli/forti** — Mostra automaticamente le varianti di pronuncia debole e forte delle parole funzionali comuni (es. "the", "to", "can"), per padroneggiare il parlato naturale collegato
- **Accento americano e britannico** — Passa tra IPA americano (en-US) e britannico (en-GB)
- **Testo-to-Speech** — Clicca il pulsante altoparlante per ascoltare la pronuncia corrispondente all'accento selezionato
- **Lettura selezione con effetto karaoke** — Seleziona testo in inglese: compare una barra compatta con pulsanti per parlare e tradurre; la lettura evidenzia le parole in tempo reale (effetto karaoke) sincronizzata all'audio
- **Traduzione della selezione** — Seleziona qualsiasi testo, clicca traduci nella barra per ottenere una traduzione istantanea tramite Bing o Google Translate, mostrata in un fumetto inline
- **Disambiguazione omografi** — Identifica automaticamente le parole con più pronunce (es. "read", "live") e sceglie quella corretta in base al contesto
- **Scorciatoie da tastiera** — Accesso rapido alle funzioni principali tramite scorciatoie personalizzabili
- **Interfaccia multilingue** — Supporta 41 lingue dell'interfaccia

---

## Come usare

### Passo 1: Installare l'estensione

Installa **IPA Reader** da [Chrome Web Store](https://chromewebstore.google.com/), oppure caricala in locale in modalità sviluppatore.

### Passo 2: Aprire una pagina web

Visita una pagina web che contenga contenuti in inglese.

### Passo 3: Attivare l'IPA

Clicca l'icona dell'estensione nella barra degli strumenti del browser. Attiva "Attiva IPA", poi "IPA pagina intera" per annotare tutte le parole della pagina. Puoi anche usare il pulsante flottante in basso a destra.

### Passo 4: Visualizzare l'IPA

Passa il mouse sulle parole per vedere i tooltip IPA con simboli fonetici a colori. Clicca l'icona altoparlante per sentire la pronuncia. Per le parole con forme deboli/forti, il tooltip mostra entrambe le varianti.

### Passo 5: Leggere e tradurre il testo selezionato

Seleziona testo in inglese con il mouse. Vicino alla selezione compare una barra compatta con due pulsanti:

- **🔊 Parla** — Legge il testo selezionato ad alta voce con evidenziazione parola per parola in stile karaoke
- **🌐 Traduci** — Mostra un fumetto di traduzione inline sotto la barra

Puoi anche fare clic destro e scegliere "IPA Reader > Leggi selezione" o "IPA Reader > Traduci selezione".

> **Suggerimento:** Clicca l'icona dell'estensione nella barra degli strumenti per aprire il pannello impostazioni e regolare tipo di accento, velocità di lettura, modalità al passaggio del mouse, motore di traduzione e altro.

---

## Modalità IPA pagina intera

Con la modalità IPA pagina intera attiva, ogni parola in inglese sulla pagina riceve un'annotazione IPA sopra il testo tramite ruby text. I simboli IPA sono codificati a colori:

- **Vocali** — evidenziate in blu
- **Consonanti** — in grigio
- **Segni d'accento** (ˈ ˌ) — in rosso
- **Segni di lunghezza** (ː) — in viola

L'estensione regola automaticamente l'altezza delle righe per evitare sovrapposizioni e scala la dimensione del font IPA in base alla lunghezza della parola.

---

## Dizionario al passaggio (WordNet)

L'estensione include un dizionario inglese integrato basato su WordNet (oltre 82.000 parole). Nelle impostazioni puoi scegliere tra diverse modalità al passaggio del mouse:

| Modalità | Comportamento |
|----------|----------------|
| **Dizionario** | Al passaggio: IPA + definizione in inglese + pulsante pronuncia |
| **Tooltip** | Al passaggio: IPA + pulsante pronuncia (senza definizioni) |
| **Disattivato** | Nessun effetto al passaggio |

In **modalità Dizionario**, il tooltip mostra:
- La parola e la trascrizione IPA
- Un pulsante pronuncia (clic per ascoltare)
- Le definizioni in inglese da WordNet

> **Suggerimento:** I dati del dizionario si caricano su richiesta quando la modalità Dizionario è attiva e vengono scaricati quando passi ad altre modalità, per risparmiare memoria.

---

## Lettore PDF

IPA Reader include un lettore PDF integrato che consente di leggere documenti PDF con annotazioni IPA, dizionario, sintesi vocale e traduzione — tutte le funzioni disponibili sulle pagine web sono ora disponibili anche per i PDF.

### Aprire un PDF

**Metodo 1: Dal popup**  
Clicca l'icona dell'estensione, poi "Open PDF Reader". Trascina un file PDF o clicca "Choose File" per aprire un PDF locale. Puoi anche incollare l'URL di un PDF.

**Metodo 2: Menu contestuale**  
Clic destro su un collegamento `.pdf` in una pagina e scegli "Open PDF with IPA Reader".

**Metodo 3: Rilevamento automatico**  
Con "PDF Smart Detection" attivo nelle impostazioni, l'estensione reindirizza automaticamente gli URL che terminano in `.pdf` al lettore integrato. Se un PDF viene rilevato ma non reindirizzato (ad esempio nel visualizzatore integrato di Chrome), vedrai notifiche e inviti ad aprirlo in IPA Reader.

### Funzioni del lettore PDF

- **Annotazioni IPA** — Tutte le funzioni IPA funzionano sul testo del PDF, inclusa la modalità pagina intera e i tooltip al passaggio
- **Dizionario al clic** — Clic su una parola per la definizione (nei PDF si usa il clic invece del passaggio per una lettura meno dispersiva)
- **Barra di selezione** — Seleziona il testo per parlare, tradurre o copiare
- **Barra laterale** — Indice e miniature di pagina
- **Ricerca** — Cerca testo nel PDF
- **Temi** — Temi di lettura Scuro, Chiaro e Seppia
- **Zoom** — Più livelli di zoom, tra cui Automatico, Adatta pagina e Larghezza pagina
- **Scorciatoie da tastiera** — Frecce per navigare, +/- per zoom, Ctrl/Cmd+F per la ricerca

---

## Forme deboli/forti

Molte parole funzionali comuni in inglese hanno due pronunce:

- **Forma debole** — la pronuncia ridotta nel parlato naturale collegato (es. "the" → /ðə/)
- **Forma forte** — la pronuncia piena per enfasi o da sola (es. "the" → /ðiː/)

Con "Mostra forme deboli/forti" attivo, passando il mouse su queste parole il tooltip mostra entrambe le varianti, etichettate "WEAK" e "STRONG". Così capisci come cambia la pronuncia nel parlato naturale.

Le parole coperte includono: articoli (the, a, an), preposizioni (to, for, of, from, at, as, than), congiunzioni (and, or, but), pronomi (you, your, her, him, his, them, us, our, there), verbi ausiliari (am, is, are, was, were, been, can, could, would, should, must, shall, will, do, does, have, has, had) e altro.

---

## Lettura selezione e karaoke

La lettura della selezione consente di selezionare testo in inglese e leggerlo ad alta voce con un clic — ideale per la pronuncia delle frasi e la pratica di lettura.

**Metodo 1: Barra della selezione**  
Seleziona testo in inglese con il mouse. Compare una barra compatta vicino alla selezione con pulsanti 🔊 parla e 🌐 traduci. Clicca parla per riprodurre. Durante la lettura ogni parola viene evidenziata in tempo reale (effetto karaoke).

**Metodo 2: Menu contestuale**  
Dopo aver selezionato testo in inglese, clic destro e scegli "IPA Reader > Leggi selezione".

**Metodo 3: Scorciatoia da tastiera**  
Seleziona il testo e premi `Alt+Shift+S` (Mac: `Ctrl+Shift+S`) per parlare.

> **Suggerimento:** L'evidenziazione karaoke funziona al meglio se il browser supporta gli eventi di confine delle parole TTS. In caso contrario, l'estensione usa un fallback basato sul tempo per un'evidenziazione fluida.

---

## Traduzione

Seleziona qualsiasi testo sulla pagina e usa la traduzione per ottenere risultati immediati.

**Metodo 1: Barra della selezione**  
Seleziona il testo, poi clicca il pulsante 🌐 traduci nella barra. Sotto compare un fumetto con il risultato e un pulsante copia.

**Metodo 2: Menu contestuale**  
Seleziona il testo, clic destro e scegli "IPA Reader > Traduci selezione".

**Metodo 3: Scorciatoia da tastiera**  
Seleziona il testo e premi `Alt+Shift+T` (Mac: `Ctrl+Shift+T`) per tradurre.

**Motori di traduzione:**

- **Bing Translate** (predefinito) — basato su Microsoft Translator
- **Google Translate** — basato su Google

Entrambi i motori supportano **108 lingue di destinazione**.

Puoi cambiare motore e lingua di destinazione nelle impostazioni dell'estensione. La lingua di destinazione viene rilevata automaticamente dalla lingua del browser.

> **Suggerimento:** Clicca fuori dalla barra o dal fumetto per chiuderli.

---

## Scorciatoie da tastiera

| Scorciatoia | Scorciatoia Mac | Azione |
|-------------|-----------------|--------|
| `Alt+Shift+I` | `Ctrl+Shift+I` | Attiva/disattiva annotazioni IPA |
| `Alt+Shift+S` | `Ctrl+Shift+S` | Leggi il testo selezionato |
| `Alt+Shift+T` | `Ctrl+Shift+T` | Traduci il testo selezionato |

> **Suggerimento:** Puoi personalizzare queste scorciatoie in Chrome in `chrome://extensions/shortcuts`.

---

## Guida impostazioni

| Impostazione | Descrizione |
|--------------|-------------|
| **Attiva IPA** | Interruttore principale per attivare o disattivare le annotazioni IPA |
| **IPA pagina intera** | Se attivo, mostra IPA a colori per tutte le parole in inglese sopra il testo |
| **Stile IPA** | Scegli tra inglese americano e britannico per IPA e pronuncia |
| **Modalità al passaggio** | Comportamento al passaggio del mouse: Dizionario (IPA + definizioni + audio), Tooltip (IPA + audio) o Disattivato |
| **Forme deboli/forti** | Mostra varianti debole e forte per le parole funzionali comuni |
| **Velocità lettura frasi** | Regola la velocità della lettura delle frasi (le singole parole non sono influenzate) |
| **Motore di traduzione** | Scegli tra Bing Translate e Google Translate |
| **Lingua di destinazione** | Imposta la lingua di destinazione della traduzione (rilevata automaticamente dalla lingua del browser) |
| **Rilevamento intelligente PDF** | Se attivo, reindirizza automaticamente gli URL dei PDF al lettore integrato e mostra notifiche quando vengono rilevati PDF |

---

## FAQ

**D: Perché non funziona su alcune pagine?**  
R: Per motivi di sicurezza, le estensioni non possono essere eseguite su pagine speciali come `chrome://`, impostazioni del browser o Chrome Web Store.

**D: E se manca l'IPA per alcune parole?**  
R: Il dizionario IPA copre oltre 134.000 parole in inglese americano e oltre 67.000 in inglese britannico. Per le parole assenti, l'estensione usa lemmatizzazione e G2P basato su regole per generare IPA approssimativo, contrassegnato con ≈ o ~ nel tooltip.

**D: Nessun suono con text-to-speech?**  
R: Controlla il volume di sistema e assicurati che i pacchetti vocali in inglese siano installati. Il supporto varia tra browser e sistemi operativi.

**D: La modalità pagina intera influenza il layout?**  
R: Le annotazioni IPA richiedono spazio extra. L'estensione regola l'altezza delle righe per ridurre l'impatto. Se disturba ancora, disattiva la modalità pagina intera e usa i tooltip al passaggio.

**D: Cosa significano i simboli ~ e ≈ nei tooltip?**  
R: ~ indica IPA generato da conversione basata su regole (G2P) anziché dal dizionario. ≈ indica IPA derivato da una parola base correlata tramite lemmatizzazione. Possono essere meno precisi delle voci del dizionario.

**D: La traduzione non funziona?**  
R: Serve una connessione Internet. Se Bing Translate fallisce, prova Google Translate nelle impostazioni. Alcune reti possono bloccare l'accesso ai servizi di traduzione.

**D: Come apro un PDF con IPA Reader?**  
R: Puoi farlo in diversi modi: clic su "Open PDF Reader" nel popup, clic destro su un collegamento PDF e "Open PDF with IPA Reader", oppure attiva "PDF Smart Detection" nelle impostazioni per reindirizzare automaticamente gli URL dei PDF al lettore integrato.

**D: PDF Smart Detection è attivo ma alcuni PDF non vengono reindirizzati?**  
R: Il reindirizzamento automatico funziona per URL che terminano in `.pdf`. Per PDF serviti senza estensione `.pdf` o nel visualizzatore integrato di Chrome compariranno notifica e badge che invitano ad aprire il file in IPA Reader.

**D: Posso usare il dizionario offline?**  
R: Sì. Il dizionario WordNet (oltre 82.000 parole) è incluso interamente nell'estensione. Tutte le ricerche avvengono in locale, senza connessione di rete.

---

## Link correlati

- [Informativa sulla privacy](../privacy-policy)
- [Supporto e feedback](../support)

---
