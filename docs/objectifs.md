---
layout: default
nav_order: 3
title: Objectifs du projet
---


                                                ROBOT  OTTO



1. RÉSUMÉ DU PROJET
 	1.1. Contexte du projet
1.2. Nos objectifs 
2. CONTEXTE ET STRATÉGIE 

2.1 Analyse et recherche 
2.2. Les innovations apportées à notre modèle
2.3 Programmation logicielle
2.4. Défis rencontrés et solutions apportées 
3. VALORISATION, GESTION DE PROJET 
3.1. Gestion des ressources et cycle d’éco conception
3.2. Tests de performance 
4. CONCLUSION


1. RÉSUMÉ DU PROJET
1.1 Contexte du projet
Dans un monde où la transformation numérique et l’automatisation changent le monde de l’industrie, savoir utiliser les nouvelles technologies et les intelligence artificielle est devenu un enjeu stratégique majeur. C'est dans ce sens  que s'inscrit le projet Otto-MKS,que l’on à  mené au sein du MakerSpace à UniLaSalle.
Le projet repose sur la modification et l'optimisation des différents éléments du robot Otto-MKS. Ce robot a été développé au départ  à partir des fichiers standards open-source; cette solution intègre un microcontrôleur de type ESP32 puissant offrant une connectivité Wi-Fi et Bluetooth ainsi qu'une gestion énergétique via une batterie rechargeable par USB-C.
Pour notre équipe, ce projet constitue une véritable mise en situation technique. Il ne s'agit pas simplement d'assembler un kit  existant, mais de faire  un cycle complet; en commençant par la  recherche,puis la  conception et enfin la  programmation afin d’arriver à un robot capable de se déplacer grâce à une application. À partir d'une base matérielle commune, notre mission a été de réfléchir à différents moyens pour parvenir à modifier notre robot pour qu’il puisse braver les différentes épreuves qu’il devra affronter. Nous avons conçu des fonctionnalités pour transformer un robot standard en un robot, performant  et différencié des autres.
1.2 Nos objectifs : apprendre et se faire plaisir
Le projet Otto-MKS ne se limite pas simplement à monter un kit, il y a un réel objectif derrière; préparer de futur ingénieur. Pour y parvenir ce projet 
Les objectifs pédagogiques
Apprendre en faisant : L’objectif est de développer concrètement nos compétences en électronique, en mécanique et en programmation. On ne se contente pas d'étudier, on manipule, on teste et on ajuste.
-Apprendre à travailler en équipe : C’est un projet de groupe. On apprend à se répartir les tâches, à communiquer, à gérer les idées de chacun et à avancer ensemble pour que les différentes parties du robot s'assemblent parfaitement.
-Résoudre des problèmes concrets : On part d'une base open-source, mais on doit l'améliorer pour gagner des épreuves bien précises (sumo, course, tir à la corde, obstacles). Cela nous force à être créatifs et à trouver des solutions astucieuses quand quelque chose ne fonctionne pas comme prévu.
Ce qui nous motive : l'esprit du projet
Travailler sur un robot, c’est stimulant. On a une grande liberté pour imaginer des modifications et rendre notre modèle unique, ce qui nous pousse à nous investir davantage.C'est l'occasion de sortir du cadre des cours classiques. On explore de nouvelles technologies comme l'ESP32 et on réfléchit par nous-mêmes à comment intégrer des fonctionnalités innovantes.On souhaite documenter notre travail pour que d’autres étudiants puissent s’en inspirer. C’est gratifiant de se dire que nos trouvailles pourraient servir à la communauté du MakerSpace et montrer ce qu’on est capables de réaliser en tant que futurs ingénieurs.

