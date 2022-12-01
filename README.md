# HOME #

<!DOCTYPE html>
<html>
	<head>
		<meta charset="UTF-8">
		<title>Home - Lê Pet Shop</title>
		<link rel="stylesheet" href="reset.css">
		<link rel="stylesheet" href="home(pet).css">
	</head>

	<body>

		<h1><img src="logo-nome.png" height="300px" width="350px" alt="Logo com nome"></h1>

		<header>
			<div class="caixa">
				<nav>
					<ul>
						<li><a href="index(pet).html">Home</a></li>
						<li><a href="produtos(pet).html">Produtos</a></li>
						<li><a href="contato(pet).html">Contato</a></li>
					</ul>
				</nav>
			</div>
		</header>

		<h2 class="titulo">Sobre a Lê Pet Shop</h2> 

		<main class="textos">
			<p>Localizada no coração da cidade a <strong>Lê Pet Shop</strong> traz para o mercado o que há de melhor para o seu bichinho de etimação. Fundada em 2022, a Lê Pet Shop já é destaque na cidade e conquista novos clientes a cada dia.</p>

			<p id="missao"><em>Nossa missão é: <strong>"Proporcionar saúde e qualidade de vida aos pets"</strong>.</em></p>

			<p>Oferecemos profissionais experientes e antenados e cuidadosos com os animais. O atendimento possui padrão de excelência e agilidade, garantindo qualidade e satisfação dos nossos clientes.</p>
		</main>

		<h3><img src="cachorro.jpg" height="300px" width="400px" alt="Cachorro"></h3>

		<footer>
			<img src="logo-coracaopng.png" height="150px" width="200px" alt="Copyright">
			<p class="copyright">&copy; Copyright Lê Pet Shop - 2022</p>
		</footer>

	</body>
	
# CSS HOME #

/*css do cabeçalho */
body {
	background: #DDA0DD;
}

header {
	padding: 20px 0;
}

h1 {
	text-align: center;
	background: #BA55D3;
}

/*css da home*/
.titulo {
	text-align: center;
	top: 200px;
	margin: 30px 0 30px 0;
	color: purple;
	text-decoration: underline;
}

.textos {
	text-align: center;
	padding: 0 200px;
}

.caixa {
	text-transform: uppercase;
	position: relative;
	width: 940px;
	margin: 0 auto;
	background: #BA55D3;
}

nav {
	text-align: center;
}

nav a {
	font-size: 25px;
	text-decoration: none;
	font-weight: bold;
	color: #000000;
}

nav a:hover {
	color: #FFFAF0;
	text-decoration: underline;
}

nav li {
	display: inline;
	margin: 0 0 0 15px;
}

/*único css da home*/
h3 {		
	text-align: center;
}

/*css do rodapé*/
footer {
	text-align: center;
	background: #BA55D3;
}

.copyright {
	font-size: 20px;
}

# PRODUTOS #

<!DOCTYPE html>
<html>
	<head>
		<meta charset="UTF-8">
		<title>Produtos - Lê Pet Shop</title>
		<link rel="stylesheet" href="reset.css">
		<link rel="stylesheet" href="produtos(pet).css">
	</head>

	<body>

		<h1><img src="logo-nome.png" height="300px" width="350px" alt="Logo com nome"></h1>

		<header>
			<div class="caixa">
				<nav>
					<ul>
						<li><a href="index(pet).html">Home</a></li>
						<li><a href="produtos(pet).html">Produtos</a></li>
						<li><a href="contato(pet).html">Contato</a></li>
					</ul>
				</nav>
			</div>
		</header>

		<main>
			<ul class="produtos">
				<li>
					<h2>Ração</h2>
					<img src="racao.jpg" height="150px" width="200px">
					<p class="produto-descricao">Ração universal para todos os pets.</p>
					<p class="produto-preco">R$14,50</p>
				</li>
					
				<li>
					<h2>Banho</h2>
					<img src="banho.jpg" height="150px" width="200px">
					<p class="produto-descricao">Lavagem completa e secagem.</p>
					<p class="produto-preco">R$45,00</p>
				</li>

				<li>
					<h2>Banho e Tosa</h2>
					<img src="banho-tosa.jpg" height="150px" width="200px">
					<p class="produto-descricao">Lavegem completa, tosa e secagem.</p>
					<p class="produto-preco">R$55,00</p>
				</li>
			</ul>
		</main>

		<footer>
			<img src="logo-coracaopng.png" height="150px" width="200px" alt="Copyright">
			<p class="copyright">&copy; Copyright Lê Pet Shop - 2022</p>
		</footer>

	</body>
	
