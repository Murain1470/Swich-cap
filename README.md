# SwitchLens Pro 🎮

> 瀏覽器版 Nintendo Switch 擷取卡工具 — 免安裝，開啟即用。

![HTML](https://img.shields.io/badge/HTML-Single%20File-blue?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)
![Platform](https://img.shields.io/badge/Platform-Chrome%20%7C%20Edge-orange?style=flat-square)

---

## ✨ 功能

| 類別 | 功能 |
|------|------|
| 📺 影像 | WebGL 渲染、16:9 比例固定、滾輪縮放（最大 8x）、拖曳平移、雙擊重設 |
| 🔴 錄影 | WebM / MP4 格式、最高 50 Mbps 位元率可調 |
| 📷 截圖 | 無損 PNG 輸出 |
| 🔊 音訊 | High Fidelity / Low Latency 監聽模式切換 |
| 🌐 多語言 | 繁體中文 / English / 日本語 |
| ⌨️ 快捷鍵 | `Space` 錄影、`S` 截圖、`M` 靜音、`F` 全螢幕 |
| 🖥️ 沉浸模式 | 3 秒閒置自動隱藏 UI、全螢幕支援 |
| 📊 即時監控 | FPS 與解析度疊層顯示 |

---

## 🚀 快速開始

**不需要安裝任何東西。**

1. 下載 `index.html`
2. 用 Chrome 或 Edge 開啟
3. 插好擷取卡，點「授權並開始擷取」
4. 在瀏覽器彈窗中允許**攝影機**與**麥克風**權限

> ⚠️ 若裝置清單是空的，請先插好擷取卡再重新整理頁面。

---

## 🖥️ 瀏覽器相容性

| 瀏覽器 | 支援狀況 |
|--------|----------|
| Google Chrome 90+ | ✅ 完整支援 |
| Microsoft Edge 90+ | ✅ 完整支援 |
| Firefox | ⚠️ 部分功能受限（WebGL desynchronized） |
| Safari | ❌ 不支援（MediaRecorder 限制） |

---

## ⌨️ 快捷鍵

| 按鍵 | 功能 |
|------|------|
| `Space` | 開始 / 停止錄影 |
| `S` | 截圖 PNG |
| `M` | 靜音 / 取消靜音 |
| `F` | 全螢幕切換 |

---

## ⚙️ 進階設定

點底部導覽列的**「設定」**圖示可開啟進階設定，包含：

- **切換來源** — 即時切換影像/音訊裝置，無需重啟
- **錄製格式** — WebM（VP9）或 MP4（H.264）
- **視訊位元率** — 2 ~ 50 Mbps 可調
- **監聽模式** — High Fidelity（無損）或 Low Latency（低延遲）
- **FPS 疊層** — 即時顯示解析度與畫面率

---

## 📝 注意事項

- 所有媒體資料**僅在本機處理**，不會上傳至任何伺服器
- 錄影檔案直接下載到本機
- 延遲取決於作業系統與擷取卡驅動，瀏覽器環境約 30–150ms（低於 OBS，但免安裝）
- 若需要零延遲或串流功能，建議搭配 [OBS Studio](https://obsproject.com/)

---

## 🛠️ 技術棧

- Vanilla HTML / CSS / JavaScript（單一檔案，無框架依賴）
- [Tailwind CSS](https://tailwindcss.com/) via CDN
- [WebGL](https://developer.mozilla.org/en-US/docs/Web/API/WebGL_API) 影像渲染
- [MediaRecorder API](https://developer.mozilla.org/en-US/docs/Web/API/MediaRecorder)
- [getUserMedia API](https://developer.mozilla.org/en-US/docs/Web/API/MediaDevices/getUserMedia)

---

## 📄 License

MIT License — 自由使用、修改與分發。
