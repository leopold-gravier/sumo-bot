# Sumobot

L'[association ESIEESPACE](https://esieespace.fr) met à disposition ce dépôt Github afin de fournir une base de code complète pour le robot Sumobot conçu par l'association. Vous y retrouverez plusieurs exemples de code commentés pour apprendre à manipuler le robot et ses différents capteurs.

Ce fichier à pour but de vous expliquer sur quelle base technique est construit le robot ainsi que de vous expliquer comment le programmer.

## Base technique

Le kit Sumobot est composé de deux parties importantes:
- **le PCB** où sont soudés les différents composants
- **la carte Arduino Nano** qui est le microcontrôleur

> **Qu'est ce qu'un PCB ?** Un circuit imprimé (ou PCB de l'anglais *printed circuit board/) est un support, en général une plaque, permettant de maintenir et de relier électriquement un ensemble de composants électroniques entre eux, dans le but de réaliser un circuit électronique complexe. ![Un exemple de circuit intégré](https://upload.wikimedia.org/wikipedia/commons/6/6c/Aurora_2ch_mixer_board_arrived_%282009-07-28_11.20.55_by_c-g.%29.jpg)

> **Qu'est ce qu'un microcontrôleur ?** Un microcontrôleur est un circuit intégré qui rassemble les éléments essentiels d'un ordinateur: processeur, mémoires, unités périphériques et interfaces d'entrées-sorties. Arduino est la marque d'une plateforme de référence permettant de créer des objets électroniques interactifs. ![Un microcontrôleur Arduino Nano](https://cdn.shopify.com/s/files/1/0438/4735/2471/products/A000005_01.iso_934x700.jpg?v=1628695103)

Toutes les instructions pour assembler le PCB sont disponible [sur notre site web SUMOBOT](https://sumobot.esieespace.fr).

### La plateforme Arduino


![Arduino  logo](https://upload.wikimedia.org/wikipedia/commons/4/42/Arduino_Uno_logo.png)

Le champs d'application d'une carte Arduino est immense : un robot, une fusée, un panneau d'affichage etc. Tout ces projets sont faisable en utilisant la plateforme Arduino et une [des diverses cartes](https://store.arduino.cc/collections/boards) que propose la fondation Arduino.
Nous vous conseillons de lire [les guides d'introduction à Arduino (en anglais)](https://docs.arduino.cc/learn/) par le site officiel de la plateforme pour les plus téméraires. Le site developpez.com fournit aussi une [introduction compréhensive (en français)](https://nboulaire.developpez.com/tutoriels/Arduino/cours-debuter-programmation-arduino/) pour débuter la programmation Arduino.

Toutes les fonctions que vous serez amenés à utiliser sont documentés sur la page [Language Reference](https://www.arduino.cc/reference/en/).
Nous vous conseillons aussi de lire [les exemples de code inclus pour divers capteurs](https://docs.arduino.cc/built-in-examples/) afin de comprendre en détails leur fonctionnement.

#### Programmation de la carte Arduino Nano

Pour le Sumobot, nous avons fait le choix d'utiliser une carte [Arduino Nano](https://docs.arduino.cc/hardware/nano) notamment pour son prix bas mais aussi pour sa petite taille (18 x 45 mm) s'intégrant parfaitement sur le PCB.

![Arduini Nano Pinout Diagram](https://content.arduino.cc/assets/Pinout-NANO_latest.png)
Vous aurez besoin d'un ordinateur avec un système d'exploitation supporté par l'IDE d'Arduino.
> **Qu'est ce qu'un IDE ?** l’IDE (ou Integrated Development Environment) regroupe un ensemble d’outils spécifiques. Ceux-ci sont dédiés aux programmeurs afin qu’ils puissent optimiser leur temps de travail et améliorer leur productivité

Téléchargez la [dernière version de l'IDE Arduino](https://www.arduino.cc/en/software)
