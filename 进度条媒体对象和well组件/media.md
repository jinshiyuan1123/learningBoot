## 1.well组件 ##
这个组件可以实现简单的嵌套效果

	<div class="well well-md">
		bootstrap
	</div>

样式  
![well](../images/media-well.png)


## 2.进度条组件 ##
进度条组件为当前工作流程或动作提供时时反馈  
基本进度条

	<div class="progress">
		<div class="progress-bar" style="width: 60%">60%</div>
	</div>

样式  
![基本](../images/media-progress.png)


最低值进度条  

	<div class="progress">
		<div class="progress-bar" style="min-width: 20px;width:0%;">0%</div>
	</div>

样式  
![最低](../images/media-progress-min.png)


结合情景的进度条

	<div class="progress">
		<div class="progress-bar progress-bar-success" style="min-width: 20px;width:60%;">60%</div>
	</div>

样式  
![success](../images/media-progress-success.png)


条纹状

	<div class="progress">
		<div class="progress-bar progress-bar-success progress-bar-striped" style="min-width: 20px;width:60%;">60%</div>
	</div>

样式  
![条纹](../images/media-progress-striped.png)


动画效果

	<div class="progress">
		<div class="progress-bar progress-bar-success progress-bar-striped active" style="min-width: 20px;width:60%;">60%</div>
	</div>

样式  
![动画](../images/media-progress-active.gif)


堆叠效果

	<div class="progress">
		<div class="progress-bar progress-bar-danger progress-bar-striped" style="min-width: 20px;width:20%;">20%</div>
		<div class="progress-bar progress-bar-warning progress-bar-striped" style="min-width: 20px;width:40%;">40%</div>
		<div class="progress-bar progress-bar-success progress-bar-striped" style="min-width: 20px;width:40%;">40%</div>
	</div>

样式  
![堆叠](../images/media-progress-group.png)

## 3.媒体对象组件 ##
媒体对象可以包含图片，视频或者音频等媒体，以达到对象和文本组合显示的样式效果。

	<div class="media">
		<div class="media-left">
			<img src="../images/small.jpg" alt="" class="media-object">
		</div>
		<div class="media-body">
			<h4 class="media-heading">内容标题</h4>
			<p>1996年，高圆圆被广告公司发掘，随后拍摄大量的商业广告，在广告圈中崭露头[1]。1997年，主演了个人首部大银幕作品《爱情麻辣烫》，从此开始了她的演艺生涯[2]  。2003年，凭借古装武侠爱情剧《倚天屠龙记》受到广泛关注。2005年，因在剧情片《青红》中饰演女主人公青红入围戛纳电影节最佳女主角奖。2006年，凭借喜剧动作片《宝贝计划》入围百花奖最佳女演员提名。2007年因在爱情电影《男才女貌》中饰演聋哑幼师秦小悠获得第11届电影表演艺术学会奖新人奖 </p>
		</div>
	</div>


样式  
![媒体](../images/media.png)
 

媒体对象列表

	<ul class="media-list">
		<li class="media">
			<div class="media-left">
				<img src="../images/small.jpg" alt="" class="media-object">
			</div>
			<div class="media-body">
				<h4 class="media-heading">内容标题</h4>
				<p>1996年，高圆圆被广告公司发掘，随后拍摄大量的商业广告，在广告圈中崭露头[1]。1997年，主演了个人首部大银幕作品《爱情麻辣烫》，从此开始了她的演艺生涯[2]  。2003年，凭借古装武侠爱情剧《倚天屠龙记》受到广泛关注。2005年，因在剧情片《青红》中饰演女主人公青红入围戛纳电影节最佳女主角奖。2006年，凭借喜剧动作片《宝贝计划》入围百花奖最佳女演员提名。2007年因在爱情电影《男才女貌》中饰演聋哑幼师秦小悠获得第11届电影表演艺术学会奖新人奖 </p>
			</div>
		</li>
		<li class="media">
			<div class="media-left">
				<img src="../images/small.jpg" alt="" class="media-object">
			</div>
			<div class="media-body">
				<h4 class="media-heading">内容标题</h4>
				<p>1996年，高圆圆被广告公司发掘，随后拍摄大量的商业广告，在广告圈中崭露头[1]。1997年，主演了个人首部大银幕作品《爱情麻辣烫》，从此开始了她的演艺生涯[2]  。2003年，凭借古装武侠爱情剧《倚天屠龙记》受到广泛关注。2005年，因在剧情片《青红》中饰演女主人公青红入围戛纳电影节最佳女主角奖。2006年，凭借喜剧动作片《宝贝计划》入围百花奖最佳女演员提名。2007年因在爱情电影《男才女貌》中饰演聋哑幼师秦小悠获得第11届电影表演艺术学会奖新人奖 </p>
				<div class="media">
					<div class="media-left">
						<img src="../images/small.jpg" alt="" class="media-object">
					</div>
					<div class="media-body">
						<h4 class="media-heading">内容标题</h4>
						<p>1996年，高圆圆被广告公司发掘，随后拍摄大量的商业广告，在广告圈中崭露头[1]。1997年，主演了个人首部大银幕作品《爱情麻辣烫》，从此开始了她的演艺生涯[2]  。2003年，凭借古装武侠爱情剧《倚天屠龙记》受到广泛关注。2005年，因在剧情片《青红》中饰演女主人公青红入围戛纳电影节最佳女主角奖。2006年，凭借喜剧动作片《宝贝计划》入围百花奖最佳女演员提名。2007年因在爱情电影《男才女貌》中饰演聋哑幼师秦小悠获得第11届电影表演艺术学会奖新人奖 </p>
					</div>
				</div>
				<div class="media">
					<div class="media-left">
						<img src="../images/small.jpg" alt="" class="media-object">
					</div>
					<div class="media-body">
						<h4 class="media-heading">内容标题</h4>
						<p>1996年，高圆圆被广告公司发掘，随后拍摄大量的商业广告，在广告圈中崭露头[1]。1997年，主演了个人首部大银幕作品《爱情麻辣烫》，从此开始了她的演艺生涯[2]  。2003年，凭借古装武侠爱情剧《倚天屠龙记》受到广泛关注。2005年，因在剧情片《青红》中饰演女主人公青红入围戛纳电影节最佳女主角奖。2006年，凭借喜剧动作片《宝贝计划》入围百花奖最佳女演员提名。2007年因在爱情电影《男才女貌》中饰演聋哑幼师秦小悠获得第11届电影表演艺术学会奖新人奖 </p>
					</div>
				</div>
				<div class="media">
					<div class="media-left">
						<img src="../images/small.jpg" alt="" class="media-object">
					</div>
					<div class="media-body">
						<h4 class="media-heading">内容标题</h4>
						<p>1996年，高圆圆被广告公司发掘，随后拍摄大量的商业广告，在广告圈中崭露头[1]。1997年，主演了个人首部大银幕作品《爱情麻辣烫》，从此开始了她的演艺生涯[2]  。2003年，凭借古装武侠爱情剧《倚天屠龙记》受到广泛关注。2005年，因在剧情片《青红》中饰演女主人公青红入围戛纳电影节最佳女主角奖。2006年，凭借喜剧动作片《宝贝计划》入围百花奖最佳女演员提名。2007年因在爱情电影《男才女貌》中饰演聋哑幼师秦小悠获得第11届电影表演艺术学会奖新人奖 </p>
					</div>
				</div>
			</div>
		</li>
	</ul>

样式  
![媒体列表](../images/media-list.png)