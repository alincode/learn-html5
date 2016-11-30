# SVG

* 全名是 Scalable Vector Graph
* 以 XML 為基礎之語言來描述
* 2D image 處理
* 支援向量圖
* 可用來設計動畫
* IE9 支援

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

**延伸閱讀**

* [SVG intro - w3schools](http://www.w3schools.com/graphics/svg_intro.asp)
* [HTML 5 Tutorials #18 - Using SVG](https://www.youtube.com/watch?v=vvuH6qS2M5Q)
* [SVG grid example](http://codepen.io/ianchen0419/details/jVWzeW)

### 元素

**circle**

<svg height="100" width="100">
  <circle cx="50" cy="50" r="40" stroke="black" stroke-width="3" fill="red" />
</svg>

```html
<svg height="100" width="100">
  <circle cx="50" cy="50" r="40" stroke="black" stroke-width="3" fill="red" />
</svg>
```

**polygon**

<svg height="210" width="500">
  <polygon points="200,10 250,190 160,210" style="fill:lime;stroke:purple;stroke-width:1" />
</svg>

```html
<svg height="210" width="500">
  <polygon points="200,10 250,190 160,210" style="fill:lime;stroke:purple;stroke-width:1" />
</svg>
```

**polyline**

<svg height="200" width="500">
  <polyline points="20,20 40,25 60,40 80,120 120,140 200,180"
  style="fill:none;stroke:black;stroke-width:3" />
</svg>

```html
<svg height="200" width="500">
  <polyline points="20,20 40,25 60,40 80,120 120,140 200,180"
  style="fill:none;stroke:black;stroke-width:3" />
</svg>
```

**ellipse**

<svg height="140" width="500">
  <ellipse cx="200" cy="80" rx="100" ry="50"
  style="fill:yellow;stroke:purple;stroke-width:2" />
</svg>

```html
<svg height="140" width="500">
  <ellipse cx="200" cy="80" rx="100" ry="50"
  style="fill:yellow;stroke:purple;stroke-width:2" />
</svg>
```

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
