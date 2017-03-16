# crime-prediction-system-montreal
Systeme de prediction de crimes pour la ville de Montreal, Projet dans le cadre du cours INFO4006 - Machine Learning.

## Introduction
Commençons par une citation d'Aaron Levenstein (statisticien et professeur américain) : "Les statistiques, c'est comme le bikini. Ce qu'elles révèlent est suggestif. Ce qu'elles dissimulent est essentiel". Par cette phrase, le professeur voudrait tout simplement lancer les bases d'un certain message caché dans les chiffres. Les chiffres sont brutes, mais lorsque mis sous une certaine forme, permettent de traduire des réalités qui s'appliquent à notre monde. Partant de cette base, nous proposons dans le cadre du cours de Machine Learning (INFO4007), un projet qui s'axe autour de l'interprétation de données. Nous voudrions fournir un outil de gestion pour la ville de Montréal sur base de plusieurs indicateurs comme le taux de criminalité, le taux de dispatch des pompiers, le taux d'accident, la météo... Cet outil permettra aussi de fournir des détails spécifiques pour chaque division administrative de la ville de Montréal.  Le choix de Montréal repose sur 2 fondements : c'est dans un premier temps une ville francophone (données francophones) et dans un second temps c'est une des villes qui a le plus de données ouvertes au Canada : la base de données contient actuellement 233 différents jeux de données, répartis sur une dizaine de catégories et accessibles dans une vingtaine de format. Un mot d'ordre en machine learning : plus il y a de données, mieux les prédictions seront bonnes. 

## Aspect théorique
La prédication des donnees tentera de répondre à des questions de style : 
— "Une prevision des types de crimes susceptibles d’advenir aujourd’hui
— Les zones les plus à risques

L’analyse de données reposera essentiellement sur 2 types de méthodes :
— La régression linéaire : pour construire des estimateurs forts et pre ́dire certaines tendances
— Laclassi cation:ide ́alpourcate ́goriserdesincidentssuivantscertainssche ́mas.C’estencelalaforcedu
deep learning : il permet d’exploiter les corrélations entre les donne ́es souvent invisibleà l’esprit humain, mais mathématiquement liées.

Une fois les constructions des modèles terminées, on pourra stocker les réultats dans une base de données, pour ainsi les obtenir à la volée. On disposera ainsi d’une interface graphique (page web) pour visualiser les résultats.

Pour l’instant nous avons déterminé les données suivantes : (dépendamment de la faisabilité et de l’accèssibilité, cela pourra évoluer) :
— Cas d’incidents criminels
- Cas d’incendies (Tels que rapportés par le SIM : Service Incendie de Montreal)
