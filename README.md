# Data Science EDA project

Exploratory Data Analysis project within the NeueFische Data Science Bootcamp.

The task was to download a dataset about King County house sales from the Postgre Database and analyze the contents.
This includes getting an overview of the data prior to cleaning it. First, general hypotheses / questions to the dataset were answered through visualization by plotting. Going deeper into specific questions, a stakeholder was chosen from the list in the assignment file and the data analysis was subsequently tailored to their individual needs. The whole process is documented in the Jupyter Notebook CB-EDA, as well as in a final presentation which contains the generated insights.

The necessary libraries and packages to set up the environment are found in the requirements file.

## Requirements

- pyenv
- python==3.9.8

### Environment

This repo contains a requirements.txt file with a list of all the packages and dependencies that are needed. Prior to installing the environment, postgresql needs to be downloaded.

```bash
brew update
brew install postgresql
```

The following commands will install the virtual environment:

```
pyenv local 3.9.8
python -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
pip install -r requirements.txt
```