# offline web application

* MIME type: text/cache-manifest
* 當 Mainfest 的檔案被修改時，瀏覽器會重新下載儲存的檔案。

### Manifest

* 註解方式，用 `#`

* CACHE
* NETWORK
* FALLBACK

### 事件

**更新檔案過程中會觸發的事件**

* checking
* downloading
* cached

**發現沒有需要更新的檔案時，會觸發的事件**

* obsolete

**檢查檔案是否要更新時，如果發現沒有 Manifest 檔，會觸發的事件**

* error

**發現需要重新下載新的檔案時，會觸發的事件**

* updateready



### 範例

```
CACHE MANIFEST
clock.html
clock.css
clock.js

NETWORK:
comm.cgi
```


