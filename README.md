Activité Pratique N°3 - GRPC
=> Première Partie :
- Unary Model
![VD1](https://user-images.githubusercontent.com/116807307/235531460-5d029f66-e48d-4f4d-8f4e-feb44c2fe738.gif)
![VD2](https://user-images.githubusercontent.com/116807307/235531614-4d344e06-37a7-4976-b4df-35442acc2124.gif)
- Server Sreaming Model
- Client Streaming Model
- BiDirectional Streaming Model
Pour le cas d'une conversion de monnaie

=> Deuxième partie
 1. Créer un serveur Chat GRPC
 2. Tester le serveur Chat avec un client GRPC comme BloomRPC
 3. Créer un client GRPC Java
 4. Créer un client GRPC Python

=> Troisième partie
 1. Créer un serveur JEU GRPC :
     - Au démarrage le serveur choisit un nombre aléatoire entre 1 et 1000. 
     - Ensuite les clients GRPC doivent deviner en compétition le nombre secret.
     - le serveur répond à chaque fois avec les éventualités suivantes :
        . Votre nombre est plus grand
        . Votre nombre est plus petit
        . BRAVO vous avez gagné et envoyer le gagnant aux clients
        . Jeu terminé, le gagnant est ""Numéro du gagnant"
