# 動態效果

### Gradient 漸變效果

**linear-gradient**

`linear-gradient(white, black, white)`

```
width: 200px;
height: 100px;
background-image: linear-gradient(top, white, black);
transform: translate(100px, 100px) rotate(30deg);
```

**radial-gradient**

**repeating-radial-gradient**

### Marguee 跑馬燈

如果要在 Chrome 可以順利運作要加 `overflow:-webkit-marquee;`


**marguee-direction**

* forwards 左到右
* revrse 右到左

**marquee-play-count**

* infinite
* 預設是1

**marquee-style**

* scroll
* slide

**overflow-style**

* marquee-block

**marquee-speed**

### Media Queries 媒體查詢

* 讓網頁可以針對不同的媒體，形式定義不同的樣式。
* 好處：不需要為不同設備寫各自獨立的樣式表

```
@media all and(max-width:400px){
    #back{
        color:red;
    }
}
```

### CSS 2D / 3D

* skew
* matrix 自由度最高
* rotateX
* rotateZ

### Transformation 轉換

```
rotate(20,30)
rotate3d(120deg, 1, 3, 1)
```

```
transform: rotateX(-70deg);
```
