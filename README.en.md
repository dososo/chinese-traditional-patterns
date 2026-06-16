<div align="center">

# Chinese Traditional Patterns · Wényàng

**An open-source catalogue of traditional Chinese patterns — browse, search, save and use them, with museum-catalogue aesthetics.**

[简体中文](README.md) · [English](README.en.md) · [日本語](README.ja.md) · [한국어](README.ko.md)

[![Website](https://img.shields.io/badge/Browse-wenyang.net-1C7C54)](https://wenyang.net)
[![Patterns](https://img.shields.io/badge/patterns-100%20live%20/%20800%20planned-C9A85C)](#-roadmap)
[![Code License](https://img.shields.io/badge/code-MIT-blue)](LICENSE)
[![Content License](https://img.shields.io/badge/content-CC%20BY--NC%204.0-lightgrey)](LICENSE-CONTENT.md)

<img src="docs/screenshots/hero.jpeg" width="760" alt="Chinese Traditional Patterns · Wényàng">

</div>

---

## 📖 Table of Contents

- [What is this](#-what-is-this)
- [Why this exists](#-why-this-exists)
- [Live website](#-live-website)
- [Featured preview](#-featured-preview)
- [Repository structure](#-repository-structure)
- [Categories](#-categories)
- [Data format](#-data-format)
- [How to use](#-how-to-use)
- [Roadmap](#-roadmap)
- [Contributing](#-contributing)
- [FAQ](#-faq)
- [License](#-license)
- [About the author](#-about-the-author)
- [Star History](#-star-history)
- [Acknowledgements](#-acknowledgements)

---

## ✨ What is this

**Chinese Traditional Patterns (Wényàng)** is an open, free catalogue of traditional Chinese patterns for designers and culture lovers.

Traditional motifs scattered across porcelain, brocade, architecture and lacquerware are re-organised here into a **structured, searchable** open resource:

- 🖼 **100 high-resolution pattern cards** (1086×1448 PNG), organised into 6 categories;
- 📝 **A data sheet for every card**: Chinese + English name, one-line summary, cultural symbolism, visual keywords, plus a Chinese detail page (composition / visual notes / common carriers / colour suggestions / modern uses / related patterns / tags);
- 📦 **Machine-readable dataset**: `data/patterns.json` and `data/patterns.csv`, aggregating all 100 records, ready to use;
- 🌐 A companion catalogue site, **[wenyang.net](https://wenyang.net)**, to browse, search, favorite, copy palettes and download originals.

> Every card is an **original AI-assisted re-design** — not a direct copy of any specific artifact — and is free to use for non-commercial learning, research and creative work.

---

## 🎯 Why this exists

Looking for traditional patterns usually means compromising — between the plasticky feel of "generic AI aesthetics", low-res stolen images, and layers of paywalls.

**We wanted to do it differently**: to organise, re-design and explain Chinese traditional patterns with **museum-catalogue aesthetics** — so designers and culture lovers can freely **browse, search, save, copy palettes and download** these original re-designs.

- 🎨 **Aesthetics first** — catalogue-grade layout and colour, no plasticky "generic AI" look;
- 🔓 **No paywall** — open and free for non-commercial use;
- 📚 **Well-grounded** — not just images, but symbolism, composition, carriers and palettes;
- ♾ **Maintained long-term** — 100 live, 800 planned, 700 to come, always growing.

---

## 🌐 Live website

For the full browse / search / favorite / copy-palette / download-original experience, visit 👉 **[wenyang.net](https://wenyang.net)**

<img src="docs/screenshots/home.jpeg" width="820" alt="Wényàng homepage">

| Gallery | Pattern detail |
|---|---|
| <img src="docs/screenshots/gallery.jpeg" alt="Gallery"> | <img src="docs/screenshots/detail.jpeg" alt="Detail page"> |

- Museum-catalogue aesthetics, three themes (Su / Xuan paper / Ink night);
- Responsive on desktop and mobile; fully static, zero tracking (anonymous visit counts only).

> Note: the website also offers bilingual text, period / region research and copyable hex palettes. This repository provides the **original source material** of the library.

---

## 🖼 Featured preview

<div align="center">

| <img src="docs/preview/001.jpg" width="180"><br>Interlocking Lotus | <img src="docs/preview/003.jpg" width="180"><br>Peony | <img src="docs/preview/021.jpg" width="180"><br>Dragon | <img src="docs/preview/028.jpg" width="180"><br>Taotie |
|:--:|:--:|:--:|:--:|
| <img src="docs/preview/041.jpg" width="180"><br>Key-fret (Huiwen) | <img src="docs/preview/061.jpg" width="180"><br>Auspicious Clouds | <img src="docs/preview/076.jpg" width="180"><br>Ruyi | <img src="docs/preview/091.jpg" width="180"><br>Longevity (Shou) |

<sub>8 of the 100 cards · see the full library at <a href="https://wenyang.net">wenyang.net</a></sub>

</div>

---

## 📁 Repository structure

```
chinese-traditional-patterns/
├── data/
│   ├── patterns.json        # all 100 records (english keys; recommended for code)
│   └── patterns.csv         # same data, spreadsheet form
├── patterns/                # patterns by category (original package files)
│   ├── 001-020_植物花卉纹/
│   │   └── 001_缠枝莲纹/
│   │       ├── 001_缠枝莲纹_卡片图.png    # high-res card 1086×1448
│   │       ├── 001_缠枝莲纹_详情页.md     # detail page (Chinese)
│   │       └── 001_缠枝莲纹_meta.json     # single-record metadata
│   ├── 021-040_动物瑞兽纹/
│   ├── 041-060_几何锦纹/
│   ├── 061-075_云水山石纹/
│   ├── 076-090_吉祥器物纹/
│   └── 091-100_文字福寿与组合纹/
└── docs/                    # website screenshots & preview thumbnails
```

> File names are kept in Chinese (`_卡片图` = card image, `_详情页` = detail page, `_meta` = metadata) to stay faithful to the original package.

---

## 🗂 Categories

| Folder | 分类 | Category | Count |
|--------|------|----------|:---:|
| `001-020_植物花卉纹` | 植物花卉纹 | Flora | 20 |
| `021-040_动物瑞兽纹` | 动物瑞兽纹 | Fauna & Beasts | 20 |
| `041-060_几何锦纹` | 几何锦纹 | Geometric | 20 |
| `061-075_云水山石纹` | 云水山石纹 | Cloud · Water · Stone | 15 |
| `076-090_吉祥器物纹` | 吉祥器物纹 | Auspicious Objects | 15 |
| `091-100_文字福寿与组合纹` | 文字福寿与组合纹 | Characters & Composite | 10 |
| | **Total** | | **100** |

---

## 🔢 Data format

Each pattern folder holds three files: the high-res card `*_卡片图.png`, a Chinese detail page `*_详情页.md`, and metadata `*_meta.json`.
`data/patterns.json` aggregates all 100 `meta` records:

| Field | Description | Example |
|-------|-------------|---------|
| `id` | three-digit id | `"001"` |
| `name_cn` / `name_en` | Chinese / English name | `"缠枝莲纹"` / `"Interlocking Lotus Scroll Pattern"` |
| `category` | category (one of six) | `"植物花卉纹"` |
| `summary` | one-line summary (Chinese) | `"以莲花与卷曲藤蔓连续展开……"` |
| `meaning` | cultural symbolism (Chinese) | `"清雅、连绵、生生不息"` |
| `visual_keywords` | visual keywords (array) | `["莲花","卷草","连续藤蔓","青绿白描"]` |
| `image_size` | image size | `"1086x1448"` |
| `card_image` / `detail_page` / `meta_json` | relative paths to the three files | `"patterns/001-020_植物花卉纹/…"` |
| `batch` | source batch label | `"第01批_001-010_植物花卉纹"` |
| `image_sha256` | card image checksum | `"4984…fa6f"` |
| `source_note` | originality note | `"原创生成与再设计，不直接复制具体文物图案。"` |

Richer notes (composition / visual features / carriers / colour suggestions / modern uses / related patterns / tags) live in each `*_详情页.md`. The narrative text is currently in Chinese — English translations are on the roadmap.

---

## 🚀 How to use

**Browse** — visit [wenyang.net](https://wenyang.net), or open any pattern's `*_详情页.md` under `patterns/` here on GitHub.

**Download a single image** — open the pattern's folder and grab the `*_卡片图.png` card.

**Batch / programmatic** — read `data/patterns.json`:

```js
// Browser or Node
const patterns = await fetch(
  'https://raw.githubusercontent.com/dososo/chinese-traditional-patterns/main/data/patterns.json'
).then(r => r.json());

const flora = patterns.filter(p => p.category === '植物花卉纹');
console.log(flora[0].name_cn, flora[0].name_en, flora[0].visual_keywords);
```

```python
# Python
import json, urllib.request
url = "https://raw.githubusercontent.com/dososo/chinese-traditional-patterns/main/data/patterns.json"
patterns = json.load(urllib.request.urlopen(url))
print(len(patterns), patterns[0]["name_en"], patterns[0]["visual_keywords"])
```

> Usage is subject to the [content license](#-license) (CC BY-NC 4.0: free for non-commercial use, attribution required).

---

## 🗺 Roadmap

A **long-term project** — the catalogue keeps growing: **100 live / 800 planned · 700 to come, stay tuned**.

- [x] **v1 · first 100 patterns** (6 categories, high-res cards + structured data)
- [x] Live website [wenyang.net](https://wenyang.net) (search / favorites / palette / download)
- [ ] **Grow to 800 patterns** — the remaining ~700 released in batches
- [ ] Add English translations, period / region research and hex palettes to the dataset (already on the site, flowing back to open data)
- [ ] **A "Chinese Traditional Patterns" AI Skill** — let AI assistants tap this library for design help and Q&A
- [ ] More export formats (SVG line art, palette swatch files, etc.)

⭐ Star to be the first to know when new patterns land.

---

## 🤝 Contributing

Help make this library more accurate, more complete and more beautiful!

- 🔍 **Add research** — contribute reliable sources for a pattern's period, region or symbolism;
- 🌏 **Contribute translations** — translate the Chinese material into English and other languages;
- 🎨 **Contribute patterns** — submit new motifs (must be original re-designs, non-infringing);
- 💻 **Improve tooling** — data validation, export scripts, visualisations.

See [CONTRIBUTING.md](CONTRIBUTING.md). By contributing you agree to license your work under this repo's terms.

> 💌 **Have suggestions, or want to help maintain this for the long run?** Open an [Issue](https://github.com/dososo/chinese-traditional-patterns/issues) or reach me on X at [@thinkszyg](https://x.com/thinkszyg). One walks faster alone; together we go further.

---

## ❓ FAQ

**Q: Can I use these patterns commercially?**
A: Content is under CC BY-NC 4.0 — free for **non-commercial** use (with attribution). For commercial licensing, contact the author.

**Q: Are the images copied from artifacts?**
A: No. They are **original AI-assisted re-designs**, inspired by the visual language of traditional motifs, not direct copies of any specific artifact or copyrighted work.

**Q: Why is the data mostly in Chinese? Is there English?**
A: Names are bilingual; the detailed descriptions are currently mostly Chinese — **English translations are on the roadmap**. The site [wenyang.net](https://wenyang.net) offers more bilingual information.

**Q: Will it keep updating?**
A: Yes. It's a long-term project aiming for 800 patterns. ⭐ Star to follow updates.

**Q: I'd like to contribute or co-maintain — how?**
A: See [Contributing](#-contributing) — open an Issue / PR or contact the author.

---

## 📜 License

This repository is **dual-licensed**:

- **Code / data structure** (scripts, the schema & organisation of `*.json` / `*.csv`): [MIT](LICENSE)
- **Pattern images & text content** (`*.png` cards, written copy): [CC BY-NC 4.0](LICENSE-CONTENT.md)
  — free to copy, adapt and redistribute, **with attribution**, **for non-commercial use**.

For commercial licensing, please contact the author below.

---

## 👤 About the author

Created and maintained solo by **BLCaptain (爆裂队长NEXT)**.

- 🌐 Website: [wenyang.net](https://wenyang.net)
- 💻 GitHub: [@dososo](https://github.com/dososo)
- 🐦 X / Twitter: [@thinkszyg](https://x.com/thinkszyg)
- ✉️ Email: [blteam2026@outlook.com](mailto:blteam2026@outlook.com)

If this project helps you, a ⭐ Star, a share, or a hello on X is much appreciated.

---

## ⭐ Star History

[![Star History Chart](https://api.star-history.com/svg?repos=dososo/chinese-traditional-patterns&type=Date)](https://star-history.com/#dososo/chinese-traditional-patterns&Date)

---

## 🙏 Acknowledgements

Gratitude to the artisans of every Chinese dynasty for the beauty of these patterns. This project re-interprets tradition in a modern design language, so that this beauty may be seen, used and carried forward by more people.

<div align="center"><sub>An unbroken thread, endlessly renewing.</sub></div>
