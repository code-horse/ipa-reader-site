---
layout: bare
title: IPA Reader Erweiterung - Benutzerhandbuch
lang: de
---

# IPA Reader - Benutzerhandbuch

> Version: v1.4.0

## Einführung

IPA Reader ist eine Browsererweiterung für Englischlernende. Sie fügt englischen Wörtern auf Webseiten und in PDFs IPA (Internationales Phonetisches Alphabet) Aussprache-Annotationen hinzu und unterstützt sowohl amerikanisches als auch britisches Englisch. Außerdem enthält sie ein integriertes englisches Wörterbuch, Text-zu-Sprache und Übersetzung — damit lernen Sie die englische Aussprache leichter.

---

## Hauptfunktionen

- **Ganzseiten-IPA-Modus** — Fügen Sie mit einem Klick IPA-Annotationen zu allen englischen Wörtern auf der Seite hinzu, mit farbcodierten IPA-Symbolen (Vokale, Konsonanten, Betonungszeichen) für einfaches Lesen
- **Hover-Wörterbuch** — Fahren Sie mit der Maus über Wörter, um englische Definitionen (über 82.000 Einträge aus WordNet), IPA mit farbcodierten Symbolen und Aussprache-Buttons zu sehen; wählen Sie zwischen Modus Wörterbuch, Tooltip, Nur sprechen oder Aus
- **PDF-Leser** — Integrierter PDF-Leser mit IPA, Wörterbuch, Sprachausgabe und Übersetzung; Drag & Drop, URL-Laden und automatische PDF-Erkennung mit intelligenter Weiterleitung
- **Schwache/starke Formen** — Automatische Anzeige der schwachen und starken Aussprachevarianten von Funktionswörtern (z. B. the, to, can) für natürliches Sprechen
- **Amerikanischer & Britischer Akzent** — Wechseln Sie zwischen amerikanischem (en-US) und britischem (en-GB) IPA
- **Text-zu-Sprache** — Klicken Sie auf den Lautsprecher-Button, um die Aussprache passend zu Ihrem gewählten Akzent zu hören
- **Auswahl-Vorlesen mit Karaoke-Effekt** — Wählen Sie englischen Text: Eine kompakte Symbolleiste mit Vorlesen- und Übersetzen-Buttons erscheint; die Wiedergabe erfolgt mit Echtzeit-Wort-für-Wort-Hervorhebung (Karaoke-Effekt), synchron zum Audio
- **Auswahl-Übersetzung** — Wählen Sie beliebigen Text, klicken Sie auf den Übersetzen-Button in der Symbolleiste für sofortige Übersetzung über Bing oder Google Translate, angezeigt in einer eingebetteten Blase
- **Homographen-Erkennung** — Automatische Erkennung von Wörtern mit mehreren Aussprachen (z. B. read, live) und Auswahl der richtigen je nach Kontext
- **Tastenkürzel** — Schneller Zugriff auf Kernfunktionen über anpassbare Tastenkürzel
- **Mehrsprachige Oberfläche** — Unterstützt 38 Oberflächensprachen

---

## Verwendung

### Schritt 1: Erweiterung installieren

