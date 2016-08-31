# Java1203
<!DOCUMENT html>
<html>
<head>
		<script type="text/javascript">
			
		function restar(num1,num2)
		{
			var r= Number(num1)-Number(num2);
			alert(r);
		}
		function sumar(num1,num2)
		{
			var r= Number(num1)+ Number(num2);
			alert(r);
		}
		function dividir(num1,num2)
		{
			var r= Number(num1)/ Number(num2);
			alert(r);
		}
		function multiplicar(num1,num2)
		{
			var r= Number(num1)*Number(num2);
			alert(r);
		}

		</script>
</head>
<body>
	
		<div>
			
			<input id="num1" type="text"/>
			<input id="num2" type="text"/>
			<br>
			<br>
			<input type="button" onclick="sumar(document.getElementById('num1').value,document.getElementById('num2').value);
			" value="sumar"/>

			<input type="button" onclick="restar(document.getElementById('num1').value,document.getElementById('num2').value);
			" value="restar"/>

			<input type="button" onclick="dividir(document.getElementById('num1').value,document.getElementById('num2').value);
			" value="dividir"/>

			<input type="button" onclick="multiplicar(document.getElementById('num1').value,document.getElementById('num2').value);
			" value="multiplicar"/>





		</div>

</body>
