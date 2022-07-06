Kaggle competition : Paddy Doctor

General information

the Paddy Doctor competition goal is to classify paddy images into 10 classes (normal + 9 diseases).
The algorithm thtt achieved best accuracy was a pre-trained ResNet152v2 CNN. The 2 last blocks of the model and the top layers (26 layers) 
were unfreezed to fit the paddy images.


Data

Paddy disease dataset on Kaggle website

https://www.kaggle.com/competitions/paddy-disease-classification/data

    Number of categories: 10
    Number of images in train set: 6411
    Number of images in test set: 3469
    Metadata (train.csv) : Image ID, variety, age, disease


Libraries

    Google Colaboratory Notebook
    Python 3.8
    Tnesorflow Keras for CNN implementation
