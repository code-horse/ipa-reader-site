---
layout: bare
title: IPA Reader Extension - User Guide
lang: en
---

# IPA Reader - User Guide

> Version: v1.3.0

## Introduction

IPA Reader is a browser extension designed for English learners. It adds IPA (International Phonetic Alphabet) pronunciation annotations to English words on web pages, supporting both American and British English accents, helping you learn English pronunciation more easily.

---

## Main Features

- **Whole Page IPA Mode** — Add IPA annotations to all English words on the page with one click; IPA symbols are color-coded by type (vowels, consonants, stress marks) for easy reading
- **Weak/Strong Forms** — Automatically display weak and strong pronunciation variants for common function words (e.g. "the", "to", "can"), helping you master natural connected speech
- **American & British Accents** — Switch between American English (en-US) and British English (en-GB) IPA
- **Text-to-Speech** — Click the speaker button to hear pronunciation matching your selected accent
- **Selection Speech with Karaoke Effect** — Select any English text, a compact toolbar appears with speak and translate buttons; speech plays with real-time word-by-word highlighting (karaoke effect) synced to the audio
- **Selection Translation** — Select any text, click the translate button in the toolbar to get instant translation via Bing or Google Translate, displayed in an inline bubble
- **Hover Tooltips** — Hover over annotated words to see IPA with color-coded symbols and pronunciation buttons
- **Heteronym Disambiguation** — Automatically identifies words with multiple pronunciations (e.g. "read", "live") and selects the correct one based on context
- **Keyboard Shortcuts** — Quick access to core features via customizable keyboard shortcuts
- **Multilingual Interface** — Supports 38 interface languages

---

## How to Use

### Step 1: Install the Extension

