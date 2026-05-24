# ANTIGRAVITY
## 💡 產品初心痛點洞察 (Product Insights)

身為一個追求輕鬆、不愛計畫的 P 人 ，每次出國旅行最痛苦的就是：
1. 收據重力： 日本街頭根本找不到垃圾桶！塞了一口袋的紙本單據，還要小心翼翼弄丟。
2. 算錢心累：團體旅行每筆消費成員都不同（有人不吃牛、有人沒去遊樂園），傳統均分工具不夠人性化。
3. 突發狀況： 旅途中常有朋友「日幣現金不夠」，需要緊急針對特定幾筆帳目「提前局部結算」拿回現金。

---

## ✨ 核心功能 (Core Features)

本產品雖然是出於好玩而開發，但依循著標準的產品經理（PM）敏捷思維，逐步擴充至企業級應用的功能規模：

*    誰出錢、誰有份？動態彈性分帳：支援自定義付款人，並可透過勾選精準選擇分攤成員，彈性應對各種消費場景。
*    跨國在地化 (Localization)**：內建繁體中文、簡體中文、英文三語系一鍵切換，方便與不同背景的國際旅伴協作。
*    多貨幣即時轉換：支援日幣 (JPY)、台幣 (TWD)、港幣 (HKD)、美金 (USD) 等，免去手動按計算機換匯的痛苦。
*    局部/選擇性結算 (Selective Settlement)：最具彈性的殺手級功能！允許勾選部分帳目優先結清，完美解決旅伴現金短缺的燃眉之急。

---

## 🛠️ 技術架構 (Technical Stack)

為了確保在國外**網路不穩、甚至斷網**的極端環境下仍能流暢使用，本專案採用完全去中心化、無後端 (Serverless) 的極輕量架構：

*   **Frontend:** HTML5, CSS3 (Tailwind CSS CDN), Vanilla JavaScript (ES6+).
*   **Storage:** `LocalStorage` (資料完全儲存在使用者手機瀏覽器，不斷網、不外洩、隱私安全)。
*   **Libraries:** `html2pdf.js` / `jspdf` 用于處理前端 PDF 渲染與下載。
*   **Deployment:** GitHub Pages (自動化靜態網頁部署)。

---

## 📊 履歷亮點與商管思維 (CV Highlights)

這個專案體現了開發者跨領域的 產品管理 (Product Management) 與 自學能力 (Self-Learning)：
1.  使用者導向思維 (User-Centric Design)：精準捕捉旅行者在特定場景（如日本垃圾桶少、日幣現金不足）的痛點，並將其轉化為產品功能。
2.  國際化思維 (Global Mindset)：從架構初期即規劃多語系與多貨幣支援，展現對國際市場在地化（Localization）的敏感度。
3.  敏捷產品開發 (Agile Development)：獨立完成從痛點發現、PRD（產品規格書）擬定、前端 UI/UX 開發到最終上線部署的完整產品生命週期。

網址 :file:///C:/Users/yixia/.gemini/antigravity/scratch/travel_app/index.html
