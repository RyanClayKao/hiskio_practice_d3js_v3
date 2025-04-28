# 老師提供的資源
## 1. 取得地理資料檔 SHP
* 世界地圖下載網址
  * https://www.naturalearthdata.com/
* 台灣縣市界線地圖下載
  * https://data.gov.tw/dataset/7442


## 2. 資料格式轉換 SHP => JSON (Geo json或 topo json)
* 將資料格式轉換、縮減檔案大小的網站
  * https://mapshaper.org/
* 轉檔步驟
  * 把拿到的 SHP資料夾中的 .shp、.dbf，丟到網站裡面
  * 點「simplify」，選擇要縮放的尺寸百分比
  * 點「Export」，選擇要輸出的 json格式，看是要 geo json或是 topo json

### geo json 與 topo json的差異
* geo json是比較通用的，但缺點是容量較大，因為每個地圖區域的界線都會畫。
* topo json是 d3.js作者自己弄出來的格式，容量會比 geo json小，因為它畫區域界線的時候，會共用界線，所以容量也就比較小了。

