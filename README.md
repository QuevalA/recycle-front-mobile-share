# reCycle

## Table des matières
- [Introduction](#introduction)
- [Technologies](#technologies)
- [Principales dépendances](#principales-dépendances)
- [Prérequis](#prérequis)
- [Installation](#installation)
- [Contributeurs](#contributeurs)

<br>

## Introduction
**reCycle** est une plateforme permettant aux utilisateurs d’échanger des biens et services sans impliquer d’argent.
De cette manière, ils peuvent donner une seconde vie à des objets dont ils n’ont plus besoin, et ceux qui n’en ont pas à distribuer peuvent toujours s’impliquer en proposant leurs compétences à travers des services.
Cette application est grandement inspirée de Leboncoin et Geev.

Un système de points a été pensé pour équilibrer les échanges, garantissant que plus vous donnez, plus vous êtes en mesure de recevoir. Chaque utilisateur a un profil public qui affiche son expérience dans l’application, incluant sa date d’inscription et le nombre de transactions qu’il a conclu avec succès.

Du point de vue technique, reCycle est basée sur un back-end Symfony servant d’API à des interfaces web en React.js (publique et back-office) et une interface mobile en React native. L'API REST est sécurisée par JWT.

**Ce dépôt contient la partie mobile du projet.**

Partie back end : https://github.com/QuevalA/recycle-back-share
<br>Partie front end : https://github.com/QuevalA/recycle-front-web-share
<br>Partie back office : https://github.com/QuevalA/recycle-back-office-share

<br>

## Technologies
- **React Native** : Version 0.70.6
- **Redux Toolkit** : Version 1.9.5
- **React Navigation** : Version 6.1.1
- **Async Storage** : Version 1.17.11
- **Axios** : Version 1.2.2
- **JWT Decode** : Version 3.1.2

<br>

## Principales dépendances
- **@react-native-async-storage/async-storage** : Version ^1.17.11
- **@react-navigation/native** : Version ^6.1.1
- **@react-navigation/native-stack** : Version ^6.9.7
- **@reduxjs/toolkit** : Version ^1.9.5
- **axios** : Version ^1.2.2
- **jwt-decode** : Version ^3.1.2
- **react** : Version 18.1.0
- **react-native** : Version 0.70.6
- **react-native-dotenv** : Version ^3.4.6
- **react-native-gesture-handler** : Version ^2.8.0
- **react-native-image-picker** : Version ^5.4.0
- **react-native-safe-area-context** : Version ^4.4.1
- **react-native-screens** : Version ^3.18.2
- **react-redux** : Version ^8.0.7
- **redux** : Version ^4.2.1

<br>

## Prérequis
- Node.js installé sur votre machine.
- Un émulateur Android ou un appareil Android connecté pour l'exécution sur Android.
- Un émulateur iOS ou un appareil iOS connecté pour l'exécution sur iOS.

<br>

## Installation
1. Clonez ce dépôt sur votre machine locale.
2. Dans le répertoire du projet, exécutez `npm install` pour installer toutes les dépendances nécessaires.
3. Pour exécuter l'application sur Android, exécutez `npm run android`.
4. Pour exécuter l'application sur iOS, exécutez `npm run ios`.
5. Pour démarrer le serveur de développement, exécutez `npm start`.

<br>

## Contributeurs
Kévin Terrier, Curtis Marty-Jackson, Alexis Carrere, Adam Queval.