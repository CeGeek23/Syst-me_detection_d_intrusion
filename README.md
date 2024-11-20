# PRESENTATION

Un système de sécurité domestique combinant détection de mouvement, surveillance vidéo et notifications à distance via application mobile et Telegram.

## 📝 Description

Ce projet propose une solution de sécurité domestique intelligente qui permet :

- La détection de mouvements via capteur PIR
- La surveillance vidéo avec ESP32-CAM
- Les notifications en temps réel sur mobile et Telegram
- Le contrôle à distance du système
- La capture automatique d'images en cas d'intrusion

## 🛠️ Composants Matériels

- ESP32-CAM avec caméra OV2640
- Capteur de mouvement PIR HC-SR501
- Arduino Uno
- Module WEMOS D1 R2 Mini
- Afficheur LCD
- Module RTC (Real Time Clock)
- Buzzer
- Composants électroniques divers (résistances, câbles, etc.)

## 💻 Technologies Utilisées

### Côté Système

- Arduino IDE
- Bibliothèques ESP32
- Protocole MQTT
- API Telegram Bot

### Côté Application Mobile

- Framework mobile (détails dans le code source de l'application)
- Base de données pour le stockage des événements
- API REST pour la communication

## ⚙️ Installation

1. Configuration du matériel

   - Assembler les composants selon les schémas de montage fournis
   - Positionner le module de détection dans la zone à sécuriser

2. Configuration logicielle

   - Installer Arduino IDE
   - Installer les bibliothèques requises
   - Configurer les paramètres WiFi et Telegram
   - Téléverser le code sur les différents composants

3. Installation de l'application mobile
   - Télécharger l'application "Secure Alert"
   - Configurer les paramètres de connexion

## 🚀 Fonctionnalités

- Détection de mouvement jusqu'à 7 mètres
- Capture d'images automatique lors d'une détection
- Streaming vidéo en direct en reseau locaal
- Alertes et control du système via Telegram
- Interface de contrôle intuitive

## 🔐 Sécurité

- Communications cryptées
- Authentification sécurisée
- Stockage sécurisé des données
- Protection contre les accès non autorisés

## 📱 Utilisation

1. Activer le système via l'application ou Telegram
2. Recevoir des notifications en cas de détection
3. Visualiser le flux vidéo en direct
4. Consulter l'historique des événements
5. Gérer les paramètres du système

## 🚧 Perspectives d'Amélioration

- Intégration de l'intelligence artificielle pour la reconnaissance faciale
- Ajout de capteurs supplémentaires (température, fumée, etc.)
- Extension de la couverture WiFi
- La communication et le control complet à distance via un appareil depuis l'applicaton mobile élaboré (le code source se trouve dans le repertoire Security_System_mobile)
- Amélioration de l'autonomie énergétique

## 📄 Licence

MIT License

## 👥 Contribution

Les contributions sont les bienvenues ! N'hésitez pas à soumettre des pull requests.

## Auteurs

    -Tene Fogang : chef de projet
    -Dada Simeu
    -Keugue Wilson
    -Tchakonte Cedrick
    -Tchemi Maxime
