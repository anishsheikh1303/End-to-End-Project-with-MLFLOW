# End-to-End-Project-with-MLFLOW

## Workflows

1. Update config.yaml
2. Update schema.yaml
3. Update params.yaml
4. Update the entity
5. Update the configuration manager in src config
6. Update the components
7. Update the pipeline
8. Update the main.py
9. Update the app.py

# How to run?

### STEPS:

Clone the repository

```bash
https://github.com/anishsheikh1303/End-to-End-Project-with-MLFLOW
```

### STEP 01 - Create a conda environment after opening the repository

```bash
conda create -p venv python==3.9 -y
```

```bash
conda activate venv/
```

### STEP 02 - install the requirements
```bash
pip install -r requirements.txt
```

```bash
# Finally run the following command
python app.py
```

Now,
```bash
open up you local host and port
```

## MLFlow

[Documentation](https://mlflow.org/docs/lates/index.html)

##### cmd
- mlflow ui

### dagshub
[dagshub](https://dagshub.com/)

MLFLOW_TRACKING_URI=https://dagshub.com/anishsheikh1303/End-to-End-Project-with-MLFLOW.mlflow \
MLFLOW_TRACKING_USERNAME=anishsheikh1303 \
MLFLOW_TRACKING_PASSWORD=286764511ed0bf1352a970cd4d290e45491e56c4 \
python script.py

Run this to export as env variables:

```bash
export MLFLOW_TRACKING_URI=https://dagshub.com/anishsheikh1303/End-to-End-Project-with-MLFLOW.mlflow

export MLFLOW_TRACKING_USERNAME=anishsheikh1303

export MLFLOW_TRACKING_PASSWORD=286764511ed0bf1352a970cd4d290e45491e56c4
```