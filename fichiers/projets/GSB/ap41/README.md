# Dépot GIT Groupe 41

## Elèves du groupe : 

#### SISR :
* Corentin HURTRET
* Elam MONNOT


## Tuto Git 

#### Git sur le serveur Docker

* Cloner le dépot : `git clone http://docker.sio.lan:3000/u-ap41/ap41.git`
* Ajouter les fichiers : `git add *`
* Mettre un commentaire : `git commit -am "commentaire"`
* Ajouter un tag : `git tag v0.0.x`
* Envoyer les fichiers : `git push`
* Envoyer les tags : `git push --tag`
* Mettre à jour le dépot : `git pull`\
A faire a chaque fois avant de push.

Identifiant : u-ap41\
Mot de passe : rootAP41

#### Git sur le serveur ap41-test

* Cloner le dépot : `git clone http://docker.sio.lan:3000/u-ap41/ap41.git`
* Ajouter les fichiers : `git add *`
* Mettre un commentaire : `git commit -am "commentaire"`
* Ajouter un tag : `git tag v0.0.x`
* Envoyer les fichiers : `git push ap41-test `
* Envoyer les tags : `git push --tag ap41-test `
* Route : `git remote add ap41-test ssh://git@ap41-test:/home/git/web`
* Mettre à jour le dépot : `git pull`\
A faire a chaque fois avant de push.

Identifiant : git\
Mot de passe : git