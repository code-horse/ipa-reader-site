---
layout: bare
title: Extensió IPA Reader - Guia d'ús
lang: ca
---

# IPA Reader - Guia d'ús

> Versió: v1.4.1

## Introducció

IPA Reader és una extensió del navegador dissenyada per a estudiants d'anglès. Afegeix anotacions de pronunciació IPA (Alfabet Fonètic Internacional) als mots en anglès de les pàgines web i dels PDF, amb suport per als accents americà i britànic. També inclou un diccionari anglès integrat, text a veu i traducció — ajudant-vos a aprendre la pronunciació anglesa més fàcilment.

---

## Característiques principals

- **Mode IPA a tota la pàgina** — Afegeix anotacions IPA a tots els mots en anglès amb un sol clic; els símbols IPA tenen color segons el tipus (vocals, consonants, accents) per facilitar la lectura
- **Diccionari al passar el cursor** — Passeu el cursor sobre les paraules per veure definicions en anglès (més de 82 mil mots de WordNet), IPA amb símbols codificats per colors i botons de pronunciació; trieu mode Diccionari, Indicador emergent o Desactivat
- **Lector PDF** — Lector PDF integrat amb anotacions IPA, diccionari, veu i traducció; admet arrossegar i deixar anar, càrrega per URL i detecció automàtica de PDF amb redirecció intel·ligent
- **Formes febles/fortes** — Mostra automàticament les variants de pronunciació feble i forta de paraules funcionals habituals (p. ex. «the», «to», «can»), per dominar el discurs enllaçat natural
- **Accents americà i britànic** — Canvieu entre IPA d'anglès americà (en-US) i anglès britànic (en-GB)
- **Text-to-Speech** — Feu clic al botó d'altaveu per escoltar la pronunciació segons l'accent seleccionat
- **Lectura de selecció amb efecte karaoke** — Seleccioneu text en anglès: apareix una barra compacta amb botons per parlar i traduir; la lectura ressalta cada paraula en temps real (efecte karaoke) sincronitzada amb l'àudio
- **Traducció de la selecció** — Seleccioneu qualsevol text, feu clic a traduir a la barra per obtenir traducció instantània amb Bing o Google Translate, mostrada en una bombolla integrada
- **Desambiguació d'homògrafs** — Identifica automàticament paraules amb diverses pronunciacions (p. ex. «read», «live») i tria la correcta segons el context
- **Dreceres de teclat** — Accés ràpid a les funcions principals amb dreceres personalitzables
- **Interfície multilingüe** — Suporta 41 idiomes d'interfície

---

## Com utilitzar-ho

### Pas 1: Instal·lar l'extensió

