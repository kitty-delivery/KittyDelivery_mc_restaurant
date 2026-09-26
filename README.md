<div align="center">
  <img src=".github/assets/banner.png" alt="KittyDelivery Restaurant Service banner" width="100%" />

  <h1>KittyDelivery, Restaurant Service</h1>

  <p>Restaurant microservice of the KittyDelivery project, in Node.js / Express with MongoDB, containerized.</p>

  <p>
    <img src="https://img.shields.io/github/last-commit/kitty-delivery/KittyDelivery_mc_restaurant" alt="last update" />
    <img src="https://img.shields.io/badge/stack-Node.js%20%2F%20Express%20%2F%20MongoDB-green" alt="stack" />
  </p>
</div>

<br />

## :notebook_with_decorative_cover: Table of Contents

- [About the Project](#star2-about-the-project)
  * [Tech Stack](#space_invader-tech-stack)
- [Installation](#gear-installation)
- [Related Repositories](#link-related-repositories)
- [Contact](#handshake-contact)

## :star2: About the Project

This repository is part of the [KittyDelivery](https://github.com/kitty-delivery/KittyDelivery) microservices architecture, a food delivery application built as a student project. This service is meant to manage restaurants and relies on MongoDB through Mongoose. It is containerized with Docker.

Its entry point (`index.js`, declared as `main` in `package.json`) is missing from the repository and no `start` script is defined: the Docker image builds but the container does not start as is.

### :space_invader: Tech Stack

<details>
  <summary>Server</summary>
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

## :gear: Installation

With Docker:

```bash
docker compose up --build
```

The service listens on port 3010.

Without Docker:

```bash
npm install
npm start
```

## :link: Related Repositories

This microservice is part of the [KittyDelivery](https://github.com/kitty-delivery/KittyDelivery) project, alongside [KittyDelivery_core](https://github.com/kitty-delivery/KittyDelivery_core), [KittyDelivery_API](https://github.com/kitty-delivery/KittyDelivery_API), [KittyDelivery_mc_user](https://github.com/kitty-delivery/KittyDelivery_mc_user), [KittyDelivery_mc_auth](https://github.com/kitty-delivery/KittyDelivery_mc_auth), [KittyDelivery_mc_component](https://github.com/kitty-delivery/KittyDelivery_mc_component), [KittyDelivery_mc_notif](https://github.com/kitty-delivery/KittyDelivery_mc_notif), [KittyDelivery_mc_article](https://github.com/kitty-delivery/KittyDelivery_mc_article), [KittyDelivery_mc_log](https://github.com/kitty-delivery/KittyDelivery_mc_log), [KittyDelivery_mc_menu](https://github.com/kitty-delivery/KittyDelivery_mc_menu) and [KittyDelivery_mc_order](https://github.com/kitty-delivery/KittyDelivery_mc_order).

## :handshake: Contact

Brieuc Dumortier, [LinkedIn](https://www.linkedin.com/in/dumortier-brieuc/), dumortier.contact@gmail.com
