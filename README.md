TP4 - Java
Réalisé par : ******

### Exercice 1 — Application des concepts POO en Java
Cet exercice m’a permis de mettre en pratique les concepts fondamentaux de la programmation orientée objet en Java, notamment :

La généricité via l’interface IMetier

L’utilisation des collections pour la gestion des données

La création d’une application console interactive avec les opérations CRUD (Create, Read, Update, Delete) sur les produits

La structure modulaire adoptée, avec une séparation claire entre les interfaces et leurs implémentations concrètes, renforce la maintenabilité et l’extensibilité du code. Cela constitue une base solide pour de futurs développements, tels que :

L’ajout de la persistance des données

La création d’une interface graphique plus évoluée

Exercice 2 — Les Wildcards en Java
Cet exercice a illustré l’importance des wildcards pour une manipulation souple et sûre des collections génériques. Voici un résumé des différentes variantes :

<? extends Animal> : permet de lire les éléments d’une collection de n’importe quelle sous-classe de Animal, mais interdit l’ajout de nouveaux éléments.

<? super Chien> : permet d’ajouter des objets de type Chien à une collection contenant des objets de type Chien ou superclasses.

<?> : accepte n’importe quel type, mais limite les opérations aux méthodes disponibles dans la classe Object.

Cette approche s’inscrit dans le principe PECS (Producer Extends, Consumer Super), qui propose une manière élégante d’écrire des méthodes génériques tout en assurant :

La sécurité de type à la compilation

Une réutilisabilité optimale du code
