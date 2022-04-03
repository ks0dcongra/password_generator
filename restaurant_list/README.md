# 餐廳清單 2.0

此專案提供使用者新增、刪除及修改餐廳的資訊，例如:餐廳類別、地址、評分、描述等

## 功能列表

1. 依照餐廳名稱及餐廳類別搜尋
  - 優化搜尋功能
  - 剔除多餘的空白
  - 搜尋沒有結果時也有對應頁面提示
2. 可從首頁點擊餐廳圖片了解餐廳詳細資訊

## 先決條件
* Windows系統

### 安裝

1.開啟終端機(Terminal)cd 到存放專案本機位置並執行:

```
git clone https://github.com/ks0dcongra/Restaurant_List.git
```

2.初始

```
cd Restaurant_List //切至專案資料夾
```

3.安操nvm
```
到這裡 https://github.com/coreybutler/nvm-windows/releases 安裝nvm，選擇最新版本的nvm-setup.zip 檔案，請注意路徑中不能有空白或中文。
npm install  //安裝套件
```
4.CMD查看是否安裝成功
```
$ nvm version
```
5.查看目前有再更新的版本
```
$ nvm list available
```

6.下載node.js 14.16.0 版
```
$ nvm use 14.16.0
```

7.使用node.js 14.16.0 版
```
$ nvm use 14.16.0
```

8.檢查node.js版本
```
$ node -v
```

9.進入專案資料夾
```
$ cd restaurant_list
```

10.開啟程式
```
npm run dev 
```

11.打開瀏覽器網址列輸入 http://localhost:3000/
終端顯示 `Express is running on http://localhost:3000` 即啟動完成，請至[http://localhost:3000](http://localhost:3000)開始使用程式


## 使用工具
- [Visual Studio Code](https://visualstudio.microsoft.com/zh-hant/) - 開發環境
- [Express](https://www.npmjs.com/package/express) - 應用程式架構
- [Express-Fileupload](https://www.npmjs.com/package/express-fileupload) - 上傳圖片並放置指定目錄
- [Express-Handlebars](https://www.npmjs.com/package/express-handlebars) - 模板引擎

## Acknowledgments
* AlphaCamp