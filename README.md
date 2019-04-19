# This repository contains the scripts and data for Kaggle Competition Plant-Seedlings-Classification

#
1. Jupyter notebooks for Kaggle Plant Seedlings Classification.
2. test folder has sample test images.
3. train folder has sample train images used for each class.
4. validation folder contains the validation images used for training.
5. vgg19_data_augumentation.ipynb is the jupyter notebook that contains the code of the model, training logs, and testing logs. Every step of training is explained in the notebook.
6. gui_script.ipynb should be run to test the model through GUI. 
7. Any image in the test, train, validation and sample_images_for_gui floders can be input to the gui for prediction.
8. The demo of the GUI can be found here https://www.youtube.com/watch?v=ZLuiq2wGC5M 
8. The trained neural network model is available at https://drive.google.com/file/d/1wRwZpCpeieRUx-7zwpmAKT6kdmIABmBe/view?usp=sharing .
8. The text files have the loss and accuracy metrics of the model while training for each epoch
10. keras_aug_4_15_12.csv file contains the predictions made by the neural network for test data. This file is submitted to kaggle to find the test accuracy. The best test accuracy achieved is 94.71%
