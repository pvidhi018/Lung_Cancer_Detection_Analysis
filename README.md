# Lung Cancer Detection Analysis (Capstone Project)
![WhatsApp Image 2024-07-13 at 1 47 02 PM](https://github.com/user-attachments/assets/671e47da-65f7-4b43-84c5-7228cfd17e0e)

![WhatsApp Image 2024-07-13 at 1 47 54 PM](https://github.com/user-attachments/assets/88e32288-bb1a-439f-88f8-ca8ca0f18c51)

![WhatsApp Image 2024-07-13 at 1 48 10 PM](https://github.com/user-attachments/assets/f5c17266-2c6d-46a6-87a4-09805b3b9670)

Lung Cancer Detection Analysis Using CNN
Project Overview

This was my capstone project, where I worked on classifying lung scan images into three categories: Normal, Benign, and Malignant. The main goal was to build a model that could analyze an uploaded image and predict which category it belongs to.

Unlike projects that use numerical data in rows and columns, this project used images to train and test a machine learning model. I tried different approaches and used a Convolutional Neural Network (CNN) to learn patterns from the images and make predictions.

 Understanding the Three Categories

The dataset contained three types of lung images:

* Normal: No tumor is present in the image. If a person has symptoms, they may be caused by something other than a tumor.
* Benign: A tumor is present, but it is non-cancerous. This means the tumor is not cancer.
* Malignant: A tumor is present and is cancerous.

These categories helped the model learn the differences between the images and predict the most suitable category for an uploaded image.

 Project Objectives

* Work with a dataset containing lung images from three categories: Normal, Benign, and Malignant.
* Train and test machine learning models to classify the images.
* Use a CNN to identify patterns in the images and make predictions.
* Test the model using different images and check how often its predictions were correct.
* Connect the trained model to a web application so users could upload an image and view the predicted result.
* Create an interface where users could upload an image from their device and receive a classification result.

Tools and Technologies

* Python: Used for model development and the project backend.
* Convolutional Neural Network (CNN): Used to learn image patterns and classify lung images.
* Flask: Used to create the backend server and connect the trained model with the application interface.
* Tableau: Used to create the interface through which users could upload an image and view the result.

 How the Project Works

1. Image Dataset: The project uses lung images belonging to the Normal, Benign, and Malignant categories.
2. Model Training: I trained and tested different models and used a CNN for image classification.
3. Model Testing: I tested the model with different images and checked its predictions using a heatmap-based evaluation to understand how often the predictions were correct.
4. Flask Backend: The Flask server connects the trained CNN model to the application and processes the image for prediction.
5. User Interface: The interface allows users to upload an image from their device.
6. Prediction Result: After the image is processed, the application displays the predicted category: Normal, Benign, or Malignant.

 Model Performance

The CNN model achieved approximately 81% classification accuracy during testing.

I tested different images to see how well the model could identify the three categories. I also used a heatmap to help evaluate the model’s predictions and understand where it was classifying images correctly or incorrectly.

Although the model performed reasonably well for this project, there is still room for improvement through further testing, better data preparation, and additional model tuning.

 Application Features

* Upload a lung image directly from a device.
* Process the uploaded image using the trained CNN model.
* Display the predicted category: Normal, Benign, or Malignant.
* Connect the model to the application through a Flask backend.
* Provide a simple interface for viewing the classification result.

 What I Learned

Through this capstone project, I gained practical experience in working with image-based datasets, training and testing a CNN model, evaluating prediction results, and connecting a machine learning model to an application using Flask.

I also learned how the different parts of a machine learning project work together, from preparing the data and training the model to allowing a user to upload an image and receive a result.

Important Note

This project was developed for learning and experimentation. The model’s prediction is not a medical diagnosis and should not be used to determine whether someone has lung cancer. Actual medical images and health concerns must be evaluated by qualified healthcare professionals.

 Project Type

Capstone Project — Machine Learning and Image Classification
