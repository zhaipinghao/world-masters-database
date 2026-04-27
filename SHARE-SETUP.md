# 分享網址設定

目前本機網址像這樣：

```text
file:///Users/linyuchen/Documents/New%20project/index.html
```

這種網址只能在你的電腦打開，傳給別人會失效。要讓別人能看，需要部署成公開網址。

## 建議公開入口

部署後請把公開網址指向：

```text
index.html
```

這個入口會連到：

- `world-masters-database.html`
- `dan-koe-database/post-slices-readable.html`

## 可用部署方式

### 方式 1：Netlify Drop

最簡單。把整個 `/Users/linyuchen/Documents/New project` 資料夾拖到 Netlify Drop，就會得到一個公開網址。

### 方式 2：GitHub Pages

適合長期版本管理。把這個資料夾 push 到 GitHub repo，再開 GitHub Pages。

### 方式 3：Vercel

適合之後要加後端或登入功能。靜態 HTML 也可以直接部署。

## 分享網址要記錄在哪裡

請更新：

```text
share-registry.json
```

欄位說明：

- `local_url`：本機網址，只給自己用。
- `public_url`：公開網址，可傳給別人。
- `status`：`local_only`、`published`、`archived`。
- `notes`：這個連結的用途。

## 注意

公開部署會把檔案上傳到第三方平台，別人可能看得到你的頁面內容。正式部署前，先確認頁面裡沒有私人資料、客戶資料、金鑰、內部文件或不想公開的內容。

