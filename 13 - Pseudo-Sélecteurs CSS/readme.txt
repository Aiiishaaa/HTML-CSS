Objectif : 
L'objectif de cet exercice est de cibler des éléments HTML dans un certain état en se basant sur les pseudo classes CSS : first-child, nth-child(), last-child, link, visited, hover ...

Exercice 1:
Soit un code html contenant deux liens :

<a href="http://www.exelib.net/exercices/developpement-web/html/">Exercices HTML</a>
<a href="http://www.exelib.net/exercices/programmation/langage-c/">Exercices C</a>

Utiliser les pseudo classes ":hover" ":visited" ":active" dans l'ordre convenable afin de définir l'apparence des liens comme suit :
* Les liens survolés: non soulignés avec un background  "#7E3661" et une couleur de texte blanche.
* Les liens visités : avec une couleur de texte égale à "#FCB941"
* Les liens (état cliqué) : avec une taille de 1.5em.



Exercice 2:
On considère le tableau html dont le code est fourni dans le fichier tableau.html et dont le résultat est présenté dans tableau.png.

Travail à faire :
1) Changer la taille du titre à "1.5em" en affichant la première lettre de chaque mot en capitale.
2) Enlever la bordure pour le tableau.
3) Ajouter une marge interne de 10px et un alignement centré pour tous les cellules "th et td".
4) Cibler  la deuxième balise "th" de la première "tr" qui contient le mois du planning pour 
lui changer la taille en "2em" et la couleur en bleu.

5) Mettre en  background "#FCB941"  tous lignes "tr" du tbody qui viennent en positions
 paires et en background "#F1654C" les lignes qui viennent en positions impaires (Utiliser le pseudo classe "nth-child").
6) Donner à la première cellule de chaque ligne en position impaire ,un background 
"#7E3661" et une couleur "#fff".(Utiliser les pseudo classes nth-child et first-child)
7) Donner à la première cellule de chaque ligne en position paire ,un background "#888888"
 et une couleur "#fff".(Utiliser les pseudo classes nth-child et first-child)
8) Donner à la dernière cellule de chaque ligne en position impaire ,un background "#8870FF" et 
une couleur "#fff".(Utiliser les pseudo classes nth-child et last-child)
9) Enlever la bordure droite et la bordure du haut, de la dernière cellule "th" qui 
possède un attribut "rowspan" (utiliser le pseudo classe "last-child' et un sélecteur d'attribut pour "rowspan".

Le résultat à obtenir est présenté dans le fichier resultat.png