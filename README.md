# 日常誌 DAILY TRACE

這是一個簡化版的靜態網站，風格接近原本的 Manus 網站，方便之後自己維護。

## 檔案說明

- `index.html`：主要頁面
- `style.css`：樣式檔
- `images/`：請自行建立此資料夾，並放入圖片

## 圖片放置方式

1. 在根目錄建立 `images` 資料夾
2. 把精選大圖命名為 `hero.jpg` 放進去
3. 其他圖片之後可以依需求新增

目前精選區塊會讀取 `images/hero.jpg`。如果圖片不存在，會自動隱藏，不影響版面。

## 如何新增文章

直接打開 `index.html`，找到 `<div class="entry-list">` 區塊。

複製其中一段 `<article class="entry">...</article>`，修改以下內容即可：

- 日期（year、day）
- 分類（data-cat 與 tag）
- 地點
- 標題
- 摘要
- 標籤

## 上傳到 GitHub

1. 把 `index.html`、`style.css` 覆蓋到你的 repository 根目錄
2. 建立 `images` 資料夾並放入圖片
3. 用 GitHub Desktop 或網頁上傳後 Commit + Push
4. 等待 1–3 分鐘，重新整理 https://bonic1001c.github.io/bonic.github.io/

## 注意

- 網址目前是 `https://bonic1001c.github.io/bonic.github.io/`
- 如果之後想改成更簡潔的 `https://bonic1001c.github.io`，需要把 repository 名稱改成 `bonic1001c.github.io`
