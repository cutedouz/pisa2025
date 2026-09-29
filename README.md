# 看懂 PISA 2025

OECD《PISA 2025 Results (Volume I): Future-Ready Students》的中文互動導讀網站，內容包括：

- 首頁
- 七個發現
- 臺灣專頁
- 國家比較器
- 體驗區
- 資料說明

整個網站只有 `index.html` 一個檔案，不需要伺服器或資料庫。

## 用 GitHub Pages 公開

1. 登入 GitHub，點右上角 **＋ → New repository**。
   - Repository name 例如填 `pisa2025`。
   - 選 **Public**。
   - 按 **Create repository**。
2. 在新的 repository 頁面點 **uploading an existing file**（或 **Add file → Upload files**），把 `index.html`（和這份 `README.md`）拖進去，按 **Commit changes**。
3. 到 **Settings → Pages**：
   - **Source** 選 **Deploy from a branch**。
   - **Branch** 選 `main`，資料夾選 `/ (root)`。
   - 按 **Save**。
4. 等 1–2 分鐘，重新整理 Settings → Pages，上方會出現網址：
   `https://你的帳號.github.io/pisa2025/`

## 之後要更新

把新的 `index.html` 再上傳一次，覆蓋舊檔，並 Commit。GitHub Pages 會在一兩分鐘內自動更新。

## 可以直接連到某一頁

在網址後面加上 `#` 和頁面代號，就能直接開啟那一頁：

- `#findings`：七個發現；`#f1` 到 `#f7` 可以直接跳到某一個發現
- `#taiwan`：臺灣專頁
- `#compare`：國家比較器
- `#lab`：體驗區；也可以直接跳到單一體驗：`#lab-wind`、`#lab-claw`、`#lab-read`、`#lab-calc`
- `#about`：資料說明

例如：`https://你的帳號.github.io/pisa2025/#taiwan`

## 授權與出處

原始資料：OECD (2026), *PISA 2025 Results (Volume I): Future-Ready Students*, OECD Publishing, Paris, https://doi.org/10.1787/73451bc5-en（CC BY 4.0）。

本網站為非官方的中文改作，觀點不代表 OECD 或其會員國的官方立場；翻譯與原文有出入時，以原文為準。網站上不使用 OECD 的標誌或封面圖片。