Instal·leu **IPA Reader** des del [Chrome Web Store](https://chromewebstore.google.com/), o carregueu-la localment en mode desenvolupador.

### Pas 2: Obrir qualsevol pàgina web

Visiteu qualsevol pàgina web que contingui contingut en anglès.

### Pas 3: Activar l'IPA

Feu clic a la icona de l'extensió a la barra d'eines. Activeu «Activar IPA» i després «IPA a tota la pàgina» per anotar tots els mots. També podeu fer servir el botó flotant a la part inferior dreta.

### Pas 4: Veure l'IPA

Passeu el cursor sobre les paraules per veure eines emergents IPA amb símbols codificats per colors. Feu clic a la icona d'altaveu per escoltar la pronunciació. Per a paraules amb formes febles/fortes, l'eina emergent mostra les dues variants.

### Pas 5: Parlar i traduir el text seleccionat

Seleccioneu text en anglès amb el ratolí. A prop de la selecció apareix una barra compacta amb dos botons:

- **🔊 Parlar** — Llegeix el text seleccionat en veu alta amb ressaltat paraula per paraula tipus karaoke
- **🌐 Traduir** — Mostra una bombolla de traducció integrada sota la barra

També podeu fer clic dret i triar «IPA Reader > Speak Selection» o «IPA Reader > Translate Selection».

> **Consell:** Feu clic a la icona de l'extensió a la barra d'eines per obrir el panell de configuració i ajustar el tipus d'accent, la velocitat de lectura, el mode al passar el cursor (hover), el motor de traducció i més.

---

## Mode IPA a tota la pàgina

Quan el mode IPA a tota la pàgina està activat, cada mot en anglès rep una anotació IPA per sobre del text amb ruby text. Els símbols IPA tenen color segons el tipus:

- **Vocals** — ressaltades en blau
- **Consonants** — en gris
- **Accents** (ˈ ˌ) — en vermell
- **Signes de longitud** (ː) — en porpra

L'extensió ajusta automàticament l'alçada de línia per evitar solapaments i escala la mida de la lletra IPA segons la longitud de la paraula.

---

## Diccionari al passar el cursor

L'extensió inclou un diccionari anglès integrat basat en WordNet (més de 82.000 mots). A la configuració podeu triar entre diversos modes al passar el cursor:

| Mode | Comportament |
|------|--------------|
| **Diccionari** | Al passar el cursor: IPA + definició en anglès + botó de pronunciació |
| **Indicador emergent** | Al passar el cursor: IPA + botó de pronunciació (sense definicions) |
| **Desactivat** | Sense efecte al passar el cursor |

En el **mode Diccionari**, l'indicador emergent mostra:
- El mot i la seva transcripció IPA
- Un botó de pronunciació (clic per escoltar)
- Definicions en anglès de WordNet

> **Consell:** Les dades del diccionari es carreguen sota demanda quan el mode Diccionari està actiu i s'alliberen en canviar a altres modes per estalviar memòria.

---

## Lector PDF

IPA Reader inclou un lector PDF integrat que us permet llegir documents PDF amb anotacions IPA, diccionari, veu i traducció — les mateixes funcions que a les pàgines web, ara també per als PDF.

### Obrir un PDF

**Mètode 1: Des del menú emergent**  
Feu clic a la icona de l'extensió i després a «Open PDF Reader». Arrossegueu i deixeu anar un fitxer PDF o feu clic a «Choose File» per obrir un PDF local. També podeu enganxar un URL de PDF.

**Mètode 2: Menú contextual**  
Feu clic dret en qualsevol enllaç `.pdf` d'una pàgina web i trieu «Open PDF with IPA Reader».

**Mètode 3: Detecció automàtica**  
Quan «PDF Smart Detection» està activat a la configuració, l'extensió redirigeix automàticament els URL que acaben en `.pdf` al lector integrat. Si es detecta un PDF però no es redirigeix (p. ex. el visor integrat de Chrome), veureu notificacions i indicacions per obrir-lo a IPA Reader.

### Funcions del lector PDF

- **Anotacions IPA** — Totes les funcions IPA funcionen sobre el text del PDF, incloent el mode de tota la pàgina i els indicadors emergents al passar el cursor
- **Diccionari per clic** — Feu clic a qualsevol paraula per veure'n la definició (al PDF s'utilitza el clic en lloc del passar el cursor per una lectura sense distraccions)
- **Barra de selecció** — Seleccioneu text per parlar, traduir o copiar
- **Barra lateral** — Índex (esquema) i miniatures de pàgina
- **Cerca** — Cerca de text al PDF
- **Temes** — Temes de lectura fosc, clar i sèpia
- **Zoom** — Diversos nivells de zoom: Automàtic, Ajust a pàgina i Amplada de pàgina
- **Dreceres de tecles** — Fletxes per navegar, +/- per al zoom, Ctrl/Cmd+F per cercar

---

## Formes febles/fortes

Moltes paraules funcionals habituals tenen dues pronunciacions:

- **Forma feble** — la pronunciació reduïda en el discurs enllaçat natural (p. ex. «the» → /ðə/)
- **Forma forta** — la pronunciació completa per èmfasi o aïllada (p. ex. «the» → /ðiː/)

Quan «Mostrar formes febles/fortes» està activat, en passar el cursor sobre aquestes paraules l'eina emergent mostra les dues variants, etiquetades com a «WEAK» i «STRONG», per entendre com canvia la pronunciació en la parla natural.

Les paraules incloses cobreixen: articles (the, a, an), preposicions (to, for, of, from, at, as, than), conjuncions (and, or, but), pronoms (you, your, her, him, his, them, us, our, there), verbs auxiliars (am, is, are, was, were, been, can, could, would, should, must, shall, will, do, does, have, has, had) i més.

---

## Lectura de selecció i karaoke

La lectura de selecció us permet seleccionar text en anglès i llegir-lo en veu alta amb un sol clic — ideal per aprendre la pronunciació de frases i practicar la lectura.

**Mètode 1: Barra de selecció**  
Seleccioneu text en anglès amb el ratolí. Apareix una barra compacta a prop de la selecció amb els botons 🔊 parlar i 🌐 traduir. Feu clic a parlar per reproduir. Durant la lectura cada paraula es ressalta en temps real (efecte karaoke).

**Mètode 2: Menú contextual**  
Després de seleccionar text en anglès, feu clic dret i trieu «IPA Reader > Speak Selection».

**Mètode 3: Drecera de teclat**  
Seleccioneu el text i premeu `Alt+Shift+S` (Mac: `Ctrl+Shift+S`) per parlar.

> **Consell:** El ressaltat karaoke funciona millor si el navegador admet esdeveniments de límit de paraula TTS. Si no, l'extensió usa un recurs temporal per mantenir un ressaltat fluid.

---

## Traducció

Seleccioneu qualsevol text de la pàgina i utilitzeu la traducció per obtenir resultats immediats.

**Mètode 1: Barra de selecció**  
Seleccioneu el text i feu clic al botó 🌐 traduir de la barra. Sota apareix una bombolla amb el resultat i un botó per copiar.

**Mètode 2: Menú contextual**  
Seleccioneu el text, feu clic dret i trieu «IPA Reader > Translate Selection».

