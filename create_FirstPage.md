
### 1️⃣ 建立 Repository

在 GitHub 上新增一個 repo：

```
gigi-igig.github.io
```

⚠️ 名字一定要完全一樣！

---

### 2️⃣ 放網站檔案

上傳你的靜態網站內容，例如：

```
index.html
style.css
script.js
```

最基本可以先放一個：

```html
<!DOCTYPE html>
<html>
<head>
  <title>My Website</title>
</head>
<body>
  <h1>Hello GitHub Pages </h1>
</body>
</html>
```

---

### 3️⃣ 開啟 GitHub Pages

進 repo：

```
Settings → Pages
```

設定：

* Source: `Deploy from a branch`
* Branch: `main`
* Folder: `/ (root)`

按 Save

---

### 4️⃣ 等待部署（約 1～2 分鐘）

完成後就可以開：

```
https://gigi-igig.github.io
```

---

CSS 分工範例：

| CSS 檔案         | 功能                                          |
| -------------- | ------------------------------------------- |
| base.css       | 全域設定         |
| layout.css     | 版面配置、容器、header/footer |
| components.css | 可重用元件                   |
| project.css      | project.html 專屬樣式           |
| index.css      | index.html 專屬樣式           |
| typography.css | 文字樣式、標題、subtitle                      |
| responsive.css | 響應式           |
| style.css      | 導入以上 CSS                                    |

---

gigi-igig.github.io/
│
├── index.html          ← 首頁
├── page/
│   └── project.html
│
├── css/
│   └── style.css
├── images/
