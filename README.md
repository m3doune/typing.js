# typing.js
打字机动画效果（animates typing）

<img src="http://withlihui.com/wp-content/uploads/2016/09/demo.gif" alt="打字机效果" width="600" height="120" />
<p>&nbsp;</p>
<h2>Download</h2>
<p>Zip：<a href="https://github.com/lihuii/typing.js/archive/master.zip" target="_blank">https://github.com/lihuii/typing.js/archive/master.zip</a></p>
<p>&nbsp;</p>
<h2>DEMO</h2>
<p>打字机效果很适合用在个人页面和主页的头部，下面是几个示例。<br />
<a href="http://fanxiangce.com" target="_blank">翻相册</a>（页脚）<br />
<a href="https://productmap.co/" target="_blank">https://productmap.co/<br />
http://www.stephanemartinw.com/</a></p>
<p>&nbsp;</p>
<h2>Usage</h2>

## Link  
CSS  
``` HTML
<link href="typing.css" rel="stylesheet">
```
JS  
``` HTML
<script src="typing.js"></script>
``` 

##Use it for text
``` HTML
<span id="words"></span><span id="cursor">|</span>
```
cursor是文字后面闪烁的光标，你可以更换它。cursor is blink, you can change it.

##Use it for placeholder
``` HTML
<input id="words" type="text" name="domain" value="" placeholder="">
```
then set `var isPlaceholder = true;`


##Setting
for one line text
```Javascript
  var strings = new Array("一段文字"); // single words
```
or multi text
```Javascript
  var strings = new Array("文段1", "文段2"); // multi words
```
  
more options
```Javascript
<script>
  var strings = new Array("text1", "text2", "...") ; // multi words
  var typingSpeed = 100; // 打出每个字的间隔时间
  var deleteSpeed = 40; // 删除每个字的间隔时间
  var isLoop = true; // 是否循环，true/false
  var waitTime = 800; // 打完一个字段后的等待时间
  var isPlaceholder = false; // if you use tying.js for placeholder, set it true.
</script>
```
