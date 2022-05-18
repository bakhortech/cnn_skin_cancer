# Project Name
> Melanoma Detection


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

The data set contains the following diseases:

    Actinic keratosis
    Basal cell carcinoma
    Dermatofibroma
    Melanoma
    Nevus
    Pigmented benign keratosis
    Seborrheic keratosis
    Squamous cell carcinoma
    Vascular lesion

## Conclusions
- The model was trained on a  dataset of about 2357 images of skin cancer types.
- 80% of the images were used for training, and 20% for validation.
- The target class lebels were 'actinic keratosis', 'basal cell carcinoma', 'dermatofibroma', 'melanoma', 'nevus', 'pigmented benign keratosis', 'seborrheic keratosis', 'squamous cell carcinoma' and 'vascular lesion'
- The original dataset had class imbalance, so data augmentation was used to add some more images to the training set
- seborrheic keratosis class has the least number of samples
- melanoma and pigmented benign keratosis dominate the data in terms of proportionate number of samples
- Increasing the number of epochs and images has helped reducing overfitting
- Sufficiently good accuracy is observed after increasing epochs and class rebalancing

## Technologies Used
- jupyter notebook - version 6.0.3
- python - version 3.8
- pandas - version 1.0.5
- numpy - version 1.18.5
- matplotlib.pyplot
- tensorflow - version 2.8.0
- tensorflow.keras

## Acknowledgements
This project is created as part of upgrad assignment on linear regression. Thanks to upgrad for inspiring to work on interesting problems.

## Contact
Created by [@bakhortechnologies] - feel free to contact me!
