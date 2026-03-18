# Upload Labs — Wiki & Tutoriel FR

Interface web interactive regroupant un **wiki de référence** et un **tutoriel complet** pour le jeu [Upload Labs v2.1](https://uploadlabs.enigmastudio.dev/), du premier nœud jusqu'à l'end game.

> **Source originale :** Guide écrit par *Andy* — [Upload Labs Guide v2.1 (Google Docs)](https://docs.google.com/document/d/1QpDOViW4pWlKfUC7cq7cNJpWqYV1GIHdp6NaYIvNb18/edit?tab=t.0#heading=h.mg8fyx24f06a)  
> Ce projet est une réinterprétation en français sous forme d'interface web, non une traduction directe.

## 🌐 Accès en ligne

**[▶ Ouvrir le guide](https://kypsoza.github.io/rules_French/upload_labs_v3.html)**

> Hébergé via GitHub Pages. Aucune installation requise — fonctionne directement dans le navigateur.  

---

## ✨ Fonctionnalités

- **Deux onglets** — Wiki (mécaniques & référence) et Tutoriel (progression pas à pas)
- **Wiki** organisé par mécanique : ressources, ratios, hacking, codage, server, AGI Core, index des nœuds
- **Tutoriel détaillé** — Portal Run #0 → #1 → End Game, chaque nœud expliqué avec son *pourquoi*
- **Diagrammes SVG** — câblage orthogonal, couleurs sémantiques par type de signal
- **Responsive mobile** — sidebar burger, overlay, layout adaptatif
- **Progressive Web App (PWA)** — installable depuis Chrome, mode hors-ligne via Service Worker
- **Recherche en temps réel** dans la sidebar
- **Navigation Précédent / Suivant** entre les sections
- **Barre de progression** en haut de page
- **100% autonome** — un seul fichier `.html`, aucune dépendance serveur

---

## 🎨 Code couleur des diagrammes

| Couleur | Signal |
|--------|--------|
| 🔵 `#38bdf8` Bleu ciel | Réseau (Download / Upload) |
| 🟣 `#c084fc` Violet | Clock Speed CPU |
| 🟠 `#fb923c` Orange | GPU Speed |
| 🟢 `#4ade80` Vert | Flux de fichiers |
| 🟡 `#facc15` Jaune | Argent / Revenus |
| 🔴 `#f87171` Rouge | Hacking / Infecté |
| 💜 `#a78bfa` Lilas | IA / Neurones |
| 🌿 `#34d399` Menthe | Recherche |

---

## 📖 Contenu du Wiki

- Qu'est-ce qu'Upload Labs ? (ressources fondamentales)
- Lire les indicateurs d'un nœud (anatomie SVG annotée)
- Types de fichiers & modificateurs
- Système de Recherche (formule + stratégie)
- Guide des Ratios (CPU, réseau, torrents, codage)
- Système de Hacking (builds, hack points)
- Système de Codage (ratios IDE/IF complets)
- Server & AGI Core (formules, diagrammes)
- Index des Nœuds (hardware, distribution, processors, apps de décomposition)
- Tokens & Succès (ordre d'achat + liste complète)

## 🎮 Contenu du Tutoriel

### Portal Run #0 (débutant absolu)
1. Tutoriel & Premiers Tokens
2. Processor & Clock Speed
3. Virus Scanner & Quarantine
4. Checksum Verifier & Reconstructor
5. Images, GPU & Crypto Mining
6. Data Lab & Section Recherche
7. Hacking — Mise en Place
8. Premier Codage & Enhancer/Compressor
9. Advanced Research & Premier Portail

### Portal Run #1
1. Démarrage ×4
2. Trojans & Component Boost
3. Fichiers IA — Neurones & Générateurs
4. Server & AGI Core
5. Portail (112 PA)

### End Game
- Runs #2+ — Architecture optimale
- Succès "Développeur Back-end / Front-end"
- No-CPU Strategy & Rewind
- Scaling infini

---

## 🚀 Utilisation

### Depuis un navigateur

Téléchargez `upload_labs_v3.html` et ouvrez-le dans n'importe quel navigateur moderne. Aucune installation requise.

```bash
# Ou depuis la ligne de commande
open upload_labs_v3.html        # macOS
xdg-open upload_labs_v3.html   # Linux
start upload_labs_v3.html       # Windows
```

### Installer comme application (PWA)

1. Ouvrez le fichier dans **Chrome** (desktop ou Android)
2. Une bannière "Installer" apparaît après quelques secondes
3. Ou via le menu ⋮ → **"Ajouter à l'écran d'accueil"** / **"Installer l'application"**
4. L'application fonctionne ensuite **hors-ligne**

### Sur iPhone / Safari

Ouvrir dans Safari → bouton Partager → **"Sur l'écran d'accueil"**

---

## 📱 Compatibilité

| Plateforme | Support |
|-----------|---------|
| Chrome Desktop | ✅ Complet + PWA installable |
| Chrome Android | ✅ Complet + PWA installable |
| Firefox | ✅ Complet |
| Safari iOS | ✅ Complet + ajout écran d'accueil |
| Edge | ✅ Complet + PWA installable |

---

## 🛠️ Stack technique

- **HTML5 / CSS3 / JavaScript vanilla** — zéro framework, zéro dépendance npm
- **Polices** : [Syne](https://fonts.google.com/specimen/Syne) (titres) + [DM Sans](https://fonts.google.com/specimen/DM+Sans) (texte) + [Space Mono](https://fonts.google.com/specimen/Space+Mono) (code/ratios) via Google Fonts
- **SVG** générés programmatiquement (Python) avec moteur de câblage orthogonal maison
- **PWA** : Web App Manifest + Service Worker inline (Blob URL), aucun fichier séparé requis
- **Event delegation** pour toute la navigation — aucun `onclick` inline

---

## 📄 Licence & Crédits

- **Guide original** : [Andy](https://docs.google.com/document/d/1QpDOViW4pWlKfUC7cq7cNJpWqYV1GIHdp6NaYIvNb18/edit?tab=t.0#heading=h.mg8fyx24f06a) — tous droits réservés sur le contenu original
- **Interface web** : réinterprétation libre en français, diagrammes et explications pédagogiques originaux
- **Jeu** : Upload Labs par [Enigma Studio](https://uploadlabs.enigmastudio.dev/)

---

*Upload Labs Guide FR — Interface web non-officielle*
