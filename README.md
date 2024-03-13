<html><head>
	<title>Calculator</title>
	<style>
		body {
			background-image:linear-gradient(45deg,black,rgb(106, 104, 104),rgb(213, 213, 213),rgb(106, 104, 104),black);
			font-family: Arial, sans-serif;
            background-position: center;
            background-repeat: no-repeat;
            height: 640px;
            float: center;
			overflow-y: hidden;
		}
		#calculator {
			margin: 0 auto;
			width: 320px;
			background-color: #303131;
			padding: 20px;
			border-radius: 10px;
			box-shadow: 0 0 10px rgb(0, 0, 0);
		}
		h1 {
			text-align: center;
			font-size: 36px;
			margin-bottom: 20px;
		}
		input[type="button"] {
			width: 64px;
			height: 64px;
			font-size: 24px;
			background-color: #4caaaf;
			color: #fff;
			border: none;
			border-radius: 5px;
			cursor: pointer;
			margin: 5px;
			box-shadow: 0 0 5px rgba(0,0,0,0.2);
		}
		input[type="text"] {
			width: 100%;
			height: 50px;
			font-size: 24px;
			padding: 5px;
			margin-bottom: 10px;
			border-radius: 5px;
			border: none;
			box-shadow: 0 0 5px rgb(0, 0, 0);
			
		}
		
		input[type="button"]:active {
			box-shadow: 0 0 2px rgba(0,0,0,0.2);
			transform: translateY(2px);
		}
        #btn{
            box-shadow: 2px 5px 5px rgb(0, 0, 0) ;
            border-radius: 1rem;
			background-color: #303131;;
			
        }
		#btn:hover{
            background-color: #3e5b8e;
		}
        #cull{
            text-shadow: 2px 5px 5px rgb(1, 1, 42) ;
			color:white;
			float:center;
        }
		#cull:hover{
			color:green;
		}
	</style>
</head>
<body>
	<div id="calculator">
		<h1 id="cull">Calculator</h1>
		<input style="width:auto;float:center;margin-left:7px;" type="text" id="result" readonly="">
		<input type="button" id="btn" value="1" onclick="document.getElementById('result').value += '1'">
		<input type="button" id="btn" value="2" onclick="document.getElementById('result').value += '2'">
		<input type="button" id="btn" value="3" onclick="document.getElementById('result').value += '3'">
		<input type="button" id="btn" value="+" onclick="document.getElementById('result').value += '+'">
		<br>
		<input type="button" id="btn" value="4" onclick="document.getElementById('result').value += '4'">
		<input type="button" id="btn" value="5" onclick="document.getElementById('result').value += '5'">
		<input type="button" id="btn" value="6" onclick="document.getElementById('result').value += '6'">
		<input type="button" id="btn" value="-" onclick="document.getElementById('result').value += '-'">
		<br>
		<input type="button" id="btn" value="7" onclick="document.getElementById('result').value += '7'">
		<input type="button" id="btn" value="8" onclick="document.getElementById('result').value += '8'">
		<input type="button" id="btn" value="9" onclick="document.getElementById('result').value += '9'">
		<input type="button" id="btn" value="*" onclick="document.getElementById('result').value += '*'">
		<br>
		<input type="button" id="btn" value="C" onclick="document.getElementById('result').value = ''">
		<input type="button" id="btn" value="0" onclick="document.getElementById('result').value += '0'">
		<input type="button" id="btn" value="=" onclick="document.getElementById('result').value = eval(document.getElementById('result').value)">
		<input type="button" id="btn" value="/" onclick="document.getElementById('result').value += '/'">
	</div>


</body></html>
