# proyecto_final_mitic

Deployment_XGBoost_Heart_Disease_UCI

Este proyecto implementa un pipeline de entrenamiento e inferencia para un modelo de XGBoost utilizando el dataset de heart.csv que fue utilizado en XGBoots core del modulo XGBOOST / Clasificación utilizando XGBoost (Core)
## Estructura del Proyecto

Project Structure
├── data/                  # Carpeta para datos de entrada (ignorada porGit)
├── models/                # Carpeta para modelos entrenados (ignorada por Git)
├── src/                   # Código fuente
│   ├── data/              # Módulos relacionados con datos
│   │   ├── data_loader.py
│   │   ├── data_splitter.py
│   │   └── data_processor.py
│   └── model/             # Módulos relacionados con el modelo
│       ├── trainer.py
│       ├── evaluator.py
│       └── saver.py
├── tests/                 # Pruebas unitarias
│   ├── conftest.py        # Configuración común para pytest
│   ├── test_data_loader.py
│   ├── test_data_splitter.py
│   ├── test_data_processor.py
│   ├── test_trainer.py
│   ├── test_evaluator.py
│   └── test_saver.py
├── main.py                # Orquestador del pipeline de entrenamiento
├── .gitignore             # Archivo para ignorar archivos y carpetas en Git
├── pyproject.toml         # Configuración de Poetry
└── README.md              # Documentación del proyecto