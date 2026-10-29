MLOps — Delivery Time Prediction

A collection of eight practicals exploring the machine learning development lifecycle, using delivery-time prediction as the central coursework theme. The repository documents the progression from reproducible experiments and model development to Python packaging, configuration, testing, experiment tracking, API-based model serving, and Docker containerization.

Practical Roadmap

Practical	Focus	Key Concepts
P01	Workbench and reproducibility	Dependencies, experiment outputs, run information
P02	First ML model	Model development and evaluation
P03	Model selection	Comparing models and evaluating generalization
P04	Python package	Reusable modules, training, prediction
P05	Configuration and testing	YAML configuration, validation, automated tests with pytest
P06	Experiment tracking	MLflow runs, model logging, experiment management
P07	Model serving	FastAPI, REST APIs, request validation, model inference
P08	Docker containerization	Dockerfiles, image building, container lifecycle, containerized API testing

See the README inside each practical folder for its specific instructions, implementation details, and learning outcomes.

Repository Structure

mlops-delivery-prediction/
├── README.md
├── .gitignore
└── practicals/
    ├── P01-workbench/
    ├── P02-first-model/
    ├── P03-model-choice/
    ├── P04-package/
    ├── P05-config-tests/
    ├── P06-mlflow/
    ├── P07-serving/
    └── P08-docker/

Each practical folder contains its corresponding notebook and supporting files.

Technologies

* Python — Core programming language for machine learning and service development
* Jupyter Notebook — Interactive practicals and experimentation
* pandas — Data manipulation and analysis
* scikit-learn — Model development, training, and evaluation
* pytest — Automated testing
* YAML — Configuration management
* MLflow — Experiment tracking and model logging
* FastAPI — REST API development and model serving
* Uvicorn — ASGI server for running the API
* Docker — Container image creation and application packaging

These technologies are represented across the practicals; not every practical uses every tool.

Learning Objectives

Through these practicals, the repository explores how to:

* Develop and evaluate machine learning models.
* Compare models and assess generalization.
* Organize reusable machine learning code into Python packages.
* Manage application configuration and validate inputs.
* Write automated tests for machine learning components.
* Track experiments and log models using MLflow.
* Expose trained models through REST APIs.
* Package an ML application and its dependencies into a Docker image.
* Test and manage a containerized prediction service.

Project Theme

Delivery-Time Prediction

Delivery-time prediction serves as the central coursework theme, connecting model development with the engineering practices needed to package, test, serve, and containerize machine learning applications.

Repository Status

The repository contains eight practicals covering key stages of the machine learning development and deployment lifecycle, from initial experimentation through containerized model serving.
