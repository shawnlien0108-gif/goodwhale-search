# 財鯨動向 直播索引（公開網站）

用關鍵字找財鯨動向每週直播講過的主題。

- `index.html`：整個網站（首頁、搜尋結果、播放頁），不需要安裝任何東西
- `data.json`：網站讀取的資料，由私人的 `video_index` 索引產生，只包含標題、摘要、標籤，**不含逐字稿**

更新方式：Claude 整理完新的集數後，會同時更新 `video_index` 和這裡的 `data.json`，到 GitHub Desktop 按 Commit、Push，網站幾分鐘內就會更新。
