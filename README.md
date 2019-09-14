# calculator

<!DOCTYPE html>

<html>
<head>
<title>calculator</title>
<style>

body{

background color:#badbc3;
margin-left:200px;
margin-top:100pcx;
}

table{

width:250px;
height:220px;
background-color:#08571c;
}

#display
{
width:230px;
height:20px;
background-color:#f2fac3;
text-align:center;
color:blue;
}

tr{

background-color:#b7f7f7;
}

input:hover{

background-color:red;
color:white;
width:38px;
height:24px;
}

</style>
</head>

<body>

<div id="clc" align="center">

<form name="calculator" align="center">

<table border="1">
<tr>
<td colspan="4">
<input type="text" name="answer" id="display" disabled>
</td>
</tr>

<tr>

<td><input type="button" value="  1  " onclick="calculator.display.value+='1'"></td>

<td><input type="button" value="  2  " onclick="calculator.display.value+='2'"></td>
 
<td><input type="button" value="  3  " onclick="calculator.display.value+='3'"></td>

<td><input type="button" value="  -  " onclick="calculator.display.value+='-'"></td>

</tr>

<tr>

<td><input type="button" value="  4  " onclick="calculator.display.value+='4'"></td>

<td><input type="button" value="  5  " onclick="calculator.display.value+='5'"></td>
 
<td><input type="button" value="  6  " onclick="calculator.display.value+='6'"></td>

<td><input type="button" value="  +  " onclick="calculator.display.value+='+'"></td>

</tr>

<tr>

<td><input type="button" value="  7  " onclick="calculator.display.value+='7'"></td>

<td><input type="button" value="  8  " onclick="calculator.display.value+='8'"></td>
 
<td><input type="button" value="  9  " onclick="calculator.display.value+='9'"></td>

<td><input type="button" value="  *  " onclick="calculator.display.value+='*'"></td>

<tr>

<td><input type="button" value="  0  " onclick="calculator.display.value+='0'"></td>

<td><input type="button" value="  =  " onclick="calculator.display.value=eval(calculator.display.value)"></td>
 
<td><input type="button" value="  C  " onclick="calculator.display.value=''"></td>

<td><input type="button" value="  /  " onclick="calculator.display.value+='/'"></td>

</tr>

</tr>

</table>
</form>
</div>
</body>
</html>
