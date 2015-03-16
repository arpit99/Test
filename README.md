# Test
<HTML>
<head>
<script>
function validate()
{
	if(document.form.username.value=="Arpit" && document.form.password.value=="Arpit@123")
		return true;
	else
		return false;
	
}
</script>
</head>
<body bgcolor='cyan' onsubmit="return validate()" >

<center>
<img src="image.jpg"/>
<h1>Welcome to Brillio Portal </h1>
<br>
<br>
<br>
<form action="home.html" name="form">
<table>
<tr><td>Username</td>
<td><input type="text" name="username"/>
</td></tr>
<tr><td>
Password</td>
<td><input type="password" name="password"/>
</td></tr>
<tr><td>
</td>
<td><input type="submit" value="Login" onSubmit=return validate()/>
</td>
</table>
</form>
</center>


</body>
</html>
