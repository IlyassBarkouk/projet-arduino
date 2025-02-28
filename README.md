# Projet Arduino - Système de Gestion de Maison Intelligente

Ce projet utilise un Arduino Mega 2560 pour créer un système de gestion de maison intelligente. Il permet de contrôler à distance différents appareils (lumières, ventilateurs, thermostats) à partir d'une interface web.

## 📁 Structure du Projet

Voici la structure des fichiers principaux de l'application :

![structure](https://github.com/user-attachments/assets/5655535d-8bb7-43bd-b946-d899dcb90eb0)

# 📌 Fichiers Clés

arduino.js : Gère les interactions avec l'Arduino.

mqtt-servient.js : Implémente le protocole MQTT pour la communication avec les appareils.

mqtt-serverweb.js : Serveur MQTT permettant l'interaction entre l'interface web et le système.

public/index.html : Interface utilisateur pour le contrôle à distance.

#### ▶️ Pour tester le projet, exécutez les commandes suivante dans des terminals différents :
      --> node mqtt-servient.js
      --> node mqtt-serverweb.js
      --> node arduino.js

# 📸 Documentation Visuelle
![smarthouse1](https://github.com/user-attachments/assets/c69b1787-4885-4da5-a695-f7b7d40a9d35)
![smarthouse2](https://github.com/user-attachments/assets/2aaa48fc-13d4-42ae-8306-1424a96d7067)


Nous avons ajouté une vidéo du fonctionnement complet du système ainsi que trois photos des câbles de la maison intelligente pour une meilleure compréhension.

# 📌 Auteurs

#### 👤 ILYASS BARKOUK📧 Contact : barkoukilyass@gmail.com || ilyassBarkouk@etud.iga.ac.ma

#### 👤 MOUNIR IYA AMINE📧 Contact : pro.mailmounir@gmail.com || mounir.iyaamine@etud.iga.ac.ma

##### 📢 Remarque : Pour toute question ou suggestion, n'hésitez pas à nous contacter !
