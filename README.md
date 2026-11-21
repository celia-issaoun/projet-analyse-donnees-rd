
# Analyse et automatisation des données rhéologiques

### Projet Data Analyst R&D | Python • Streamlit • Statistiques

**Stage de fin d'études — Groupe Bel | 2026**

---

## 1. Présentation du projet

Dans le cadre de mon stage de fin d'études au sein
du centre de Recherche et Développement du Groupe Bel,
j'ai travaillé sur l'automatisation du traitement
et de l'analyse de données scientifiques issues
de mesures rhéologiques.

Les analyses rhéologiques permettent d'étudier
le comportement des matériaux et leurs propriétés
mécaniques dans différentes conditions expérimentales.

Le traitement de ces données nécessite plusieurs
étapes : préparation des fichiers, extraction
des paramètres caractéristiques, visualisation
des courbes et interprétation des résultats.

L'objectif de ce projet était de développer
une solution permettant de simplifier et
d'automatiser ces traitements, tout en améliorant
leur fiabilité et leur reproductibilité.

Pour répondre à ces besoins, j'ai développé
une application web interactive avec Python
et Streamlit, permettant aux utilisateurs
d'effectuer différentes analyses sans avoir
à exécuter directement du code Python.

---

## 2. Objectifs du projet

Les principaux objectifs étaient :

- Automatiser le traitement des données expérimentales.
- Réduire les opérations manuelles répétitives.
- Standardiser les méthodes d'extraction.
- Extraire automatiquement des indicateurs pertinents.
- Faciliter la visualisation et l'interprétation
  des résultats.
- Intégrer des méthodes d'analyse statistique.
- Améliorer la fiabilité et la reproductibilité
  des traitements.
- Développer une interface simple et accessible
  aux utilisateurs scientifiques.
- Faciliter l'exportation et la comparaison
  des résultats.

---

## 3. Technologies utilisées

| Technologie | Utilisation |
|------------|-------------|
| Python | Développement et automatisation |
| Pandas | Nettoyage et structuration des données |
| NumPy | Calculs numériques |
| SciPy | Calculs scientifiques et tests statistiques |
| Matplotlib | Visualisation des données |
| Streamlit | Développement de l'application web |
| Excel | Importation et exportation des résultats |
| Jupyter Notebook | Exploration et développement |
| GitLab | Gestion du projet et déploiement |

---

## 4. Développement de l'application Streamlit

Afin de faciliter l'utilisation des traitements,
j'ai développé une application web interactive
avec Streamlit.

L'application centralise plusieurs fonctionnalités
d'analyse des données rhéologiques et permet
aux utilisateurs d'importer directement
leurs fichiers expérimentaux.

### Fonctionnalités principales

- Importation de plusieurs fichiers Excel.
- Identification des données nécessaires aux analyses.
- Sélection des traitements à effectuer.
- Extraction automatique des indicateurs.
- Génération de graphiques.
- Affichage des résultats sous forme de tableaux.
- Comparaison de plusieurs échantillons.
- Réalisation d'analyses statistiques.
- Exportation des résultats vers Excel.

### Aperçu de l'interface

![Interface principale](images/interface_principale.png)

*Interface générale de l'application Streamlit.*

### Interface des fonctionnalités

![Fonctionnalités](images/interface_fonctionnalites.png)

*Présentation des différents traitements disponibles.*

---

## 5. Traitement et analyse des données rhéologiques

Dans le cadre de ce projet, j'ai développé
plusieurs fonctionnalités permettant d'automatiser
l'exploitation de données issues d'analyses
rhéologiques.

Les principaux travaux réalisés comprennent :

- **Analyse de refonte :** traitement des courbes
  rhéologiques, extraction des paramètres
  caractéristiques et identification automatique
  des températures de transition.

- **Analyse de cassure :** exploitation des courbes
  couple-déplacement et contrainte-déformation
  pour identifier et extraire les paramètres
  caractéristiques de cassure.

- **Analyse de viscosité :** traitement des données
  de viscosité en fonction du temps et du gradient
  de cisaillement, visualisation des courbes
  et identification des changements de comportement.

