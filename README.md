# ✈️ 環遊世界點擊探索指南 (Travel Pop-up Explorer)

一個以純原生 HTML5、CSS3 與 JavaScript 打造的趣味互動式世界地圖探索網頁，無需安裝任何套件與依賴，開箱即用！

---

## ✨ 核心特色

1. **🗺️ 國際標準向量地理邊界**：
   - 採用權威 Natural Earth 110m 真實地理向量邊界與端正的 Miller 圓柱投影。
   - 赤道與回歸線完全水平筆直，加美邊界端正平直，絕無變形與歪斜。
2. **🇹🇼 預設以台灣為核心聚焦**：
   - 電腦版與手機版各自擁有最佳黃金比例（手機版特寫台灣島長度達 80px+，電腦版兼顧亞太宏觀視野）。
   - 支援滑鼠拖曳、滾輪縮放、手機單指滑動與雙指捏合縮放 (Pinch-to-zoom)。
3. **💥 物理彈跳資訊卡 (Pop-up Bounce)**：
   - 點擊國家或地標時，彈出具備彈簧回彈效果的資訊卡（`@keyframes popIn`）。
   - 包含國旗、代表動植物、專屬法定貨幣與硬幣冷知識、驚喜 Fun Fact。
4. **✨ 炫彩 Emoji 粒子噴發特效**：
   - 點擊地圖或卡片元素時，游標處噴灑該國專屬的代表物、金幣與星星粒子。
5. **🌐 19 大世界知名代表國**：
   - 橫跨五大洲：美洲 5 國、歐洲 5 國、亞洲 5 國、非洲 2 國、大洋洲 2 國。

---

## 🚀 GitHub Pages 免費部署步驟

1. **在 GitHub 建立儲存庫**：
   - 前往 [GitHub New Repository](https://github.com/new)。
   - Repository name 輸入 `travel-explorer`（或自訂名稱）。
   - 設定為 **Public**（公開），不要勾選新增 README，直接點選 **Create repository**。

2. **在本地終端機推送程式碼**：
   ```bash
   git remote add origin https://github.com/<你的使用者名稱>/<你的儲存庫名稱>.git
   git push -u origin main
   ```

3. **啟用 GitHub Pages**：
   - 進入該儲存庫的 **Settings** 頁面。
   - 點擊左側選單的 **Pages**。
   - 在 **Build and deployment** 下方：
     - **Source** 選擇 `Deploy from a branch`
     - **Branch** 選擇 `main`，資料夾選擇 `/(root)`
     - 點擊 **Save**。

4. **完成上線**：
   - 等待約 1~2 分鐘後，重新整理 Pages 設定頁面，上方就會顯示您的專屬公開網址：
     `https://<你的使用者名稱>.github.io/<你的儲存庫名稱>/`
