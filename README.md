## End-to-End Machine Learning Project: House Price Prediction

## Overview

This project demonstrates an end-to-end MLOps pipeline for a house price prediction model using the Ames Housing dataset. The pipeline covers data ingestion, preprocessing, model training, deployment, monitoring, and CI/CD automation.

## Project Structure

. data/
|
._ raw/
|
._ processed/
. src/
|
._ data_ingestion.py
|
._ data*preprocessing.py
|
.* model*training.py
|
.* model*deployment.py
|
.* requirement.txt
|
._ Dockerfile
. notebooks/
|
._ data*exploration.ipynb
|
.* model*training.ipynb
|
.* deployment.ipynb
. .github/
|
._ workflows/
|
._ ci*cd_pipeline.yml
. monitoring/
|
.* prometheus*config.yml
|
.* grafana_dashboard.jason

. docker-compose.yml

. README.md
