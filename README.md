# time_series_project
Projet de l’unité « Machine learning et séries temporelles » en E5 à l'ESIEE Paris (2022)

Réalisé par Clément BOUDOU et Baptiste BONTOUX

Le rapport correspond au fichier "Rapport_BOUDOU_BONTOUX.pdf"

---

- Dossier data/ : Pre-processed data

- Dossier uber-tlc-foil-response-master/ : Données brutes

- deep_learning.ipynb :  Prédiction ddu nombre de commande uber par heure à New York avec 3 modèles de deep learning différents (Dense, RNN, LTSM) à T+1 et T+n selon la base ou la location.

- ExponentialSmoothing.ipynb :  Prédiction du nombre de commande uber par heure à New York avec un lissage exponentiel et un modèle de Holt.

- Sarimax.ipynb :  Prédiction du nombre de commande uber par heure à New York avec un modèle statistique Sarimax.

- 10minutes_predict :  Prédiction du nombre de commande toutes les 10 minutes à New York avec un réseau de neuronne LTSM.

- merge_data.ipynb :  Fusion de certaines données et création de datasets.

- New-York.ipynb :  Data Visualization des commandes uber par heure à New York.

- clement_try.ipynb :  Essais, Exploration des data et Data Visualization.
