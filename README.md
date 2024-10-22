# Bay Wheels Data Analysis

## Description
Ce projet analyse les données de Bay Wheels pour l'année 2019. L'objectif principal est d'explorer les habitudes d'utilisation des vélos, d'identifier des tendances et d'en tirer des conclusions sur les différents types d'utilisateurs (clients occasionnels vs abonnés).

## Table des matières
- [Technologies utilisées](#technologies-utilisées)
- [Données](#données)
- [Préparation des données](#préparation-des-données)
- [Analyse des données](#analyse-des-données)
- [Conclusions](#conclusions)
- [Installation](#installation)
- [Contributeurs](#contributeurs)

## Technologies utilisées
- PostgreSQL
- Pandas (Python)
- Jupyter Notebook (pour l'analyse)

## Données
Les données utilisées proviennent de l'API de Bay Wheels et contiennent des informations sur les trajets, les stations de départ et d'arrivée, et le type d'utilisateur. Les fichiers principaux utilisés dans ce projet sont :
- `baywheels_2019.xlsx` : Données brutes des trajets.
- `baywheels2019_Postgresql.rtf` : Scripts SQL pour le traitement des données.

## Préparation des données
1. Suppression des colonnes indésirables.
2. Vérification des doublons.
3. Nettoyage des valeurs manquantes.
4. Comptage des trajets et des vélos.

## Analyse des données
1. Analyse du pourcentage de clients et d'abonnés.
2. Analyse des trajets par mois.
3. Distribution des trajets par jour de la semaine.

## Conclusions
Les résultats de l'analyse montrent des tendances intéressantes sur l'utilisation des vélos, notamment la répartition entre les clients occasionnels et les abonnés, ainsi que les périodes de forte utilisation.

## Installation
Pour exécuter ce projet, clonez le dépôt et installez les dépendances requises.

```bash
git clone <URL-du-dépôt>
cd <répertoire-du-projet>
pip install -r requirements.txt
