# WIK-DPS-TP01-Lucas

 A savoir :
- Le projet est basé sur TypeScript et a été conçu pour fonctionner sur un système Windows. 
- Le script réalisé se situe dans TP1.1>src>index.ts.
- L'unique variable d'environnement doit s'appeler PING_LISTEN_PORT elle permet de spécifier le port du serveur HTTP.
- Redémarrer VS Studio Code à chaque fois que la variable d'environnement du port est modifiée dans Windows.
- Node.js doit être installé sur le poste.
- Pour transpiler, utiliser la commande "npx tsc".
    
Fonctionnement du projet :

- Démarrer le serveur HTTP :
      Dans un terminal Vs Studio Code, en ayant le projet ouvert, entrer la commande "node build/index.js" le serveur démarre avec le port précisé dans la variable         PING_LISTEN_PORT.
    
- Utiliser l'API : 
      Dans un autre terminal, utiliser la commande curl http://127.0.0.1:'numéro_de_port_choisi'/ping -v avec cette commande la requête est bien GET /ping alors le         résultat de commande sera Ok.
