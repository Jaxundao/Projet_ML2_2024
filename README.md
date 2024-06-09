Lien vers l'API : https://projetml2024-apwpm9cuydqeiypugjxgys.streamlit.app/
Ce dossier est composé de 3 sous dossiers : data, notebooks et appli_prediction

- **data** :
Il contient les données mise à notre disposition pour le projet dont le dataset initial (train.csv) et le jeu de données obtenu après apurement (churn-apure.csv)

- **notebooks** :
Vous trouverez à l'intérieur de ce dossier 3 notebooks : churn_01_EDA, churn_02_model_AUC et churn_02_model_f2_weighted

EDA_cleaning : contient l'ensemble des codes utilisés 
pour l'analyse exploratoire.

churn_02_model_AUC : contient les différents modèles testés et leurs
 résultats en se basant sur le AUC comme principale métrique de performance.

churn_02_model_f2_weighted : contient les différents modèles testés et leurs 
résultats en se basant sur le f2_weighted comme principale métrique de performance.

les 2 modélisation étant effectuée dans le but de comparer ces 2 métriques et chosir le meilleur modèle qui prend en charge le déséquilibre des données.
- **appli_prediction** : 
Il contient le code python ayant servi à concevoir l'API (main.py) ainsi que le modèle utilisé (model.sav). 

Le fichier requirements.txt contient l'ensemble des dépendances de l'application permettant le déploiement de l'application.
