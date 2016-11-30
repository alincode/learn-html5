# 表單設計

* 觸發驗證的時機點，是在資料變動的時候

## HTML5新增的input類型

* color
* date
* datetime
* datetime-local
* email
* month
* number
* range
* search
* tel (The tel type is currently supported only in Safari 8.)
* time
* url(not supported in IE9 and earlier versions.)
* week

**檢查資料格式**

* url
* email

**不檢查資料格式**

* tel
* (略...)


## 複習其他 input 類型

* file

```
<input type="file" name="upfile[]"/>
```


## 元素

### output

http://www.w3schools.com/jsref/dom_obj_output.asp

### datalist

* [demo](http://www.w3schools.com/tags/tryit.asp?filename=tryhtml5_datalist)
* The <datalist> element is not supported in Internet Explorer 9 (and earlier versions), or Safari.
* [Datalist options Collection](http://www.w3schools.com/jsref/coll_datalist_options.asp)

### optgroup

http://www.w3schools.com/jsref/dom_obj_optgroup.asp

### fieldset

http://www.w3schools.com/jsref/dom_obj_fieldset.asp

### legend

http://www.w3schools.com/jsref/dom_obj_legend.asp

### progress

http://www.w3schools.com/tags/tag_progress.asp

### meter

http://www.w3schools.com/jsref/dom_obj_meter.asp

### select-option

### keygen

http://www.w3schools.com/jsref/dom_obj_keygen.asp

### legend

http://www.w3schools.com/jsref/dom_obj_legend.asp

### input sttr

**autocomplete**

### button

**type=submit**

* formaction
* formmethod

```html
<form action="demo_form.asp" method="get">
  First name: <input type="text" name="fname"><br>
  Last name: <input type="text" name="lname"><br>
  <button type="submit">Submit</button>
  <button type="submit" formmethod="post" formaction="demo_post.asp">Submit using POST</button>
</form>
```

http://www.w3schools.com/tags/att_button_formmethod.asp

**formtarget**

form-target

http://www.w3school.com.cn/tags/att_button_formtarget.asp

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


### form attr

**novalidate**

http://www.w3school.com.cn/tags/att_form_novalidate.asp

### custom elements

* [w3 custom elements](https://www.w3.org/TR/custom-elements/)

## 參考來源

* [w3schools html_form_input_types](http://www.w3schools.com/html/html_form_input_types.asp)
* [w3 html5](https://www.w3.org/TR/html5/forms.html)

