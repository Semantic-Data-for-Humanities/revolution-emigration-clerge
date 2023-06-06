# revolution-emigration-clerge

## Utilisation des carnets

L'utilisation des carnets est proposée selon deux modalités:

* soit on clone ce dépôt et on exécute le code localement. Dans ce cas il est nécessaire de:
  *  créer un environnement conda contenant les paquets nécessaires listés dans le fichier environment.yml
  *  commande à exécuter:\
  <code bash>conda env create -f environment.yml</code>\
  Cf. la documentation de [cette page](https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html#creating-an-environment-from-an-environment-yml-file)
  *  activer le nouvel environnement _emigration_ dans jupyter lab (cf. [ces instructions](http://phn-wiki.ish-lyon.cnrs.fr/doku.php?id=python:environnement_conda&#recette))
  *  copier les fichiers à traiter dans le dossier 'fichiers'
* soit en exécutant ce dépôt de code dans Binder [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Semantic-Data-for-Humanities/revolution-emigration-clerge/main)
  * dans ce cas il faudra d'une part télécharger les fichiers à traiter dans le dossier 'fichiers' de l'espace Binder
  *  d'autre part, exporter les fichiers contenant les résultats vers son propre ordinateur
