在媒体查询时，针对不同的分辨率大小，有时需要显示和隐藏部分内容，响应工具类，就提供了这种解决方法。

![响应式工具](../images/resp-tool.png)

响应式工具目前只适用于块和表切换。  
形如.visible-*-*的类针对每种屏幕大小都有三种变体，针对每个css不同的display属性

![显示](../images/resp-tool-display.png)

代码：

	<div class="visible-xs-block a">A</div>


	<div class="hidden-xs a">B</div>

这段代码意思是当屏幕分辨率小于768px时，显示A，当屏幕大于768px时，显示B。

![响应](../images/resp.gif)