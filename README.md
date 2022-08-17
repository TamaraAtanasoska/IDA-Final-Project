# Identifying interested customers from insurance data - Final IDA&ML I project SoSe 2021
This repository contains the final project for the  "Intelligent Data Analysis and Machine Learning I" module part of the [Cognitive Systems](https://www.ling.uni-potsdam.de/cogsys/) program at the [Univeristy of Potsdam](https://www.uni-potsdam.de/en/university-of-potsdam). 

The aim of the project is to find the profiles of customers that would be interesting in obtaining caravan insurance. The data contains 86 different categories of information about the customers. 

The data and goals of the projects were taken from a list proposed by the course administrators. The project was submitted in SoSe 2022. 

## Setup and usage

### Environment recreation 

In the folder ```setup/``` you can find the respective environment replication and package requirements files. There are two options:

1. You can run ```pip install -r setup/requirements.txt``` to install the necessary packages in your existing environment.

2. If you are using [conda](https://conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html) to manage your virtual environments, you can replicate and activate the full exact environment with the following commands:

   ```
   conda env create --name <name> --file setup/conda.yml
   conda activate <name>
   ```

### How to use

You can pick the data location, the mode, the model and the evaluation method you would like to run. Below is a list of all the commandline options, and their possible variations in the comment line.
```
--data-dir <path-to-data>
--mode <mode> #train, test, compare
--model <model> #dec-tree, lin-class, log-reg, kernel, nn
--ev TODO: pick ev methods
```

TODO: Commands to run and example 

## Analysis

### Algorithms/Models

The course aims to demistify the basic machine learning algorithms, look into their mathematical representations and discuss their usage. I have picked 5 of the algorithms featured in the course. In the respective sections below, I will discuss each of the algorithm/model specifics. These descriptions won't contain how these algorithms/models relate to the project data and the results after running them. This is discussed in detail in the [Discussion](#discussion) section below. 

TODO: Subdivision for any normalisation etc.

### Decision Trees
### Linear classification
### Logistic regression
### Kernel methods
### Neural Networks

### Evaluation

TODO: Listing all evaluation options and comparison groupings.

### Discussion

Discussion specific to the results of the processed data and conclusions 
