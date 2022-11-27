# INDEX #

<!DOCTYPE html>
<html>
	<head>
		<meta charset="UTF-8">
		<title>Home - Lê Pet Shop</title>

		<link rel="stylesheet" href="reset.css">
		<link rel="stylesheet" href="style(2).css">
	</head>
	
		<header>
			<div class="caixa">
				<h1><img src="coracaopng.png"></h1>

				<nav>
					<ul>
						<li><a href="index(2).html">Home</a></li>
						<li><a href="produtos(2).html">Produtos</a></li>
						<li><a href="contato(2).html">Contato</a></li>
					</ul>
				</nav>
			</div>
		</header>

		<img class="nomeroxo" src="nomeroxo.jpg">

	<body>
		<main>
			<section class="principal">
				<h2 class="titulo-principal">Sobre a Lê Pet Shop</h2>
		 
				<p>Localizada no coração da cidade a <strong>Lê Pet Shop</strong> traz para o mercado o que há de melhor para o seu bichinho de etimação. Fundada em 2022, a Lê Pet Shop já é destaque na cidade e conquista novos clientes a cada dia.</p>

				<p id="missao"><em>Nossa missão é: <strong>"Proporcionar saúde e qualidade de vida aos pets"</strong>.</em></p>

				<p>Oferecemos profissionais experientes e antenados e cuidadosos com os pets. O atendimento possui padrão de excelência e agilidade, garantindo qualidade e satisfação dos nossos clientes.</p>
			</section>
		</main>

		<img class="cachorro" src="cachorro.jpg">

		<footer>
			<img src="logo-coracaopng.png" alt="Logo da Barbearia Alura">
			<p class="copyright">&copy; Copyright Lê Pet Shop - 2022</p>
		</footer>
	</body>
</html>

# PODUTOS #

<!DOCTYPE html>
<html>
	<head>
		<meta charset="UTF-8">
		<title>Produtos - Lê Pet Shop</title>

		<link rel="stylesheet" href="reset.css">
		<link rel="stylesheet" href="style(2).css">
	</head>

		<header>
			<div class="caixa">
				<h1><img src="coracaopng.png"></h1>

				<nav>
					<ul>
						<li><a href="index(2).html">Home</a></li>
						<li><a href="produtos(2).html">Produtos</a></li>
						<li><a href="contato(2).html">Contato</a></li>
					</ul>
				</nav>
			</div>
		</header>

	<body>
		<main>
			<ul class="produtos">
				<li>
					<h2>Ração</h2>
					<img src="racao.jpg">
					<p class="produto-descricao">Ração universal para todos os animais. (informar espécie no pedido)</p>
					<p class="produto-preco">R$ 14,50 Kg</p>
				</li>
				<li>
					<h2>Banho</h2>
					<img src="banho.jpg">
					<p class="produto-descricao">Seu pet volta cherosinho com um acessório.</p>
					<p class="produto-preco">R$ 30,00</p>
				</li>
				<li>
					<h2>Banho + Tosa</h2>
					<img src="banho-tosa.jpg">
					<p class="produto-descricao">Pacote completo de banho e tosa, incluindo acessório.</p>
					<p class="produto-preco">R$ 40,00</p>
				</li>
			</ul>
		</main>

		<footer>
			<img src="logo-coracaopng.png" alt="Logo da Lê Pet Shop">
			<p class="copyright">&copy; Copyright Lê Pet Shop - 2022</p>
		</footer>
	</body>
</html>

# CONTATO #

