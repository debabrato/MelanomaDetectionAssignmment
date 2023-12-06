# Melanoma Detection Assignment



## Table of Contents
* [General Info](#general-information)
* [Conclusions](#conclusions)


## General Information
Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

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

It was concluded that the data was not balanced. Thus augmentor was used in order to augment the data.
After adding 500 additional images in each of the 9 classes, the CNN model was executed again and it showed a good fit.
The training accuracy was 94% and validation accuracy was 82%.

## Contact
Created by [@debabrato] - feel free to contact me!

