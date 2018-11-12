## Gulp 與 Webpack 開發工具
gulp+webpack+scss+babel

附帶 [gulp-version-number](https://www.npmjs.com/package/gulp-version-number) 避免快取問題

### gulp-version-number
HTML 內圖片路徑會自動被加上`?v=xxxxxxx`
JS 或 CSS 檔自行加上 `?v={VERSION_REPlACE}`
詳細設定在 gulpfile 內

### 如何使用

***

Node 版本號 ： v8.9.4

npm 版本號 ： v5.6.0

***

安裝：

```
$ npm install
```

啟用：

```
$ npm run start
```

### 目錄結構

```
|-- src
   |-- scss
   |-- app
   |-- html
   |-- images
|-- dest
   |-- css
   |-- js
   |-- html
   |-- images
|-- .eslintrc          ## ESLint 相關設定
|-- gulpfile.js
|-- webpack.config.js
|-- package.json
|-- README.md
```
