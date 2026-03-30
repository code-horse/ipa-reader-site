---
layout: bare
title: Extension IPA Reader - Guide utilisateur
lang: fr
---

# IPA Reader - Guide utilisateur

> Version : v1.3.0

## Introduction

IPA Reader est une extension de navigateur conçue pour les apprenants d'anglais. Elle ajoute des annotations de prononciation IPA (alphabet phonétique international) aux mots anglais des pages web, en prenant en charge les accents américain et britannique, pour faciliter l'apprentissage de la prononciation anglaise.

---

## Fonctionnalités principales

- **Mode IPA page entière** — Ajoutez des annotations IPA à tous les mots anglais de la page en un clic ; les symboles IPA sont codés par couleur (voyelles, consonnes, accents) pour une lecture facile
- **Formes faibles/fortes** — Affiche automatiquement les variantes de prononciation faible et forte des mots fonctionnels courants (ex. « the », « to », « can »), pour maîtriser l’enchaînement naturel
- **Accents américain et britannique** — Basculez entre l’IPA américain (en-US) et britannique (en-GB)
- **Synthèse vocale** — Cliquez sur le bouton haut-parleur pour entendre la prononciation correspondant à l’accent choisi
- **Lecture de sélection avec effet karaoké** — Sélectionnez du texte anglais : une barre compacte apparaît avec des boutons parler et traduire ; la lecture met en surbrillance chaque mot en temps réel (effet karaoké) synchronisé avec l’audio
- **Traduction de la sélection** — Sélectionnez n’importe quel texte, cliquez sur traduire dans la barre pour une traduction instantanée via Bing ou Google Translate, affichée dans une bulle intégrée
- **Infobulles au survol** — Passez la souris sur les mots annotés pour voir l’IPA avec symboles colorés et boutons de prononciation
- **Désambiguïsation des homographes** — Identifie automatiquement les mots à plusieurs prononciations (ex. « read », « live ») et choisit la bonne selon le contexte
- **Raccourcis clavier** — Accès rapide aux fonctions principales via des raccourcis personnalisables
- **Interface multilingue** — Prend en charge 38 langues d’interface

---

## Comment utiliser

### Étape 1 : Installer l’extension

