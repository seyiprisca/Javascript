# Javascript
few javascript works
<html>
<head>
 <link rel="stylesheet" href="bootstrap.css">
<script src="jquery.js"></script>
<script src= "bootstrap.js"></script>
<script type="text/javascript">
function sum(){
 var num1 = parseInt(document.getElementById("firstNumber").value);
  var num2 = parseInt(document.getElementById("secondNumber").value);
  var summ = num1 + num2;
  document.getElementById("summ").value = summ
 
}

</script>
</head>
<body>
<div class="container"> 
<form>
Num1:<br>
<input class="form-control" type="text" name="" id="firstNumber">
<br>
Num2:<br>
<input class="form-control" type="text" name="secondNumber" id ="secondNumber">
<br>
Sum:<br>
<input class="form-control" type="text" name="summ" id="summ">
<button onclick="sum()" type="button" class="btn btn-danger" value="sum">Sum</button>
</form>
</div>
</body>
</html>
