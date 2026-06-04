
# Traitement de données médicales — SDD1002

Notebook Jupyter de traitement, d'analyse exploratoire et de modélisation sur un dataset de maladies cardiaques, couvrant le prétraitement, la visualisation, la sélection de caractéristiques et le clustering.

## Contenu du notebook

- Chargement des données depuis Google Drive
- Prétraitement : imputation des valeurs manquantes (moyenne / mode), encodage avec LabelEncoder, standardisation avec StandardScaler
- Comparaison des méthodes d'encodage : OneHotEncoding, LabelEncoder, get_dummies
- Analyse exploratoire (EDA) : histogrammes KDE, boîtes à moustaches, diagrammes à bandes par variable catégorielle
- Carte de chaleur (heatmap) de corrélation entre variables numériques
- Sélection de caractéristiques par RFE (Recursive Feature Elimination) avec régression logistique
- Clustering hiérarchique agglomératif (AgglomerativeClustering, 4 clusters) visualisé en 3D

## Technologies

- Python
- Pandas
- scikit-learn (LabelEncoder, StandardScaler, RFE, LogisticRegression, AgglomerativeClustering)
- Matplotlib / Seaborn
- Plotly
- Google Colab

## Prérequis

```bash
pip install pandas scikit-learn matplotlib seaborn plotly requests
```

Développé sous Google Colab. Le dataset `heart_disease_uci.csv` est chargé depuis Google Drive — le lien peut nécessiter une mise à jour selon l'environnement.

## Structure

```
Traitement_Donnees_Médicales.ipynb  — notebook principal (4 sections)
```

---

Projet universitaire solo — cours SDD1002, UQTR.
