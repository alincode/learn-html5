# Web Socket

* 雙向資料傳輸

**建立 WebSocket 物件**

```
socket = new WebSocket("was://localhost:12345");
// or
socket = new WebSocket("wa://localhost:12345/socket");
// or
socket = new WebSocket("wa://localhost:12345");
```

**傳送訊息到伺服器端**

* send()


### 屬性

**readyState**

* closing
* open
* connecting

### 事件

**onopen**

物件建立成功

**onmessage**

物件建立成功後，接收資料。
