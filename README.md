<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
<head>
<meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
<title>Başlıksız Belge</title>
<script>
var a=0;
function kapat()
{
	
	if(a==0)
	{
		document.getElementById("syh").src="img/belgesel.png"
		a=1;
	}
	else if(a==1)
	{
		document.getElementById("syh").src="img/siyah.jpg"
		a=0;
	}
}

function tus1()
{
if(a==1)	document.getElementById("syh").src="img/belgesel.jpg";
}
function tus2()
{
if(a==1)	document.getElementById("syh").src="img/koro.jpg";
}
function tus3()
{
if(a==1)	document.getElementById("syh").src="img/yarisma.jpg";
}

</script>
<style type="text/css">
body {
	background-color: #000;
}
#televizyon {
	background-image: url(img/tv.png);
	margin-right: auto;
	margin-left: auto;
	height: 333px;
	width: 500px;
	
}
#televizyon img {
	width: 480px;
	height: 270px;
	margin-top: 10px;
	margin-left: 10px;
}
#kumanda {
	background-image: url(img/kumanda.png);
	height: 300px;
	width: 80px;
	margin-right: auto;
	margin-left: auto;
}
#kapa {
	height: 20px;
	width: 20px;
	margin-top: 10px;
	margin-left: 7px;
	cursor: pointer;
}
#k1 {
	height: 18px;
	width: 20px;
	margin-left: 7px;
	margin-top: 5px;
	float: left;
	cursor: pointer;
}
#k2 {
	float: left;
	height: 18px;
	width: 20px;
	margin-top: 5px;
	margin-left: 3px;
	cursor: pointer;
}
#k3 {
	float: left;
	height: 18px;
	width: 20px;
	margin-top: 5px;
	margin-left: 3px;
	cursor: pointer;
}
</style>
</head>

<body>
<div id="televizyon"><img src="img/siyah.jpg" width="491" height="274" id="syh"/></div>
<div id="kumanda">
  <div id="kapa" onclick="kapat()"></div>
  <div id="k1" onclick="tus1()"></div>
  <div id="k2" onclick="tus2()"></div>
  <div id="k3" onclick="tus3()"></div>
</div>
</body>
</html>
