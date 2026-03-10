---
layout: bare
title: Estensione IPA Reader - Guida utente
lang: it
---

# IPA Reader - Guida utente

> Versione: v1.2.1

## Introduzione

IPA Reader è un'estensione per browser progettata per chi studia l'inglese. Aggiunge annotazioni di pronuncia IPA (alfabeto fonetico internazionale) alle parole in inglese nelle pagine web, supportando sia l'accento americano che quello britannico, aiutandoti a imparare più facilmente la pronuncia dell'inglese.

---

## Funzionalità principali

- **Annotazione selezione** — Seleziona testo in inglese nelle pagine web per mostrare automaticamente IPA e pulsanti vocali
- **Modalità IPA pagina intera** — Aggiunge annotazioni IPA a tutte le parole in inglese della pagina con un clic
- **Accento americano e britannico** — Passa tra IPA americano (en-US) e britannico (en-GB)
- **Testo-to-Speech** — Clicca il pulsante altoparlante per ascoltare la pronuncia corrispondente all'accento selezionato
- **Lettura selezione** — Seleziona testo in inglese, clicca il pulsante flottante o tasto destro «Leggi selezione» per riprodurre
- **Tooltip al passaggio** — Passa il mouse sulle parole annotate per vedere IPA e pulsanti di pronuncia
- **Forme deboli/forti** — Visualizzazione automatica delle varianti di pronuncia debole e forte delle parole funzionali (es. the, to, can) per padroneggiare il parlato naturale
- **Disambiguazione omografi** — Identificazione automatica delle parole con più pronunce (es. read, live) e selezione corretta in base al contesto
- **Interfaccia multilingue** — Supporta 38 lingue dell'interfaccia

---

## Come usare

### Passo 1: Installare l'estensione

Installa **IPA Reader** da [Chrome Web Store](https://chromewebstore.google.com/), oppure caricala in locale in modalità sviluppatore.

### Passo 2: Aprire una pagina web

Visita una pagina web che contenga contenuti in inglese.

### Passo 3: Selezionare testo o usare il pulsante flottante

Seleziona il testo in inglese da annotare, oppure clicca il pulsante flottante in basso a destra per attivare la modalità IPA pagina intera.

### Passo 4: Visualizzare IPA

Passa il mouse sulle parole per vedere i tooltip IPA, clicca l'icona altoparlante per sentire la pronuncia.

### Passo 5: Leggere il testo selezionato

Seleziona testo in inglese con il mouse, clicca il pulsante 🔊 flottante per leggere; oppure tasto destro e scegli «Leggi selezione».

> **Suggerimento:** Clicca l'icona dell'estensione nella barra degli strumenti del browser per aprire il pannello impostazioni e regolare tipo di accento, velocità di lettura e altro.

---

## Lettura selezione

La funzione di lettura selezione permette di selezionare testo in inglese e leggerlo ad alta voce con un clic — perfetta per imparare la pronuncia delle frasi e fare esercizi di lettura.

**Metodo 1: Pulsante flottante**  
Seleziona testo in inglese con il mouse, compare un pulsante altoparlante in alto a destra della selezione — clicca per leggere.

**Metodo 2: Menu contestuale**  
Dopo aver selezionato testo in inglese, tasto destro e scegli «Leggi selezione» dal menu.

> **Suggerimento:** La lettura selezione usa la velocità delle frasi configurata nelle impostazioni. La pronuncia delle singole parole usa la velocità predefinita. La voce TTS corrisponde al tipo di accento selezionato (americano o britannico).

---

## Guida impostazioni

| Impostazione | Descrizione |
|--------------|-------------|
| **Attiva IPA** | Interruttore principale per attivare o disattivare la funzione di annotazione IPA |
| **IPA pagina intera** | Quando attivo, mostra IPA per tutte le parole in inglese (può influire sul layout della pagina) |
| **Tipo accento** | Scegli tra inglese americano e britannico per IPA e pronuncia |
| **Velocità frasi** | Regola la velocità di lettura delle frasi (la pronuncia delle singole parole non è influenzata) |
| **Forme deboli/forti** | Mostra le varianti di pronuncia debole e forte delle parole funzionali |
| **Tooltip al passaggio** | Mostra tooltip IPA al passaggio del mouse |

---

## FAQ

**D: Perché non funziona su alcune pagine?**  
R: Per motivi di sicurezza, le estensioni del browser non possono essere eseguite su pagine speciali come `chrome://`, impostazioni del browser o Chrome Web Store.

**D: E se manca l'IPA per alcune parole?**  
R: Il dizionario IPA copre le parole inglesi comuni. Per le parole non presenti, l'estensione genera un IPA approssimativo tramite lemmatizzazione e G2P, contrassegnato con ≈ o ~ nel tooltip.

**D: Nessun suono con text-to-speech?**  
R: Controlla le impostazioni del volume di sistema e assicurati che i pacchetti vocali in inglese siano installati. Il supporto vocale varia tra browser e sistemi operativi.

**D: La modalità pagina intera influenza il layout?**  
R: Le annotazioni IPA richiedono spazio extra, che può influire sul layout originale della pagina. Se influisce sulla lettura, disattiva la modalità pagina intera e usa invece i tooltip al passaggio.


**D: Cosa significano i simboli ~ e ≈ nei tooltip?**  
R: ~ significa che l'IPA è stato generato da regole (G2P), e ≈ che è stato derivato da una parola base correlata. Possono essere meno precisi delle voci del dizionario.

---

## Link correlati

- [Informativa sulla privacy](../privacy-policy)
- [Supporto e feedback](../support)

---
