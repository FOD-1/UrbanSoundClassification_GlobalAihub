# UrbanSoundClassification
This project aim to classify urban sound signals using convolutional neural network.
# Creating Spectrogram
In this section we first load the wav file and took their spectrogram and save them in the desired directory
# Preprocessing
1- we perform grayscale transformation, resizing and normalization by reading the images (spectrograms) sequentially.

2- we add images to a list in [image, label] format, with their labels.

3- We use this list to create the X_train, y_train, X_val, y_val, X_test, and y_test datasets.

4- we save these datasets in the desired directory.

# Model Preparation and Training
1- Prepare a CNN model.

2- Train the model using the data you have prepared.

3-Print the model's performance metrics, loss and accuracy graphs on the screen.

4- Do hyperparameter optimization based on the results you get.

