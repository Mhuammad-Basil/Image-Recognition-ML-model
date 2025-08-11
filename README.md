# Image-Recognition-ML-model
This project implements a deep learning model to distinguish between cat and dog images using transfer learning with the MobileNetV2 architecture. The model was developed in Google Colab using Keras and trained on a labeled dataset from Kaggle.
Approach:
MAde use of MobileNetV2 as a feature extractor to benefit from pre-trained ImageNet weights.
Applied data augmentation techniques (rotation, flipping, zooming) to improve generalization.
Fine-tuned the last few layers of MobileNetV2 for task-specific learning.
Used Adam optimizer and categorical cross-entropy loss for training.
Results:
Achieved high accuracy on both training and validation sets, with minimal overfitting.
Implemented on lightweight MobileNetV2 architecture, making it suitable for deployment on resource-constrained devices.
