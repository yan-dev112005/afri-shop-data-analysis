# 🛒 AFRI-SHOP — Analyse des données e-commerce

## 📌 Présentation du projet

**AFRI-SHOP** est un projet d'analyse de données portant sur une activité e-commerce en Afrique de l'Ouest.

L'objectif de ce projet est d'exploiter des données commerciales afin d'évaluer les performances de l'entreprise, d'identifier les principaux moteurs du chiffre d'affaires et du bénéfice, et de formuler des recommandations basées sur les données.

Ce projet a été réalisé dans le cadre de la constitution d'un **portfolio Data Analyst**.

---

## 🎯 Objectifs

L'analyse vise à :

* Analyser le chiffre d'affaires et le bénéfice
* Identifier les périodes les plus performantes
* Étudier les méthodes de paiement
* Analyser les statuts des commandes
* Comparer les performances par pays
* Évaluer les différents canaux de vente
* Identifier les catégories et produits performants
* Construire un dashboard avec les principaux KPIs
* Transformer les résultats en recommandations business

---

## 🗂️ Données utilisées

Le projet repose sur cinq fichiers CSV :

| Fichier           | Description                                      |
| ----------------- | ------------------------------------------------ |
| `customers.csv`   | Informations relatives aux clients               |
| `products.csv`    | Informations relatives aux produits              |
| `orders.csv`      | Informations relatives aux commandes             |
| `order_items.csv` | Détails des articles présents dans les commandes |
| `payments.csv`    | Informations relatives aux paiements             |

### 📊 Volume des données

* **4 220 clients**
* **30 produits**
* **12 500 commandes**
* **20 576 lignes d'articles de commande**
* **12 500 paiements**

---

## 🛠️ Technologies utilisées

* 🐍 **Python**
* 🐼 **Pandas** — manipulation, nettoyage et analyse des données
* 📊 **Matplotlib** — visualisation des données
* 📓 **Jupyter Notebook** — environnement d'analyse

---

## 🔄 Méthodologie

Le projet suit plusieurs étapes :

### 1. Exploration des données

* Importation des différents fichiers CSV
* Inspection de la structure des données
* Identification des colonnes et types de données
* Vérification des valeurs manquantes et doublons

### 2. Nettoyage et préparation

* Traitement des données manquantes
* Vérification des doublons
* Contrôle de la cohérence des données
* Préparation des variables nécessaires à l'analyse
* Fusion des différentes tables

### 3. Analyse exploratoire

Plusieurs dimensions de l'activité ont été étudiées :

* Performance mensuelle
* Méthodes de paiement
* Statuts des commandes
* Performance par pays
* Canaux de vente
* Catégories et produits
* Chiffre d'affaires
* Bénéfice
* Marge

### 4. Visualisation

Des graphiques ont été créés afin de faciliter l'interprétation des résultats.

### 5. Dashboard

Un dashboard final a été construit afin de présenter les principaux KPIs et insights de manière synthétique.

---

# 📈 Principaux résultats

## 💰 Performance commerciale

Le chiffre d'affaires total analysé est d'environ **4,64 millions de dollars**, pour un bénéfice total d'environ **1,25 million de dollars**.

La marge globale se situe autour de **27 %**.

---

## 📅 Performance mensuelle

Le meilleur mois identifié est **mai 2025**.

### Résultats de mai 2025

* 💰 Chiffre d'affaires : **296 884 $**
* 📈 Bénéfice : **78 821 $**
* 🛒 Commandes : **740**

Cette période constitue le principal pic de performance identifié dans l'analyse.

---

## 💳 Méthodes de paiement

**Mobile Money** est le principal moyen de paiement utilisé.

Il représente environ **44,90 % du chiffre d'affaires**.

La carte bancaire arrive en deuxième position avec environ **30,32 %** du chiffre d'affaires.

Les marges sont relativement proches entre les différentes méthodes de paiement, ce qui indique que leur principal impact concerne davantage le **volume des transactions** que la rentabilité.

---

## 📦 Statuts des commandes

Les commandes **Completed** représentent environ **80,74 % du chiffre d'affaires**.

Les commandes **Pending, Cancelled et Returned** représentent ensemble environ **19,08 % des commandes**.

Ces statuts constituent donc un axe important à surveiller afin d'améliorer la performance commerciale.

---

## 🌍 Performance par pays

