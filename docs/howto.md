# Comment a été réalisé ce site web 

* [Rédaction : mkdocs](https://www.mkdocs.org/)
* [Thème : materials for mkdocs](https://squidfunk.github.io/mkdocs-material/)
* [Hosting : github pages](https://pages.github.com/)

## Procédure détaillée :

* Dans Web/bia-web
* `git status` : pour savoir quels fichiers ont été modifiés,
* `git add *` : pour accepter les fichiers modifiés,
* `git rm --cached -r <dir>' : si besoin de supprimer un répertoire de la liste des fichiers à 'commiter'
* `git rm --cached <file>' : si besoin de supprimer un fichier à 'commiter'
* `git commit -m "message pour le commit"` : pour réaliser un commit local
* `git push origin master` : pour transférer les sources sur GitHub
* `mkdocs gh-deploy --ignore-version` : pour publier le site. 
