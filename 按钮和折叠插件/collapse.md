## 折叠 ##
通过点击可以折叠内容

	<button class="btn btn-primary" data-toggle="collapse" data-target="#content">
		Bootstrap
	</button>
	<div class="collapse" id="content">
		<div class="well">bootstrap是有Twitter公司推出的一个用于前端开发的开源工具包。</div>
	</div>

![样式](../images/collapse-basic.gif)

手风琴折叠

	<div class="panel-group" id="accordion">
		<div class="panel panel-default">
			<div class="panel-heading">
				<h4 class="panel-title">
					<a href="#collapseOne" data-toggle="collapse" data-parent="#accordion">第一部分链接</a>
				</h4>
			</div>
			<div class="panel-collapse collapse" id="collapseOne">
				<div class="panel-body">
					第一部分内容
				</div>
			</div>
		</div>
		

		<div class="panel panel-default">
			<div class="panel-heading">
				<h4 class="panel-title">
					<a href="#collapseTwo" data-toggle="collapse" data-parent="#accordion">第二部分链接</a>
				</h4>	
			</div>
			<div class="panel-collapse collapse" id="collapseTwo">
				<div class="panel-body">
					第二部分内容
				</div>
			</div>
		</div>
		

		<div class="panel panel-default">
			<div class="panel-heading">
				<h4 class="panel-title">
					<a href="#collapseThree" data-toggle="collapse" data-parent="#accordion">第三部分链接</a>
				</h4>	
			</div>
			<div class="panel-collapse collapse" id="collapseThree">
				<div class="panel-body">
					第三部分内容
				</div>
			</div>
		</div>
		

		<div class="panel panel-default">
			<div class="panel-heading">
				<h4 class="panel-title">
					<a href="#collapseFour" data-toggle="collapse" data-parent="#accordion">第四部分链接</a>
				</h4>	
			</div>
			<div class="panel-collapse collapse" id="collapseFour">
				<div class="panel-body">
					第四部分内容
				</div>
			</div>
		</div>	
	</div>

![折叠](../images/collapse-shou.gif)

折叠中的事件

	<script>
	 $('#content').on('show.bs.collapse',function(){
		alert('调用show方法时执行');
	 });
	</script>