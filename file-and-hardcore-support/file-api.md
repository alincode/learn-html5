# File API


**讀取檔案**

* FileList 物件：存放所選取的檔案
* File 物件：用來讀取檔案的資訊
    * name
    * size
    * type
* Blob 物件：二進位原始資料

```js
document.getElementById("file1").files;
// File array object
```

```html
<input type="file" id="file1">
```

### FileReader 介面

* 可以將 File 物件的資料讀入記憶體中
* 可以將 Blob 物件的資料讀入記憶體中
* 可以透過 result 屬性來讀取記憶體中的資料

### 範例

```js
function fileViewer(){
    var theFile = document.getElementById("file1").files[0];
    var reader = new FileReader();
    reader.onload = function(e){
        var fileContent = e.target.result;
        document.getElementById("show").value = fileContent;
        reader.readAsText(theFile);
    }
}


```
