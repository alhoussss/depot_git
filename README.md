# depot_git

Depôt exemple de tutos d'installation de git et de son utilisation.  

# But

Ce dépôt est à but pédagogique. Il ressence les différents tutoriels d'installations écrit par les élèves.

# Utilisation

## Pré-requis

Faire partie de la classe.

## Méthode

* Faire un *fork* du dépôt.
* Modifier le code.
* faire un *merge request*.

# Markdown

## Exemples d'utilisations

### Tutoriel pratique français

https://www.markdowntutorial.com/

### Tutoriel pratique anglais
https://commonmark.org/

## Documentation

### Bases (français)

https://documentation-snds.health-data-hub.fr/contribuer/guide_contribution/tutoriel_markdown.html#titres

### Bases (anglais)

https://www.markdownguide.org/basic-syntax/

### Avancé (anglais)

https://www.markdownguide.org/extended-syntax/

### Expert (anglais)

https://spec.commonmark.org/0.28/

# Git

## Créer un nouveau dépôt à partir de zéro

```bash
echo "# depot_git" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:DanielC-N/depot_git.git
git push -u origin main
```

