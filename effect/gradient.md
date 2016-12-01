# Gradient 漸變效果

## linear-gradient

### 語法

**新的語法**

```
linear-gradient(
  [ <angle> | to <side-or-corner> ,]? <color-stop> [, <color-stop>]+ )
```

**舊的語法**

```
-moz-linear-gradient([ [ [top | bottom] || [left | right] ],]? <color-stop>[, <color-stop>]+);
```

```
linear-gradient(direction, color-stop1, color-stop2, ...);
```

### 範例

**Linear Gradient - Top to Bottom 範例**

[demo](http://www.w3schools.com/css/tryit.asp?filename=trycss3_gradient-linear)

```css
#grad {
     background: linear-gradient(red, yellow);
}
```

**Linear Gradient - Left to Right 範例**

[demo](http://www.w3schools.com/css/tryit.asp?filename=trycss3_gradient-linear_ltr)

```css
#grad {
    height: 200px;
    background: linear-gradient(to right, red , yellow);
}
```

```css
#grad {
    height: 200px;
    background: linear-gradient(123deg, red , yellow);
}
```

**題庫 6-27**

```css
div {
  width: 200px;
  height: 100px;
  // background-image: -moz-linear-gradient(top, white, black);
  background-image: linear-gradient(to bottom, white, black);
  transform: translate(100px, 100px) rotate(30deg)
}
```

* [demo](http://codepen.io/alincode/pen/bBYPyZ)


### 延伸閱讀
* [css3 gradients - w3schools  ](http://www.w3schools.com/css/css3_gradients.asp)
* [CSS3 漸層背景 (background linear gradient) 實作練習 - Yijen's blog](http://blog.yam.com/hanasan/article/66887138)
