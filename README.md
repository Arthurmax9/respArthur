<!DOCTYPE html>
<html>
<head>
	<title>Captura de Dados</title>
	<style>
		body {
			background-color: darkgreen;
			color: white;
			font-family: Arial, sans-serif;
		}

		.container {
			max-width: 600px;
			margin: 0 auto;
			padding: 20px;
			background-color: rgba(0, 0, 0, 0.7);
			border-radius: 10px;
		}

		h1 {
			font-size: 36px;
			font-weight: bold;
			text-align: center;
			margin-bottom: 20px;
			color: #00cc66;
		}

		input[type=text], input[type=email], input[type=tel] {
			width: calc(100% - 24px);
			padding: 10px;
			margin: 0 0 20px 0;
			border-radius: 5px;
			border: none;
			background-color: rgba(255, 255, 255, 0.7);
			color: black;
			font-size: 16px;
			font-weight: bold;
			box-sizing: border-box;
		}

		button[type=submit] {
			display: block;
			width: calc(100% - 24px);
			padding: 10px;
			margin: 0 0 20px 0;
			border-radius: 5px;
			border: none;
			background-color: #00cc66;
			color: white;
			font-size: 16px;
			font-weight: bold;
			cursor: pointer;
			box-sizing: border-box;
		}

		button[type=submit]:hover {
			background-color: #008040;
		}
	</style>
</head>
<body>
	<div class="container">
		<h1>Captura de Dados</h1>
		<form>
			<label for="nome">Nome:</label>
			<input type="text" id="nome" name="nome" required>

			<label for="email">E-mail:</label>
			<input type="email" id="email" name="email" required>

			<label for="telefone">Telefone:</label>
			<input type="tel" id="telefone" name="telefone" required>

			<button type="submit">Enviar</button>
		</form>
	</div>
</body>
</html>
