# Gestion d'un parking avec Arduino

Projet d'informatique industrielle, EMSI Casablanca, année universitaire 2025–2026.

**Auteur : Saifalislam Moubarrad** · Encadrant : Mohamed Lamane.

## Contribution personnelle
Réalisation intégrale du projet par Saifalislam Moubarrad, selon sa déclaration.

## Objectif et éléments documentés
La présentation décrit un parking de cinq places avec détection d'entrée et de sortie, ouverture des barrières, affichage du nombre de places disponibles et signalisation sonore et lumineuse.

Composants décrits : Arduino UNO, deux capteurs HC-SR04, deux servomoteurs, LCD 16×2 I2C, LED rouge et verte, buzzer, photorésistance et bouton de remise à zéro.

Le fonctionnement décrit comprend un seuil de détection de 15 cm, des flags pour éviter le double comptage et un mode jour/nuit avec seuils 350/450 et délai de trois secondes. Ces détails proviennent de la présentation ; le code n'a pas encore été exporté et inspecté.

## Simulation et présentation
[Projet sur Tinkercad](https://www.tinkercad.com/things/aLPXE6tvcu4-gestion-de-parking)

Le lien de partage complet a été fourni pour la préparation du portfolio. L'accès au lien public ci-dessus doit être vérifié avant publication.

[Présentation du projet](docs/Presentation_Parking_Arduino.pptx)

## État du dépôt
Cette version contient la documentation et le lien de simulation. Aucun fichier `.ino` n'a été fourni. Aucun code de remplacement n'a été inventé.

La présentation rapporte huit scénarios réussis : remplissage, refus d'entrée quand le parking est plein, sortie, remise à zéro, passage en mode nuit, retour en mode jour, absence de double comptage et sortie à vide. Ces résultats n'ont pas été reproduits pendant la préparation du dépôt. Aucun déploiement physique n'est confirmé par les fichiers examinés.

## Pour compléter la reproduction
Exporter le programme Arduino depuis Tinkercad, ajouter une capture lisible du circuit et préciser les bibliothèques et le brochage exact d'après ce programme.

## Compétences mobilisées
Programmation embarquée, entrées/sorties numériques et analogiques, capteurs, servomoteurs, affichage I2C et gestion d'états.
