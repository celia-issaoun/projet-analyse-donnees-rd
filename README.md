
# Analyse et automatisation des données rhéologiques

### Projet Data Analyst R&D — Python | Streamlit | Statistiques

**Projet réalisé dans le cadre de mon stage de fin d'études
au sein du centre R&D du Groupe Bel — 2026.**

---

## 1. Présentation du projet

Dans le cadre de mon stage de fin d'études au sein
du Groupe Bel, j'ai travaillé sur l'amélioration
et l'automatisation du traitement de données
scientifiques issues d'analyses rhéologiques.

Les analyses rhéologiques permettent d'étudier
le comportement des matériaux et leurs propriétés
mécaniques dans différentes conditions expérimentales.

L'objectif de mon projet était de développer
une solution permettant de faciliter l'exploitation
des données, d'automatiser l'extraction d'indicateurs
et d'améliorer la reproductibilité des analyses.

Pour répondre à ces besoins, j'ai développé
une application web interactive avec Python
et Streamlit, destinée à faciliter le travail
des équipes scientifiques.

---

## 2. Objectifs du projet

Les principaux objectifs étaient :

- Automatiser le traitement des fichiers expérimentaux.
- Réduire les opérations manuelles répétitives.
- Standardiser les méthodes d'analyse.
- Extraire automatiquement des indicateurs pertinents.
- Visualiser les courbes et les résultats.
- Réaliser des analyses statistiques.
- Faciliter la comparaison des échantillons.
- Améliorer la fiabilité et la reproductibilité
  des traitements.
- Proposer une interface accessible aux utilisateurs
  ne maîtrisant pas nécessairement Python.

---

## 3. Technologies utilisées

| Technologie | Utilisation |
|------------|-------------|
| Python | Programmation et automatisation |
| Pandas | Manipulation et structuration des données |
| NumPy | Calculs numériques |
| SciPy | Calculs scientifiques et statistiques |
| Matplotlib | Visualisation des données |
| Streamlit | Développement de l'application web |
| Excel | Importation et exportation des résultats |
| Jupyter Notebook | Développement et expérimentation |
| GitLab | Gestion du projet et déploiement |

---

## 4. Présentation de l'application Streamlit

L'application a été conçue pour permettre
aux utilisateurs d'importer des fichiers
de mesures et de réaliser différentes analyses
à partir d'une interface interactive.

Elle regroupe plusieurs fonctionnalités
d'extraction, de visualisation et de comparaison
des résultats.

### Interface principale

![Interface principale](images/interface_principale.png)

*Capture de l'interface générale de l'application.*

### Principales fonctionnalités

- Importation de fichiers expérimentaux.
- Sélection du type d'analyse.
- Extraction automatique d'indicateurs.
- Visualisation interactive des courbes.
- Présentation des résultats sous forme de tableaux.
- Exportation des résultats vers Excel.

---

## 5. Analyse des courbes de refonte

### Objectif

L'analyse de refonte consiste à étudier
l'évolution des propriétés viscoélastiques
d'un échantillon en fonction de la température.

Les principales mesures étudiées sont :

- G' : module de conservation.
- G'' : module de perte.
- tan δ : rapport entre G'' et G'.

### Méthodologie

Le traitement comprend notamment :

1. Importation des données expérimentales.
2. Identification des mesures disponibles.
3. Préparation des courbes.
4. Analyse des variations de comportement.
5. Détection des changements de régime.
6. Extraction des températures caractéristiques.
7. Visualisation des résultats.

Une partie du travail repose sur l'identification
de zones de comportement et l'utilisation
d'intersections de droites ou de tangentes
pour déterminer des transitions.

### Visualisation des courbes

![Courbes de refonte](images/refonte_courbes.png)

*Exemple de visualisation des mesures rhéologiques.*

### Détection des transitions

![Transitions](images/refonte_transitions.png)

*Illustration de la détection des températures
caractéristiques par intersection de droites.*

### Extraction des résultats

![Résultats de refonte](images/refonte_resultats.png)

*Exemple de tableau récapitulatif des températures
extraites automatiquement.*

### Résultats obtenus

Cette fonctionnalité permet notamment :

- D'identifier plusieurs transitions sur une courbe.
- D'extraire automatiquement les températures associées.
- De visualiser les zones et les intersections détectées.
- De comparer les résultats entre différents fichiers.
- De centraliser les indicateurs dans un tableau.

---

## 6. Analyse des données de cassure

### Objectif

Cette analyse vise à identifier des paramètres
caractéristiques du comportement mécanique
des échantillons.

Deux types de représentations peuvent être utilisés :

- Couple en fonction du déplacement.
- Contrainte en fonction de la déformation.

### Méthodologie

Le traitement comprend :

1. Importation des fichiers.
2. Identification automatique des colonnes utiles.
3. Extraction des paramètres de cassure.
4. Organisation des résultats par échantillon
   et répétition.
5. Visualisation des courbes.
6. Exportation des indicateurs.

### Visualisation

![Analyse de cassure](images/cassure_courbes.png)

*Exemple de visualisation des courbes de cassure.*

### Tableau des résultats

![Résultats de cassure](images/cassure_resultats.png)

*Exemple de tableau des paramètres extraits.*

