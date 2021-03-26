# Testing JAVASCRIPT
Testing my first website

<!DOCTYPE html> 
<html>
  <head>
    <meta charset="utf-8">
    <title>Site Teste Nelson</title>  
    <link rel="stylesheet" href="style.css">	
  </head>
  <body>
     <header>
	   <h1 id="title">Aprendendo HMTL5 e CSS3 com Lucas Vilaboim e obtendo a eterna ajuda do Teteu!!</h1>
	 </header>
	 <section>
	   <header>
	     <img src="HTML CODE.jpg" alt="Imagem HTML CODE" class="subtitle_image">
	     <h2 class="subtitle">Relação dos textos</h2>
	   </header>
	   <article class="post">
	      <header>
		    <h3 class="post_title">Meu relato</h3>
		  </header>
		  <p class="post_content">
			<img src="https://br.stockfresh.com/image/9241632/thumb-up-emoticon" alt="minha imagem" class="post_photo"> 
			Aprender do zero e via EAD qualquer assunto não é fácil, 
			principalmente quando se tem que dividir a tarefa de estudar 
			com as tarefas de casa e do trabalho. O contexto só piora 
			quando se leva em consideração o atual momento global, 
			de pandemia da Covid-19. O simples fato de ir correr 
			para espairecer se torna algo muito preocupante, quase 
			não há espairecimento. Ainda temos que colocar nesste contexto 
			a ausência da família e dos amigos. O conforto está na esposa, 
			a Manu, uma, quase sempre, ótima companhia. O que poderia ser 
			muito difícil, se tornou só díficl, pois 
			<a href="https://www.linkedin.com/in/matheuscmpm/" target="_blank">Teteu</a> 
			está sempre disponível com toda a paciência e didática do 
			mundo para me explicar o que o <a href="https://www.linkedin.com/in/vilaboim/" target="_blank">Lucas Vilaboim</a> 
			já explicou, mas eu não entendi.
		  </p>
	   </article>
	 <section>
	 <footer>
	    <ul class="contacts_list">
		  <li>
		    <a href="https://www.linkedin.com/in/nelson-p-021729200/" target="_blank">Linkedin do Nelson</a>
		  </li>
		  <li>
		  <a href="mailto:nelson.amazonas@gmail.com">nelson.amazonas@gmail.com</a>
		  </li>
		</ul>  
	 </footer> 
 </body>
</html>
 



style css

body {
	background: yellow;
	font-family: verdana;
	max-width: 1300px;
	margin: auto;
}

.post_photo {
	border: 5px solid black;
	border-radius: 50%;
	height: 300px;
}
		

#title, .subtitle, .post_title {
	color: black;
}

#title {
	font-size: 25px;
	text-transform: uppercase;
}

a {
	text-decoration: underline;
	color: blue  ;
}

.subtitle {
	color: black;
	font-size: 25px;
	margin-bottom: 10px;
}

.subtitle_image {
	width: 100%;
	height: 300px;
}
	
.post_title {
	font-size: 22px;
	margin: 0;
	margin-bottom: 0;
	text-transform: capitalize;
}

.post {
	padding: 15px;
	border: 5px solid #000;
	font-size: 25px;
	margin-top: 0px;
	font-style: italic;
	border-radius: 10px;
	text-align: justify;
	margin-bottom: 15px;
	padding-top: 0;
}

.post_photo {
	float:left;
}

.post_image {
	margin-bottom: 15 px;
}

.contacts_list {
	list-style-type: none;
	padding-left: 15px;
	
}
