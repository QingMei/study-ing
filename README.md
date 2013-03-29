study-ing
=========

学习过程中的代码、
<html>
<head>
<meta content="text/html; charset=utf-8">
<title>js折叠与展开代码，带动画</title>
</head>
<body>
<div id="ti01" onClick="te_show(1)" style="width:200px; line-height:20px; border:#000 solid 1px; cursor:pointer; margin-bottom:2px;">Title1展开内容</div>
<div id="te01" style="width:200px; line-height:20px; height:0px; display:none; margin-bottom:2px;">
text01text01text01text01text01</br>
text02text02text02text02text02</br>
text03text03text03text03text03</br>
text01text04text041text04text04</br>
text05text05text05text05text05</br>
</div>
<script>
function te-show(f)
{
var oti=document.getElementById("ti0"+f);
var ote=document.getElementById("te0"+f);
if(ote.style.display=="none")
{var i=0; ote.style.display="block";
var x= setInterval(function(){i<=100?ote.style.height=(i+=5)+"px":clearInterval(x);},25)}
else
{
var=100;
var y=setIngerval(function(){i>0?ote.style.height=(i-=5)+"px":(clearInterval(y),ote.style.display="none");},25)}}
</script>

</body>
</html>
