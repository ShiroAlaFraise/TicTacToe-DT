# TicTacToe Decentralized App

## Description
Ce projet est une application décentralisée (DApp) simple qui implémente un jeu de TicTacToe. L'application est hébergée sur IPFS via Pinata et utilise GitHub Actions pour automatiser le déploiement.

## Fonctionnalités
- Jeu de TicTacToe simple en HTML.
- Hébergement décentralisé via IPFS.
- Automatisation du déploiement avec GitHub Actions.

## Structure du projet
+-- README.md # Documentation du projet. 
+-- LICENSE # Licence du projet.
src/ 
   +-- index.html # Le fichier principal contenant le jeu. 
.GitHub/
   +-- workflows/
	+--deploy.yml


## Hébergement
Le projet est hébergé sur IPFS. Après chaque mise à jour dans le dépôt GitHub, un nouveau CID est généré, permettant d'accéder à la dernière version via le lien :

https://gateway.pinata.cloud/ipfs/bafkreida7e325zyqmrm4fymlmcen2p3qkieybbkv7fmf5htlwz37rbibjy


## Dépendances
- Compte Pinata pour héberger les fichiers sur IPFS.
- Configuration de GitHub Actions pour l'automatisation des déploiements.

## Comment contribuer
1. Clonez le dépôt :
   ```bash
   git clone <URL_DU_DEPOT>
   cd tictactoe-dapp
2. Créez une nouvelle branche pour vos modifications :
   git checkout -b feature/nom-de-votre-feature
3. Commitez vos changements et poussez votre branche :
   git add .
   git commit -m "Ajout d'une nouvelle fonctionnalité"
   git push origin feature/nom-de-votre-feature
4. Créez une pull request sur GitHub.
