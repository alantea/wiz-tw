# wiz-tw
《問答RPG 魔法使與黑貓維茲》活動題庫搜尋
本題庫改自 https://github.com/chrisliuqq/wiz-tw/

---

本次活動: 前進吧!!高捷少女!! 2015.12.24(四) 15:00 - 2016.01.20(三) 14:59

---

### 修改表格說明
1. 將Google Sheet發佈到網路 (不是開啟共用)
	* 檔案 -> 發佈到網路
2. 取得sheetID
	* 若Google sheet的網址為 https://docs.google.com/spreadsheets/d/blackcatiswiz，則sheetID為 blackcatiswiz
3. 取得gridID
	* 打開 https://spreadsheets.google.com/feeds/worksheets/{SHEET-ID}/public/basic?alt=json 會看到一堆資料
	* 將資料貼至http://jsonlint.com/後在 feed -> entry -> id -> $t
	* https://spreadsheets.google.com/feeds/worksheets/blackcatiswiz/public/basic/apple，則apple為gridID
4. 將sheetID, gridID在 wiz.js修改後即可使用
