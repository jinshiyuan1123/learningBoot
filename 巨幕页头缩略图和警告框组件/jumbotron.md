## 1.巨幕组件 ##
在固定的范围内，有圆角。

	<div class="container">
		<div class="jumbotron">
			<h3>网站标题</h3>
			<p>我是网站的详细简介！</p>
			<p><a href="#" class="btn btn-default">快速进入</a></p>
		</div>
	</div>

样式   
![范围](../images/jumbotron-notfull.png)


100%全屏，没有圆角

	<div class="jumbotron">
		<div class="container">
			<h3>网站标题</h3>
			<p>我是网站的详细简介</p>
			<p><a href="#" class="btn btn-default">快速进入</a></p>
		</div>
	</div>

样式      
![100%](../images/jumbotron-full.png)   

 
## 2.页头组件 ##
增加一些空间

	<div class="page-header">
		<h1>我是大标题<small>我是小标题</small></h1>
	</div>

样式      
![100%](../images/jumbotron-header.png)   

 
## 3.缩略图组件 ##
缩略图配合响应式

	<div class="container">
		<div class="row">
			<div class="col-md-3 col-ms-4 col-xs-6">
				<div class="thumbnail">
					<img src="../images/gaoyuanyuan.jpg" alt="">
					<div class="caption">
						<h3>图片</h3>
						<p>关于这张图的详情</p>
						<p><a href="#" class="btn btn-default">快速进入</a></p>
					</div>
				</div>
			</div>
			<div class="col-md-3 col-ms-4 col-xs-6">
				<div class="thumbnail">
					<img src="../images/gaoyuanyuan.jpg" alt="">
					<div class="caption">
						<h3>图片</h3>
						<p>关于这张图的详情</p>
						<p><a href="#" class="btn btn-default">快速进入</a></p>
					</div>
				</div>
			</div>
			<div class="col-md-3 col-ms-4 col-xs-6">
				<div class="thumbnail">
					<img src="../images/gaoyuanyuan.jpg" alt="">
					<div class="caption">
						<h3>图片</h3>
						<p>关于这张图的详情</p>
						<p><a href="#" class="btn btn-default">快速进入</a></p>
					</div>
				</div>
			</div>
			<div class="col-md-3 col-ms-4 col-xs-6">
				<div class="thumbnail">
					<img src="../images/gaoyuanyuan.jpg" alt="">
					<div class="caption">
						<h3>图片</h3>
						<p>关于这张图的详情</p>
						<p><a href="#" class="btn btn-default">快速进入</a></p>
					</div>
				</div>
			</div>
		</div>
	</div>

样式      
![100%](../images/jumbotron-thumb.gif)   

 
## 4.警告框组件 ##
基本警告框

	<div class="alert alert-success">Bootstrap</div>
	<div class="alert alert-warning">Bootstrap</div>
	<div class="alert alert-danger">Bootstrap</div>
	<div class="alert alert-info">Bootstrap</div>

样式      
![100%](../images/jumbotron-alert.png)   

 
带关闭的警告框

	<div class="alert alert-success" style="margin: 0 100px;">
		请到<a href="#" class="alert-link">官网下载</a>
		<button class="close" data-dismiss="alert">
			<span>&times;</span>
		</button>
	</div>

样式      
![100%](../images/Jumbotron-alert-close.gif)   

 
