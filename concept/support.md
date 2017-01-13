# 相容性

* 是一份規格書，讓大家朝往同個方向前進。
* Chrome 跟 Firefox 支援度最高，IE 跟 Safari 支援度最低
* IE9以後的版本，對HTML5的支援度才有提升
* 所有瀏覽器，都支援 HTML5 的~~所有~~`部分`功能


### `<input type="tel">`

* 只有 Safari 8 支援

### HTML5Shiv

* 解決相容IE8的問題
* The HTML5Shiv is a JavaScript workaround to enable styling of HTML5 elements in versions of Internet Explorer prior to version 9.

```html
<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<!--[if lt IE 9]>
  <script src="https://oss.maxcdn.com/libs/html5shiv/3.7.0/html5shiv.js"></script>
<![endif]-->
</head>
```

### 當input元素無法被正確解讀時

*  當成普通的 `<input type="text">`
*  不檢查資料格式

**延伸閱讀**

* [Can I Use?](http://caniuse.com/)
* [支援度測試](http://html5test.com/)
