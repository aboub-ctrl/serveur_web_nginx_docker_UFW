# Local Nginx Web Server with Docker and UFW

## Description
Ce projet présente la mise en place d’un serveur web Nginx exécuté dans un
conteneur Docker sur un environnement local (PC personnel), avec une
sécurisation basique à l’aide du pare-feu UFW.

## Objectifs du projet
- Comprendre le fonctionnement des conteneurs Docker
- Lancer un serveur web Nginx sans installation manuelle
- Appliquer des règles de filtrage réseau avec UFW
- Tester un environnement web local sécurisé

## Environnement de travail
- Système : Ubuntu (local)
- Conteneurisation : Docker, Docker Compose
- Serveur web : Nginx
- Sécurité : UFW (Uncomplicated Firewall)

## Architecture (simplifiée)
Utilisateur → Navigateur → Docker (conteneur Nginx) → UFW → Système hôte

## Mise en route
```bash
docker compose up -d
