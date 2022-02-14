# [Lien](https://www.youtube.com/watch?v=X_8Nh5XfRw0)


# DOCUMENTATION



# installations

## GIT

apt get install git

## SSH
### Generer une clé ssh

ssh-keygen -t rsa -b 4096 -C "votre adresse mail"
eval "$(ssh-agent -s)"

##ajouter sa clé privé au dictionnaire

ssh-add ~/.ssh/id_rsa 

##ou

#ss-add "nom du fichier ou est stocké la clé ssh"

##tester si ca marche

#ssh -T git@github.com

# utilisation de git  
## initialisation d'un nouveau repository

```bash

 git config --global user.mail ""
 git config --global user.name ""
 git init  
 git add .
 git commit -m  "votre message"
 git branch -M nom du fichier   
 git remote add git@github.com  chemin du fichier
 git push -u origin main  
```

 ##commandes à savoir

```bash
 git pull: permet de tirer des modifications à partir du serveur main
 git diff: permet de voir les modifications apportées sur un fichier
 git log: permet de voir le moment ou les lignes ont été modifiés
 git stash: prend nos modifs et les empile ailleurs
 git stash pop : prend et enlève l'element le plus recent de la pile
 git stash clear: supprime les éléments de la liste
 .gitignore: les fichiers qui seront ignorés par la commande git add .
 **/*.extensions à supprimer
 ```

## manipulation des branches
```bash

git branch:permet de créer une branche
git checkout -b "nom de la branche":permet de créer une nouvelle branche
git branch –d "nom branche":supprime une branche
git checkout "nom branche":permet de passer d'une branche à une autre
git merge "nom branche": La commande git merge est utilisée pour fusionner une branche dans la branche active
git branch -r :affiche les branches presentent sur la branche principale
git merge:permet de faire fusionner deux branches
git push origin -d "nom branche":supprime une branche en remote
```






