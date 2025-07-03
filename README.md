# 🎨 Plateforme IA Générative Multi-modale pour le Design Industriel

Ce projet propose une application interactive qui exploite l’**IA générative** pour assister les designers dans la conception de produits. Il combine plusieurs modalités d'entrée (texte, esquisse, image) et intègre les contraintes **Design for X (DfX)** dès la phase d’idéation.

---

## 🚀 Objectifs du projet

- Accélérer et enrichir le processus de conception industrielle.
- Intégrer dès le départ des contraintes de **coût**, **qualité**, **durabilité**, etc.
- Offrir un outil interactif où l’**IA agit comme un copilote créatif**.

---

## 🧠 Technologies utilisées

- **Stable Diffusion XL (SDXL)** : pour la génération d’images haute qualité.
- **ControlNet + HED** : pour guider l’IA à partir d’esquisses structurées.
- **Img2Img** : pour générer des variantes à partir d’images de contexte.
- **Gradio** : pour l’interface utilisateur web.
- **Python / Hugging Face Diffusers / OpenCV / PIL**.

---

## 🖼️ Fonctionnalités principales

- **Multi-entrée** : prompt textuel, esquisse (sketch), image de mise en situation.
- **Génération guidée** : respect de la structure et des contraintes utilisateur.
- **Analyse DfX** : évaluation instantanée des concepts (coût, faisabilité, etc.).
- **Assistant IA** : pour modifier les designs de façon itérative en langage naturel.
- **Export** : téléchargement des résultats (ZIP), statistiques et visualisation.

---

## 📦 Installation locale

1. Clonez ce dépôt :
   ```bash
   git clone https://github.com/ton-utilisateur/nom-du-depot.git
   cd nom-du-depot
