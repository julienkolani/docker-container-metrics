# Docker Container Metrics

Jupyter notebooks for automated collection and analysis of Docker container performance data. Uses the Docker API to gather CPU usage, memory consumption, network I/O, and block I/O statistics. Includes data processing, visualization, and utility notebooks for Docker and GitLab automation.

## Features

- Docker container metrics collection via Docker API (CPU, memory, network I/O, block I/O)
- Data processing and analysis pipeline
- Request generation utilities for load testing
- Cron interval validation utility
- Docker Compose file generation for GitLab project groups
- Docker image vs YAML configuration comparison tools

## Tech Stack

- Python 3
- Jupyter Notebook
- Docker SDK for Python
- croniter
- pandas, matplotlib (data processing and visualization)

## Setup

```bash
pip install docker croniter pandas matplotlib jupyter
jupyter notebook
```

## Project Structure

```
script_collecte_donnees.ipynb        # Docker metrics data collection
script_de_traitement_donnees.ipynb   # Data processing and analysis
script_generation_requettes.ipynb    # Request generation utility
test_fonc.ipynb                      # Functional tests
test_reminder_fonc.ipynb             # Reminder function tests
cron_interval_fix.ipynb              # Cron expression interval comparison fix
docker_mount_cache_gen.ipynb         # Docker build cache mount option generator
docker_file_sync.ipynb               # Selective file sync between local/online repos
gitlab_compose_generator.ipynb       # GitLab project update scripts and compose file generator
docker_image_yaml_compare.ipynb      # Docker image vs YAML config comparison
docker_image_yaml_compare_v2.ipynb   # Refined Docker image vs YAML comparison
```
