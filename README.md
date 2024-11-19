# presentation 
  le present repos contient de la documentation qui est basé sur le code disponible a l'adresse suivante : https://github.com/melchaubaroux/stage

# Documentation technique

  ## gestion des accées : 
    l'authentification se fait par un systeme de login/mot de passe 

  ## roles utilisateurs : 
    il n'existe qu'un seul type de roles utilsateur , ceux ci ont accées a toutes les services, cependant seul les developeur ont accées a certains endpoints comme celui de remise a zéro des tables de données

  ## dépendance logiciel : 
    python 
    postgressql
    ollama

  ## Données impliquées :
    données audio (compatible avec ffmpeg soit tous les types de fichiers audio classiques compressé ou non )
    données textuel (format exploitable par le lecteur de fichier natif de python: txt ,bin ) 

  ## protection de la donnée :
    les données ne sont accessible que par les employé.
    pour les données soumis au rgpd il suffit de mettre a jour le fichier de support de la vectorisation et remplacer le fichier dans la base 
    
  ## procedure d'installation : 
    cloner le repos fournis plus haut 
    installer python 3 (le code fonctionne sous 3.11.5)
    intstaller Node.js (`20.17.0`) et npm (`10.8.2`).
    installer postgressql et son extension pg vector
    installer ollama 
    aller dans le sous dossier du front et faire npm install
    aller dans le sous dossier du composant whisper et écrire pip install requirements.txt
    
    

    
    
    