### Résultats obtenus

L'automatisation facilite :

- L'extraction des paramètres caractéristiques.
- Le traitement de plusieurs répétitions.
- La comparaison des échantillons.
- La structuration des résultats.
- La réduction des traitements manuels.

---

## 7. Analyse de viscosité

### Objectif

L'analyse de viscosité permet d'étudier
l'évolution du comportement d'un échantillon
en fonction du temps ou du gradient
de cisaillement.

### Méthodologie

Les fonctionnalités développées comprennent :

- L'importation des mesures.
- L'identification des colonnes pertinentes.
- La préparation des données.
- La visualisation des courbes.
- L'analyse des changements de comportement.
- L'extraction de paramètres caractéristiques.

Pour certaines analyses, des intersections
de tangentes permettent d'identifier
des transitions sur les courbes.

### Visualisation viscosité-temps

![Viscosité en fonction du temps](images/viscosite_temps.png)

*Exemple de courbe viscosité-temps.*

### Analyse des transitions

![Transitions de viscosité](images/viscosite_transitions.png)

*Exemple de détection des changements de régime.*

### Résultats

![Résultats viscosité](images/viscosite_resultats.png)

*Exemple de tableau des paramètres extraits.*

---

## 8. Analyses statistiques

### Objectif

Au-delà de l'extraction des indicateurs,
le projet comprend une partie statistique
permettant d'étudier les différences
entre plusieurs groupes d'échantillons.

### Méthodes utilisées

Selon les données et les conditions
d'application, les analyses peuvent comprendre :

- Statistiques descriptives.
- Calcul des moyennes et écarts-types.
- Étude de la dispersion des mesures.
- Test de Levene pour l'homogénéité des variances.
- Analyse de variance (ANOVA).
- ANOVA de Welch lorsque les variances
  ne sont pas homogènes.
- Visualisation des résultats par groupe.

### Visualisation statistique

![Comparaison statistique](images/statistiques_graphique.png)

*Exemple de comparaison des groupes.*

### Résultats des tests

![Résultats statistiques](images/statistiques_resultats.png)

*Exemple de tableau des résultats statistiques.*

### Intérêt

Cette partie permet :

- De résumer les mesures.
- D'étudier la variabilité des résultats.
- De comparer plusieurs groupes.
- D'évaluer statistiquement certaines différences.
- De faciliter l'interprétation des résultats.

---

## 9. Résultats et apports du projet

Le développement de cette application
a permis de mettre en place une solution
centralisant plusieurs traitements de données
scientifiques.

### Automatisation

Des traitements auparavant réalisés
manuellement peuvent être exécutés
à partir de l'application.

### Standardisation

Les méthodes d'extraction sont intégrées
dans des traitements reproductibles.

### Visualisation

Les utilisateurs disposent de graphiques
pour examiner les courbes et les paramètres
extraits.

### Exploitation des résultats

Les indicateurs sont organisés dans
des tableaux et peuvent être exportés
pour des analyses complémentaires.

### Accessibilité

L'interface Streamlit facilite l'utilisation
des traitements sans nécessiter
l'exécution directe de scripts Python.

---

## 10. Collaboration et déploiement

Le projet a été réalisé en collaboration
avec différents interlocuteurs :

- Experts scientifiques R&D.
- Équipes Data.
- Équipe informatique (IT).

Ces échanges ont permis de mieux comprendre
les besoins des utilisateurs, de valider
les résultats et de préparer la mise
à disposition de l'application.

Le projet a également impliqué l'utilisation
de GitLab dans le cadre de son déploiement.

---

## 11. Compétences développées

### Compétences techniques

- Programmation Python.
- Traitement de données scientifiques.
- Automatisation des analyses.
- Développement d'applications Streamlit.
- Extraction d'indicateurs.
- Visualisation de données.
- Analyses statistiques.
- Gestion et structuration des résultats.
- Utilisation de GitLab.

### Compétences transversales

- Analyse des besoins utilisateurs.
- Résolution de problèmes.
- Travail en autonomie.
- Collaboration avec des équipes
  pluridisciplinaires.
- Communication des résultats.
- Adaptation à un domaine scientifique
  spécialisé.

---

## 12. Confidentialité

Ce dépôt a pour objectif de présenter
les compétences techniques et les méthodes
mobilisées dans le cadre du projet.

Le code source de l'application, les données
expérimentales internes et les informations
confidentielles du Groupe Bel ne sont
pas publiés.

Les éventuelles visualisations présentées
dans ce dépôt doivent être autorisées
pour diffusion publique ou réalisées
à partir de données entièrement fictives.

---

## 13. À propos

**Celia ISSAOUN**

Data Analyst Junior

Master 2 Statistiques Appliquées et
Analyse Décisionnelle

Université de Caen Normandie — 2026

### Liens

- Portfolio :
  https://celia-issaoun.github.io/

- GitHub :
  https://github.com/celia-issaoun

- LinkedIn :
  https://www.linkedin.com/in/celia-issaoun/

- E-mail :
  issaouncelia21@gmail.com

---

*Projet présenté à des fins de valorisation
des compétences professionnelles.
Le code source et les données internes
ne sont pas accessibles publiquement.*
