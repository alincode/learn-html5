# Server-Sent Events

* 單向資料傳輸
* IE 不支援
* 接受伺服器端回傳的資料 EventSource

**Cross-documents Messageing**

* 讓兩個不同網域的網頁，能夠互相傳遞及接收資料。

**單向的從伺服器端發送訊息到瀏覽器**

* Server-Sent Event
* MIME type: text/event-stream

**傳送資料的格式**

* uft-8
* 發送的資料使用 `data:` 為開頭
* 要傳送多筆資料時，資料與資料之間要空一行


### 延伸閱讀
* [HTML5 的 Server-Sent Events 串流使用教學 - GTW](https://blog.gtwang.org/web-development/stream-updates-with-server-sent-events/)
* [Server-Sent Events - w3school](http://www.w3schools.com/html/html5_serversentevents.asp)

