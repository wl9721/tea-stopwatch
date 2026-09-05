Tea Stopwatch｜GitHub Pages 上傳包

這個資料夾已經準備好直接放到 GitHub Pages。

檔案：
- index.html              主程式
- manifest.webmanifest    PWA 設定
- sw.js                   離線快取／更新
- icon.svg                主畫面圖示

第一次建立：
1. GitHub 建立新 Repository，名稱建議：tea-stopwatch
2. 把這 4 個檔案全部上傳到 Repository 根目錄
3. Repository → Settings → Pages
4. Build and deployment → Source 選 Deploy from a branch
5. Branch 選 main
6. Folder 選 / (root)
7. Save
8. 等 GitHub Pages 產生網址
9. 用 iPhone Safari 開該網址
10. Safari 分享 → 加入主畫面
11. 若 iPhone 有開「直向鎖定」，先關掉，才能橫直自動切換

之後改版：
- 保持網址不變
- 只要把新版 index.html（或其他有修改的檔案）覆蓋上傳
- GitHub Pages 更新後，Tea Stopwatch 下次開啟會優先抓新版
- 沒網路時仍會使用上一次快取的版本

V1.2 目前操作：
- 停止狀態：圓形「開始」
- 計時中：圓形「重置」
- 短按重置：00:00.0 並立即重新開始
- 長按約 0.85 秒：停止／重新啟動
- 顯示精度：0.1 秒
- 直放、橫放自動排版
- 計時中要求螢幕保持常亮
