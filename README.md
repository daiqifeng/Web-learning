# Web-learning
115homepage
<!-login_html-->
<!DOCTYPE html>
<html>
<head>
<meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
<title>用户登录</title>
<link rel="stylesheet" href="css/reset.css">
<link rel="stylesheet" href="css/font-awesome.min.css">
<link rel="stylesheet" href="css/loginstyle.css">
<script type="text/javascript" src="js/loginjs.js"></script>
</head>

<body>
<script src="/demos/googlegg.js"></script>

<div class="link">
	<a href="javascript:showDialog();" style="color:gray">登录</a>
</div>

<div class="ui-mask" id="mask" onselectstart="return false"></div>

<div class="ui-dialog" id="dialogMove" onselectstart='return false;'>
	<div class="ui-dialog-title" id="dialogDrag"  onselectstart="return false;" >
		用户登录
		<a class="ui-dialog-closebutton" href="javascript:hideDialog();"></a>
	</div>
	<div class="ui-dialog-content">
		<div class="ui-dialog-l40 ui-dialog-pt15">
			<input class="ui-dialog-input ui-dialog-input-username" type="input" placeholder="手机/邮箱/用户名" value="" />
		</div>
		<div class="ui-dialog-l40 ui-dialog-pt15">
			<input class="ui-dialog-input ui-dialog-input-password" type="input" placeholder="密码" value="" />
		</div>
		<div>
			<a class="ui-dialog-submit" href="#" >登 录</a>
		</div>
		<div class="ui-dialog-l40-1">
				<a href="#" style="color:gray">忘记密码</a>
				<span class="dotted"> | </span>
				<a href="#" style="color:gray">立即注册</a>
		</div>
	</div>
</div>
