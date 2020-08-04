餐廳清單網站
使用node.js、express和express-handlebars、body-parser、mongoDB與mongoose所做的網站

環境建置與需求
node.js v10.15.0 -執行環境
express v4.17.1 -框架
express-handlebars v4.0.4 -模板引擎
body-parser v1.19.0 -中介軟體
mongoDB - 4.2.6 -資料庫管理系統
mongoose v 5.9.14 - 物件映射工具
安裝與使用
下載專案
git clone https://github.com/wanglala5131/Restaurant-list-refactor.git
安裝package
npm install
新增種子資料
npm run seed
使用nodemon啟動伺服器
npm run dev
或正常啟動
npm start
網站功能
可以瀏覽喜好餐廳的名字、類型與評分
點擊餐廳卡片，可瀏覽更詳細的資訊
根據關鍵字可搜尋餐廳名稱、類型
可新增新的餐廳資料
可編輯餐廳資料
可刪除餐廳資料
根據餐廳名稱、類型與評分可排列順序



# 我的餐廳清單

使用Node.js, Express, Express-handlebars, mongodb 套件製作而成

![Alt text](https://github.com/hsiyu1121/restaurant_list_CRUD/blob/master/restaurant-list-crud.png)

## 功能清單
* 點選"我的餐廳清單"即可重新整理
* 可以透過搜尋店家名稱，找到自己要的餐廳
* 使用者可以新增一家餐廳
* 使用者可以瀏覽一家餐廳的詳細資訊
* 使用者可以瀏覽全部所有餐廳
* 使用者可以修改一家餐廳的資訊
* 使用者可以刪除一家餐廳

## 環境需求
* Node.js: v10.15.0
* Express: v4.17.1
* Express-handlebars: v5.1.0
* Mongoose: v5.9.25

## 啟動方式
* 將專案下載至本機內

  ``git clone https://github.com/hsiyu1121/restaurant_list_CRUD.git``
* 切換至資料夾內

  ``cd restaurant_list_CRUD``
* 安裝相關的套件

  ``npm install``
* 建立資料庫

  ``npm run seed``
* 透過node執行程式