Installieren Sie **IPA Reader** aus dem [Chrome Web Store](https://chromewebstore.google.com/) oder laden Sie sie lokal im Entwicklermodus.

### Schritt 2: Beliebige Webseite öffnen

Besuchen Sie eine beliebige Webseite mit englischem Inhalt.

### Schritt 3: IPA aktivieren

Klicken Sie auf das Erweiterungssymbol in der Browser-Symbolleiste. Schalten Sie „IPA aktivieren“ ein, dann „Ganzseiten-IPA“, um alle Wörter auf der Seite zu annotieren. Sie können auch den schwebenden Button unten rechts verwenden.

### Schritt 4: IPA anzeigen

Fahren Sie mit der Maus über Wörter, um IPA-Tooltips zu sehen, klicken Sie auf das Lautsprecher-Symbol, um die Aussprache zu hören. Bei Wörtern mit schwachen/starken Formen zeigt der Tooltip beide Varianten.

### Schritt 5: Ausgewählten Text vorlesen und übersetzen

Wählen Sie englischen Text mit der Maus aus. In der Nähe der Auswahl erscheint eine kompakte Symbolleiste mit zwei Buttons:
- **🔊 Vorlesen** — Liest den ausgewählten Text mit Karaoke-artiger Wort-für-Wort-Hervorhebung vor
- **🌐 Übersetzen** — Zeigt eine eingebettete Übersetzungsblase unter der Symbolleiste

Sie können auch rechtsklicken und „IPA Reader > Speak Selection“ oder „IPA Reader > Translate Selection“ wählen.

> **Tipp:** Klicken Sie auf das Erweiterungssymbol in der Browser-Symbolleiste, um das Einstellungsfenster zu öffnen und Akzenttyp, Sprechgeschwindigkeit, Hover-Modus, Übersetzungs-Engine und mehr anzupassen.

---

## Ganzseiten-IPA-Modus

Wenn der Ganzseiten-IPA-Modus aktiv ist, erhält jedes englische Wort auf der Seite eine IPA-Annotation darüber als Ruby-Text. Die IPA-Symbole sind farbcodiert:

- **Vokale** — blau hervorgehoben
- **Konsonanten** — grau dargestellt
- **Betonungszeichen** (ˈ ˌ) — rot hervorgehoben
- **Längenzeichen** (ː) — violett hervorgehoben

Die Erweiterung passt den Zeilenabstand automatisch an und skaliert die IPA-Schriftgröße je nach Wortlänge.

---

## Hover-Wörterbuch

Die Erweiterung enthält ein integriertes englisches Wörterbuch auf Basis von WordNet (über 82.000 Wörter). In den Einstellungen können Sie mehrere Hover-Modi wählen:

| Modus | Verhalten |
|-------|-----------|
| **Wörterbuch** | Hover zeigt IPA + englische Definition + Aussprache-Button |
| **Tooltip** | Hover zeigt IPA + Aussprache-Button (ohne Definitionen) |
| **Nur sprechen** | Klick auf ein Wort spielt die Aussprache ab (ohne Tooltip) |
| **Aus** | Kein Hover-Effekt |

Im Modus **Wörterbuch** zeigt der Tooltip:
- Das Wort und seine IPA-Transkription
- Einen Aussprache-Button (Klick zum Abspielen)
- Englische Definitionen aus WordNet

> **Tipp:** Die Wörterbuchdaten werden bei aktiviertem Wörterbuch-Modus bei Bedarf geladen und beim Wechsel zu anderen Modi entladen, um Speicher zu sparen.

---

## PDF-Leser

IPA Reader enthält einen integrierten PDF-Leser, mit dem Sie PDF-Dokumente mit IPA, Wörterbuch, Sprachausgabe und Übersetzung lesen können — dieselben Funktionen wie auf Webseiten, jetzt auch für PDFs.

### PDF öffnen

**Methode 1: Über das Popup**  
Klicken Sie auf das Erweiterungssymbol, dann auf „Open PDF Reader“. Ziehen Sie eine PDF-Datei per Drag & Drop hinein oder klicken Sie auf „Choose File“, um eine lokale PDF zu öffnen. Sie können auch eine PDF-URL einfügen.

**Methode 2: Kontextmenü**  
Rechtsklick auf einen `.pdf`-Link auf einer Webseite, dann „Open PDF with IPA Reader“.

**Methode 3: Automatische Erkennung**  
Ist „PDF Smart Detection“ in den Einstellungen aktiviert, leitet die Erweiterung `.pdf`-URLs automatisch zum integrierten Leser um. Wird ein PDF erkannt, aber nicht umgeleitet (z. B. Chromes eingebaute Ansicht), erscheinen Hinweise, es in IPA Reader zu öffnen.

### Funktionen des PDF-Lesers

- **IPA-Annotationen** — Alle IPA-Funktionen gelten für PDF-Text, einschließlich Ganzseiten-Modus und Hover-Tooltips
- **Klick-Wörterbuch** — Klicken Sie auf ein Wort für die Definition (im PDF wird Klick statt Hover genutzt, um Ablenkung zu vermeiden)
- **Auswahl-Symbolleiste** — Text auswählen zum Vorlesen, Übersetzen oder Kopieren
- **Seitenleiste** — Inhaltsverzeichnis und Seitenminiaturen
- **Suche** — Textsuche im PDF, einschließlich Pinyin-zu-Zeichen-Suche für chinesische PDFs
- **Designs** — Dunkel, Hell und Sepia als Lesethemen
- **Zoom** — Mehrere Stufen, u. a. Auto, Seite anpassen und Seitenbreite
- **Tastenkürzel** — Pfeiltasten zur Navigation, +/- zum Zoomen, Strg/Cmd+F für die Suche

---

## Schwache/starke Formen

Viele häufige englische Funktionswörter haben zwei Aussprachen:

- **Schwache Form** — die reduzierte Aussprache in natürlicher Rede (z. B. „the“ → /ðə/)
- **Starke Form** — die volle Aussprache bei Betonung oder isoliert (z. B. „the“ → /ðiː/)

Ist „Schwache/starke Formen anzeigen“ aktiviert, zeigen Tooltips bei diesen Wörtern beide Varianten mit den Labels „WEAK“ und „STRONG“.

Erfasst sind u. a.: Artikel (the, a, an), Präpositionen (to, for, of, from, at, as, than), Konjunktionen (and, or, but), Pronomen (you, your, her, him, his, them, us, our, there), Hilfsverben (am, is, are, was, were, been, can, could, would, should, must, shall, will, do, does, have, has, had) und mehr.

---

## Auswahl-Vorlesen & Karaoke

Mit der Auswahl-Vorlesen-Funktion wählen Sie englischen Text und lesen ihn mit einem Klick vor — ideal für Satzaussprache und Leseübung.

**Methode 1: Auswahl-Symbolleiste**  
Wählen Sie englischen Text mit der Maus. Eine kompakte Symbolleiste mit 🔊 Vorlesen und 🌐 Übersetzen erscheint. Klicken Sie auf Vorlesen. Während der Wiedergabe wird jedes Wort in Echtzeit hervorgehoben (Karaoke-Effekt).

**Methode 2: Rechtsklick-Menü**  
Nach Auswahl von englischem Text rechtsklicken Sie und wählen „IPA Reader > Speak Selection“.

**Methode 3: Tastenkürzel**  
Wählen Sie Text und drücken Sie `Alt+Shift+S` (Mac: `Ctrl+Shift+S`).

> **Tipp:** Der Karaoke-Effekt funktioniert am besten, wenn der Browser TTS-Wortgrenzen-Ereignisse unterstützt. Andernfalls nutzt die Erweiterung einen zeitbasierten Fallback für flüssige Hervorhebung.

---

## Übersetzung

Wählen Sie beliebigen Text auf der Seite und nutzen Sie die Übersetzungsfunktion für sofortige Übersetzungen.

**Methode 1: Auswahl-Symbolleiste**  
Wählen Sie Text, klicken Sie auf 🌐 Übersetzen in der Symbolleiste. Darunter erscheint eine Übersetzungsblase mit Ergebnis und Kopier-Button.

**Methode 2: Rechtsklick-Menü**  
Wählen Sie Text, rechtsklicken Sie und wählen „IPA Reader > Translate Selection“.

**Methode 3: Tastenkürzel**  
Wählen Sie Text und drücken Sie `Alt+Shift+T` (Mac: `Ctrl+Shift+T`).

**Übersetzungs-Engines:**
- **Bing Übersetzen** (Standard) — von Microsoft Translator
- **Google Übersetzen** — von Google

Beide Engines unterstützen **108 Zielsprachen**.

Engine und Zielsprache stellen Sie in den Erweiterungseinstellungen ein. Die Zielsprache wird aus der Browsersprache erkannt.

> **Tipp:** Klicken Sie außerhalb der Symbolleiste oder Blase, um sie zu schließen.

---

## Tastenkürzel

| Tastenkürzel | Mac-Tastenkürzel | Aktion |
|----------|-------------|--------|
| `Alt+Shift+I` | `Ctrl+Shift+I` | IPA-Annotationen ein/aus |
| `Alt+Shift+S` | `Ctrl+Shift+S` | Auswahl vorlesen |
| `Alt+Shift+T` | `Ctrl+Shift+T` | Auswahl übersetzen |

> **Tipp:** Sie können diese Tastenkürzel in Chrome unter `chrome://extensions/shortcuts` anpassen.

---

## Einstellungsübersicht

| Einstellung | Beschreibung |
|-------------|--------------|
| **IPA aktivieren** | Hauptschalter zum Aktivieren oder Deaktivieren der IPA-Annotation |
| **Ganzseiten-IPA** | Wenn aktiviert, farbcodiertes IPA über allen englischen Wörtern |
| **Akzenttyp** | Wählen Sie zwischen amerikanischem und britischem Englisch für IPA und Aussprache |
| **Hover-Modus** | Hover-Verhalten: Wörterbuch (IPA + Definitionen + Audio), Tooltip (IPA + Audio), Nur sprechen (Klick zum Hören), oder Aus |
| **Schwache/starke Formen** | Schwache und starke Aussprachevarianten von Funktionswörtern anzeigen |
| **Satz-Sprechgeschwindigkeit** | Passen Sie die Geschwindigkeit des Satz-Vorlesens an (Einzelwort-Aussprache nicht betroffen) |
| **Übersetzungs-Engine** | Wählen Sie zwischen Bing Übersetzen und Google Übersetzen |
| **Zielsprache** | Zielsprache für Übersetzungen festlegen (automatisch aus der Browsersprache) |
| **PDF Smart Detection** | Wenn aktiviert, leitet PDF-URLs automatisch zum integrierten Leser um und zeigt Hinweise, wenn PDFs erkannt werden |

---

## FAQ

**F: Warum funktioniert es auf einigen Seiten nicht?**  
A: Aus Sicherheitsgründen können Browsererweiterungen nicht auf speziellen Seiten wie `chrome://`, Browser-Einstellungen oder dem Chrome Web Store ausgeführt werden.

**F: Was, wenn für einige Wörter kein IPA vorhanden ist?**  
A: Das IPA-Wörterbuch umfasst über 134.000 amerikanische und über 67.000 britische englische Wörter. Für Wörter außerhalb des Wörterbuchs generiert die Erweiterung näherungsweise IPA durch Lemmatisierung und regelbasiertes G2P, markiert mit ≈ oder ~ im Tooltip.

**F: Kein Ton bei Text-zu-Sprache?**  
A: Bitte überprüfen Sie Ihre System-Lautstärkeeinstellungen und stellen Sie sicher, dass englische Sprachpakete installiert sind. Die Sprachunterstützung variiert je nach Browser und Betriebssystem.

**F: Ganzseiten-Modus beeinflusst das Layout?**  
A: IPA-Annotationen benötigen zusätzlichen Platz. Die Erweiterung passt den Zeilenabstand an. Wenn es stört, deaktivieren Sie den Ganzseiten-Modus und nutzen Sie Hover-Tooltips.

**F: Was bedeuten die Symbole ~ und ≈ in den Tooltips?**  
A: ~ bedeutet, dass die IPA durch Regeln (G2P) generiert wurde, und ≈, dass sie von einem verwandten Grundwort abgeleitet wurde. Diese können weniger genau sein als Wörterbucheinträge.

**F: Übersetzung funktioniert nicht?**  
A: Übersetzung erfordert eine Internetverbindung. Wenn Bing Übersetzen fehlschlägt, wechseln Sie in den Einstellungen zu Google Übersetzen. Manche Netzwerke blockieren Übersetzungsdienste.

**F: Wie öffne ich ein PDF mit IPA Reader?**  
A: Klicken Sie im Popup auf „Open PDF Reader“, rechtsklicken Sie auf einen PDF-Link und wählen Sie „Open PDF with IPA Reader“, oder aktivieren Sie „PDF Smart Detection“, um PDF-URLs automatisch zum integrierten Leser umzuleiten.

**F: PDF Smart Detection ist an, aber manche PDFs werden nicht umgeleitet?**  
A: Die automatische Umleitung gilt vor allem für URLs, die mit `.pdf` enden. Für PDFs ohne diese Endung oder in Chromes eingebauter Ansicht erscheinen Benachrichtigung und Hinweis, das Dokument in IPA Reader zu öffnen.

**F: Kann ich das Wörterbuch offline nutzen?**  
A: Ja. Das WordNet-Wörterbuch (über 82.000 Wörter) ist vollständig in der Erweiterung enthalten. Alle Abfragen erfolgen lokal ohne Netzwerkverbindung.

---

## Verwandte Links

- [Datenschutzrichtlinie](../privacy-policy)
- [Support & Feedback](../support)

---
