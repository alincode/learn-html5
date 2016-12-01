# Javascript

* 採用物件導向程式語言
* 為直譯是程式語言
* `不包含修正資料`

### 注意事項

* 分號(;)的使用

```js
var x = 0;

var sayHi = function(name){
    console.log('hi, ' + name);
};

sayHi('alincode');
```

### 布林運算

**範例一**

```js
var x = 3;

console.log(x === "3"); // false
console.log(x === 3);   // true
```

**範例二**

```js
console.log('0 % 3 == 0'); // true
```

**範例三**

`!null = true`

http://www.w3schools.com/js/js_booleans.asp

### 數字連接字串

**範例一**

```js

var x, X, result;
x = 1 + 2;
X = "3" + "4";
result = x + X;
cnosole.log(result);

```

**範例二**

```js
// 八進位
console.log((8).toString(8)); // 10
// 二進位
console.log((2).toString(2)); // 10
console.log(String(2)); // 2

var test = (2).toString(2) + String(2);
console.log(test); // 102
```

**語法**

`number.toString(radix)`

**延伸閱讀**

* http://www.w3schools.com/jsref/jsref_tostring_number.asp
* http://www.w3school.com.cn/js/pro_js_typeconversion.asp

### 陣列 (Array)

**宣告**

方法一：
```js
var family = new Array();
family.push('mother');
family.push('father');
family.push('sister');
```

方法二：
```js
var family = ['mother', 'father', 'sister'];

console.log(family[0]);

```

**存取方式**

```
console.log(family[0]); // output: mother

```

### 物件

**宣告**

```js

// 方法一
var persion = {};
persion.nickname = 'alincode';

// 方法二
var persion = {
    nickname: 'alincode'
};

```

**存取方式**

* 記得雙引號

```js
var persion = {
    name: 'alincode',
    email: 'alincode@gmail.com'
}

console.log(persion.name);
console.log(persion["name"]);
```

**for loop 物件值**

loops through the properties of an object

*解析題庫*：1-39

```js
for(x in persion){
    console.log(x);
}
```

**物件屬性值，存不存在**

*解析題庫*：1-41

* 要用引號包起來

```js
cnosole.log("name" in persion); // true
cnosole.log("phone" in persion); // false
```

**物件比較**

```js
var person1 = {
  name: 'Paul',
  age: 25
};

var person2 = {
  name: 'Tommy',
  age: 26
};

var person3 = person2;

console.log(person1 == person2); // false
console.log(person2 == person3); // true
console.log(person1 === person2); // false
console.log(person2 === person3); //  true
```

### function

### 例外處理

* try catch
* exception

```js
function example(){
    try{
        throw new Error("I am error.");
    }catch(e){
        console.error(e);
    }
}
```

### 修改元素內容

```html
<p id="A">Output A</p>
<p id="B">Output B</p>
<p id="C">Output C</p>
```

```js

<script type="text/javascript">
    document.getElementById("B").innerHTML="Change D.";
</script>

```

### ECMAScript

ECMAScript是由ECMA-262標準化的腳本語言的名稱。JavaScript和JScript與ECMAScript相容，但包含超出ECMAScript的功能。

```
type="text/ecmascript"
type="text/javascript"
```

MIME_type

### 迴圈(for loop)

* for
* for/in - loops through the properties of an object
* while
* do/while

http://www.w3schools.com/js/js_loop_for.asp

### array method

*解析題庫*：1-46

* shift()
* push()
* reverse()
* `sort()`

```js
console.log('=== origin array ===\n', ["Banana", "Orange", "Apple", "Mango"]);

function shift() {
  var fruits = ["Banana", "Orange", "Apple", "Mango"];
  fruits.shift()
  console.log('=== shift output ===\n', fruits);
}

shift();

function sort() {
  var fruits = ["Banana", "Orange", "Apple", "Mango"];
  fruits.sort()
  console.log('=== sort output ===\n', fruits);
}

sort();

function reverse() {
  var fruits = ["Banana", "Orange", "Apple", "Mango"];
  fruits.reverse()
  console.log('=== reverse output ===\n', fruits);
}

reverse();
```

**output**

```
=== origin array ===
 [ 'Banana', 'Orange', 'Apple', 'Mango' ]
=== shift output ===
 [ 'Orange', 'Apple', 'Mango' ]
=== sort output ===
 [ 'Apple', 'Banana', 'Mango', 'Orange' ]
=== reverse output ===
 [ 'Mango', 'Apple', 'Orange', 'Banana' ]
```

**資料來源**

* [w3school - JS array methods](http://www.w3schools.com/js/js_array_methods)
* [w3school - JS array sort](http://www.w3schools.com/js/js_array_sort.aspasp)
