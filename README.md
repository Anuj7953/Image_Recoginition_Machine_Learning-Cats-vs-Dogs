🐾 Cat vs Dog Image Classifier
This project is a deep learning-based image classification system designed to differentiate between images of cats and dogs. It utilizes the MobileNetV2 architecture with transfer learning to achieve high accuracy while maintaining efficiency. The model processes an input image, resizes it to the required dimensions, applies preprocessing, and outputs a prediction indicating whether the image is of a cat or a dog.

The implementation is done in Python using the TensorFlow/Keras framework, and the training and testing were carried out in Google Colab for easy accessibility and GPU support. The model can handle .jpg and .png image formats and can be easily integrated into various applications requiring pet image classification.

The repository contains the complete notebook for running the classification process, including uploading an image, preprocessing it, making predictions, and displaying results. This makes it suitable for learning purposes, quick deployment, and further customization.

🎯 Project Objective
The primary objective of this project is to build a lightweight, accurate, and fast image classification model that can reliably identify whether an image contains a cat or a dog. This system is intended for use in educational projects, pet recognition tools, and AI-based image categorization applications.

🔄 Workflow
Model Loading – Pre-trained MobileNetV2 model is loaded for transfer learning.

Image Uploading – User uploads an image in .jpg or .png format.

Preprocessing – The image is resized to 224x224 pixels and preprocessed for the model.

Prediction – The model outputs a probability score to determine the class..

Result Display – The system displays whether the image is classified as a “Cat” or “Dog”
