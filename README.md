# SpeedReader Pro ⚡

**Powered by Aura OS, backed by Paper X.**

[![Aura OS: Paper X](https://img.shields.io/badge/Aura%20OS-Paper%20X-indigo.svg)](https://zenodo.org/records/22177051)
[![Zenodo DOI](https://img.shields.io/badge/DOI-10.5281%2Fzenodo.22177051-blue.svg)](https://zenodo.org/records/22177051)
[![GitHub Repository](https://img.shields.io/badge/GitHub-SpeedReaderPro-slate.svg?logo=github)](https://github.com/dallascourchene-commits/SpeedReaderPro)
[![Live Demo](https://img.shields.io/badge/Live%20Demo-GitHub%20Pages-2ea44f.svg)](https://dallascourchene-commits.github.io/SpeedReaderPro/)
[![License: MIT](https://img.shields.io/badge/License-MIT-emerald.svg)](LICENSE)
[![Offline Capable](https://img.shields.io/badge/Offline-100%25%20Client--Side-teal.svg)](#privacy--offline-first)
[![Speed](https://img.shields.io/badge/WPM-Up%20to%202%2C000-violet.svg)](#high-velocity-engine)

**SpeedReader Pro** is a zero-latency, high-velocity RSVP (Rapid Serial Visual Presentation) reading engine published as **SpeedReader Pro of AuraOS**. Engineered for peak visual comprehension, it combines **flush-left optical anchoring**, **uppercase Bionic typography**, and **discrete zero-bounce container stabilization** to allow distraction-free reading speeds up to **2,000 words per minute (WPM)**.

**Live Web App:** [Launch SpeedReader Pro](https://dallascourchene-commits.github.io/SpeedReaderPro/) — use it instantly in your browser, no install required.  
Official Repository: [https://github.com/dallascourchene-commits/SpeedReaderPro](https://github.com/dallascourchene-commits/SpeedReaderPro)  
Archival Record & Paper X: [https://zenodo.org/records/22177051](https://zenodo.org/records/22177051)

---

## 📖 Table of Contents

- [Overview](#overview)
- [Key Features](#key-features)
- [The Cognitive Science](#the-cognitive-science)
  - [1. Flush-Left Optical Guide vs. Center Alignment](#1-flush-left-optical-guide-vs-center-alignment)
  - [2. Uppercase Bionic Anchoring](#2-uppercase-bionic-anchoring)
  - [3. Discrete Snap-Down Sizing (Zero-Bounce)](#3-discrete-snap-down-sizing-zero-bounce)
  - [4. Cognitive Punctuation Weighting](#4-cognitive-punctuation-weighting)
- [Controls & Gestures](#controls--gestures)
  - [Mouse & Touch Gestures](#mouse--touch-gestures)
  - [Keyboard Shortcuts](#keyboard-shortcuts)
- [Supported Formats](#supported-formats)
- [Getting Started](#getting-started)
- [Privacy & Offline Architecture](#privacy--offline-architecture)
- [Citation & Archival (Paper X)](#citation--archival-paper-x)
- [About Aura OS](#about-aura-os)
- [License](#license)

---

## Overview

Traditional reading requires the human visual cortex and eye muscles to perform rapid, continuous physical jumps (saccades) along lines of text, consuming energy, causing eye strain, and introducing cognitive latency. SpeedReader Pro isolates and presents words sequentially at a strictly stationary boundary, utilizing capitalization-based fixation anchors so your visual cortex instantly parses the root morpheme before completing the remainder of the word.

Everything executes 100% locally in your browser—completely offline with zero servers, telemetry, or external API dependencies.

---

## Getting Started

Because SpeedReader Pro is built as a single, self-contained file, setup takes seconds:

### Try It Live (AUTO RECOMMENDED)

**[Launch SpeedReader Pro on GitHub Pages](https://dallascourchene-commits.github.io/SpeedReaderPro/)** — no download or installation required.

---

## Key Features

- **🚀 Ultra-High Velocity:** Adjustable speed scaling in real time from **100 WPM** to **2,000 WPM**.
- **🎯 Flush-Left RSVP Fixation:** An illuminated left vertical guide line keeps eye fixation locked at the left boundary, eliminating saccadic eye drift.
- **🔤 Uppercase Bionic Anchoring:** Capitalizes leading letters of each word to highlight the word root (`REAd`, `TECHnology`).
- **🎛️ Dynamic or Fixed Anchor Lengths:** Switch instantly between an intelligent cognitive curve (`Auto`) or fixed `1`, `2`, `3`, or `4` capitalized anchor letters.
- **📐 Discrete Snap-Down Font Sizing:** Choose any baseline uniform font size (32px to 72px). Long words automatically snap down to pre-calibrated boundary tiers to ensure zero container bouncing, frame jitter, or layout reflows.
- **🎨 Independent Color Customization:** Live palette controls for anchor capitals (White, Yellow, Indigo, Emerald) and trailing letters (White, Slate, Soft Yellow).
- **📂 Universal Client-Side Document Importer:** Read `.pdf` (via bundled PDF.js worker), `.txt`, `.md`, and raw document text completely offline.
- **👆 Rapid Multi-Tap Rewind Gestures:** Tap the stage twice to rewind 5 words (`-5`); tap three times to jump back 15 words (`-15`).
- **💻 Minimalist Single-File Architecture:** Fully portable standalone application running in any standard web browser.

---

## The Cognitive Science

### 1. Flush-Left Optical Guide vs. Center Alignment
Most standard RSVP readers center words horizontally. While visually symmetrical, center-aligned RSVP forces the eyes to continuously micro-adjust left or right because words have varying character lengths. SpeedReader Pro anchors the first character directly flush against an illuminated vertical guide on the left margin, keeping eye muscles 100% stationary.

### 2. Uppercase Bionic Anchoring
SpeedReader Pro converts anchor fragments to **uppercase** and pairs them with high-contrast color weighting. When configured to `Auto`, it dynamically adjusts based on morpheme length:
- **1–2 letters** (*to, in*): **1** letter capitalized (`To`, `In`) to prevent full-word capitalization.
- **3–5 letters** (*the, what*): **2** letters capitalized (`THe`, `WHat`).
- **6–8 letters** (*reader, stream*): **3** letters capitalized (`REAders`, `STRream`).
- **9+ letters** (*presentation*): **4** letters capitalized (`PRESentation`).

### 3. Discrete Snap-Down Sizing (Zero-Bounce)
Dynamically calculating text bounds per word causes frame jitter and micro-delays that disorient readers at speeds above 600 WPM. SpeedReader Pro resolves this with **discrete snap-down containment**:
- Standard words maintain your selected uniform font size.
- Words exceeding threshold lengths instantaneously snap to a scaled sub-tier to fit within the box boundaries.
- The next word snaps right back to your baseline size, with zero layout shift or container bouncing.

### 4. Cognitive Punctuation Weighting
At high speeds, natural comprehension breaks are essential. SpeedReader Pro automatically applies a **1.3× cognitive weighting delay** for terminal punctuation (`.`, `,`, `;`, `:`, `!`, `?`) and a **1.1× delay** for words longer than 8 characters, ensuring natural cadence.

---

## Controls & Gestures

### Mouse & Touch Gestures

| Action | Result |
| :--- | :--- |
| **Single Tap / Click** | Toggle Play / Pause |
| **Double Tap (within 350ms)** | Instant Rewind **5 words** (`-5`) |
| **Triple Tap (within 350ms)** | Instant Rewind **15 words** (`-15`) |
| **Timeline Slider** | Scrub across any point in the text |

### Keyboard Shortcuts

| Key | Result |
| :--- | :--- |
| `Space` | Play / Pause |
| `Arrow Left (←)` | Jump backward 5 words |
| `Arrow Right (→)` | Skip forward 5 words |

---

## Supported Formats

SpeedReader Pro processes all documents client-side:
- **PDF Documents** (`.pdf`) — Automated text stream extraction via PDF.js worker.
- **Markdown** (`.md`)
- **Plain Text** (`.txt`)
- **Rich/Word Documents** (`.doc`, `.docx` plain-text buffers)

---

### Quick Run
1. Download or clone this repository:
   ```bash
   git clone https://github.com/dallascourchene-commits/SpeedReaderPro.git
   cd SpeedReaderPro
   ```
2. Open `speed_reader_app.html` directly in any modern desktop or mobile browser (Chrome, Firefox, Safari, Edge, Brave).
3. Click **Load Sample** or upload any document file, adjust your desired WPM, and press **Spacebar** or click **Play**.

---

## Privacy & Offline Architecture

- **Zero Server Uploads:** Your documents never leave your browser memory.
- **Air-Gapped Operation:** All dependencies (including rendering loops and PDF parsing workers) execute locally in your client environment.
- **No Telemetry / No Tracking:** Zero analytics scripts, tracking pixels, or data collection.

---

## Citation & Archival (Paper X)

SpeedReader Pro is indexed and permanently archived as **Paper X of Aura OS** on Zenodo. If you use or reference SpeedReader Pro in your cognitive science research, reading efficiency benchmarks, or digital interface studies, please cite this work:

```bibtex
@software{speedreader_pro_paper_x_auraos,
  author       = {{AuraOS} and Courchene, Dallas},
  title        = {SpeedReader Pro: High-Velocity RSVP Reader with Uppercase Bionic Anchors and Flush-Left Fixation (Paper X of Aura OS)},
  year         = {2026},
  publisher    = {Zenodo},
  version      = {v1.0.0},
  doi          = {10.5281/zenodo.22177051},
  url          = {https://zenodo.org/records/22177051}
}
```

- **Zenodo Record:** [https://zenodo.org/records/22177051](https://zenodo.org/records/22177051)
- **DOI:** `10.5281/zenodo.22177051`

---

## About Aura OS

SpeedReader Pro was developed under the **AuraOS** initiative—an exploratory human-machine interface framework focusing on high-bandwidth information absorption, recursive cognitive frameworks, and zero-latency human-AI workflows.

---

## License

This project is licensed under the [MIT License](LICENSE) — free to use, modify, and distribute for personal, academic, and commercial applications.
