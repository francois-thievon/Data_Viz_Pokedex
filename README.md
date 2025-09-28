# 🌟 Data Viz Pokédex - Analyse et Visualisation Interactive

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.8+-blue.svg" alt="Python Version">
  <img src="https://img.shields.io/badge/Plotly-Interactive-orange.svg" alt="Plotly">
  <img src="https://img.shields.io/badge/Matplotlib-Visualization-green.svg" alt="Matplotlib">
  <img src="https://img.shields.io/badge/Pandas-Data%20Analysis-purple.svg" alt="Pandas">
</p>

## 📖 Description

**Data Viz Pokédex** est un projet d'analyse et de visualisation de données interactives explorant l'univers des Pokémon. Ce projet présente une étude statistique complète des 151 premiers Pokémon à travers des visualisations dynamiques et esthétiques.

Développé par **François Gonon** et **François Thievon** dans le cadre du cours de Data Visualization, ce projet combine analyse statistique approfondie et storytelling visuel pour révéler les secrets cachés du monde Pokémon.

## ✨ Fonctionnalités

### 📊 Analyses Statistiques
- **Distribution des types** : Répartition et fréquence des types de Pokémon
- **Analyse des statistiques** : HP, Attaque, Défense, Vitesse, etc.
- **Corrélations** : Relations entre les différentes caractéristiques
- **Comparaisons générationnelles** : Évolution des Pokémon à travers les générations

### 🎨 Visualisations Interactives
- **Graphiques Plotly interactifs** : Zoom, filtres, et exploration dynamique
- **Cartes de chaleur** : Corrélations entre statistiques
- **Graphiques en radar** : Profils complets des Pokémon
- **Animations** : Évolutions temporelles et comparaisons
- **Intégration d'images** : Visualisation avec les sprites officiels des Pokémon

### 🔍 Analyses Avancées
- **Clustering** : Regroupement de Pokémon par similarité
- **Analyse IMC** : Calcul et analyse de l'Indice de Masse Corporelle
- **Profils de combat** : Identification des forces et faiblesses
- **Comparaisons multi-dimensionnelles** : Analyse des performances

## 🚀 Installation et Utilisation

### Prérequis
```bash
Python 3.8+
Jupyter Notebook ou JupyterLab
```

### Installation des dépendances
```bash
pip install pandas numpy matplotlib plotly seaborn ipywidgets
```

### Lancement du projet
1. Clonez le repository
```bash
git clone https://github.com/francois-thievon/Data_Viz_Pokedex.git
cd Data_Viz_Pokedex
```

2. Lancez Jupyter Notebook
```bash
jupyter notebook
```

3. Ouvrez les notebooks :
   - `pokedex.ipynb` : Analyse complète et exploration des données
   - `presentation.ipynb` : Version présentation avec visualisations clés

## 📁 Structure du Projet

```
Data_Viz_Pokedex/
│
├── 📄 Pokedex.csv              # Dataset principal des Pokémon
├── 📓 pokedex.ipynb            # Notebook d'analyse complète
├── 📓 presentation.ipynb       # Notebook de présentation
├── 📖 README.md                # Ce fichier
│
└── 🖼️ images/                  # Collection d'images des Pokémon
    ├── 1.jpg                   # Bulbizarre
    ├── 2.jpg                   # Herbizarre
    ├── ...                     # Tous les sprites Pokémon
    └── 151.jpg                 # Mew
```

## 📊 Données Utilisées

Le dataset contient **1027 Pokémon** avec les caractéristiques suivantes :
- **Identifiant** : ID unique
- **Nom** : Nom du Pokémon
- **Types** : Type primaire et secondaire
- **Statistiques** : HP, Attaque, Défense, Attaque Spé, Défense Spé, Vitesse
- **Caractéristiques physiques** : Taille, Poids
- **Métadonnées** : Génération, Total des stats

### Variables calculées :
- **IMC** : Indice de Masse Corporelle (Poids/Taille²)
- **Chemins d'images** : Liens vers les sprites correspondants

## 🎯 Objectifs Pédagogiques

Ce projet vise à démontrer :
- **Maîtrise des outils de visualisation** (Matplotlib, Plotly, Seaborn)
- **Analyse exploratoire de données** (EDA)
- **Storytelling avec les données**
- **Création de visualisations interactives**
- **Présentation de résultats de manière esthétique**

## 🛠️ Technologies Utilisées

| Technologie | Usage |
|-------------|-------|
| **Python** | Langage principal |
| **Pandas** | Manipulation des données |
| **NumPy** | Calculs numériques |
| **Matplotlib** | Visualisations statiques |
| **Plotly** | Visualisations interactives |
| **Seaborn** | Visualisations statistiques |
| **IPyWidgets** | Interfaces interactives |
| **Jupyter** | Environnement de développement |

## 📈 Exemples de Visualisations

- **Graphiques en barres interactifs** : Distribution des types de Pokémon
- **Scatter plots animés** : Relations taille/poids avec évolutions
- **Graphiques radar** : Profils statistiques complets
- **Heatmaps** : Matrices de corrélation
- **Box plots** : Distributions par génération
- **Graphiques 3D** : Exploration multi-dimensionnelle

## 👥 Contributeurs

- **François Gonon** - Analyse de données et visualisations
- **François Thievon** - Développement et interface interactive

## 📚 Ressources

- [Documentation Plotly](https://plotly.com/python/)
- [Documentation Matplotlib](https://matplotlib.org/)
- [Pokémon Database](https://pokemondb.net/)
- [Pandas Documentation](https://pandas.pydata.org/)

## 🎮 Fun Facts

- 🔥 **Type le plus répandu** : Découvrez quel type domine le Pokédex
- ⚡ **Pokémon le plus rapide** : Identifiez les champions de vitesse
- 🛡️ **Meilleure défense** : Trouvez les Pokémon les plus résistants
- 📊 **Corrélations surprenantes** : Relations inattendues entre les stats

---

<p align="center">
  <strong>Attrapez-les tous... les insights ! 🎯</strong>
</p>

<p align="center">
  Fait avec ❤️ pour la Data Visualization
</p>