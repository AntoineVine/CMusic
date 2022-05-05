#Projet CMusic

- To launch the application, launch main.c 

##Client Fonctionnel 

Pour les versions Windows : aller dans common.h -> modifier #define MAC en #define WINDOWS

Pour les versions Mac : aller dans common.h -> modifier #define WINDOWS en #define MAC

##Serveur 
Serveur en nodeJS : se lance avec la commande :

```npx node-media-server```

Lancement de la musique avec :

```ffmpeg -i {fichier audio} -f flv -vn rtmp://localhost/live/STREAM_NAME```

