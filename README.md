# 🌟 我的網頁作品集 (Mobile-First Web Portfolio)

> 專為行動端打造的高質感網頁作品集，收錄一頁式文化紀念網頁、沉浸式計時工具、動態桌布與結構化研究圖表。

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![License](https://img.shields.io/badge/License-MIT-blue?style=flat-square)

---

## 📱 核心特色 (Features)

* **手機優先設計 (Mobile-First Architecture)**：以智慧型手機為第一出發點，具備底部常駐導覽列、橫向分類滑動膠囊與極致流暢的觸控反饋。
* **雙模式無縫切換**：整合「作品目錄」與「關於我」分頁切換，具備平滑滾動與即時篩選能力。
* **原生 Web API 深度整合**：全面運用 Web Audio API、Fullscreen API、Clipboard API、Web Storage API 與 Date/Timer API，無額外重量級前端框架依賴。
* **高質感視覺與深色主題**：採用現代深色科技美學（Slate 950 色系），並針對文字排版與陰影動效進行細緻調校。

---

## 📂 作品目錄 (Projects & Catalog)

| 作品名稱 | 檔案路徑 | 類型 | 核心技術 / Web APIs |
| :--- | :--- | :---: | :--- |
| **倪柝聲紀念網頁** | [`web.html`](web.html) | 紀念專頁 | `Clipboard API`, `Web Storage API`, `DOM Events API`, `Tailwind CSS` |
| **極簡多風格計時鐘** | [`tools/colock.html`](tools/colock.html) | 實用工具 | `Web Audio API`, `Fullscreen API`, `Timing API`, `Local Storage API` |
| **屬靈桌布與紀念站** | [`about/index.html`](about/index.html) | 紀念專頁 | `Unsplash Web API`, `JavaScript Date API`, `CSS Transform`, `Touch Events` |
| **亞伯拉罕歷程對照表** | [`art/abraham_comparison_table.md`](art/abraham_comparison_table.md) | 研究圖表 | `Markdown Table`, `Horizontal Scroll API`, `PDF Viewer` |

---

## 🔍 作品詳細簡介

### 1. 倪柝聲紀念網頁 (`web.html`)
一頁式歷史屬靈紀念網站，深入整理倪柝聲先生生平年表、核心著作選輯、心靈箴言與經典名句。介面提供即時全文搜尋高亮、字級無段縮放與佳句一鍵複製功能，讓讀者無論在行動裝置或電腦端，皆能享受典雅沉靜的閱讀與研究體驗。

### 2. 極簡多風格超大數字計時鐘 (`tools/colock.html`)
專為高效率專注打造的多風格時鐘與倒數計時工具。支援全螢幕沉浸顯示、番茄鐘工作法、自訂計時長度與提示音效，並收錄溫暖鄉村、復古打字機、書香典雅及深色護眼等多種視覺主題，提供極致流暢與簡約的美學計時介面。

### 3. 屬靈桌布與生平紀念站 (`about/index.html`)
結合動態桌布更換與大字即時走時的特色網頁，收錄倪柝聲珍貴生平遺言手跡、名字由來與召會運動歷程。內建右側滑入式半透明設定面板，提供隨機高畫質風景切換與即時鐘錶展示，呈現兼具視覺美感與文史深度的互動體驗。

### 4. 亞伯拉罕神學歷程對照表 (`art/abraham_comparison_table.md`)
系統化梳理聖經創世記中亞伯拉罕十八個關鍵屬靈階段的結構化分析對照表。全面統整神的呼召、顯現、說話與立約歷程，清楚呈現神在各個階段的屬性與對信徒生命之深遠塑造，為查經與神學研究提供清晰直觀的對照檢索依據。

---

## 🗂️ 專案目錄結構 (Project Structure)

```text
watchmannee/
├── index.html            # 主首頁：手機優先作品集入口與關於我
├── web.html              # 倪柝聲生平與著作一頁式紀念網頁
├── README.md             # 專案說明文件
├── about/                # 屬靈桌布與紀念站
│   └── index.html
├── tools/                # 實用工具集（含多風格超大數字計時鐘）
│   └── colock.html
├── art/                  # 圖表與神學研究對照表
│   ├── 2026-05 fITERO02圖表.pdf
│   └── abraham_comparison_table.md
├── videos/               # 影像素材與歷史手跡照片
│   ├── handwriting.0.jpg
│   ├── Nee-Watchman.webp
│   ├── WatchmanNee.jpg
│   └── 亞伯拉罕.jpg
├── apps/                 # 應用程式擴充模組目錄
├── games/                # 遊戲擴充模組目錄
└── music/                # 音樂擴充模組目錄
```

---

## 🚀 本地開啟與使用 (Getting Started)

1. **直接開啟**：
   在瀏覽器中直接按兩下開啟 `index.html` 即可瀏覽作品集首頁。

2. **使用靜態伺服器**（推薦）：
   ```bash
   # 使用 Python
   python -m http.server 8080
   
   # 或使用 Node.js npx
   npx serve
   ```
   瀏覽器開啟 `http://localhost:8080` 或相應端口。

---

## 👤 作者 (Author)

* **GitHub**: [@xiaowu97-commits](https://github.com/xiaowu97-commits)

---

## 📄 授權 (License)

本專案採用 [MIT License](LICENSE) 授權。
