# Plant-Disease-Detection-using-CNN
## Overview

This project aims to develop a convolutional neural network (CNN) to predict plant diseases using images of plant leaves. This project can assist in early detection and management of plant diseases, thereby potentially reducing yield losses and contributing to global food security.
## Dataset

The PlantVillage dataset contains over 50,000 expertly curated images of healthy and infected plant leaves. These images are categorized into 38 different classes, each corresponding to a specific plant disease or a healthy state. Some examples of the classes include:

- Apple___Apple_scab
- Blueberry___healthy
- Cherry_(including_sour)___Powdery_mildew
- Corn_(maize)___Cercospora_leaf_spot Gray_leaf_spot
- Grape___Black_rot
- ## Convolutional Neural Network (CNN)

A Convolutional Neural Network (CNN) is a deep learning algorithm that can take in an input image, assign importance to various aspects in the image, and differentiate one image from the other. CNNs are particularly useful for image classification tasks due to their ability to automatically and adaptively learn spatial hierarchies of features from input images.
## Model Development

### Model Architecture

The CNN model used in this project consists of multiple convolutional layers followed by max-pooling layers to reduce the spatial dimensions. The model then uses dense layers to perform the final classification.

### Training and Evaluation

The model is trained on the PlantVillage dataset with a validation split to monitor its performance. The training process involves optimizing the model parameters to minimize the loss function and maximize accuracy.
## Results

After training for 5 epochs, the model achieves a validation accuracy of approximately 95%. This indicates that the model is effective at distinguishing between different plant diseases and healthy states based on leaf images.
## Usage

The trained model can be used to predict the class of new images of plant leaves. This involves preprocessing the images to the required format and using the model to make predictions.
## Conclusion

This project demonstrates the potential of using CNNs for plant disease detection, which can play a crucial role in modern agriculture by enabling early diagnosis and treatment of diseases, ultimately contributing to increased crop yields and food security.
