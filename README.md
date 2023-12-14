# Bienvenu sur ESGI International Airport ![Logo](./image/logo.png)


## Description
Vous trouverez dans cette documentation tout les outils et '"tips" pour passer un agréable voyage avec l'application ESGI International Airport :airplane: .

[![GitHub](https://badgen.net/badge/icon/github?icon=github&label)](https://github.com)
[![Discord](https://badgen.net/badge/icon/discord?icon=discord&label)](https://https://discord.com/)
[![Open Source Love svg1](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](https://github.com/ellerbrock/open-source-badges/)

## Table of Contents <!-- omit in toc -->

- [Site pré-requis](#site-pré-requis)
- [Installation](#installation)
- [Features](#features)
- [Liens](#liens)
- [Database](#database)
- [Contact](#contacts)

## Site pré-requis

- [Php](https://www.php.net/downloads)
- [Docker Compose](https://docs.docker.com/compose/install/)
- [Vite.js](https://vitejs.dev/config/) (ex: sudo apt-get install vite)

## Installation

```
git clone https://www.google.com my-app
cd my-app/
cp env-example .env
docker compose up -d
```

For check status run

```
docker compose logs
```
### ou

Les différentes étapes pour l'installation d'ESGI International Airport sont :
1. Exportez le fichier
2. Exécutez la commande  ``git status`` puis ``git add .``
3. Exécutez les logiciels JetBrains :
   * PhpStorm
   * WebStorm

Vous pouvez dès maintenant utiliser l'application.

## Features

- [x] Database.
- [x] Config Service.
- [x] Mailing.
- [x] Admin and User roles.
- [x] File uploads. Support local.
- [x] Tests.
- [x] Docker.

## Liens

- Admin: <http://localhost:8080>
- Maildev: <http://localhost:1080>
- Deploiement: [deploy.md](docs/deploy.md)

# Database

Generate migration

```bash
npm run migration:generate -- src/database/migrations/CreateNameTable
```

Run migration

```bash
npm run migration:run
```

Revert migration

```bash
npm run migration:revert
```

Drop all tables in database

```bash
npm run schema:drop
```

Run seed

```bash
npm run seed:run
```


## Contacts

Contactez notre support à l'adresse suivante : support@esgi-international-airport.fr
**Kevin**, **Catalina** et **Camille** répondrons à toute vos questions.




# ESGI-International-Airport

Pour les branches: 
Main -> sur main on ne fait pas des changements que des hotfix si besoin 
Develop -> tous les changements on le merge sur develop pour tester et apres on les merge sur main
feature/.... -> les branches avec des nouvelles fonctionnalites commencent par feature/...
fix/... -> les branches pour fixer un bug 
hotfix/... -> les branche de main avec MR sur main direct pour des urgences

