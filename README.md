# china-bot
 藐視國會法執行者

## .env檔
* DCTOKEN = discord機器人的token
* OWNERID = 機器人擁有者的用戶id
* BOTID = 機器人的用戶id
* OWNERNAME = 擁有者姓名(影響藐視xxx罪)

## 可設定內容
* 禁字 line 21 bad_word -> list
> * 為虛偽陳述類
> * 例如: 原P
* 禁字 line 22 banned_word -> list
> * 為藐視xxx類
> * 例如:幹xx
* 允許字 line 23 good_word -> list
> * 用以防止非禁字因包含禁字而被審查
> * 例如:"不是"為bad_word，而"是不是"為good_word
* 回覆時間 line 32 reply_time -> int
> * 當擁有者@某人時，須於reply_time秒內回覆
* 藐視訊息暫存數量 line 34 bad_message_id_count -> int
> * 紀錄包含禁字或反質詢的訊息id
> * 用於偵測是否被刪除

## 特色
* ~~可以把自己的discord伺服器變成藍白黨國會~~
* 可以進行言論審查
* 要求其他人回覆
* ~~藐視現在的國會~~
* ~~讓伺服器內的人體驗社會主義的鐵拳~~

## 詳細功能
* 若有使用者說出了~~當權者~~擁有者不想聽的話，會被認定為藐視xxx、虛偽陳述
* 若被擁有者@的使用者會於時限內回覆、會被認定為拒絕答覆
* 若違反第一項的訊息被刪除，會被認定為隱匿資訊
* 若有使用者@擁有者或機器人，會被認定為反質詢
* 可透過指令查詢禁字與允許字
* 可透過指令暫停、啟動機器人的功能
* 非擁有者嘗試使用暫停、啟動指令時，會得到國昌老師的訕笑 (聲音檔來源:https://kuochang.tw/quote/yjV0Axd5wr, hahaha.mp3)
* 觸犯"藐視xxx罪"者，將被國昌老師的**太離譜了**制裁 (聲音檔來源:https://kuochang.tw/quote/Beyavja1r7, bruh.mp3)

# 由於~~國會改革的法條~~此機器人的功能過於~~擴權~~惱人，請謹慎使用