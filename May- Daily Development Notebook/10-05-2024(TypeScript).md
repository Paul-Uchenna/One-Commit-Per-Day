# [FR] Journal de Développement - TypeScript

## 10/05/2024

### Progrès Réalisés

Aujourd'hui, je continu mon cours portant sur TypeScript.

Voici un recapitulatif de ce qu'il y'a a retenir et un exercice:

1. TypeScript: Puissant sur-ensemble de JavaScript, améliore la qualité du code et la productivité.
2. Syntaxe de base et types de données: Crucial pour écrire efficacement du code TypeScript.
3. Fonctions: Modularité et réutilisabilité du code.
4. Interfaces: Définissent des contrats pour les formes d'objets, facilitent la vérification de type.
5. Classes: Structures orientées objet, encapsulent données et comportement.
6. Modules: Améliorent la maintenabilité et la réutilisabilité du code, structure de projet.
7. Code asynchrone: Gestion des opérations sans bloquer l'exécution.
8. Génériques: Code réutilisable avec sécurité des types.
9. Fichiers de déclaration de type: Informations de type pour les bibliothèques JavaScript, amélioration de l'interopérabilité.
10. Décorateurs: Ajoutent des métadonnées et des fonctionnalités, organisation du code et réutilisation.
11. Débogage: Crucial pour identifier et corriger efficacement les erreurs.

### Exercice

Instructions :

Définissez une interface nommée `Vehicle` avec les propriétés suivantes :

- `make` de type `string`
- `model` de type `string`
- `year` de type `number`
- Une méthode `start` qui retourne `void` et enregistre "Moteur démarré" dans la console.

Implémentez une classe nommée `Car` qui implémente l'interface `Vehicle`. La classe `Car` doit avoir :

- Un constructeur qui initialise les propriétés `make`, `model`, et `year`.
- Implémentez la méthode `start` pour enregistrer "Démarrage du moteur de la voiture" dans la console.

Créez une instance de la classe `Car` et initialisez-la avec des valeurs pour `make`, `model`, et `year`.
Appelez la méthode `start` sur l'instance de la classe `Car` pour vérifier qu'elle enregistre le message approprié dans la console.

Enfin, compilez votre code TypeScript en JavaScript et exécutez-le pour vous assurer que tout fonctionne comme prévu.

# [EN] Development Journal - TypeScript

## May 10,2024

### Progress Achieved

Today, I continue my course on TypeScript.

Here's a recap of what to remember and an exercise:

1. TypeScript: Powerful superset of JavaScript, improves code quality and productivity.
2. Basic syntax and data types: Crucial for writing effective TypeScript code.
3. Functions: Modularity and code reusability.
4. Interfaces: Define contracts for object shapes, facilitate type checking.
5. Classes: Object-oriented structures, encapsulate data and behavior.
6. Modules: Enhance code maintainability and reusability, project structure.
7. Asynchronous code: Handling operations without blocking execution.
8. Generics: Reusable code with type safety.
9. Type declaration files: Type information for JavaScript libraries, improves interoperability.
10. Decorators: Add metadata and functionality, code organization and reuse.
11. Debugging: Crucial for effectively identifying and fixing errors.

### Exercise

Instructions:

Define an interface named `Vehicle` with the following properties:

- `make` of type `string`
- `model` of type `string`
- `year` of type `number`
- `start` method which returns `void` and logs "Engine started" to the console.

Implement a class named `Car` that implements the `Vehicle` interface. The `Car` class should have:

- A constructor that initializes the `make`, `model`, and `year` properties.
- Implement the `start` method to log "Car engine started" to the console.

Create an instance of the `Car` class and initialize it with some values for `make`, `model`, and `year`.
Call the `start` method on the instance of the `Car` class to verify that it logs the appropriate message to the console.

Finally, compile your TypeScript code into JavaScript and run it to ensure everything works as expected.
