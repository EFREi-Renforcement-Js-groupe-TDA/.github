# MyCv

Projet final du cours de renforcement javascript.

Groupe : 
- Thomas L. (Orden14)
- David W. (niceley)
- Antoine Huchard

## Contexte

Le but de ce projet est de créer une application de génération de CV.  
Nous avons décidé de séparer ceci en deux projets distincts : myCvApi et myCvStoreFront.

## Env

- Node version : 20.13.1  
- Npm version : 10.8.3  
- Mongodb docker : [lien](https://www.mongodb.com/docs/manual/tutorial/install-mongodb-community-with-docker/#std-label-docker-mongodb-community-install)

## Setup
Si vous utilisez un setup de mongodb different, modifier les variables d'environnement dans le fichier .env.local du projet myCvApi.

Pour lancer le projet : 
- Clonez myCvApi et myCvStoreFront
- Assurez-vous que mongodb est lancé
- Exécutez la commande "npm install" dans chacun des projets
- Exécutez la commande "npm start" dans chacun des projets

L'API sera accessible à l'adresse : http://localhost:3000 et le storefront est disponible à l'adresse : http://localhost:8001
