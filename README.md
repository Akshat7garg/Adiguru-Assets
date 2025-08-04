# 🕉️ Adiguru Assets

**Adiguru Assets** is a static content repository for the [Adiguru](https://your-adiguru-site-link.com) platform. It includes high-quality devotional audio files, JSON scriptures, and images for seamless integration with web and mobile applications.

---

## 📦 Contents

| Category         | Folder              | Description |
|------------------|---------------------|-------------|
| 🪔 Aarti          | `aarti/`            | Short devotional songs sung during worship to offer light and reverence to the deity. |
| 📜 Chalisa        | `chalisa/`          | Forty-verse hymns that praise and seek blessings from various deities. |
| 🕉️ Stotra         | `stotra/`           | Sanskrit verses and prayers that glorify divine forms and guide inner reflection. |
| 📖 Gita           | `scriptures/gita/`  | The ultimate guidance from Lord Krishna to every human being on how to live, act, and attain liberation. |
| 🧭 Prashnavali    | `scriptures/prashnavali/` | A divine medium to ask GOD whether your action or decision is right or not. |
| 🖼️ Images         | `images/`           | Web-optimized images used across the Adiguru platform. |
| 📁 Metadata       | `metadata/`         | JSON files that describe and organize the content by category, enabling dynamic rendering in the app. |

---

## 📁 Folder Structure

```text
adiguru-audible/
├── aarti/             # All Aarti audio files (.mp3)
├── chalisa/           # All Chalisa audio files (.mp3)
├── stotra/            # All Stotra audio files (.mp3)
├── scriptures/            
    ├── aarti/                # Aarti text data (JSON)
    ├── chalisa/              # Chalisa text data (JSON)
    ├── gita/                 # Gita chapters and verses (JSON)
    ├── prashnavali/          # Prashnavali responses (JSON)
├── metadata/          # Master data to organize and render content
    ├── gita/                  # Metadata for each adhyay Bhagavad Gita
    ├── aarti.json
    ├── chalisa.json
    ├── prashnavali.json
    └── stotra.json
└── index.json         # Master index for all content categories
```

---

## 🧠 Usage

- Audio, text, and images are consumed by the Adiguru frontend using jsDelivr CDN.
- Content is modular and dynamically rendered using metadata JSON files.
- Scripture data can be parsed for display, audio syncing, and spiritual guidance.

---

## 🔖 License

[![License: CC BY-NC 4.0](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg)](http://creativecommons.org/licenses/by-nc/4.0/)

This repository contains devotional content for educational and spiritual purposes only. Use with respect and non-commercial intent.

---

> **OM NAMAH SHIVAY 🙏**  
> “Let your ears be filled with the sound of devotion.”
