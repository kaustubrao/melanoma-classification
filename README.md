# Melanoma Classification

The purpose of this project is to build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC)
- A CNN model is trained to classify 9 different classes of oncological diseases based on their images
- Due to smaller number of samples, augmentation strategies have to be applied, and care should be taken to prevent overfitting
- Imbalanced classes also need to be treated (some classes have very few samples)

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Dropout will help with the overfitting problem
- Added augmented images to increase the number of samples will also lead to less overfitting
- Augmenting images in a way that reduces class imbalance will greatly improve both the performance on training data as well as validation (less overfitting)

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Tensorflow
- Keras
- Numpy
- Pandas
- Matplotlib
- Augmentor

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Contact
Created by [@githubusername] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->