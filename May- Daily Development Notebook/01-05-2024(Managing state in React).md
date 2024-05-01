# [FR] Journal de Développement - Gestion de l'état dans React

## 01/05/2024

### Progrès Réalisés

Aujourd'hui, j'ai codé pendant 3 heures et 30 minutes, dont 2 heures le matin et 1 heure 30 minutes le soir, ce qui correspond à 7 pomodoros de 30 minutes avec une pause de 3 minutes entre chaque pomodoro.

Utilisant [Pomodoro Tracker](https://pomodoro-tracker.com/) pour suivre mon temps. Je fais des sessions de travail d'une heure, sans interruption, pour rester concentré et productif. Cela me permet de mesurer précisément mon temps de programmation solo, en excluant les discussions et le pair programming.

je poursuis mon exploration de React Router. j'ai etudier la Gestion de l'état dans React.

Gérer l'état local et distant :

- **État local :** Fait référence aux données spécifiques à un composant et est géré de manière interne à ce composant. Il est généralement utilisé pour les données liées à l'interface utilisateur ou les données qui n'ont pas besoin d'être partagées avec d'autres composants.
- **État distant :** Fait référence aux données récupérées depuis une source externe, telle qu'une API, et gérées par l'application. Ces données peuvent être partagées entre plusieurs composants et nécessitent souvent des opérations asynchrones pour les récupérer et les mettre à jour.

Gestion de l'état de l'URL et du stockage web :

- **État de l'URL :** Fait référence à la partie de l'état de l'application encodée dans l'URL. Il est utile pour les signets, le partage de liens et le maintien de l'état de l'application entre les rafraîchissements de page.
- **Stockage web :** Fait référence aux mécanismes de stockage du navigateur tels que localStorage et sessionStorage. Ils permettent aux développeurs de stocker des données localement dans le navigateur de l'utilisateur, même après le rechargement ou la fermeture de la page. Ils sont couramment utilisés pour mettre en cache des données ou stocker les préférences de l'utilisateur.

Gestion de l'état partagé, dérivé et immuable :

- **État partagé :** Fait référence aux données partagées entre plusieurs composants dans une application React. Il nécessite souvent une gestion prudente pour assurer la cohérence et éviter les conflits.
- **État dérivé :** Fait référence aux valeurs d'état dérivées d'autres valeurs d'état ou calculées en fonction d'elles. Il est utile pour transformer ou agréger des données avant de les afficher dans l'interface utilisateur.
- **État immuable :** Fait référence aux données d'état qui ne peuvent pas être modifiées directement. Au lieu de cela, les modifications entraînent la création de nouveaux objets d'état, maintenant l'immutabilité de l'état d'origine. L'immutabilité aide à prévenir les effets secondaires non intentionnels et simplifie la gestion de l'état dans les applications complexes.

Gestion de l'état du formulaire et validation :

- **État du formulaire :** Fait référence aux données associées aux entrées de formulaire dans une application React. Il inclut les valeurs saisies par les utilisateurs, l'état de validation et les messages d'erreur.
- **Validation du formulaire :** Fait référence au processus visant à garantir que la saisie de l'utilisateur dans un formulaire respecte certains critères ou contraintes. Cela implique de vérifier les valeurs saisies par rapport aux règles de validation et d'afficher des messages d'erreur aux utilisateurs en cas d'échec de la validation.

Gestion de l'état via les références :

- **Références :** Les références en React fournissent un moyen d'accéder et d'interagir directement avec les éléments du DOM. Bien qu'elles soient principalement utilisées pour accéder aux nœuds DOM ou aux composants React, les références peuvent également être utilisées pour gérer l'état dans certaines situations, telles que la gestion du focus ou l'accès aux méthodes impératives des composants enfants.

Gestion de l'état complexe avec useReducer :

- **useReducer :** Un hook React qui fournit une alternative à useState pour gérer la logique d'état complexe. Il est particulièrement utile lorsque les transitions d'état impliquent plusieurs sous-valeurs ou lorsque l'état suivant dépend de l'état précédent. useReducer suit le modèle réducteur couramment utilisé en JavaScript et permet une gestion de l'état plus structurée.

Partage de l'état et des fonctions via le contexte :

- **Contexte :** Une fonctionnalité de React qui permet de transmettre des données à travers l'arborescence des composants sans avoir à transmettre manuellement les props à chaque niveau. Il est souvent utilisé pour partager l'état, les paramètres de configuration ou les fonctions entre les composants éloignés dans l'arborescence des composants. Le contexte offre une solution pour éviter le forage de props et simplifier le partage de données ou de fonction

---

# [EN] Development Journal - Managing state in React

## May 01,2024

### Progress Achieved
