# 📦 Backend - API Strapi pour Phasmophobia Demo

Ce dépôt contient le **backend** de la démo Phasmophobia, réalisé avec **Strapi**.  
Il a été développé **en solo**, en parallèle du [frontend React TypeScript](https://github.com/Veltako/Phasmophobia-Demo-React-TypeScript), dans le cadre de ma formation **Développeur Web et Web Mobile**.

> ⚠️ Ce backend a été réalisé en **1 mois**, **sans expérience préalable avec Node.js ni Strapi**.  
> Il est **encore en cours de développement**.

---

## 🎯 Objectif

- Créer une **API REST** simple pour alimenter le site vitrine Phasmophobia
- Découvrir le CMS headless **Strapi**
- Manipuler les contenus dynamiques (entités, médias, relations)
- Fournir des données structurées au frontend via requêtes API

---

## 🛠️ Technologies utilisées

- [Strapi](https://strapi.io/) (v4)
- Node.js
- SQLite (par défaut)
- API REST

---

## 🚀 Lancer le projet en local

### Prérequis

- Node.js (v18 recommandé)
- npm ou yarn

### Installation

```bash
# Cloner le dépôt
git clone https://github.com/Veltako/backend.git

# Accéder au dossier
cd backend

# Installer les dépendances
npm install

# Démarrer Strapi (avec création auto des tables si non présentes)
npm run develop
