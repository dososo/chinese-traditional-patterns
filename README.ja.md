<div align="center">

# Chinese Traditional Patterns · Wényàng

**中国伝統紋様のオープンカタログ — 美術館の図録のような審美性で、閲覧・検索・保存・活用できます。**

[简体中文](README.md) · [English](README.en.md) · [日本語](README.ja.md) · [한국어](README.ko.md)

[![Website](https://img.shields.io/badge/Browse-wenyang.net-1C7C54)](https://wenyang.net)
[![Patterns](https://img.shields.io/badge/patterns-100%20live%20/%20800%20planned-C9A85C)](#-ロードマップ)
[![Code License](https://img.shields.io/badge/code-MIT-blue)](LICENSE)
[![Content License](https://img.shields.io/badge/content-CC%20BY--NC%204.0-lightgrey)](LICENSE-CONTENT.md)

<img src="docs/screenshots/hero.jpeg" width="760" alt="Chinese Traditional Patterns · Wényàng">

</div>

---

## 📖 目次

- [概要](#-概要)
- [なぜ作ったのか](#-なぜ作ったのか)
- [公開サイト](#-公開サイト)
- [注目の紋様プレビュー](#-注目の紋様プレビュー)
- [リポジトリ構成](#-リポジトリ構成)
- [カテゴリ](#-カテゴリ)
- [データ形式](#-データ形式)
- [使い方](#-使い方)
- [ロードマップ](#-ロードマップ)
- [コントリビュート](#-コントリビュート)
- [FAQ](#-faq)
- [ライセンス](#-ライセンス)
- [作者について](#-作者について)
- [Star History](#-star-history)
- [謝辞](#-謝辞)

---

## ✨ 概要

**Chinese Traditional Patterns（Wényàng）** は、デザイナーや文化愛好家のためのオープンで無料の中国伝統紋様カタログです。

陶磁器・錦・建築・漆器などに散らばっていた伝統的なモチーフを、ここでは **構造化され、検索可能な** オープンリソースとして再編成しています。

- 🖼 **高解像度の紋様カード100点**（1086×1448 PNG）を、6つのカテゴリに分類；
- 📝 **カードごとのデータシート**：中国語名・英語名、一行要約、文化的な象徴、ビジュアルキーワード、さらに中国語の詳細ページ（構図／ビジュアルの特徴／主な使用媒体／配色の提案／現代的な活用／関連紋様／タグ）；
- 📦 **機械可読なデータセット**：`data/patterns.json` と `data/patterns.csv` に全100件のレコードを集約し、すぐに利用可能；
- 🌐 閲覧・検索・お気に入り登録・配色のコピー・原寸ダウンロードができる、付属のカタログサイト **[wenyang.net](https://wenyang.net)**。

> すべてのカードは **AI 支援によるオリジナルの再デザイン** であり、特定の文物をそのまま複製したものではありません。非商用の学習・研究・創作目的で自由に利用できます。

---

## 🎯 なぜ作ったのか

伝統紋様を探すとき、たいていは何かを妥協させられます。プラスチックのように安っぽい「いかにも AI らしい審美性」、低解像度の盗用画像、そして幾重にも重なる有料の壁——そのいずれかに。

**私たちは、違うやり方をしたいと考えました**：中国の伝統紋様を **美術館の図録のような審美性** で整理し、再デザインし、解説する——デザイナーや文化愛好家が、これらのオリジナル再デザインを自由に **閲覧・検索・保存し、配色をコピーし、ダウンロード** できるように。

- 🎨 **審美性を最優先** — 図録水準のレイアウトと色づかい。安っぽい「いかにも AI」な見た目とは無縁；
- 🔓 **有料の壁なし** — オープンで、非商用なら無料；
- 📚 **裏づけがある** — 画像だけでなく、象徴・構図・使用媒体・配色まで；
- ♾ **長期的に維持** — 100点公開、800点を計画、残り700点、つねに成長を続けます。

---

## 🌐 公開サイト

閲覧／検索／お気に入り／配色のコピー／原寸画像のダウンロードといったすべての体験は、ぜひこちらから 👉 **[wenyang.net](https://wenyang.net)**

| ギャラリー | 紋様の詳細 |
|---|---|
| <img src="docs/screenshots/gallery.jpeg" alt="Gallery"> | <img src="docs/screenshots/detail.jpeg" alt="Detail page"> |

- 美術館の図録を思わせる審美性、3つのテーマ（蘇／宣紙／墨夜）；
- デスクトップ・モバイルの両方に対応するレスポンシブ設計。完全な静的サイトで、トラッキングは一切なし（匿名のアクセス数のみ）。

> 補足：サイトでは二言語のテキスト、時期・地域の考証、コピー可能な HEX 配色も提供しています。本リポジトリは、このライブラリの **オリジナル素材** を提供するものです。

---

## 🖼 注目の紋様プレビュー

<div align="center">

| <img src="docs/preview/001.jpg" width="180"><br>唐草蓮文 | <img src="docs/preview/003.jpg" width="180"><br>牡丹文 | <img src="docs/preview/021.jpg" width="180"><br>龍文 | <img src="docs/preview/028.jpg" width="180"><br>饕餮文 |
|:--:|:--:|:--:|:--:|
| <img src="docs/preview/041.jpg" width="180"><br>雷文（回文） | <img src="docs/preview/061.jpg" width="180"><br>瑞雲文 | <img src="docs/preview/076.jpg" width="180"><br>如意文 | <img src="docs/preview/091.jpg" width="180"><br>寿字文 |

<sub>100点のうち8点 · 全ライブラリは <a href="https://wenyang.net">wenyang.net</a> でご覧いただけます</sub>

</div>

---

## 📁 リポジトリ構成

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

> ファイル名は、オリジナルパッケージに忠実であるため中国語のまま残しています（`_卡片图` = カード画像、`_详情页` = 詳細ページ、`_meta` = メタデータ）。

---

## 🗂 カテゴリ

| Folder | 分类 | Category | 点数 |
|--------|------|----------|:---:|
| `001-020_植物花卉纹` | 植物花卉纹 | 植物・花卉文 | 20 |
| `021-040_动物瑞兽纹` | 动物瑞兽纹 | 動物・瑞獣文 | 20 |
| `041-060_几何锦纹` | 几何锦纹 | 幾何文 | 20 |
| `061-075_云水山石纹` | 云水山石纹 | 雲・水・山石文 | 15 |
| `076-090_吉祥器物纹` | 吉祥器物纹 | 吉祥器物文 | 15 |
| `091-100_文字福寿与组合纹` | 文字福寿与组合纹 | 文字・福寿・複合文 | 10 |
| | **合計** | | **100** |

---

## 🔢 データ形式

各紋様のフォルダには3つのファイルが含まれます：高解像度カード `*_卡片图.png`、中国語の詳細ページ `*_详情页.md`、そしてメタデータ `*_meta.json`。
`data/patterns.json` は、全100件の `meta` レコードを集約したものです：

| フィールド | 説明 | 例 |
|-------|-------------|---------|
| `id` | 3桁のID | `"001"` |
| `name_cn` / `name_en` | 中国語名／英語名 | `"缠枝莲纹"` / `"Interlocking Lotus Scroll Pattern"` |
| `category` | カテゴリ（6つのいずれか） | `"植物花卉纹"` |
| `summary` | 一行要約（中国語） | `"以莲花与卷曲藤蔓连续展开……"` |
| `meaning` | 文化的な象徴（中国語） | `"清雅、连绵、生生不息"` |
| `visual_keywords` | ビジュアルキーワード（配列） | `["莲花","卷草","连续藤蔓","青绿白描"]` |
| `image_size` | 画像サイズ | `"1086x1448"` |
| `card_image` / `detail_page` / `meta_json` | 3つのファイルへの相対パス | `"patterns/001-020_植物花卉纹/…"` |
| `batch` | 出典バッチのラベル | `"第01批_001-010_植物花卉纹"` |
| `image_sha256` | カード画像のチェックサム | `"4984…fa6f"` |
| `source_note` | オリジナリティに関する注記 | `"原创生成与再设计，不直接复制具体文物图案。"` |

より詳しい解説（構図／ビジュアルの特徴／使用媒体／配色の提案／現代的な活用／関連紋様／タグ）は、各 `*_详情页.md` に収められています。解説文は現在のところ中国語です。英訳はロードマップに含まれています。

---

## 🚀 使い方

**閲覧** — [wenyang.net](https://wenyang.net) を訪れるか、ここ GitHub 上の `patterns/` 配下にある任意の紋様の `*_详情页.md` を開いてください。

**単一画像のダウンロード** — 紋様のフォルダを開き、`*_卡片图.png` カードを取得してください。

**バッチ／プログラムによる利用** — `data/patterns.json` を読み込みます：

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

> 利用は [コンテンツライセンス](#-ライセンス)（CC BY-NC 4.0：非商用に限り無料、表示が必要）に従ってください。

---

## 🗺 ロードマップ

これは **長期プロジェクト** です。カタログは成長を続けます：**100点公開／800点を計画 · 残り700点、お楽しみに**。

- [x] **v1 · 最初の100紋様**（6カテゴリ、高解像度カード + 構造化データ）
- [x] 公開サイト [wenyang.net](https://wenyang.net)（検索／お気に入り／配色／ダウンロード）
- [ ] **800紋様まで拡充** — 残る約700点をバッチごとに公開
- [ ] データセットへ英訳・時期/地域の考証・HEX 配色を追加（サイトには実装済み。オープンデータへ還元していく）
- [ ] **「中国伝統紋様」AI スキル** — AI アシスタントがこのライブラリを活用し、デザイン支援や Q&A を行えるように
- [ ] エクスポート形式の拡充（SVG 線画、配色スウォッチファイルなど）

⭐ Star を付けておくと、新しい紋様が公開されたときに誰よりも早く知ることができます。

---

## 🤝 コントリビュート

このライブラリを、より正確に、より充実したものに、そしてより美しくするのを手伝ってください！

- 🔍 **考証を追加** — 紋様の時期・地域・象徴について、信頼できる出典を寄せる；
- 🌏 **翻訳を寄稿** — 中国語の素材を英語やその他の言語へ翻訳する；
- 🎨 **紋様を寄稿** — 新しいモチーフを投稿する（オリジナルの再デザインで、権利を侵害しないものに限る）；
- 💻 **ツールを改善** — データ検証、エクスポートスクリプト、可視化など。

[CONTRIBUTING.md](CONTRIBUTING.md) を参照してください。コントリビュートすることで、あなたの成果物を本リポジトリの条件の下でライセンスすることに同意したものとみなされます。

> 💌 **ご提案があったり、長期的な維持を一緒に担いたいと思ったら？** [Issue](https://github.com/dososo/chinese-traditional-patterns/issues) を立てるか、X の [@thinkszyg](https://x.com/thinkszyg) までご連絡ください。一人なら速く進めますが、共にならより遠くへ行けます。

---

## ❓ FAQ

**Q: これらの紋様を商用利用できますか？**
A: コンテンツは CC BY-NC 4.0 のもとにあります——**非商用** 利用に限り無料です（表示が必要）。商用ライセンスについては作者までご連絡ください。

**Q: 画像は文物を複製したものですか？**
A: いいえ。これらは **AI 支援によるオリジナルの再デザイン** であり、伝統的なモチーフのビジュアル言語に着想を得たもので、特定の文物や著作権で保護された作品をそのまま複製したものではありません。

**Q: なぜデータはほとんど中国語なのですか？英語はありますか？**
A: 名称は二言語です。詳しい解説は現在のところほとんど中国語ですが——**英訳はロードマップに含まれています**。サイト [wenyang.net](https://wenyang.net) では、より多くの二言語情報を提供しています。

**Q: 今後も更新されますか？**
A: はい。800紋様を目指す長期プロジェクトです。⭐ Star を付けて更新をフォローしてください。

**Q: コントリビュートや共同維持をしたいのですが、どうすれば？**
A: [コントリビュート](#-コントリビュート) を参照してください——Issue / PR を立てるか、作者までご連絡ください。

---

## 📜 ライセンス

本リポジトリは **デュアルライセンス** です：

- **コード／データ構造**（スクリプト、`*.json` / `*.csv` のスキーマと構成）：[MIT](LICENSE)
- **紋様画像とテキストコンテンツ**（`*.png` カード、執筆されたテキスト）：[CC BY-NC 4.0](LICENSE-CONTENT.md)
  — **表示を条件に**、**非商用に限り**、複製・改変・再配布が自由です。

商用ライセンスについては、下記の作者までご連絡ください。

---

## 👤 作者について

**BLCaptain（爆裂队長NEXT）** が単独で制作・維持しています。

- 🌐 ウェブサイト：[wenyang.net](https://wenyang.net)
- 💻 GitHub：[@dososo](https://github.com/dososo)
- 🐦 X / Twitter：[@thinkszyg](https://x.com/thinkszyg)

このプロジェクトがお役に立てたなら、⭐ Star やシェア、X での一声をいただけると大変うれしいです。

---

## ⭐ Star History

[![Star History Chart](https://api.star-history.com/svg?repos=dososo/chinese-traditional-patterns&type=Date)](https://star-history.com/#dososo/chinese-traditional-patterns&Date)

---

## 🙏 謝辞

これらの紋様の美を生み出した、中国の歴代王朝の職人たちに感謝します。本プロジェクトは伝統を現代のデザイン言語で読み解き直し、その美がより多くの人々に見られ、使われ、受け継がれていくことを願っています。

<div align="center"><sub>An unbroken thread, endlessly renewing.</sub></div>
