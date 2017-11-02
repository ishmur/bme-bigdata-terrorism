# bme-bigdata-terrorism

This repository contains the assignment #1 of the BME - Big Data course.

# Dataset
The Global Terrorism Database (GTD) has been downloaded from:
https://www.kaggle.com/START-UMD/gtd
To conduct the analysis, create a new directory named 'Data' in the repo root directory and put the .csv file there.

Working structure (hard-coded):
'./Data/globalterrorismdb_0617dist.csv'

Please consult the official GTD website (http://start.umd.edu/gtd/) for information on how the database is structured
(what are the criteria for incident inclusion, variables description, etc.).

# Repository contents:
1) README.md - this file

2) requirements.txt - conda environment used during the analysis. Use the following command to install the env:
$ conda create --name <env> --file requirements.txt,
where <env> is the name of the new enviroment.

3) terrorism_dataset_analysis.ipynb - Jupyter notebook with the analysis. Run it from bash as:
$ jupyter notebook terrorism_dataset_analysis.ipynb

# Required libraries:
pandas
numpy
matplotlib
