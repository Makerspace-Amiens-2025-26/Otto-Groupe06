---
layout: default
title: Assemblage
parent: Etapes de fabrication
nav_order: 2
---

## Introduction

Ce guide vous accompagne pas à pas dans l'assemblage mécanique et le câblage électronique de votre robot **Otto-MKS**. Avant de commencer, assurez-vous d'avoir imprimé toutes vos pièces en PLA (corps, pieds, jambes, tête et bras inspirés de Wall-E) et de disposer du kit électronique de base (carte ESP32, servomoteurs SG90, batterie et capteurs).

---

## Étape 1 : Calibration des servomoteurs (Important)

> **Attention :** Avant de fixer quoi que ce soit mécaniquement, vous devez impérativement calibrer vos 4 servomoteurs (ou plus si vous utilisez des bras) à leur angle central (**90°**). Si vous ne le faites pas, le robot risque de forcer sur ses axes et de casser les pignons dès l'allumage.

1. Connectez vos servomoteurs à la carte ESP32.
2. Téléversez un code de calibration basique via l'IDE Arduino pour positionner tous les moteurs à 90°.
3. Retirez les palonniers (les petites pièces en plastique blanc) une fois les moteurs positionnés.

---

## Étape 2 : Assemblage des jambes et des pieds

1. **Fixation des moteurs des pieds :** Prenez les deux servomoteurs dédiés à l'inclinaison des pieds et insérez-les dans les emplacements prévus au niveau des jambes.
2. **Fixation des palonniers :** Fixez un palonnier simple sous chaque jambe, orienté perpendiculairement à l'axe de la jambe.
3. **Jonction jambe-pied :** Emboîtez le pied sur le palonnier de la jambe. Assurez-vous que le pied est bien horizontal lorsque le moteur est à 90°. Sécurisez l'axe à l'aide de la petite vis centrale fournie avec le servomoteur.

---

## Étape 3 : Fixation des jambes sur le châssis (Le Corps)

1. **Moteurs des hanches :** Insérez les deux servomoteurs de hanche à l'intérieur du corps inférieur du robot. Fixez-les solidement à l'aide des vis pointues.
2. **Alignement :** Placez le palonnier sur l'axe du moteur de la hanche, puis emboîtez le haut de la jambe. 
3. **Vérification :** À 90°, les jambes doivent être parfaitement droites et parallèles par rapport au corps. Vissez pour bloquer l'ensemble.

---

## Étape 4 : Installation de l'électronique et de la carte ESP32

1. **Passage des câbles :** Faites remonter tous les câbles des servomoteurs (jambes et pieds) à l'intérieur du corps vers le haut.
2. **Mise en place de la carte :** Positionnez la carte d'extension ESP32 dans les glissières ou sur les ergots de fixation situés à l'intérieur du corps.
3. **Connexions des moteurs :** Branchez les câbles des servomoteurs sur les broches correspondantes de la carte (suivez le schéma de câblage de votre code, généralement spécifié pour les broches des hanches et des pieds). Respectez le sens des détrompeurs (GND/Masse sur le fil marron ou noir).

---

## Étape 5 : Assemblage de la tête et des capteurs (Version Wall-E)

1. **Capteur ultrason (les yeux) :** Insérez le module ultrason HC-SR04 à l'avant de la tête (dans notre design personnalisé, ces yeux font également office de bouclier de protection).
2. **Câblage du capteur :** Connectez les 4 fils (VCC, Trig, Echo, GND) du capteur ultrason aux broches dédiées de l'ESP32.
3. **Batterie :** Logez la batterie LiPo rechargeable par USB-C dans son emplacement dédié au centre de la tête ou du corps, en veillant à ce qu'elle ne gêne pas la fermeture de la structure.

---

## Étape 6 : Fermeture

1. Réunissez délicatement la tête et le corps en veillant à ne coincer aucun fil électrique à l'intérieur.
2. Clipsez ou vissez la tête sur le corps selon les tolérances de votre modèle Onshape.

Votre robot **Otto-MKS** est maintenant assemblé et prêt à être programmé pour les épreuves de combat et de course !
