---
layout: default
title: Préparation des Matériaux
parent: Etapes de fabrication
nav_order: 1
---

# Préparation des Matériaux

Cette section décrit la première étape du processus de fabrication : la préparation des matériaux.

## Liste des Matériaux

| **Microcontrôleur ESP32** | 1 | Carte principale avec Wi-Fi/Bluetooth intégrés pour le pilotage à distance. |
| **Shield d'extension ESP32** | 1 | Carte d'extension pour faciliter le branchement des servomoteurs et capteurs. | 
| **Servomoteurs SG90 (9g)** | 6 | 4 pour les jambes/pieds + 2 pour l'articulation des bras Wall-E. | 
| **Capteur Ultrason HC-SR04** | 1 | Capteur de distance (les yeux) pour la détection d'obstacles et le mode Sumo. | 
| **Batterie LiPo 3.7V** | 1 | Source d'énergie principale du robot. | 
| **Module de charge USB-C** | 1 | Pour la recharge sécurisée de la batterie (souvent intégré au shield). |
| **Interrupteur ON/OFF** | 1 | Bouton de coupure générale (placé sous la tête protectrice). | 
| **Câbles de prototypage (Dupont)** | 1 lot | Fils Femelle-Femelle pour interconnecter les modules si nécessaire. |
| **Vis de fixation du moteur** | 12 | Diamètre : 2mm Longueur : 8 ou 9 mm .Vous en utilisez 2 par servomoteur. |
| **Vis de l'axe central** | 6 | Diamètre : 2mm Longueur : 4 ou 5 mm .Vous en utilisez 1 par servomoteur. | 

-------------------------------------------------------------------------------------------------------------------------------------------------------------------

Toutes ces pièces ont été modélisées par nos soins sur **Onshape** afin de respecter la charte graphique de Wall-E et d'optimiser la résistance mécanique.

*   **[ ] 1 x Tête personnalisée (Style Wall-E) :** Intègre les logements pour le capteur ultrason et protège l'interrupteur.
*   **[ ] 1 x Corps inférieur (Châssis) :** Reçoit la carte ESP32, la batterie et soutient les servomoteurs de hanche.
*   **[ ] 2 x Jambes :** Pièces de liaison entre les hanches et les pieds.
*   **[ ] 2 x Pieds larges :** Dessinés pour maximiser la surface de contact au sol et améliorer la stabilité.
*   **[ ] 2 x Bras articulés :** Conçus pour servir de leviers anti-basculement lors des combats de sumo.

# Procédure de Préparation

## Étape 1 : Exportation des modèles CAO depuis Onshape

1. Ouvrez votre projet sur **Onshape**.
2. Faites un clic droit sur chaque pièce de la structure (Corps inférieur, Tête Wall-E, Bras articulés, Yeux protecteurs, Jambes et Pieds).
3. Sélectionnez **Exporter** et choisissez le format **STL** ou **3MF** avec une résolution "Fine" pour garantir la précision des emboîtements.

---

## Étape 2 : Configuration du Slicer (Trancheur) & Éco-conception

Pour l'impression, nous utilisons du filament **PLA**. Afin de réduire l'empreinte écologique du projet, suivez scrupuleusement ces configurations dans votre logiciel de tranchage (Cura, PrusaSlicer, etc.) :

| Paramètre | Valeur recommandée | Justification technique |
| :--- | :--- | :--- |
| **Hauteur de couche** | `0.2 mm` | Excellent compromis entre qualité visuelle et temps d'impression. |
| **Remplissage (*Infill*)** | `15%` à `20%` maximum | Suffisant pour la solidité sans surcharger le châssis en plastique. |
| **Motif de remplissage** | `Gyoïde` ou `Grille` | Offre une excellente résistance mécanique multidirectionnelle pour les chocs (Sumo). |
| **Parois (*Wall Line Count*)**| `3 lignes` | Renforce la coque extérieure de la structure face aux impacts. |

> 🍃 **Note d'éco-conception :** L'utilisation de la simulation numérique sur Onshape nous a permis d'éliminer les structures de support superflues sur plusieurs pièces, économisant ainsi de la matière et du temps de post-traitement.

---



## Conseils de Sécurité

- Portez toujours l'équipement de protection individuelle.
- Suivez les instructions de sécurité des outils utilisés.

---

Une fois cette étape terminée, passez à l'[Assemblage](/assemblage).
