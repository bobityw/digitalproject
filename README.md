# Dashboard de Suivi des Projets Digitaux
Ce mini-projet a pour objectif de réaliser un tableau de bord sur différents projets digitaux fictifs. 
Le data set a été généré par ChatGPT. Il inclut: 
- Le nom du projet
- Le statut
- La date de début et de fin prévue
- La date réelle de fin
- Le budget prévu et réel 
- L'écart de budget
- La satisfaction client %: optionnelle pour les projets en cours
- Le risque %: Évaluation du pourcentage de risque lié à chaque projet (problèmes de délais, dépassement de budget).
- Le délai
- Le temps passé
- Le responsable
- Le département
- FTE: calculé à partir de l'effort.

## Page 1 : Vue Générale des Projets

Cette page fournit un aperçu global des projets en cours, terminés, et en attente. Elle inclut :

- Une **jauge du budget actuel** par rapport aux prévisions.
- Le **nombre total de projets**, répartis par statut (terminés, en cours, non démarrés).
- Un radar pour **visualiser les FTE** (équivalents temps plein) par projet.
- Un tableau récapitulatif affichant **les principaux indicateurs** des projets.
  
![Page 1](/Images/Page%201.png)

## Page 2 : Suivi des KPI et Déviations

La deuxième page permet d'analyser en profondeur les indicateurs de performance :
- Un graphique en courbes pour **comparer le budget courant au budget prévisionnel**.
- Un tableau montrant la **répartition des projets et FTE par département**.
- Des **indicateurs clés** tels que le dépassement de budget et le temps passé par projet.
- Une mesure de la **satisfaction par département**, permettant d'identifier les zones à risque.

![Page 2](/Images/Page%202.png)

## Dans ce repository
Vous trouverez dans ce repository les éléments nécessaires à la réalisation de ce mini-projet, à savoir:

1. BI: *DigitalProjects.pbix* - Utilisé pour la mise en place des dashboards
2. Dataset:
    
    2.1 *dataset.ipynb* - Notebook Jupyter pour l'exploration de données dans Python
    
    2.2 *digitals_projects_tracker.csv* - Données initiales générées par ChatGPT, utilisées pour l'exploration de données
    
    2.3 *digitals_projects_tracker.xlsx* - Données finales utilisées dans PowerBI
3. Images: Images de présentation du résultat final