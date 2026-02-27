# AUDI⊙LAB PR⊙ — Professional Mastering Suite

> 🎛️ Un moteur de mastering audio professionnel 100% dans le navigateur, propulsé par la Web Audio API.

![Version](https://img.shields.io/badge/version-3.2.0-orange)
![License](https://img.shields.io/badge/license-MIT-green)
![Status](https://img.shields.io/badge/status-production-brightgreen)
![Web Audio](https://img.shields.io/badge/Web_Audio_API-supported-blue)

---

## 🚀 Demo en ligne

👉 **[Ouvrir Audio Lab Pro](https://MOD-PROD.github.io/audio-lab-pro)**

---

## ✨ Fonctionnalités

### 🎚️ Modules de traitement
| Module | Description |
|--------|-------------|
| **Tonality** | EQ 3 bandes (Lowshelf, Peaking, Highshelf) avec contrôle de la fréquence et du Q |
| **Warmth** | Saturation harmonique analogique (algorithme tanh) |
| **Compressor** | Compresseur dynamique avec threshold et ratio réglables |
| **Limiter** | Limiteur brickwall (ratio 20:1) anti-écrêtage |
| **Mid/Side** | Contrôle de la largeur stéréo par matrice Mid/Side |
| **Reverb** | Réverbération convolutive avec decay réglable |
| **Master Gain** | Volume de sortie final calibré en dBFS |

### 📊 Analyse en temps réel
- **FFT Spectrum** — Visualisation spectrale temps réel
- **Vector Scope** — Contrôle de la corrélation stéréo
- **Peak & RMS** — Mètres de niveau en dB
- **Gain Reduction** — Affichage de la compression appliquée
- **Momentary LUFS** — Mesure de loudness (standard streaming)

### 🎧 Transport
- Lecture / Pause / Stop
- Barre de progression avec seek interactif
- Mode **A/B** (Dry vs Wet) pour comparaison instantanée

### 💾 Export
- Export **WAV 16-bit PCM** avec toute la chaîne de traitement
- Rendu offline via `OfflineAudioContext`

---

## 🛠️ Technologies

- **Web Audio API** — Traitement audio natif dans le navigateur
- **Canvas 2D** — Visualisations FFT et Vector Scope
- **OfflineAudioContext** — Export WAV haute qualité
- **Tailwind CSS** — Interface responsive
- **JetBrains Mono** — Typographie monospace

---

## 📦 Installation

Aucune dépendance, aucun build requis. Clonez et ouvrez directement :

```bash
git clone https://github.com/MOD-PROD/audio-lab-pro.git
cd audio-lab-pro
open index.html
```

Ou déployez via **GitHub Pages** pour un accès en ligne immédiat.

---

## 🎯 Utilisation

1. **Chargez** un fichier audio (MP3, WAV, FLAC, OGG…)
2. **Ajustez** les paramètres de chaque module
3. **Prévisualisez** en temps réel avec les analyseurs
4. **Comparez** l'original avec le mode A/B
5. **Exportez** le résultat en WAV

### 📡 Cibles LUFS recommandées
| Plateforme | Cible |
|------------|-------|
| Spotify | -14 LUFS |
| Apple Music | -16 LUFS |
| YouTube | -14 LUFS |
| CD / Master | -9 LUFS |

---

## 📁 Structure du projet

```
audio-lab-pro/
├── index.html      # Application complète (single file)
└── README.md       # Documentation
```

---

## 📄 Licence

MIT © 2026 — Libre d'utilisation, modification et distribution.

---

<p align="center">
  Made with 🎛️ and Web Audio API
</p>
