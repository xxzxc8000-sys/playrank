# 玩鑑 PlayRank

手機遊戲評測與排行資訊站，純 HTML5 / CSS3 / Vanilla JavaScript 打造，無框架依賴，可直接部署至 GitHub Pages。

## 檔案結構

```
playrank/
├── index.html        # 首頁（Hero、評測特色、遊戲排行、試玩、操作說明、活動、FAQ、CTA）
├── terms.html         # 權益說明（服務條款 / 隱私條款 / 遊戲規章）
├── 404.html           # 自訂錯誤頁
├── css/
│   └── style.css      # 設計系統：色彩、字體、版面、元件、動畫、RWD
├── js/
│   └── main.js        # Header 縮放、行動選單、捲動顯示、計數動畫、FAQ 手風琴
├── images/
│   └── favicon.svg
├── robots.txt
├── sitemap.xml
├── manifest.json
└── README.md
```

## 部署到 GitHub Pages

1. 建立新的 GitHub repository，將本資料夾內容全部上傳。
2. 進入 repository 的 **Settings → Pages**。
3. Source 選擇 `main` branch，資料夾選擇 `/ (root)`。
4. 儲存後，網站會發佈在 `https://<your-username>.github.io/<repo-name>/`。

部署前請將 `index.html`、`terms.html`、`sitemap.xml`、`robots.txt` 中的 `https://example.com` 替換為實際網域。

## 設計系統摘要

- **色彩**：墨夜藍 `#10102B`、次層藍 `#181B45`、電紫 `#7C5CFF`、薄荷綠 `#37E6B5`、霧白 `#F4F3FF`、灰紫 `#9291B5`
- **字體**：標題 Space Grotesk、正文 Inter、數據 JetBrains Mono
- **核心視覺**：首頁 Hero 的排行卡片會依序「歸位」成排序狀態，呼應網站排行的核心功能

## 內容聲明

本專案為手機遊戲評測與排行資訊網站範本，不含任何登入儲值、下注投注、真人對戰下注等博彩相關功能。若需擴充會員系統或第三方登入，建議另行評估相關法規與資料保護需求。
