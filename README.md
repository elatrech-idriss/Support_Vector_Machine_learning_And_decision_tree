# Support Vector Machine Learning and Decision Tree  

##  Objectif du projet  
Ce projet a pour but d’explorer et de comparer les performances de deux algorithmes d’apprentissage supervisé très utilisés en machine learning :  
- **Les Machines à Vecteurs de Support (SVM)**  
- **Les Arbres de Décision (Decision Trees)**  

L’objectif est de comprendre comment ces modèles prennent leurs décisions, comment ils réagissent selon les hyperparamètres choisis et comment évaluer leur capacité à généraliser sur de nouvelles données.  

---

##  Contenu du projet  
Le projet se déroule dans un **notebook Jupyter (`.ipynb`)** et comprend les étapes suivantes :  

### 1. Chargement et préparation des données  
- Génération ou importation d’un jeu de données.  
- Séparation entre données d’entraînement et de test.  
- Normalisation éventuelle pour les modèles sensibles à l’échelle des données (comme le SVM).  

### 2. Implémentation du modèle **SVM**  
- Entraînement d’un classifieur SVM avec différentes valeurs de **C** (paramètre de régularisation).  
- Test de différents **kernels** (linéaire, polynomial, RBF).  
- Visualisation des frontières de décision pour mieux comprendre le comportement du modèle.  
- Évaluation des performances avec des métriques comme **accuracy**, **precision**, **recall** et **f1-score**.  

### 3. Implémentation du modèle **Decision Tree**  
- Entraînement d’un arbre de décision sur le même jeu de données.  
- Étude de l’impact du paramètre **max_depth** sur l’overfitting et l’underfitting.  
- Visualisation de la structure de l’arbre et des zones de décision.  
- Comparaison des résultats avec ceux obtenus par le SVM.  

### 4. Analyse comparative  
- Discussion des avantages et limites de chaque modèle :  
  - **SVM** : précis mais sensible au choix du kernel et au bruit.  
  - **Decision Tree** : interprétable mais peut facilement sur-apprendre.  
- Observation des performances en fonction de la complexité du modèle.  

---

## 📊 Résultats attendus  
- Une compréhension claire de la différence entre un modèle à marge maximale (SVM) et un modèle basé sur la segmentation de l’espace (Decision Tree).  
- La capacité d’ajuster les hyperparamètres pour obtenir le meilleur compromis entre **biais et variance**.  
- Une comparaison visuelle et chiffrée entre les deux méthodes.  

---

## 🧩 Technologies utilisées  
- **Python**  
- **Scikit-learn** pour les modèles de machine learning  
- **Matplotlib / Seaborn** pour la visualisation  
- **NumPy / Pandas** pour la manipulation des données  
- **Jupyter Notebook** pour l’expérimentation et l’analyse interactive  

---

## 🧑‍💻 Auteur  
Projet réalisé par **Idriss Elatrech**
