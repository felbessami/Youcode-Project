# Projet Sell4All – Exploration de données avec Python

## Présentation

L'objectif général de ce projet est d'utiliser Python pour explorer et nettoyer un
jeu de données clients fourni par l'entreprise Sell4All. Ce travail constitue une
première étape avant l'intégration d'une fonctionnalité d'intelligence artificielle
(système de recommandation) sur le site de l'entreprise. Il fallait donc comprendre
les données disponibles, vérifier leur qualité, puis produire un fichier propre et
exploitable pour la suite du projet.

## Étapes suivies

* Installation de Miniconda, Jupyter Notebook, Pandas et Matplotlib.
* Chargement et exploration du fichier CSV fourni.
* Analyse des données (statistiques descriptives et visualisation).
* Nettoyage des données (suppression des doublons et des dépenses inférieures à 10 €).
* Export des données nettoyées dans un nouveau fichier CSV.

## Fonctionnalités développées

* Lecture d'un fichier CSV avec Pandas.
* Affichage des premières lignes et des informations générales du jeu de données.
* Calcul de la moyenne et de la médiane de certaines colonnes.
* Visualisation des dépenses par pays sous forme de graphique à barres.
* Nettoyage des données (doublons, valeurs faibles).
* Export des données nettoyées dans un nouveau fichier CSV.

## Difficultés rencontrées

* Prise en main de l'environnement Python (Miniconda, Jupyter).
* Compréhension de certaines fonctions Pandas et Matplotlib.

**Solutions mises en place :** consultation de la documentation officielle de
Pandas/Matplotlib et de tutoriels vidéo pour comprendre le fonctionnement des
fonctions utilisées.

## Mode d'exécution

### Prérequis

* Miniconda
* Jupyter Notebook
* Pandas
* Matplotlib

### Installation

```bash
conda install jupyter pandas matplotlib
```

### Lancement

```bash
jupyter notebook
```

Ouvrir le fichier `exploration.ipynb` puis exécuter les cellules dans l'ordre.

---

**Auteur : Ferdaous El Bessami**