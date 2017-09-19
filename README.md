<!DOCTYPE html>
<html>
<title>JiaYing</title>
<head>
	<meta charset="UTF-8">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>
  <script>
$(document).ready(function(){
        $("#div1").fadeIn();
        $("#div2").fadeIn("slow");
        $("#div3").fadeIn(3000);  
        $("#div4").fadeIn(4000);
});
</script>
  <style>
div {
  background-color: #FFAC12;
  color: #FFFFFF;
  font-size: 18px;
    width: 100px;
    height: 30px;
  margin: 10px;
  text-align: center;
  padding: 30px;  
  display: none;
}
div:hover {
	border-radius: 15px;
    border: 0px solid green;
}
.web_head {
	padding: 10px;
	height: 70px;
	
}
table {
	padding: 10px;
}
   </style>
</head>
<body>
<table border="1" width="50%">
	<tr>
		<td class="web_head">JiaYing_test</td>
	</tr>
</table>
<a href="#" style="text-decoration: none"><div class="box" id="div1">­個人簡介</div></a> 
<div class="box" id="div2">文宣設計</div> <br>
<div class="box" id="div3">網頁習作</div> 
<div class="box" id="div4">文字創作</div>
</body>
</html>
