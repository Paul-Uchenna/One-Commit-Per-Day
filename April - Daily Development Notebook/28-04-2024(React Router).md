# [FR] Journal de Développement -React Router

## 28/04/2024

### Progrès Réalisés

Aujourd'hui, j'ai entamé l'exploration d'un nouveau sujet concernant React, plus précisément React Router.

React Router est une bibliothèque populaire utilisée avec React pour gérer la navigation dans une application à pages multiples. Elle permet de définir des routes qui correspondent à des URL spécifiques et de rendre des composants React correspondants lorsque ces routes sont atteintes.

Voici quelques points clés que j'ai retenu :

- Définition des routes : React Router permet de définir des routes dans une application React en associant des composants à des URL spécifiques. Cela se fait généralement en utilisant le composant `<Route>`.
- Navigation entre les pages : Le composant `<Link>` de React Router est utilisé pour créer des liens entre les différentes pages de l'application. Contrairement aux balises d'ancrage HTML traditionnelles, `<Link>` permet une navigation fluide entre les pages sans rechargement complet de la page.
- Gestion des paramètres d'URL : React Router permet également de gérer les paramètres d'URL dynamiques à l'aide de placeholders dans les routes. Ces paramètres peuvent être extraits et utilisés dans les composants pour personnaliser le contenu en fonction de l'URL.
- Gestion de l'historique de navigation : React Router fournit un composant `BrowserRouter` qui utilise l'API HTML5 History pour gérer l'historique de navigation de manière cohérente.

---

# [EN] Development Journal - React Router

## April 28,2024

### Progress Achieved

Today, I began exploring a new topic regarding React, specifically React Router.

React Router is a popular library used with React to manage navigation in a multipage application. It allows defining routes that correspond to specific URLs and rendering corresponding React components when these routes are reached.

Here are some key points I've gathered:

- Route definition: React Router allows defining routes in a React application by associating components with specific URLs. This is typically done using the `<Route>` component.
- Navigation between pages: The `<Link>` component of React Router is used to create links between different pages of the application. Unlike traditional HTML anchor tags, `<Link>` enables smooth navigation between pages without a full page reload.
- Handling URL parameters: React Router also enables managing dynamic URL parameters using placeholders in routes. These parameters can be extracted and used in components to customize content based on the URL.
- Managing navigation history: React Router provides a `BrowserRouter` component that utilizes the HTML5 History API to manage navigation history consistently. This allows updating the browser's URL without a page reload and maintaining a consistent application state.
