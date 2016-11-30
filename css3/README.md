# CSS3

* `不被 IE9 支援`

### CSS3 新增的語法

* border-image  圖片邊框
* border-radius 圓角邊框

### 適用 CSS3 的情況

*題庫解析*：1-26

* 定義特定標籤格式
* 使網站上的每一個網站編排達到一致性

### background-position

```
background-position: bottom right;
background-position: right bottom;
background-position: 100% 100%;
```

### background-image

**同時使用多個背景**

```
background-image: url(A.gif), url(B.gif);
```

### text-indent

將指定文字元素第一行空下 50px

```css
p {
    text-indent: 50px;
}
```

* [demo](http://www.w3schools.com/cssref/tryit.asp?filename=trycss_text-indent)

### borders

### 文字樣式

### CSS3 Multi-Column Layout

### resize

讓使用者能改變指定元素的大寫

`resize:both; overflow:auto`

**參數**

* none
* both
* vertical

### overflow

用來定義元素超過某個範圍的時候該如何呈現，例如圖片超過預設區域的大小、文字長度超出原本的範圍等

**CSS overflow 常見的值**

* overflow: auto;　// 預設會自動使用捲軸
* overflow:visible;　 // 顯示的文字或圖片會直接超出範圍，不使用捲軸。
* overflow:hidden;　// 自動隱藏超出的文字或圖片。
* overflow:scroll;　// 自動產生捲軸。
* overflow:inherit;　// 繼承自父元素的可見性


** 延伸閱讀**
* [CSS overflow 屬性用法 - Wibibi 網頁設計教學百科](http://www.wibibi.com/info.php?tid=157)
* http://www.w3schools.com/cssref/pr_pos_overflow.asp

### position

* relative: 該元素原應在的位置

### text-align

* left
* right
* center
* justified

http://www.w3schools.com/cssref/css3_pr_text-justify.asp
