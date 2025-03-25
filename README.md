 # 💉 Analyse des Données de Vaccination COVID-19 et Pilotage de Dashboard

## 📝 Description
Ce projet vise à analyser les données de vaccination contre la COVID-19 et à concevoir un tableau de bord interactif permettant de suivre les tendances mondiales. Il comprend l'extraction, le nettoyage et la transformation des données, ainsi que la création de visualisations optimisées pour faciliter l'interprétation et la prise de décision.

## 🚀 Fonctionnalités
- **Extraction des données** issues de l'OMS pour identifier les KPIs pertinents.
- **Data Cleaning** pour traiter les données incomplètes et garantir la qualité des informations.
- **Transformation des données** avec Power Query Editor.
- **Création de visualisations interactives** dans Power BI :
  - Histogrammes
  - Nuages de points
  - Graphiques en anneau
  - Graphiques empilés
- **Optimisation des visualisations** pour une meilleure compréhension des tendances mondiales.

## 🛠️ Stack Technique
- **Power BI** pour la création du tableau de bord.
- **Power Query** pour la transformation des données.
- **DAX (Data Analysis Expressions)** pour les mesures avancées.
- **Microsoft Excel** pour la manipulation et la structuration des données.
- **Git/GitHub** pour le versionnement et la collaboration.

## 📥 Installation et Utilisation
### 📌 Prérequis
- Microsoft Power BI Desktop installé.
- Accès aux données de vaccination (fichier CSV, API OMS, etc.).
- Connaissance de base en Power Query et DAX.

### 📂 Clonage du Projet
```sh
git clone https://github.com/JennyTchiegue/Analyse_covid.git
cd  Analyse_covid
```

### 📊 Importation des Données
1. Ouvrir **Power BI Desktop**.
2. Aller dans **Accueil > Obtenir des données > Fichier Excel**.
3. Sélectionner le fichier de données et l'importer.
4. Nettoyer et transformer les données avec **Power Query**.

### 📈 Création du Dashboard
1. Ajouter des **visualisations interactives**.
2. Créer des mesures personnalisées avec **DAX**.
3. Organiser les éléments pour une meilleure lisibilité.

## 🎯 KPIs Analytiques
- Nombre total de doses administrées.
- Nombre de personnes entièrement vaccinées.
- Comparaison des taux de vaccination par pays/région.
- Tendances temporelles de la vaccination.

## 📌 Structure du Projet
```
├── data/              # Fichiers de données bruts
├── reports/           # Captures d'écran et exports du dashboard
├── src/              
│   ├── data_cleaning.pq  # Script Power Query
│   ├── measures.dax      # Calculs DAX
├── README.md          # Documentation principale
├── dashboard.pbix     # Fichier Power BI contenant le tableau de bord
```

## ✅ Tests et Validation
- Vérification de la qualité des données après nettoyage.
- Validation des KPIs avec des sources officielles.
- Test des interactions sur Power BI pour assurer la clarté des analyses.

## 🤝 Contribution
1. Forker le projet
2. Créer une branche (`git checkout -b feature-nouvelle-visualisation`)
3. Committer (`git commit -m "Ajout d'un graphique comparatif"`)
4. Pousser (`git push origin feature-nouvelle-visualisation`)
5. Ouvrir une Pull Request

 
## 📩 Contact
Si tu as des questions, n'hésite pas à me contacter sur [LinkedIn](https://linkedin.com/in/jenny-tchiegue-907803257) ou à ouvrir une issue sur GitHub ! 🚀
