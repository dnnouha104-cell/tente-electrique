# Tende Électrique Automatique

## Description

Le but de ce projet est de concevoir une tende motorisée automatique qui s'ouvre et se ferme en fonction de la luminosité ambiante.

Le système utilise un capteur LDR pour mesurer la lumière, un servo-moteur pour contrôler le mouvement de la tende et une LED pour indiquer visuellement l'état du système.

## Matériels utilisés

- Arduino Uno
- Capteur LDR (photo-résistance)
- Servo-moteur
- LED
- Résistance pour le capteur LDR
- Fils de connexion
- Alimentation (pile)

## Fonctionnalités principales

### Lecture de la luminosité

Le capteur LDR mesure la quantité de lumière ambiante.

Lorsque l'intensité lumineuse dépasse un certain seuil, le système interprète cela comme un signal pour ouvrir la tende.

### Contrôle du servo-moteur

Si la luminosité est suffisamment élevée, la tende s'ouvre avec le servo-moteur à 90°.

Si la luminosité est faible, la tende se ferme avec le servo-moteur à 0°.

### LED

La LED s'allume pendant le mouvement de la tende, que ce soit lors de l'ouverture ou de la fermeture.

Elle s'éteint lorsque le mouvement est terminé.

### Seuil de luminosité

Le seuil de luminosité est défini dans le programme Arduino et peut être ajusté selon les besoins.

## Technologies utilisées

- Arduino Uno
- Arduino IDE
- Capteur LDR
- Servo-moteur
- Électronique embarquée

## Objectif du projet

Ce projet permet d'automatiser l'ouverture et la fermeture d'une tende en fonction de la luminosité ambiante.
