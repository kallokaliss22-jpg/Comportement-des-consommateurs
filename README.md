# Comportement-des-consommateurs
L'analyse de données du comportement des consommateurs utilisant Python, SQL and Power BI
Consumer Shopping Behavior Analysis Project
Project Overview

Ce projet vise à analyser le comportement d'achat des consommateurs afin d'identifier les tendances d'achat, comprendre les facteurs influençant les décisions des clients et fournir des recommandations stratégiques permettant d'améliorer les ventes, la satisfaction client et la fidélisation.

L'analyse a été réalisée à l'aide de Python pour la préparation des données, SQL Server pour l'analyse des données, Power BI pour la visualisation et Gamma pour la présentation finale des résultats.

Project Objectives

Les principaux objectifs du projet sont :

Identifier les tendances de consommation selon le sexe, l'âge et les catégories de produits.
Évaluer l'impact des remises, des avis clients et des modes de livraison sur les ventes.
Analyser le comportement des clients abonnés et non abonnés.
Mesurer la fidélité des clients à travers leurs achats répétés.
Fournir des recommandations basées sur les données pour améliorer les performances commerciales.
Technologies Used
Python

Utilisé pour :

L'importation des données.
Le nettoyage et la préparation des données.
La transformation et l'enrichissement des variables.
L'exportation des données nettoyées vers SQL Server.

Bibliothèques utilisées :

Pandas
NumPy
SQLAlchemy
PyODBC
SQL Server

Utilisé pour :

Le stockage des données nettoyées.
La création des tables analytiques.
L'exécution des requêtes métier.
L'extraction des indicateurs de performance.
Power BI

Utilisé pour :

La conception du tableau de bord interactif.
La visualisation des indicateurs clés.
L'analyse des performances commerciales.
Gamma

Utilisé pour :

La création de la présentation finale.
La communication des résultats aux parties prenantes.
La mise en valeur des recommandations stratégiques.
Project Workflow
1. Data Importation

Les données brutes ont été importées dans Python à partir du fichier source.

Principales opérations :

Chargement du fichier CSV.
Vérification de la structure des données.
Analyse exploratoire initiale.
2. Data Cleaning

Les données ont été nettoyées afin d'améliorer leur qualité.

Actions réalisées :

Suppression des doublons.
Traitement des valeurs manquantes.
Correction des types de données.
Standardisation des formats.
3. Data Transformation

Création de nouvelles variables analytiques :

Groupe d'âge.
Segments de fidélité.
Statut de client récurrent.
Calculs de revenus et indicateurs métiers.
Python to SQL Server Integration

Une connexion a été établie entre Python et SQL Server à l'aide de SQLAlchemy et PyODBC.

Processus :

Connexion à SQL Server.
Création de la base de données analytique.
Exportation des données nettoyées.
Vérification de l'intégrité des données importées.
SQL Analysis

Les analyses réalisées incluent :

Revenu total par sexe.
Analyse des remises appliquées.
Produits les mieux notés.
Comparaison des modes de livraison.
Analyse des abonnements.
Produits bénéficiant le plus de remises.
Segmentation des clients.
Produits les plus achetés par catégorie.
Analyse des clients récurrents.
Contribution des groupes d'âge au revenu total.
Power BI Dashboard

Le tableau de bord permet de visualiser :

Customer Analysis
Répartition des clients par sexe.
Répartition des clients par âge.
Clients abonnés vs non abonnés.
Revenue Analysis
Revenu par sexe.
Revenu par groupe d'âge.
Revenu par catégorie de produit.
Purchase Analysis
Produits les plus vendus.
Impact des remises.
Analyse des modes de livraison.
Loyalty Analysis
Clients récurrents.
Segmentation de fidélité.
Taux d'abonnement.
Key Findings

Les résultats montrent que :

Les hommes génèrent une part importante du revenu total.
Les adultes représentent le groupe d'âge le plus rentable.
Les clients non abonnés génèrent un revenu total plus élevé.
Les clients fidèles contribuent significativement aux ventes.
Certains produits fortement notés génèrent également des revenus élevés.
Business Recommendations
Mettre en place un programme de fidélisation pour les clients récurrents.
Développer des campagnes marketing ciblées pour les produits les mieux notés.
Encourager l'abonnement grâce à des avantages exclusifs.
Exploiter davantage les segments de clientèle les plus rentables.
Utiliser l'analyse des données pour personnaliser les offres commerciales.
Presentation

Les résultats de l'analyse ont été présentés à l'aide de Gamma afin de fournir une présentation claire, interactive et professionnelle destinée aux décideurs.
