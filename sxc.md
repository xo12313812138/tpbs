<form>
		姓名：<input type="text" name="userName">
		密码：<input type="password" name="passwd">
		性别：<input type="radio" name="sex" value="1">男     
		<input type="radio" name="sex" value="0">女
		爱好：
		<input type="checkbox" name="hobby" value="1">读书
		<input type="checkbox" name="hobby" value="2">音乐
		<input type="checkbox" name="hobby" value="3">运动
		学历：
		<select name="degree">
			<option value="">--请选择--</option>    
			<option value="1">专科</option>    
			<option value="2">本科</option>    
			<option value="3">硕士</option>    
			<option value="4">博士及以上</option>
		</select>
		
		备注：<textarea name="comment" rows="5" cols="30"></textarea>
		
		<input type="submit" value="提交">
		<input type="reset" value="重置">
		<input type="button" value="返回">
		
		<input type="hidden" name="userId" value="1001">
</from>	
