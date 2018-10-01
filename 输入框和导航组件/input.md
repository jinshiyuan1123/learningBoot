文本输入框就是可以在input元素前后加上文字或者按钮，可以实现对表单控件的扩展。  
## 往左侧添加文字 ##   

	<div class="input-group">
		<span class="input-group-addon">@</span>
		<input type="text" class="form-control">
	</div>

样式

![输入框](../images/input-addon-left.png)

## 往右侧添加文字 ##  

	<div class="input-group">
		<input type="text" class="form-control">
		<span class="input-group-addon">@163.com</span>
	</div>

样式
![输入框](../images/input-addon-right.png)

## 往两侧添加文字 ##

	<div class="input-group">
		<span class="input-group-addon">$</span>
		<input type="text" class="form-control">
		<span class="input-group-addon">.00</span>
	</div>

样式

![两侧](../images/input-addon-both.png)

## 左侧使用复选框和单选框 ##

	<div class="input-group">
		<span class="input-group-addon">
			<input type="checkbox">
		</span>
		<input type="text" class="form-control">
	</div>

样式

![复选框](../images/input-addon-checkbox.png)

## 右侧使用按钮 ##

	<div class="input-group">
		<input type="text" class="form-control">
		<div class="input-group-btn">
			<button class="btn btn-default">提交</button>
		</div>
	</div>
样式   
![按钮](../images/input-addon-btn.png)

## 使用下拉菜单或分列式 ##

	<div class="input-group">
		<input type="text" class="form-control">
		<div class="input-group-btn">
			<button class="btn btn-default" data-toggle="dropdown">
				下拉菜单
				<span class="caret"></span>
			</button>
			<ul class="dropdown-menu">
				<li class="dropdown-header">网站导航</li>
				<li><a href="#">首页</a></li>
				<li><a href="#">资讯</a></li>
				<li><a href="#">产品</a></li>
				<li class="divider"><a href="#">产品</a></li>
				<li class="disabled"><a href="#">关于</a></li>
			</ul>
		</div>
	</div>

样式   
![下拉菜单](../images/input-addon-menu.gif)