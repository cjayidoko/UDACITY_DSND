# UDACITY_DSND
Data Science Nanodegree capstone project

# Churn prediction of Sparkify users using Spark

## Table of Contents
1. Installation
2. Project Motivation
3. File Descriptions
4. Results
5. Licensing, Authors, and Acknowledgements

## Installation: 
The codes .py and .ipynb files in this repository run on an anaconda and pyspark installed Python environment. The .py files can run on terminal

## Project Motivation:
The motivation behind this project is develop a supervised predictive model that can predict at any point in time if a user is likely to cancel his subscription of sparkify music streaming service. This is based on important metrics the user has recorded since starting the use of the service

## File Descriptions:
The dataset utilized for this study is a big data obtained and provided by Udacity, and thus not publicly available. The dataset is a .json file with record of events of all users on the sparkify streaming platform. These events can be any point say -liking a song, rolling advert, logging out.
The full size is 12 GB and was anylized on a cluster of computers  resnted from AWS and using spark. The files on this platform include
 - The 'ETL sparkify.ipynb' file is the notebook used in cleaning, preprocessing, and modelling
- The 'ML Pipeline preparation.ipynb' is the python notebook used in building, training, testing, evaluating, and applying the machine learning models.
- The 'process_data2.py' file is the python script that applies all the works done on 'ETL Pipeline' and can take in the raw dataset and return a cleaned SQLite table.
- The 'train_model1.py' file will take in an SQLite table of the cleaned dataset and apply all the works done on ML Pipeline preparation while creating a machine learning model saved as a pickle file.
- The 'run.py' file will take the results of 'process_data2.py', and 'train_model1.py' and produce a web app that one can type in any message during disaster and get a category of the message. 
- These can run on the terminal. 

## Results: 
The findings of this study are in the repository and published on my medium [here](https://medium.com/@idokochijioke)
## Licensing, Authors, Acknowledgements
Many thanks to Figure-8 for making this available to Udacity for training purposes. Special thanks to udacity for the training. Feel free to utilize the contents of this while citing me, udacity, and/or figure-8 accordingly.
