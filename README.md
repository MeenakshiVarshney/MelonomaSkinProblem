# Project Name
> In this assignment, you will build a multiclass classification model using a custom convolutional neural network in tensorflow.

Problem statement: To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.
The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant. The data set contains the following diseases:

Actinic keratosis
Basal cell carcinoma
Dermatofibroma
Melanoma
Nevus
Pigmented benign keratosis
Seborrheic keratosis
Squamous cell carcinoma
Vascular lesion


## Table of Contents
* [General Info](#general-information)
* [Approach]
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)



## General Information
Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

Objective
To build a CNN based model which can accurately detect melanoma.

## Approach
Following is the step-by-step approach followed to solve the given problem statement:

Data Understanding
Building Simple Model (Model I)
Building Model with Augment layer (Model II)
Using Augmentor (for increase dataset)
Building Model with Augmentor dataset (Model III)


## Conclusions
- After Model I
1.   We can clearly observe a drastic difference between Traning and Validation Accuracy, which indicates that the model has overfitted 
2.  Also we can observe that the validation accuracy the model has achieved is *51* % Overall we need to apply techniques like Data Augmentation and Dropout to handle the overfitting issue of the model
- After Model II
 As we can see that now the Training and Validation accuracy are almost in the same level and the highest accuracy achieved is around 61% , this shows the impact of how performing Data Augmentation can improve the model performance But we can still try to increase the accuracy of the model
- We can see class imbalance, used Augmentor to add more images
- After Model III
We can infer that the Model is fit with a good enough accuracy for both Train and Validation Data of max accuracy around 80% Rectifying the Class Imbalance and performing Data augumentation on the dataset has resulted in a model with higher accuracy and overcoming overfitting This is a good model to be used to predict Skin Cancer using CNN



## Technologies Used
Python (ver 3.12.7)
NumPy (ver 1.26.4)
Pandas (ver 2.2.2)
MatplotLib (ver 3.9.2)
Tensorflow (ver 2.18.0)
Keras (ver 3.8.0)
Augmentor (ver 0.2.12)

## Acknowledgements
Give credit here.
- This project was inspired by CNN Study material & base code file provided for the case study


## Contact
Created by @Meenakshi1112- feel free to contact me!

<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->


