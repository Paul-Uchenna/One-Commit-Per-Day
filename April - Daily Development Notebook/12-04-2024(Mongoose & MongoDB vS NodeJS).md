# [FR] Journal de Développement - Mongoose & MongoDB vS NodeJS

## 12/04/2024

### Progrès Réalisés

Aujourd'hui, j'ai consacré 2 heures et 30 minutes à coder, ce qui équivaut à 5 pomodoros de 30 minutes, avec une pause de 3 minutes entre chaque pomodoro.

J'utilise [Pomodoro Tracker](https://pomodoro-tracker.com/) pour suivre mon temps. Mes sessions de travail d'une heure sont sans interruption, ce qui me permet de rester concentré et productif. Cette méthode me permet de mesurer précisément le temps que je passe à programmer seul, en excluant les discussions et le pair programming.

Je poursuis mon apprentissage sur Mongoose & MongoDB vS NodeJS.

### Mongoose Intro

Mongoose est une bibliothèque de modélisation de données objet (ODM) pour MongoDB et Node.js. Il est responsable de:

- La gestion des relations de données.
- La validation de schéma.
- L'implémentation de la traduction entre les objets de code et leur représentation dans MongoDB.

### La création d'un modèle Mongoose comprend principalement trois parties

- **Définition du schéma** : Spécifier la structure des données et les règles de validation.
- **Création du modèle** : Compiler le schéma en un modèle Mongoose.
- **Utilisation du modèle** : Effectuer des opérations CRUD et personnaliser les requêtes.

### Opérations Basiques

- **Créer un Enregistrement** : Pour créer un enregistrement, nous utiliserons la méthode `save` sur une instance du modèle Mongoose.
- **Récupérer un Enregistrement** : Nous utiliserons l'appel `find` pour supprimer un enregistrement.
- **Mettre à Jour** un Enregistrement : Nous utiliserons l'appel `findOneAndUpdate` pour supprimer un enregistrement.
- **Supprimer un Enregistrement** : Nous utiliserons l'appel `findOneAndRemove` pour supprimer un enregistrement.

---

# [EN] Development Journal - Express.js

## April 12,2024

### Progress Achieved

Today, I spent 2 hours and 30 minutes coding, which equates to 5 pomodoros of 30 minutes each, with a 3-minute break between each pomodoro.

I use [Pomodoro Tracker](https://pomodoro-tracker.com/) to track my time. My one-hour work sessions are uninterrupted, allowing me to stay focused and productive. This method enables me to precisely measure the time I spend programming alone, excluding discussions and pair programming.

I continue my learning journey with Mongoose & MongoDB vs NodeJS.

### Mongoose Intro

Mongoose is an Object Data Modeling (ODM) library for MongoDB and Node.js. It is responsible for:

- Managing data relationships.
- Schema validation.
- Implementing translation between code objects and their representation in MongoDB.

### Creating a Mongoose Model Comprises Primarily of Three Parts

- **Schema Definition**: Specify the data structure and validation rules.
- **Model Creation**: Compile the schema into a Mongoose model.
- **Model Usage**: Perform CRUD operations and customize queries.

### Basic Operations

- **Create a Record**: To create a record, we will use the `save` method on a Mongoose model instance.
- **Fetch a Record**: We will use the `find` call to fetch a record.
- **Update Record**: We will use the `findOneAndUpdate` call to update a record.
- **Delete Record**: We will use the `findOneAndRemove` call to delete a record.
