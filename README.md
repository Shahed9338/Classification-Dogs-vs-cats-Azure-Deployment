# Classification Dogs vs cats Azure Deployment

## Workflow : 

    1. update config.yaml
    2. update params.yaml
    3. update the entity
    4. update the configuration manager in src config
    5. update the components
    6. update the pipeline
    7. update the main.py
    8. update the app.py

# How to run?

## STEP 01- Clone the repository

```bash
https://github.com/Shahed9338/Classification-Dogs-vs-cats-Azure-Deployment.git
```

## STEP 02- Create a conda environment after opening the repository

```bash
conda create -n dogcat python
```

```bash
source activate dogcat
```
## STEP 03- Install the requirements

```bash
pip install -r requirements.txt
```
## STEP 04- Run the app

```bash
python app.py
```

```bash
Now open up your local host 0.0.0.0:8080
```


# AZURE-CICD-Deployment-with-Github-Actions

## Save pass:

## Run from terminal:

## Deployment Steps:

    1. Build the Docker image of the Source Code
    2. Push the Docker image to Container Registry
    3. Launch the Web App Server in Azure
    4. Pull the Docker image from the container registry to Web App server and run
    