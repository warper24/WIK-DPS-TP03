﻿# WIK-DPS-TP03
 
 Création d'un **fichier docker-compose.yaml** pour configurer docker compose
 
 On run **docker-compose.yaml** avec pour seul service un container basé sur le Dockerfile créé dans le TP WIK-DPS-TP02

On rajoute a **docker-compose.yaml** 4 réplicas et on le run.

On rajoute ensuite à **docker-compose.yaml** un reverse proxy(nginx) et on l'expose sur notre hôte sur le port 8080

On configure le fichier **nginx.conf** pour loadbalancer les requêtes vers le service basé sur votre image

Et pour finir on modifie notre fichier **index.ts** pour afficher le hostname dans les logs à chaque requête sur /ping.

# FIN
