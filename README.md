# Term-Project-1: PIXNET癖客幫

Data來自2016年pixne舉辦的hackathon(https://github.com/pixnet/2016-pixnet-hackathon-recommendation) 由於檔案有點大，所以就沒有重新上傳到這裡。而在裡我們僅選用瀏覽紀錄，並沒有使用全文資料集。

瀏覽紀錄中一共有24個檔案，而檔案格式為.json，讀取後所轉成的DataFrame資訊如下圖(單一檔案)。

url：當前文章的網址url

country：瀏覽者目前所在的國家(如：tw、cn)

city：瀏覽者目前所在區域

resolution：瀏覽者目前所使用的螢幕大小

browser：瀏覽者目前所使用的瀏覽器類型

browser_version：瀏覽者目前所使用的瀏覽器版本

os：瀏覽者的os類型

os_version：瀏覽者的os版本

device_marketing：瀏覽者目前所使用的裝置市場名稱

device_brand：瀏覽者裝置品牌名稱

cookie_pta：瀏覽者cookie

date：瀏覽日期(格式:yyyymmdd)

timestamp：瀏覽時間timestamp

hour：瀏覽時的時間(小時)

author_id：文章作者帳號

category_id：文章分類id

# Data Processing
利用
# Analyze
由於資料量相當龐大，，以及在採樣了五個檔案後也得到相近的結果，這裡僅針對24個檔案中的兩個檔案做分析，以利分析進行
# Result 
# Discussion
