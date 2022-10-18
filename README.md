# multiclass classification model using a custom convolutional neural network in TensorFlow to detect Melanoma
To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

## General Information
The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

### The data set contains the following diseases:

1. Actinic keratosis
2. Basal cell carcinoma
3. Dermatofibroma
4. Melanoma
5. Nevus
6. Pigmented benign keratosis
7. Seborrheic keratosis
8. Squamous cell carcinoma
9. Vascular lesion


## Approach Explaination

### Base Model
1. Data Reading/Data Understanding → Defining the path for train and test images 
2. Dataset Creation→ Create train & validation dataset from the train directory with a batch size of 32. Also, make sure you resize your images to 180*180.
3. Dataset visualisation → Create a code to visualize one instance of all the nine classes present in the dataset  
4. Create a CNN model, which can accurately detect 9 classes present in the dataset. While building the model, rescale images to normalize pixel values between (0,1).
5. Adam optimizer and sparse cross entropy loss 
6. Train the model for ~20 epochs
7. Write your findings after the model fit. You must check if there is any evidence of model overfit or underfit.

### Model with augmentation layer
1. Augmentation layer preparation 
2. Model Building & training on the augmented data :
3. Create a CNN model, which can accurately detect 9 classes present in the dataset. While building the model rescale images to normalize pixel values between (0,1).
4. Adam optimizer and sparse cross entropy loss
5. Train the model for ~20 epochs
6. Write your findings after the model fit, see if the earlier issue is resolved or not?

### Model with augmented data
1. Class distribution: Examine the current class distribution in the training dataset.
2. Handling class imbalances: Rectify class imbalances present in the training dataset with Augmentor library.
3. Create a CNN model, which can accurately detect 9 classes present in the dataset. While building the model, rescale images to normalize pixel values between (0,1).
4. Adam optimizer and sparse cross entropy loss
5. Train the model for ~30 epochs
6. Write your findings after the model fit, see if the issues are resolved or not? 

## Technologies Used
- Tensorflow
- keras
- Python
- MatplotLib

## Contact
Created by [@govind430] - feel free to contact me!