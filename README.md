# 河內跨年自由行 12/31–1/4

手機版行程網頁，只有一個 `index.html`，不需要安裝或建置。

## 放到 GitHub Pages

1. 在 GitHub 建立新的 repository（例如 `hanoi-trip`）
2. 上傳 `index.html` 和 `README.md`
3. 到 **Settings → Pages**，Source 選 **Deploy from a branch**，Branch 選 `main`、資料夾選 `/ (root)`，按 Save
4. 大約 1–2 分鐘後，網址會是 `https://<你的帳號>.github.io/hanoi-trip/`

## 直接分享某一天

網址後面加上分頁代號，例如：

- `#prep` 行前準備
- `#d1` ～ `#d5` 第 1～5 天

## 修改行程

行程資料都在 `index.html` 裡的 `DAYS` 陣列，每一筆行程的欄位：

| 欄位 | 說明 |
|---|---|
| `t` / `sm` | 時間／副時間 |
| `title` / `sub` | 名稱／越南文或地點 |
| `cost` | 費用 |
| `st` | `ok` 已預訂、`tbd` 待確認，其他不顯示 |
| `art` | 插畫代號（見 `ART` 物件） |
| `q` | Google 地圖與照片的搜尋關鍵字 |
| `desc` / `info` / `tips` | 介紹段落／資訊表／小提醒 |

> 注意：GitHub Pages 的公開 repo 任何人都看得到，不要放訂位代號、護照號碼等個人資料。
