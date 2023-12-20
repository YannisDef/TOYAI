# TOYAI

## Résumé

Nous avons pour but d'aider la population de demain. Nous avons donc fait plusieurs recherche de dataset interessant sur des maladies.
Nous avons fini par trouver un dataset correcte qui contient des photos de rétines normales et malades. Les malades sont atteintes de NC (neovascularisation choroidienne de type 3), DMLA (dégénérescence maculaire liée à l’âge) ou Drusen (déchets provenant de la destruction de cellules forment alors des dépôts jaunâtres qui s'accumulent sous la rétine).

Nous avons pour objectif de faire une IA capable de:
- Dans un premier temps, réussir à différencier les rétines normales et les rétines malades.
- Si le premier cas est une réussite, nous aimerions l'améliorer et lui permettre de différencier les trois maladies différentes: CNV, DME et Drusen.

## Introduction

Peut etre commencer par un "Linear SVC", si celui ci ne fonctionne pas nous pourrons essayer un "Kneighbors Classifier". Si celui ci ne fonctionne pas non plus nous pourrons peut être enfin essayer un "SVC". ????????

## Revue de la littérature

Retinal optical coherence tomography (OCT) is an imaging technique used to capture high-resolution cross sections of the retinas of living patients. Approximately 30 million OCT scans are performed each year, and the analysis and interpretation of these images takes up a significant amount of time (Swanson and Fujimoto, 2017).

## Input-Output-Dataset

Nous avons trouvé sur "Kaggle" un dataset contenant 84 495 images qui sont plus précisement des "Retinal OCT Images (optical coherence tomography)".

Ce dataset est composé de:
- 37 200 images de rétines atteintes de CNV
- 11 300 images de rétines atteintes de DME
- 8 616 images de rétines atteintes de Drusen
- 26 300 images de rétines normales

## Mesures de performance

Quelles mesures utiliserez-vous pour mesurer vos performances ?

Pour savoir si notre IA réalise des résultats satisfaisant, nous allons évaluer notre projet en le comparant avec l'IA d'un autre developpeur qui a utilisé les mêmes données.

Nous l'avons trouvé sur "Kaggle" et voici ces résultats:
```
VGG16 - Test Loss: 0.3146, Test Accuracy: 87.09%
Xception - Test Loss: 0.1303, Test Accuracy: 96.18%
InceptionV3 - Test Loss: 0.1681, Test Accuracy: 94.11%
```
(https://www.kaggle.com/code/siddhantsindhkar/oct-images-xception-transfer-learning)

## Ressources informatiques

Nous avons deux ordinateurs portables:
- Lenovo T590 (i7 8565U, 16GB de RAM, pas de carte graphique)
- HP Probook (i7 10510U, 16GB de RAM, pas de carte graphique)

Si nous pouvons avoir accès à Google Colab, ca ne sera pas de refus.

## Liste de contrôle
