# dns
la vue personnalisée est conçue pour surveiller le service DNS et afficher uniquement les événements critiques, erreurs, avertissements et certaines informations spécifiques (démarrage/arrêt du service).  

La vue personnalisée sélectionne uniquement les événements liés au DNS.  
Sélection des niveaux d’événements :  

Critique (1) : Problèmes graves affectant le fonctionnement.  
Erreur (2) : Échecs nécessitant une action.  
Avertissement (3) : Problèmes potentiels à surveiller.  
Information (4) : Événements généraux (ex. démarrage/arrêt du DNS).  
Filtrage par sources d’événements :  

DNS-Server-Service : Suit les opérations du serveur DNS.  
DNS Client Events : Enregistre les requêtes/réponses DNS des clients.  
Filtrage par ID d’événements (événements spécifiques au DNS) :  

2 : Démarrage du service DNS.  
4 : Arrêt du service DNS.  
409 : Échec de résolution DNS.  
501-502 : Échec de chargement d’une zone DNS.  
6001-6002 : Problèmes de réplication DNS.  
