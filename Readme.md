# Docker Symfony Project

Projet Symfony avec Docker sur Windows.

## Prérequis

- Docker Desktop pour Windows
- Git
- PowerShell ou Windows Terminal

## Installation

```bash
# Cloner le projet
git clone https://github.com/Maxime-LEGENTIL/Docker-Symfony.git
cd Docker-Symfony

# Construire les conteneurs
docker-compose build

# Démarrer les services
docker-compose up -d

# Installer Symfony
docker-compose exec php symfony new . --webapp