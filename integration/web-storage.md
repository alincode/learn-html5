# 儲存 (Web Storage)

* 以 key-value 的型式來儲存資料
* 建議每個網站儲存的大小為 5MB
* localStorage 跟 sessionStorage 使用方式一樣，只要替換物件名稱就可以了。

**local storage object 有兩種**

* window.localStorage - 存在本地端，不會過期。
* window.sessionStorage - 存在本地端，只要瀏覽器關閉就失效。

**設定值**

```js
localStorage.setItem("lastname", "Smith");
// or
localStorage.lastname = "Smith";
// or
localStorage["lastname"] = "Smith";
```

**取得值**

```js
localStorage.getItem("lastname");
// or
localStorage.lastname;
```

**刪除值**

```js
localStorage.removeItem("lastname");
```

**判斷支不支援 Storage**

```
if (typeof(Storage) !== "undefined") {
    // Code for localStorage/sessionStorage.
} else {
    // Sorry! No Web Storage support..
}
```

http://www.w3schools.com/html/html5_webstorage.asp
