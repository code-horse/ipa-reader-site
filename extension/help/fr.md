---
layout: bare
title: Extension IPA Reader - Guide utilisateur
lang: fr
---

# IPA Reader - Guide utilisateur

> Version : v1.4.0

## Introduction

IPA Reader est une extension de navigateur conçue pour les apprenants d’anglais. Elle ajoute des annotations de prononciation IPA (alphabet phonétique international) aux mots anglais des pages web et des PDF, en prenant en charge les accents américain et britannique. Elle inclut également un dictionnaire anglais intégré, la synthèse vocale et la traduction — pour faciliter l’apprentissage de la prononciation anglaise.

---

## Fonctionnalités principales

- **Mode IPA page entière** — Ajoutez des annotations IPA à tous les mots anglais de la page en un clic ; les symboles IPA sont codés par couleur (voyelles, consonnes, accents) pour une lecture facile
- **Dictionnaire au survol** — Passez la souris sur les mots pour voir les définitions en anglais (plus de 82 000 entrées WordNet), l’IPA avec symboles colorés et les boutons de prononciation ; choisissez le mode Dictionnaire, Infobulle ou Désactivé
- **Lecteur PDF** — Lecteur PDF intégré avec IPA, dictionnaire, parole et traduction ; glisser-déposer, ouverture par URL et détection intelligente des PDF avec redirection automatique
- **Formes faibles/fortes** — Affiche automatiquement les variantes de prononciation faible et forte des mots fonctionnels courants (ex. « the », « to », « can »), pour maîtriser l’enchaînement naturel
- **Accents américain et britannique** — Basculez entre l’IPA américain (en-US) et britannique (en-GB)
- **Synthèse vocale** — Cliquez sur le bouton haut-parleur pour entendre la prononciation correspondant à l’accent choisi
- **Lecture de sélection avec effet karaoké** — Sélectionnez du texte anglais : une barre compacte apparaît avec des boutons parler et traduire ; la lecture met en surbrillance chaque mot en temps réel (effet karaoké) synchronisée avec l’audio
- **Traduction de la sélection** — Sélectionnez n’importe quel texte, cliquez sur traduire dans la barre pour une traduction instantanée via Bing ou Google Translate, affichée dans une bulle intégrée
- **Désambiguïsation des homographes** — Identifie automatiquement les mots à plusieurs prononciations (ex. « read », « live ») et choisit la bonne selon le contexte
- **Raccourcis clavier** — Accès rapide aux fonctions principales via des raccourcis personnalisables
- **Interface multilingue** — Prend en charge 41 langues d’interface

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

> **Conseil :** Cliquez sur l’icône de l’extension dans la barre d’outils pour ouvrir le panneau des paramètres et régler le type d’accent, la vitesse de lecture, le mode au survol, le moteur de traduction, etc.

---

## Mode IPA page entière

Lorsque le mode IPA page entière est activé, chaque mot anglais de la page reçoit une annotation IPA au-dessus du texte en ruby. Les symboles IPA sont codés par couleur :

- **Voyelles** — surlignées en bleu
- **Consonnes** — affichées en gris
- **Accents** (ˈ ˌ) — surlignés en rouge
- **Signes de longueur** (ː) — surlignés en violet

L’extension ajuste automatiquement la hauteur de ligne pour éviter les chevauchements et adapte la taille de la police IPA à la longueur du mot.

---

## Dictionnaire au survol

L’extension inclut un dictionnaire anglais intégré basé sur WordNet (plus de 82 000 mots). Vous pouvez choisir parmi plusieurs modes au survol dans les paramètres :

| Mode | Comportement |
|------|--------------|
| **Dictionnaire** | Le survol affiche IPA + définition en anglais + bouton de prononciation |
| **Infobulle** | Le survol affiche IPA + bouton de prononciation (sans définitions) |
| **Désactivé** | Aucun effet au survol |

En mode **Dictionnaire**, l’infobulle affiche :
- Le mot et sa transcription IPA
- Un bouton de prononciation (clic pour écouter)
- Les définitions en anglais issues de WordNet

> **Conseil :** Les données du dictionnaire sont chargées à la demande lorsque le mode Dictionnaire est activé, et déchargées lorsque vous passez à un autre mode pour économiser la mémoire.

---

## Lecteur PDF

IPA Reader inclut un lecteur PDF intégré qui permet de lire des documents PDF avec annotations IPA, dictionnaire, parole et traduction — les mêmes fonctions que sur les pages web, désormais pour les PDF.

### Ouvrir un PDF

**Méthode 1 : depuis la fenêtre contextuelle**  
Cliquez sur l’icône de l’extension, puis sur « Open PDF Reader ». Glissez-déposez un fichier PDF ou cliquez sur « Choose File » pour ouvrir un PDF local. Vous pouvez aussi coller une URL de PDF.

**Méthode 2 : menu contextuel**  
Clic droit sur un lien `.pdf` dans une page web, puis « Open PDF with IPA Reader ».

