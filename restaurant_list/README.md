# 餐廳清單 2.0

此專案提供使用者新增、刪除及修改餐廳的資訊，例如:餐廳類別、地址、評分、描述等

## 功能列表

1. 依照餐廳名稱及餐廳類別搜尋
  -  優化搜尋功能
    - 剔除多餘的空白
    - 搜尋沒有結果時也有對應頁面提示
2. 可從首頁點擊餐廳圖片了解餐廳詳細資訊

### 安裝

1.開啟終端機(Terminal)cd 到存放專案本機位置並執行:

```
git clone https://github.com/Eason0in/Restaurant-CRUD.git
```

2.初始

```
cd Restaurant-CRUD  //切至專案資料夾
```

```
npm install  //安裝套件
```

3.產生預設使用者及餐廳資料至 MongoDB

```
npm run insertSeeds  //執行增加資料至 MongoDB
```

終端顯示 `users insert done! 及 restaurants insert done!` 即完成新增資料

```
Ctrl+C *2  //連按兩下Ctrl+C結束批次工作
```

4.開啟程式

```
npm run start  //執行程式
```

終端顯示 `db is connected!` 即啟動完成，請至[http://localhost:3000](http://localhost:3000)開始使用程式

## Test Data

- Account
  - email_1：asd@asd
  - email_2：asd2@asd