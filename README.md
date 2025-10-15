# 📘 Introduction à la Science des Données

## 🧮 Travail Pratique 02 – Outils pour le calcul scientifique II

### 👥 Informations de groupe

* **Kilian Stockinger**
* **Candas Kat**
* **Jeremy Bortone**

**Professeurs** : Carlos Peña et Stephan Robert
**Assistants** : Thibault Schowing, Arthur Babey, Cédric Campos Carvalho
**Contact** : [prenom.nom@heig-vd.ch](mailto:prenom.nom@heig-vd.ch) *(ou via Teams de préférence)*

---

## 📅 Modalités de rendu

* **Date limite :** 🕐 **02.11.2025 à 23h55**
* **Travail en groupe** de 2 ou 3 étudiants
* **Fichier à rendre :**

  ```
  TP2_ISD_SA2025_Nom1_Nom2(_Nom3).ipynb
  ```

  > ⚠️ Les fichiers mal nommés seront pénalisés.
* **Soumission :** sur **Cyberlearn** ou **Teams** (selon les consignes).

---

## 🧾 Déroulement et notation

* **Total : 70 points**

  * **64 points** pour les exercices
  * **6 points** pour la **présentation**, la **mise en page** et le **respect du format**
* Les questions sont mises en évidence par du **gras**, du **bleu** ou des blocs d’instructions.
* Les zones de réponse sont indiquées par *« Réponse : »* ou une cellule de code à compléter.
* Les remarques et points obtenus seront ajoutés directement dans le notebook lors de la correction.

---

## 🎯 Objectifs pédagogiques

* Manipuler des **DataFrames** avec la bibliothèque **Pandas**.
* Effectuer des **analyses descriptives** et de **vérification de données**.
* Créer des **visualisations** avec **Matplotlib**.
* Interpréter les résultats et comprendre les **distributions de données**.

---

## 🧠 Ressources utiles

### 🗂 Cheatsheets recommandées :

* [Pandas – Data Wrangling Cheat Sheet](https://pandas.pydata.org/Pandas_Cheat_Sheet.pdf)
* [Matplotlib Cheatsheets](https://matplotlib.org/cheatsheets/)

### 💬 Aide :

* Consultez votre **TP1** pour les rappels sur Python, Numpy, Pandas et Matplotlib.
* Contactez vos **assistants** via **Teams** en cas de question.

---

## 🧩 Structure du notebook

| Partie | Contenu                                   | Points |
| :----- | :---------------------------------------- | :----: |
| **1**  | Analyse des données socio-économiques     |    5   |
| **2**  | Histogrammes                              |   10   |
| **3**  | Manipulations et vérification des données |   12   |
| **4**  | Transformations et graphiques             |   43   |

---

## 📊 Données utilisées

Le TP utilise la base de données **Gapminder**, développée par la fondation du même nom.
Elle contient pour chaque pays :

* la **population**
* l’**espérance de vie** (*life expectancy*)
* le **PIB par habitant** (*GDP per capita*)
* le **continent** et **l’année** (1952–2007)

### Installation du module :

```bash
pip install gapminder
```

### Chargement du jeu de données :

```python
import pandas as pd
from gapminder import gapminder
df = gapminder
```

---

## 🧮 Contenu des parties

### Partie 1 – Analyse exploratoire

Découverte du jeu de données :

* `head()`, `describe()`, `info()`
* Compréhension des variables : **observations** vs **caractéristiques**

### Partie 2 – Histogrammes

* Visualisation de la distribution des variables
* Interprétation des histogrammes
* Analyse du paramètre `bins`

### Partie 3 – Manipulations

* Groupement (`groupby`) et vérification de valeurs manquantes
* Comptage des entrées par pays et par année
* Génération d’abréviations à l’aide d’un outil d’IA

### Partie 4 – Transformations et graphiques

* Calculs de moyennes par **année** et **continent**
* Utilisation de `unstack()` pour restructurer les données
* Création de **bar charts**, **scatter plots** et **line plots**
* Détection et interprétation d’**outliers** (valeurs extrêmes)

---

## 🧾 Rendu attendu

Le notebook final doit :

* Contenir des **réponses rédigées** en phrases complètes.
* Être **propre**, **clair** et **bien commenté**.
* Contenir **les graphiques** correctement titrés et annotés.
* Être **nommé selon la convention** donnée.

---

## ✅ Conseils

* Testez votre code régulièrement avec `print()` avant d’afficher les graphiques.
* Supprimez les impressions de débogage avant le rendu.
* Utilisez le **method chaining** (`df.method1().method2()...`) pour des transformations lisibles.
* Sauvegardez votre travail fréquemment.

---

## 🧑‍💻 Exemple de lancement

```bash
# Lancer Jupyter Notebook
jupyter notebook TP2_ISD_SA2025_Nom1_Nom2_Nom3.ipynb
```

---

## 📚 Références

* [Documentation officielle Pandas](https://pandas.pydata.org/docs/)
* [Documentation officielle Matplotlib](https://matplotlib.org/stable/users/index.html)
* [Fondation Gapminder](https://www.gapminder.org)
