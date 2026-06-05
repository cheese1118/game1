# 幼升小暑假自習大冒險 V01 PWA 版

## GitHub Pages 上傳方式

1. 建立一個新的 GitHub Repository。
2. 將本資料夾內所有檔案上傳到 Repository 根目錄：
   - index.html
   - manifest.json
   - service-worker.js
   - icons/icon-192.png
   - icons/icon-512.png
3. 到 GitHub Repository 的 Settings → Pages。
4. Source 選擇 Deploy from a branch。
5. Branch 選擇 main / root。
6. 儲存後等待 GitHub Pages 產生網址。
7. 用手機 Safari 或 Chrome 開啟 GitHub Pages 網址，即可加入主畫面。

## 注意

此版已具備 PWA 基本格式與 Service Worker 快取。原版仍使用 Tailwind CDN 與 Google Fonts，因此第一次載入仍建議保持網路連線；成功載入一次後，Service Worker 會盡量快取資源。
若要完全無網路也穩定顯示，下一版建議製作「V02 完全離線版」。
