# offline web application (離線網路應用程式)

* MIME type: text/cache-manifest
* 當 Mainfest 的檔案被修改時，瀏覽器會重新下載儲存的檔案。
* [应用缓存初级使用指南 - html5rocks   ](https://www.html5rocks.com/zh/tutorials/appcache/beginner/)

### Manifest

* 註解方式，用 `#`

**分成三個部分**

* CACHE
* NETWORK：不要被 cache
* FALLBACK

**範例**

```h
CACHE MANIFEST
# 2010-06-18:v2

# Explicitly cached 'master entries'.
CACHE:
/favicon.ico
index.html
stylesheet.css
images/logo.png
scripts/main.js

# Resources that require the user to be online.
NETWORK:
login.php
/myapi
http://api.twitter.com

# static.html will be served if main.py is inaccessible
# offline.jpg will be served in place of all images in images/large/
# offline.html will be served in place of all other .html files
FALLBACK:
/main.py /static.html
images/large/ images/offline.jpg
*.html /offline.html
```



http://www.w3schools.com/html/html5_app_cache.asp

### `cache event` (事件)

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
