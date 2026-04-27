# Dan Koe 資料庫第一版

建立日期：2026-04-27  
備註：使用者原文寫「DANKOL」，本資料庫先以最可能對象「Dan Koe」整理。如果你指的是另一個品牌或人物，之後可直接改檔名與來源表。

## 檔案

- `dan-koe-master-profile.md`：主資料庫，含人物定位、商業模式、內容主軸、可學框架、風險判讀。
- `sources.csv`：來源表，可匯入 Notion、Google Sheet 或 Airtable。
- `frameworks.csv`：可直接拿來研究、拆解、改寫成你自己的內容/產品/筆記系統的框架表。
- `content-map.csv`：主流內容主題地圖，方便之後做選題資料庫。
- `dan-koe-summary-tw.md`：繁體中文摘要版，從簡單到進階說明 Dan Koe 的核心概念。
- `post-slices-tw.md`：15 篇可改寫後直接 PO 的繁體貼文切片。
- `post-slices-outline-tw.md`：比較不擠的條列版，適合貼到 Notion 或再丟給 AI 改寫。
- `post-slices-readable.html`：可直接用瀏覽器打開的閱讀版，含 Dan Koe 人物簡介、每集封面照、難度篩選、展開收合、複製貼文。
- `post-slices-tw.csv`：貼文切片資料表，可匯入 Notion / Sheet。
- `posts-data.json`：貼文資料底稿，含圖片、台灣例子、學生例子、AI prompt metadata、短影音欄位。
- `posting-strategy-tw.md`：給台灣觀眾的發文順序、難度階梯、貼文公式與 CTA 庫。
- `posting-helper-agent.md`：可重複使用的貼文幫手 Agent prompt。
- `../world-masters-database.html`：通用版「世界高手資料庫」網頁，可新增任何高手、內容集數、封面照、來源連結，並匯出/匯入 JSON。

## 使用方式

建議先把 `sources.csv` 匯入資料庫，再把 `frameworks.csv` 和 `content-map.csv` 分成兩個表，欄位用 `source_url` 回連到來源。之後你看到新的 Dan Koe 影片、文章、Podcast，可以用同樣欄位補上去。

## 可信度規則

- `official`：Dan Koe 官方網站、官方產品頁、Substack、Podcast 平台頁、Eden/Kortex 官方頁。
- `platform`：YouTube、Apple Podcasts、社群平台頁等平台資料。
- `third_party`：Social Blade、評論文章、案例拆解等，適合做輔助，不適合當成最終事實。
- `self_reported`：營收、學生數、客戶結果等由作者或銷售頁自述，使用時要標明「官方自述」。
