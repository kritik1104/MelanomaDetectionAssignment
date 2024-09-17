# Project Name: Melanoma Detection Assignment
> To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information

## About Dataset
The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

The data set contains the following diseases:

 - Actinic keratosis
 - Basal cell carcinoma
 - Dermatofibroma
 - Melanoma
 - Nevus
 - Pigmented benign keratosis
 - Seborrheic keratosis
 - Squamous cell carcinoma
 - Vascular lesion

## What has been done?
Created a multiclass classification model using a custom convolutional neural network in TensorFlow that predicts the malignant and benign oncological diseases with around 90% accuracy from images.

 - Import necessary dependencies
 - Loaded Data
 - Trained the model, evaludated and assessed its performance to decide the next steps
 - Data Augmentation utility was created which was included in the model architecture and trained it
 - Evaluated the performance of the model having the augmentation layer to decide the subsequent steps
 - Class rebalance using Augmentor
 - Build the final model, assessed its performance and used it to predict the class label on a test image.
 - At each step from the model building to finalization, included comments to better keep track of the insights we observed. 



## Conclusions
The baseline model performed better than the model having the augmentation layer. But, both their performance were not upto the mark and they seemed to underfit. When we increase the number of sanmples using the Augmentor library, we were able to improve the performance of underlying model drastically which became our finalized model exhibiting accuracy of 90% on validation set.


## Technologies Used
- tensorflow - version 2.15.0
- pathlib  - version 1.0.1
- matplotlib - version 3.7.1
- numpy - version 1.25.2
- seaborn - version 0.13.1
- pandas - version 2.0.3
- glob2 - version 0.7
- Pillow - version 5.2.0
- Augmentor - version 0.2.12


## Acknowledgements
- This research was motivated by IIIT-B, for the Machine Learning and Artificial Intelligence course


## Contact
Created by [@KritikMohanty] - feel free to contact me!
