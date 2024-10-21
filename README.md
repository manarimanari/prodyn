# prodyn
Résumé du TP : Utilisation de la Programmation Dynamique avec Java
L'objectif de ce TP est de comprendre l'utilisation de la programmation dynamique en Java pour instancier des classes, injecter des dépendances et invoquer des méthodes via la réflexion. Cela permet de charger dynamiquement des classes et de configurer une application sans dépendre de la configuration statique. L'application créée consiste en une interface et des classes pour effectuer un calcul, avec un mécanisme d'injection de dépendances basé sur un fichier de configuration.
projet java
Conclusion
Ce TP permet de comprendre les principes de la programmation dynamique en Java. L'utilisation de la réflexion permet de créer des applications plus flexibles et modulaires. L'injection de dépendances via la réflexion facilite également la maintenance et l'évolution du code, car les classes peuvent être chargées et configurées dynamiquement sans avoir besoin de modifier le code source.
Explication des Concepts
1.	Programmation dynamique : C'est un paradigme qui permet de modifier la structure d'un programme pendant son exécution. Dans ce TP, cela se traduit par la capacité de charger des classes et d'injecter des dépendances à la volée.
2.	Réflexion : La réflexion en Java permet d'analyser et d'interagir avec des classes, des méthodes et des champs à l'exécution. Cela est utilisé dans la classe Presentation2 pour instancier les classes et invoquer des méthodes sans connaître les types au moment de la compilation.
3.	Injection de dépendances : C'est une technique qui permet de décarreler la création des objets de leur utilisation. Cela rend le code plus modulaire et testable.