- **Détection des transitions :** développement
  de traitements permettant d'identifier
  des changements de régime à partir
  de l'analyse des courbes et des intersections
  de droites ou de tangentes.

- **Automatisation :** développement de fonctions
  Python pour traiter plusieurs fichiers,
  organiser les répétitions et standardiser
  l'extraction des indicateurs.

- **Visualisation et exportation :** génération
  de graphiques et de tableaux récapitulatifs,
  avec possibilité d'exporter les résultats
  vers Excel.

### Exemples de visualisations

![Visualisation des analyses](images/visualisation_courbes.png)

*Exemple de visualisation de courbes rhéologiques.*

### Extraction automatique des paramètres

![Extraction des paramètres](images/extraction_parametres.png)

*Exemple de détection de paramètres caractéristiques
sur les courbes.*

### Tableaux des résultats

![Résultats des analyses](images/resultats_analyses.png)

*Exemple de tableau récapitulatif des indicateurs
extraits automatiquement.*

---

## 6. Analyses statistiques et comparaison des échantillons

### 6.1. Objectif

Une partie du projet a été consacrée à l'analyse
statistique des paramètres extraits afin
d'étudier la variabilité des mesures et
de comparer différents groupes d'échantillons.

L'objectif était de compléter les observations
graphiques et les statistiques descriptives
par des méthodes statistiques permettant
d'évaluer la significativité des différences
observées entre les groupes.

En effet, les différences constatées entre
plusieurs moyennes ne permettent pas,
à elles seules, de conclure à l'existence
d'une différence statistiquement significative.

### 6.2. Préparation des données

Avant de réaliser les analyses statistiques,
plusieurs étapes de préparation ont été effectuées :

- Regroupement des données par échantillon.
- Identification et organisation des répétitions.
- Vérification des valeurs disponibles.
- Structuration des tableaux de résultats.
- Préparation des variables à comparer.

Ces traitements permettent de disposer
de données structurées et adaptées
aux méthodes statistiques utilisées.

### 6.3. Statistiques descriptives

Une première analyse descriptive permet
de résumer les données et d'étudier
leur variabilité.

Les principaux indicateurs utilisés sont :

- Nombre d'observations.
- Moyenne.
- Écart-type.
- Dispersion des mesures.

Ces indicateurs permettent de comparer
les caractéristiques générales des groupes
et de mettre en évidence les premières
différences observées.

Cependant, les statistiques descriptives
ne suffisent pas à déterminer si les différences
entre les groupes sont statistiquement
significatives.

### 6.4. Tests statistiques

Afin d'approfondir les comparaisons,
différents tests statistiques ont été intégrés
aux traitements.

#### Test de Levene

Le test de Levene permet d'évaluer
l'homogénéité des variances entre
plusieurs groupes.

Il est utilisé pour vérifier si les variances
peuvent être considérées comme homogènes
et orienter le choix de la méthode
de comparaison des moyennes.

#### Analyse de variance (ANOVA)

L'analyse de variance permet de comparer
les moyennes de plusieurs groupes.

Lorsque les conditions d'application
sont satisfaites, elle permet de tester
l'hypothèse selon laquelle les moyennes
des groupes sont égales.

Un résultat statistiquement significatif
indique qu'au moins une moyenne diffère
des autres, sans nécessairement identifier
directement les groupes concernés.

#### ANOVA de Welch

Lorsque l'hypothèse d'homogénéité
des variances n'est pas satisfaite,
l'ANOVA de Welch peut être utilisée.

Cette méthode est adaptée à la comparaison
des moyennes lorsque les variances
des groupes sont inégales.

Le choix du test permet ainsi de tenir
compte des caractéristiques des données
et de produire une analyse statistique
plus adaptée.

### 6.5. Visualisation des résultats statistiques

Les résultats statistiques sont présentés
sous forme de graphiques et de tableaux
afin de faciliter leur interprétation
par les experts scientifiques.

Les visualisations permettent notamment :

- De comparer les moyennes entre les groupes.
- De représenter la variabilité des mesures.
- De visualiser les écarts observés.
- De faciliter l'interprétation des résultats
  des tests statistiques.

#### Comparaison des moyennes

