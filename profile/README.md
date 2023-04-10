# Company Poll
Company poll est une application de vote en ligne sécurisée.
## Notes d'installation :
0. Créer le réseau Docker permettant aux différents conteneurs de communiquer : 
```bash
docker network create companypoll-network
```
1. Lancer les conteneurs des keyholders
2. Lancer le scrutateur. Attendre que la clé publique soit générée
3. Lancer le serveur après la génération de la clé publique.
