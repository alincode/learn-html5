# 元素

* element
* tag

### hidden

*題庫解析*：2-02

* 隱藏元素的屬性

```html
<p hidden>This paragraph should be hidden.</p>
```

### wbr

*題庫解析*：2-03

* 當顯示的寬度不夠時，可以讓一個較長的英文字自行斷行。
* Word Break Opportunity
http://www.w3schools.com/TAgs/tag_wbr.asp

*題庫解析*：2-03

http://www.w3schools.com/tags/tag_wbr.asp

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

*題庫解析*：2-10

### pre

*題庫解析*：2-12

```html
<pre>
    <code>多行程式碼</code>
</pre>
```

### ins

* 插入資訊

```html
<p>My favorite color is <del>blue</del> <ins>red</ins>!</p>
Try it Yourself »
```

### ruby, rt

在文字旁邊表示注音

```html
<ruby>
漢 <rt> ㄏㄢˋ </rt>
</ruby>
```

http://www.w3schools.com/tags/tag_ruby.asp

### rp


### area


### html

`<html lang>`

http://www.w3schools.com/TAgs/tag_html.asp

*題庫解析*：2-17

### small

* 適合用來表示版權聲明、法律限制以及註解等時使用

*題庫解析*：2-18

### s

* 用來表示不再正確或不再有關係的內容

*題庫解析*：2-19

### q

* 適合用來表示引用別人說過的話

*題庫解析*：2-20

### bdi

* 可以用來改變一段文字的書寫方向，讓其與原來的文字書寫方向不同。

*題庫解析*：2-21

### abbr

* 縮寫

*題庫解析*：2-22

### title

* 可以表示 `<abbr>` 縮寫的全名
* 如果有多個 `<title>`，只會選是第一個出現的。
* 應該要放在 `<head>` 裡面，但即使沒放在裡面也可以正常顯示。

*題庫解析*：1-37, 2-23

### sup, sub

* 上標字
* 下標字

*題庫解析*：2-24, 2-37

### img

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

**title**

* 使用滑鼠移到圖片上時，會顯示說明。

*題庫解析*：2-45

**alt**

* 圖片無法讀取時的替代文字

*題庫解析*：2-33

### mark

* 文字中要突顯的部分

*題庫解析*：2-30

### blockquote

* 引用了別人文章裡面的一段內容

*題庫解析*：2-31

### bdo

* 改變文字的顯示方向

*題庫解析*：2-32

### frameset, noframe, frame, iframe

*題庫解析*：2-35

### media

*題庫解析*：2-39

### address

* 適合用來表示網頁或文章作者的聯絡資訊

*題庫解析*：2-43

### command

**定義**

* 方便使用者使用之按鈕
* The type attribute specifies the type of command.
* Internet Explorer 9 (not earlier or later versions), supports the type attribute. However it only supports the "command" type.

http://www.w3schools.com/tags/att_command_type.asp

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

*題庫解析*：2-18


