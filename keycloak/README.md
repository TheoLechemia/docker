Doc
===

Fichier docker-compose pour deployer keycloak avec une base PostgreSQL.
Ajoute une extension pour filtrer les utilisateurs pour certains clients : https://github.com/sventorben/keycloak-restrict-client-auth

Copier le fichier `.env.example` en fichier `.env` et le renseigner.

Lancer l'app : 

::
    docker-compose up