![Graphique statistique](images/statistiques_graphique.png)

*Exemple de comparaison des moyennes avec
représentation de la variabilité des mesures.*

#### Résultats des tests statistiques

![Résultats statistiques](images/statistiques_resultats.png)

*Exemple de tableau récapitulatif des résultats
des tests statistiques.*

### 6.6. Apports des analyses statistiques

Cette partie du projet permet :

- De compléter les analyses descriptives
  par des tests statistiques.
- D'étudier la variabilité des mesures.
- De comparer plusieurs groupes d'échantillons.
- D'adapter les méthodes statistiques
  aux caractéristiques des données.
- De faciliter l'interprétation des résultats.
- De communiquer les conclusions de manière
  claire aux experts scientifiques.

---

## 7. Résultats et apports du projet

Le développement de cette application
a permis de centraliser plusieurs traitements
de données scientifiques dans une interface unique.

### Automatisation des traitements

Des opérations auparavant réalisées
manuellement peuvent être automatisées,
ce qui facilite le traitement de plusieurs
fichiers expérimentaux.

### Fiabilité et reproductibilité

L'utilisation de fonctions Python permet
de standardiser les traitements et
d'appliquer des méthodes cohérentes
aux différentes données analysées.

### Extraction des indicateurs

Les paramètres caractéristiques sont
extraits automatiquement et organisés
dans des tableaux récapitulatifs.

### Visualisation des données

Les graphiques facilitent l'exploration
des mesures et l'interprétation
des résultats.

### Analyse statistique

L'intégration des méthodes statistiques
permet d'approfondir les comparaisons
entre les échantillons.

### Accessibilité

L'interface Streamlit facilite
l'utilisation des traitements par
des experts scientifiques ne maîtrisant
pas nécessairement la programmation Python.

---

## 8. Collaboration et déploiement

Le projet a été réalisé en collaboration
avec les équipes scientifiques et Data.

Les échanges avec les experts métier
ont permis de :

- Comprendre les besoins liés aux analyses.
- Identifier les paramètres à extraire.
- Adapter les traitements aux données.
- Vérifier et valider les résultats.
- Améliorer la présentation des visualisations.
- Faciliter l'utilisation de l'application.

L'application a également été intégrée
dans un environnement GitLab dans le cadre
de sa mise à disposition des utilisateurs.

---

## 9. Compétences développées

### Compétences techniques

- Analyse et traitement de données scientifiques.
- Programmation Python.
- Nettoyage et structuration des données.
- Automatisation des traitements.
- Extraction d'indicateurs.
- Analyses statistiques.
- Visualisation de données.
- Développement d'applications Streamlit.
- Gestion des fichiers Excel.
- Utilisation de GitLab.

### Compétences transversales

- Analyse des besoins utilisateurs.
- Résolution de problèmes.
- Travail en autonomie.
- Collaboration avec des équipes
  pluridisciplinaires.
- Communication des résultats.
- Vulgarisation des analyses statistiques.
- Adaptation à un environnement R&D.

---

## 10. Confidentialité

Ce dépôt présente une synthèse des travaux
et des compétences développées dans
le cadre de ce projet.

Le code source de l'application, les données
expérimentales internes et les informations
confidentielles du Groupe Bel ne sont
pas publiés.

Les illustrations présentées sont
des exemples de démonstration autorisés
pour diffusion publique ou réalisés
à partir de données fictives.

---

## 11. À propos

**Celia ISSAOUN**

**Data Analyst Junior**

Diplômée d'un Master 2 Mathématiques appliquées,
statistiques — parcours Statistiques Appliquées
et Analyse Décisionnelle.

Université de Caen Normandie — 2026.

Spécialisée dans le traitement, l'analyse
statistique et la visualisation des données,
avec un intérêt particulier pour l'automatisation
et le développement de solutions facilitant
l'exploitation des données.

### Me retrouver

- **GitHub :** https://github.com/celia-issaoun
- **Portfolio :** https://celia-issaoun.github.io/

---

*Projet présenté dans le cadre de la valorisation
de mes compétences professionnelles.
Le code source et les données confidentielles
ne sont pas accessibles publiquement.*
