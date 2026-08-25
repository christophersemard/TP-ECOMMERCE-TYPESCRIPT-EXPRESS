<h1 align="center">🛍️ E-commerce TypeScript API</h1>

<p align="center">API REST de gestion de produits, utilisateurs et commandes avec authentification JWT.</p>

<p align="center">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/Express-4-000000?style=flat-square&logo=express&logoColor=white" alt="Express" />
  <img src="https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white" alt="Prisma" />
  <img src="https://img.shields.io/badge/JWT-Authentication-000000?style=flat-square&logo=jsonwebtokens&logoColor=white" alt="JWT" />
</p>

## À propos

Cette API de formation couvre les principaux parcours d'un e-commerce : authentification, catalogue, utilisateurs et commandes. Prisma modélise les relations entre utilisateurs, produits, commandes et lignes de commande.

## Fonctionnalités

- inscription et connexion JWT ;
- validation des entrées ;
- gestion des produits ;
- création et consultation des commandes ;
- mots de passe hachés avec bcrypt ;
- protections Helmet et limitation de requêtes ;
- schéma relationnel Prisma.

## Lancer en local

Prérequis : Node.js et une base compatible avec Prisma.

    npm install
    npx prisma generate
    npm run build
    npm start

Configurer DATABASE_URL et JWT_SECRET dans un fichier .env.local avant le lancement.

## Contexte

Projet de formation conservé comme exemple d'API TypeScript structurée. Les tests automatisés et la configuration de production restent à compléter.

## Auteur

[Christopher Semard](https://github.com/christophersemard)
