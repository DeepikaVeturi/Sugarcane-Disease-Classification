# Sugarcane-Leaf-Disease-Classification
A deep learning-based system for classifying diseases in sugarcane crops from images. Utilizes convolutional neural networks (CNNs) to accurately identify and categorize various sugarcane diseases, aiding farmers in effective crop health management.

### Dataset:
Link to Dataset: https://www.kaggle.com/datasets/pungliyavithika/sugarcane-leaf-disease-classification

* It consists of 224 images of healthy and diseased crop leaves
* The dataset has 3 classes - Healthy, Red Rot, Red Rust.
  * Healthy: 75 Images
  * Red Rot: 74 Images
  * Red Rust: 75 Images
    
### Methodology:
Transfer Learning approach was implemented with the help of DenseNet201 architecture. To improve the accuracy of the model, Support Vector Machine (SVM) was incorporated in the final layer of the model. An Accuracy of 98% and a Validation Accuracy of 97.78% was obtained.
