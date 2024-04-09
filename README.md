# Melanoma Detection using custom Convolutional Neural Network Case Study
- To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin   cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.


## Table of Contents
* [General Info](#general-information)
* [Conclusions](#conclusions)
* [Technologies Used](#technologies-used)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- This assignment is to build a multiclass classification model using a custom convolutional neural network in TensorFlow.

**Busiesss Problem Statement:**
- To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

**Dataset Used:**
- The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

    - Actinic keratosis
    - Basal cell carcinoma
    - Dermatofibroma
    - Melanoma
    - Nevus
    - Pigmented benign keratosis
    - Seborrheic keratosis
    - Squamous cell carcinoma
    - Vascular lesion

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Initial model turned out to be highly overfitting. Training accuracy and validation accuracy were off by large margins. The model achieved only around 55% accuracy on the validation set.
- Then we used augmentation strategy and drop out. As a result, overfitting was fairly reduced and training accuracy and validation accuracy were closely aligned. However, the overall model accuracy was still around 50%.
- Finally, we identified class imbalance in the data. The class rebalance helped in reducing overfititng of the data and thus the loss is beng reduced. Training accuracy and validation accuracy is closely aligned now.
- Class rebalancing using Augmentor helped marginally in bringing the validation accuracy closer to training accuracy. But the overall model accuracy increased to a great extent.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- library - version 1.0
- Jupyter Notebook
- tensorFlow v2.11.0
- keras v3.1.1
- PIL v9.4.0
- numpy - 1.24.3
- python - 3.11.4
- pandas - 1.5.3
- plotly - 5.17.0
- matplotlib - 3.7.1

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was based on [Convolutional Neural Network Assignment from Upgrad](https://learn.upgrad.com/course/4705/segment/47956/289239/880085/4398556).


## Contact
Created by [https://github.com/kallalnath] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->