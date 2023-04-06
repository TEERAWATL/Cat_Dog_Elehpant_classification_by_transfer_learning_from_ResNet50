# Cat, Dog, and Elephant Classification by Transfer Learning from ResNet50

Classify cats, dogs, and elephants using transfer learning with the ResNet50 model.
## Description

This project utilizes the ResNet50 model as a backbone for classifying images of cats, dogs, and elephants. Transfer learning is used to build a custom model based on the ResNet50 architecture.

Usage
Run the main script to execute the project:
transfer_learning_from_ResNet50_to_CNN_classified_multicalss_cat_dog_elephant (1).ipynb

Dependencies
The project requires the following libraries:

numpy
matplotlib
tensorflow
Install the dependencies using the following command:

pip install numpy matplotlib tensorflow

Dataset Preparation
Collect and organize images of cats, dogs, and elephants into separate folders.
Use ImageDataGenerator from TensorFlow to apply data augmentation and preprocessing.
Split the dataset into training, validation, and testing sets.
Model Training
Load the pre-trained ResNet50 model from TensorFlow.
Create a custom model using the Sequential API from TensorFlow, including the ResNet50 backbone and additional layers.
Use EarlyStopping and ModelCheckpoint callbacks during training to monitor the model's performance and save the best weights.
Train the model using the training and validation sets.
Model Evaluation
Evaluate the trained model on the test set and visualize the classification results. You can use the decode_predictions function from the ResNet50 library to map the predicted class indices to their corresponding class labels.
