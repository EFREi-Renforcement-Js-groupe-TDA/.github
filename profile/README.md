# MyCv

Projet final du cours de renforcement javascript.

Groupe 8 : 
- Thomas L. (Orden14)
- David W. (niceley)
- Antoine Huchard

## Demo

La version de démonstration est disponible en ligne : https://mycvstorefront-tda.netlify.app/ (La démo en ligne sera disponible jusqu'au 19/11/2024)

## Env

- Node version : 20.13.1  
- Npm version : 10.8.3  
- Mongodb docker : [lien](https://www.mongodb.com/docs/manual/tutorial/install-mongodb-community-with-docker/#std-label-docker-mongodb-community-install)

## Setup
Si vous utilisez un setup de mongodb different, modifier les variables d'environnement dans le fichier .env.local du projet MyCvApi.

Pour lancer le projet : 
- Clonez les repository MyCvApi et MyCvStoreFront (disponibles sur la page de l'organisation ([lien](https://github.com/EFREi-Renforcement-Js-groupe-TDA/))
- Assurez-vous que mongodb est lancé
- Exécutez la commande "npm install" dans chacun des projets
- Exécutez la commande "npm start" dans chacun des projets

L'API sera accessible sur l'adresse : http://localhost:3003 et le storefront est disponible sur l'adresse : http://localhost:8001

## Commits
Les commits doivent impérativement être fait en ligne de commande (ne pas utiliser l'intrégration git de vsc/jetbrains) pour que husky puisse effectuer les pre-commit (prettier & eslint) correctement.
