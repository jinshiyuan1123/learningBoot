按钮组件就是多个按钮集成在一个容器里形成独有的效果。
## 基本格式 ##

	<div class="btn-group">
		<button class="btn btn-default">左</button>
		<button class="btn btn-default">中</button>
		<button class="btn btn-default">右</button>
	</div>

样式    
![基本格式](../images/btn-group-basic.png)


## 将多个按钮组整合起来方便管理 ##

	<div class="btn-toolbar">
		<div class="btn-group">
			<button class="btn btn-default">左</button>
			<button class="btn btn-default">中</button>
			<button class="btn btn-default">右</button>
		</div>
		<div class="btn-group">
			<button class="btn btn-default">1</button>
			<button class="btn btn-default">2</button>
			<button class="btn btn-default">3</button>
		</div>
	</div>

样式;   
![toolbar](../images/btn-group-tool.png)  

## 设置按钮组大小 ##

	<div class="btn-toolbar">
		<div class="btn-group btn-group-lg">
			<button class="btn btn-default">左</button>
			<button class="btn btn-default">中</button>
			<button class="btn btn-default">右</button>
		</div>
		<div class="btn-group btn-group-ms">
			<button class="btn btn-default">1</button>
			<button class="btn btn-default">2</button>
			<button class="btn btn-default">3</button>
		</div>
		<div class="btn-group btn-group-xs">
			<button class="btn btn-default">4</button>
			<button class="btn btn-default">5</button>
			<button class="btn btn-default">6</button>
		</div>
	</div>

样式：

![大小](../images/btn-group-lg.png)

## 嵌套一个分组，比如下拉菜单 ##

	<div class="btn-group">
		<button class="btn btn-default">左</button>
		<button class="btn btn-default">中</button>
		<button class="btn btn-default">右</button>
		<div class="btn-group">
			<button class="btn btn-default dropdown-toggle" data-toggle="dropdown">
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
![嵌套](../images/btn-group-qiantao.png)


## 设置垂直按钮组 ##

	<div class="btn-group-vertical">
		<a href="#" class="btn btn-default">上</a>
		<a href="#" class="btn btn-default">中</a>
		<a href="#" class="btn btn-default">下</a>
	</div>

样式   
![垂直按钮](../images/btn-group-vertical.png)

## 设置两端对齐按钮 ##

使用<a\>标签  

	<div class="btn-group-justified">
		<a href="#" class="btn btn-default">左</a>
		<a href="#" class="btn btn-default">中</a>
		<a href="#" class="btn btn-default">右</a>
	</div>

样式   
![两端对齐](../images/btn-group-justified.png)