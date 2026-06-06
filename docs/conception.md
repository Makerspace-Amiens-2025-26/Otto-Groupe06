---
layout: default
nav_order: 5
title: Conception et prototypage
---

# Conception et prototypage

## 2.2. Les innovations apportées à notre modèle 

Pour passer d’un robot standard à notre propre version  Wall-E, nous avons dû repenser l'architecture globale. 

Plutôt que de surcharger le robot, nous avons opté pour une approche minimaliste et fonctionnelle, où chaque ajout a une utilité précise pour les épreuves de combat.

Plutôt que d'utiliser des fichiers 3D génériques, nous avons modélisé nos propres pièces sur Onshape. L'idée était de garder une ligne épurée tout en intégrant des éléments iconiques du personnage.

#### -La structure : 
Le corps a été entièrement redessiné pour offrir une silhouette robuste et fidèle à l'esthétique du robot Wall-E, avec une attention particulière portée à la gestion des volumes pour ne pas déséquilibrer le robot.

#### -Les yeux :
Ils sont le cœur de l'identité visuelle de notre projet. 

En plus de donner vie au robot, ils ont été pensés pour agir comme une protection naturelle au-dessus de sa tête, bloquant les tentatives d'extinction du bouton principal par les adversaires.

Nous avons ajouté des bras articulés qui ne sont pas là que pour le look .Ces bras ont été conçus pour offrir une amplitude de mouvement efficace.

Ils permettent à la fois de stabiliser le robot lors des déplacements rapides et de servir de levier en combat.

Nous avons misé sur la capacité à soulever l'adversaire et  à se maintenir en position pour ne pas basculer vers l'arrière.

C’est un choix tactique qui nous évite d'ajouter des mécanismes complexes et lourds de type coups de poing, qui risqueraient de nous faire perdre notre centre de gravité.Nous avons volontairement limité les accessoires superflus.

Trop d'ajouts auraient alourdi le châssis et complexifié la programmation. En restant sur une structure simple mais personnalisée, nous garantissons une meilleure réactivité des servomoteurs, ce qui est crucial pour nos épreuves de vitesse et d'agilité.

La peinture de notre robot ajoute un réel plus c’est ce qui fait passer notre robot de simple robot modifier a un super robot.

## 2.3. Programmation logicielle : le cerveau de notre robot

La partie logicielle est le cœur du projet. Pour que notre robot ne soit pas seulement une structure esthétique mais une machine qui puisse se déplacer et faire des actions, nous avons dû travailler sur deux axes majeurs : le pilotage matériel et l'interface de contrôle.

La programmation des déplacements a été un défi technique, surtout lorsqu'on cherche la performance pour les épreuves de vitesse.

Nous avons cherché à pousser les servomoteurs au maximum de leurs capacités. Cela a nécessité des ajustements précis dans le code pour optimiser les cycles de marche et éviter les blocages mécaniques, tout en apprenant à gérer les limites physiques du matériel suite à quelques incidents de parcours.

Le code est conçu pour être fluide, ce qui est crucial lors des combats pour esquiver ou se repositionner rapidement.Pour piloter le robot, nous avons développé une application dédiée qui communique avec l'ESP32.

Plutôt que de surcharger l'écran, nous avons opté pour une interface sobre et intuitive, avec les commandes essentielles accessibles rapidement.

L'application permet de basculer facilement entre les différents comportements du robot, notamment pour le faire se déplacer ou pour le faire attaquer.

Afin de garantir la meilleure stabilité possible, la personne en charge du codage du robot a également pris en main le développement complet de l'application. Cette centralisation a permis une meilleure cohérence entre les commandes envoyées et la réponse mécanique du robot.

En résumé, le logiciel ne sert pas uniquement à faire bouger le robot ; il sert à traduire nos intentions tactiques en actions concrètes sur le terrain. C’est un travail de précision qui continue d'évoluer au fil de nos tests.