2.1. Analyse et recherche : vers notre propre vision du robot
Avant de nous lancer tête baissée dans l'assemblage, nous avons pris le temps d'analyser les différentes options qu’internet pouvait nous offrir. Notre objectif était clair, transformer notre robot  pour qu'il soit compétitif sur les différentes épreuves qui nous attendaient, comme le combat de sumo, la course de vitesse, le tir à la corde ou encore le franchissement d'obstacles.
Nous avons commencé par explorer les designs existants sur Internet. Très vite, une référence commune s'est imposée à nous,  Wall-E. Ce petit robot seul dans son monde désolé nous a tous marqués, et nous avions à cœur de donner à notre création cette identité visuelle unique. Le problème, c'est que les fichiers 3D disponibles en ligne ne nous convenaient pas,  soit ils ne respectaient pas notre design Wall-E, soit ils étaient impossibles à modifier correctement pour nos différents besoins techniques. C’est ce constat qui a fait que nous avons préféré tout concevoir nous-mêmes, du corps jusqu'aux accessoires. Pour nous, c'est ça le cœur de l'ingénierie, créer plutôt que de simplement assembler des fichiers tout faits.
Répartition des rôles et organisation Pour mener ce projet à bien, nous avons réparti les missions en fonction des forces de chacun :
-Design du corps : Refonte totale de la structure pour coller à notre vision esthétique.
-Accessoires et mécaniques : Conception des bras et des yeux, essentiels pour le look final et pour nos stratégies de combat.
-Développement logiciel : Gestion du code pour le déplacement, la marche, et la création de l'application de contrôle à distance.
-Gestion du projet et finition : Rédaction de ce rapport, finalisation de l'interface de l'application et coordination de la peinture pour une esthétique soignée.
Nos phases de recherche et les idées abandonnées
 L'innovation, c'est aussi savoir abandonner les idées qui ne fonctionnent pas. Nous avons testé pas mal de pistes :
