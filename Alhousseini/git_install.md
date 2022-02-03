# [Lien](https://www.youtube.com/watch?v=X_8Nh5XfRw0)


# DOCUMENTATION



## installations

### SSH

```bash
git status  
cd ~/.ssh  
ssh-keygen -t rsa -b 4096 -C "adresse mail de github"
eval "$(ssh-agent -s)"
ssh-add alhousseini
ssh -T git@github.com 
```
### GIT

```bashh

#apt get install git

## utilisation de git  
### initialisation d'un nouveau repository

# git init  
# git add  
# git commit (-am)  
# git branch -M nom du fichier   
# git remote add git@github.com  chemin du fichier
# git push -u origin main  

##Generer une clé ssh

# ssh-keygen -t rsa -b 4096 -C "votre adresse mail"
#eval "$(ssh-agent -s)"

##ajouter sa clé privé au dictionnaire

#ssh-add ~/.ssh/id_rsa 
##ou
#ss-add "nom du fichier ou est stocké la clé ssh"

##tester si ca marche

#ssh -T git@github.com




