# [FR] Journal de Développement - Cloud Fundamentals & Deployment

## 18/05/2024

### Progrès Réalisés

Aujourd'hui, je continu le cours sur les Fondamentaux et déploiement du cloud a travers un exercise.

### Checkpoint : Héberger une application MERN sur Microsoft Azure

### Instructions

#### 1. Préparer votre application MERN

- Assurez-vous que votre application MERN est entièrement développée et testée localement.
- Assurez-vous que le backend de votre application (Node.js/Express) est connecté à MongoDB pour le stockage des données.

#### 2. Créer un compte Microsoft Azure

- Si vous ne l'avez pas encore fait, inscrivez-vous pour un compte Microsoft Azure.
- Accédez au portail Azure et naviguez jusqu'au tableau de bord.

#### 3. Configurer MongoDB Atlas

- Puisqu'Azure n'offre pas MongoDB en tant que service directement, utilisez MongoDB Atlas (le service cloud de MongoDB) pour votre base de données.
- Inscrivez-vous pour un compte MongoDB Atlas si vous n'en avez pas déjà un.
- Créez un nouveau cluster MongoDB et configurez-le selon les besoins de votre application.

#### 4. Préparer votre application MERN pour le déploiement

- Mettez à jour la configuration de votre application MERN pour utiliser des variables d'environnement pour les données sensibles telles que les informations d'identification de la base de données.
- Construisez votre frontend React pour la production en utilisant `npm run build`.

#### 5. Créer un service Web App Azure

- Dans le portail Azure, naviguez jusqu'à "Créer une ressource" > "Web" > "Web App".
- Remplissez les détails requis comme le nom de l'application, le groupe de ressources et la région.
- Choisissez le niveau de tarification approprié en fonction de vos besoins.

#### 6. Configurer la source de déploiement

- Dans les paramètres de votre Web App Azure, naviguez jusqu'à "Centre de déploiement".
- Choisissez la source de déploiement comme "Git local" ou connectez-vous à votre système de contrôle de version préféré (par exemple, GitHub).

#### 7. Déployer votre application MERN

- Si vous utilisez Git local, clonez le dépôt Git de votre Web App Azure sur votre machine locale.
- Copiez vos fichiers frontend React construits dans un dossier au sein de votre projet backend (par exemple, `server/public`).
- Commitez et poussez vos modifications dans le dépôt Git d'Azure.
- Azure détectera automatiquement les changements et déploiera votre application.

#### 8. Configurer les variables d'environnement

- Dans les paramètres de votre Web App Azure, naviguez jusqu'à "Configuration".
- Définissez les variables d'environnement pour votre application MERN, y compris la chaîne de connexion MongoDB et autres configurations nécessaires.

#### 9. Tester votre application MERN déployée

- Accédez à votre application MERN déployée via l'URL fournie par Azure.
- Testez toutes les fonctionnalités pour vous assurer du bon déploiement et de la connectivité avec la base de données.

---

# [EN] Development Journal - React Debugging

## May 18,2024

### Progress Achieved

Today, I am continuing the course on Cloud Fundamentals and Deployment through an exercise.

### Checkpoint: Hosting a MERN App on Microsoft Azure

### Instructions

#### 1. Prepare Your MERN Application

- Ensure that your MERN application is fully developed and tested locally.
- Make sure your application's backend (Node.js/Express) is connected to MongoDB for data storage.

### 2. Create a Microsoft Azure Account

- If you haven't already, sign up for a Microsoft Azure account.
- Access the Azure Portal and navigate to the dashboard.

### 3. Set Up MongoDB Atlas

- Since Azure doesn't offer MongoDB as a service directly, use MongoDB Atlas (MongoDB's cloud service) for your database.
- Sign up for a MongoDB Atlas account if you don't have one already.
- Create a new MongoDB cluster and configure it according to your application's requirements.

### 4. Prepare Your MERN App for Deployment

- Update your MERN application's configuration to use environment variables for sensitive data like database credentials.
- Build your React frontend for production using `npm run build`.

### 5. Create an Azure Web App Service

- In the Azure Portal, navigate to "Create a resource" > "Web" > "Web App".
- Fill in the required details like app name, resource group, and region.
- Choose the appropriate pricing tier based on your requirements.

### 6. Set Up Deployment Source

- In your Azure Web App's settings, navigate to "Deployment Center".
- Choose the deployment source as "Local Git" or connect to your preferred version control system (e.g., GitHub).

#### 7. Deploy Your MERN App

- If using Local Git, clone your Azure Web App's Git repository to your local machine.
- Copy your built React frontend files to a folder within your backend project (e.g., `server/public`).
- Commit and push your changes to Azure's Git repository.
- Azure will automatically detect changes and deploy your application.

#### 8. Configure Environment Variables

- In your Azure Web App's settings, navigate to "Configuration".
- Set environment variables for your MERN application, including MongoDB connection string and other required configurations.

#### 9. Test Your Deployed MERN App

- Access your deployed MERN application through the URL provided by Azure.
- Test all functionalities to ensure proper deployment and database connectivity.
