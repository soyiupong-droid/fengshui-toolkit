# Feng Shui Toolkit

手機優先的風水工具入口，集中開啟以下現有應用：

- 羅盤地圖（compass-map）
- 擇日小幫手（luckyday）
- 奇門通勝（luckyday-2）
- 奇門導航（qimen-navigator）

首頁是所有工具的單一網站入口；每個工具保留為獨立頁面，並隨本專案一同部署。
原有 repositories 不會被修改。

## 本機預覽

```bash
python3 -m http.server 4173
```

然後開啟 `http://localhost:4173`。

## 部署

所有檔案均為靜態內容，可直接部署至 GitHub Pages 或其他靜態網站服務。透過 HTTPS
部署後可安裝到手機主畫面。
