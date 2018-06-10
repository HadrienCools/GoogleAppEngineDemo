

# Tutoriel Google app engine

Dans cet exemple on va simplemmemnt utiliser et tester les commandes de base de google appp engine et les exemples de base en mettant en place un micro-serveur sous Flask.


## Setup 

* La première étape est de créer son compte sur google app engine.
Aller dans le tableau de commande et créer un nouveau projet.
[Adresses du dashboard, il faut etre enregistré](https://console.cloud.google.com/home/)
* Aller dans la barre d'outils et cliquer sur "nouveau  projet", rentrer les informations demandées.
* La base du projet est maintenant crée, il faut le sélectionner dans la liste des projets, ici le projet sera appelé "VirtualisationTuto".

## Initialisation

* Une fois connecté au cloud shell, il est possible d'interagir avec celui-ci, la console est en réalité connectée avec une machine virtuelle située sur le cloud de google. 

* Se rendre dans l'exemple de flask ` cd ~/src/flaskapi-204813/python_gae_quickstart_editor-2018-05-21-15-10/appengine/standard/flask/hello_world `

* Lancer le serveur de test ` dev_appserver.py $PWD `

* Il est possible de configurer son environnement comme bon nous semble et d'installer ses pakages. 

* Pour Modifier la configuration il est possible d'éditer le fichier .YAML .

## Mise en Production

* Il faut se rendre à la page [De management des ressources. ](https://console.cloud.google.com/appengine?project=flaskapi-204813&serviceId=default&duration=PT1H)



* Pour déployer le serveur rentrer ` gcloud app deploy app.yaml --project flaskapi-204813 `

* Aller à ce [lien pour voir l'aplication en production](https://flaskapi-204813.appspot.com/).






