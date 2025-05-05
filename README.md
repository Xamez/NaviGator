# NaviGator

NaviGator est un projet de développement d'une application Web codée en PHP pour calculer l'itinéraire le plus court entre plusieurs communes.

## Table des matières

- [Présentation](#présentation)
- [Fonctionnalités](#fonctionnalités)
- [Technologies utilisées](#technologies-utilisées)
- [Installation](#installation)
- [Utilisation](#utilisation)
- [Images](#images)
- [Contributions](#Contributions)

## Présentation

Ce projet est une application Web développée en PHP qui permet de calculer l'itinéraire le plus court entre plusieurs communes ou noeudRoutier en utilisant l'algorithme A*. L'application offre également des fonctionnalités supplémentaires telles que la gestion des utilisateurs, l'historique des trajets, le ping lors d'un clique sur la carte d'une destination et l'estimation de la consommation en fonction du véhicule choisi.

## Fonctionnalités

- Calcul de l'itinéraire le plus court entre plusieurs communes en utilisant l'algorithme A*.
- Gestion des utilisateurs (inscription, connexion, déconnexion).
- Historique des trajets effectués.
- Estimation de la consommation en fonction du véhicule choisi.
- Affichage et calcul des étapes du trajet (ex: Montpellier -> Paris -> Brest).
- Mise en cache par département pour optimiser les performances.

## Technologies utilisées

- PHP
- JavaScript
- Twig (moteur de templates)
- PostgreSQL (base de données)
- PostGIS (extension pour la manipulation de données géométriques)

## Installation

1. Cloner le dépôt Git : `git clone https://github.com/Xamez/NaviGator.git`
2. Installer les dépendances avec Composer : `composer install`
3. Importer la base de données PostgreSQL avec les données géométriques.
4. Configurer les paramètres de connexion à la base de données dans le fichier de configuration.
5. Configurer l'environnement de développement (xDebug, PHPUnit, etc.) selon les besoins.
6. Accéder à l'application via un navigateur web.

## Utilisation

1. S'inscrire ou se connecter à l'application.
2. Saisir les communes de départ et d'arrivée.
3. Choisir les options supplémentaires telles que le véhicule, les étapes du trajet, etc.
4. Cliquer sur le bouton "Calculer l'itinéraire".
5. Afficher le résultat avec l'itinéraire le plus court, la distance, le temps estimé et la consommation en carburant.
6. Consulter l'historique des trajets effectués.

## Images
![CalculNaviGator](Navigator1.png)
