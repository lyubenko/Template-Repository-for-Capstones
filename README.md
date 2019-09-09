# Stock_Ranking_with_Alternative_Data-
This repository houses Stock Ranking Modeling Pipeline developed by CMU students.

# Notes to Students:

Due to confidentiality concerns, please ensure that all the code EXCLUDES log-in credentials. Instead, your code should contain the fields in which user is able to enter his own credentials, i.e.

myconn <- odbcConnect("enter_database", uid="enter_you_user_name", pwd="enter_your_password")

Also, DO NOT put any data on GitHub. All the data will be housed in the SQL Database to which you will be given read-only  access

 
# Basic Structure of this Repository:

## README.md                <- Front page of the project. This will be updated with major points/findings of the Project
│
## models                   <- This folder houses model predictions/summaries 
│                        
│
## notebooks                <- This folder houses R Markdown Files or Jupiter Notebooks documenting in detail student's code
│                         
│
## reports                  <- Reports folder contains report in pdf, LaTeX or HTML format
│   └── figures              <- Generated figures.
│
## requirements.txt         <- File for reproducing the environment. For Python
│                                `$ pip freeze > requirements.txt`
│
## code                     <- This folder houses all the code
    ├── main.R               <- Main File to Execute the Pipeline. 
    │
    ├── custom_functions.R   <- Various custom functions written by the students.
    │
    ├── data                 <- Scripts to download or generate data.
    │   └── make_dataset.py
    │
    ├── screening            <- Scripts written for factor screening are housed in this folder 
    │   │                
    │   └── continuous.R
    │
    ├── models               <- Scripts to train models and then use
    │   │                       trained models to make predictions.
    │   │                 
    │   ├── predict_model.py
    │   └── train_model.py
    │
    └── visualizations        <- Scripts to create visualizations.            
        └── viz.py
        
 References:
 Vishnu and the following website 
 https://medium.com/@rrfd/cookiecutter-data-science-organize-your-projects-atom-and-jupyter-2be7862f487e
