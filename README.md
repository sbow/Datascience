# Datascience POC's

No models / data, datascience repo

## python environment
- pyenv & pipenv

## Getting started

```
git clone https://github.com/sbow/Datascience
cd /path/to/this/project

pyenv install -v 3.10
pipenv --python 3.10
pipenv install --dev
```

## Looking around
- azure_datafactory
  - json files for developing ADF pipelines
- src
  - python files
- notebooks
  - jupyter notebooks
- docker-compose.yml
  - 

## Required enviornment variables
- localstack : S3 storage emulation for development
  - DATA_DIR=/path/to/local/directory localstack start