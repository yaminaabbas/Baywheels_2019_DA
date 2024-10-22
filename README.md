# Analyse des Données Bay Wheels 2019

## Vue d'Ensemble

Ce projet analyse les données de partage de vélos Bay Wheels de 2019. L'objectif de l'analyse est de dériver des insights sur le comportement des utilisateurs et les tendances des trajets en utilisant PostgreSQL pour le nettoyage des données et JExcel pour la visualisation.

## Objectifs

Les principaux objectifs de cette analyse sont :
- Comprendre les habitudes d'utilisation des services de partage de vélos.
- Évaluer la répartition des trajets entre les différents types d'utilisateurs.
- Identifier les périodes de forte utilisation et les stations populaires.
  

## Nettoyage et Préparation des Données

Les données ont été traitées et préparées à l'aide de requêtes SQL pour réaliser les tâches suivantes :

- **Suppression des Colonnes Indésirables** : Les colonnes "rental_access_method" et "bike_share_for_all_trip" ont été supprimées.
  
- **Vérification des Doublons** : Un comptage des trajets uniques a été effectué pour garantir l'intégrité des données.

- **Suppression des Valeurs Manquantes** : Des requêtes ont été exécutées pour filtrer les enregistrements avec des valeurs nulles.

- **Statistiques sur les Trajets** :
  - Nombre total de trajets : 2 407 259
  - Nombre total de vélos : 10 766
  - Heure de début du premier trajet : 2019-01-01 00:07:10.576
  - Heure de fin du dernier trajet : 2020-01-01 08:58:51.25

## Analyse

L'analyse a porté sur divers aspects des données :

1. **Trajets avec la Même Station de Départ et d'Arrivée** : Seulement 59 066 trajets avaient des stations de départ et d'arrivée identiques.

2. **Répartition par Type d'Utilisateur** :
   - Clients : 472 217 trajets (19,62 %)
   - Abonnés : 1 935 042 trajets (80,38 %)

3. **Pourcentages de Trajets par Mois** : Les pourcentages de trajets par mois ont été analysés pour identifier les tendances saisonnières.

4. **Répartition des Trajets par Jour** : Le nombre de trajets par jour de la semaine a été évalué pour trouver les périodes de forte utilisation.

5. **Stations Principales** : L'analyse a mis en évidence les dix stations principales en termes de nombre total de trajets.

## Visualisation

Les résultats de l'analyse ont été visualisés à l'aide de graphiques dans JExcel, incluant :

- Graphiques à barres montrant les répartitions par type d'utilisateur et les tendances mensuelles des trajets.
- Graphiques linéaires illustrant le nombre de trajets par jour.

## Conclusion

Les résultats de cette analyse fournissent des insights précieux sur les tendances d'utilisation de Bay Wheels en 2019, révélant des informations clés sur le comportement des utilisateurs, les itinéraires populaires et les périodes de forte affluence.
