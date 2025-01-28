# TicTacToe Decentralized App

## Description
Ce projet est une application d�centralis�e (DApp) simple qui impl�mente un jeu de TicTacToe. L'application est h�berg�e sur IPFS via Pinata et utilise GitHub Actions pour automatiser le d�ploiement.

## Fonctionnalit�s
- Jeu de TicTacToe simple en HTML.
- H�bergement d�centralis� via IPFS.
- Automatisation du d�ploiement avec GitHub Actions.

## Structure du projet
+-- README.md # Documentation du projet. 
+-- LICENSE # Licence du projet.
src/ 
   +-- index.html # Le fichier principal contenant le jeu. 
.GitHub/
   +-- workflows/
	+--deploy.yml


## H�bergement
Le projet est h�berg� sur IPFS. Apr�s chaque mise � jour dans le d�p�t GitHub, un nouveau CID est g�n�r�, permettant d'acc�der � la derni�re version via le lien :

https://gateway.pinata.cloud/ipfs/bafkreida7e325zyqmrm4fymlmcen2p3qkieybbkv7fmf5htlwz37rbibjy


## D�pendances
- Compte Pinata pour h�berger les fichiers sur IPFS.
- Configuration de GitHub Actions pour l'automatisation des d�ploiements.

## Comment contribuer
1. Clonez le d�p�t :
   ```bash
   git clone <URL_DU_DEPOT>
   cd tictactoe-dapp
2. Cr�ez une nouvelle branche pour vos modifications :
   git checkout -b feature/nom-de-votre-feature
3. Commitez vos changements et poussez votre branche :
   git add .
   git commit -m "Ajout d'une nouvelle fonctionnalit�"
   git push origin feature/nom-de-votre-feature
4. Cr�ez une pull request sur GitHub.
