Le fichier optimisation.zip contient le code source du projet java.

Dans ce fichier zip le code source se trouve dans optimisation > src > optimisation > implementation_techniques.java
Dans ce fichier java se trouve notre code pour l'heuristique qui est la méthode gloutonne et le code pour la méta-heuristique qui est le recuit simulé, il y également le code permettant de trouver la borne supérieure Lagrangienne mais nous n'avons pas réussi à obtenir de solution pour cette-dernière.
Pour lancer le code, il suffit de l'importer dans eclipse et de faire run.


Le fichier executable.zip contient le fichier Executable.jar ainsi que le fichier Launch_ME.bat qui permet de lancer l'éxécutable.
Pour lancer le fichier Launch_ME il suffit de double cliquer sur celui-ci et une fenêtre s'ouvre montrant les résultats obtenus.
Il est préférable de lancer Launch_ME sur Window.

Lorsque l'on lance Launch_ME, il peut arriver que le programme renvoi pour le recuit simule "Exception in thread 'main' java.lang.ArrayIndexOutOfBoundsException: 50"; cette erreur est probablement dû à un problème lié à un ensemble mal définis dans le code mais nous n'avons pas réussi à corriger ce problème. 
Lorsque cette erreur apparaît il suffit de relancer le fichier jusqu'à ne plus avoir cette erreur qui apparaît de façon aléatoire.

A chaque fois que l'on lance notre programme le générateur aléatoire génère de nouvelles données pour les revenus et les encombrements de ce fait les différentes valeurs pour notre méthode gloutonne et du recuit simulé changent également.

Les 2 méthodes renvoient le profit en k euros qu'elles ont générées suivant le générateur aléatoire du dessus, dans les résultats nous affichons aussi des informations concernant les dépassements et les revenus.