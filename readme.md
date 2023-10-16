# Application Docker avec Serveur Node.js et Client React

Ce projet est une application web composée d'un serveur Node.js et d'une application client React. Les deux sont configurés pour s'exécuter dans des conteneurs Docker. 

## Prérequis

Avant de commencer, assurez-vous d'avoir les éléments suivants installés sur votre système :

- [Docker](https://www.docker.com/get-started)

## Clonage du dépôt

Clonez ce dépôt sur votre ordinateur en utilisant la commande suivante :

```bash
git clone  git@github.com:Ptbambie/Docker-React_test.git
cd Docker-React_test

## Démarrage de l'application

Pour lancer l'application en mode développement, suivez ces étapes :

Assurez-vous d'être dans le répertoire du projet.

Exécutez la commande suivante pour construire et lancer les conteneurs Docker :

```bash
docker compose -f docker-compose.dev.yml up --build

Cela lancera les conteneurs Docker du serveur Node.js, du client React et de MongoDB.

Une fois que les conteneurs sont démarrés, l'application React sera accessible à l'adresse http://localhost:8080 dans votre navigateur.

Le serveur Node.js sera accessible à l'adresse

```bash
http://localhost:5050.

## Arrêt de l'application
Pour arrêter l'application, utilisez la combinaison de touches Ctrl + C dans le terminal où Docker Compose est en cours d'exécution.