**Mètode 3: Drecera de teclat**  
Seleccioneu el text i premeu `Alt+Shift+T` (Mac: `Ctrl+Shift+T`) per traduir.

**Motors de traducció:**

- **Bing Translate** (per defecte) — amb Microsoft Translator
- **Google Translate** — amb Google

Tots dos motors admeten **108 llengües de destinació**.

Podeu canviar el motor i l'idioma de destinació a la configuració de l'extensió. L'idioma de destinació es detecta automàticament des de l'idioma del navegador.

> **Consell:** Feu clic fora de la barra o la bombolla per tancar-les.

---

## Dreceres de teclat

| Drecera | Drecera Mac | Acció |
|---------|-------------|-------|
| `Alt+Shift+I` | `Ctrl+Shift+I` | Activar/desactivar anotacions IPA |
| `Alt+Shift+S` | `Ctrl+Shift+S` | Parlar el text seleccionat |
| `Alt+Shift+T` | `Ctrl+Shift+T` | Traduir el text seleccionat |

> **Consell:** Podeu personalitzar aquestes dreceres a Chrome a `chrome://extensions/shortcuts`.

---

## Guia de configuració

| Configuració | Descripció |
|--------------|------------|
| **Activar IPA** | Interruptor principal per activar o desactivar les anotacions IPA |
| **IPA a tota la pàgina** | Si està activat, mostra IPA codificat per colors per a tots els mots en anglès per sobre del text |
| **Estil IPA** | Trieu entre anglès americà i britànic per a IPA i pronunciació |
| **Mode al passar el cursor** | Trieu el comportament: Diccionari (IPA + definicions + àudio), Indicador emergent (IPA + àudio) o Desactivat |
| **Formes febles/fortes** | Mostra variants feble i forta per a paraules funcionals habituals |
| **Velocitat de lectura de frases** | Ajusteu la velocitat de lectura de frases (les paraules individuals no es veuen afectades) |
| **Motor de traducció** | Trieu entre Bing Translate i Google Translate |
| **Idioma de destinació** | Definiu l'idioma de destinació de la traducció (detecció automàtica des de l'idioma del navegador) |
| **Detecció intel·ligent de PDF** | Si està activat, redirigeix automàticament els URL de PDF al lector integrat i mostra notificacions quan es detecta un PDF |

---

## Preguntes freqüents

**P: Per què no funciona en algunes pàgines?**  
R: Per motius de seguretat, les extensions no poden executar-se en pàgines especials com `chrome://`, la configuració del navegador o el Chrome Web Store.

**P: Què passa si falta IPA per algunes paraules?**  
R: El diccionari IPA cobreix més de 134.000 mots en anglès americà i més de 67.000 en anglès britànic. Per als que no hi són, l'extensió genera IPA aproximat mitjançant lematització i G2P basat en regles, marcat amb ≈ o ~ a l'indicador.

**P: No hi ha so del text-to-speech?**  
R: Comproveu el volum del sistema i assegureu-vos que teniu instal·lats paquets de veu en anglès. El suport varia segons navegadors i sistemes operatius.

**P: El mode de tota la pàgina afecta el disseny?**  
R: Les anotacions IPA necessiten espai addicional. L'extensió ajusta l'alçada de línia per reduir l'impacte. Si encara molesta, desactiveu el mode de tota la pàgina i utilitzeu les eines emergents al passar el cursor.

**P: Què signifiquen els símbols ~ i ≈ als indicadors?**  
R: ~ indica que l'IPA s'ha generat per conversió per regles (G2P) i no des del diccionari. ≈ indica que s'ha derivat d'una paraula base relacionada per lematització. Poden ser menys precisos que les entrades del diccionari.

**P: La traducció no funciona?**  
R: Cal connexió a Internet. Si Bing Translate falla, proveu Google Translate a la configuració. Algunes xarxes poden bloquejar l'accés als serveis de traducció.

**P: Com obro un PDF amb IPA Reader?**  
R: Podeu obrir PDF de diverses maneres: «Open PDF Reader» al menú emergent, clic dret en un enllaç PDF i «Open PDF with IPA Reader», o activeu «PDF Smart Detection» a la configuració per redirigir automàticament els URL de PDF al lector integrat.

**P: «PDF Smart Detection» està activat però alguns PDF no es redirigeixen?**  
R: La redirecció automàtica funciona per a URL que acaben en `.pdf`. Per a PDF servits sense extensió `.pdf` o oberts amb el visor integrat de Chrome, veureu una notificació i una insígnia que us conviden a obrir-los a IPA Reader.

**P: Puc fer servir el diccionari sense connexió?**  
R: Sí. El diccionari WordNet (més de 82.000 mots) va inclòs dins l'extensió. Totes les consultes es fan localment sense cap connexió de xarxa.

---

## Enllaços relacionats

- [Política de privacitat](../privacy-policy)
- [Suport i comentaris](../support)

---
