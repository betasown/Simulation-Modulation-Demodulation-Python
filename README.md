# ESCAPE NO GAME - LIVRABLE n°4 : Codage du message

## Introduction
Ce projet a pour objectif de simuler la modulation et la démodulation de signaux en utilisant les techniques ASK et FSK. Ce livrable se concentre sur la modulation FSK.

## Membres du Groupe A3
- Krimm Maud
- Bernard Jules
- Zabollone Léo
- Drouhin Louis

## Contenu du Projet
Le projet contient plusieurs sections de code, chacune ayant un rôle spécifique dans le processus de modulation et démodulation FSK.

### Conversion ASCII en Binaire
Le code commence par convertir un message ASCII en binaire.

### Manipulation des Bits
Les bits du message binaire sont manipulés pour préparer la modulation.

### Modulation FSK
Le message binaire est modulé en utilisant la technique FSK, où différentes fréquences sont utilisées pour représenter les bits 0 et 1.

### Démodulation FSK
Le signal modulé est ensuite démodulé pour récupérer le message original.

### Vérification d'Erreurs
Le code inclut également des mécanismes pour vérifier les erreurs de transmission en utilisant des techniques de contrôle de redondance cyclique (CRC).

### Affichage des Résultats
Les résultats de la modulation et de la démodulation sont affichés sous forme de graphiques pour une meilleure compréhension.

## Dépendances
Le projet utilise les bibliothèques suivantes :
- numpy
- matplotlib
- sounddevice

## Exécution du Projet
Pour exécuter le projet, assurez-vous d'avoir installé toutes les dépendances nécessaires. Ensuite, lancez le notebook Jupyter pour voir les résultats de chaque étape du processus de modulation et démodulation.

## Conclusion
Ce projet démontre l'utilisation des techniques de modulation et démodulation FSK pour transmettre des messages binaires. Les mécanismes de vérification d'erreurs assurent l'intégrité des données transmises.
