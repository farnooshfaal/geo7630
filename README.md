# geo7630
Tp2
Étudier la relation entre le taux de criminalité et le revenu moyen
•	Objectif
•	Les sources de données
•	Etabli FME
•	Schématisation du processus FME
•	Projet QGIS
•	Criminalité 2019
•	Criminalité 2020




Objectif:
Le but de ce projet est d'explorer la relation entre les taux de criminalité et les niveaux de revenu à Montréal, en mettant l'accent sur l'impact de la pandémie de COVID-19 sur la criminalité dans la ville. Le projet analyse les données sur la criminalité de 2019 et 2020 pour comparer les taux de criminalité avant et après le début de la pandémie. Le projet examine également la relation entre les taux de criminalité et les niveaux de revenu pour identifier les zones de la ville qui sont plus à risque de criminalité.

Les sources de données:
  Le projet utilise trois principales sources de données : les données sur la criminalité, les données de recensement et les données sur les quartiers. Les données sur la criminalité ont été obtenues du portail Données ouvertes de Montréal et comprennent des informations sur le lieu, le type et la date des crimes signalés à Montréal en 2019 et 2020. Les données du recensement ont également été obtenues du portail Données ouvertes de Montréal et comprennent des informations sur les caractéristiques démographiques. et le statut socioéconomique par quartier. Les données sur les quartiers ont été obtenues du portail Données ouvertes de Montréal et comprennent des informations sur les limites de chaque quartier de Montréal. Tous ces ensembles de données ont été prétraités et combinés à l'aide du logiciel FME pour créer un ensemble de données complet à analyser. De plus, d'autres données telles que le lidar ont été préparées pour ce projet.
De plus, des informations d'imagerie lidar et aérienne ont été utilisées dans ce projet pour obtenir des données 3D.

Workbench FME:
FME (Feature Manipulation Engine) est un outil logiciel qui permet aux utilisateurs de manipuler et de transformer des données spatiales et non spatiales.
J'ai utilisé FME pour prétraiter et combiner plusieurs ensembles de données afin de créer un ensemble de données complet pour l'analyse de la relation entre les taux de criminalité et les niveaux de revenu à Montréal.
FME fonctionne en utilisant des "transformateurs" pour manipuler les données. Les transformateurs sont comme des blocs de construction qui peuvent être connectés ensemble pour créer un flux de travail pour le traitement des données. Par exemple, j'utilise un transformateur pour reprojeter des données spatiales d'un système de coordonnées à un autre, ou pour filtrer des données en fonction de certains critères.
Pour créer mon flux de travail FME, j'ai connecté une série de transformateurs ensemble dans un ordre spécifique pour prétraiter et combiner mes sources de données. Par exemple, j'ai utilisé un transformateur pour filtrer les données sur la criminalité afin d'inclure uniquement les données de 2019 et 2020, puis j'ai utilisé un autre transformateur pour joindre les données sur la criminalité aux données du recensement basées sur le quartier.
En utilisant le lien que j'ai mis à la fin de ce fichier, vous pouvez facilement obtenir les données nécessaires pour exécuter fme.

![schema_fme](https://user-images.githubusercontent.com/55294090/224590755-2b091bc2-7f17-469f-86fe-d0de650ae8f2.png)

Schematization of the FME process:
![schema image](https://user-images.githubusercontent.com/55294090/224590862-e31cc46e-56a8-49a3-9044-c3caf88ecac2.jpg)

Projet QGIS
• Criminalité 2019
![crime 2019 image](https://user-images.githubusercontent.com/55294090/224590908-e53af77d-61e2-4fd8-bdf7-244c62e73a4e.png)

Criminalité 2020
![crime 2020 image](https://user-images.githubusercontent.com/55294090/224590963-d6276bf4-40fa-4b8f-9833-4471ad798acc.png)


link for FME data:
https://drive.google.com/drive/folders/1ZmRHiAduSLKjWPiTdDMVx4jLj9XKjbX2?usp=share_link
