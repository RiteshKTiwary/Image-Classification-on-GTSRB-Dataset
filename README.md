# Image-Classification-on-GTSRB-Dataset
This Project consist of of python jupyter program which classifies image into one of possible 43 signs of Traffic signals.
Dataset can be downloaded from kaggle website with link - https://www.kaggle.com/datasets/meowmeowmeowmeowmeow/gtsrb-german-traffic-sign


The dataset consists of more than 50,000 images of size 30*30 in total with more than 40 classes.
Steps used in this project:
1. Extract File
2. Partition the dataset for training (31,367 images) and testing (7842 images)
3. Trained with CNN models (Conv2D -> MaxPool2D -> Dropout -> Flatten -> Dense)
4. Optimized using Adam and compiled using categorical-crossentropy
5. Achieved accuracy of .9452


At the end, if you provide a path to any image from test dataset, most of the time it will classify correctly for one of those 43 classes.
