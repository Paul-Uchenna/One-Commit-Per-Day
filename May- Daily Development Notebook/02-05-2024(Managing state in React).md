# [FR] Journal de Développement - Gestion de l'état dans React

## 02/05/2024

### Progrès Réalisés

Aujourd'hui, je poursuis mon exploration de React Router. j'ai etudier la Gestion de l'état dans React.
A travers un exercice protique.

### Exercice (Développer une Application de Liste de tâches)

#### Description

Créez une application simple To-Do List en utilisant React qui démontre divers aspects de la gestion d'état. L'application devrait permettre aux utilisateurs d'ajouter, modifier, supprimer et marquer les tâches comme terminées. En outre, mettre en œuvre la validation de formulaire pour ajouter/modifier des tâches et utiliser le stockage du navigateur pour persister les tâches entre les sessions.

#### Livrables

- Une application React qui répond aux exigences décrites ci-dessous (vérifier les instructions).
- Le code doit être bien structuré, avec des composants séparés pour différentes parties de l'application (par exemple, TaskList, TaskForm, TaskItem).
- Inclure des commentaires dans le code pour expliquer le but de chaque composant et fonction.
- Fournir un bref README.md fichier expliquant comment exécuter l'application localement et toute information ou considérations supplémentaires.

#### Instructions

1. Mettre en place un formulaire pour ajouter de nouvelles tâches. Le formulaire doit inclure des champs de saisie pour le nom et la description de la tâche, et il doit effectuer une validation pour s'assurer que les deux champs sont remplis avant d'ajouter une tâche.
2. Affichez la liste des tâches avec des options pour modifier, supprimer et marquer les tâches comme terminées. Les tâches terminées doivent être distinguées visuellement des tâches actives.
3. Autoriser les utilisateurs à modifier les détails de la tâche en cliquant sur la tâche. Mettre en œuvre un formulaire pré-rempli avec les détails de la tâche qui permet aux utilisateurs de mettre à jour le nom et la description de la tâche.
4. Fournir des fonctionnalités pour supprimer des tâches de la liste. Inclure une invite de confirmation avant de supprimer une tâche.
5. Implémenter le stockage du navigateur (localStorage ou sessionStorage) pour persister les tâches entre les sessions. Assurez-vous que les tâches sont chargées à partir du stockage lorsque l'application initialise et enregistrées dans le stockage chaque fois qu'il y a un changement dans la liste des tâches.
6. Style de l'application en utilisant CSS pour le rendre visuellement attrayant et convivial. Utilisez un style approprié pour mettre en évidence les tâches actives et terminées.

#### Facultatif

- Implémentez des fonctionnalités supplémentaires telles que le filtrage des tâches en fonction de l'état d'achèvement, le tri des tâches par priorité ou date d'échéance, ou l'ajout de dates d'échéance aux tâches.

---

# [EN] Development Journal - Managing state in React

## May 02,2024

### Progress Achieved

Today, I continue my exploration of React Router. I studied State Management in React.
Through a protic exercise

### Exercise (Developing a Todo List Application)

#### Description

Create a simple Todo List application using React that demonstrates various aspects of state management. The application should allow users to add, edit, delete, and mark tasks as completed. Additionally, implement form validation for adding/editing tasks and use browser storage to persist tasks between sessions.

#### Deliverables

- A React application that meets the requirements outlined below (check instructions).
- Code should be well-structured, with separate components for different parts of the application (e.g., TaskList, TaskForm, TaskItem).
- Include comments in the code to explain the purpose of each component and function.
- Provide a brief README.md file explaining how to run the application locally and any additional information or considerations.

#### Instructions

1. Set up a form to add new tasks. The form should include input fields for the name and description of the task, and it should perform validation to ensure both fields are filled before adding a task.
2. Display the list of tasks with options to edit, delete, and mark tasks as completed. Completed tasks should be visually distinguished from active tasks.
3. Allow users to edit task details by clicking on the task. Implement a pre-filled form with task details that allows users to update the name and description of the task.
4. Provide functionality to delete tasks from the list. Include a confirmation prompt before deleting a task.
5. Implement browser storage (localStorage or sessionStorage) to persist tasks between sessions. Ensure tasks are loaded from storage when the application initializes and saved to storage whenever there is a change in the task list.
6. Style the application using CSS to make it visually appealing and user-friendly. Use appropriate styling to highlight active and completed tasks.

#### Optional

- Implement additional features such as task filtering based on completion status, sorting tasks by priority or due date, or adding due dates to tasks.
