# Exemple de submodule avec git

## Commandes:

- Pour clone le projet avec les submodules: `git clone <url> --recursive`
- Pour ajouter un repo en tant que submodule: `git submodule add <url>`
- Pour mettre à jour les submodules: `git submodule update --init --recursive`
- Pour lancer un pull sur tous les submodules: `git submodule foreach git pull origin master`