La **Côte d'Ivoire** est le marché générant le plus de chiffre d'affaires.

Elle est suivie notamment par :

* 🇳🇬 Nigeria
* 🇧🇯 Bénin
* 🇸🇳 Sénégal
* 🇹🇬 Togo
* 🇬🇭 Ghana

Les marges restent relativement proches entre les différents pays, ce qui montre que les différences de chiffre d'affaires sont principalement liées au **volume d'activité**.

---

## 🛍️ Canaux de vente

Le **site web** constitue le principal canal de vente.

Il représente environ **46,94 % du chiffre d'affaires**.

Les autres canaux analysés sont :

* WhatsApp
* Boutique
* Marketplace

Le site web constitue donc un canal stratégique pour AFRI-SHOP.

---

# 📊 Dashboard

Le dashboard final présente les principaux indicateurs de performance :

### KPIs

* 💰 Chiffre d'affaires total
* 📈 Bénéfice total
* 🛒 Nombre de commandes
* 📊 Marge globale

### Visualisations

* 📅 Évolution mensuelle du chiffre d'affaires
* 🏷️ Chiffre d'affaires par catégorie
* 🛍️ Répartition du chiffre d'affaires par canal de vente
* 🌍 Chiffre d'affaires par pays

---

# 🔎 Principaux insights

L'analyse permet de retenir plusieurs enseignements :

1. **Mai 2025** est la période la plus performante.
2. **Mobile Money** est le principal moyen de paiement.
3. Le **site web** est le principal canal de vente.
4. La **Côte d'Ivoire** est le marché le plus performant en chiffre d'affaires.
5. La marge globale est relativement stable autour de **27 %**.
6. Les commandes non finalisées représentent un axe d'amélioration potentiel.

---

# 💡 Recommandations business

À partir des résultats obtenus, plusieurs recommandations peuvent être formulées :

### 1. Optimiser le site web

Le site web étant le principal canal de vente, son optimisation peut contribuer à maintenir et augmenter les performances commerciales.

### 2. Développer Mobile Money

Compte tenu de son poids dans le chiffre d'affaires, il est pertinent de maintenir une expérience de paiement Mobile Money simple et fiable.

### 3. Réduire les commandes annulées et retournées

Une analyse plus approfondie des causes d'annulation et de retour pourrait permettre d'améliorer le taux de finalisation des commandes.

### 4. Renforcer les marchés performants

La Côte d'Ivoire, le Nigeria et le Bénin présentent des niveaux de chiffre d'affaires importants. Ces marchés peuvent faire l'objet d'une attention particulière dans les futures stratégies commerciales.

### 5. Étudier le pic de mai 2025

Identifier les facteurs ayant contribué à la performance exceptionnelle de mai 2025 pourrait permettre de reproduire certaines stratégies efficaces.

---

# 📁 Structure du projet

```text
AFRI-SHOP-Data-Analysis/
│
├── data/
│   ├── customers.csv
│   ├── order_items.csv
│   ├── orders.csv
│   ├── payments.csv
│   └── products.csv
│
├── notebook/
│   └── AFRI_SHOP_Data_Analysis.ipynb
│
├── dashboard/
│   └── dashboard.png
│
├── README.md
└── requirements.txt
```

---

# 🚀 Comment utiliser le projet

### 1. Cloner le repository

```bash
git clone [URL_DU_REPOSITORY]
```

### 2. Installer les dépendances

```bash
pip install pandas matplotlib jupyter
```

### 3. Lancer Jupyter Notebook

```bash
jupyter notebook
```

### 4. Ouvrir le notebook

Ouvrir :

```text
notebook/AFRI_SHOP_Data_Analysis.ipynb
```

---

# 📚 Compétences démontrées

Ce projet permet de démontrer des compétences en :

* Analyse exploratoire des données (EDA)
* Nettoyage et préparation des données
* Manipulation de données avec Pandas
* Agrégation et transformation de données
* Analyse des performances commerciales
* Analyse temporelle
* Analyse géographique
* Analyse des canaux de vente
* Visualisation de données
* Création de KPIs
* Interprétation business
* Formulation de recommandations basées sur les données

---

# 👨‍💻 Auteur

**Yanis**

Étudiant en **Systèmes Informatiques et Logiciels (SIL)**

Orientation professionnelle : **Data Analysis & Programmation**

---

⭐ **Projet réalisé dans le cadre de mon portfolio Data Analyst.**
