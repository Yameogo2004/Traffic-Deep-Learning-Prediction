#   PREDICTION DU TRAFFIC ROUTIER À L’AIDE DU DEEP LEARNING POUR L’OPTIMISATION DES RÉSEAUX IOT DE TRANSPORT INTELLIGENT
Traffic volume and speed prediction using ML &amp; Deep Learning (LSTM, GRU, CNN-LSTM, Transformer, Random Forest,etc)

Traffic Volume & Speed Prediction Project 🚦

Ce projet vise à prédire le volume de trafic et la vitesse des véhicules sur l’autoroute I-94 en utilisant différents modèles de Machine Learning, Time Series et Deep Learning. L’objectif est d’analyser, modéliser et visualiser les tendances du trafic à partir de données historiques pour optimiser les réseaux IoT de transport intelligent.

## 📌 Objectifs

Comprendre et appliquer des modèles de séries temporelles et de deep learning pour la prédiction du trafic

Comparer les performances des différents modèles

Visualiser la qualité des prédictions pour faciliter la prise de décision

## 📁 Données

Le dataset utilisé :
Metro_Interstate_Traffic_Volume_with_speed.csv

Colonnes principales :

date_time : horodatage

traffic_volume : volume de trafic

speed : vitesse moyenne des véhicules

weather, temp, precipitation, … : variables additionnelles influençant le trafic

## 🧠 Modèles testés
✔ Machine Learning

Persistence Model (baseline)

Linear Regression

KNN

Decision Tree

Random Forest

✔ Time Series Models

ARIMA

SARIMAX

✔ Deep Learning Models

Single-step prediction :

MLP, LSTM, GRU, CNN, Transformer, CNN-LSTM

Multi-step prediction (6 heures) :

Seq2Seq, GRU, CNN-GRU, CNN-LSTM

⚙️ Tech Stack

Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, TensorFlow, Keras, Plotly, Jupyter Notebook

## 📊 Évaluation des modèles

Metrics utilisées : RMSE (Root Mean Square Error), MAE (Mean Absolute Error)

Visualisation :

Comparaison graphique des prédictions vs valeurs réelles

Graphique comparatif des erreurs (MSE/RMSE) entre modèles

Meilleures performances observées :

ML model : Random Forest

Time Series model : SARIMAX

Deep Learning model : CNN-LSTM
