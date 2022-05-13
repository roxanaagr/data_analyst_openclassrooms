Ce projet a été réalisé en utilisant le langage de programmation R. J'ai utilisé des fichiers RMarkdown car ils constituent un moyen simple d'inclure à la fois du code et des commentaires. Chaque fichier a déjà été exécuté (la sortie étant un fichier html), de sorte que si quelqu'un est intéressé par le nettoyage/l'analyse et qu'il n'utilise pas R ou n'a pas tous les packages, il peut toujours voir tous les résultats du nettoyage et de l'analyse.

Ce projet a été réalisé en utilisant le langage de programmation R. J'ai utilisé des fichiers RMarkdown car ils constituent un moyen simple d'inclure à la fois du code et des commentaires. Chaque fichier a déjà été exécuté (la sortie étant un fichier html), de sorte que si quelqu'un est intéressé par le nettoyage/l'analyse et qu'il n'utilise pas R ou n'a pas tous les packages, il peut toujours voir tous les résultats du nettoyage phase et la phase d'analyse.

Afin d'exécuter ce projet, les packages suivants doivent être utilisés (en plus de ceux liés à RMarkdown):

- tidyverse
- lubridate
- gglorenz
- hrbrthemes

Tous peuvent être facilement installés en utilisant install.packages("package_name").

De plus, il s'agit d'un dossier RProject, par conséquent, un double-clic sur le P4_Agrigoroaie_Roxana.Rproj ouvrirait automatiquement RStudio (s'il est installé) et en utilisant Fichier -> Ouvrir un fichier (et en sélectionnant soit les fichiers de nettoyage soit les fichiers d'analyse), l'utilisateur peut facilement exécuter chacun des dossiers préparés pour ce projet.

Chaque morceau de code R peut être exécuté manuellement, ou le fichier entier peut être exécuté à l'aide de la fonctionnalité Knit.
Certains des graphiques de la phase d'analyse étaient déjà enregistrés dans le dossier des graphiques (graphs). Lorsque le fichier est exécuté à nouveau, les graphiques sont écrasés.

Ce projet contient les dossiers suivants:

- data -> qui contient toutes les données nécessaires
	-> customers.csv
	-> products.csv
	-> transactions.csv
	-> clean_data.csv
	-> clean_data.RData

- graphs -> qui contient les graphes qui ont été sauvegardés lors de l'analyse

Ce projet contient les fichiers suivants:

- P4_01_nettoyage_donnees.Rmd  -> Fichier R Markdown contenant le code et les commentaires pour la phase de nettoyage
- P4_01_nettoyage_donnees.html -> un fichier html contenant la sortie du code et les commentaires de la phase de nettoyage.
- P4_02_analyse.Rmd  -> R fichier Markdown contenant le code et les commentaires pour la phase d'analyse
- P4_02_analyse.html -> un fichier html contenant la sortie du code et les commentaires pour la phase d'analyse.
- P4_Agrigoroaie_Roxana.RProj -> le fichier projet R

Comment exécuter le code:

- Double-cliquez sur CompanySales.RProj. L'interface RStudio s'ouvrira alors. Fichier->Ouvrir le fichier et sélectionnez d'abord data_cleaning_fr.Rmd. Vous pouvez soit appuyer sur Knit pour exécuter l'intégralité du fichier et le résultat sera un fichier html (qui est déjà disponible dans le dossier du projet), soit exécuter chaque morceau de code individuellement.

Ensuite, vous pouvez ouvrir le fichier analysis_fr.Rmd et soit appuyer sur Knit pour exécuter le fichier entier et le résultat sera un fichier html (qui est déjà disponible dans le dossier du projet), ou vous pouvez exécuter chaque morceau de code individuellement.
