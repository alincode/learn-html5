# CSS

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

* Cascading Style Sheets

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

*解析題庫*：1-35

What style will be used when there is more than one style specified for an HTML element?

Generally speaking we can say that all the styles will "cascade" into a new "virtual" style sheet by the following rules, where number one has the highest priority:

* Inline style (inside an HTML element)
* External and internal style sheets (in the head section)
* Browser default


So, an inline style (inside a specific HTML element) has the highest priority, which means that it will override a style defined inside the <head> tag, or in an external style sheet, or a browser default value.

id, class

**Multiple Style Sheets**

[DEMO](http://www.w3schools.com/css/tryit.asp?filename=trycss_howto_multiple)



### CSS Transition Event

Kirupa Chinnathambi - CSS Transition Event
https://www.youtube.com/watch?v=m-JY1Yl-ALQ

**資料來源**

http://www.w3schools.com/css/css_howto.asp


