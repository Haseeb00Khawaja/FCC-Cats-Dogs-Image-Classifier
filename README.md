# FCC Cats vs Dogs Classifier – CNN with TensorFlow/Keras

📦 FCC-Cats-Dogs-Image-Classifier
A convolutional neural network (CNN) built with TensorFlow/Keras to classify images of cats and dogs. Completed as part of FreeCodeCamp’s Machine Learning with Python Certification.

🧠 Overview
This project demonstrates how to build and train a CNN to perform binary image classification. It includes data preprocessing, model architecture design, training, evaluation, and prediction steps.

📁 Dataset Structure
Organized for use with ImageDataGenerator.flow_from_directory():
bash
Copy
Edit
/train
    /cats
    /dogs
/validation
    /cats
    /dogs
/test
    (unlabeled images)

🧱 Model Summary
Convolutional Layers: Feature extraction
Pooling Layers: Downsampling
Dense Layers: Classification
Activation: Sigmoid (for binary output)

⚙️ Training
Optimizer: Adam
Loss Function: Binary Crossentropy
Metric: Accuracy
Includes optional data augmentation and dropout for regularization

📊 Output
Predictions on test images are visualized with labels and probabilities.

🔗 Resources
Keras Documentation
https://keras.io/ 

TensorFlow Image Classification Guide
https://www.tensorflow.org/tutorials/images/classification

freeCodeCamp Machine Learning with Python Certification
https://www.freecodecamp.org/learn/machine-learning-with-python/
