# To build a CNN based model which can accurately detect melanoma. 

## Table of Contents
1. Importing Skin Cancer Data
2. Load using keras.preprocessing
3. Visualize the data
4. Create the first model
5. Create the model with augmented images
6. Solving the imbalance issue in the dataset
7. Creating the final model, training and then visulasing the results.
8. Conclusions

## General Information
- Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.
- To build a CNN based model which can accurately detect melanoma
- This assignment uses a dataset of about 2357 images of skin cancer types. The dataset contains 9 sub-directories in each train and test subdirectories. The 9 sub-directories contains the images of 9 skin cancer types respectively.

## Conclusions
- Conclusion 1- The first vanilla model does very good job on the training data set, however there is clear indication of overfitting as the validation accuracy just reaches 55%.
- Conclusion 2 - It is tried to resolve the issue by changing the model architecture, however even that does not solve the issue completely.
- Conclusion 3 - Next, the the same model is trained with some random augmented images with some dropouts, which indicates that chnaging the model architecture with some dropouts and using more number of images in each class improve the model.

- Conclusion 4 - Finally, the model created by adding some dropout layers and using the enlarged dataset, which shows a training accuracy above 90% and validation accuracy as high as 62%.


## Technologies Used
pathlib
Path
tensorflow
matplotlib.pyplot
numpy 
pandas
os
PIL
keras
layers
Sequential