**Méthode 3 : détection automatique**  
Lorsque « PDF Smart Detection » est activé dans les paramètres, l’extension redirige automatiquement les URL se terminant par `.pdf` vers le lecteur intégré. Si un PDF est détecté mais pas redirigé (ex. visionneuse intégrée de Chrome), des notifications vous invitent à l’ouvrir dans IPA Reader.

### Fonctionnalités du lecteur PDF

- **Annotations IPA** — Toutes les fonctions IPA s’appliquent au texte PDF, y compris le mode page entière et les infobulles au survol
- **Dictionnaire au clic** — Cliquez sur un mot pour voir sa définition (dans le PDF, le clic remplace le survol pour une lecture plus fluide)
- **Barre de sélection** — Sélectionnez du texte pour parler, traduire ou copier
- **Barre latérale** — Plan (table des matières) et miniatures des pages
- **Recherche** — Recherche de texte dans le PDF
- **Thèmes** — Thèmes de lecture Sombre, Clair et Sépia
- **Zoom** — Plusieurs niveaux : Auto, Adapter la page, Largeur de page
- **Raccourcis clavier** — Flèches pour la navigation, +/- pour le zoom, Ctrl/Cmd+F pour la recherche

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

Les deux moteurs prennent en charge **108 langues cibles**.

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
| **Mode au survol** | Comportement au survol : Dictionnaire (IPA + définitions + audio), Infobulle (IPA + audio) ou Désactivé |
| **Formes faibles/fortes** | Afficher les variantes faible et forte pour les mots fonctionnels courants |
| **Vitesse lecture phrases** | Ajuster la vitesse de lecture des phrases (la lecture des mots isolés n’est pas affectée) |
| **Moteur de traduction** | Choisir entre Bing Translate et Google Translate |
| **Langue cible** | Définir la langue cible de la traduction (détection automatique à partir de la langue du navigateur) |
| **PDF Smart Detection** | Si activé, redirige automatiquement les URL PDF vers le lecteur intégré et affiche des notifications lorsque des PDF sont détectés |

---

## FAQ

**Q : Pourquoi cela ne fonctionne-t-il pas sur certaines pages ?**  
R : Pour des raisons de sécurité, les extensions ne peuvent pas s’exécuter sur les pages spéciales comme `chrome://`, les paramètres du navigateur ou le Chrome Web Store.

**Q : Que faire si l’IPA manque pour certains mots ?**  
R : Le dictionnaire IPA couvre plus de 134 000 mots en anglais américain et plus de 67 000 en anglais britannique. Pour les mots absents, l’extension génère un IPA approximatif par lemmatisation et G2P par règles, marqué ≈ ou ~ dans l’infobulle.

**Q : Pas de son avec la synthèse vocale ?**  
R : Vérifiez le volume système et assurez-vous que les packs vocaux anglais sont installés. Le support varie selon les navigateurs et systèmes d’exploitation.

**Q : Le mode page entière affecte-t-il la mise en page ?**  
R : Les annotations IPA nécessitent de l’espace supplémentaire. L’extension ajuste la hauteur des lignes pour limiter l’impact. Si cela gêne encore, désactivez le mode page entière et utilisez les infobulles au survol.

**Q : Que signifient les symboles ~ et ≈ dans les infobulles ?**  
R : ~ indique que l’IPA a été généré par conversion par règles (G2P) plutôt que par le dictionnaire. ≈ indique qu’il a été dérivé d’un mot de base apparenté par lemmatisation. Ils peuvent être moins précis que les entrées du dictionnaire.

**Q : La traduction ne fonctionne pas ?**  
R : La traduction nécessite une connexion Internet. Si Bing Translate échoue, essayez Google Translate dans les paramètres. Certains réseaux peuvent bloquer l’accès aux services de traduction.

**Q : Comment ouvrir un PDF avec IPA Reader ?**  
R : Plusieurs possibilités : cliquez sur « Open PDF Reader » dans la fenêtre de l’extension, clic droit sur un lien PDF puis « Open PDF with IPA Reader », ou activez « PDF Smart Detection » pour rediriger automatiquement les URL PDF vers le lecteur intégré.

**Q : PDF Smart Detection est activé mais certains PDF ne sont pas redirigés ?**  
R : La redirection automatique fonctionne pour les URL se terminant par `.pdf`. Pour les PDF servis sans extension `.pdf` ou ouverts dans la visionneuse intégrée de Chrome, une notification et un badge vous invitent à ouvrir le fichier dans IPA Reader.

**Q : Puis-je utiliser le dictionnaire hors ligne ?**  
R : Oui. Le dictionnaire WordNet (plus de 82 000 mots) est entièrement inclus dans l’extension. Toutes les recherches sont effectuées localement, sans connexion réseau.

---

## Liens utiles

- [Politique de confidentialité](../privacy-policy)
- [Support et commentaires](../support)

---