-La protection contre les coups : On a imaginé une "casquette" pour éteindre les robots adverses ou une coupole pour protéger le bouton d'arrêt d'urgence . Problème , soit c'était moche, soit cela déséquilibrait complètement le robot. Finalement, nous avons intégré les yeux de façon à ce qu'ils servent naturellement de bouclier.
-Le brouillage à ultrasons : On a pensé à utiliser les ondes pour déstabiliser les autres robots, mais en plus de la complexité technique, nous avons préféré renoncer pour respecter les règles éthiques du tournoi qui est de ne jamais endommager le matériel adverse.
-Le système de combat (bras et coups de poing) : Après plusieurs tests, les systèmes de "coups de poing" rétractables dans le ventre se sont révélés trop lourds ou trop complexes à recharger. Nous avons aussi essayé des poignée articulés pour faire basculer l'adversaire, mais là encore, le poids et le déséquilibre créé nous ont poussés à privilégier, des bras qui vont faire office de levier afin de faire basculer nos adversaires.
Au cours de nos tests de vitesse, nous avons même poussé nos servomoteurs au maximum. Cela nous a coûté un peu de casse avec un servomoteur qui a lâché et un autre bloqué par un défaut d'usine,  mais c’est grâce à ces échecs que nous avons appris à mieux calibrer nos mouvements. Pour finir, ces recherches nous ont permis d'affiner notre robot, non seulement pour qu'il soit performant, mais pour qu'il garde le style  de "Wall-E" que nous voulions absolument conserver.
2.2. Les innovations apportées à notre modèle 
Pour passer d’un robot standard à notre propre version  Wall-E, nous avons dû repenser l'architecture globale. Plutôt que de surcharger le robot, nous avons opté pour une approche minimaliste et fonctionnelle, où chaque ajout a une utilité précise pour les épreuves de combat.
Plutôt que d'utiliser des fichiers 3D génériques, nous avons modélisé nos propres pièces sur Onshape. L'idée était de garder une ligne épurée tout en intégrant des éléments iconiques du personnage.
-La structure : Le corps a été entièrement redessiné pour offrir une silhouette robuste et fidèle à l'esthétique du robot Wall-E, avec une attention particulière portée à la gestion des volumes pour ne pas déséquilibrer le robot.
-Les yeux : Ils sont le cœur de l'identité visuelle de notre projet. En plus de donner vie au robot, ils ont été pensés pour agir comme une protection naturelle au-dessus de sa tête, bloquant les tentatives d'extinction du bouton principal par les adversaires.
Nous avons ajouté des bras articulés qui ne sont pas là que pour le look .Ces bras ont été conçus pour offrir une amplitude de mouvement efficace. Ils permettent à la fois de stabiliser le robot lors des déplacements rapides et de servir de levier en combat. Nous avons misé sur la capacité à soulever l'adversaire et  à se maintenir en position pour ne pas basculer vers l'arrière. C’est un choix tactique qui nous évite d'ajouter des mécanismes complexes et lourds de type coups de poing, qui risqueraient de nous faire perdre notre centre de gravité.Nous avons volontairement limité les accessoires superflus. Trop d'ajouts auraient alourdi le châssis et complexifié la programmation. En restant sur une structure simple mais personnalisée, nous garantissons une meilleure réactivité des servomoteurs, ce qui est crucial pour nos épreuves de vitesse et d'agilité.La peinture de notre robot ajoute un réel plus c’est ce qui fait passer notre robot de simple robot modifier a un super robot.
2.3. Programmation logicielle : le cerveau de notre robot
La partie logicielle est le cœur du projet. Pour que notre robot ne soit pas seulement une structure esthétique mais une machine qui puisse se déplacer et faire des actios, nous avons dû travailler sur deux axes majeurs : le pilotage matériel et l'interface de contrôle.
La programmation des déplacements a été un défi technique, surtout lorsqu'on cherche la performance pour les épreuves de vitesse.Nous avons cherché à pousser les servomoteurs au maximum de leurs capacités. Cela a nécessité des ajustements précis dans le code pour optimiser les cycles de marche et éviter les blocages mécaniques, tout en apprenant à gérer les limites physiques du matériel suite à quelques incidents de parcours.
Le code est conçu pour être fluide, ce qui est crucial lors des combats pour esquiver ou se repositionner rapidement.Pour piloter le robot, nous avons développé une application dédiée qui communique avec l'ESP32.
Plutôt que de surcharger l'écran, nous avons opté pour une interface sobre et intuitive, avec les commandes essentielles accessibles rapidement.L'application permet de basculer facilement entre les différents comportements du robot, notamment pour le faire se déplacer ou pour le faire attaquer.Afin de garantir la meilleure stabilité possible, la personne en charge du codage du robot a également pris en main le développement complet de l'application. Cette centralisation a permis une meilleure cohérence entre les commandes envoyées et la réponse mécanique du robot.
En résumé, le logiciel ne sert pas uniquement à faire bouger le robot ; il sert à traduire nos intentions tactiques en actions concrètes sur le terrain. C’est un travail de précision qui continue d'évoluer au fil de nos tests.
2.4. Défis rencontrés et solutions apportées
Tout projet d'ingénierie comporte sa part d'imprévus. L'intérêt de ce projet Otto-MKS a justement été de nous confronter à des problèmes concrets qui nous ont obligés à monter en compétence rapidement.
Le principal défi a été l'interdépendance des pièces. Comme tout le robot doit s'emboîter parfaitement, la moindre modification sur une pièce impliquait de revoir la structure globale. Cela nous a demandé beaucoup de rigueur sur le logiciel de conception. La modélisation des yeux, par exemple, s'est révélée complexe à modéliser au vue des détails ajouter.Côté programmation, nous avons dû gérer des soucis d'interfaçage entre la carte ESP32 et l'IDE Arduino. Faire communiquer le code avec le matériel demande une grande précision, et nous avons dû passer du temps pour stabiliser les connexions. Ces difficultés, bien que frustrantes sur le moment, nous ont permis de mieux comprendre le fonctionnement de l'ESP32 et de fiabiliser notre code de base.Nous avons également rencontré des imprévus mécaniques, comme la casse de servomoteurs lors de tests de vitesse trop intensifs ou des défauts de fabrication sur certains composants fournis. Ces expériences nous ont appris à tester nos hypothèses avant de les valider, et surtout à être plus méthodique dans notre gestion du matériel.
3.1. Gestion des ressources et cycle d’éco conception
Plutôt que d'imprimer des dizaines de prototypes inutiles, nous avons privilégié la simulation numérique sur Onshape. Chaque pièce a été pensée pour minimiser le taux de remplissage  lors de l'impression 3D tout en conservant une rigidité structurelle suffisante pour les chocs en combat. Cette approche nous a permis de réduire notre consommation de filament PLA et de limiter les déchets plastiques. Pour le robot de test que nous devions fabriquer, nous avons utilisé des pièces que nos concurrents avaient jetées. 


3.2. Tests de performance 
Nous avons soumis les servomoteurs à des cycles de marche pour mesurer leur comportement et leur réactivité. Ces tests ont permis d'affiner les angles de rotation dans le code afin d'optimiser la vitesse de déplacement tout en préservant l'intégrité des composants.Nous avons testé la répartition des masses. L'ajout des bras articulés a été validé par des tests de poussée où nous avons pu observer comment le robot utilisait ces points d'appui pour éviter le basculement arrière .
Conclusion
Le projet Otto-MKS a représenté bien plus qu’un simple exercice technique ; il a été une véritable immersion dans le cycle complet de conception d'un produit, de l'idée initiale à sa réalisation concrète. En transformant une base open-source standard en une version unique, inspirée par l'univers de Wall-E, notre équipe a su relever le défi de concilier esthétique, robustesse mécanique et performance logicielle.Cette aventure nous a permis de consolider des compétences essentielles. Au-delà des acquis techniques, ce qui restera comme notre meilleur réussite sur ce projet est l'esprit de collaboration qui a animé notre groupe. Nous sommes fiers de notre robot et des modifications que nous lui avons apportées. 
