# input

**檢查資料格式**

* url
* `email`
    * [email invalid](http://codepen.io/alincode/pen/LbOJYO)
    * [email invalid and disabled](http://codepen.io/alincode/pen/gLXdaZ)

**不檢查資料格式**

* tel
* (略...)

## HTML5新增的

* `color`
* date
* datetime
* datetime-local
* `email`
* month
* number
* `range`
* search
* tel (The tel type is currently supported only in Safari 8.)
* time
* url(not supported in IE9 and earlier versions.)
* week

## HTML4 就有的

* file

`<input type="file" name="upfile[]"/>`

* text

## 屬性

**autocomplete**

**form**

* IE 不支援

```html
<form action="demo_form.asp" method="get" id="form1">
  First name: <input type="text" name="fname"><br>
  Last name: <input type="text" name="lname"><br>
</form>

<button type="submit" form="form1" value="Submit">Submit</button>
```

http://www.w3schools.com/tags/att_button_form.asp
