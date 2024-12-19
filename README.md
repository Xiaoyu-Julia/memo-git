# memo-git
La prise de note sur l'apprentissage de git.
Lien pour télécharger l'outil Git-it  : https://github.com/jlord/git-it-electron (cliquer sur releases pour trouver le .zip à installer selon le system de l'ordinateur).

Les lignes de commandes Linux : 
- Créer un nouveau dossier : mkdir <FOLDERNAME>
- Naviguer entre les répertoires : cd <FOLDERNAME>
- Lister les éléments dans un répertoire : ls
- Voir le chemin absolu du répertoire de travail dans lequel on se trouve : pwd
- Renommer un fichier : mv old_file_name new_file_name
- Déplacer un fichier dans un autre répertoire : mv file_path destination_directory
- Déplacer un répertoire : mv directory_path destination_directory
- Supprimer un fichier : rm file_name
- Supprimer un répertoire et son contenu : rm -r directory_name

Les commandes git :
- Activez Git pour un repertoire : git init
- Vérifiez l'état des modifications dans un dépôt : git status
- Afficher les modifications apportés aux fichiers : git diff
- Ajouter les modifications d'un fichier à soumettre : git add <FILENAME>
- Pour ajouter toutes les modifications d'un seul coup : git add .
- Pour soumettre les modifications que vous avez ajoutées avec un court message décrivant les modifications : git commit -m "your commit message"
- Créer une branche main : git branch -M main
- Déposer sur un repository existant: git push -u origin main
- Pour supprimer un fichier déposé sur git : git rm <FILENAME>
- Ajoutez le nom d'utilisateur à la configuration Git: git config --global user.username <USerNamE> (pas besoin de noter <> dans la commande lors d'ajout du nom d'utilisateur
- Vérifier le nom d'utilisateur configuré dans Git en tapant: git config --global user.username
- Voir les différents commits effectués dans le répertoire dans l'ordre chronologique inverse : git log
- Changer de branche ou restaurer les fichiers de l'arborescence de travail : git checkout
- Réinitialiser la HEAD actuelle à l'état spécifié : git reset
