# 屬性

找一些真實網站的範例

### 易忽略的 HTML4全域屬性 (global attribute)

<table class="w3-table-all notranslate">
<tbody><tr>
<th style="width:25%">Attribute</th>
<th>Description</th>
</tr>
<tr>
<td><a href="http://www.w3schools.com/tags/att_global_accesskey.asp">accesskey</a></td>
<td>熱鍵</td>
</tr>
<tr>
<td><a href="http://www.w3schools.com/tags/att_global_dir.asp">dir</a></td>
<td>Specifies the text direction for the content in an element</td>
</tr>
<tr>
<td><a href="http://www.w3schools.com/tags/att_global_lang.asp">lang</a></td>
<td>Specifies the language of the element's content</td>
</tr>
<tr>
    <td><a href="http://www.w3schools.com/tags/att_global_tabindex.asp">tabindex</a></td>
    <td>Specifies the tabbing order of an element</td>
  </tr>
</tbody></table>

### accessKey

* 熱鍵
* windown os 可搭配控制鍵 alt，做 focus 位置切換
* mac os 可搭配控制鍵 ctrol + alt，做 focus 位置切換

*解析題庫*：1-33, 2-07

Differences Between HTML 4.01 and HTML5
In HTML5, the accesskey attribute can be used on any HTML element (it will validate on any HTML element. However, it is not necessarily useful).

In HTML 4.01, the accesskey attribute can be used with:

```
<a>, <area>, <button>, <input>, <label>, <legend>, and <textarea>.
```

http://www.w3schools.com/tags/att_global_accesskey.asp

### dir

**語法**

`<element dir="ltr|rtl|auto">`

**範例**

`<p dir="rtl">Write this text right-to-left!</p>`

**屬性值**

<table>
  <tbody><tr>
		<th style="width:20%">Value</th>
    <th>Description</th>
  </tr>
  <tr>
    <td>ltr</td>
    <td>預設，左到右呈現 (Left-to-right text direction) </td>
  </tr>
  <tr>
    <td>rtl</td>
    <td>右到左 (Right-to-left text direction) </td>
  </tr>
  <tr>
    <td>auto</td>
    <td>Let the browser figure out the text direction, based on the content 	(only recommended if the text direction is unknown)</td>
  </tr>
</tbody></table>

http://www.w3schools.com/tags/att_global_dir.asp

### lang

Common examples are "en" for English, "es" for Spanish, "fr" for France and so on.

**範例**

`<p lang="fr">Ceci est un paragraphe.</p>`

**補充: Differences Between HTML 4.01 and HTML5**

In HTML5, the lang attribute can be used on any HTML element (it will validate on any HTML element. However, it is not necessarily useful).

In HTML 4.01, the lang attribute cannot be used with: `<base>, <br>, <frame>, <frameset>, <hr>, <iframe>, <param>, <script>`


### tabindex

**定義**

The tabindex attribute specifies the tab order of an element (when the "tab" button is used for navigating).

**語法**

`<element tabindex="number">`

**範例**

```
<a href="http://www.w3schools.com/" tabindex="2">W3Schools</a>
<a href="http://www.google.com/" tabindex="1">Google</a>
<a href="http://www.microsoft.com/" tabindex="3">Microsoft</a>
```

*題庫解析*：2-05

http://www.w3schools.com/tags/att_global_tabindex.asp

### HTML5 新增的全域屬性

<table>
<tbody><tr>
<th style="width:25%">Attribute</th>
<th>Description</th>
</tr>
<tr>
<td class="html5badge">contenteditable</a></td>
<td>元素內容可以被編輯</td>
</tr>
<tr>
<td class="html5badge">contextmenu</a></td>
<td>Specifies a context menu for an element. The context menu appears when a
user right-clicks on the element </td>
</tr>
<tr>
<td class="html5badge">data-*</a></td>
<td>Used to store custom data private to the page or application</td>
</tr>
<td class="html5badge">draggable</a></td>
<td>設定可拖曳元素</td>
</tr>
<tr>
<td class="html5badge">dropzone</a></td>
<td>拖放區域</td>
</tr>
<tr>
<td class="html5badge">hidden</a></td>
<td>隱藏元素, Specifies that an element is not yet, or is no longer, relevant</td>
</tr>
<tr>
<td class="html5badge">spellcheck</a></td>
<td>Specifies whether the element is to have its spelling and grammar checked or
not</td>
</tr>
<tr>
<td class="html5badge">translate</a></td>
<td>Specifies whether the content of an element should be translated or not</td>
</tr>
</tbody></table>


*題庫解析*：2-02, 2-04, 2-06, 2-15
