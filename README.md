# JYu's Backend Learning Path

- 這是我自己學習後端的路程，和使用到的一些資源。

- 語言/框架以 PHP/Laravel 為主，如果你是學其他語言的，自己代換即可。差異不大。

- 在某些檔案中，我會註明最好先學什麼，再繼續進行下去。但也沒有絕對的先後順序，端看個人學習狀態。

- 每個 Section 後面我會標完全零經驗者大概要花多久完成該 Section。

- 我提供的資源（網站/課程/影片/書籍），不一定適用於所有人。建議大家從我提供的資源中，找出一些關鍵字，去搜尋對自己最有幫助的資源。

- 完成到 Sec. 5 去找工作「可能」會比較穩，但還是依公司型態和個人背景而定，沒有絕對。

---
## Sec. 0 在開始之前 (Est. 1 Week)
### 😄 環境設置：
 - OS: Linux or MacOS，不建議 Windows。你也可以開一台 Host，直接從純 CLI 介面開始。
 - Database: MySQL or Mariadb or PostgreSQL
- Webserver: Nginx(推) or Apache
- Language: PHP or others
### 😀 工具安裝（自己選擇要裝什麼）
- texteditor: vscode or vim or phpstorm
- Git GUI: sourcetree 
- Database GUI: tableplus, datagrip


---
## Sec. 1 (Est. 2.5~3.5 Month)
> 初學者安裝完以上的東西應該已經心力交瘁，甚至重灌好幾次，但接下來才是挑戰的開始...
> 以下四個基本上是後端工程師的必備技能

### 🤨 [PHP Learning Path](https://github.com/JYu1999/BackendLearningPath/blob/master/PHP%20Learning%20Path.md)
用來寫後端的語言，沒什麼好說的

### 😗 [Git Learning Path](https://github.com/JYu1999/BackendLearningPath/blob/master/Git%20Learning%20Path.md)
用來版本控制，每個工程師都該會

### 😶 HTML & CSS Learning Path
後端基本上還是要會「看得懂」前端
網路上相關資源非常多，這裡就不列出資源。
要特別注意的是，後端不用特別在意切版，只要對 HTML tag, attribute, flexbox, grid 等稍微有概念即可。

### 😯 (Basic) [Database Learning Path](https://github.com/JYu1999/BackendLearningPath/blob/master/Database%20Learning%20Path.md)
跟資料庫互動也是一定要會的，不過這裡只單純指 sql 語法，還不用去優化效率和容量。

### 😲 Stop to Practice!
看完以上幾個，可以先作一個小作品出來。像是留言板、TodoList 之類的
並嘗試在此作品中用到以下概念：
- Session/Cookie
- MVC
- CRUD
- OOP
- SQL/HTML Injection
- Validation
- 約定式提交

---
## Sec. 2 (Est. 2~2.5 Month)
> 完成以上的路程，對後端也有一定的認識了。
> 接著我們進到稍微複雜一點的地帶...

### 🫤 Javascript Learning Path
主要集中在 DOM 的部分，這裡大概知道 DOM 會怎麼跟 HTML  做互動即可。沒空的話，詳細的 JS 概念（e.g. hoisting, callstack)可以不用了解。
有空的話當然就去把 JS  概念補一補～

### 😵‍💫 [Laravel Learning Path](https://github.com/JYu1999/BackendLearningPath/blob/master/Laravel%20Learning%20Path.md)
PHP 的框架，藉由 Convention 讓工程師的溝通協作更順暢，也不用擔心架構。

---
## Sec. 3 (Est. 2~3 Month)
> 學完 Sec. 2，對於本地端開發應該已經熟悉了。
> 不過後端要會怎麼把網站 Deploy 到 Server 上。

### 😨 [Linux Learning Path](https://github.com/JYu1999/BackendLearningPath/blob/master/Linux%20Learning%20Path.md)
學完 Laravel  應該就具備基礎網頁製作的能力，接下來就是要把網頁上 Server。不過在上 Server 之前最好徹底熟悉一下 Linux，否則會不斷搞砸、不斷重啟、然後還不知道問題在哪...
而且 Linux 也跟系統安全性息息相關，千萬不要隨意略過。

### 🥺 [Deploy Learning Path](https://github.com/JYu1999/BackendLearningPath/blob/master/Deploy%20Learning%20Path.md)
再來要先知道如何把辛苦做的網站部署到 Host 上，並熟悉其原理。當然可以只看著教學一步步做，不管背後發生了什麼。但缺點就是發生了問題，也很難 debug...

### 😥 (Basic) [API Learning Path](https://github.com/JYu1999/BackendLearningPath/blob/master/API%20Learning%20Path.md)
基礎的 API 以 RESTful 為主，且先不用管安全性、認證之類的東西。

---
以下僅為草稿，期待後續我繼續往下走的時候更新。

---


## Sec. 4

### Docker Learning Path
Docker 是一個可以幫助個人和團隊省下不少時間的工具，簡單來說就是將 application 和其所有的相依元件打包。
不僅很多公司會要求應徵者有使用 docker 的經驗，在 [Stack Overflow 2022 的問卷調查](https://survey.stackoverflow.co/2022/#technology-worked-with-vs-want-to-work-with)中，docker 和 npm 可以說是在 other tool 類別裡面稱霸了。


### Testing Learning Path

### CI/CD Learning Path

## Sec. 5 進階
> 上面的路程基本上都是以「會使用」工具為主，到這邊開始會需要深入去探討安全性、效能相關的問題

### Algorithm Learning Path

### (Advanced) [Database Learning Path](https://github.com/JYu1999/BackendLearningPath/blob/master/Database%20Learning%20Path.md)

### (Advanced) [API Learning Path](https://github.com/JYu1999/BackendLearningPath/blob/master/API%20Learning%20Path.md)





