# audio

**定義**

* Defines sound content
* 是 Media Element

Before HTML5, audio files could only be played in a browser with a plug-in (like flash).

The HTML5 <audio> element specifies a standard way to embed audio in a web page.


**瀏覽器支援度**

In HTML5, there are 3 supported audio formats: MP3, Wav, and Ogg.

<table>
<tbody><tr>
<th style="width:25%">Browser</th>
<th style="width:25%">MP3</th>
<th style="width:25%">Wav</th>
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
<td>YES</td>
<td>NO</td>
</tr>
<tr>
<td>Opera</td>
<td>YES</td>
<td>YES</td>
<td>YES</td>
</tr>
</tbody></table>

**範例**

```
<audio controls>
  <source src="horse.ogg" type="audio/ogg">
  <source src="horse.mp3" type="audio/mpeg">
Your browser does not support the audio element.
</audio>
```

**資料來源**

http://www.w3schools.com/html/html5_audio.asp
http://www.w3schools.com/jsref/dom_obj_audio.asp
