## 响应式轮播图 ##

	<div id="mycarousel" class="carousel slide">
		<ol class="carousel-indicators">
			<li data-target="#mycarousel" data-slide-to="0" class="active"></li>
			<li data-target="#mycarousel" data-slide-to="1" ></li>
			<li data-target="#mycarousel" data-slide-to="2" ></li>
		</ol>
		<div class="carousel-inner">
			<div class="item active" style="background-color: #223240">
				<img src="../images/slide1.png" alt="">
			</div>
			<div class="item" style="background-color: #f5e4dc">
				<img src="../images/slide2.png" alt="">
			</div>
			<div class="item" style="background-color: #de2a2d">
				<img src="../images/slide3.png" alt="">
			</div>
		</div>
		<a href="#mycarousel" data-slide="prev" class="carousel-control left">&lsaquo;</a>
		<a href="#mycarousel" data-slide="next" class="carousel-control right">&rsaquo;</a>
	</div>
	<script>
		$(function(){

			//设置自动播放
			$('#mycarousel').carousel({
				interval:3000,
			});

			//设置垂直居中
			$('.carousel-control').css('line-height',$('.carousel-inner img').height()+'px');
			$(window).resize(function(){
				var height=$('.carousel-inner img').eq(0).height()||$('.carousel-inner img').eq(1).height()||$('.carousel-inner img').eq(2).height();
				$('.carousel-control').css('line-height',height+'px');
			});
			



		});	
	</script>

样式  
![响应式轮播图](../images/progect-2-carousel.gif)