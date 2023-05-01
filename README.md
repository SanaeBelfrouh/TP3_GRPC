# Activité Pratique N°3 - GRPC

Dans le cadre de notre TP, nous avons travaillé sur GRPC (Google Remote Procedure Call), une technologie de communication inter-processus développée par Google. Le but de ce TP est de se familiariser avec GRPC et de comprendre comment il peut être utilisé pour créer des services distribués.
Ci-dessous, vous trouverez des captures d'écran des clients GRPC utilisant chacun des quatre modèles :

## => Première Partie 

### - Unary Model
     Dans le modèle Unary, le client envoie une seule requête au serveur et attend une réponse. 

#### 🎯 En utilisant BloomRPC
![alt text](https://user-images.githubusercontent.com/116807307/235531460-5d029f66-e48d-4f4d-8f4e-feb44c2fe738.gif)
#### 🎯 Un client java 
![alt text](https://user-images.githubusercontent.com/116807307/235531614-4d344e06-37a7-4976-b4df-35442acc2124.gif)
### - Server Sreaming Model
     Dans le modèle Server Streaming, le client envoie une requête et le serveur envoie plusieurs réponses en retour.

#### 🎯 En utilisant BloomRPC
![alt text](https://user-images.githubusercontent.com/116807307/235536289-970455af-08b9-4631-8e55-33d8698e6f66.gif)

#### 🎯 Un client java 
![alt text](https://user-images.githubusercontent.com/116807307/235536001-2f27f45d-9c6a-4fce-8c30-153bfa5d0549.gif)


- Client Streaming Model

#### 🎯 En utilisant BloomRPC
![alt text](https://user-images.githubusercontent.com/116807307/235536715-e63634d1-021f-45b4-961d-6d23ff01007a.gif)

#### 🎯 Un client java
![alt text](https://user-images.githubusercontent.com/116807307/235540574-70df1e6d-04a2-4a02-a9bd-96b25510d879.gif)


- BiDirectional Streaming Model
#### 🎯 En utilisant BloomRPC

#### 🎯 Un client java 


=> Deuxième partie
 1. Créer un serveur Chat GRPC
 2. Tester le serveur Chat avec un client GRPC comme BloomRPC
 🎯
 3. Créer un client GRPC Java
 🎯
 4. Créer un client GRPC Python
 🎯
=> Troisième partie
 1. Créer un serveur JEU GRPC :
     - Au démarrage le serveur choisit un nombre aléatoire entre 1 et 1000. 
     - Ensuite les clients GRPC doivent deviner en compétition le nombre secret.
     - le serveur répond à chaque fois avec les éventualités suivantes :
        . Votre nombre est plus grand
        . Votre nombre est plus petit
        . BRAVO vous avez gagné et envoyer le gagnant aux clients
        . Jeu terminé, le gagnant est ""Numéro du gagnant"
