# GIVE ME SOME CREDIT

Dans le cadre de la formation Data / IA à l'Ecole IA Microsoft (Powered by Simplon), il a été demandé de travailler sur un projet d'analyse prédictive.
D'abord effectué directement sur la plateforme en ligne [BigML](https://bigml.com/), l'ensemble de processus d'apprentissage automatique supervisé a du être réalisé sur Python grâce à Jupyter Notebook.

**But :** pouvoir établir une prédiction et transmettre le résultat sur [Kaggle](https://www.kaggle.com/), une plateforme web organisant des compétitions en science des données.

Pour retrouver la compétition en question, vous retrouverez tous les renseignements et datasets ainsi que le classement directement sur cette page : [GiveMeSomeCredit](https://www.kaggle.com/c/GiveMeSomeCredit/overview).

## Pré-requis

Le script en question ne sera fonctionnel qu'après un certain nombre d'outils :
* [Docker](https://www.docker.com/) ;
* [Jupyter Notebooks](https://github.com/ageron/handson-ml2) : Vous trouverez dans ce repo GitHub tout ce qui est nécessaire pour la mise en place ;
* Un compte sur Kaggle ;
* Un compte sur GitHub si vous souhaitez push votre projet en ligne et de façon publique ;
* Importation de modules :
  * BigML : API pour établir tout le processus décisionnel ;
  * Kaggle : API pour transmettre le résultat de notre algorithme et participer à la compétition ;
  * Pandas : bibliotèque Python permettant la manipulation et l'analyse des données ;
  * Matplotlib : pour créer une visualisation graphique des données.
* Vous pouvez pull le projet et dans le dossier "docker", créez un fichier "auth.env" que vous organiserez ainsi :
~~~html
BIGML_USERNAME=**votre_username**
BIGML_API_KEY=**votre_clé_api**
KAGGLE_USERNAME=**votre_username**
KAGGLE_KEY=**votre_clé_api**
~~~

## Composition du projet

* Une Exploratory Data Analysis (EDA) avec Python ;
* Une prédiction avec BigML ;
* Une prédiction avec SkLearn.

## Auteur

* **Nicolas SEVERINO** - [Autres projets](https://github.com/nicolasseverino/)
