# button

http://www.w3schools.com/tags/tag_button.asp

**type `種類`**

* submit
* button
* reset

### type

**submit**

* formaction: e.g. demo_post.asp
* formmethod: e.g. post

```html
<form action="demo_form.asp" method="get">
  First name: <input type="text" name="fname"><br>
  Last name: <input type="text" name="lname"><br>
  <button type="submit">Submit</button>
  <button type="submit" formmethod="post" formaction="demo_post.asp">Submit using POST</button>
</form>
```

* `formenctype`: e.g. multipart/form-data

```html
<form action="demo_form.asp" method="get">
  First name: <input type="text" name="fname"><br>
  Last name: <input type="text" name="lname"><br>
  <button type="submit">Submit</button>
  <button type="submit" formenctype="multipart/form-data">Submit using POST</button>
</form>
```

http://www.w3schools.com/tags/att_button_formmethod.asp

### formtarget

form-target

http://www.w3school.com.cn/tags/att_button_formtarget.asp

