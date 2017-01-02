# 語意元素 in HTML5

* New tags：新的標籤，像是<header>、<section> 等
* Application tags：也是新的標籤，像是<meter>、<progress> 等
* Microdata：加入語意的資料讓搜尋引擎等網站可以正確顯示
* Form type：<form> 可以加入的 type 便多了，包含 email 和 tel 等屬性，瀏覽器會協助進行資料格式的驗證
* 有特殊意義的元素，由名稱可以了解到它與其他內容的差異。
* 語意元素全部都是 block elements

<table>
<tbody><tr>
<th style="width:20%">Tag</th>
<th>Description</th>
</tr>
<tr>
<td><a href="http://www.w3schools.com/tags/tag_article.asp">&lt;article&gt;</a></td>
<td>Defines an article</td>
</tr>
<tr>
<td><a href="http://www.w3schools.com/tags/tag_aside.asp">&lt;aside&gt;</a></td>
<td>Defines content aside from the page content</td>
</tr>
<tr>
<td><a href="http://www.w3schools.com/tags/tag_details.asp">&lt;details&gt;</a></td>
<td>Defines additional details that the user can view or hide</td>
</tr>
<tr>
<td><a href="http://www.w3schools.com/tags/tag_figcaption.asp">&lt;figcaption&gt;</a></td>
<td>描述圖片的標題, Defines a caption for a &lt;figure&gt; element</td>
</tr>
<tr>
<td><a href="http://www.w3schools.com/tags/tag_figure.asp">&lt;figure&gt;</a></td>
<td>Specifies self-contained content, like illustrations, diagrams, photos, code
listings, etc.</td>
</tr>
<tr>
<td><a href="http://www.w3schools.com/tags/tag_footer.asp">&lt;footer&gt;</a></td>
<td>Defines a footer for a document or section</td>
</tr>
<tr>
<td><a href=http://www.w3schools.com"/tags/tag_header.asp">&lt;header&gt;</a></td>
<td>描述文件或區段之標題, Specifies a header for a document or section</td>
</tr>
<tr>
<td><a href="http://www.w3schools.com/tags/tag_main.asp">&lt;main&gt;</a></td>
<td>Specifies the main content of a document</td>
</tr>
<tr>
<td><a href="http://www.w3schools.com/tags/tag_mark.asp">&lt;mark&gt;</a></td>
<td>文字中要突顯的部分</td>
</tr>
<tr>
<td><a href="http://www.w3schools.com/tags/tag_nav.asp">&lt;nav&gt;</a></td>
<td>Defines navigation links</td>
</tr>
<tr>
<td><a href="http://www.w3schools.com/tags/tag_section.asp">&lt;section&gt;</a></td>
<td>Defines a section in a document</td>
</tr>
<tr>
<td><a href="http://www.w3schools.com/tags/tag_summary.asp">&lt;summary&gt;</a></td>
<td>Defines a visible heading for a &lt;details&gt; element</td>
</tr>
<tr>
<td><a href="http://www.w3schools.com/tags/tag_time.asp">&lt;time&gt;</a></td>
<td>`適合用來表示時間`</td>
</tr>
</tbody></table>

### article

* 通常擁有自己的標題
* `<article>` 中，還可以在包含 `<article>`
* 表示網頁中一段完整的文件，或可單獨使用的文件

*題庫解析*：2-36

### section

* 包含內容及標題
* 可以將一段文章，分成好幾個 `<section>`

*題庫解析*：2-38

### `footer`

* 一個網頁中，可以有多個 `<footer>`
* 適合用來表示版權資訊
* 適用用來表示相關的文章連結資訊

### figure

* 用來包含影像及其說明，以便將圖及說明一連結在一起。
* [demo](http://www.w3schools.com/TAgs/tryit.asp?filename=tryhtml5_figcaption)

```html
<figure>
  <img src="img_pulpit.jpg" alt="The Pulpit Rock" width="304" height="228">
  <figcaption>Fig.1 - A view of the pulpit rock in Norway.</figcaption>
</figure>
```

http://www.w3schools.com/TAgs/tag_figure.asp

### figcaption

* 圖片標題
* [demo](http://www.w3schools.com/tags/tryit.asp?filename=tryhtml5_figcaption)

*題庫解析*：2-11

http://www.w3schools.com/TAgs/tag_figcaption.asp

### aside

* 適合放置廣告

*題庫解析*：2-40

### header

* 可以加入 table
* 可以加入搜尋表單
* 可以加入 `<nav>`

*題庫解析*：2-41

### nav

*題庫解析*：2-41

### 延伸閱讀
* http://www.w3schools.com/html/html5_semantic_elements.asp
