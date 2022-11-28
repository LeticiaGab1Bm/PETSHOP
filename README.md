# INDEX (html 1) #

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

# CONTATO (html 2) #

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
				<label for="nomesobrenome">Nome e Sobrenome</label>
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

# PRODUTOS (html 3) #

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

# SYLE.CSS (petshop) # 

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

# INDEX JAVA #

<!DOCTYPE html>
<html lang="pt-br">
	<head>
		<meta charset="UTF-8">
		<title>Cintrole - Lê Pet Shop</title>
		<link rel="icon" href="favicon.ico" type="image/x-icon">
		<link rel="stylesheet" type="text/css" href="css/reset.css">
		<link rel="stylesheet" type="text/css" href="css/index.css">

	</head>
	<body>

		<header>
			<div class="container">
				<h2 class="titulo">Controle dos Pets</h2>
			</div>
		</header>
		<main>
			<section class="container">
				<h2>Pets</h2>
				<label for="filtrar-tabela">Filtre:</label>
				<input type="text" name="filtro" id="filtrar-tabela" placeholder="Digite o nome do pet">
				<table>
					<thead>
						<tr>
							<th>Nome</th>
							<th>Peso(kg)</th>
							<th>Raça</th>
							<th>Nome do Dono</th>
							<th>Preço</th>
						</tr>
					</thead>
					<tbody id="tabela-pacientes">
						<tr class="paciente" id="primeiro-paciente">
							<td class="info-nome">Rex</td>
							<td class="info-peso">100</td>
							<td class="info-altura">2.00</td>
							<td class="info-gordura">10</td>
							<td class="info-imc">0</td>
						</tr>

						<tr class="paciente" >
							<td class="info-nome">Bibi</td>
							<td class="info-peso">80</td>
							<td class="info-altura">1.72</td>
							<td class="info-gordura">40</td>
							<td class="info-imc">0</td>
						</tr>

						<tr class="paciente" >
							<td class="info-nome">Atlas</td>
							<td class="info-peso">54</td>
							<td class="info-altura">1.64</td>
							<td class="info-gordura">14</td>
							<td class="info-imc">0</td>
						</tr>

						<tr class="paciente">
							<td class="info-nome">Picolé</td>
							<td class="info-peso">85</td>
							<td class="info-altura">1.73</td>
							<td class="info-gordura">24</td>
							<td class="info-imc">0</td>
						</tr>
						<tr class="paciente" >
							<td class="info-nome">Marmore</td>
							<td class="info-peso">46</td>
							<td class="info-altura">1.55</td>
							<td class="info-gordura">19</td>
							<td class="info-imc">0</td>
						</tr>
					</tbody>
				</table>
				<span id="erro-ajax" class="invisivel">Erro ao buscar pet</span>

				<button id="buscar-pacientes" class="botao bto-principal">Buscar pet</button>

			</section>
		</main>

		<section class="container">
		    <h2 id="titulo-form">Adicionar novo pet</h2>
			<ul id="mensagens-erro"></ul>
		    <form id="form-adiciona">
		        <div class="">
		            <label for="nome">Nome:</label>
		            <input id="nome" name="nome" type="text" placeholder="digite o nome do pet" class="campo">
		        </div>
		        <div class="grupo">
		            <label for="peso">Peso:</label>
		            <input id="peso" name="peso" type="text" placeholder="digite o peso do pet"ss class="campo campo-medio">
		        </div>
		        <div class="grupo">
		            <label for="altura">Raça:</label>
		            <input id="altura" name="altura" type="text" placeholder="digite a raça do pet" class="campo campo-medio">
		        </div>
		        <div class="grupo">
		            <label for="altura">Nome do dono:</label>
		            <input id="altura" name="altura" type="text" placeholder="digite a raça do pet" class="campo campo-medio">
		        </div>
		        <div class="grupo">
		            <label for="gordura">Preço:</label>
		            <input id="gordura" type="text" placeholder="digite o nome do dono" class="campo campo-medio">
		        </div>

		        <button id="adicionar-paciente" class="botao bto-principal">Adicionar</button>
		    </form>
		</section>

		<script src="js/calcula-imc.js" ></script>
		<script src="js/form.js" ></script>
		<script src="js/remover-paciente.js" ></script>
		<script src="js/filtra.js" ></script>
		<script src="js/buscar-pacientes.js" ></script>

	</body>
</html>

# CALCULA IMC (preço) #

var titulo = document.querySelector(".titulo");
titulo.textContent = "Aparecida Nutricionista";

var pacientes = document.querySelectorAll(".paciente");

for (var i = 0; i < pacientes.length; i++) {

    var paciente = pacientes[i];

    var tdPeso = paciente.querySelector(".info-peso");
    var peso = tdPeso.textContent;

    var tdAltura = paciente.querySelector(".info-altura");
    var altura = tdAltura.textContent;

    var tdImc = paciente.querySelector(".info-imc");

    var pesoEhValido = validaPeso(peso);
    var alturaEhValida = validaAltura(altura);

    if (!pesoEhValido) {
        console.log("Peso inválido!");
        pesoEhValido = false;
        tdImc.textContent = "Peso inválido";
        paciente.classList.add("paciente-invalido");
    }

    if (!alturaEhValida) {
        console.log("Altura inválida!");
        alturaEhValida = false;
        tdImc.textContent = "Altura inválida";
        paciente.classList.add("paciente-invalido");
    }

    if (pesoEhValido && alturaEhValida) {
        var imc = calculaImc(peso, altura);
        tdImc.textContent = imc;
    }
}

function calculaImc(peso) {
    var imc = 0;
    preço = peso * 8 (peso * 8);

    return imc.toFixed(2);
}

function validaPeso(peso) {

    if (peso >= 0 && peso <= 1000) {
        return true;
    } else {
        return false;
    }
}

function validaAltura(altura) {

    if (altura >= 0 && altura <= 3.00) {
        return true;
    } else {
        return false;
    }
}


