# dl-timeseries-airline-passengers

Ce projet est une étude comparative des réseaux de neurones récurrents (RNN), LSTM (Long Short-Term Memory) et GRU (Gated Recurrent Unit) appliquée à la prédiction de séries temporelles en utilisant le dataset classique **Airline Passengers**.

## 🚀 Objectifs 
- Implémenter et comparer des architectures RNN simples, LSTM et GRU.
- Analyser l'impact de la fenêtre de contexte (`lookback`) sur la précision.
- Étudier l'effet de l'empilement de couches récurrentes (Deep RNNs).

## ## 🛠️ Technologies utilisées
- Python 3.x
- TensorFlow / Keras
- Pandas & Numpy
- Scikit-learn (MinMaxScaler, Mean Squared Error)
- Matplotlib

##Visualisation du jeu de données original 

<img width="1123" height="607" alt="msedge_FOmJxBUlZg" src="https://github.com/user-attachments/assets/fc84434d-0980-4e06-bf12-c28fe9172d8c" />

##Prédictions du modèle Simple RNN (Configuration de base)

<img width="1129" height="520" alt="msedge_FhFsddbAfV" src="https://github.com/user-attachments/assets/8b0fcd31-0e76-42b7-9551-1f4424da9a29" />

##Comparaison des performances : RNN vs LSTM vs GRU (Lookback=1)

<img width="1134" height="588" alt="msedge_K3wqVGM9m8" src="https://github.com/user-attachments/assets/3fca34f6-90d4-4952-afeb-f929830efcd4" />

<img width="1131" height="349" alt="msedge_LijiYcjXFI" src="https://github.com/user-attachments/assets/bd562789-032b-49fa-bd4d-d1d8305087d0" />



