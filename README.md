# GIT

Les outils de versionning : ont pour mission de modifier des documents voire des fichiers. Ils sauvegardent dans une archive toutes les versions créées comprenant les horodatages ainsi que les identifiants uniques, de sorte que les anciennes données peuvent à tout moment être chargées voire restaurées 

Git : Le créateur de Linux Linus Thorvald a commencé le développement d’un nouveau logiciel de versionning en avril 2005. Il y était plus ou moins forcé. La raison de ce rebondissement était que les développeurs du noyau Linux avaient perdu leur accès gratuit du fait d’une modification de la licence du système BitKeeper. Le nouveau système avait pour but de présenter les mêmes flux de travail que BitKeeper et de protéger contre les modifications délibérées ou accidentelles. Par ailleurs, son efficacité était bien supérieure. C’est seulement après seulement quelques jours que Thorvald présentait la première version de Git. 

Derrière Git se cache un système de versionning décentralisé. Il existe un dépôt (de l’anglais repository) dans lequel tous les changements sont incorporés et qui permet aux utilisateurs d’y télécharger leurs propres copies de travail. Ils disposent également d’un dépôt complet qui comprend l’historique local sans qu’ils n’aient besoin d’une connexion permanente au réseau. Par ailleurs, les modifications sont transférées rapidement dans le dépôt principal. En conséquence, Git ne propose pas de système de verrouillage mais permet à tous les utilisateurs de créer leurs propres branches qui seront ensuite téléchargées dans le dépôt principal. Chaque utilisateur dispose par ailleurs des droits de lecture et d’écriture standards pour tout le répertoire. S’il existe d’autres droits, d’autres répertoires principaux doivent alors être définis. Chaque copie de travail est une sauvegarde individuelle du répertoire principal, ce qui présente un avantage au cas où celui-ci tombe en panne ou est abîmé. Git ne définit que les contenus des répertoires, c’est pourquoi les répertoires vides sont automatiquement supprimés. 

GitHub : La plateforme GitHub permet aux programmeurs informatiques de collaborer librement sur des projets de code. Découvrez tout ce que vous devez savoir sur ce service massivement utilisé dans la Data Science et le Machine Learning, et comment apprendre à l'utiliser. 

GitHub est un service d’hébergement Open-Source, permettant aux programmeurs et aux développeurs de partager le code informatique de leurs projets afin de travailler dessus de façon collaborative. On peut le considérer comme un Cloud Dédié au code informatique. 

Le code source des projets est hébergé dans différents langages de programmation, et les changements apportés à chaque itération sont gardés en mémoire. Les autres utilisateurs de GitHub peuvent passer en revue le code et proposer des modifications ou des améliorations. 

L’une des principales fonctionnalités de GitHub est son système de contrôle de version. Grâce à cette fonctionnalité, les autres utilisateurs peuvent modifier le code d’un logiciel sans toutefois impacter directement le logiciel ou l’expérience des utilisateurs actuels. Les changements proposés peuvent être intégrés au logiciel, après avoir été passés en revue et approuvés. 

Un autre point fort est la possibilité d’intégrer GitHub avec la plupart des plateformes et services les plus communs comme Amazon, Google Cloud Ou Code Climate. En outre, ce service est compatible avec la syntaxe de plus de 200 langages de programmation différents. 

Notons que GitHub n’est pas le seul site web dédié au développement collaboratif de logiciel grâce au contrôle de version. Cependant, il s’agit certainement du plus populaire. En juillet 2020, la plateforme fédère plus de 45 millions d’utilisateurs. 

---->Le succès de ce service a attiré l’attention de Microsoft. En 2018, le géant américain a acquis GitHub pour la somme de 7,5 milliards de dollars en actions. 

----> code, issue, pull request 

Le forking (bifurcation), les pull requests (requêtes de tirage), et le merging (fusion). 

  

Le forking consiste à créer une copie d’un projet. Ainsi, il est possible d’expérimenter librement sur ce projet sans affecter l’original. 

  

Après avoir effectué des changements satisfaisants, il suffit de soumettre un pull request ou requête de tirage. Cette requête est envoyée au propriétaire du projet, qui peut alors passer en revue les modifications effectuées et poser ses éventuelles questions. 

  

Si le propriétaire du projet est satisfait par les changements proposés, il ne lui reste plus qu’à fusionner la pull reiquets avec le code d’origine. Les modifications seront alors apportées au projet originel. 
