⚈Introduction
This project aims to build an efficient and accurate COVID Detection System (CDS) using transfer learning to classify X-ray images of patients into two classes:
normal and COVID-19 positive cases. 
The system will aid healthcare professionals in making quicker and   more accurate decisions for potential cases of COVID-19 using X-ray images.

●Problem Statement
The primary goal of this project is to minimize false predictions while accurately identifying COVID-19 positive cases through X-ray images.

⚈Proposed Solution
Our solution involves using transfer learning, where we leverage pre-trained deep learning models to achieve accurate COVID-19 detection from X-ray images.

⚈Tech Stack used
Python
FastAPI
Docker
GitHub Action
Airflow

⚈Infrastructure Required
AWS S3: Used for storing datasets and model artifacts.
AWS ECR: Container registry to store Docker images.
AWS EC2: Virtual server for deploying the FastAPI application.
Git: Version control system for collaborative development


14/09/2025 - Initialize GitHub repository for the project

18/09/2025 -  initialize project with directory and file structure


19/09/2025 -  initialize project with core files and configuration

Added initial setup including:
- main.py as entry point
- requirements.txt for dependencies
- setup.py for packaging
- start.sh for startup script
- Dockerfile and docker-compose.yml for containerization
- s3_setup.py for S3 integration

21/09/2025           
 Add dataset and install required packages
- Located and tested dataset
- Installed dependencies: os, shutil, random, numpy, pandas, cv2, skimage, matplotlib, seaborn
- Verified dataset execution with initial scripts


23/09/2025 add dataset loading functionality
- Implemented dataset loading in project
- Prepared for preprocessing and further analysis.




