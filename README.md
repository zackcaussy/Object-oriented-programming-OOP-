# Object-Oriented-Programming-OOP

## Programmation Orientée Objet - ex. Java



### Définition - Que signifie "objet" en Java ?

Un objet Java est une combinaison de données et de procédures qui manipulent les données disponibles. Les objets ont un état et un comportement. L'état d'un objet est stocké dans des champs (variables ou attributs) et des méthodes (fonctions) représentent le comportement de l'objet. Les objets sont créés à partir de modèles appelés classes. En Java, les objets sont créés avec le mot clé "new".

### Création d'objet

La création d'un objet est appelée instanciation car un objet est une instance d'une classe. Cette instanciation se fait à l'aide de l'opérateur new, suivi du nom de la classe à instancier et de parenthèses contenant les paramètres d'instanciation (ou parenthèses vides s'il n'y a pas de paramètres).

```java
class Personne{
	int age;
	int taille;
	int poids;
}
```

L'instanciation de cette classe (rudimentaire et actuellement inutile...) se fait de la façon suivante : 

```java
new Personne();
```

Les classes et les objets sont les composants fondamentaux de la POO (Programmation Orientée Objet). Il y a souvent une confusion entre les classes et les objets. Comment vous expliquer la différence entre classe et objet?
 
 
Le concept d’utilisation de classes et d’objets consiste à encapsuler l’état et le comportement dans une seule unité de programmation. Les objets Java sont similaires aux objets du monde réel. Par exemple, nous pouvons créer un objet voiture en Java, qui aura des propriétés telles que la vitesse et la couleur actuelle et un comportement comme: Accélérer et Freiner.
