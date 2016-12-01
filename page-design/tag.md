# 元素

* element
* tag

## HTML5 新增的

* meter
* video

### `ruby, rt`

在文字旁邊表示注音

<ruby>
漢 <rt> ㄏㄢˋ </rt>
</ruby>

```html
<ruby>
漢 <rt> ㄏㄢˋ </rt>
</ruby>
```

http://www.w3schools.com/tags/tag_ruby.asp

## HTML4 就有的

### `pre`

```html
<pre>
    <code>多行程式碼</code>
</pre>
```

### `html`

宣告 HTML 文件使用的語言

`<html lang="en">`

http://www.w3schools.com/TAgs/tag_html.asp

### `legend`

* [demo](http://www.w3schools.com/TAGs/tryit.asp?filename=tryhtml_fieldset)

```html
<form>
  <fieldset>
    <legend>Personalia:</legend>
    Name: <input type="text" size="30"><br>
    Email: <input type="text" size="30"><br>
    Date of birth: <input type="text" size="10">
  </fieldset>
</form>
```

http://www.w3schools.com/jsref/dom_obj_legend.asp

### img

**`title`**

* `使用滑鼠移到圖片上時，會顯示說明。`
* [demo](http://www.w3schools.com/tags/tryit.asp?filename=tryhtml_image_test)

*題庫解析*：2-45

**alt**

* 圖片無法讀取時的替代文字

*題庫解析*：2-33

**usemap**

與 `<map>` 配合，設定圖片上不同的超連結區域。

```html
<img src="planets.gif" width="145" height="126" alt="Planets" usemap="#planetmap">

<map name="planetmap">
  <area shape="rect" coords="0,0,82,126" href="sun.htm" alt="Sun">
  <area shape="circle" coords="90,58,3" href="mercur.htm" alt="Mercury">
  <area shape="circle" coords="124,58,8" href="venus.htm" alt="Venus">
</map>
```

*題庫解析*：2-29

http://www.w3schools.com/TAgs/att_img_usemap.asp

### a

* 超連結
* `media: 定義超連結對象是要針對哪一種類型的設備使用`

```html
<a href="att_a_media.asp?output=print" media="print and (resolution:300dpi)">
    Open media attribute page for print.
</a>
```

http://www.w3schools.com/tags/att_media.asp

### wbr

*題庫解析*：2-03

* 當顯示的寬度不夠時，可以讓一個較長的英文字自行斷行。
* Word Break Opportunity
* http://www.w3schools.com/tags/tag_wbr.asp

### del

表示需刪除的文章內容

*題庫解析*：2-09

http://www.w3schools.com/TAgs/tag_del.asp

### cite

描述書的書名

```html
<p>
    <cite>The Scream</cite> by Edward Munch. Painted in 1893.
</p>
```

*題庫解析*：2-10

### dfn

*題庫解析*：2-10

### abbr

* 縮寫

### ins

* 插入資訊

```html
<p>My favorite color is <del>blue</del> <ins>red</ins>!</p>
Try it Yourself »
```

### small

* 適合用來表示版權聲明、法律限制以及註解等時使用

### s

* 用來表示不再正確或不再有關係的內容

### q

* 適合用來表示引用別人說過的話

### bdi

* 可以用來改變一段文字的書寫方向，讓其與原來的文字書寫方向不同。

### abbr

* 縮寫

### title

* 可以表示 `<abbr>` 縮寫的全名
* 如果有多個 `<title>`，只會選是第一個出現的。
* 應該要放在 `<head>` 裡面，但即使沒放在裡面也可以正常顯示。

### sup, sub

* 上標字
* 下標字

*題庫解析*：2-24, 2-37

### blockquote

* 引用了別人文章裡面的一段內容


### bdo

* `改變文字的顯示方向`

*題庫解析*：2-32

### frameset, noframe, frame, iframe

*題庫解析*：2-35

### media

*題庫解析*：2-39

### address

* 適合用來表示網頁或文章作者的聯絡資訊

*題庫解析*：2-43

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

### progress

http://www.w3schools.com/tags/tag_progress.asp

### meter

http://www.w3schools.com/jsref/dom_obj_meter.asp

### select-option

### keygen

http://www.w3schools.com/jsref/dom_obj_keygen.asp


### display special types of text

```
<b> - Bold text
<strong> - Important text
<i> - Italic text
<em> - Emphasized text
<mark> - Marked text
<small> - Small text
<del> - Deleted text
<ins> - Inserted text
<sub> - Subscript text
<sup> - Superscript text
```
