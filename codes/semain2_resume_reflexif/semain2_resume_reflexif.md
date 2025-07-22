
# Résumé du Cours – 2ème Semaine

## 1. Définir la Problématique en Recherche

La **problématique** est la question centrale qu'une recherche cherche à résoudre. Elle s'élabore en identifiant :

- **Le domaine** : Le champ scientifique ou technique concerné (exemples : santé, finance, intelligence artificielle)
- **L’axe de recherche** : L’angle précis ou sous-thème ciblé de la recherche
- **L’état de l’art** : L’analyse des publications existantes pour comprendre les limites actuelles et dégager des pistes d’innovation

## 2. Choisir l’Approche

Une fois la problématique définie, il s'agit de détailler l'approche méthodologique, souvent axée sur l’IA ou l’analyse de données :

- **Mojo** : Excellente performance pour les calculs lourds
- **Julia** : Très rapide et orienté vers le calcul scientifique
- **Python** : Langage de prédilection en science des données grâce à la richesse de ses bibliothèques (*pandas*, *numpy*, *matplotlib*…)

## 3. Collecte de Données

Résoudre une problématique requiert la collecte de données, par différents moyens :

- **Bases de données (SGBD)**
  - **SQL** (MySQL, PostgreSQL) : pour des données structurées
  - **NoSQL** (MongoDB, Firebase) : pour des données semi-structurées ou non structurées
- **Documents** : Fichiers XML, JSON, CSV exportés de bases ou tableurs
- **Web**
  - **Sites classiques**
    - **Statique (2 tiers)** : pages HTML fixes (le client reçoit toujours un fichier .html)
    - **Dynamique (3 tiers)** : pages générées à la volée avec client, serveur web, serveur BDD
  - **Services Web (APIs)** : récupération de données via requêtes HTTP (REST, SOAP), tous types de fichiers possibles

> Pour les réseaux sociaux, l’utilisation de **SGBD NoSQL**, notamment les bases de graphes (Neo4j), est conseillée.

## 4. Traitement et Visualisation des Données

Après la collecte vient le **traitement** et la **visualisation** :

- **Traitement (processing) :**
  - *pandas* : manipulation et nettoyage de données tabulaires
  - *numpy* : calculs numériques rapides, statistiques et manipulation de matrices

- **Visualisation :**
  - *matplotlib* : création de graphiques
  - Parfois, utilisation de *seaborn* ou *plotly* pour des visualisations avancées

## 5. Workflow Général en Recherche IA / Data Science

Le processus global suit cette démarche :

1. **Définir la problématique** ([Domaine], [Axe], [État de l’art])
2. **Choisir une approche** (modèles, langages, outils)
3. **Collecter les données** (SGBD, documents, web)
4. **Prétraiter et analyser** (*pandas*, *numpy*)
5. **Visualiser les résultats** (*matplotlib*, *seaborn*, …)
6. **Évaluer les performances** (comparaison de différentes approches)