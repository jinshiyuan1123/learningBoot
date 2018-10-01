## 轮播插件 ##
轮播插件就是讲几张同等大小的大图，安装顺序依次播放

	<div id="mycarousel" class="carousel slide" >
		<ol class="carousel-indicators">
			<li data-target="#mycarousel" data-slide-to="0" class="active"></li>
			<li data-target="#mycarousel" data-slide-to="1"></li>
			<li data-target="#mycarousel" data-slide-to="2"></li>
		</ol>
		<div class="carousel-inner">
			<div class="item active">
				<img src="../images/Harry.jpg" alt="第一张">
			</div>
			<div class="item">
				<img src="../images/dunk.jpg" alt="第二张">
			</div>
			<div class="item">
				<img src="../images/Holly.jpg" alt="第三张">
			</div>
		</div>
		<a href="#mycarousel" data-slide="prev" class="carousel-control left">&lsaquo;</a>
		<a href="#mycarousel" data-slide="next" class="carousel-control right">&rsaquo;</a>
	</div>
	<button id="cycle" class="btn btn-default">开始</button>
	<button id="pause" class="btn btn-default">停止</button>
	<script>
	// $('#mycarousel').carousel({
	// 	interval:2000,
	// 	//wrap:false,   只播放一次
	// });
	$('#cycle').click(function(){
		$('#mycarousel').carousel('cycle');
	});
	$('#pause').click(function(){
		$('#mycarousel').carousel('pause');
	});
	</script>
	

样式   
![轮播](../images/carousel.gif)