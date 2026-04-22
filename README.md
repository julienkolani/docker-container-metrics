# Docker Container Metrics

Notebooks Jupyter pour la collecte et l'analyse automatisée des métriques de performance des conteneurs Docker.

## Fonctionnalités

- Collecte via l'API Docker : CPU, RAM, I/O réseau, I/O disque
- Pipeline complet : collecte → traitement → analyse
- Génération de requêtes de test pour simuler la charge
- Comparaison et synchronisation d'images/configurations YAML

## Stack technique

- Python, Jupyter Notebook
- API Docker, Pandas, CSV

## Installation

```bash
pip install docker pandas jupyter
jupyter notebook
```
