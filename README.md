# 💧 Water Potability Prediction – Flask App

Ce projet est une application web développée avec **Flask**, permettant de prédire si une eau est **potable ou non** à partir de ses caractéristiques chimiques.  
Le modèle de machine learning utilisé est un **Random Forest Classifier**, entraîné à partir d’un dataset Kaggle.

---

## 🎯 Objectif du projet

- Prédire la potabilité de l’eau à partir de ses paramètres physico-chimiques.
- Comparer plusieurs modèles de classification et choisir le plus performant.
- Intégrer le modèle retenu dans une **application web Flask** interactive.

---

## 📊 Dataset utilisé

- **Source** : [Kaggle - Water Potability Dataset](https://www.kaggle.com/datasets/adityakadiwal/water-potability)
- **Taille** : 3 276 lignes, 10 colonnes

**Variables utilisées :**
- `ph` – potentiel hydrogène  
- `Hardness` – dureté de l’eau  
- `Solids` – concentration de solides dissous  
- `Chloramines` – taux de chloramine  
- `Sulfate` – concentration en sulfate  
- `Conductivity` – conductivité électrique  
- `Organic_carbon` – carbone organique  
- `Trihalomethanes` – composés organiques chlorés  
- `Turbidity` – turbidité  
- `Potability` – cible (1 = potable, 0 = non potable)

✅ **Aucune valeur manquante** dans les données.

---

## 🧠 Modèles testés

Modèles évalués :
- Logistic Regression
- Decision Tree
- Random Forest ✅
- Extra Trees
- Support Vector Machine (SVM)
- K-Nearest Neighbors
- Gradient Boosting
- AdaBoost
- Gaussian Naive Bayes

📌 **Meilleur modèle sélectionné : `RandomForestClassifier()`**  
🎯 Performant, robuste aux outliers, et excellent sur ce type de données.  
🔐 Sauvegardé avec `joblib` pour intégration dans Flask.

---

## 🧰 Technologies utilisées

- **Python 3**
- **Flask**
- **Scikit-learn**
- **Pandas**, **NumPy**
- **HTML/CSS**

---

## 🌐 Fonctionnalités

- Saisie des caractéristiques de l’eau via une page web
- Affichage immédiat de la prédiction : "Eau potable" ou "Eau non potable"
- Application locale simple et fonctionnelle

---

## 🚀 Exécution locale

 je executé mon projet  localement  
