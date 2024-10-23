# Melanoma Detection Assignment
> The objective is to create a CNN-based model that can accurately detect melanoma, a type of cancer that accounts for 75% of skin cancer deaths if not identified early. This model will analyze images and notify dermatologists of melanoma's presence, greatly minimizing the manual effort involved in diagnosis.

## Table of Contents
- [Melanoma Detection Assignment](#melanoma-detection-assignment)
  - [Table of Contents](#table-of-contents)
  - [General Information](#general-information)
  - [Conclusions](#conclusions)
    - [Technologies Used](#technologies-used)
    - [Libraries and Modules Utilized:](#libraries-and-modules-utilized)
      - [From TensorFlow Keras:](#from-tensorflow-keras)
  - [Acknowledgements](#acknowledgements)
  - [Contact](#contact)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- This assignment involves creating a multiclass classification model using a custom convolutional neural network (CNN) in TensorFlow.
- The objective is to build a CNN-based model that can accurately detect melanoma, a form of cancer that can be fatal if not identified early.
- The model will process medical images and provide alerts to dermatologists about the presence of melanoma, significantly reducing the manual effort in diagnosis.
- The dataset contains 2,357 images of both malignant and benign skin conditions, sourced from the International Skin Imaging Collaboration (ISIC). These images are classified following ISIC's standards, with most subsets balanced, although melanomas and moles are slightly more frequent. The data is divided into training and testing sets.







<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Class rebalancing helped reduce overfitting, leading to a decrease in loss, but it also caused a significant drop in accuracy.
- Initially, the model was trained without data augmentation, resulting in severe overfitting.
- To address this, we introduced dropout and data augmentation, which successfully reduced the overfitting issue.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


### Technologies Used
- Python: Version 3.9.6
### Libraries and Modules Utilized:
- pathlib
- os
- PIL
- tensorflow
- keras
- matplotlib (v3.8.4)
- numpy (v1.26.4)
- pandas (v2.2.1)
#### From TensorFlow Keras:

- layers from tensorflow.keras
- Sequential from tensorflow.keras.models

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project draws inspiration from Course 4 on Convolutional Neural Networks within the Deep Learning specialization.



## Contact
Created by [@rajeevin] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
