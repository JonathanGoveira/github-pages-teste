## Welcome to My Game Snake_Git
	<head>
		<title>Jogo Snake em HTML5</title>
		<meta http-equiv="content-language" content="pt-br" />
		<meta http-equiv="content-type" content="text/html; charset=ISO-8859-1" />	
		<link rel="stylesheet" href="default.css" type="text/css"/>
		<meta name="author" content="Danilo Augusto - maktuiu@gmail.com" />
		<meta name="description" content="Jogo simples para demonstração de funcionamento de canvas em HTML5" />
		<!--[if IE]> <script type="text/javascript" src="js/excanvas.compiled.js"></script>	<![endif]-->
		<script type="text/javascript" src="snake.js"></script>		
	</head>
	<body>
		<div id="container">
			<canvas id="canvas" width="405" height="405">
				Seu browser não suporta canvas
			</canvas>
		</div>
		<div id="box_score">
			<h1> <span id="pontos"> 0 </span>&nbsp;pontos </h1>
		</div>
		
		<div class="legenda">
			<h1>Comandos</h1>
			<p><strong>I</strong> - Iniciar;</p>
			<p><strong>P</strong> - pause;</p>
		</div>
		
	</body>
</html>
