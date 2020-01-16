<html>
	<head>
		<title>Portal</title>
		<meta charset="UTF-8" />
		<meta id="viewport" name="viewport" content="width=device-width, user-scalable=no" />
		<link href="assets/css/style.css" rel="stylesheet" />
		<script type="text/javascript" src="assets/js/script.js"></script>
	</head>
	<body>
		<div class="topo">
			<div class="topoint">
				<div class="topoleft">
					<ul>
						<li><a href="./" class="ativo">Home</a></li>
						<li><a href="quem somos">Quem Somos</a></li>
						<li><a href="anuncie aqui">Anuncie Aqui</a></li>
						<li><a href="contatos">Contatos</a></li>
					</ul>
				</div>
				<div class="toporight">
					<input type="Image" src="assets/imagens/lupa_branca2.png" title="Pesquisa" border="0" width="26" height="26" />
					<input type="text" name="busca" class="topobusca" placeholder="Busca..." />
					<a href=""><img src="assets/imagens/youtube.png" title="Youtube" border="0" width="26" height="26" /></a>
					<a href=""><img src="assets/imagens/Twitter2.png" title="Twitter" border="0" width="26" height="26" /></a>
					<a href=""><img src="assets/imagens/facebook.png" title="Facebook" border="0" width="26" height="26" /></a>
					<a href=""><img src="assets/imagens/google_plus.png" title="Google Plus" border="0" width="26" height="26" /></a>
					<a href=""><img src="assets/imagens/rss3.png" title="RSS3" border="0" width="26" height="26" /></a>
				</div>
			</div>
		</div>
		<div class="topo2">
			<div class="topoint2">
				<div class="logo">
					<img src="assets/imagens/mega_portal2.jpg" border="0" width="230" title="Logo" />
				</div>
				<div class="banner">

				</div>
			</div>
		</div>
		<div class="menu">
			<div class="menuint">
				<img src="assets/imagens/menu.png" border="0" width="40" height="40" class="menumobile" onclick="toggleMenu()" />
				<ul id="menu">
					<li><a href="./" class="ativo">Home</a></li>
					<li><a href="./">Economia</a></li>
					<li>
						<a href="./">Entretenimento</a>
						<img src="assets/imagens/setinha2.png" border="0" width="10" />
						<div class="submenu">
							<a href="./"><div class="submenuitem">Cultura</div></a>
							<a href="./"><div class="submenuitem">Cinema</div></a>
							<a href="./"><div class="submenuitem">Moda</div></a>
							<a href="./"><div class="submenuitem">Música</div></a>
						</div>
					</li>
					<li>
						<a href="./">Esportes</a>
						<img src="assets/imagens/setinha2.png" border="0" width="10" />
						<div class="submenu">
							<a href="./"><div class="submenuitem">Futebol</div></a>
							<a href="./"><div class="submenuitem">Basquete</div></a>
							<a href="./"><div class="submenuitem">Outros...</div></a>
						</div>
					</li>
					<li><a href="./">Geral</a></li>
					<li>
						<a href="./">Noticias</a>
						<img src="assets/imagens/setinha2.png" border="0" width="10" />
						<div class="submenu">
							<a href="./"><div class="submenuitem">Politica</div></a>
							<a href="./"><div class="submenuitem">Policia</div></a>
						</div>
					</li>
					<li><a href="./">Polícia</a></li>
					<li><a href="./">Videos</a></li>
				</ul>
			</div>
		</div>
		<div class="ultimasnoticias">
			<div class="ultimasnoticiasint">
				<div class="barrabranca">
					<div class="titulobarra">
						ÚLTIMAS NOTÍCIAS
					</div>
					<div class="ultnoticias">
						Criador da internet teme a perda de todas as nossas memórias digitais no futuro.
					</div>
				</div>
			</div>
		</div>
		<div class="container">
			<div class="containerint">
				<div class="leftside">
					<div class="slideshow" id="slideshow">
						<div class="slidebotao">
							<div class="botao" onclick="mudarSlide(0)"></div>
							<div class="botao" onclick="mudarSlide(1)"></div>
							<div class="botao" onclick="mudarSlide(2)"></div>
							<div class="botao" onclick="mudarSlide(3)"></div>
						</div>
						<div class="slideshowarea">
							<a href="./">
								<div class="slide" style="background-image:url('assets/imagens/elseworlds.jpg')" border="0" width="100%" height="335" >
									<div class="slideinfo">
										<div class="slideinfo_titulo">Crossover da CW, "Crise nas Infinitas Terras" pode incluir Lúcifer!</div>
										<div class="slideinfo_subtitulo">O crossover Crise nas Infinitas Terras segue rendendo encontros entre os atores das séries do Arrowverso, mas um novo rumor pode ter expandido ainda mais o alcance dos episódios.</div>
									</div>
								</div>
							</a>
							<a href="./">
								<div class="slide" style="background-image:url('assets/imagens/desenhos.jpg')" border="0" width="100%" height="335" >
									<div class="slideinfo">
										<div class="slideinfo_titulo">Artista do Maranhão faz sucesso com seus desenhos.</div>
										<div class="slideinfo_subtitulo">Jovem faz desenhos de personagens famosos da cultura pop, usando PhotoFiltre.</div>
									</div>
								</div>
							</a>
							<a href="./">
								<div class="slide" style="background-image:url('assets/imagens/superman.jpg')" border="0" width="100%" height="335" >
									<div class="slideinfo">
										<div class="slideinfo_titulo">Superman vai ganhar novos poderes!!!</div>
										<div class="slideinfo_subtitulo">A DC Comics pretende dá novos poderes para o seu maior herói em nova Hq.</div>
									</div>
								</div>
							</a>
							<a href="./">
								<div class="slide" style="background-image:url('assets/imagens/cartago.jpg')" border="0" width="100%" height="335" >
									<div class="slideinfo">
										<div class="slideinfo_titulo">Power Rangers vai ganhar um novo arco feito pela BOOM! studio.</div>
										<div class="slideinfo_subtitulo">Os heróis vão ganhar novos histórias já em novembro desse ano.</div>
									</div>
								</div>
							</a>
						</div>
					</div>
					<div class="widget">
						<div class="widget_titulo">
							NOTÍCIAS
						</div>
						<div class="widget_conteudo">
							<div class="noticiaarea1">
								<a href="./">
									<div class="noticiaitem noticiabig">
										<div class="noticiaimagem">
											<img src="assets/imagens/quadrilha.jpg" border="0" width="80" height="80" />
										</div>
										<div class="noticiatitulo">
											Polícia Militar prende quadrilha com drogas e metralhadora na zona norte de Teresina.
										</div>
										<div class="noticiainfo">
											23 dia atrás	deixe um comentário.
										</div>
									</div>
								</a>
							</div>
							<div class="noticiaarea2">
								<a href="./">
									<div class="noticiaitem">
										<div class="noticiaimagem">
											<img src="assets/imagens/jogo.jpg" border="0" width="80" height="80" />
										</div>
										<div class="noticiatitulo">
											Em retorno ao Minerão, Cruzeiro empata por 1 x 1 com a Caldense no Campeonato Mineiro.
										</div>
										<div class="noticiainfo">
											5 dias atrás	deixe um comentário.
										</div>
									</div>
								</a>
								<a href="./">
									<div class="noticiaitem">
										<div class="noticiaimagem">
											<img src="assets/imagens/Barack Obama.jpg" border="0" width="80" height="80" />
										</div>
										<div class="noticiatitulo">
											Barack Obama é fragado tirando foto com o "pau de selfie"
										</div>
										<div class="noticiainfo">
											8 dias atrás	deixe um comentário.
										</div>
									</div>
								</a>
								<a href="./">
									<div class="noticiaitem">
										<div class="noticiaimagem">
											<img src="assets/imagens/Vint Cerf-um dos pais da web.jpg" border="0" width="80" height="80" />
										</div>
										<div class="noticiatitulo">
											Criador da internet teme a perda de todas as nossas mémorias digitais no futuro.
										</div>
										<div class="noticiainfo">
											15 dias atrás	deixe um comentário.
										</div>
									</div>
								</a>
								<a href="./">
									<div class="noticiaitem">
										<div class="noticiaimagem">
											<img src="assets/imagens/Chinelo Cartago Malta.jpg" border="0" width="80" height="80" />
										</div>
										<div class="noticiatitulo">
											Novo modelo da sandália está próximo de ser lançado, diz chefe da MALTA.
										</div>
										<div class="noticiainfo">
											15 dias atrás	deixe um comentário.
										</div>
									</div>
								</a>
							</div>
							<div style="clear:both"></div>
						</div>
					</div>
					<div class="widget">
						<div class="widget_titulo">
							ESPORTES
						</div>
						<div class="widget_conteudo">
							<div class="noticiaarea1">
								<a href="./">
									<div class="noticiaitem noticiabig">
										<div class="noticiaimagem">
											<img src="assets/imagens/messi.jpg" border="0" width="80" height="80" />
										</div>
										<div class="noticiatitulo">
											Messi chega à 6º título da Chuteira de Ouro e recebe troféu Hoje.
										</div>
										<div class="noticiainfo">
											3 dia atrás	deixe um comentário.
										</div>
									</div>
								</a>
							</div>
							<div class="noticiaarea2">
								<a href="./">
									<div class="noticiaitem">
										<div class="noticiaimagem">
											<img src="assets/imagens/cristiano-ronaldo.jpg" border="0" width="80" height="80" />
										</div>
										<div class="noticiatitulo">
											Cristiano Ronaldo recebe mais por publicações no Instagram do que por jogar na Juventus.
										</div>
										<div class="noticiainfo">
											2 dias atrás	deixe um comentário.
										</div>
									</div>
								</a>
								<a href="./">
									<div class="noticiaitem">
										<div class="noticiaimagem">
											<img src="assets/imagens/lebron-james-la-lakers.jpg" border="0" width="80" height="80" />
										</div>
										<div class="noticiatitulo">
											LeBron James se envolve na disputa entre NBA e China.
										</div>
										<div class="noticiainfo">
											7 dias atrás	deixe um comentário.
										</div>
									</div>
								</a>
								<a href="./">
									<div class="noticiaitem">
										<div class="noticiaimagem">
											<img src="assets/imagens/corinthians-1.png" border="0" width="80" height="80" />
										</div>
										<div class="noticiatitulo">
											Corinthians x Cruzeiro: veja desfalques e prováveis escalações.
										</div>
										<div class="noticiainfo">
											10 dias atrás	deixe um comentário.
										</div>
									</div>
								</a>
								<a href="./">
									<div class="noticiaitem">
										<div class="noticiaimagem">
											<img src="assets/imagens/tombrady.jpg" border="0" width="80" height="80" />
										</div>
										<div class="noticiatitulo">
											Aos 42, Tom Brady não fala em aposentadoria, mas NFL vive com medo do dia chegar.
										</div>
										<div class="noticiainfo">
											15 dias atrás	deixe um comentário.
										</div>
									</div>
								</a>
							</div>
							<div style="clear:both"></div>
						</div>
					</div>
				</div>
				<div class="rightside">
					<div class="widget">
						<div class="widget_titulo">
							SOCIAL
						</div>
						<div class="widget_conteudo">
							<a href=""><img src="assets/imagens/youtube.png" title="Youtube" border="0" width="26" height="26" /></a>
							<a href=""><img src="assets/imagens/Twitter2.png" title="Twitter" border="0" width="26" height="26" /></a>
							<a href=""><img src="assets/imagens/facebook.png" title="Facebook" border="0" width="26" height="26" /></a>
							<a href=""><img src="assets/imagens/google_plus.png" title="Google Plus" border="0" width="26" height="26" /></a>
							<a href=""><img src="assets/imagens/rss3.png" title="RSS3" border="0" width="26" height="26" /></a>
						</div>
					</div>
					<div class="widget">
						<div class="widget_titulo">
							ÚLTIMAS NOTÍCIAS
						</div>
						<div class="widget_conteudo">
							<div class="noticia_item">
								<a href="./">Epic Games:Já disponível gratuitamente: Alan Wake's American Nightmare and Observer.</a>
							</div>
							<div class="noticia_item">
								<a href="./">Messi ganha sua 6º Chuteira de Ouro, é ser torna o único jogador a alcançar tal feito.</a>
							</div>
							<div class="noticia_item">
								<a href="./">"Pessoas como ela são alicerces para que o melhor da moda não morra!"</a>
							</div>
							<div class="noticia_item">
								<a href="./">Playstation demitiu dezenas de funcionarios no dia do anuncio do PS5.</a>
							</div>
							<div class="noticia_item">
								<a href="./">O filtro do Coringa é o novo efeito que vem fazendo sucesso no Instagram Stories.</a>
							</div>
						</div>
					</div>
					<div class="widget">
						<div class="widget_titulo">
							PUBLICIDADE
						</div>
						<div class="widget_conteudo">
							<b>Controverso "Skilly Pills" atingiua internet.</b>
							<img src="assets/imagens/girl.jpg" border="0" width="275" />
							<b>Eles são muito stong para ficar em lojas?</b>
						</div>
					</div>
					<div class="widget">
						<div class="widget_titulo">
							ENCONTRE-NOS NO FACEBOOK
						</div>
						<div class="widget_conteudo">
							<iframe src="https://www.facebook.com/plugins/page.php?href=https%3A%2F%2Fwww.facebook.com%2FSoccerDolls%2F&tabs=timeline&width=275&height=500&small_header=true&adapt_container_width=true&hide_cover=false&show_facepile=true&appId=566890540721284" width="275" height="500" style="border:none;overflow:hidden" scrolling="no" frameborder="0" allowTransparency="true" allow="encrypted-media"></iframe>
						</div>
					</div>
				</div>
			</div>
		</div>
	</body>
</html>
