# RallyeLecture-
TP: RallyeLecture C# ###

Le but du Tp est de d'alimenter une base de donnée avec un fichier csv , avec creation de mot de passe et 

Les outils mis en oeuvre:
* Git
* Visual Studio
* C#
* Windows Form

Dans un premier temps, il fut nécessaire de créer la fenêtre Principal.
Celle-ci est entre autre la fenêtre par défaut générer par la solution Windows Form.
Ainsi, afin de ne pas la laisser vide, nous avons fait le choix d'ajouter différentes fonctionnalités:



1. Bouton New: Instancie une nouvelle fenêtre et l'ajouter à la List Box.
La mère ayant de nombreuses Filles, celles-ci seront stockées dans un objet de type ArrayList géré par la fenêtre mère:

  
2. Bouton Close: Ferme la fenêtre préalablement séléctionnée dans la List Box et l'efface de la List Box (Elle n'existe plus en mémoire).
3. List Box: Liste les fenêtres Fille instanciées.
4. Bouton Show: Ouvre, affiche la fenêtre Fille selectionnée dans la List Box.
5. Bouton Hide: Cache la fenêtre fille selectionnées dans la List Box.
6. Bouton Show Dialog: Ouvre une fenêtre fille selectionnée dans la List Box en tant que Show Dialog.

![FilleNew.png](http://image.noelshack.com/fichiers/2018/42/5/1539939823-fillenew.png)

![FilleMere.png](http://image.noelshack.com/fichiers/2018/42/5/1539939856-fillemere.png)