Installez **IPA Reader** depuis le [Chrome Web Store](https://chromewebstore.google.com/), ou chargez-la localement en mode développeur.

### Étape 2 : Ouvrir une page web

Visitez une page web contenant du contenu en anglais.

### Étape 3 : Activer l’IPA

Cliquez sur l’icône de l’extension dans la barre d’outils. Activez « Activer IPA », puis « IPA page entière » pour annoter tous les mots de la page. Vous pouvez aussi utiliser le bouton flottant en bas à droite.

### Étape 4 : Consulter l’IPA

Passez la souris sur les mots pour afficher les infobulles IPA avec symboles colorés. Cliquez sur l’icône haut-parleur pour entendre la prononciation. Pour les mots à formes faibles/fortes, l’infobulle affiche les deux variantes.

### Étape 5 : Lire et traduire le texte sélectionné

Sélectionnez du texte anglais avec la souris. Une barre compacte apparaît près de la sélection avec deux boutons :

- **🔊 Parler** — Lit le texte sélectionné à voix haute avec surbrillance mot par mot façon karaoké
- **🌐 Traduire** — Affiche une bulle de traduction intégrée sous la barre

Vous pouvez aussi faire un clic droit et choisir « IPA Reader > Lire la sélection » ou « IPA Reader > Traduire la sélection ».

> **Conseil :** Cliquez sur l’icône de l’extension dans la barre d’outils pour ouvrir le panneau des paramètres et régler le type d’accent, la vitesse de lecture, le moteur de traduction, etc.

---

## Mode IPA page entière

Lorsque le mode IPA page entière est activé, chaque mot anglais de la page reçoit une annotation IPA au-dessus du texte en ruby. Les symboles IPA sont codés par couleur :

- **Voyelles** — surlignées en bleu
- **Consonnes** — affichées en gris
- **Accents** (ˈ ˌ) — surlignés en rouge
- **Signes de longueur** (ː) — surlignés en violet

L’extension ajuste automatiquement la hauteur de ligne pour éviter les chevauchements et adapte la taille de la police IPA à la longueur du mot.

---

## Formes faibles/fortes

De nombreux mots fonctionnels courants ont deux prononciations :

- **Forme faible** — la prononciation réduite dans l’enchaînement naturel (ex. « the » → /ðə/)
- **Forme forte** — la prononciation pleine pour l’emphase ou à l’isolement (ex. « the » → /ðiː/)

Lorsque « Afficher les formes faibles/fortes » est activé, le survol de ces mots affiche les deux variantes dans l’infobulle, libellées « WEAK » et « STRONG », pour comprendre l’évolution de la prononciation dans la parole naturelle.

Les mots couverts incluent : articles (the, a, an), prépositions (to, for, of, from, at, as, than), conjonctions (and, or, but), pronoms (you, your, her, him, his, them, us, our, there), auxiliaires (am, is, are, was, were, been, can, could, would, should, must, shall, will, do, does, have, has, had), et plus encore.

---

## Lecture de sélection et karaoké

La lecture de sélection permet de sélectionner du texte anglais et de le faire lire en un clic — idéal pour la prononciation des phrases et la pratique de la lecture.

**Méthode 1 : Barre de sélection**  
Sélectionnez du texte anglais avec la souris. Une barre compacte apparaît près de la sélection avec les boutons 🔊 parler et 🌐 traduire. Cliquez sur parler pour lire. Pendant la lecture, chaque mot est surligné en temps réel (effet karaoké).

**Méthode 2 : Menu contextuel**  
Après avoir sélectionné du texte anglais, clic droit et choisissez « IPA Reader > Lire la sélection ».

**Méthode 3 : Raccourci clavier**  
Sélectionnez le texte et appuyez sur `Alt+Shift+S` (Mac : `Ctrl+Shift+S`) pour lire.

> **Conseil :** La surbrillance karaoké fonctionne au mieux si le navigateur prend en charge les événements de limites de mots TTS. Sinon, l’extension utilise un repli temporel pour une surbrillance fluide.

---

## Traduction

Sélectionnez n’importe quel texte sur la page et utilisez la traduction pour obtenir des résultats instantanés.

**Méthode 1 : Barre de sélection**  
Sélectionnez le texte, puis cliquez sur le bouton 🌐 traduire dans la barre. Une bulle de traduction s’affiche en dessous avec le résultat et un bouton copier.

**Méthode 2 : Menu contextuel**  
Sélectionnez le texte, clic droit et choisissez « IPA Reader > Traduire la sélection ».

**Méthode 3 : Raccourci clavier**  
Sélectionnez le texte et appuyez sur `Alt+Shift+T` (Mac : `Ctrl+Shift+T`) pour traduire.

**Moteurs de traduction :**

- **Bing Translate** (par défaut) — fourni par Microsoft Translator
- **Google Translate** — fourni par Google

Vous pouvez changer le moteur et la langue cible dans les paramètres de l’extension. La langue cible est détectée automatiquement à partir de la langue du navigateur.

> **Conseil :** Cliquez en dehors de la barre ou de la bulle pour les fermer.

---

## Raccourcis clavier

| Raccourci | Raccourci Mac | Action |
|-----------|---------------|--------|
| `Alt+Shift+I` | `Ctrl+Shift+I` | Activer / désactiver les annotations IPA |
| `Alt+Shift+S` | `Ctrl+Shift+S` | Lire le texte sélectionné |
| `Alt+Shift+T` | `Ctrl+Shift+T` | Traduire le texte sélectionné |

> **Conseil :** Vous pouvez personnaliser ces raccourcis dans Chrome à l’adresse `chrome://extensions/shortcuts`.

---

## Guide des paramètres

| Paramètre | Description |
|-----------|-------------|
| **Activer IPA** | Interrupteur principal pour activer ou désactiver les annotations IPA |
| **IPA page entière** | Si activé, affiche l’IPA coloré pour tous les mots anglais au-dessus du texte |
| **Style IPA** | Choisir entre anglais américain et britannique pour l’IPA et la prononciation |
| **Infobulles au survol** | Afficher l’infobulle IPA avec bouton de prononciation au survol |
| **Formes faibles/fortes** | Afficher les variantes faible et forte pour les mots fonctionnels courants |
| **Vitesse lecture phrases** | Ajuster la vitesse de lecture des phrases (la lecture des mots isolés n’est pas affectée) |
| **Moteur de traduction** | Choisir entre Bing Translate et Google Translate |
| **Langue cible** | Définir la langue cible de la traduction (détection automatique à partir de la langue du navigateur) |

---

## FAQ

**Q : Pourquoi cela ne fonctionne-t-il pas sur certaines pages ?**  
R : Pour des raisons de sécurité, les extensions ne peuvent pas s’exécuter sur les pages spéciales comme `chrome://`, les paramètres du navigateur ou le Chrome Web Store.

**Q : Que faire si l’IPA manque pour certains mots ?**  
R : Le dictionnaire IPA couvre les mots anglais courants. Pour les mots absents, l’extension génère un IPA approximatif par lemmatisation et G2P par règles, marqué ≈ ou ~ dans l’infobulle.

**Q : Pas de son avec la synthèse vocale ?**  
R : Vérifiez le volume système et assurez-vous que les packs vocaux anglais sont installés. Le support varie selon les navigateurs et systèmes d’exploitation.

**Q : Le mode page entière affecte-t-il la mise en page ?**  
R : Les annotations IPA nécessitent de l’espace supplémentaire. L’extension ajuste la hauteur des lignes pour limiter l’impact. Si cela gêne encore, désactivez le mode page entière et utilisez les infobulles au survol.

**Q : Que signifient les symboles ~ et ≈ dans les infobulles ?**  
R : ~ indique que l’IPA a été généré par conversion par règles (G2P) plutôt que par le dictionnaire. ≈ indique qu’il a été dérivé d’un mot de base apparenté par lemmatisation. Ils peuvent être moins précis que les entrées du dictionnaire.

**Q : La traduction ne fonctionne pas ?**  
R : La traduction nécessite une connexion Internet. Si Bing Translate échoue, essayez Google Translate dans les paramètres. Certains réseaux peuvent bloquer l’accès aux services de traduction.

---

## Liens utiles

- [Politique de confidentialité](../privacy-policy)
- [Support et commentaires](../support)

---
