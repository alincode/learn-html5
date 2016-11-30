# Geolocation

* 精準度會因為你的裝置而有所不同
* 可以取得個人所在位置的資料
* 可以透過 IP 來計算你的所在位置
* 成功取得使用者的地理位置後，會回傳 Position 物件

**判斷是否支援**

```
navigator.geolocation // 因為 window 是全域變數，可以被省略
window.navigator.geolocation
```

**watch**

* 可用 watchPosition() 來持續追蹤使用者的地理位置
* 可用 clearWatch() 來停止追蹤使用者的位置


**Position 物件的屬性**

<table>
<tbody>
<tr>
    <th style="width:150px">Property</th>
    <th>Returns</th>
</tr>
<tr>
    <td>coords</td>
    <td> Coordinates 座標物件, 存放傳回之位置資訊</td>
</tr>
<tr>
    <td>timestamp</td>
    <td>取得位置資訊之時間 (毫秒)</td>
</tr>
</tbody></table>

**Coordinates 物件的屬性**

<table>
<tbody><tr>
<th style="width:150px">Property</th>
<th>Returns</th>
</tr>
  <tr>
<td>latitude</td>
<td>經度</td>
  </tr>
  <tr>
<td>longitude</td>
<td>緯度</td>
  </tr>
  <tr>
<td>accuracy</td>
<td>物置誤差</td>
  </tr>
  <tr>
<td>altitude</td>
<td>高度</td>
  </tr>
  <tr>
<td>altitudeAccuracy</td>
<td>高度誤差</td>
  </tr>
  <tr>
<td>heading</td>
<td>移動方向</td>
  </tr>
  <tr>
<td>speed</td>
<td>移動速度</td>
  </tr>
</tbody></table>

**Handling Errors**

*題庫解析**：7-03

```js
function showError(error) {
    switch(error.code) {
        case error.PERMISSION_DENIED: // 0
            x.innerHTML = "User denied the request for Geolocation."
            break;
        case error.POSITION_UNAVAILABLE: // 1
            x.innerHTML = "Location information is unavailable."
            break;
        case error.TIMEOUT: // 2
            x.innerHTML = "The request to get user location timed out."
            break;
        case error.UNKNOWN_ERROR: // 3
            x.innerHTML = "An unknown error occurred."
            break;
    }
}
```

**延伸閱讀**
* [Geolocation API Specification 2nd Edition - W3C](https://www.w3.org/TR/geolocation-API/)
* [html5 geolocation](http://www.w3schools.com/html/html5_geolocation.asp)
* [W3C Geolocation API Specification](https://dev.w3.org/geo/api/spec-source.html)
* [小狐狸事務所 - HTML5 Geolocation API (地理位置) 測試](http://yhhuang1966.blogspot.tw/2013/10/html5-geolocation-api.html)
