Objectif :
Appliquer les styles relatifs aux bordures.

Énoncé :
Soit le code html suivant (que vous retrouverez dans le fichier index.html) :

<!doctype html>
<html>
<head>
	<title>Bordure</title>
	<meta charset="utf-8">
	<!-- Le fichier style.css est le fichier que vous devez compléter -->
	<link rel="stylesheet" type="text/css" href="style.css">
</head>
<body>
      <article class="article">
      	<h2 class="titre-article">Titre</h2>
      	<div class="detail-article">	
			 <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
			 tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
			 quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
			 consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
			 cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
			 proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
			 </p>
			 <a href="#">Read more</a>
      	</div>
      </article>
</body>
</html>

Appliquez les propriétés de bordures en css : border et border-radius afin de réaliser un design équivalent à celui du fichier resultat.png

Indications :
1) Appliquez une bordure solid de couleur rgba(0,0,0,0.3) et un arrondi de 10px.
 Ajoutez les marges qui conviennent et une hauteur de ligne à 1.5.

2) Donnez au titre une bordure du bas pointillée et une police.
3) Pour la classe "detail-article" appliquez un alignement centré de texte pour centrer le lien.
4) Appliquez la couleur #7b7b7b, une taille de 1em, et un alignement justifié 
au paragraphe fils de la classe "detail-article".
5) Le lien avec une bordure de forme elliptique 200px/50px.
