# Projet FIL ROUGE

## 1. Description 
Ce projet met en place un pipeline ETL (Extract, Transform, Load) conteneurisé avec Docker, stockant les données sur MinIO et utilisant Python pour automatiser le traitement des données.

## 2. Fonctionnalités
- Extraction depuis différents formats : CSV, Excel, API
- Transformation : nettoyage, enrichissement
- Chargement : stockage local et MinIO (compatible S3)

## 3. Arborescence du projet
```text
projet_etl/
│
├── docker-compose.yml
├── Dockerfile
├── config/
├── src/
├── tests/
├── data/
├── logs/
└── requirements.txt
