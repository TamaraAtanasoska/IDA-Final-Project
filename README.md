# Identifying interested customers from insurance data - Final IDA&ML I project SoSe 2021
This repository contains the final project for the  "Intelligent Data Analysis and Machine Learning I" module part of the [Cognitive Systems](https://www.ling.uni-potsdam.de/cogsys/) program at the [Univeristy of Potsdam](https://www.uni-potsdam.de/en/university-of-potsdam). 

The aim of the project is to find the profiles of customers that would be interesting in obtaining caravan insurance. The data contains 86 different categories of information about the customers. 

The data and goals of the projects were taken from a list proposed by the course administrators. The project was submitted in SoSe 2022. 

The whole project is contained [in this notebook for the time being](project.ipynb).
See the presentaton with a summary [here](https://github.com/TamaraAtanasoska/IDA-Final-Project/blob/main/Insurance%20sales%20leads%20data%20analysis.pdf).

## Setup and usage

### Environment recreation 

In the folder ```setup/``` you can find the respective environment replication and package requirements files. There are two options:

1. You can run ```pip install -r setup/requirements.txt``` to install the necessary packages in your existing environment.

2. If you are using [conda](https://conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html) to manage your virtual environments, you can replicate and activate the full exact environment with the following commands:

   ```
   conda env create --name <name> --file setup/conda.yml
   conda activate <name>
   ```
