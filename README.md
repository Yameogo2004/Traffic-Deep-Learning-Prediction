##  PREDICTION DU TRAFFIC ROUTIER À L’AIDE DU DEEP LEARNING POUR L’OPTIMISATION DES RÉSEAUX IOT DE TRANSPORT INTELLIGENT
Traffic volume and speed prediction using ML &amp; Deep Learning (LSTM, GRU, CNN-LSTM, Transformer, Random Forest,etc)

# 🚦 Prédiction du trafic routier avec Deep Learning et Machine Learning

**Prévision du volume de trafic et de la vitesse des véhicules sur l’autoroute I-94 à l’aide de ML, Time Series et Deep Learning pour des réseaux IoT de transport intelligents.**

[![Python](https://img.shields.io/badge/Python-3.10-blue)](https://www.python.org/)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-2.15-orange)](https://www.tensorflow.org/)


---

## 📌 Présentation du projet

La congestion routière est un enjeu majeur dans les villes modernes.  
Ce projet vise à prédire **le volume de trafic** et **la vitesse des véhicules** à partir de données historiques, afin de permettre **une gestion intelligente du trafic** et **l’optimisation des réseaux IoT**.


**Dataset :** `Metro_Interstate_Traffic_Volume_with_speed.csv`  
- **Lignes :** 48 000  
- **Colonnes :** 10 (`date_time`, `traffic_volume`, `speed`, `weather`, `temp`, `precipitation`, …)  

**Objectifs :**  
- Appliquer des modèles de séries temporelles et de deep learning pour la prédiction du trafic  
- Comparer les performances des modèles ML, Time Series et Deep Learning  
- Visualiser la qualité des prédictions pour faciliter la prise de décision

---

## 🧠 Modèles utilisés

### ✔ Machine Learning
- Persistence Model (baseline)  
- Régression Linéaire  
- KNN  
- Decision Tree  
- Random Forest  

### ✔ Séries temporelles
- ARIMA  
- SARIMAX  

### ✔ Deep Learning

**Prédiction single-step :** MLP, LSTM, GRU, CNN, Transformer, CNN-LSTM  
**Prédiction multi-step (6 heures) :** Seq2Seq, GRU, CNN-GRU, CNN-LSTM  

---

## ⚙️ Technologies utilisées

Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, TensorFlow, Keras, Plotly, Jupyter Notebook  

---

## 📊 Évaluation des modèles

- **RMSE** (Root Mean Square Error)  
- **MAE** (Mean Absolute Error)  

**Meilleurs modèles observés :**  
- ML : Random Forest  
- Time Series : SARIMAX  
- Deep Learning : CNN-LSTM  

**Visualisations :**  
- Prédictions vs valeurs réelles  
- Graphiques comparatifs des erreurs (MAE/RMSE)  
