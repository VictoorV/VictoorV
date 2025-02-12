# 👋 Bienvenue

Statisticien/Data scientist passionné avec une solide formation en mathématiques appliquées et IA/machine learning.

## 🛠️ Compétences en programmation

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/-PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![R](https://img.shields.io/badge/-R-276DC3?style=flat&logo=r&logoColor=white)
![SQL](https://img.shields.io/badge/-SQL-4479A1?style=flat&logo=postgresql&logoColor=white)
![Java](https://img.shields.io/badge/-Java-007396?style=flat&logo=oracle&logoColor=white)
![C++](https://img.shields.io/badge/-C++-00599C?style=flat&logo=c%2B%2B&logoColor=white)
![C#](https://img.shields.io/badge/-C%23-239120?style=flat&logo=c-sharp&logoColor=white)
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
| [Détection de tumeurs du cerveau](https://github.com/VictoorV/Brain_tumor) | Python, PyTorch, ResNet50, ConvNeXt, Scikit-learn, CNN | - Visualisation et analyse de scans IRM.<br>- Classification multiple.|
| [Détection du cancer du sein](https://github.com/VictoorV/Breast_cancer) | Python, PyTorch, ResNet50, ConvNeXt, EfficientNet, Scikit-learn, CNN | - Visualisation et analyse d'images de mammographie.<br>- Transfer learning sur des CNN, 71% d'accuracy.|
| [Génération d'images de saules](https://github.com/VictoorV/Saules_GAN) | Python, PyTorch, Pandas, ML | - Création et gestion d’une BDD d’images de saules.<br>- Développement et utilisation d’un GAN pour générer des images de saules. |

### NLP
| Projet | Technologies | Description |
|--------|-------------|-------------|
| [Analyse de sentiments](https://github.com/VictoorV/movie_classif_lstm) | Python, LSTM | - Traitement des données par batch.<br>- Entrainement d'un modèle LSTM bidirectionnel.<br>- Accuracy de 87,33% sur IMDB. |

### Classification / régression sur des données tabulaires

| Projet | Technologies | Description |
|--------|-------------|-------------|
| [Risque financier pour l'approbation de prêt](https://github.com/VictoorV/Risques_financiers) | Python, Scikit-learn, Pandas, ML | - EDA (données financières), tests et fiting de lois statistiques.<br>- Scoring, régression pour la prédiction de score (métriques : score f1/precision).<br>- Décision pour l'attribution ou non d'un prêt, classification pour l'attribution de label.<br>- Ajout du modèle de scoring au modèle de classification pour tester si les prédictions de score permettent d'améliorer la prise de décision. |
| [Prédiction des maladies cardiaques pour une meilleure prévention](https://github.com/VictoorV/Maladie_cardiaque) | Python, Scikit-learn, Pandas, ML | - EDA (données de diabète, angine ...) + pre-processing.<br>- Optimisation de modèles de machine learning (MLP, RDF, XGB, SVC ...) pour avoir les meilleurs résultats (métriques : score f1/recall). |
| [Prédire si un individu est positif au COVID-19](https://github.com/VictoorV/Prediction_COVID19) | Python, Scikit-learn, Pandas, ML | - Analyse de données (données tests sanguins, tests viraux ...), pre-processing des données, feature engineering.<br>- Oversampling avec SMOTENC + méthodologie.<br>- Création de pipelines pour éviter TOUT data leakage.<br>- Optimisation de modèles de machine learning (MLP, RDF, XGB, SVC ...) pour avoir les meilleurs résultats (métriques : score f1/recall).<br>- Ajustement du seuil de décision et conclusion. |
| [Détection de logiciels malveillants](https://github.com/VictoorV/Detection_malwares) | Python, Scikit-learn, Pandas, ML | - Nettoyage, visualisation, analyse de données. Étude statistique préliminaire.<br>- Sélection d’algorithmes de classification adaptés (régression logistique, KNN, arbres de décision, SVM, méta-algorithmes). Implémentation avec Scikit-learn.<br>- Évaluation des modèles avec des métriques de performance (AUC, précision, rappel, validation croisée). Identification des variables influentes. |

### Études statistiques 

| Projet | Technologies | Description |
|--------|-------------|-------------|
| [Estimation par bootstrap et déchiffrage d'un message codé](https://github.com/VictoorV/Bootstrap_MCMC) | R, Python | - Estimation des paramètres par maximum de vraisemblance et construction d’intervalles de confiance pour les paramètres du modèle.<br>- Application de deux approches bootstrap (non paramétrique et paramétrique), calcul des intervalles de confiance/prédiction (IC, IP) bootstrap.<br>- Comparaison des méthodes bootstrap selon la taille d’échantillon, basée sur la précision des IC et la représentation graphique des IP.<br>- Création d’outils pour encoder, décoder et analyser les fréquences de lettres.<br>- Déchiffrage avec un algorithme Monte-Carlo par chaînes de Markov. |
| [Étude de la criminalité aux États-Unis](https://github.com/VictoorV/Criminalite_US) | R | - Analyse de la criminalité en fonction de variables socio-économiques.<br>- Sélection et comparaison de modèles de régression multiple (R², AIC). Tests d’hypothèses sur les coefficients et sur la significativité des modèles. |
| [Analyse biostatistique des données d'expression génique avec tests multiples](https://github.com/VictoorV/Analyse_biostatistique) | R | - Recherche et théorie sur les tests multiples.<br>- Tests multiples avec corrections sur des données réelles d'expression génique. |

### Programmation orientée objet

| Projet | Technologies | Description |
|--------|-------------|-------------|
| [Application de réservation de salles](https://github.com/VictoorV/Reservation_salles_java) | Java, MySQL | - Gestion automatique afin d'éviter les conflits de réservation.<br>- Connexion Java - base de données SQL. |
| [Équation de la chaleur en 2D](https://github.com/VictoorV/Projet2_Cpp) | C++ | - Modélisation numérique par différences finies.<br>- Résolution du problème de diffusion thermique en 2D dans un four. |
| [Résolution de systèmes linéaires en C++](https://github.com/VictoorV/Projet1_Cpp) | C++ | - Résolution de systèmes par factorisation LU.<br>- Méthode de la puissance / puissance inverse. |


### Programmation linéaire

| Projet | Technologies | Description |
|--------|-------------|-------------|
| [Planification industrielle et optimisation de la supply chain 2](https://github.com/VictoorV/Planification_industrielle_supply_chain2) | AMPL | - Modélisation d'un problème réel en problème mathématique.<br>- Analyse post-optimisation. |
| [Planification industrielle et optimisation de la supply chain 1](https://github.com/VictoorV/Planification_industrielle_supply_chain1) | AMPL | - Modélisation d'un problème réel en problème mathématique.<br>- Analyse post-optimisation. |

## 📊 Expérience professionnelle

### Ingénieur R&D chez SEGULA Technologies (mars - septembre 2024)
- Veille technologique et état de l'art sur l'apprentissage par renforcement en gestion énergétique.
- Modélisation et résolution de problèmes MILP afin d'optimiser la consommation des bâtiments.
- Développement d'un système innovant de gestion de l'énergie en temps réel par IA.

## 🎓 Formation

### Master en mathématiques appliquées, Ingénierie Statistique et Numérique, à l'université de Lille (2022-2024)
- Statistiques et probabilités (tests d'hypothèses, modélisation statistique, régression, séries temporelles, statistiques computationnelles, statistiques spatiales, biostatistiques, analyse de données, analyse factorielle).
- Théorie et méthodes d'apprentissage (apprentissage supervisé, non supervisé, par renforcement, traitement naturel du langage, génération d'images).
- Calcul scientifique (optimisation, recherche opérationnelle, traitement du signal).
- Outils du big data (Git, Docker).

### Licence en mathématiques pures à l'université de Lille (2021 - 2022)
- Analyse réelle, complexe, numérique et matricielle.
- Structures algébriques
- Topologie
- Probabilités
- Équations différentielles

😄
