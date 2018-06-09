<HTML>
	<head>
		<title>primeiro titutlo</title>
		<meta charset="utf-8">
		<style>
			body {
			margin: 0px;
			}
			.cabecalho {
				width: 100%;
				height: 150px;
				background-color: orange;
				display: -webkit-flex;
				display: flex;
				margin: 0px;
				border-bottom: solid;
			}

			.rodape {
				width: 100%;
				height: 120px;
				background-color: black;
			}
			#pesquisa {
				width: 250px;
				height: 30px;
				margin-top: 20px;
				margin-left: 60%;
				border-style: solid;
				border-radius: 10px 0 0 10px;
				background-color: #F8EBD7;
				border-color: black;
				margin-right: none;
			}
			#busca {
				width: 62px;
				height: 30px;
				margin-top:20px;
				border-radius: 0 10px 10px 0;
				background-color: black;
				border-style: solid;
				border-color: gray;
				color: white;
				font-family: cursive;
			}
			#link {
				width: 500px;
				height: 500px;
				background-color: black;
				margin-left: 50%;
			}
			#buttonmuttley {
				border-radius: 10px;
			}
			.centro {
				background-color: #ccffff;
				height: 2000px;
				margin: 0px;
				border-top: solid;
				display: flex;
				flex-direction: column;
			}
			#personagens {
				color: black;
				font-family: arial;
				margin-left: 29%;
				font-size: 40px;
				letter-spacing: 0.5em; word-spacing: 0.5em;
				margin-top: 20px;
			}



		</style>
	</head>
	<body>
		<div class="cabecalho"> <img class="fotos" src="cachorro.jpg" style="border-radius: 50%;width: 100px;height: 100px;margin-top: 25px;margin-left:30px;">
			<input id="pesquisa" placeholder="search..."></input>
			<button id="busca">Search</button>
		</div>
		<div class="centro">
			<p id="personagens"><i><b>PERSONAGENS</b></i></p>
			<img class="dog" src="muttley.jpg" style="width: 300px; height: 300px;">
			<a href="file:///C:/Users/matheus/Downloads/site1%20html/muttley.html"><button id="buttonmuttley">Muttley</button></a>

			<img  class="vigarista" src="dick vigarista.jpg" style="width: 300px; height: 300px;">
			<a href="file:///C:/Users/matheus/Downloads/site1%20html/vigarista.html"><button id="buttonmuttley">Dick vigarista</button></a>

		</div>
		<div class="rodape">
		</div>
	</body>
</html>
