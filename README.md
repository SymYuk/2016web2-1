<!DOCTYPE html>

<html lang="jp">
	<head>
		<meta charset="UTF-8"/>
		<title>はろーじぇーくえりぃ</title>
		<script type="text/javascript" src="https://code.jquery.com/jquery-3.1.0.min.js"></script>
		<script type="text/javascript">
			$(function(){
				$('#hey').mouseover(function () {
					$(this).css('background-color','#55ff33');
 				});
				$('#hey').mouseout(function () {
   					$(this).css('background-color','#ffffff');
				});
			});
		</script>
	</head>
	<body>
		<div id="hey">マウスオンしていると緑くなります</div>
		<p><sup>なんだこれ</sup></p>
		<footer>
			&copy 2016 g1527043
		</footer>
	</body>
</html>
