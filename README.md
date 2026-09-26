<div align="center">
  <h1>KittyDelivery_mc_restaurant</h1>
  <p>Microservice restaurants du projet KittyDelivery, en Node.js / Express avec MongoDB, conteneurisé.</p>

<p>
  <img src="https://img.shields.io/badge/stack-Node.js%20%2F%20Express%20%2F%20MongoDB-green" alt="stack" />
</p>
</div>

<br />

## Table des matières

- [A propos](#a-propos)
- [Stack technique](#stack-technique)
- [Installation](#installation)
- [Dépôts liés](#depots-lies)
- [Contact](#contact)

## A propos

Ce dépôt fait partie de l'architecture microservices de [KittyDelivery](https://github.com/BaditSad/KittyDelivery), un projet d'application de livraison de repas réalisé dans le cadre de mes études. Ce service est destiné à la gestion des restaurants et s'appuie sur MongoDB via Mongoose. Il est conteneurisé avec Docker.

## Stack technique

<details>
  <summary>Serveur</summary>
  <ul>
    <li><a href="https://expressjs.com/">Express</a></li>
    <li><a href="https://mongoosejs.com/">Mongoose</a> / MongoDB</li>
    <li>cors, body-parser</li>
  </ul>
</details>

<details>
  <summary>Infra</summary>
  <ul>
    <li><a href="https://www.docker.com/">Docker</a> / Docker Compose</li>
  </ul>
</details>

## Installation

Avec Docker :

```bash
docker compose up --build
```

Le service écoute sur le port 3010.

Sans Docker :

```bash
npm install
npm start
```

## Dépôts liés

Ce microservice fait partie du projet [KittyDelivery](https://github.com/BaditSad/KittyDelivery), aux côtés de [KittyDelivery_API](https://github.com/BaditSad/KittyDelivery_API), [KittyDelivery_mc_user](https://github.com/BaditSad/KittyDelivery_mc_user), [KittyDelivery_mc_auth](https://github.com/BaditSad/KittyDelivery_mc_auth), [KittyDelivery_mc_component](https://github.com/BaditSad/KittyDelivery_mc_component), [KittyDelivery_mc_notif](https://github.com/BaditSad/KittyDelivery_mc_notif), [KittyDelivery_mc_article](https://github.com/BaditSad/KittyDelivery_mc_article), [KittyDelivery_mc_log](https://github.com/BaditSad/KittyDelivery_mc_log), [KittyDelivery_mc_menu](https://github.com/BaditSad/KittyDelivery_mc_menu) et [KittyDelivery_mc_order](https://github.com/BaditSad/KittyDelivery_mc_order).

## Contact

Brieuc Dumortier, [LinkedIn](https://www.linkedin.com/in/dumortier-brieuc/), dumortier.contact@gmail.com
