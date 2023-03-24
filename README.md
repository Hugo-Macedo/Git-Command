<link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.15.4/css/all.css" integrity="sha384-DyZ88mC6Up2uqS4h/KRgHuoeGwBcD4Ng9SiP4dIRy0EXTlnuz47vAwmeGwVChigm" crossorigin="anonymous"/>

# Git Helper command line
Ceci est un guide pour les commandes git  de bases

    git init

Cette commande est utilisée pour initialiser un projet avec git

    git help config
    
Comme indiquée cette commande permet d'afficher toutes les configurations possible sur votre projet Git.

    git config -- global user.name "name"
    git config -- global user.mail "mail"
   
 Ces commandes permettent de configurer votre nom et mail, nécessaire à la configuration
 
    git status

Permet de voir l'état du dossier avec les fichiers qui sont trackés et ceux qui ne le sont pas
    
    git add (--all)
    
Permet de tracker les fichiers ou dossier, --all permet de tracker tous les documents.

    git commit -m
    
Pour enregister les modifs (y ajouter le message).

    git commit -a -m (message) 
    
Permet de commit tous les fichiers trackés.

    git log (-n 2 ou -online ou -p )
    
Permet de regarder les derniers commit -n 2 pour les 2 derniers commits, -online en une seule ligne et -p pour choisir un fichier particulier.

    git diff
    
Permet d'observer les différence apportées par rapport au dernier commit.

    git checkout (id du commit)

Permet de revenir en mode spéctateur sur le commit précisé.<i class="fa-solid fa-triangle-exclamation"></i> Aucune modification n'est possible. git checkout (branche) pour revenir dans le présent

    
