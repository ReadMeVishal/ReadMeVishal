# ReadMeVishal
Portfolio

<!DOCTYPE html>
<html>
<head>
	<title>RGB Color Game</title>
	<style type="text/css">
		body{
			background-color: #232323;
			margin: 0;
			font-family: "Montserrat","Avenir";
		}

		h1{
			color: white;
			text-align: center;
			background: steelblue;
			margin: 0;
			text-transform: uppercase;
			font-weight: normal;
			line-height: 1.1;
			padding: 20px 0;
		}

		#msg{
			display: inline-block;
			width: 20%;
		}

		#colorDisp{
			font-size: 200%;
		}

		button{
			border: none;
			background: none;
			text-transform: uppercase;
			height: 100%;
			font-weight: 700;
			color: steelblue;
			letter-spacing: 1px;
			font-size: inherit;
			/*transition property takes two arguments 
			1st one for whenan and the 2nd one is time to transition in seconds*/
			transition: all 0.3s;
			outline: none;
		}

		button:hover{
			color: white;
			background: steelblue;
		}

		.square{
			width: 30%;
			background: green;
			padding-bottom: 30%;
			float: left;
			margin: 1.66%;
			border-radius: 15%;
			transition: background 0.5s;
			-webkit-transition: background 0.5s;
			-moz-transition: background 0.5s;
		}

		#container{
			max-width: 600px;
			margin: 20px auto;
		}

		#stripe{
			text-align: center;
			background: white;
			height: 21px;
			color: black;
		}

		.selected{
			color: white;
			background: steelblue;
		}

	</style>
</head>
<body>
	<h1>
		The Great<br> <span id="colorDisp"></span> <br>Color Game
	</h1>

	<div id="stripe">
		<button id='reset'>New Colors</button>
		<span id="msg"></span>
		<button class="level">Easy</button>
		<button  class="level selected">Hard</button>
	</div>

	<div id="container">
		<div class="square"></div>
		<div class="square"></div>
		<div class="square"></div>
		<div class="square"></div>
		<div class="square"></div>
		<div class="square"></div>
	</div>
	<script type="text/javascript">
		
	</script>
</body>
</html>

