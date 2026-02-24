# 🎓 Analyse de la Performance des Étudiants (Student Performance)

Ce projet propose une analyse statistique complète des scores d'étudiants à partir d'un fichier CSV. L'objectif est de mettre en pratique les concepts de tendance centrale, de dispersion et de visualisation de données avec Python.

## 🛠️ Technologies Utilisées

* **Python 3**
* **Pandas** : Lecture et manipulation des données.
* **NumPy** : Calculs statistiques avancés.
* **Plotly** : Création d'histogrammes interactifs.

---

## 📂 Structure des Exercices

### EXERCICE 1 : Mesures de Tendance Centrale
* Importation de `numpy` et `pandas`.
* Chargement du fichier CSV.
* Calcul et affichage de :
    * **Moyenne** : La valeur moyenne des scores.
    * **Médiane** : La valeur séparant la moitié supérieure de la moitié inférieure.
    * **Mode** : La valeur la plus récurrente.
* **Analyse** : Déduction du type de distribution (Symétrique, Skewed/Asymétrique) selon la position relative de ces mesures.



### EXERCICE 2 : Dispersion des Données
* **Étendue** (Range) : Écart entre le score maximum et minimum.
* **Variance** : Mesure de la variabilité des scores.
* **Écart-type** : Mesure de la dispersion autour de la moyenne.

### EXERCICE 3 : Quartiles et Valeurs Aberrantes
* Calcul de l'**IQR** (Interquartile Range).
* **Détection des Outliers** : Identification des valeurs atypiques qui pourraient fausser l'analyse en utilisant la méthode des barrières de Tukey ($Q1 - 1.5 \times IQR$ et $Q3 + 1.5 \times IQR$).



[Image of boxplot showing outliers and interquartile range]


### EXERCICE 4 : Visualisation Interactive
* Utilisation de `plotly.express`.
* Génération d'un **histogramme** pour visualiser la distribution réelle des scores et confirmer les hypothèses de l'Exercice 1.

---

## 🚀 Installation et Utilisation

1. **Cloner le projet** :
   ```bash
   git clone [https://github.com/votre-nom-utilisateur/student-performance-analysis.git](https://github.com/votre-nom-utilisateur/student-performance-analysis.git)
