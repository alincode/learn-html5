# video

**定義**

* Defines a video
* 是 Media Element
* 是嵌入是內容（embedded content)
* IE9 支援
* tips：The autoplay attribute does not work in mobile devices like iPad and iPhone.

**HTML5 支援的`編碼`**

* H.265
* VP8

**範例**

```html
<video width="320" height="240" autoplay>
  <source src="movie.mp4" type="video/mp4">
  <source src="movie.ogg" type="video/ogg">
Your browser does not support the video tag.
</video>
```

**延伸閱讀**

* http://www.w3schools.com/html/html5_video.asp
* http://www.w3schools.com/jsref/dom_obj_video.asp
* http://www.w3schools.com/tags/ref_av_dom.asp
* http://www.w3schools.com/tags/tag_video.asp

## 屬性

### controls

* Play
* Pause
* Seeking
* Volume
* Fullscreen toggle
* Captions/Subtitles (when available)
* Track (when available)

http://www.w3schools.com/tags/att_video_controls.asp

*解析題庫*：4-16

### poster

在 video 下載錢，指定顯示的圖像。

```
<video controls="controls" paster="image.gif"></video>
```

### preload

**語法**

`<video preload="auto|metadata|none">`

*解析題庫*：4-01

http://www.w3schools.com/tags/att_video_preload.asp

### loop

播放結束之後，重新開始播放。

**語法**

`<video loop>`

*解析題庫*：4-02

http://www.w3schools.com/tags/att_video_loop.asp

## Video DOM event

**事件發生的順序**

* loadstart
* durationchange
* loadedmetadata
* loadeddata
* progress
* canplay
* canplaythrough

**載入成功**

* onloadstart
* oncanplay
* onloadedmetadata

**載入失敗**

* onerror
* onloadstart

**多媒體黨無法下載**

* onstalled

**播放完畢**

* onended

**實際下載音頻和開始播放**

```js
var vid = document.getElementById("myVideo");
vid.oncanplaythrough = function() {
    alert("Can play through video without stopping");
};
```

http://www.w3schools.com/TAgs/av_event_canplaythrough.asp

## `<source>`

**定義**

Defines multiple media resources for media elements, such as `<video>` and `<audio>`

The `<source>` element allows you to specify alternative audio files which the browser may choose from. The browser will use the first recognized format.

```html
<vidoe>
    <source media="screen and (max-height:700px)">
    或
    <source media="not screen and (max-height:700px)">
    或
    <source media="screen, (max-height:700px)">
</video>
```

http://www.w3schools.com/jsref/dom_obj_source.asp

## `<track>`

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
http://www.w3schools.com/TagS/ref_av_dom.asp

## Video DOM method

### canplaytype

回傳是否能播放指定的影片檔案格式

```
var vid = document.createElement('video');
isSupp = vid.canPlayType(vidType+';codecs="'+codType+'"');
```

http://www.w3schools.com/TagS/av_met_canplaytype.asp

## Video Dom Properties

### videoHeight, videoWidth

* 屬於`立即可用` (interactive content)

```
<video id="foo" src="foo.mp4"></video>

var vid = document.getElementById("foo");
vid.videoHeight; // returns the intrinsic height of the video
vid.videoWidth; // returns the intrinsic width of the video
```

### defaultPlaybackRate

設定播放速度

```
var vid = document.getElementById("myVideo");
vid.defaultPlaybackRate = 0.5;
```

http://www.w3schools.com/TagS/av_prop_defaultplaybackrate.asp

## Video DOM `error property`

* 1 = MEDIA_ERR_ABORTED - fetching process aborted by user
* 2 = MEDIA_ERR_NETWORK - error occurred when downloading
* 3 = MEDIA_ERR_DECODE - error occurred when decoding
* 4 = MEDIA_ERR_SRC_NOT_SUPPORTED - audio/video not supported

*題庫解析*：4-42

## 瀏覽器影片格式支援度

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


