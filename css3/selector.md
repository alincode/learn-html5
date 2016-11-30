# Selector 選擇器

```html
<footer id="layout-footer" class="myclass">
    <address>OOXX</adress>
</footer>
```

**universal 通用選擇器**

```
* {...}
```

**ID 選擇器**

```
#layout-footer {...}
```

**class 類型選擇器**

```
.myclass {...}
```

**type 型態選擇器**

```
footer {...}
```

**child 子選擇器**

```
footer > address {...}
```

**descendant 後代選擇器**

```
footer address {...}
```

**attr 屬性**

```
:invalid {
  background-color: grey;
}
```

### 常見`錯誤`的使用

**錯誤一**

```
footer + address {...}
```

**錯誤二**

```
footer >> address {...}
```

**錯誤三**

```
footer ~ address {...}
```
