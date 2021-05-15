<!DOCTYPE html>
<html lang="en">
<head>
 <meta charset="UTF-8">
<title>Carta</title>
<SCRIPT LANGUAGE=JavaScript>
function botao1() {open("https://nandahbrodt.github.io/carta-especial/index.html", "", "height=450,width=900");}
</SCRIPT>

<style>

.carta{position:absolute;
  top: 1px;
  }

.data {
  position: absolute;
  top: 20px;
  left: 300px;
  font-size: 20px;
}
.saudacao {
  position: absolute;
  top: 55px;
  left: 50px;
  font-size: 20px;
}
.mensagem {
  position: absolute;
  top: 120px;
  left: 50px;
  font-size: 20px;
}

.assina {
  position: absolute;
  top: 290px;
  left: 340px;
  font-size: 20px;
}
.redireciona {
  position: absolute;
  top: 350px;
  left: 50px;
  font-size:20px;
}
.botao{
  position: absolute;
  top: 350px;
  left: 700px;
  font-size: 20px;
  }
 body {font-size: 20px; 
 }

button {
  border: #FFFFFF;
  color: #FFFFFF;
  padding: 10px 20px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 18px;
  margin: 1px 1px;
  cursor: pointer;
  background: #262FA2
}
</style>
</head>

<body>

<svg height="450" width="900">
<polygon points="0,2,  900,2 ,900,450, 0,450" style="fill:#D6E5FC ;width:4" />

<div class="data">Cambori&uacute;, 14 de maio de 2021</div>

<div class="saudacao">Querido Leonardo!</div>

<div class="mensagem"> Eu e o vov&ocirc;, estamos aqui contando os minutos at&eacute; a hora que voc&ecirc; chega aqui para nos visitar.<br> 
Pode trazer as tarefas da escola para fazer aqui no nosso apartamento. Porque eu tamb&eacute;m tenho<br>
tarefas da Univali para entregar. Desta forma, podemos fazer as tarefas na mesma hora.<br>
<p>Beijos!</p>
</div>
<div class="assina">T&acirc;nia Michel Pereira</div>
<div class="redireciona">Veja a cartinha da Fernanda, minha colega!</div>

<div class="botao">
	<button onclick="botao1()">Ver</button>
</div>

</svg>
</body>
</html>

