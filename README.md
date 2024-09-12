# Data-Science-Project-Melanoma-Detection-Using-Custom-CNN-for-Multiclass-Classification

Melanoma Detection Using Custom CNN for Multiclass Classification

In this project, we developed a custom Convolutional Neural Network (CNN) model using TensorFlow to tackle the challenge of accurately detecting melanoma, a dangerous form of skin cancer responsible for 75% of skin cancer deaths. Early detection is crucial in improving survival rates, and our model aims to assist dermatologists by evaluating skin lesion images to identify melanoma and other skin conditions. The dataset, sourced from the International Skin Imaging Collaboration (ISIC), includes 2,357 images of malignant and benign skin diseases, classified into nine categories.

Dataset Details:

9 skin disease classes: Actinic keratosis, Basal cell carcinoma, Dermatofibroma, Melanoma, Nevus, Pigmented benign keratosis, Seborrheic keratosis, Squamous cell carcinoma, and Vascular lesion.
The dataset includes images of varying distributions, with melanoma and mole images being slightly dominant.
Project Pipeline:

Data Understanding & Preparation:

Load and split the dataset into training and validation sets.
Resize images to 180x180 pixels and set a batch size of 32 for efficient processing.
Data Visualization:

Visualize sample images from each of the nine classes to gain insights into the dataset.
Model Building:

Design and implement a custom CNN model from scratch to classify images into nine classes.
Normalize image pixel values between 0 and 1.
Select an appropriate optimizer (e.g., Adam) and loss function (e.g., categorical crossentropy) to train the model.
Train the model for approximately 20 epochs and analyze performance to identify underfitting or overfitting issues.
Addressing Overfitting/Underfitting:

Implement data augmentation techniques to improve the model's generalization.
Re-train the model on augmented data for 20 more epochs and evaluate if performance improves.
Class Imbalance Handling:

Analyze class distribution to identify imbalance (e.g., which classes dominate or are underrepresented).
Use the Augmentor library to balance the dataset by generating synthetic data for minority classes.
Model Training on Rectified Data:

Train the model on the balanced dataset for 30 epochs and assess the performance to ensure class imbalance issues are addressed.
The custom CNN built during this project demonstrates how deep learning can contribute to early melanoma detection and potentially reduce the manual workload for dermatologists.
