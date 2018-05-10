# Event-brite like, Devise Version
Créations d'app Ruby on Rails mises en ligne avec Heroku



![alt tag](images/img-marseille-3.png)

-------------

# Introduction : Présentation de l'équipe

## ** WEST COAST MARSEILLE**

##- Audrey (@audreycouture)

##- Jerome (@Jerome)

##- Damien (@damien13005)

##- Maxime (@Maxime)

##- Sam (@sam)


##Fait en pair programming

![alt tag](images/pairProgramming.jpg)

-------------

# But de l´exercice

Pour ce Jeudi 10 Mai 2018 dans le cadre de l'approfondissement de Ruby on Rails, nous devions créer une une landing page pour the hacking project.

Notre cahier des charges :

1. Proposer 1 version de la landing page THP
2. Favoriser le CTA (call to Action)
3. Créer une esthétique et un design authentique
4. Design dynamique
5. Optimiser l'apparition sur Google
6. Action Intégrer des outils : 
        ◦ D'analyse de visites via Google Analytics
        ◦ De gestion des Newsletter via MailChimp
7.  Lier cette landing page à des outils d’acquisition
        ◦ Bot Twitter
        ◦ Scrapping
        ◦ ID de génie
8. Favoriser le CTA call to Action
------------   



# Consignes d'utilisation

## Tests en local:

Pour ouvrir chaque app et la tester il faut downloader le dossier, se placer dedans dans votre terminal et lancer en commande:

> $ bundle install --without production


Pour voir la base données exécuter en commande un

> $ rails db:migrate

Puis tapez la commande suivante pour tester en local l'appli:

> $ rails server

La vous pouver vous balader sur notre code.

Puis ouvrir le fichier sqlite dans le dossier db de l'app, soit avec dbBrowser soit avec SqliteStudio ou autre et visionner.

et Tester la Version en Local host en allant dans ton navigateur sur :

> localhost:3000



## Test en ligne:

Aller sur les liens Heroku suivants


> https://pure-beyond-78575.herokuapp.com



------------


# Explications détaillés 

------------- choix du design  -------------

2 personnes ont disséqué  les ressources proposées pour retenir certains points clés : 
        ◦ Des éléments visuels attirants
        ◦ Ne pas trop charger la lending page
        ◦ Pas de Nav Bar (pour favoriser le call to action) 
        ◦ Attirer le clic et favoriser les contacts 

------------- comment le code a été fait : -------------

    1. Nouveau projet Rails : landing page
        a. $ rails new landing_pages
        b. Modif du gemfile (pour integration heroku ) 
    2. Nouveau Repo sur Github
        a. cd dossier landing_page
        b. $ git init 
        c. $ git remote
        d. $ git Add . 
        e. $ git commit -m’’firstcommit’’
        f. $ git push 
    3. Heroku compatible
        a. $ heroku create
        b. $ git add .
        c. $ git commit -m’’heroku’’
        d. $ git push heroku master
        e. Succés avec site en ligne appelé https://pure-beyond-78575.herokuapp.com
    4. Créer un compte Mailchimp 
        a. Créer un fichier .env avec les clées API de Mailchimp
        b. Dans le gitiniore rajouter le .env
        c. Sur mailchimp.com paramétrer avec le site heroku  
    5. Ajout de Boostrap
        a. Insertion des liens boostrap (du CDN) dans application html  
    6. Envoi de requetes sur Twitter à l'aide d'un bot
	a. Compte Twitter : https://twitter.com/hackingproject_?lang=en

-------------  choix des éléments -------------

    • Ne demander que l’email pas de prenom ; 
    • Pas de header ni de Footer 
    

------------- pourquoi la page a telle structure -------------

    • Ne demander que l’email pas de prenom ; 
    • Pas de header ni de Footer 

------------- choix des sous-parties ------------- 

    • Ne demander que l’email pas de prenom ; 
    • Pas de header ni de Footer 


# Résultats

Réception de 500 mails grâce au bot Twitter.

A vous de voir ;)


Merci pour la correction ! 
