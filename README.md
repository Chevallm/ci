# Formulaire en plusieurs étapes sans session - Cargo

## Description
Reprise d'un ancien projet Java EE adapté mais adapté avec le plugin Cargo afin de permettre son déploiement automatique sur un container LXC TomEE une fois compilé par Jenkins

## A noter
Afin de faciliter l'utilisation, j'ai créé un profil Maven spécifique pour le déploiement avec Cargo. 
La commande utilisée par Jenkins s'en trouve donc un peu modifiée (ajout d'un __-P CI__)