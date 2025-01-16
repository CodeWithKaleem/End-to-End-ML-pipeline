# End-to-End-ML-pipeline

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
https://github.com/CodeWithKaleem/End-to-End-ML-pipeline
```

### STEP 01- Create a conda environment after opening the repository

```bash
conda create -n MLproject python=3.8 -y
```

```bash
conda activate MLproject
```

### STEP 02- install the requirements

```bash
pip install -r requirements.txt
```

```bash
python app.py
```

## Docker Custom image

docker build -t codewithkaleem/wine_quality_prediction:latest .

docker run -p 8080:8080 codewithkaleem/wine_quality_prediction:latest

docker run -d -p 8080:8080 codewithkaleem/wine_quality_prediction:latest

## Push to Docker Hub:

1. docker login
2. docker push codewithkaleem/wine_quality_prediction:latest
