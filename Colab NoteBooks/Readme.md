### Instructions

This folder contains the code for Validation only. Training can also be done in a similar way. Inorder to run the validation of the model, the data has to be preprocessed. A colab file for PreProcessing is also present in this Folder. Minimal Documentation is present in the colab files to run the entire model

Main Colab File - TryPreSumm.ipynb

After cloning the PreSumm Repo in a Colab File, the files present here has to be replaced with the repo files. Files to be Replaced :

Data_loader.py - Path " PreSumm/src/models/data_loader.py "
Model_builder.py - Path " PreSumm/src/models/Model_builder.py "
Trainer_ext.py - Path "PreSumm/src/models/Trainer_ext.py"
Train.py - Path "PreSumm/src/train.py"
Train_extractive.py - Path "PreSumm/src/Train_extractive.py"
Also please mention the directory path for Tensorboard log in trainer.ext at Line 43.
