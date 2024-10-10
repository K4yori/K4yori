- 👋 Hi, I’m @K4yori

<!DOCTYPE html>
<html>
<head>
<title>MEU CURRÍCULO</title>
<meta charset="UTF-8">
<body style="background-color:
gray;">

</head>
<body>

<h1>Felipe de Melo Araujo</h1>
<h2>Desenvolverdor Iniciante</h2>
<p hidden> Não, Eu não usei Chat GPT para fazer essa pagina!</p><br>
<nav>
<tr>
<td><a class="menu-link" href="#">Apresentação</a></td>
<td><a class="menu-link" href="#">O'que Procuro</a></td>
</tr>
</nav>
<hr>
<div class="comprimento">
<p id="ele">Bom Dia!</p>
<script>
  let painel = document.getElementById("ele");
  let hora = new Date().getHours();
  if (hora<11){ painel.innerHTML= "Bom Dia!";} 
  else if(hora<18){ painel.innerHTML= "Boa Tarde!";}
  else{ painel.innerHTML="Boa Noite!";}  
</script>

<p id="demo">Hoje é</p>
	
<script>
	let day;
	switch (new Date().getDay()){
		case 0: day = "Domingo"; Break;
		case 1: day = "Segunda"; Break;
		case 2: day = "Terça"; Break;
		case 3: day = "Quarta"; Break;
		case 4: day = "Quinta"; Break;
		case 5: day = "Sexta"; Break;
		default: day = "Sabadou";}
	document.getElementById("demo").innerHTML = "Hoje é" + day;
</script>
</div>
<div class="apressentacao">
<h3>Apressentação</h3>
<br>
<p>Eu me chamo Felipe de Melo Araujo, Tenho 22 Anos, Moro em Atibaia-SP, Tenho curso de HardWare e Agora comecei o curso de ingles, Justamente pela programação, Faço o curso em uma das melhores escolas online da atualidade, Para realmente ter um bom desempenho para trabalho.
<br>
<br>
Gosto de fusar no computador desde muito cedo, Pois quando era criança, Ganhei um computador, E sempre ia aprendendo para deixa-lo melhor, Depois disso fui ter um contato com programação em 2021,Criei um site de vendas, Mas pelo Shopify, Mexi bem pouco com script, Mas tive que mexer em alguns, Depois disso, Gostei muito dessa área, E entrei na faculdade de engenharia de software, Para Entrar nessa área, E aqui estou eu, Me apresentando pelo meu WebSite kkk.

</div>
<hr>
<div class="oque-procuro"> 
<h3>O'que Procuro</h3>
<br>
Estou a procura de um estagio para conseguir mergulhar de vez nessa mundo da programação, Pois assim como diz a teoria, Para aprender você tem que sempre está usando em sua vida, E por isso, Procuro um lugar para me desenvolver cada vez mais e aprender como funciona esse mundo!
</div>

<div>



</body>
</html>