<!DOCTYPE html>
<html>
	<head>
		<meta charset="UTF-8">
		<title>Contato - Lê Pet Shop</title>

		<link rel="stylesheet" href="reset.css">
		<link rel="stylesheet" href="style(2).css">
	</head>

		<header>
			<div class="caixa">
				<h1><img src="coracaopng.png"></h1>

				<nav>
					<ul>
						<li><a href="index(2).html">Home</a></li>
						<li><a href="produtos(2).html">Produtos</a></li>
						<li><a href="contato(2).html">Contato</a></li>
					</ul>
				</nav>
			</div>
		</header>

	<body>
		<main>
			<form>
				<label for="nomesobrenome">Nome e sobrenome</label>
				<input type="text" id="nomesobrenome" class="input-padrao" required>

				<label for="email">Email</label>
				<input type="email" id="email" class="input-padrao" required placeholder="seuemail@dominio.com">

				<label for="telefone">Telefone</label>
				<input type="tel" id="telefone" class="input-padrao" required placeholder="(XX) XXXXX-XXXX">

				<label for="mensagem">Mensagem</label>
				<textarea cols="70" rows="10" id="mensagem" class="input-padrao" required></textarea>

				<fieldset>
					<legend>Como prefere o nosso contato?</legend>
					<label for="radio-email"><input type="radio" name="contato" value="email" id="radio-email"> Email</label>
					
					<label for="radio-telefone"><input type="radio" name="contato" value="telefone" id="radio-telefone"> Telefone</label>
					
					<label for="radio-whatsapp"><input type="radio" name="contato" value="whatsapp" id="radio-whatsapp" checked> WhatsApp</label>
				</fieldset>

				<fieldset>
					<legend>Qual horário prefere ser atendido?</legend>
					<select>
						<option>Manhã</option>
						<option>Tarde</option>
						<option>Noite</option>
					</select>
				</fieldset>

				<label class="checkbox"><input type="checkbox" checked>Gostaria de receber nossas novidades por email?</label>

				<input type="submit" value="Enviar formulário" class="enviar">
			</form>

			<table>
				<tr>
					<td>Dia</td>
					<td>Horário</td>
				</tr>
				<tr>
					<td>Segunda</td>
					<td>8h ~ 20h</td>
				</tr>
				<tr>
					<td>Quarta</td>
					<td>8h ~ 20h</td>
				</tr>
				<tr>
					<td>Sexta</td>
					<td>8h ~ 20h</td>
				</tr>
			</table>
		</main>

		<footer>
			<img src="~coracaopng.png" alt="Logo da Lê Pet Shop">
			<p class="copyright">&copy; Copyright Lê Pet Shop - 2022</p>
		</footer>
	</body>
</html>

# SYLE.CSS # 

body {
	font-family: 'Montserrat', sans-serif;
}

header {
	background: 939;
	padding: 20px 0;
}

.caixa {
	position: relative;
	width: 940px;
	margin: 0 auto;
}

.dados {
	width: 940px;
	margin: 0 auto;
	padding: 50px 0;
}

nav {
	position: absolute;
	top: 110px;
	right: 0;
}

nav li {
	display: inline;
	margin: 0 0 0 15px;
}

nav a {
	text-transform: uppercase;
	color: #000000;
	font-weight: bold;
	font-size: 22px;
	text-decoration: none;
}

nav a:hover {
	color: #C78C19;
	text-decoration: underline;
}

.produtos {
	width: 940px;
	margin: 0 auto;
	padding: 50px 0;
}

.produtos li {
	display: inline-block;
	text-align: center;
	width: 30%;
	vertical-align: top;
	margin: 0 1.5%;
	padding: 30px 20px;
	box-sizing: border-box;
	border: 2px solid #000000;
	border-radius: 10px;
}

.produtos li:hover {
	border-color: #C78C19;
}

.produtos li:active {
	border-color: #088C19;	
}

.produtos li:hover h2 {
	font-size: 34px;
}

.produtos h2 {
	font-size: 30px;
	font-weight: bold;
}

.produto-descricao {
	font-size: 18px;
}

.produto-preco {
	font-size: 22px;
	font-weight: bold;
	margin-top: 10px;
}

footer {
	text-align: center;
	background: url("bg.jpg");
	padding: 40px 0;
}

.copyright {
	color: #FFFFFF;
	font-size: 13px;
	margin: 20px 0 0;
}

form {
	margin: 40px 0;
}

form label, form legend {
	display:block;
	font-size: 20px;
	margin: 0 0 10px;
}

.input-padrao {
	display: block;
	margin: 0 0 20px;
	padding: 10px 25px;
	width: 50%;
}

.checkbox {
	margin: 20px 0;
}

.enviar {
	width:40%;
	padding: 15px 0;
	background: orange;
	color: white;
	font-weight: bold;
	font-size: 18px;
	border: none;
	border-radius: 5px;
	transition: 1s all;
	cursor: pointer;
}

.enviar:hover {
	background: darkorange;
	transform: scale(1.2);
}

table {
	margin: 20px 0 40px;
}

thead {
	background: #555555;
	color: white;
	font-weight: bold;
}

td, th {
	border: 1px solid #000000;
	padding: 8px 15px;
}


/* css da página inicial */
.nomeroxo {
	width:100%;
}

.titulo-principal {
	text-align: center;
	font-size: 2em;
	margin: 0 0 1em;
	clear: left;
}

.principal {
	padding: 3em 0;
	background: #FEFEFE;
	width: 940px;
	margin: 0 auto;
}

.principal p {
	margin: 0 0 1em;
}

.principal strong {
	font-weight: bold;
}

.principal em {
	font-style: italic;
}

.cachorro {
	width: 940px;
	margin: 0 auto;
	padding: 50px 0;
}









