# Module M2 : Data-analyse

## Notebook
* `m2-brief0.ipynb` : Notebook d'exercice brief 0, prise en main
* `m2-brief1.ipynb` : Notebook d'exercice brief 1, approfondissement
* `m2-brief2.ipynb` : Notebook exercice final d'analyse et d'exploitation d'un dataset dans le bug de la création d'un modele.

## Dataset

On ne s'interesse qu'au dataset pour `m2-brief2.ipynb`, les autres dataset ont été destiné a faire des exercices et ne sera pas réellement exploité.

Dans cette analyse les fichiers de donnés sont stocké dans le dossier `data`:
* le dataset source est `dataset.csv`, ce fichier est une copie du fichier `data-all-68482f115ac04033078508.csv` fournis dans le module.
* le dataset resultant du traitement de fond sur les données se nomme `00-reconstructed-dataset.csv`. Dans celui-ci se trouve quasiment toutes les colonnes originales. Les données qui sont clairement identifiées comme inutiles dans la suite du traitement sont retiré le plus tôt possible.
* Le dataset final destiné a être utilisé pour le training d'un model se nomme `01-final-dataset.csv`, celui-ci ne comprend que des valeurs numériques.

## Remarques

* Le `requirements.txt` reste le fichier le plus simple possible pour éviter des dépendance trop lié a la version de python utilisé, on compte sur la résolution des dépendance pour tout installer correctement