Install **IPA Reader** from the [Chrome Web Store](https://chromewebstore.google.com/), or load it locally in developer mode.

### Step 2: Open Any Web Page

Visit any web page containing English content.

### Step 3: Enable IPA

Click the extension icon in your browser toolbar. Toggle "Enable IPA" on, then toggle "Whole Page IPA" to annotate all words on the page. You can also click the floating button at the bottom right.

### Step 4: View IPA

Hover over words to see IPA tooltips with color-coded phonetic symbols. Click the speaker icon to hear pronunciation. For words with weak/strong forms, the tooltip shows both variants.

### Step 5: Speak and Translate Selected Text

Select any English text with your mouse. A compact toolbar appears near the selection with two buttons:
- **🔊 Speak** — Reads the selected text aloud with karaoke-style word-by-word highlighting
- **🌐 Translate** — Shows an inline translation bubble below the toolbar

You can also right-click and choose "IPA Reader > Speak Selection" or "IPA Reader > Translate Selection".

> **Tip:** Click the extension icon in your browser toolbar to open the settings panel and adjust accent type, speech rate, translation engine, and more.

---

## Whole Page IPA Mode

When whole page IPA mode is enabled, every English word on the page gets an IPA annotation displayed above it using ruby text. The IPA symbols are color-coded for easy reading:

- **Vowels** — highlighted in blue
- **Consonants** — displayed in gray
- **Stress marks** (ˈ ˌ) — highlighted in red
- **Length marks** (ː) — highlighted in purple

The extension automatically adjusts line height to prevent annotations from overlapping with text, and scales IPA font size based on word length for a clean layout.

---

## Weak/Strong Forms

Many common English function words have two pronunciations:

- **Weak form** — the reduced pronunciation used in natural connected speech (e.g. "the" → /ðə/)
- **Strong form** — the full pronunciation used for emphasis or in isolation (e.g. "the" → /ðiː/)

When "Show weak/strong forms" is enabled, hovering over these words shows both variants in the tooltip, labeled as "WEAK" and "STRONG". This helps you understand how pronunciation changes in natural speech.

Covered words include: articles (the, a, an), prepositions (to, for, of, from, at, as, than), conjunctions (and, or, but), pronouns (you, your, her, him, his, them, us, our, there), auxiliary verbs (am, is, are, was, were, been, can, could, would, should, must, shall, will, do, does, have, has, had), and more.

---

## Selection Speech & Karaoke

The selection speech feature allows you to select any English text and read it aloud with one click — perfect for learning sentence pronunciation and reading practice.

**Method 1: Selection Toolbar**  
Select English text with your mouse. A compact toolbar appears near the selection with a 🔊 speak button and a 🌐 translate button. Click the speak button to play. As the text is read aloud, each word is highlighted in real time (karaoke effect), helping you follow along.

**Method 2: Right-Click Menu**  
After selecting English text, right-click and choose "IPA Reader > Speak Selection".

**Method 3: Keyboard Shortcut**  
Select text and press `Alt+Shift+S` (Mac: `Ctrl+Shift+S`) to speak.

> **Tip:** The karaoke highlighting effect works best when your browser supports TTS word boundary events. If not supported, the extension uses a timing-based fallback for smooth highlighting.

---

## Translation

Select any text on the page and use the translation feature to get instant translations.

**Method 1: Selection Toolbar**  
Select text, then click the 🌐 translate button in the toolbar. A translation bubble appears below showing the result, with a copy button.

**Method 2: Right-Click Menu**  
Select text, right-click and choose "IPA Reader > Translate Selection".

**Method 3: Keyboard Shortcut**  
Select text and press `Alt+Shift+T` (Mac: `Ctrl+Shift+T`) to translate.

**Translation Engines:**
- **Bing Translate** (default) — Powered by Microsoft Translator
- **Google Translate** — Powered by Google

Both engines support **108 target languages**.

You can switch the translation engine and target language in the extension settings. The target language is automatically detected from your browser language.

> **Tip:** Click anywhere outside the toolbar or bubble to dismiss them.

---

## Keyboard Shortcuts

| Shortcut | Mac Shortcut | Action |
|----------|-------------|--------|
| `Alt+Shift+I` | `Ctrl+Shift+I` | Toggle IPA annotations on/off |
| `Alt+Shift+S` | `Ctrl+Shift+S` | Speak selected text |
| `Alt+Shift+T` | `Ctrl+Shift+T` | Translate selected text |

> **Tip:** You can customize these shortcuts in Chrome at `chrome://extensions/shortcuts`.

---

## Settings Guide

| Setting | Description |
|---------|-------------|
| **Enable IPA** | Master switch to enable or disable the IPA annotation feature |
| **Whole Page IPA** | When enabled, displays color-coded IPA for all English words above the text |
| **IPA Style** | Choose between American English and British English IPA and pronunciation |
| **Show hover tooltip** | Show IPA tooltip with pronunciation button on mouse hover |
| **Show weak/strong forms** | Display weak and strong pronunciation variants for common function words |
| **Sentence Speech Rate** | Adjust the speed of sentence reading (single word speech is not affected) |
| **Translation Engine** | Choose between Bing Translate and Google Translate |
| **Target Language** | Set the translation target language (auto-detected from browser language) |

---

## FAQ

**Q: Why doesn't it work on some pages?**  
A: For security reasons, browser extensions cannot run on special pages like `chrome://`, browser settings, or the Chrome Web Store.

**Q: What if IPA is missing for some words?**  
A: The IPA dictionary covers common English words. For words not in the dictionary, the extension uses lemmatization and rule-based G2P (grapheme-to-phoneme) conversion to generate approximate IPA. These are marked with ≈ or ~ in the tooltip.

**Q: No sound from text-to-speech?**  
A: Please check your system volume settings and ensure English voice packs are installed. Speech support varies across browsers and operating systems.

**Q: Whole page mode affects layout?**  
A: IPA annotations require extra space. The extension automatically adjusts line height to minimize layout impact. If it still affects reading, disable whole page mode and use hover tooltips instead.

**Q: What do the ~ and ≈ symbols in the tooltip mean?**  
A: The ~ symbol indicates the IPA was generated by rule-based conversion (G2P) rather than from the dictionary. The ≈ symbol indicates the IPA was derived from a related base word through lemmatization. These may be less accurate than dictionary entries.

**Q: Translation not working?**  
A: Translation requires an internet connection. If Bing Translate fails, try switching to Google Translate in the settings. Some network environments may block access to translation services.

---

## Related Links

- [Privacy Policy](../privacy-policy)
- [Support & Feedback](../support)

---
