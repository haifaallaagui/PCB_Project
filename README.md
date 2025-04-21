# ⚙️ PBC – Variateur de Vitesse Intelligent pour Moteurs à Courant Continu

Projet de conception et de réalisation d’un **variateur de vitesse intelligent** destiné aux **moteurs à courant continu (DC)**. Ce système permet de contrôler et d’ajuster dynamiquement la vitesse du moteur selon des paramètres précis, en intégrant une logique intelligente d’optimisation et de sécurité.

---

## 🎯 Objectif du projet

- Concevoir un système de contrôle de la vitesse d’un moteur DC.
- Intégrer un algorithme intelligent de régulation (PID ou autre).
- Optimiser la réponse dynamique du moteur (stabilité, précision, rapidité).
- Ajouter une interface utilisateur pour le pilotage et la surveillance.

---

## 🧰 Technologies & Composants

- 🧠 **Microcontrôleur** : Arduino / STM32 / autre (selon implémentation)
- ⚡ **Moteur DC** : moteur à balais avec codeur (si nécessaire)
- 🔌 **Driver de puissance** : L298N, H-bridge, etc.
- 🌀 **Capteurs** : capteur de vitesse ou encodeur optique
- 🖥️ **Interface** : écran LCD / application PC (série ou web)
- 🔄 **Algorithme** : PID / logique floue / régulation adaptative

---

## 🔁 Fonctionnalités principales

- Réglage dynamique de la vitesse via entrée utilisateur
- Lecture en temps réel de la vitesse réelle du moteur
- Correction automatique de l’erreur entre la vitesse cible et la vitesse réelle
- Affichage de l’état du moteur et paramètres de contrôle
- Sécurité : arrêt d’urgence, limitation de la tension ou courant




