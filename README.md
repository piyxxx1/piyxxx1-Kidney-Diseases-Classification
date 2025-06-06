# Kidney-Disease-Classification-MLflow-DVC


## Workflows

1. Update config.yaml
2. Update secrets.yaml [Optional]
3. Update params.yaml
4. Update the entity
5. Update the configuration manager in src config
6. Update the components
7. Update the pipeline 
8. Update the main.py
9. app.py

# How to run?
### STEPS:

Clone the repository

```bash
https://github.com/piyxxx1/piyxxx1-Kidney-Diseases-Classification.git
```
### STEP 01- Create a conda environment after opening the repository

```bash
conda create -n cnncls python=3.8.18 -y
```

```bash
conda activate cnncls
```


### STEP 02- install the requirements
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






## MLflow

- [Documentation](https://mlflow.org/docs/latest/index.html)

- [MLflow tutorial](https://youtu.be/qdcHHrsXA48?si=bD5vDS60akNphkem)

##### cmd
- mlflow ui

### dagshub
[dagshub](https://dagshub.com/)

MLFLOW_TRACKING_URI=https://dagshub.com/piyxxx1/piyxxx1-Kidney-Diseases-Classification.mlflow \
MLFLOW_TRACKING_USERNAME=piyxxx1 \
MLFLOW_TRACKING_PASSWORD=778e6e53e302dd1978a6cffbb5109ee72f4df2dd \
python script.py

Run this to export as env variables:

```bash

export MLFLOW_TRACKING_URI=https://dagshub.com/piyxxx1/piyxxx1-Kidney-Diseases-Classification.mlflow

export MLFLOW_TRACKING_USERNAME=piyxxx1 

export MLFLOW_TRACKING_PASSWORD=778e6e53e302dd1978a6cffbb5109ee72f4df2dd

```

## About MLflow

MLflow

 - Its Production Grade
 - Trace all of your expriements
 - Logging & taging your model
