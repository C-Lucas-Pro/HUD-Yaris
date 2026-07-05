# 🚗 Yaris Hybrid HUD (Cyberpunk Edition)

Un affichage tête haute (HUD) DIY pour Toyota Yaris 4 Hybride, basé sur Raspberry Pi et OBDII.
Design inspiré des interfaces Cyberpunk / Sci-Fi.

![Status](https://img.shields.io/badge/Status-Work_In_Progress-yellow)
![Python](https://img.shields.io/badge/Python-3.x-blue)

## 🤖 Développement et Intelligence Artificielle

Ce projet a été entièrement conçu, développé et optimisé en étroite collaboration avec des outils d'**Intelligence Artificielle (IA)**. L'IA a été utilisée comme un partenaire de programmation (Pair Programming) pour :
* La génération, la structuration et le débogage du code Python.
* L'optimisation de la communication avec le protocole OBDII.
* La conception logique de l'interface graphique (Dual Theme).

## ✨ Fonctionnalités

* **Connexion OBDII Bluetooth** : Récupération temps réel (Vitesse, RPM, Charge Moteur, Température Eau).
* **Dual Theme** :
    * 🔴 **Mode ZEN** : Minimaliste pour la conduite de nuit (inspiré Saab Night Panel).
    * 🔵 **Mode CYBER** : Interface complète avec jauges dynamiques et indicateur de batterie hybride.
* **Gestion Jour/Nuit** : Bascule automatique des couleurs via capteur de luminosité.
* **Auto-Start** : Démarrage autonome et résilient sur Raspberry Pi.
* **Miroir HUD** : Inversion automatique de l'affichage pour projection sur pare-brise.

## 🛠️ Matériel Requis

* **Ordinateur** : Raspberry Pi Zero 2 W (ou 3B+).
* **Affichage** : Écran LCD 4.3" HDMI (Waveshare IPS 800x480 recommandé).
* **Data** : Adaptateur OBDII Bluetooth (vLinker MC+ recommandé).
* **Capteur** : Module Photoresistor (KY-018) pour la luminosité.

## 📦 Installation

1. Cloner le projet :
    ```bash
    git clone [https://github.com/C-Lucas-Pro/HUD-yaris.git](https://github.com/C-Lucas-Pro/HUD-yaris.git)
    cd HUD-yaris
    ```

2. Installer les dépendances :
    ```bash
    pip3 install -r requirements.txt
    ```

3. Lancer le HUD :
    ```bash
    python3 main.py
    ```

## 🔧 Configuration

Le fichier `config.py` permet de modifier :
* Les couleurs des thèmes.
* La résolution de l'écran.
* Le mode Simulation (pour tester sans voiture).

## 📸 Aperçu

*(Captures d'écran de l'interface à venir)*

## 📄 Mentions Légales et Copyright

Copyright (c) 2026 C-Lucas-Pro. Tous droits réservés.

Le code source, les designs graphiques et les configurations de ce projet sont la propriété exclusive de son auteur. Toute reproduction, distribution ou modification non autorisée est strictement interdite.