# CSS PRODUTOS #

/*css do cabeçalho*/
body {
	background: #DDA0DD;
}

header {
	padding: 20px 0;
}

h1 {
	text-align: center;
	background: #BA55D3;
}

.caixa {
	text-transform: uppercase;
	position: relative;
	width: 940px;
	margin: 0 auto;
	background: #BA55D3;
}

nav {
	text-align: center;
}

nav a {
	font-size: 25px;
	text-decoration: none;
	font-weight: bold;
	color: #000000;
}

nav li {
	display: inline;
	margin: 0 0 0 15px;
}

nav a:hover {
	color: #FFFAF0;
	text-decoration: underline;
}

/*css apenas dos produtos*/
.produtos {
	width: 940px;
	margin: 0 auto;
	padding: 50px 0;
}

.produtos li {
	display: inline-block;
	text-align: center;
	width: 30%;
	margin: 0 1%;
	border-color: #939;
	border-width: 3px;
	border-style: solid;
}

.produtos li:hover {
	border-color: #FFFAF0;
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
}

/*css do rodapé*/
footer {
	text-align: center;
	background: #BA55D3;
}

.copyright {
	font-size: 20px;
}

# CONTATO #

<!DOCTYPE html>
<html>
	<head>
		<meta charset="UTF-8">
		<title>Contato - Lê Pet Shop</title>

		<link rel="stylesheet" href="reset.css">
		<link rel="stylesheet" href="contato(pet).css">
	</head>

	<body>

		<h1><img src="logo-nome.png" height="300px" width="350px" alt="Logo com nome"></h1>

		<header>
			<div class="caixa">
				<nav>
					<ul>
						<li><a href="index(pet).html">Home</a></li>
						<li><a href="produtos(pet).html">Produtos</a></li>
						<li><a href="contato(pet).html">Contato</a></li>
					</ul>
				</nav>
			</div>
		</header>

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
			</form>

				<table>
					<thead>
						<tr>
							<th>Dia</th>
							<th>Horário</th>
						</tr>
					</thead>
					
					<tbody>
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
					</tbody>
				</table>

				<input type="submit" value="Enviar formulário" class="enviar">
			
		</main>

		<footer>
			<img src="logo-coracaopng.png" height="150px" width="200px" alt="Copyright">
			<p class="copyright">&copy; Copyright Lê Pet Shop - 2022</p>
		</footer>

	</body>
</html>

# CSS CONTATO #

/* css do cabeçalho */
body {
	background: #DDA0DD;
}

header {
	padding: 20px 0;
}

h1 {
	text-align: center;
	background: #BA55D3;
}

.titulo {
	text-align: center;
	top: 200px;
	margin: 30px 0 30px 0;
	color: #939;
	text-decoration: underline;
}

.textos {
	text-align: center;
	padding: 0 200px;
}

.caixa {
	text-transform: uppercase;
	position: relative;
	width: 940px;
	margin: 0 auto;
	background: #BA55D3;
}

nav {
	text-align: center;
}

nav a {
	font-size: 25px;
	text-decoration: none;
	font-weight: bold;
	color: #000000;
}

nav a:hover {
	color: #FFFAF0;
	text-decoration: underline;
}

nav li {
	display: inline;
	margin: 0 0 0 15px;
}

/*css do contato*/

main {
	width: 940px;
	margin: 0 auto;
}

form {
	margin: 40px 0;
}

form label, form legend {
	display: block;
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

/*css do botão enviar*/
.enviar {
	width: 20%;
	padding: 15px 0;
	margin: 10px 0;
	color: white;
	font-size: 18px;
	background: purple;
	transition: 1s background;
}

.enviar:hover {
	background: orange;
}

/*css da tabela*/
table {
	margin: 20px 0 40px;
}

thead {
	background: #BA55D3;
	color: white;
	font-weight: bold;
}

th {
	border: 1px solid #000000;
	padding: 8px 15px;
}

td {
	border: 1px solid #000000;
	padding: 8px 15px;
	background: white;
}

/*css do rodapé*/
footer {
	text-align: center;
	background: #BA55D3;
}

.copyright {
	font-size: 20px;
}
