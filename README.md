# 「好頂線上生鮮超市」開發模擬實作

### 開發情境

「好頂超市」是一間販售生鮮雜貨的超市。因為疫情大大改變人們的購物習慣，現在使用 App 購買生鮮雜貨的目標客群愈來愈多。為了搶攻線上購物市場，近期該公司想要開發一款**線上生鮮超市 App**。

在實際進入網頁工程開發之前，開發部門希望能在終端機上進行可行性實測。線上商城最基本的服務功能有：**「註冊」、「登入/登出」、「線上商品清單」、「加入購物車」、「結帳」**。

經過會議討論後，決定分成兩階段開發:
第一階段為**「開發商城後端 API」**。總共需開發 **10 個**系統函式，內容包含處理會員資料、比對與生成資料庫商品資訊等功能。

第二階段為**「開發商城功能運作邏輯」**。主要是利用開發好的後端 API，在終端機進行功能實現。

本次開發共有 5 位工程師一同參與，版本控制採用 **gitHub flow**。

主管已先建立共同開發的 github 存放庫，內含：測試用的**商品資料（product.json）**、**會員資料（user_data.json）**，以及**專案執行檔（project_005.py）**。

請先 fork 到自己的 gitHub 上，並建立新的分支後開始開發實作。
