# Simple-Calculator
-----------------------------A calculator using HTML and CSS------------------------------------------------------

<html>
<head>
<title>CALCULATOR HOSTED THROUGH AWS</title>
<style>
.formstyle{
 width:250px;
 height:390px;
 margin:auto;
 border:2px solid black;
}

input{
 width:80px;
 height:40px;
 background-color:orange;
 
 font-size:30px;
 color:black;
 border-bottom:1px red;
 
}

#finalanswer{
 width:250px;
}

#clearbutton{
 width:250px;
}

</style>
</head>
<body>
<div class="formstyle">
<form name="formCalci">

<input type="text" name="answers"  id="finalanswer"> <br> </br>

<input type="button" value="1" onclick="formCalci.answers.value += '1' " >
<input type="button" value="2" onclick="formCalci.answers.value += '2' " >  
<input type="button" value="3" onclick="formCalci.answers.value += '3' " >


<br> </br>

<input type="button" value="4" onclick="formCalci.answers.value += '4' " >
<input type="button" value="5" onclick="formCalci.answers.value += '5' " >
<input type="button" value="6" onclick="formCalci.answers.value += '6' " >


<br> </br>

<input type="button" value="7" onclick="formCalci.answers.value += '7' " >
<input type="button" value="8" onclick="formCalci.answers.value += '8' " >
<input type="button" value="9" onclick="formCalci.answers.value += '9' " >

<br> </br>

<input type="button" value="+" onclick="formCalci.answers.value += '+' " >
<input type="button" value="-" onclick="formCalci.answers.value += '-' " >
<input type="button" value="/" onclick="formCalci.answers.value += '/' " >

<br></br>

<input type="button" value="0" onclick="formCalci.answers.value += '0' " >
<input type="button" value="*" onclick="formCalci.answers.value += '*' " >
<input type="button" value="="onclick="formCalci.answers.value = eval(formCalci.answers.value) " >
<br> </br>

<input type="button" value="Clear All" id="clearbutton" onclick="formCalci.answers.value = '' " >


</form>
</div>
</body>
</html>
