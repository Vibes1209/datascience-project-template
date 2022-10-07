# Datascience-Project-Template

## Description
Welcome to this repository!
This repository holds a minimalistic general project structure for a data science project

## Table of Contents
1. [Project Structure](#project-structure)
2. [Installation](#installation)
3. [Run and test the project](#run-and-test-the-project)
4. [Acknowledgements](#acknowledgements)

### Project Structure
| Folder/File | Description |
| --- | --- |
| ./data | This folder contains the raw and processed data  |
| ./docs | This folder contains reference documents, images and other documentary artifacts  |
| ./models | This folder contains local copy of the saved models  |
| ./src | All the relevant source code is contained in this folder  |
| ./tests | Test files to run unit tests and functional tests can go in this folder  |
| .gitignore | Files and folders ignored by git from tracking and versioning  |
| DockerFile | This is the dockerfile used for building docker image of this project  |
| LICENSE | License file indicating the usage permissions and licenses  |
| README.md | This is the Markdown file for explaining the contents of this repository  |
| requirements.txt | List of dependencies and requirements for building and running this project  |

### Installation
1. Build from requirement.txt
```
python3 -m venv venv
source venv/bin/activate
pip install --no-cache-dir -r requirements.txt
```
2. Docker build and run container
```
docker build . -t mydockerimage
docker run mydockerimage
```

### Run and test the project

Run ```python3 src/train.py``` to train the model<br>
Run ```python3 src/predict.py``` to make model prediction<br>
Run ```python3 src/visualize.py``` to vizualize the performance metrics<br>
Run ```pytest tests``` to run testcases for various functions in the project<br>

### Acknowledgements
1. Contributor1
2. Contributor2
3. Reference repository1
4. Reference repository2
