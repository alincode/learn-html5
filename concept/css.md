# CSS

### Box model

* padding, 留白
* border, 邊框
* margin, 邊界

### Elements level

* Block-level Elements

```html
<div>
<h1> - <h6>
<p>
<form>
<header>
<footer>
<section>
```

* Inline Elements

```
<span>
<a>
<img>
```

```css
li {
    display: inline;
}
```

http://www.w3schools.com/css/css_display_visibility.asp

### 撰寫位置

*解析題庫*：1-34

**External style sheet**

```html
<head>
    <link rel="stylesheet" type="text/css" href="mystyle.css">
</head>
```

**Internal style sheet**

```html
<head>
    <style>
    body {
        background-color: linen;
    }

    h1 {
        color: maroon;
        margin-left: 40px;
    }
    </style>
</head>
```

**Inline style**

```html
<h1 style="color:blue;margin-left:30px;">This is a heading.</h1>
```

## CSS selector

![css selector](http://www.w3schools.com/css/selector.gif)

### 優先權 (Cascading Order)

* Inline stylesheet
* Embedded stylesheet
* Imported stylesheet
* Linked stylesheet
* Browser's own stylesheet

*解析題庫*：1-35

**Multiple Style Sheets**

[DEMO](http://www.w3schools.com/css/tryit.asp?filename=trycss_howto_multiple)

### CSS Transition Event

Kirupa Chinnathambi - CSS Transition Event
https://www.youtube.com/watch?v=m-JY1Yl-ALQ

**資料來源**

http://www.w3schools.com/css/css_howto.asp
