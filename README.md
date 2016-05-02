# Stage Louis 2016

## Intro

Cette répertoire git va servir de cahier de laboratoire pour le stage de Louis
à l'été 2016. Les tâches seront définies à travers le système d'Issues.

## Matériel didactique

### git

* [Intro sur les commandes de base de git.](https://rogerdudler.github.io/git-guide/)
* [Github flow](https://guides.github.com/introduction/flow/)
* [Comment écrire des bons messages de commit.](http://chris.beams.io/posts/git-commit/)
* [Syntaxe markdown de github](https://help.github.com/categories/writing-on-github/)
* [Introduction aux paquets R](https://hilaryparker.com/2014/04/29/writing-an-r-package-from-scratch/)
* [Guide sur les paquets R](http://r-pkgs.had.co.nz/)

**Note**: Les commandes les plus importantes sont `init`, `add`, `commit`, `push` et `pull`.

### Le format JSON

* [JSON primer](http://guide.couchdb.org/draft/json.html)

### Les projets ENCODE et Roadmap

* [ENCODE](http://www.nature.com/nature/journal/v489/n7414/abs/nature11247.html)
* [Roadmap](http://www.nature.com/nbt/journal/v28/n10/abs/nbt1010-1045.html)
* [L'API REST d'ENCODE](https://www.encodeproject.org/help/rest-api/)
* [Le schéma des tables d'ENCODE](https://github.com/ENCODE-DCC/encoded/tree/master/src/encoded/schemas)

### Le langage R

* [Petite intro de R](https://cran.r-project.org/doc/contrib/Torfs+Brauer-Short-R-Intro.pdf)
* [`jsonlite`](https://cran.r-project.org/web/packages/jsonlite/index.html)
* [`data.table`](https://github.com/Rdatatable/data.table/wiki)
* [`shiny`](https://github.com/CharlesJB/Stage_Louis_2016/shiny.rstudio.com)

## Les *pull requests*

Les pull request devront respecter les critères suivant:
* **Le code doit être fonctionnel!**
 * `R CMD build`
 * `R CMD check`
 * `R CMD BiocCheck`
* La mise en forme du code doit respecter le
[*coding style* de Bioconductor](https://www.bioconductor.org/developers/how-to/coding-style/).
* Les tests unitaires doivent être à jour pour valider que les changements
  fonctionnent comme prévu.
* Le fichier `NEWS` doit être mis à jour.
* La version du logiciel dans le fichier `DESCRIPTION` doit être incrémentée.
* Le message du commit doit être clair et complet.
