# Drag and Drop (拖放)

### `DataTransfer` 物件

用來儲存及讀取被拖曳物件的資料

**properties 屬性**

* dropEffect
* effectAllowed
* files
* items
* types

**mehtod 方法**

* clearData()
* getData()
* setDate()
* setDragImage()
* 略...

https://developer.mozilla.org/zh-TW/docs/Web/API/DataTransfer

### 屬性

**draggable**

* boolean
* 設定此物件可不可以被拖放

### 事件

**drop**

放下被拖曳的物件

**dragend**

移除被拖曳的物件

### 範例

```js
function dropHandler(e){
    e.preventDefault();
    e.stopPropagation();
    var files = e.dataTransfer.files;
    for(var i=0; i<files.length; i++){
        alert(files[i].name);
    }
}
```
