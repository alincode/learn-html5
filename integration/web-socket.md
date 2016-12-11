# Web Socket

* 雙向資料傳輸

**建立 WebSocket 物件**

* ws：不安全通訊協定
* wss：安全通訊協定

```
socket = new WebSocket("wss://localhost:12345");

// or

socket = new WebSocket("ws://localhost:12345");
```

**傳送訊息到伺服器端**

* send()


### 屬性

**readyState**

* closing
* open
* connecting

### event 事件

**onopen**

物件建立成功

**onmessage**

物件建立成功後，接收資料。
