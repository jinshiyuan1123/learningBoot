## 1.基本使用 ##
使用模态框组件需要三层div容器。分别为modal、dialog、content。在内容里面，还有三层，分别为header、body、footer.


	<!-- 模态框声明 -->
	<div class="modal fade" id="myModal" tabindex="-1">
		<!-- 窗口声明 -->
		<div class="modal-dialog modal-sm">
			<!-- 内容声明 -->
			<div class="modal-content">
				<div class="modal-header">
					<button class="close" data-dismiss="modal"><span>&times;</span></button>
					<h4>会员登录</h4>
				</div>
				<div class="modal-body">
					<div class="container-fluid">
						<div class="row">
							<div class="col-md-4">1</div>
							<div class="col-md-4">2</div>
							<div class="col-md-4">3</div>
						</div>
					</div>
				</div>
				<div class="modal-footer">
					<button class="btn btn-default">注册</button>
					<button class="bn  btn-primary">登录</button>
				</div>
			</div>
		</div>
	</div>

	<button class="btn btn-primary btn-lg" data-toggle="modal" data-target="#myModal">点击弹窗</button>

![modal](../images/modal-1.gif)

也可以用jQuery设置。

	<button class="btn btn-primary btn-lg" id="btn">点击弹窗</button>
	<script type="text/javascript">
		$('#btn').click(function(){
			$('#myModal').modal('show');
		});
		$('#myModal').modal({
			show:false,
		});

		$('#myModal').on('show.bs.modal',function(){
			alert('当调用show方法时立即触发');
		});

		$('#myModal').on('shown.bs.modal',function(){
			alert('当弹窗完全出现再执行');
		});

		$('#myModal').on('hide.bs.modal',function(){
			alert('在hide方法立即调用时触发');
		});

		$('#myModal').on('hidden.bs.modal',function(){
			alert('模态框关闭后触发');
		});
	</script>

样式

![modal](../images/modal-2.gif)


设置淡入淡出效果的代码

	<div class="modal fade" id="myModal" tabindex="-1">

在主体中使用栅格系统中的流体

	<div class="modal-body">
		<div class="container-fluid">
			<div class="row">
				<div class="col-md-4">1</div>
				<div class="col-md-4">2</div>
				<div class="col-md-4">3</div>
			</div>
		</div>
	</div>

data属性  
data-toggle  表示触发类型  
data-target  表示触发的节点

选项  

![选项](../images/modal-options.png)

方法  

![方法](../images/modal-methods.png)