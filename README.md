# Melanoma-Detection-using-Convolutional-Neural-Network-Case-Study

> This assignment is to build a multiclass classification model using a custom convolutional neural network in TensorFlow.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* * [Contact](#contact)


## General Information
- What is the background of your project?

To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

- What is the business problem that your project is trying to solve?

A model needs to be built to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.

- What is the dataset that is being used?

The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

- Actinic keratosis
- Basal cell carcinoma
- Dermatofibroma
- Melanoma
- Nevus
- Pigmented benign keratosis
- Seborrheic keratosis
- Squamous cell carcinoma
- Vascular lesion

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
Created by [puspanjalis](https://github.com/puspanjalis) - feel free to contact me!
