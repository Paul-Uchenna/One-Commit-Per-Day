# [FR] Journal de Développement -React avec TypeScript

## 11/05/2024

### Progrès Réalisés

Aujourd'hui, j'ai entamé un nouveau cours portant sur TypeScript avec React. Voici ce que j'ai appris :

- **Configuration de TypeScript dans une application React** : J'ai appris à configurer TypeScript dans une application React en installant les types nécessaires et en configurant le fichier `tsconfig.json` pour prendre en charge TypeScript dans le projet.
- **Utilisation des Hooks avec TypeScript** : J'ai exploré comment utiliser les Hooks de React, tels que `useState` et `useEffect`, tout en profitant des avantages de TypeScript pour garantir la sécurité des types dans notre code.
- **Déclaration des composants et des props avec TypeScript** : J'ai compris comment déclarer les types pour les composants React et leurs props en utilisant TypeScript, ce qui améliore la lisibilité et la maintenabilité du code tout en réduisant les erreurs potentielles.

### Exercice

Instructions :

Dans ce point de contrôle, nous convertirons les extraits de code React donnés en TypeScript. Nous ajouterons des annotations de type appropriées et garantirons la sécurité des types dans le code.

#### Code 01

```javascript
import React from "react";

const Greeting: React.FC<GreetingProps> = ({ name }) => {
  return <div>Hello, {name}!</div>;
};

export default Greeting;
```

#### Code 02

```javascript
import React, { Component } from "react";
class Counter extends Component {
  state = {
    count: 0,
  };
  increment = () => {
    this.setState({ count: this.state.count + 1 });
  };
  render() {
    return;
    <div>
      <p>Count: {this.state.count}</p>
      <button onClick={this.increment}>Increment</button>
    </div>;
  }
}
export default Counter;
```

---

# [EN] Development Journal -React with TypeScript

## May 11,2024

### Progress Achieved

Today, I started a new course on TypeScript with React. Here's what I've learned:

- **Configuring TypeScript in a React Application**: I learned how to configure TypeScript in a React application by installing the necessary types and configuring the `tsconfig.json` file to support TypeScript in the project.
- **Using Hooks with TypeScript**: I explored how to use React Hooks, such as `useState` and `useEffect`, while leveraging TypeScript's benefits to ensure type safety in our code.
- **Declaring Components and Props using TypeScript**: I understood how to declare types for React components and their props using TypeScript, improving code readability and maintainability while reducing potential errors.

### Exercise

Instructions:

In this checkpoint, we will convert the given React code snippets into TypeScript. We will add appropriate type annotations and ensure type safety in the code.

#### Code 01

```javascript
import React from "react";

const Greeting: React.FC<GreetingProps> = ({ name }) => {
  return <div>Hello, {name}!</div>;
};

export default Greeting;
```

#### Code 02

```javascript
import React, { Component } from "react";
class Counter extends Component {
  state = {
    count: 0,
  };
  increment = () => {
    this.setState({ count: this.state.count + 1 });
  };
  render() {
    return;
    <div>
      <p>Count: {this.state.count}</p>
      <button onClick={this.increment}>Increment</button>
    </div>;
  }
}
export default Counter;
```
