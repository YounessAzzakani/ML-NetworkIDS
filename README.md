# Détection d’attaques réseau à l’aide du jeu de données NSL-KDD

## Description du projet
Ce projet a pour objectif le **développement d’un modèle de classification supervisée** capable de **détecter les attaques réseau** à partir du jeu de données **NSL-KDD**, largement utilisé dans la recherche en sécurité informatique.  

L’approche repose sur une **analyse comparative de plusieurs algorithmes de Machine Learning** afin d’évaluer leur efficacité dans la détection d’intrusions.

## Méthodologie
1. **Prétraitement du jeu de données** : nettoyage, encodage des variables catégorielles et normalisation.  
2. **Entraînement de plusieurs modèles** :
   - **Random Forest**  
   - **XGBoost**  
   - **SVM (Support Vector Machine)**  
3. **Évaluation des performances** à l’aide de :
   - La **précision (Accuracy)**
   - Le **rappel (Recall)**
   - Le **F1-score**
4. **Analyse approfondie** via les **matrices de confusion** et les **rapports de classification** afin d’identifier le modèle le plus performant.

## 📊 Jeu de données
Le projet utilise le **jeu de données [NSL-KDD](https://www.kaggle.com/datasets/hassan06/nslkdd)**, une version améliorée du célèbre KDD’99, conçu pour l’évaluation de systèmes de détection d’intrusions.  
Ce dataset contient des connexions réseau étiquetées comme normales ou malveillantes, couvrant plusieurs types d’attaques (DoS, Probe, R2L, U2R).

## 🧩 Technologies utilisées
- **Python**
- **Pandas**, **NumPy**
- **Scikit-learn**
- **XGBoost**
- **Matplotlib**, **Seaborn** pour la visualisation

## 📈 Résultats
Les modèles ont été comparés en fonction de leurs performances globales.  
Les métriques obtenues ont permis d’identifier les approches les plus efficaces pour la **détection des intrusions** dans des environnements réseau simulés.

## 📁 Contenu du dépôt
- `notebook_ids_Final.ipynb` → Notebook principal contenant le code complet, les analyses et les visualisations.
- `nsl-kdd/` → Répertoire contenant le jeu de données **NSL-KDD** utilisé pour l’entraînement et les tests.
- `README.md` → Ce fichier de présentation du projet.


