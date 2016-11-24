# video

**定義**

* Defines a video
* IE9 才支援
* tips：The autoplay attribute does not work in mobile devices like iPad and iPhone.

**瀏覽器支援度**

In HTML5, there are 3 supported video formats: MP4, WebM, and Ogg.

<table>
<tbody><tr>
<th style="width:25%">Browser</th>
<th style="width:25%">MP4</th>
<th style="width:25%">WebM</th>
<th style="width:25%">Ogg</th>
</tr>
<tr>
<td>Internet Explorer</td>
<td>YES</td>
<td>NO</td>
<td>NO</td>
</tr>
<tr>
<td>Chrome</td>
<td>YES</td>
<td>YES</td>
<td>YES</td>
</tr>
<tr>
<td>Firefox</td>
<td>YES</td>
<td>YES</td>
<td>YES</td>
</tr>
<tr>
<td>Safari</td>
<td>YES</td>
<td>NO</td>
<td>NO</td>
</tr>
<tr>
<td>Opera</td>
<td>YES (from Opera 25)</td>
<td>YES</td>
<td>YES</td>
</tr>
</tbody></table>

**範例**

```
<video width="320" height="240" autoplay>
  <source src="movie.mp4" type="video/mp4">
  <source src="movie.ogg" type="video/ogg">
Your browser does not support the video tag.
</video>
```

**資料來源**

http://www.w3schools.com/html/html5_video.asp
http://www.w3schools.com/jsref/dom_obj_video.asp
http://www.w3schools.com/tags/ref_av_dom.asp

### source

**定義**

Defines multiple media resources for media elements, such as `<video>` and `<audio>`

The `<source>` element allows you to specify alternative audio files which the browser may choose from. The browser will use the first recognized format.

**資料來源**

http://www.w3schools.com/jsref/dom_obj_source.asp

### track

**定義**

This element is used to specify subtitles, caption files or other files containing text, that should be visible when the media is playing.

**範例**

```
<video width="320" height="240" controls>
  <source src="forrest_gump.mp4" type="video/mp4">
  <source src="forrest_gump.ogg" type="video/ogg">
  <track src="subtitles_en.vtt" kind="subtitles" srclang="en" label="English">
  <track src="subtitles_no.vtt" kind="subtitles" srclang="no" label="Norwegian">
</video>
```

**資料來源**

http://www.w3schools.com/tags/tag_track.asp
https://dev.w3.org/html5/spec-preview/content-models.html
