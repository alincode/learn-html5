# 基本應用

## 離線功能

HTML5 透過 JavaScript 提供了數種不同的離線儲存功能，相對於傳統的 Cookie 而言有更好的彈性以及架構，並且可以儲存更多的內容。

* WebStorage -- 比 Cookies 更大、更有彈性的的儲存
* Web SQL Database -- 本地端的 SQL 資料庫
* Indexed DB -- Key-value 的本地端資料庫
* Application Cache -- 將部分常用的網頁內容 cache 起來

## 即時通訊

以往網站由於 HTTP 協定以及瀏覽器的設計，即時的互動性相當的受限，只能使用一些技巧來「模擬」即時的通訊效果，但 HTML5 提供了完善的即時通訊支援。

* WebSocket -- 即時的 socket 連線
* Web Workers -- 以往 JavaScript 都是 single thread，透過 Worker 可以有多個運算
* Notifications -- 原生的提示訊息，類似像 OS X 的 Growl 提示

**延伸閱讀**

* [demo](https://davidwalsh.name/demo/notifications-api.php)
* [Notification API](https://developer.mozilla.org/en-US/docs/Web/API/notification)
* [w3 notifications](https://www.w3.org/TR/notifications/)


```
Notification.requestPermission()
```

```
Notification.permission
```

## 檔案以及硬體支援

不知道大家有沒有發現，在 Gmail 等新的網頁程式當中，已經可以透過拖拉的方式將檔案作為郵件附件？這就是這部份 HTML5 檔案的功能中的 Drag'n Drop 和 File API。

* Drag'n Drop -- HTML 元素的拖拉
* File API -- 讀取使用者本機電腦的內容
* Geolocation -- 地理定位
* Device orientation -- 手持裝置的方向
* Speech input -- 語音輸入

## 語意化

語意化的網路是可以讓電腦能夠更加理解網頁的內容，對於像是搜尋引擎的優化（SEO）或是推薦系統可以有很大的幫助。

* New tags -- 新的標籤，像是<header>、<section> 等
* Application tags -- 也是新的標籤，像是<meter>、<progress> 等
* Microdata -- 加入語意的資料讓搜尋引擎等網站可以正確顯示
* Form type -- <form> 可以加入的 type 便多了，包含 email 和 tel 等屬性，瀏覽器會協助進行資料格式的驗證

## 多媒體

Audio、Video 的標籤支援以及 Canvas 的功能應該是大家對於 HTML5 最熟悉的部份了，也是許多人認為 Flash 會被取代的主要原因。

* Audio video -- 影片和音樂的原生播放支援
* Canvas -- 2D 的繪圖功能支援
* Canvas 3D -- 3D 的繪圖功能支援
* SVG -- 向量圖支援

## CSS 3

CSS3 支援了字體的嵌入、版面的排版，以及最令人印象深刻的動畫功能。

* Selector -- 更有彈性的選擇器
* Webfonts -- 嵌入式字體
* Layout -- 多樣化的排版選擇
* Stlying radius gradient shadow -- 圓角、漸層、陰影
* Border background -- 邊框的背景支援
* Transition -- 元件的移動效果
* Transform -- 元件的變形效果
* Animation -- 將移動和變形加入動畫支援

## JavaScript

在比較 JavaScript 的基本面也新增了 DOM 的 API、和瀏覽器上下頁的紀錄修改。

* DOM API -- 更方便的查詢 DOM 元件
* History API -- 瀏覽器的上下頁內容修改，方便 AJAX 可以保留瀏覽記錄
