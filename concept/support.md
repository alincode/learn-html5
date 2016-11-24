# 相容性

* 是一份規格書，讓大家朝往同個方向前進。
* Chrome 跟 Firefox 支援度最高
* IE 跟 Safari 支援度最低
* IE9以後的版本，對HTML5的支援度才有提升
* 所有瀏覽器，都支援 HTML5 的~~所有~~`部分`功能

```
<input type="tel" name="usrtel">
```
The tel type is currently supported only in Safari 8.

*解析題庫*：1-05, 1-49

### HTML5Shiv

解決相容IE8的問題

The HTML5Shiv is a JavaScript workaround to enable styling of HTML5 elements in versions of Internet Explorer prior to version 9.

```
<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<!--[if lt IE 9]>
  <script src="https://oss.maxcdn.com/libs/html5shiv/3.7.0/html5shiv.js"></script>
<![endif]-->
</head>
```


### 哪些元素在HTML5被刪掉了？
