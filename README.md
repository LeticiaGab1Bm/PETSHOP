# HTML 1 #

<!DOCTYPE html>
<html lang="pt-br">
	<head>
		<meta charset="UTF-8">
		<meta name="viewport" content="width=device-width">
		<title>Lê Pet Shop</title>

		<link rel="stylesheet" href="reset.css">
		<link rel="stylesheet" href="style.css">
		<link href="https://fonts.googleapis.com/css?family=Montserrat:wght@200&display=swap" rel="stylesheet">
	</head>

	<body>
		<header>
			<div class="caixa">
				<h1><img src="logo-arranhao.png"></h1>

				<nav>
					<ul>
						<li><a href="index.html">Home</a></li>
						<li><a href="produtos.html">Produtos</a></li>
						<li><a href="contato.html">Contato</a></li>
					</ul>
				</nav>
			</div>
		</header>

		<img class="banner" src="gatoecachorro.jpg">

		<main>
			<section class="principal">
				<h2 class="titulo-principal">Sobre a Lê Pet Shop</h2>

				<img class="utensilios" src="utensilios.jpg" alt="Utensilios de um barbeiro">
		 
				<p>Localizada no coração da cidade a <strong>Lê Pet Shop</strong> traz para o mercado o que há de melhor para o seu bichinho de estimação. Fundada em 2022, a Lê Pet Shop já é destaque na cidade e conquista novos clientes a cada dia.</p>

				<p id="missao"><em>Nossa missão é: <strong>"Proporcionar saúde e qualidade de vida aos pets"</strong>.</em></p>

				<p>Oferecemos profissionais experientes e antenados. O atendimento possui padrão de excelência e agilidade, garantindo qualidade e satisfação dos nossos clientes.</p>
			</section>

			<section class="mapa">
				<h3 class="titulo-principal">Nosso Estabelecimento</h3>
				<p>Nosso estabelecimento está localizado no coração da cidade.</p>

				<div class="mapa-conteudo">
					<iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3657.106693514147!2d-46.65391084917274!3d-23.564611267522842!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x94ce59541c6c79c3%3A0x36b90a85f0f8cb33!2sGrupo%20Alura!5e0!3m2!1spt-BR!2sbr!4v1663113024050!5m2!1spt-BR!2sbr" width="100%" height="300" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
				</div>

			</section>

			<section class="beneficios">
				<h3 class="titulo-principal">Benefícios</h3>
				<div class="conteudo-beneficios">
					<ul class="lista-beneficios">
						<li class="itens">Atendimento aos Clientes</li>
						<li class="itens">Espaço diferenciado</li>
						<li class="itens">Localização</li>
						<li class="itens">Profissionais Qualificados</li>
						<li class="itens">Pontualidade</li>
						<li class="itens">Limpeza</li>
					</ul><img src="beneficios.jpg" class="imagem-beneficios">
				</div>
				
			</section>
		</main>

		<footer>
			<img src="logo-branco.png">
			<p class="copyright">&copy; Copyright Barbearia Alura - 2019</p>
		</footer>
	</body>
</html>
