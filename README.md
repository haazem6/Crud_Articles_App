# Crud_Articles_App
## Tawa_Backend

## Description
Le backend est construit avec [Node.js](https://nodejs.org/) et [Express](https://expressjs.com/). Il gère les fonctionnalités serveur, la communication avec la base de données, et offre des API pour la gestion des utilisateurs et des articles.

## Fonctionnalités

- Inscription et connexion d'utilisateurs,
- Gestion des articles.

## Technologies Utilisées

-  Node.js
-  Express.js
-  MongoDB


## Configuration du Projet

### Prérequis
- Node.js installé
- MongoDB installé 

### Installation
1. Clônez le dépôt : `git clone https://github.com/haazem6/Crud_Article_App.git`
2. Naviguez dans le répertoire du projet : `cd tawaBack`
3. Installez les dépendances : `npm install`

### Configuration
1. Créez un fichier `.env` à la racine du projet et configurez les variables d'environnement nécessaires.

## Utilisation

1. Lancez le serveur : `npm start`
2. Accédez à l'application dans votre navigateur à l'adresse `http://localhost:5000` .

## API Endpoints
- Exemple :
  - `POST /api/user/signup`: Inscription d'un nouvel utilisateur.
  - `POST /api/user/signin`: Connexion d'un utilisateur existant.
  - `GET /api/article/getAll`: Récupération de tous les articles.
  - `Post /api/article/article/${id}`: Récupération de tous les articles, etc.



---
## Tawa_Frontend

## Description

 plateforme web moderne développée pour simplifier la gestion des articles. Que vous soyez un passionné d'écriture ou un éditeur professionnel,offre une expérience intuitive pour la création, la modification et la suppression d'articles.

### Principales Caractéristiques

- **Gestion Facile :** Créez, éditez et supprimez des articles en toute simplicité.
- **Interface Réactive :** Profitez d'une interface réactive pour une expérience utilisateur fluide.


## Technologies Utilisées

- [React](https://reactjs.org/) et [Redux](https://redux.js.org/) pour une gestion d'état efficace.
- [React Router](https://reactrouter.com/) pour une navigation fluide.
- [Axios](https://axios-http.com/) pour des requêtes HTTP.
- [Tailwind CSS](https://tailwindcss.com/) pour un stylage moderne et flexible.

## Structure du Projet

- `/src`: Contient le code source de l'application.
  - `/components`: Composants réutilisables.
  - `/api`: Fonctions pour effectuer des appels API.
  - `/redux`: Configuration et tranches Redux pour la gestion de l'état.
  - `/routes`: Configuration des routes de l'application.
  - `/App.js`: Composant principal de l'application.
  - `/index.js`: Point d'entrée de l'application.

## Capture d'écran

![Capture d'écran de l'application](homePage.png)

## Configuration et Installation

1. **Clonez le dépôt :** `git clone https://github.com/haazem6/Crud_Article_App.git`
2. **Accédez au répertoire du projet :** `cd tawaFront`
3. **Installez les dépendances :** `npm install`

## Scripts Disponibles

- `npm start` : Lance l'application en mode développement.

## Utilisation

- **Lancez l'application :** `npm start`
- **Accédez à l'application dans votre navigateur :** [http://localhost:3000](http://localhost:3000)


---


