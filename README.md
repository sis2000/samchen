業務 SOP 教育訓練系統 (Sales SOP Training Portal)

這是一個基於 Web 的互動式教育訓練平台，旨在幫助業務同仁快速掌握標準作業流程 (SOP)。本系統將傳統的 Word 文件轉化為易於閱讀、互動性強的網頁應用程式，並支援跨國團隊的雙語需求。

🚀 功能特色 (Features)

單一檔案架構 (Single HTML File)：無需安裝任何伺服器或編譯工具，下載即可直接在瀏覽器運行。

雙語切換系統 (Bilingual Support)：內建「繁體中文 / 越南文」一鍵切換，適合跨國工廠與業務團隊使用。

結構化導覽 (Structured Navigation)：左側導覽列整合 8 大流程章節，手機版自動適配。

互動式學習 (Interactive Content)：

流程步驟：卡片式呈現，清晰易讀。

時程與職責 (Analysis)：整合「標準時程表」與「職責矩陣」，明確定義各角色權責與作業時間。

隨堂測驗 (Quiz)：每章節附帶互動測驗與即時評分功能。

📅 版本修改記錄 (Changelog)

v1.0.3 (Current) - 2025-01-10

[修正] 資料錯誤：修正第七章與第八章的「隨堂測驗」題目在中文模式下誤顯示為越南文的問題。

[優化] 代碼清理：移除未使用的 Chart.js 相關設定，提升載入效能。

v1.0.2 - 2025-01-10

[修正] 顯示錯誤：修正第七章「職責矩陣」在中文模式下誤顯示為越南文的問題。

[優化] 手機體驗：優化側邊導覽列在手機版點擊後的自動收合行為。

v1.0.1 - 2025-01-10

[變更] 視覺化調整：

應需求移除原本的「工作權重分佈圖」 (Pie/Bar Charts)。

新增 「標準時程表 (Time Management Table)」，根據 SOP 文件具體列出各階段工時（如：皮料交期 30-35 天、BOM Ready 前置期等）。

[保留] 核心功能：保留並優化「職責矩陣」顯示方式。

v1.0.0 - Initial Release

專案初始化：將 Word 版 SOP 轉化為 SPA (Single Page Application) 網頁。

核心架構：建立 Tailwind CSS 響應式介面、章節切換邏輯。

功能實作：完成雙語切換、測驗計分系統。

🛠️ 如何使用 (How to Use)

下載：將專案中的 index.html (或 SOP_Training_System.html) 下載到您的電腦。

開啟：直接雙擊檔案，使用 Chrome、Edge 或 Safari 瀏覽器開啟即可。

部署 (可選)：

將檔案上傳至 GitHub Repository。

開啟 GitHub Pages 功能 (Settings -> Pages -> Branch: main -> Save)。

分享生成的網址給團隊成員。

📂 檔案結構

.
├── index.html      # 完整應用程式代碼 (包含 HTML/CSS/JS)
└── README.md       # 專案說明與修改記錄
