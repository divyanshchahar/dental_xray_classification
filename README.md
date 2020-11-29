# Root Canal Classification Challenge

## Objective
The objective of this code is to classify dental x-ray imges as having one ore more than one root.

## Understanding the file structure
This repo contains 5 different kind of files spread across various directories

 - code_testing_cnnx.ipynb: Jupyter Notebook containing the code used for the project
 - dataset_predicting: directory to hold test or validation images. This directory is divided into 2 subdirectories
    - one: This directory will hold all the validation images having one root
    - multiple: This directory will hold all the the validation images having more than one root
-  dataset_training: This directory holds all the the images used for training the model. This directory is divided into 2 subdirectories
    - one: This directory holds all the images having one root
    - multiple: This directory holds all the the validation images having more than one root
- model_config: This directory holds all the saved models from all the code excutions
- model_parameters: This directory contains the checkpoints from all the code executions
- model_log: This directory contains .csv files containg the loss, accuracy, validation loss and validation accuracy data for all the models.

---
The code was run on google collab to reduce run time. All the callbacks, model checkpoints and saved models were originally generated in google drive and are transferred here.

---
All the jupyter notebboks except code_testing_cnn5.ipynb contains the output as well as the code. Due to a slight error this notebook was overwritten. The code, modelecheckpoints, logs and savedmodels associated with this notebook are the same as generated during execution. There might be slight changes however at a later point of time as the notebook will be run again and associated data will be updated soon.

---
Due to github's limitation against uploading large files, model checkpoints are not uploaded rather a link is provided in notepad which will take you directly to the google drive folder containing these files