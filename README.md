# Analyse Exploratoire et Modélisation de Données

## 1. Contexte

Ce projet consiste à explorer et modéliser deux jeux de données distincts afin de réaliser un processus complet de data mining, inspiré de méthodologies telles que **CRISP-DM** ou le processus **KDD**.

### Jeux de données

1. **Titanic**

   - Informations démographiques et socio-économiques sur les passagers (classe, sexe, âge, tarif, etc.).
   - Objectif : prédire la survie (`0` ou `1`) des passagers.
   - Enjeux : nombreuses valeurs manquantes, variables catégorielles et numériques.

2. **Bank Marketing**
   - Données issues de campagnes de marketing téléphonique d’une banque portugaise.
   - Objectif : prédire si un client souscrit à un dépôt à terme (`yes` ou `no`).
   - Enjeux : dataset volumineux, variables catégorielles multiples, valeurs manquantes possibles.

---

## 2. Objectifs du projet

- Mettre en œuvre un processus structuré de découverte de connaissances.
- Développer des compétences en manipulation de données, visualisation et modélisation.
- Comparer les performances de différents modèles de classification selon le dataset et la méthode de validation.

---

## 3. Méthodologie

### 3.1 Prétraitement des données

- Identification et traitement des valeurs manquantes.
- Encodage des variables catégorielles (One-Hot, Label Encoding).
- Normalisation ou standardisation des variables numériques.
- Librairies : **Pandas**, **Scikit-learn**.

### 3.2 Analyse exploratoire (EDA)

- Statistiques descriptives : moyenne, médiane, quartiles, écart-type.
- Visualisations : histogrammes, boxplots, countplots, heatmaps de corrélation.
- Observation des corrélations et outliers.
- Librairies : **Pandas**, **Matplotlib**, **Seaborn**, **Plotly**.

### 3.3 Modélisation

- 7 algorithmes de classification :
  1. Régression Logistique
  2. Arbre de Décision
  3. Forêt Aléatoire
  4. K-Nearest Neighbors (KNN)
  5. Support Vector Machine (SVM)
  6. Naive Bayes
  7. Réseaux de Neurones
- Validation : split 70/30 et cross-validation (5, 7 et 10 folds).
- Évaluation : **Accuracy**, **Précision**, **Rappel**, **F1**, **AUC-ROC**.

### 3.4 Évaluation et discussion

- Comparaison des modèles et des méthodes de validation.
- Analyse du surapprentissage (overfitting).
- Comparaison entre les datasets en termes de faisabilité, prétraitement et robustesse des modèles.

---

## 4. Résultats attendus

- Dataset nettoyé et prétraité.
- Graphiques et matrices de corrélation.
- Tableau comparatif des performances des 7 modèles pour chaque dataset et chaque méthode de validation.
- Discussion des résultats et recommandations.

---

## 5. Conclusion

- Synthèse des résultats et des facteurs explicatifs majeurs.
- Limites et biais potentiels.
- Pistes d’amélioration : feature engineering, tuning d’hyperparamètres, réduction de dimensions.

---

## 6. Références

- [Dataset Titanic]
- [Dataset Bank Marketing](https://archive.ics.uci.edu/dataset/222/bank+marketing)

## Autheur

Djeutchou Thierry
