# Melanoma Detection Deep Learning Assignment 

## Objective 

Develop and train a custom Convolutional Neural Network (CNN) model in Tensorflow to accurately classify skin images into nine categories , including melanoma .

This project aims to assist dermatologists by automating the initial screening process for various skin conditions .

## About the Dataset 

The dataset comprises 2357 images of oncological diseases collected from the International Skin Imaging Collaboration (ISIC).

The classes are : 

1. Actinic keratosis
2. Basal cell carcinoma
3. Dermatofibroma
4. Melanoma
5. Nevus
6. Pigmented benign keratosis
7. Seborrheic keratosis
8. Squamous cell carcinoma
9. Vascular lesion

## Project Pipeline 

1. Data Preparation :

* Load and Organize: Read and organize the dataset, defining paths for training and testing images.
* Create Datasets: Generate TensorFlow datasets for training and validation with a batch size of 32. Resize images to 180x180 pixels.
* Visualize: Create visualizations to understand the distribution of images across different classes.

2. Initial Model Development & Training:

* Build CNN: Design and implement a custom CNN architecture in TensorFlow.
Data Preprocessing: Normalize pixel values between 0 and 1.
* Training: Train the model for approximately 20 epochs using an appropriate optimizer and loss function.
* Evaluation: Analyze the model's performance and identify potential issues (overfitting/underfitting).

3. Addressing Overfitting/Underfitting (if applicable):

* Data Augmentation: Implement suitable data augmentation techniques (e.g., rotation, flipping, zooming) to enhance model robustness and mitigate overfitting/underfitting.
* Retrain: Re-train the model on the augmented data for 20 epochs.
* Re-evaluate: Analyze the model's performance after augmentation.

4. Handling Class Imbalance:

* Analyze Class Distribution: Determine the class distribution in the training dataset, identifying underrepresented and overrepresented classes.
* Class Balancing: Utilize the Augmentor library to address class imbalances through techniques like oversampling of underrepresented classes or undersampling of overrepresented classes.

5. Final Model Development & Training:

* Build CNN: Design and implement a custom CNN architecture in TensorFlow.
* Data Preprocessing: Normalize pixel values between 0 and 1.
* Training: Train the model for approximately 30 epochs using an appropriate optimizer and loss function.
* Evaluation: Evaluate the final model's performance and analyze the results.

*** Note: 

This project may require significant computational resources. Consider utilizing Google Colab for model training.

This project focuses on building a custom CNN model and does not involve the use of pre-trained models or transfer learning techniques.

*** Disclaimer
This is a deep learning assignment and the model is not intended for real-world medical diagnosis. Always consult a qualified healthcare professional for any skin concerns.
