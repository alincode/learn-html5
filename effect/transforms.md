# transforms

**名詞**

* angle 角度
* rotate 旋轉
* matrix 矩陣

### 2D

* matrix
* translate
* scale
* rotate
* skew

**Transform 屬性**

* transform
* transform-origin

**Transform Methods**

* matrix(n,n,n,n,n,n): using a matrix of six values
* `translate(x,y)`
* translateX(n)
* translateY(n)
* scale(x,y)
* scaleX(n)
* scaleY(n)
* `rotate(angle)`
* skew(x-angle,y-angle)
* skewX(angle)
* skewY(angle)

**範例**

```css
div {
    transform: rotateX(-70deg);
}
```

## 3D

### `rotate` 旋轉

* rotateX
* rotateY
* rotateZ
* rotate3d(x,y,z,angle)

```css
transform: rotate3d(1, 0, 0, 60deg);
```

### `matrix3d` 矩陣

* * matrix `自由度最高`

matrix3d(n,n,n,n,n,n,n,n,n,n,n,n,n,n,n,n)

Defines a 3D transformation, using a 4x4 matrix of `16 values`

### 延伸閱讀

* [CSS3 3D Transforms - w3school ](http://www.w3schools.com/css/css3_3dtransforms.asp)
* [CSS 3D 旋轉 rotate3d 與 translate3d - puritys.me](https://www.puritys.me/docs-blog/article-353-CSS-3D-%E6%97%8B%E8%BD%89-rotate3d-%E8%88%87-translate3d.html)
* [CSS transform 能旋轉、傾斜、縮放變形 box - 網頁藝術思考](http://boohover.pixnet.net/blog/post/35341387-%E6%97%8B%E8%BD%89%E3%80%81%E5%82%BE%E6%96%9C%E3%80%81%E7%B8%AE%E6%94%BE%E7%9A%84%E8%AE%8A%E5%BD%A2%E6%95%88%E6%9E%9C-transform-(css-prope)
* [CSS3 Animation Transform Rotate - Village Park Source](https://youtu.be/fLgmlWEybuM?t=2m26s) (video)
* [CSS3 3D Transforms - SnoOpy - Interactive Development ](https://www.youtube.com/watch?v=yOsk3_sc0bc) (video)

### 3D Transforms 瀏覽器支援度

-webkit-, -moz-, or -o- specify the first version that worked with a prefix.

**範例**

```cs
div {
    -ms-transform: rotate(20deg); /* IE 9 */
    -webkit-transform: rotate(20deg); /* Safari */
    transform: rotate(20deg);
}
```

<table>
  <tbody><tr>
 <th style="width:25%;font-size:16px;text-align:left;">Property</th>
    <th style="width:15%;">Chrome</th>
    <th style="width:15%;">Internet Explorer / Edge</th>
    <th style="width:15%;">Firefox</th>
    <th style="width:15%;">Safari</th>
    <th style="width:15%;">Opera</th>
  </tr>
  <tr>
    <td style="text-align:left;">transform</td>
    <td>36.0<br>12.0&nbsp;-webkit-</td>
    <td>10.0</td>
    <td>16.0<br>10.0&nbsp;-moz-</td>
    <td>9.0<br>4.0&nbsp;-webkit-</td>
    <td>23.0<br>15.0&nbsp;-webkit-</td>
  </tr>
    <tr>
    <td style="text-align:left;">transform-origin<br>(three-value syntax)</td>
    <td>36.0<br>12.0&nbsp;-webkit-</td>
    <td>10.0</td>
    <td>16.0<br>10.0&nbsp;-moz-</td>
    <td>9.0<br>4.0&nbsp;-webkit-</td>
    <td>23.0<br>15.0&nbsp;-webkit-</td>
    </tr>
    <tr>
    <td style="text-align:left;">`transform-style`</td>
    <td>36.0<br>12.0&nbsp;-webkit-</td>
    <td>`11.0`</td>
    <td>16.0<br>10.0&nbsp;-moz-</td>
    <td>9.0<br>4.0&nbsp;-webkit-</td>
    <td>23.0<br>15.0&nbsp;-webkit-</td>
    </tr>
    <tr>
    <td style="text-align:left;">perspective</td>
    <td>36.0<br>12.0&nbsp;-webkit-</td>
    <td>10.0</td>
    <td>16.0<br>10.0&nbsp;-moz-</td>
    <td>9.0<br>4.0&nbsp;-webkit-</td>
    <td>23.0<br>15.0&nbsp;-webkit-</td>
    </tr>
    <tr>
    <td style="text-align:left;">perspective-origin</td>
    <td>36.0<br>12.0&nbsp;-webkit-</td>
    <td>10.0</td>
    <td>16.0<br>10.0&nbsp;-moz-</td>
    <td>9.0<br>4.0&nbsp;-webkit-</td>
    <td>23.0<br>15.0&nbsp;-webkit-</td>
    </tr>
    <tr>
    <td style="text-align:left;">backface-visibility</td>
    <td>36.0<br>12.0&nbsp;-webkit-</td>
    <td>10.0</td>
    <td>16.0<br>10.0&nbsp;-moz-</td>
    <td>9.0<br>4.0&nbsp;-webkit-</td>
    <td>23.0<br>15.0&nbsp;-webkit-</td>
    </tr>
</tbody></table>
