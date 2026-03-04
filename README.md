<!DOCTYPE html>
<html lang="ar">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Secret</title>

<style>
body{
background:#000;
color:white;
font-family:Arial;
display:flex;
justify-content:center;
align-items:center;
height:100vh;
margin:0;
text-align:center;
}

.box{
background:#111;
padding:30px;
border-radius:15px;
width:300px;
}

input{
width:100%;
padding:10px;
margin-top:10px;
border:none;
border-radius:8px;
}

button{
margin-top:10px;
padding:10px;
width:100%;
border:none;
background:#ff2e63;
color:white;
border-radius:8px;
font-size:16px;
}

#result{
margin-top:20px;
font-size:24px;
}
</style>
</head>

<body>

<div class="box">

<h2>ادخل الباسورد</h2>

<input id="pass" type="password" placeholder="الباسورد">

<button onclick="check()">دخول</button>

<div id="result"></div>

</div>

<script>

function check(){

let password = document.getElementById("pass").value

if(password == "17/5"){

document.getElementById("result").innerHTML = "❤️ بحبك ❤️"

}else{

document.getElementById("result").innerHTML = "غلط"

}

}

</script>

</body>
</html>
