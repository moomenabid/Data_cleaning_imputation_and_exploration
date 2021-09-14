# Data_cleaning_imputation_and_exploration
__#Data cleaning 
__#Data imputation 
__#Data exploration

On m'a assigné une mission d'exploration de jeu de données public en open source qui est le __Open DAMIR__
__Ceci est un projet d’exploration, nettoyage et imputation de jeu de donnée publique en open source.__

Ce jeu de données concerne l'ensemble des prestations prises en charge par l'Assurance Maladie sur toute la France. 
Ces dépenses sont détaillées selon la période de soin, le département, les données du bénéficiaire, de l’organisme exécutant…
Vous trouverez le jeu de données dans des fichiers Excels au site web suivant https://www.data.gouv.fr/fr/datasets/open-damir-base-complete-sur-les-depenses-dassurance-maladie-inter-regimes/

Il n y avait pas de problème par rapport au volume des données car c'est un jeu de donnée volumineux. 
Il y a les dépenses mensuelles entre les années 2009 et 2019, et pour chaque mois, les dépenses correspondantes sont groupées dans un fichiers Excel de taille 5Go ce qui fait un total de 200Go correspondant à 220M lignes et 55 colonnes. 
On s’est donc dit que cette source sera sûrement utile pour y entraîner un modèle de Machine Learning. 

Après avoir effectué l’analyse exploratoire, le nettoyage et l'imputation des données, cette étude nous a permis de savoir que la source de donnée n’est pas du tout liée à notre niche qui est le marché des diagnostics in vitro. En effet, la grande majorité des actes n’étaient pas des actes d’analyses biologiques ou de diagnostic : c’était par exemple des actes de consultation chez un médecin, des actes chirurgicales, actes de radiologie...

On a donc passé aux autres sources de données qu'on peut exploiter.

