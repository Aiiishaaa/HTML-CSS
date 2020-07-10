Objectif :
Améliorer la typographie de texte en utilisant des propriétés css comme : font, line-height, color , margin et padding ... 

Travail à faire : 
À partir de la page html suivante :

<!doctype html>
<html>
<head>
	<title>Typographie</title>
	<meta charset="utf-8">
	<!-- On charge le reset  des propriétés CSS -->
	<link rel="stylesheet" type="text/css" href="reset.css">
	<!-- Le fichier style.css est le fichier que vous devez compléter -->
	<link rel="stylesheet" type="text/css" href="style.css">
</head>
<body>
	<h1>Web Mobile</h1>
	<p>D'après wikipedia :Le Web Mobile ou Webmobile est une technique qui permet d'accéder à Internet depuis un téléphone mobile, on parle alors de l'Internet Mobile et des smartphones. Le web mobile se matérialise notamment par l'utilisation de navigateur mobiles ou d'applications pour Smartphones mais aussi par des widgets, la consultation de mails de façon instantanée... C'est l'évolution des équipements, des usages et des forfaits de téléphone mobile qui ont permis le démarrage du web mobile.</p>
    <blockquote>
     	<p>L'initiative du Web mobile est importante : l'information doit être traité de façon transparente sur n'importe quel appareil</p>
     	<em>&mdash;Tim Berners-Lee</em>
     </blockquote>

	<a href="https://fr.wikipedia.org/wiki/Web_mobile">Plus de détails</a>
</body>
</html>
Complétez le fichier style.css pour arriver au rendu présenté dans le fichier resultat.png en utilisant les propriétés css pour la typographie.

On commence par faire un css-reset à l'aide du fichier css fourni. Dans notre exercice, nous utilisons le reset le plus populaire de Eric Meyer disponible dans le fichier reset.css.
Css-reset c'est une remise à 0 des propriétés css pour éviter les différences d'affichage sur les divers navigateurs dues aux valeurs par défaut potentiellement différentes de chaque navigateur.


Étapes à suivre:

Le body doit être :
* dans l'ordre de préférence de police helvetica, Arial,  et sans-serif
* d'une hauteur de ligne de 1.5 sans unité
* d'une marge de 10px
* d'une taille police de 1em.

Le titre h1 avec :
* une police helvetica Arial serif
* une taille police de 1.5em
* une marge du bas à 1.5em
* la couleur "#454545"
* et un épaisseur de caractères gras.

Pour le paragraphe qui suit le titre :
* une couleur #7a7a7a.
* une marge gauche de 20 px.
* une marge du bas de 1.5em.

Le blockquote doit avoir :
* une police italic de taille 1.2em
* une marge droite de 80px du bas de 20px et de gauche de 60px
* un background #e7f2fa et une couleur #444
* une bordure gauche solide de 5px et de couleur #8870FF
* une marge interne de 15px 

La balise em avec :
* un affichage en bloc
* un alignement à droite 
* le lien "plus de détails" :
* Une couleur #8870FF
* une marge gauche de 20px