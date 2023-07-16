# Digit-Recognition
## Objective: 
To develop a CNN model for accurate image recognition and classification.

## Approach:
1. Data Preprocessing: Imported necessary libraries, including numpy, pandas, and matplotlib. Loaded the image dataset using pandas' read_csv() function.
2. Data Preparation: Separated the target labels (y_train) and input features (x_train) from the dataset. Reshaped the input features to match the CNN model requirements and normalized the pixel values.
3. Data Visualization: Utilized matplotlib to visualize a sample of images from the dataset along with their corresponding labels.
4. One-Hot Encoding: Applied one-hot encoding to convert categorical labels into numerical vectors using sklearn's OneHotEncoder.
5. Model Architecture: Created a CNN model using the Sequential class from Keras. Defined convolutional, pooling, and dense layers with activation functions to extract features and classify the images.
6. Model Training: Compiled the model using the Adam optimizer and categorical cross-entropy loss. Trained the model using the fit() function with specified callbacks for model checkpointing, early stopping, and learning rate reduction.
7. Performance Evaluation: Plotted the accuracy and loss curves during training using matplotlib to assess the model's performance.
8. Image Prediction: Displayed a sample of test images with their predicted labels using the trained model.

## Impact:
The project demonstrates the application of Convolutional Neural Networks (CNNs) for image recognition and classification tasks. By developing a CNN model and training it on a labeled dataset, the project aims to achieve high accuracy in identifying and classifying images. Such image recognition systems have extensive real-world applications, ranging from autonomous vehicles to medical imaging, enhancing object detection, and improving computer vision technology.

## Libraries Used:
1. numpy: For numerical operations and array manipulation.
2. pandas: For data handling and manipulation.
3. matplotlib: For data visualization and plotting.
4. keras: For building and training the CNN model.
5. sklearn: For one-hot encoding categorical labels.
