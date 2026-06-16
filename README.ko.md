<div align="center">

# Chinese Traditional Patterns · Wényàng

**중국 전통 문양을 위한 오픈소스 도록 — 미술관 도록 수준의 미감으로 둘러보고, 검색하고, 저장하고, 활용하세요.**

[简体中文](README.md) · [English](README.en.md) · [日本語](README.ja.md) · [한국어](README.ko.md)

[![Website](https://img.shields.io/badge/Browse-wenyang.net-1C7C54)](https://wenyang.net)
[![Patterns](https://img.shields.io/badge/patterns-100%20live%20/%20800%20planned-C9A85C)](#-로드맵)
[![Code License](https://img.shields.io/badge/code-MIT-blue)](LICENSE)
[![Content License](https://img.shields.io/badge/content-CC%20BY--NC%204.0-lightgrey)](LICENSE-CONTENT.md)

<img src="docs/screenshots/hero.jpeg" width="760" alt="Chinese Traditional Patterns · Wényàng">

</div>

---

## 📖 목차

- [소개](#-소개)
- [왜 만들었나](#-왜-만들었나)
- [라이브 사이트](#-라이브-사이트)
- [대표 문양 미리보기](#-대표-문양-미리보기)
- [저장소 구조](#-저장소-구조)
- [분류](#-분류)
- [데이터 포맷](#-데이터-포맷)
- [사용 방법](#-사용-방법)
- [로드맵](#-로드맵)
- [기여하기](#-기여하기)
- [자주 묻는 질문](#-자주-묻는-질문)
- [라이선스](#-라이선스)
- [제작자 소개](#-제작자-소개)
- [Star History](#-star-history)
- [감사의 말](#-감사의-말)

---

## ✨ 소개

**Chinese Traditional Patterns (Wényàng)** 는 디자이너와 문화 애호가를 위한 개방형 무료 중국 전통 문양 도록입니다.

도자기, 직금(織錦), 건축, 칠기 등에 흩어져 있던 전통 문양을 여기에서 **구조화되고 검색 가능한** 오픈 리소스로 새롭게 정리했습니다:

- 🖼 **고해상도 문양 카드 100점**(1086×1448 PNG), 6개 대분류로 정리;
- 📝 **카드마다 데이터 시트 1장**: 중국어·영어 명칭, 한 줄 요약, 문화적 상징, 시각적 키워드, 그리고 중국어 상세 페이지(구성 / 시각적 특징 / 일반적 사용처 / 색상 제안 / 현대적 활용 / 연관 문양 / 태그);
- 📦 **기계 판독 가능 데이터셋**: `data/patterns.json` 및 `data/patterns.csv`, 100개 레코드 전체를 집약하여 바로 사용 가능;
- 🌐 둘러보기·검색·즐겨찾기·팔레트 복사·원본 다운로드를 위한 도록 사이트 **[wenyang.net](https://wenyang.net)**.

> 모든 카드는 특정 유물을 그대로 복제한 것이 아니라 **AI 보조로 새롭게 재디자인한 원작**이며, 비상업적 학습·연구·창작 용도로 자유롭게 사용할 수 있습니다.

---

## 🎯 왜 만들었나

전통 문양을 찾다 보면 대개 타협하게 됩니다 — 플라스틱처럼 인공적인 "흔한 AI 미감", 저해상도 도용 이미지, 그리고 겹겹의 유료 장벽 사이에서 말이죠.

**우리는 다르게 하고 싶었습니다**: 중국 전통 문양을 **미술관 도록 수준의 미감**으로 정리하고, 재디자인하고, 풀어내어 — 디자이너와 문화 애호가가 이 원작 재디자인을 자유롭게 **둘러보고, 검색하고, 저장하고, 팔레트를 복사하고, 다운로드**할 수 있도록 하는 것입니다.

- 🎨 **미감 우선** — 도록 수준의 레이아웃과 색감, 플라스틱 같은 "흔한 AI" 느낌 없이;
- 🔓 **유료 장벽 없음** — 비상업적 용도로 개방되고 무료;
- 📚 **탄탄한 근거** — 단순한 이미지가 아니라 상징, 구성, 사용처, 팔레트까지;
- ♾ **장기적 유지** — 100점 공개, 800점 목표, 700점이 더 남아 끊임없이 성장 중.

---

## 🌐 라이브 사이트

브라우징 / 검색 / 즐겨찾기 / 팔레트 복사 / 원본 다운로드까지 전체 경험을 누리려면 👉 **[wenyang.net](https://wenyang.net)** 을 방문하세요.

<img src="docs/screenshots/home.jpeg" width="820" alt="중국 전통 문양 도감 홈페이지">

| 갤러리 | 문양 상세 |
|---|---|
| <img src="docs/screenshots/gallery.jpeg" alt="Gallery"> | <img src="docs/screenshots/detail.jpeg" alt="Detail page"> |

- 미술관 도록 수준의 미감, 세 가지 테마(쑤(素) / 선지(宣纸) / 묵야(墨夜));
- 데스크톱과 모바일 모두 반응형; 완전 정적이며 추적 없음(익명 방문 수만 집계).

> 참고: 웹사이트는 이중 언어 텍스트, 시기 / 지역 고증, 복사 가능한 HEX 팔레트도 함께 제공합니다. 이 저장소는 라이브러리의 **원본 소스 자료**를 제공합니다.

---

## 🖼 대표 문양 미리보기

<div align="center">

| <img src="docs/preview/001.jpg" width="180"><br>연꽃 당초문 | <img src="docs/preview/003.jpg" width="180"><br>모란문 | <img src="docs/preview/021.jpg" width="180"><br>용문 | <img src="docs/preview/028.jpg" width="180"><br>도철문 |
|:--:|:--:|:--:|:--:|
| <img src="docs/preview/041.jpg" width="180"><br>뇌문(회문) | <img src="docs/preview/061.jpg" width="180"><br>상운문 | <img src="docs/preview/076.jpg" width="180"><br>여의문 | <img src="docs/preview/091.jpg" width="180"><br>수(壽)자문 |

<sub>100점 중 8점 · 전체 라이브러리는 <a href="https://wenyang.net">wenyang.net</a> 에서</sub>

</div>

---

## 📁 저장소 구조

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

> 파일명은 원본 패키지에 충실하기 위해 중국어로 유지했습니다(`_卡片图` = 카드 이미지, `_详情页` = 상세 페이지, `_meta` = 메타데이터).

---

## 🗂 분류

| Folder | 分类 | Category | 개수 |
|--------|------|----------|:---:|
| `001-020_植物花卉纹` | 植物花卉纹 | 식물·꽃 문양 | 20 |
| `021-040_动物瑞兽纹` | 动物瑞兽纹 | 동물·서수 문양 | 20 |
| `041-060_几何锦纹` | 几何锦纹 | 기하 문양 | 20 |
| `061-075_云水山石纹` | 云水山石纹 | 구름·물·산석 문양 | 15 |
| `076-090_吉祥器物纹` | 吉祥器物纹 | 길상 기물 문양 | 15 |
| `091-100_文字福寿与组合纹` | 文字福寿与组合纹 | 문자·복수·복합 문양 | 10 |
| | **합계** | | **100** |

---

## 🔢 데이터 포맷

각 문양 폴더에는 세 개의 파일이 들어 있습니다: 고해상도 카드 `*_卡片图.png`, 중국어 상세 페이지 `*_详情页.md`, 그리고 메타데이터 `*_meta.json`.
`data/patterns.json` 은 100개의 `meta` 레코드 전체를 집약합니다:

| 필드 | 설명 | 예시 |
|-------|-------------|---------|
| `id` | 세 자리 번호 | `"001"` |
| `name_cn` / `name_en` | 중국어 / 영어 명칭 | `"缠枝莲纹"` / `"Interlocking Lotus Scroll Pattern"` |
| `category` | 분류(6개 중 하나) | `"植物花卉纹"` |
| `summary` | 한 줄 요약(중국어) | `"以莲花与卷曲藤蔓连续展开……"` |
| `meaning` | 문화적 상징(중국어) | `"清雅、连绵、生生不息"` |
| `visual_keywords` | 시각적 키워드(배열) | `["莲花","卷草","连续藤蔓","青绿白描"]` |
| `image_size` | 이미지 크기 | `"1086x1448"` |
| `card_image` / `detail_page` / `meta_json` | 세 파일에 대한 상대 경로 | `"patterns/001-020_植物花卉纹/…"` |
| `batch` | 출처 배치 라벨 | `"第01批_001-010_植物花卉纹"` |
| `image_sha256` | 카드 이미지 체크섬 | `"4984…fa6f"` |
| `source_note` | 원작성 표기 | `"原创生成与再设计，不直接复制具体文物图案。"` |

더 풍부한 주석(구성 / 시각적 특징 / 사용처 / 색상 제안 / 현대적 활용 / 연관 문양 / 태그)은 각 `*_详情页.md` 안에 있습니다. 서술형 텍스트는 현재 중국어로 되어 있으며, 영어 번역은 로드맵에 포함되어 있습니다.

---

## 🚀 사용 방법

**브라우징** — [wenyang.net](https://wenyang.net) 을 방문하거나, 여기 GitHub에서 `patterns/` 아래 임의의 문양 `*_详情页.md` 파일을 여세요.

**개별 이미지 다운로드** — 해당 문양의 폴더를 열고 `*_卡片图.png` 카드를 받으세요.

**일괄 / 프로그래밍 방식** — `data/patterns.json` 을 읽으세요:

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

> 사용은 [콘텐츠 라이선스](#-라이선스)(CC BY-NC 4.0: 비상업적 용도로 자유롭게 사용 가능, 출처 표시 필수)를 따릅니다.

---

## 🗺 로드맵

**장기 프로젝트**입니다 — 도록은 계속 성장합니다: **100점 공개 / 800점 목표 · 700점이 더 남아 있으니 기대해 주세요**.

- [x] **v1 · 첫 100점**(6개 대분류, 고해상도 카드 + 구조화된 데이터)
- [x] 라이브 사이트 [wenyang.net](https://wenyang.net)(검색 / 즐겨찾기 / 팔레트 / 다운로드)
- [ ] **800점까지 확장** — 나머지 약 700점을 순차적으로 공개
- [ ] 데이터셋에 영어 번역, 시기 / 지역 고증, HEX 팔레트 추가(이미 사이트에 적용되어 있으며, 오픈 데이터로 환원 예정)
- [ ] **「중국 전통 문양」 AI Skill** — AI 어시스턴트가 이 라이브러리를 활용해 디자인 보조와 질의응답을 할 수 있도록
- [ ] 더 많은 내보내기 포맷(SVG 라인 아트, 팔레트 견본 파일 등)

⭐ Star를 눌러 두면 새로운 문양이 공개될 때 가장 먼저 소식을 받을 수 있습니다.

---

## 🤝 기여하기

이 라이브러리를 더 정확하고, 더 완전하고, 더 아름답게 만드는 데 함께해 주세요!

- 🔍 **고증 보강** — 문양의 시기, 지역, 상징에 대한 신뢰할 수 있는 출처를 기여;
- 🌏 **번역 기여** — 중국어 자료를 영어 및 기타 언어로 번역;
- 🎨 **문양 기여** — 새로운 문양 제출(반드시 원작 재디자인이며 권리를 침해하지 않아야 함);
- 💻 **도구 개선** — 데이터 검증, 내보내기 스크립트, 시각화.

[CONTRIBUTING.md](CONTRIBUTING.md) 를 참고하세요. 기여하면 해당 작업물을 이 저장소의 약관에 따라 라이선스하는 데 동의하는 것으로 간주됩니다.

> 💌 **제안할 점이 있거나, 장기적으로 함께 유지·관리하고 싶으신가요?** [Issue](https://github.com/dososo/chinese-traditional-patterns/issues) 를 열거나 X [@thinkszyg](https://x.com/thinkszyg) 로 연락 주세요. 혼자 가면 빠르지만, 함께 가면 더 멀리 갑니다.

---

## ❓ 자주 묻는 질문

**Q: 이 문양들을 상업적으로 사용할 수 있나요?**
A: 콘텐츠는 CC BY-NC 4.0 라이선스를 따릅니다 — **비상업적** 용도로 무료입니다(출처 표시 필요). 상업적 라이선스는 제작자에게 문의해 주세요.

**Q: 이미지는 유물을 복제한 건가요?**
A: 아닙니다. 전통 문양의 시각 언어에서 영감을 받은 **AI 보조 원작 재디자인**이며, 특정 유물이나 저작권이 있는 작품을 그대로 복제한 것이 아닙니다.

**Q: 데이터가 대부분 중국어인 이유는요? 영어도 있나요?**
A: 명칭은 이중 언어이며, 상세 설명은 현재 대부분 중국어입니다 — **영어 번역은 로드맵에 포함되어 있습니다**. 사이트 [wenyang.net](https://wenyang.net) 에서 더 많은 이중 언어 정보를 제공합니다.

**Q: 계속 업데이트되나요?**
A: 네. 800점을 목표로 하는 장기 프로젝트입니다. 업데이트를 받으려면 ⭐ Star를 눌러 주세요.

**Q: 기여하거나 함께 유지·관리하고 싶은데 어떻게 하나요?**
A: [기여하기](#-기여하기) 를 참고하세요 — Issue / PR을 열거나 제작자에게 연락 주세요.

---

## 📜 라이선스

이 저장소는 **이중 라이선스**로 제공됩니다:

- **코드 / 데이터 구조**(스크립트, `*.json` / `*.csv` 의 스키마와 구성): [MIT](LICENSE)
- **문양 이미지 및 텍스트 콘텐츠**(`*.png` 카드, 작성된 문안): [CC BY-NC 4.0](LICENSE-CONTENT.md)
  — **출처를 표시하고**, **비상업적 용도**에 한하여 자유롭게 복제·각색·재배포할 수 있습니다.

상업적 라이선스가 필요하면 아래 연락처로 제작자에게 문의해 주세요.

---

## 👤 제작자 소개

**BLCaptain (爆裂队长NEXT)** 가 단독으로 제작하고 유지·관리합니다.

- 🌐 웹사이트: [wenyang.net](https://wenyang.net)
- 💻 GitHub: [@dososo](https://github.com/dososo)
- 🐦 X / Twitter: [@thinkszyg](https://x.com/thinkszyg)
- ✉️ 이메일: [blteam2026@outlook.com](mailto:blteam2026@outlook.com)

이 프로젝트가 도움이 되었다면 ⭐ Star, 공유, 또는 X에서의 인사 한마디가 큰 힘이 됩니다.

---

## ⭐ Star History

[![GitHub Repo stars](https://img.shields.io/github/stars/dososo/chinese-traditional-patterns?style=social)](https://github.com/dososo/chinese-traditional-patterns/stargazers)

> 📈 **[실시간 Star 추이 보기 →](https://star-history.com/#dososo/chinese-traditional-patterns&Date)**

---

## 🙏 감사의 말

이토록 아름다운 문양을 남겨 준 중국 역대 장인들에게 감사드립니다. 이 프로젝트는 전통을 현대적 디자인 언어로 다시 풀어내어, 그 아름다움이 더 많은 사람에게 보이고 쓰이며 이어지기를 바랍니다.

<div align="center"><sub>끊이지 않는 무늬의 맥, 생생히 이어지다.</sub></div>
