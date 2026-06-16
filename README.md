# 📑 Projet de Business Intelligence & Data Analytics

## 👥 Auteurs
* **MOHAMED SINE SANGARE** (MI23016)
* **MOUSTAPHA KABA** (MI23027)
* **MARIAMA DJOULDE BALDE**

---

## 🎯 Présentation du Projet
Ce projet consiste en la conception et le développement d'une solution d'analyse de données interactive réalisée sous **Power BI**. L'objectif principal est de transformer des données brutes en indicateurs clés de performance (KPI) actionnables, afin d'accompagner la prise de décision stratégique.

L'application intègre un cycle complet de Business Intelligence :
1. **Extraction et Chargement** des données (ETL).
2. **Modélisation et Nettoyage** (Power Query & Data Model).
3. **Calcul d'indicateurs avancés** (Mesures et colonnes calculées en DAX).
4. **Restitution Visuelle** (Création de dashboards dynamiques, filtres croisés et graphiques interactifs).

---

## 🛠️ Technologies Utilisées
* **Outil Principal :** Power BI Desktop
* **Langage de Requêtage :** M (Power Query) pour la transformation des données.
* **Langage d'Analyse :** DAX (Data Analysis Expressions) pour la création de mesures d'analyse temporelle et d'agrégations complexes.
* **Thème Visuel :** Personnalisé avec une charte graphique épurée (fichiers de configuration de thèmes intégrés `CY26SU04.json`).

---

## 📐 Architecture du Projet & Modèle de Données
Le projet repose sur un fichier source consolidé nommé `final_project.pbix`. 

Le modèle a été optimisé pour garantir une excellente fluidité de navigation :
* **Schéma en Étoile (Star Schema) :** Séparation claire entre les tables de faits (contenant les métriques et transactions) et les tables de dimensions (contenant les axes d'analyse : Temps, Géographie, Produits/Catégories, Clients, etc.).
* **Gestion des Relations :** Mise en place de relations saines (1 à plusieurs) avec une direction de filtrage optimisée pour éviter les ambiguïtés dans les rapports.
* **Sécurité :** Configuration native de liaisons de sécurité applicative (`SecurityBindings`).

---

## 📊 Fonctionnalités du Dashboard
Le rapport final comprend plusieurs pages et modules visuels conçus pour différents profils d'utilisateurs (analystes, managers, directeurs) :
* **Vue d'Ensemble (Executive Summary) :** Affichage des KPI globaux sous forme de cartes de données claires et synthétiques.
* **Analyses Temporelles :** Évolution des indicateurs clés mois par mois, comparaison d'une année sur l'autre (YoY).
* **Filtres Croisés & Segmentations :** Possibilité d'affiner l'analyse par segments de marché, catégories ou zones géographiques en un seul clic.
* **Visualisations Avancées :** Utilisation de graphiques combinés, de matrices dynamiques et de visuels personnalisés nettoyés pour une lecture intuitive.

---

## 🚀 Installation et Utilisation

### Prérequis
* Disposer de **Power BI Desktop** (version récente recommandée).

### Instructions
1. Cloner ou télécharger ce dépôt contenant le fichier du projet.
2. Ouvrir le fichier `final_project.pbix` à l'aide de Power BI Desktop.
3. Si les sources de données initiales sont locales, modifier les paramètres de la source de données dans Power Query (`Accueil > Modifier les requêtes > Paramètres de la source de données`) pour pointer vers vos chemins d'accès actuels.
4. Cliquer sur **Actualiser** pour mettre à jour les visuels.

---

## 📄 Licence
Ce projet a été réalisé dans un cadre académique / professionnel. Tous droits réservés aux auteurs.
