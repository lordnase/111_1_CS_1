# **111_1_CS_1_德文三 09123010 陳昕龍_實習作業五**

## **Linux 背景知識 - 什麼是 Linux？**  
● Linux 是一種自由開放原始碼的類 Unix 作業系統  
● 廣泛運用於伺服器和嵌入式系統中  
● 具有可移植性的 Open Source 的作業系統，它的程式碼可以被修改適合在各種機
器上運行  
● 目前主流的 Linux 發佈版本包括：Debian、Fedora、CentOS、Ubuntu 等  
     
           
## **Linux 背景知識 - 使用者與群組**  
➔ 關於身份：  
◆ 身份分類：  
● user (owner)  
● group  
● others  
◆ 群組 (group) 的主要用意：  
● 將帳號歸類，有助於專案開發  
● 使用者可加入多個群組  
➔ 關於身份類別：  
◆ 系統管理員： root  
◆ 一般帳號：  
● 系統帳號 （用於操作系統工作的帳號 e.g. 關閉電腦 etc.）  
● 一般使用者帳號 （用於一般使用者登入用）    
  
>## **Linux 指令 - 壓縮檔案**  
>>ip  
>>>◆ 壓縮：gzip FileName  
>>>◆ 解壓縮：  
>>>● gunzip FileName.gz  
>>>● gzip -d FileName.gz  
>>>➔ xz  
>>>◆ 壓縮：xz -z FileName  
>>>◆ 解壓縮：xz -d FileName.xz  
  
## **Linux 背景知識 - 資料傳輸**  
溝通案例：開瀏覽器(客戶端)並輸入Youtube首頁網址(伺服器端)  
1. 瀏覽器(客戶端)向YouTube的遠端主機(伺服器端)發出一個請求  
2. 該請求透過網路被傳遞到YouTube的遠端主機(伺服器端)  
3. 位於YouTube首頁的遠端主機(伺服器端)收到一個請求  
4. 遠端主機(伺服器端)會根據請求內容，找到對應的資料  
5. 取出對應資的資料，伺服器將其回傳至瀏覽器  
6. 瀏覽器(客戶端)收到回傳內容，開始解析資源，顯示於瀏覽器上  
  
>## **正則表達式 Regular Expression**  
正則表達式是透過一些特殊符號來比對字串的方法，並可對符合比對  
條件的字串進行搜尋、截取、替代、轉換等等  
>>練習網站: https://regex101.com/  
  

## **awk 文字分析工具**  
```
● 常用在對文字和資料進行分析處理  
● 檔案逐行的讀入  
  
awk Script    
工作原理:  
○ 第一步執行BEGIN 語句  
○ 第二步從檔案或標準輸入讀取一行，然後再執行pattern語句，逐行  
掃描檔案到檔案全部被讀取  
○ 第三步執行END語句  
awk ‘BEGIN{ print “start” } pattern{ commands } END{ print “end” }’ filename  
```
