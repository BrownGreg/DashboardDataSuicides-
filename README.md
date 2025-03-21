# Projet d'analyse des taux de suicide et des dépenses de santé

## Introduction

Ce projet a pour objectif d'analyser la relation entre les taux de suicide et les dépenses de santé dans différents pays, à travers une visualisation interactive avec Streamlit. Nous avons utilisé un dataset provenant de Kaggle contenant des informations sur les décès par suicide, la population, et les dépenses de santé. 


##  Description du dataset

Les données proviennent du fichier `WHO_MHExp_and_Deaths.csv`. Ce fichier contient des informations sur les décès par suicide, la population, et les dépenses de santé de plusieurs pays sur plusieurs années.

**Principales colonnes:**

*   `Country_Name`: Nom du pays.
*   `Year`: Année de l'enregistrement des données.
*   `Population`: Population totale du pays.
*   `Deaths_Suicides`: Nombre total de décès par suicide.
*   `HExp_Pctage_Y`: Pourcentage du PIB consacré aux dépenses de santé.
*   `Suicide_Rate_100k`: Taux de suicide pour 100 000 habitants (calculé).


##  Etapes du projet

1.  **Extraction:** Nous avons téléchargé le fichier CSV depuis Kaggle et l'avons importé dans notre code Python avec Pandas.
2.  **Transformation:** Nous avons prétraité les données en supprimant les doublons et les valeurs nulles. Nous avons également calculé le taux de suicide par 100 000 habitants.
3.  **Analyse et visualisation:** Nous avons réalisé des analyses exploratoires pour identifier les tendances et les corrélations entre les taux de suicide et les dépenses de santé. Les analyses incluent :
    * l'évolution temporelle des taux de suicide,
    * le classement des pays selon leurs taux de suicide,
    * la comparaison des taux de suicide en fonction du niveau de dépenses de santé,
    * la simulation de facteurs causaux et d'efficacité des interventions.
4.  **Dashboard Streamlit:** Nous avons développé un dashboard interactif avec Streamlit pour visualiser les résultats de notre analyse. Il comprend une carte du monde, des graphiques d'évolution temporelle, des classements, et des diagrammes pour explorer les données et mieux comprendre la relation entre les variables.


## Conclusion

Ce projet a permis d'explorer la relation complexe entre les taux de suicide et les dépenses de santé. Le dashboard Streamlit offre une interface intuitive pour visualiser les tendances et comparer les données entre les pays. Les résultats obtenus peuvent contribuer à mieux comprendre les facteurs associés aux taux de suicide et à identifier les interventions potentielles pour prévenir ce phénomène.


##  Technologies utilisées

*   Python
*   Pandas
*   Matplotlib
*   Seaborn
*   Streamlit
*   Plotly
*   Ngrok


##  Contributeurs

* Lydie Havugimana
* Enzo Bandinu
* Grégory Hery
