# Building an AI Chatbot using Prompts
### Medium Article: https://medium.com/@shrutiebony/building-an-ai-chatbot-and-predicting-house-prices-with-machine-learning-f52e890d5465
## Introduction

This project involves building an AI chatbot utilizing ChatGPT's code interpreter, Python, TensorFlow, and Matplotlib for visualization. Following the CRISP-DM framework (Cross Industry Standard Process for Data Mining), we will create a machine learning model to automatically predict house prices. This README provides an overview of the six phases of CRISP-DM as applied to this project.

## CRISP-DM Framework Phases

### 1. Business Understanding

The primary objective is to develop a machine learning model that can predict house prices accurately. The AI chatbot will assist users by processing data and making predictions based on trained models.

### 2. Data Understanding

In this phase, we explore the dataset to understand its structure, contents, and potential challenges.

#### Key Objectives:

Data Collection: Import and examine the dataset to familiarize ourselves with its structure.

Descriptive Statistics: Analyze the dataset's size, distribution, and identify any missing values.

Visualization: Generate samples to uncover patterns and challenges.

Quality Assessment: Detect and address missing, corrupt, or irrelevant data that could hinder model performance.

### 3. Data Preparation

Prepare the dataset for model training by performing essential pre-processing steps.

#### Key Steps:

Normalization: Scale features to a range between 0 and 1 to improve model performance.

Reshaping: Ensure the data is appropriately scaled, typically using a standard or normal scaler.

Train-Test Split: Divide the dataset into training and validation sets as required.

Data Augmentation (Optional): Use techniques like rotation, flipping, and zooming to artificially expand the dataset and enhance generalization.

### 4. Model Training

Using TensorFlow, we will train a Convolutional Neural Network (CNN) model optimized for the dataset.

#### Approach:

Define the CNN architecture.

Train the model using prepared data.

Optimize hyperparameters to enhance performance.

### 5. Model Evaluation

Evaluate the model’s performance and generalization ability on unseen data to ensure it meets project objectives.

#### Key Metrics:

Accuracy: Measure the percentage of correctly predicted house prices.

Confusion Matrix: Analyze classification results and identify areas of confusion.

Precision, Recall, and F1-Score: Assess false positives and negatives for deeper insights.

Loss and Accuracy Curves: Visualize model performance across training epochs.

### 6. Model Deployment

Deploy the trained model into a production environment for real-time or batch predictions.

#### Common Deployment Options:

Web Service: Serve the model via a REST API to handle input data and return predictions.

Mobile/Embedded Application: Export the model to formats like TensorFlow Lite for compatibility with mobile and edge devices.

Cloud Deployment: Use scalable cloud services such as AWS, Google Cloud, or Azure for deployment.

## Tools and Technologies

ChatGPT Code Interpreter: For AI-assisted coding and testing.

Python: The primary programming language for this project.

TensorFlow: For building and training the machine learning model.

Matplotlib: For data visualization.

## Project Setup

Clone the repository:

git clone <repository-url>

Install dependencies:

pip install -r requirements.txt

Run the chatbot interface:

python chatbot.py

## Future Improvements

Incorporate advanced data augmentation techniques.

Experiment with different neural network architectures.

Enable additional deployment options, such as integrating with mobile applications.

License

This project is licensed under the MIT License. See the LICENSE file for details.
