# Web Workers (執行緒應用)

* new Workers()
* new Shared Worker()
* 可以使用 navigator 物件
* 可以使用 XMLHttpRequest 物件
* 可以使用 WebSockets
* 此技術使得 Javascript 可以單獨被執行。

**在 Web Worker 中，從網頁呼叫 Share Worker 會觸發**

* onconnect


### 範例

```html
<!DOCTYPE html>
<html>
<body>

<p>Count numbers: <output id="result"></output></p>
<button onclick="startWorker()">Start Worker</button>
<button onclick="stopWorker()">Stop Worker</button>

<p><strong>Note:</strong> Internet Explorer 9 and earlier versions do not support Web Workers.</p>

</body>
</html>

```

```js
var w;

function startWorker() {
    if(typeof(Worker) !== "undefined") {
        if(typeof(w) == "undefined") {
            w = new Worker("demo_workers.js");
        }
        w.onmessage = function(event) {
            document.getElementById("result").innerHTML = event.data;
        };
    } else {
        document.getElementById("result").innerHTML = "Sorry, your browser does not support Web Workers...";
    }
}

function stopWorker() {
    w.terminate();  // 停止執行緒
    w = undefined;
}
```

** Web Worker File**

```js
// demo_workers.js
var i = 0;

function timedCount() {
    i = i + 1;
    postMessage(i); // 發送訊息
    setTimeout("timedCount()",500);
}

timedCount();
```

The important part of the code above is the postMessage() method - which is used to post a message back to the HTML page.

Note: Normally web workers are not used for such simple scripts, but for more CPU intensive tasks.


### 延伸閱讀

* [w3schools - html5 worker](http://www.w3schools.com/html/html5_webworkers.asp)
* [w3schools - example](http://www.w3schools.com/html/tryit.asp?filename=tryhtml5_webworker)
