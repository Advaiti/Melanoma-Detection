# Melanoma-Detection-using-Convolutional-Neural-Network

> This assignment is to build a multiclass classification model using a custom convolutional neural network in TensorFlow.

## Table of Contents
* [Problem Statement](#problem-statement)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Contact](#contact)


## Problem Statement

In this assignment, you will build a multiclass classification model using a custom convolutional neural network in tensorflow. 

####  To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.
The data set contains the following diseases:

1. Actinic keratosis
2. Basal cell carcinoma
3. Dermatofibroma
4. Melanoma
5. Nevus
6. Pigmented benign keratosis
7. Seborrheic keratosis
8. Squamous cell carcinoma
9. Vascular lesion
 
NOTE: You don't have to use any pre-trained model using Transfer learning. All the model building process should be based on a custom model.

#### Project Pipeline
- Data Reading/Data Understanding → Defining the path for train and test images 
- Dataset Creation→ Create train & validation dataset from the train directory with a batch size of 32. Also, make sure you resize your images to 180*180.
- Dataset visualisation → Create a code to visualize one instance of all the nine classes present in the dataset 
- Model Building & training : 
    Create a CNN model, which can accurately detect 9 classes present in the dataset. While building the model rescale images to normalize pixel values between (0,1).
- Choose an appropriate optimiser and loss function for model training
- Train the model for ~20 epochs
- Write your findings after the model fit, see if there is evidence of model overfit or underfit
- Choose an appropriate data augmentation strategy to resolve underfitting/overfitting
**Model Building & training on the augmented data :**
  - Create a CNN model, which can accurately detect 9 classes present in the dataset. While building the model rescale images to normalize pixel values between (0,1).
  - Choose an appropriate optimiser and loss function for model training
  - Train the model for ~20 epochs
  - Write your findings after the model fit, see if the earlier issue is resolved or not?

**Class distribution:**
  - Examine the current class distribution in the training dataset 
  - Which class has the least number of samples?
  - Which classes dominate the data in terms of the proportionate number of samples?
**Handling class imbalances:** 
  - Rectify class imbalances present in the training dataset with Augmentor library.
**Model Building & training on the rectified class imbalance data:**
  - Create a CNN model, which can accurately detect 9 classes present in the dataset. While building the model rescale images to normalize pixel values between (0,1).
  - Choose an appropriate optimiser and loss function for model training
  - Train the model for ~30 epochs
  - Write your findings after the model fit, see if the issues are resolved or not?


## Technologies Used
- tensorFlow v2.18.0

## Conclusions

- The results demonstrate remarkable improvement following the application of dataset augmentation techniques. The model achieved an impressive training accuracy of 0.9582 and a commendable validation accuracy of 0.9236 at 29 epochs, signifying a well-trained and robust model.

- Highlights of the Results:
**Enhanced Generalization:**

The close alignment between training and validation accuracy indicates that the model is generalizing well to unseen data. This reflects the effectiveness of augmentation in reducing overfitting and improving performance.

**Consistent Training Progress:**

The training loss steadily decreased over epochs, confirming that the model optimized its parameters effectively.
Validation loss followed a similar trend, with only minor fluctuations, suggesting stability in the model's generalization capacity.

**Performance Metrics:**

Achieving over 95.8% accuracy on the training set and maintaining 92.4% accuracy on the validation set underscores the success of dataset augmentation in enhancing the model's ability to learn from diverse patterns in the data.

**Positive Outcomes of Dataset Augmentation:**

The use of augmentation has enriched the training process by exposing the model to a wider variety of scenarios, making it more robust to variations in data. This directly contributes to the superior performance observed compared to previous models.

**Conclusion:**
These results highlight the effectiveness of the current approach, showcasing how careful preprocessing and augmentation can significantly boost a model's performance. This paves the way for further fine-tuning or testing on additional datasets to validate its scalability and real-world application.

## Contact
Created by [Chidambaram Ananthakrishnan](https://www.linkedin.com/in/chidambaram-ananthakrishnan/)
