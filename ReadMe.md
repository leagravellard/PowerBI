# Power BI – Business Intelligence & Data Visualization

## 🎯 Objectif du projet
L’objectif est de concevoir une **solution décisionnelle complète**, depuis l’architecture data jusqu’à la création de **tableaux de bord interactifs**, permettant d’analyser l’activité bancaire, la rentabilité, le comportement client et les risques de défaut de paiement.

## 🏗️ Architecture décisionnelle
Le projet repose sur une architecture data inspirée des environnements professionnels :
- **Datalake** pour le stockage des données sources
- **Operational Data Store (Azure SQL Server)** pour les données opérationnelles
- **Data Warehouse (Azure SQL Server)** pour l’analyse décisionnelle
- **Power BI** pour le reporting et la visualisation

Le modèle cible est basé sur un **schéma en constellation (galaxy schema)** avec des tables de faits et de dimensions.

## 📊 Modélisation & Alimentation des données
- Intégration des données clients, agences, transactions, produits bancaires et dépenses
- Création de tables de faits et de dimensions
- Choix méthodologiques explicités (hypothèses métiers, périmètre des revenus et charges)

## 📈 Tableaux de bord & Analyses
### Suivi des transactions
- Analyse de l’évolution des transactions dans le temps
- Typologie des transactions (retraits, virements, paiements, dépôts)
- Répartition des volumes financiers

### Analyse financière & rentabilité
- Analyse des revenus et des charges
- Étude des marges par agence
- Identification des agences déficitaires et rentables

### Analyse prédictive des risques de défaut (bonus)
- Création d’indicateurs métiers avancés
- Construction d’un **score de risque de défaut (0–100)**
- Classification des clients selon leur niveau de risque
- Visualisation dynamique des profils à risque

### Segmentation client
- Segmentation dynamique des clients :
  - Premium
  - Réguliers
  - Inactifs
- Analyse du comportement financier par segment et par zone géographique

### Recommandations décisionnelles
- Croisement de la segmentation et du score de risque
- Identification des clients stratégiques
- Aide à la prise de décision pour la fidélisation et la gestion du risque

## 🛠️ Technologies utilisées
- Power BI
- DAX
- Modélisation décisionnelle
- Azure SQL Server
- Data Warehouse / Data Lake
- Visualisation de données


## 🚀 Compétences mobilisées
- Business Intelligence
- Modélisation décisionnelle
- DAX et mesures calculées
- Visualisation et storytelling data
- Analyse client
- Aide à la décision
