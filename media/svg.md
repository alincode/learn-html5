# SVG

* Scalable Vector Graph
* 以 XML 為基礎之語言來描述
* 2D image 處理
* 支援向量圖
* 可用來設計動畫

*題庫解析*：1-23, 4-28, 4-35

**好處**

* 可以延伸 (Stretch) 圖像 (Image)
* 圖像縮放不失真
* 可以壓縮
* 可以透過編輯 XML 來改變 image
* 搜尋引擎可以讀取與解析 SVG image
* 支持多種濾鏡和特殊效果
* 可以方便地建立文字檢索

**壞處**

* 在繪製複雜圖形時，rendering 速度緩慢

**特性**


**學習資源**

* [HTML 5 Tutorials #18 - Using SVG](https://www.youtube.com/watch?v=vvuH6qS2M5Q)
* [SVG grid example](http://codepen.io/ianchen0419/details/jVWzeW)

### 範例

```html
<canvas id="myCanvas">
    Your browser does support the canvas element.
</canvas>
```

```js
var c = document.getElementById("myCanvas");
var ctx = c.getContext("2d");
ctx.moveTo(10, 10);
ctx.lineTo(50, 50);
ctx.stroke();
```
