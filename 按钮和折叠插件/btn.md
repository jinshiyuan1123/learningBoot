## 按钮 ##
可以通过按钮创建不同状态的按钮   
单个切换

	<button class="btn btn-primary" data-toggle="button">按钮</button>

样式  
![单个切换](../images/btn-toggle.gif)

单选按钮

	<div class="btn-group" data-toggle="buttons">
		<label for="" class="btn btn-primary active">
			<input type="radio" name="sex" value="男" checked="checked">男
		</label>
		<label for="" class="btn btn-primary">
			<input type="radio" name="sex" value="女">女
		</label>
	</div>

![单选按钮](../images/btn-radio.gif)

复选按钮

	<div class="btn-group" data-toggle="buttons">
		<label for="" class="btn btn-primary active">
			<input type="checkbox" name="fa" value="体育" checked="checked">体育
		</label>
		<label for="" class="btn btn-primary">
			<input type="checkbox" name="fa" value="音乐">音乐
		</label>
		<label for="" class="btn btn-primary">
			<input type="checkbox" name="fa" value="艺术">艺术
		</label>
		<label for="" class="btn btn-primary">
			<input type="checkbox" name="fa" value="电脑">电脑
		</label>
	</div>

![复选状态](../images/btn-checkbox.gif)

加载状态

	<button class="btn btn-primary" data-loading-text="loading...." autocomplete="off" id="btn">开始上传</button>
	<script>
	$('#btn').click(function(){
		var btn =$(this).button('loading');
		setTimeout(function(){
			btn.button('reset');
		},1000);
	});
	</script>

![加载状态](../images/btn-loading.gif)