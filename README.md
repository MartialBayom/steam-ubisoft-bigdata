# Steam / Ubisoft - Stratégie de lancement Big Data

##  Objectif
Analyser les tendances du marché Steam pour guider la stratégie 
de lancement d'un nouveau jeu Ubisoft (genres, éditeurs, avis, plateformes).

##  Dataset
- Catalogue complet Steam chargé depuis AWS S3
- Variables : titre, éditeur, genre, prix, avis positifs/négatifs

##  Méthodologie
1. Chargement des données depuis AWS S3 via PySpark
2. Nettoyage et structuration sur Databricks
3. Analyse macro : top éditeurs, évolution des sorties par année
4. Analyse des genres et plateformes les plus rentables
5. Analyse des avis joueurs
6. Recommandations stratégiques business pour Ubisoft

##  Stack
![PySpark](https://img.shields.io/badge/PySpark-E25A1C?style=flat&logo=apache-spark&logoColor=white)
![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=flat&logo=databricks&logoColor=white)
![AWS](https://img.shields.io/badge/AWS_S3-232F3E?style=flat&logo=amazon-aws&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)

##  Structure
```
steam-ubisoft-bigdata/
│
├── Steam_Analysis_Ubisoft_Project_JDH.ipynb
└── README.md
```

##  Formation
Jedha AI School — Certification Data Science RNCP Niveau 6
