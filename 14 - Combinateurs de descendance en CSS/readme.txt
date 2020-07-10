Objectif :
Dans cet exercice on va utiliser les combinateurs de descendance, d'adjacence et filial en CSS.
Avant de commencer cet exercice, il est recommandé de vous exercer sur cet exercice : https://flukeout.github.io/

Enoncé :
En se basant sur le code html suivant (que vous trouverez dans le fichier index.html) :

<html>
<head>
	<title>Les selecteurs complexes</title>
    <meta charset="utf-8">
	<!-- Le fichier style.css est le fichier que vous devez compléter -->
	<link rel="stylesheet" type="text/css" href="style.css">
</head>
<body>
     <div class="article">
		 <h2>Titre1</h2>
		 <ul> 
			<li>Item1:<p>resumé item1..........</p></li>
			<li>Item2:<p>resumé item2.......</p></li>
			<li>Item3:<p>resumé item3........</p></li>
		 </ul>
		 <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit</p>
		 <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit</p>

     	<h2>Titre2</h2>
     	<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit</p>
     	<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit</p>
     	<div class="exemple">
     		<h2>exemple1</h2>
     		<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit</p>   
     	</div>
     </div>
</body>
</html>

Utiliser les combinateurs et appliquer les styles CSS ci-dessous :
* Un retrait gauche de 20px pour tous les paragraphes descendants de la classe "article".
* Un background de couleur jaune pour  les paragraphes frères directs du titre "h2" (qui se trouvent immédiatement après h2, et non pas en dessous).
* Une bordure noir et solide pour les paragraphes adjacents du titre "h2".
* Une couleur verte pour les paragraphes fils des éléments "li".

Le résultat à obtenir se trouve dans le fichier resultat.png
