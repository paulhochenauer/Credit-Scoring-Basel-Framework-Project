# Credit-Scoring-Basel-Framework-Project
Auteur : Paul HOCHENAUER

Description : Projet de modélisation du risque de crédit et de calibration de la Probabilité de Défaut (PD) selon les principes réglementaires de Bâle.

## Objectifs
Analyse de données : Traitement d'un dataset bancaire et étude des variables explicatives.

Modélisation : Calcul d'un score de risque et segmentation des clients en trois catégories (Low, Medium, High).

Calibration : Détermination de la PD calibrée par catégorie en intégrant des marges de conservatisme (MoC) pour refléter les cycles économiques.

## Contenu du dépôt
Projet_Basel.ipynb : Notebook complet incluant les visualisations et l'analyse statistique.

projet_basel.py : Script Python pour une exécution directe du pipeline de traitement.

## Installation
Prérequis : pandas, numpy, matplotlib, seaborn.

Le projet nécessite les fichiers de données suivants dans le répertoire /sample_data/ :

TD3 - 12Janv.csv

data_dictionary.csv

## Méthodologie de Calibration
La calibration s'appuie sur le taux de défaut observé (ODR) avec des ajustements spécifiques :

Catégorie Low : Prise en compte de la tendance haussière récente.

Catégorie Medium : Restriction temporelle des données pour garantir une prudence accrue.

Catégorie High : Stabilisation des taux pour les profils les plus risqués.
