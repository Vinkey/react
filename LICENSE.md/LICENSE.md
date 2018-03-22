初识篇：react<br>
处理思路：现在要做什么？怎么做？为什么做？什么时候做？后期优化还要考虑怎么做更合适？

多说无益，直接抛出问题，撸代码！<br>
接需求：定制表单，表单每隔2min自动提交一次。表单内容，输入用户名，密码(length>8 && length<10)，忘记密码？将对应的用户信息一并提交给成功转向的页面。

模拟环境:模拟假用户数据，实际从接口或数据库获取对应用户信息。
var arr={
[username:'zhangsan',age:'20',sex:'male'],
[username:'lisi',age:'30',sex:'female'],
[username:'zhihong',age:'25',sex:'male']
}

第一步：做什么
<form>
<label>用户名：<input type="text"></label>
<label>密码：<input type="password" minlength='11'></label>
</form>
