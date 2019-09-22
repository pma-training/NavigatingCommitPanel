# Navigating the Commit Panel
How to use the commit panel and its functions to commit changes to .do files (_Français ci-dessous_)

_Video:_ [Navigating the Commit Panel](https://www.youtube.com/watch?v=ZooZz4B2rPY&list=PLaCCIQf3NY979c70cnegKx8Cmo3Wltkia&index=5&t=0s)

### Summary 
Introduces users to how to understand commits made by other GitHub users

#### By the end of this video, you should know how to use each of the following GitKraken functionalities:
- Read the commit graph
- Identify a commit summary and description
- Identify the author of a commit
- Identify the details of the comment
- Identify which files were updated
- Identify all files in the repository
- Open the Diff Viewer
- Open the File Viewer
- Open and read Hunk View
- Open and read Inline View
- Open and read Split View


### Commit Definition
An individual change to a file or several files that includes specific information on who made the commit, when the commit was made, and a description of what occurred in the commit. 

### Key Commit Features
#### Commit Graph:
Each commit is displayed in the commit graph and is identified by a small circle that indicates who made the commit, and the commit summary. When you click on a commit, the following information will be displayed in the commit panel:
- Commit Summary: A summary of the commit
- Commit Description: A more in-depth description of what occurred during the commit
- Number of files: Number of files that were affected by the commit
- Icons indicating the type of change
    - Orange: Modified
    - Red: Deleted
    - Green: Added
    - Blue: Renamed

#### Diff Viewer:
When you click on a commited file in the commit panel, the diff viewer will open. The diff viewer allows you to see the before and after of the file.  There are multiple ways to display the information in the diff check, they are:
- File View: Shows all of the code as is, does not highlight differences
  - History: Lists all the commits that affected the given file
  - Blame: A more in-depth look at the commit history of the file
- Diff View: Shows exactly what changed in a file. Red lines are deletions and green lines are additions
  - Hunk View: Shows changes to the .do files in chunks of code, only displays what has changed (not the entire file)
  - In-line View: Shows changes to the .do file imbedded in the entire file
    - The sidebar displays where you are in the .do file and where the changes are located
  - Split View: Displays the old version of the .do file side-by-side with the new version of the .do file
    - The sidebar displays where you are in the .do file and where the changes are located
  - Navigation arrows: Allows users to jump from one change to another
  - Ignore Whitespace: Function to ignore all changes that are not written text, such as additions of spaces, indentations and enters


### Glossary of terms:
| Term | Definition |
| ---- | ---------- |
| Branch | A branch is a parallel version of a repository that allows you to work freely without disrupting the master version of a file. PMA uses branches to update .do file content and prepare .do files for round specific data collection |
| Commit | A commit is a way to save a change to a file that also stores information on what changes were made, when and by who. PMA uses commits to systematically document changes to .do files |
| Master | The default branch that is made each time a new repository is created. At PMA, the master branch contains the template of any give .do file. No changes should be made in the master branch |
| Repository | Contains all of the project files and documentation and stores each file’s revision history. Can have multiple collaborators. PMA keeps its .do files in repositories that are organized by survey type and action |
| Tag | Active points to commits that do not move. PMA tags the final commit before releasing data products so the version of the specific .do file can be easily referenced for future use |


_________________________________________________________________


# Naviguer sur le Panel de Commit
Comment utiliser le panel de commit et ses fonctionnalités pour engager (commit) les modifications de .do files.

_Vidéo:_ [Naviguer le Commit Panel](https://www.youtube.com/watch?v=_310YSrp2V4&list=PLaCCIQf3NY97bYG9q4ha8mEUlM8W7kJpE&index=5&t=0s)

### Résumé  
Explique aux utilisateurs/trices comment comprendre les commits effectués par d’autres utilisateurs de GitHub

#### À la fin de la vidéo, vous devriez savoir utiliser chacune des fonctionnalités de GitKraken suivantes :
- Lire le graphique des commits 
- Identifier le résumé et la description d’un commit 
- Identifier l’auteur d’un commit
- Identifier les détails d’un commentaire
- Identifier quels fichiers ont été mis à jour 
- Identifier tous les fichiers d’un repository
- Ouvrir en Diff View
- Ouvrir en File View
- Ouvrir et lire en Hunk View
- Ouvrir et lire en Inline View
- Ouvrir et lire en Split View


### Définition d'un Commit
DESCRIPTION
Modification individuelle effectuée dans un fichier ou plusieurs fichiers, comprenant des informations spécifiques sur qui a effectué le commit, quand le commit a été fait, et une description de ce qui s’est produit dans le commit. 

### Functionnalités clés d'un commit
#### Graphique des commits :
Chaque commit s’affiche dans le graphique des commits et peut être identifié par un petit cercle indiquant qui a effectué le commit, et le résumé du commit. Lorsque vous cliquez sur un commit, les informations suivantes s’afficheront dans le panel de commit :
- « Commit Summary » : Résumé du commit
- « Commit Description » : Description plus détaillée de ce qui s’est produit pendant le commit
- « Number of files » : Nombre de fichiers affectés par le commit
- Icônes indiquant le type de modification :  
  - Orange : Modifié
  - Rouge : Effacé
  - Vert : Ajouté
  - Bleu : Renommé
  
#### Diff Viewer :
En cliquant sur un fichier dans lequel des modifications ont été engagées (commit) dans le panel du commit, le lecteur diff s’ouvrira. Le lecteur diff vous permet de visualiser l’avant et l’après d’un fichier. Vous pouvez afficher ces informations de plusieurs manières :
- « File View » : Vous montre le code tel qu’il est, sans mettre en évidence les différences 
  - « History » : Référence tous les commits ayant affecté le fichier 
  - « Blame » : Visualisation plus détaillée de l’historique des commits du fichier
- « Diff View » : Vous montre exactement ce qui a été modifié dans un fichier. Les lignes rouges représentent des suppressions et les vertes des ajouts. 
  - « Hunk View » : Vous montre les modifications des .do files par « morceaux » de code, n’affichant que ce qui a été modifié (pas le fichier entier).
  - « In-line View » : Vous montre les modifications des .do files intégrées au fichier entier.
    - La barre latérale indique l’endroit où vous vous trouvez dans le .do file et où les modifications sont situées. 
  - « Split View » : Affiche l’ancienne version du .do file à côté de la nouvelle version. 
    - La barre latérale affiche l’endroit où vous vous trouvez dans le .do file et où les modifications sont situées.  
  - Flèches de navigation : Permet aux utilisateurs de passer d’une modification à une autre. 
  - « Ignore Whitespace » : Fonction permettant d’ignorer toutes les modifications qui ne sont pas du texte écrit, comme les ajouts d’espaces, les alinéas, les retours à la ligne, etc. 


### Glossaire :
| Terme | Definition |
| ---- | ---------- |
| Branch | Version parallèle d’un repository permettant de travailler librement sans perturber la version master d’un fichier. PMA utilise des branches pour mettre à jour le contenu des dofiles et les préparer pour la collecte de données d’une vague d’enquête spécifique. |
| Commit | Manière de sauvegarder une modification d’un fichier en stockant aussi des informations sur les changements qui ont été faits, quand et par qui. PMA utilise des commits pour documenter systématiquement les modifications des .do files |
| Master | Branch par défaut générée à chaque fois qu’un nouveau repository est créé. À PMA, la master branch contient le modèle de chaque .do file. Aucune modification ne devrait être apportée à la master branch |
| Repository | Contient tous les fichiers et la documentation du projet, et stocke l’historique de révision de chaque fichier. Peut avoir plusieurs collaborateurs. PMA garde ses .do files dans des repositories organisés par type d’enquête et d’action |
| Tag | Points actifs des commits qui ne bougent pas. PMA attribue un tag au commit final avant de publier les produits de données pour que la version spécifique d’un .do file soit référencée et puisse être facilement utilisée plus tard |
