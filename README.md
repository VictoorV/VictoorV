# 👋 Bienvenue

Statisticien/Data scientist passionné avec une solide formation en mathématiques appliquées et IA/machine learning.

## 🛠️ Compétences en programmation

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/-PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![R](https://img.shields.io/badge/-R-276DC3?style=flat&logo=r&logoColor=white)
![SQL](https://img.shields.io/badge/-SQL-4479A1?style=flat&logo=postgresql&logoColor=white)
![Java](https://img.shields.io/badge/-Java-007396?style=flat&logo=oracle&logoColor=white)
![C++](https://img.shields.io/badge/-C++-00599C?style=flat&logo=c%2B%2B&logoColor=white)
![Git](https://img.shields.io/badge/-Git-F05032?style=flat&logo=git&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat&logo=docker&logoColor=white)

## 🚀 Projets
La plupart des projets d'IA sont réalisés en utilisant PyTorch et des low-level APIs.

### Vision par ordinateur

| Projet | Technologies | Description |
|--------|-------------|-------------|
| [Segmentation d'IRM du cerveau](https://github.com/VictoorV/mri_segmentation) | Python, PyTorch, U-Net, CV2 | - Segmentation sémantique pour localiser les tumeurs.<br>- 80%+ de score Dice/IoU sur les patients de test.|
| [Segmentation d'images de football](https://github.com/VictoorV/Football_segmentation) | Python, PyTorch, U-Net, CV2 | - Segmentation pour détecter les joueurs/arbitres.<br>- Création d'un réseau U-Net, 85% d'IoU.|
| [Classification chien chat avec bruit](https://github.com/VictoorV/Catdog) | Python, PyTorch, CV2, filtre de Wiener, ConvNeXtV2 | - Traitement d'images avec flou et bruit sel poivre.<br>- Transfer learning sur ConvNeXtv2, 92,7% d'accuracy.|
| [Détection de port du masque](https://github.com/VictoorV/Mask_detection) | Python, PyTorch, YOLOv8, Faster R-CNN | - Transfer learning sur YOLOv8 et Faster R-CNN.<br>- Comparaison des résultats des modèles.|
| [Détection de tumeurs du cerveau](https://github.com/VictoorV/Brain_tumor) | Python, PyTorch, ResNet50, ConvNeXt, Scikit-learn | - Visualisation et analyse de scans IRM.<br>- Classification multiple.|
| [Détection du cancer du sein](https://github.com/VictoorV/Breast_cancer) | Python, PyTorch, ResNet50, ConvNeXt, EfficientNet, Scikit-learn | - Visualisation et analyse d'images de mammographie.<br>- Transfer learning sur des CNN, 71% d'accuracy.|
| [Génération d'images de saules](https://github.com/VictoorV/Saules_GAN) | Python, PyTorch, Pandas, ML | - Création et gestion d’une BDD d’images de saules.<br>- Développement et utilisation d’un GAN pour générer des images de saules. |

### NLP
| Projet | Technologies | Description |
|--------|-------------|-------------|
| [Analyse de sentiments](https://github.com/VictoorV/movie_classif_lstm) | Python, PyTorch, Torchtext, LSTM | - Entrainement d'un modèle LSTM bidirectionnel à plusieurs couches.<br>- Traitement des données par batch, 87,3% d'accuracy sur IMDB. |

### Classification / régression sur des données tabulaires

| Projet | Technologies | Description |
|--------|-------------|-------------|
| [Risque financier pour l'approbation de prêt](https://github.com/VictoorV/Risques_financiers) | Python, Scikit-learn, Pandas, ML | - EDA (données financières), tests et fiting de lois statistiques.<br>- Scoring, régression pour la prédiction de score, classification pour l'attribution de label (métriques : score f1/precision). |
| [Prédiction des maladies cardiaques pour une meilleure prévention](https://github.com/VictoorV/Maladie_cardiaque) | Python, Scikit-learn, Pandas, ML | - EDA (données de diabète) et pre-processing.<br>- Optimisation de modèles de machine learning (MLP, RDF, XGB, SVC) pour avoir les meilleurs résultats (métriques : score f1/recall). |
| [Prédire si un individu est positif au COVID-19](https://github.com/VictoorV/Prediction_COVID19) | Python, Scikit-learn, Pandas, ML | - EDA (données tests sanguins), feature engineering.<br>- Création de pipelines et optimisation de modèles de machine learning (MLP, RDF, XGB, SVC). |
| [Détection de logiciels malveillants](https://github.com/VictoorV/Detection_malwares) | Python, Scikit-learn, Pandas, ML | - Nettoyage, visualisation, analyse et étude statistique des données.<br>- Évaluation des modèles avec des métriques de performance (AUC, précision). Identification des variables influentes. |

### Études statistiques 

| Projet | Technologies | Description |
|--------|-------------|-------------|
| [Estimation par bootstrap et déchiffrage d'un message codé](https://github.com/VictoorV/Bootstrap_MCMC) | R, Python | - Application de deux approches bootstrap (non paramétrique et paramétrique), calcul des IC/IP bootstrap.<br>- Comparaison des méthodes bootstrap selon la taille d’échantillon, basée sur la précision des IC et la représentation graphique des IP.<br>- Déchiffrage d'un message caché avec un algorithme MCMC. |
| [Étude de la criminalité aux États-Unis](https://github.com/VictoorV/Criminalite_US) | R | - Analyse de la criminalité en fonction de variables socio-économiques.<br>- Sélection et comparaison de modèles de régression multiple (R², AIC). Tests d’hypothèses sur les coefficients et sur la significativité des modèles. |
| [Analyse biostatistique des données d'expression génique avec tests multiples](https://github.com/VictoorV/Analyse_biostatistique) | R | - Recherche et théorie sur les tests multiples.<br>- Tests multiples avec corrections sur des données réelles d'expression génique. |

### Programmation orientée objet

| Projet | Technologies | Description |
|--------|-------------|-------------|
| [Application de réservation de salles](https://github.com/VictoorV/Reservation_salles_java) | Java, MySQL | - Gestion automatique afin d'éviter les conflits de réservation.<br>- Connexion Java - base de données SQL. |
| [Équation de la chaleur en 2D](https://github.com/VictoorV/Projet2_Cpp) | C++ | - Modélisation numérique par différences finies.<br>- Résolution du problème de diffusion thermique en 2D dans un four et optimisation des calculs. |
| [Résolution de systèmes linéaires en C++](https://github.com/VictoorV/Projet1_Cpp) | C++ | - Résolution de systèmes par factorisation LU.<br>- Méthode de la puissance / puissance inverse. |


### Programmation linéaire

| Projet | Technologies | Description |
|--------|-------------|-------------|
| [Planification industrielle et optimisation de la supply chain 2](https://github.com/VictoorV/Planification_industrielle_supply_chain2) | AMPL | - Modélisation mathématique d'un problème de gestion et résolution.<br>- Analyse post-optimisation. |
| [Planification industrielle et optimisation de la supply chain 1](https://github.com/VictoorV/Planification_industrielle_supply_chain1) | AMPL | - Modélisation mathématique d'un problème de gestion et résolution.<br>- Analyse post-optimisation. |

😄
