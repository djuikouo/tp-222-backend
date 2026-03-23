CleeRoute - API Backend de Gestion de Blog
Ce projet a été réalisé dans le cadre du TAF 1 à l'ENSP. Il s'agit d'une API REST construite avec Node.js et Express permettant de gérer des articles de blog avec une documentation interactive via Swagger.

 Fonctionnalités
CRUD Complet : Création, Lecture, Mise à jour et Suppression d'articles.

Recherche Avancée : Filtrage par auteur, catégorie ou mots-clés.

ID Dynamique : Génération automatique des identifiants uniques.

Documentation UI : Interface Swagger intégrée pour tester l'API.

 Technologies utilisées
Runtime : Node.js
Framework : Express.js

Documentation : Swagger UI Express & OpenAPI 3.0
Outil de test : Postman / Swagger UI
 Installation et Lancement
Cloner le projet ou extraire le ZIP :cd taf2_backend
Installer les dépendances :npm install
Lancer le serveur : node index.js
Le serveur sera disponible sur http://localhost:3000

Utilisation de l'API
Une fois le serveur lancé, tu peux accéder à la documentation interactive ici :http://localhost:3000/api-docs
 Structure du projet
index.js : Configuration du serveur et de Swagger.

/route/articleroute.js : Définition des points d'entrée (endpoints).

/controleur/articlecontrolleur.js : Logique métier et gestion des données.
