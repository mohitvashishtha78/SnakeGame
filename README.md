<!DOCTYPE html>
<html>
<head>
	<title>Snake Game</title>
	<link rel="shortcut icon" href="icon.ico">
	<link rel="stylesheet" type="text/css" href="snakestyle.css">
</head>
<body>

	<div class="snake__game">
		<div class="game__canvas">
			<canvas id= "snake" height="608" width="608"></canvas>
		</div>
		
		<div class="game__score">
			<div id="scoring" class="points">Score: 0</div>
		</div>	
		<div id="end" class="gameover"></div>
	</div>

	
	
	<script type="text/javascript" src="snake.js"></script>
</body>
</html>
