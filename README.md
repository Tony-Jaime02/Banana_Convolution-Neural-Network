# Banana Convolutional Neural Network

This project contains the code for a convolutional neural network with Tensorflow that classifies images of bananas into three different categories:
    
    ->Fresh
    ->Rotten
    ->Unripe

The dataset used for training, validation, and testing consists of more than 400 images. To enhance the dataset and improve model performance, image data augmentation techniques were applied. The following augmentation metrics were used:

    ->Rescale
    ->Brightness
    ->Rotation
    ->Zoom
    ->Horizontal flip
    ->Vertical flip

By incorporating data augmentation techniques and using a combination of multiple datasets, 
the model aims to improve its ability to classify bananas accurately.

The images were collected from the following sources:

    ->https://www.sciencedirect.com/science/article/pii/S2352340922007594?ref=pdf_download&fr=RR-2&rr=7c994fbbc8004865
    ->https://www.kaggle.com/datasets/sriramr/fruits-fresh-and-rotten-for-classification
    ->https://github.com/giovannipcarvalho/banana-ripeness-classification
    ->https://data.mendeley.com/datasets/y3649cmgg6
