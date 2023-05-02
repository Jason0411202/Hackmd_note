# Angular 學習筆記
## 概述與使用原因
Angular是一個前端框架，能幫助開發者有效維護大型程式碼

優點:
1. 模組化
2. 架構明確
3. 維護簡單

## 開發環境配置
1. 下載Node.js與其套件管理系統NPM並安裝
    https://nodejs.org/en (點擊recommended)
    
2. 進入cmd，將目錄移至安裝的資料夾下，輸入以下指令安裝Angular CLI
    > npm install -g @angular/cli

3. 驗證是否安裝成功
    > node -v (node.js)
    > npm -v (NPM)
    > ng v  (CLI工具)

## 創建專案並執行
1. 輸入以下指令創建專案
```
ng new 專案名
```
:::warning
ex: ng new Hallo_World
:::

2. 切至專案資料夾中，並輸入以下指令執行
```
ng serve
```

網站預設會在此
:::warning
http://localhost:4200/
:::